# ElevateIntern_Project_2
Web Application Vulnerability Scanner

Description:
A Python-based tool that scans websites for common security vulnerabilities like:
Cross-Site Scripting (XSS)
SQL Injection (SQLi)

It includes a simple Flask-based web interface where users can input a URL and receive vulnerability results.

Tools Used:
Python 3
Flask
Requests
BeautifulSoup4

How to Run Web Scanner:
1. Install Required Libraries
   In the web_scanner/ folder, open terminal and run:
   cd web_scanner
   pip install -r requirements.txt

2. Launch the Test Server
   Navigate to the folder containing app.py.
   Start the Flask server:
   python app.py
   
3. Confirm it's running at:
   http://127.0.0.1:5000

4. Visit test pages manually to verify:
   XSS: http://127.0.0.1:5000/xss
   SQLi: http://127.0.0.1:5000/sqli

5.Launch the Scanner Application
  Open a new terminal.
  Navigate to the web_scanner/ folder.
  Start the scanner:
  python app.py
  
6. Open the scanner interface in your browser:
   http://127.0.0.1:5000
   This UI allows you to target URL for scanning

7. Perform the Scan:
   In the Input field, Enter-
   http://127.0.0.1:5000/xss

8. Click Scan, If the scanner detects a vulnerability, it will display:
   XSS found at http://127.0.0.1:5000/xss

9. Repeat the same for SQLi:
    http://127.0.0.1:5000/sqli

10. Click Scan, If the scanner detects a vulnerability, it will display:
    SQL Injection found at http://127.0.0.1:5000/sqli


This project is built for educational purposes only. 
Do not use any part of this code on real systems or websites without proper authorization. 
Unauthorized vulnerability scanning may be illegal.
