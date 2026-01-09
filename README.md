# AUTOMATED-REPORT-GENERATION 

COMPANY NAME: CODTECH IT SOLUTIONS PRIVATE LIMITED

NAME: BHAVANA S

INTERN ID: CTIS0245

DOMAIN: PYTHON PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

*AUTOMED REPORT GENRATION*:

This project demonstrates a simple but powerful Automated Report Generator using Python and Flask. The goal of the system is to read information from a dataset and convert it into a downloadable PDF report that is created dynamically. This type of automation is important in modern data-driven environments, where manual reporting consumes a lot of time and effort. The project shows how Python libraries and web technologies can work together to make reporting faster, easier, and more reliable.

The application uses Flask, a lightweight Python web framework, to build the backend. Flask provides routing, server execution, and page rendering. It enables a user-friendly interface where users can click one button in the browser and get the required output. The homepage is created using HTML and CSS, which are essential web technologies for creating the user interface. HTML structures the webpage content, and CSS styles it to make the design more attractive and easier to interact with.

The data for the report is taken from a CSV file named student.csv. This file contains student names and their marks in various subjects. To load and read this dataset, the project uses Pandas, a popular Python data analysis library. Pandas allows the program to easily calculate values such as number of students, list of columns, or any analytical summary required. Instead of manually scanning spreadsheets, Pandas extracts information programmatically.

After reading the data, the report is generated in PDF format using ReportLab, a Python library for document creation. ReportLab allows drawing text, adding headings, and presenting calculated results neatly inside a downloadable file. When the user clicks the “Generate Report” button, Flask calls a function that loads the CSV, analyzes it, writes the calculated summary into a PDF, and automatically sends it to the browser as a downloadable file.

The primary source code for this project is contained in app.py, which includes Flask routes, CSV loading logic, and PDF generation commands. The HTML page is stored inside a templates folder as index.html, following Flask’s project structure. The student data is stored locally in the same folder as the application, making it easy to replace, edit, or expand.

This project highlights several advantages. First, it automates reporting, saving significant time. Second, it reduces errors because the computer handles calculations instead of humans. Third, it creates professional-looking documents that can be shared or printed. It also allows future expansion to include graphs, multiple datasets, user uploads, or even a database connection.

In summary, this project successfully combines data handling, web programming, and PDF generation using essential programming tools. The main technologies used are Flask (webserver), Pandas (data analysis), ReportLab (PDF creation), HTML/CSS (frontend), and a CSV file (data source). Together, they form a complete automated system capable of reading real-world data and converting it into a formatted report with just one click.

*OUTPUT*:

<img width="1762" height="865" alt="Image" src="https://github.com/user-attachments/assets/ee499667-6ace-41c2-b4b9-11dee4690191" />

<img width="1848" height="876" alt="Image" src="https://github.com/user-attachments/assets/b9b73a1f-4579-43a7-9711-43b5d1d2b3bb" />

