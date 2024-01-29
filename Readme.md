PDF Data Extraction and Excel Formatting
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
bash
Copy code
pip install -r requirements.txt
Usage Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/pdf-data-extraction.git
Install Python dependencies:

bash
Copy code
pip install -r requirements.txt
Run the script:

bash
Copy code
python data_extraction.py
Check the console for successful execution and find the extracted data in extracted_data.xlsx.

Code Overview
The Python script (data_extraction.py) uses tabula for PDF parsing, pandas for data manipulation, and openpyxl for Excel formatting. The script extracts specific columns from a PDF document, removes bold formatting, and saves the data to an Excel file.

Optimization and Improvements
Utilized list comprehension for concise
Ensure that you paste it into your README.md file as plain text, and the Markdown formatting should be preserved.
