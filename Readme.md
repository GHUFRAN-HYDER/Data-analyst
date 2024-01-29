# PDF Data Extraction and Excel Formatting

This project focuses on extracting specific columns from a PDF document containing tabular data and formatting the extracted data into an Excel file using Python. The script utilizes the `tabula` library for PDF parsing, `pandas` for data manipulation, and `openpyxl` for Excel formatting.

## Installation Instructions

### 1. Install Java:

If you haven't already, download and install the Java Runtime Environment (JRE) or the Java Development Kit (JDK) from [Oracle's Java Downloads](https://www.oracle.com/java/technologies/downloads/).

Ensure you choose the version compatible with your operating system and architecture (32-bit or 64-bit).

### 2. Set the JAVA_HOME Environment Variable:

**For Windows:**

1. Right-click on "This PC" or "My Computer" and select "Properties."
2. Click on "Advanced system settings" and then "Environment Variables."
3. Under "System variables," click "New."
4. Enter "JAVA_HOME" as the variable name and the path to your Java installation directory (e.g., C:\Program Files\Java\jdk-19.0.1) as the value.
5. Click "OK" on all open windows.

### 3. Python Version Compatibility:

This project is compatible with Python 3.8 and above.

### 4. Install Python Dependencies:

```bash
pip install -r requirements.txt


Code Overview
The Python script (data_extraction.py) uses tabula for PDF parsing, pandas for data manipulation, and openpyxl for Excel formatting. The script extracts specific columns from a PDF document, removes bold formatting, and saves the data to an Excel file.

Optimization and Improvements
Utilized list comprehension for concise code.
Directly removed bold formatting for the first row in the Excel file.
Ensured consistent code formatting and indentation.
