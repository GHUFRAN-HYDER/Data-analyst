
Project Title: PDF Data Extraction and Excel Formatting
This project focuses on extracting specific columns from a PDF document containing tabular data and formatting the extracted data into an Excel file using Python. The script utilizes the tabula library for PDF parsing, pandas for data manipulation, and openpyxl for Excel formatting.

Installation Instructions
1. Install Java:
If you haven't already, download and install the Java Runtime Environment (JRE) or the Java Development Kit (JDK) from Oracle's Java Downloads.

Ensure you choose the version compatible with your operating system and architecture (32-bit or 64-bit).

2. Set the JAVA_HOME Environment Variable:
For Windows:

Right-click on "This PC" or "My Computer" and select "Properties."
Click on "Advanced system settings" and then "Environment Variables."
Under "System variables," click "New."
Enter "JAVA_HOME" as the variable name and the path to your Java installation directory (e.g., C:\Program Files\Java\jdk-19.0.1) as the value.
Click "OK" on all open windows.

3. Python Version Compatibility:
This project is compatible with Python 3.8 and above.

4. Install Python Dependencies:

pip install -r requirements.txt

Run the script:

python dat.py

Check the console for successful execution and find the extracted data in extracted_data.xlsx.


Optimization and Improvements

Utilized list comprehension for concise code.
Directly removed bold formatting for the first row in the Excel file.
Ensured consistent code formatting and indentation.

Issues and Contributions
If you encounter any issues or have suggestions for improvement, please open an issue.

Note: Ensure that you have Python 3.8 or above installed on your machine before running the script.