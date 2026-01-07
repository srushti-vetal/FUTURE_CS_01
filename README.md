FUTURE_CS_01

Cyber Security Internship – Task 1  
 Web Application Security Testing

This repository contains my submission for Task 1 of the Cyber Security Internship.  
The aim of this task is to understand basic web application security testing by working on a vulnerable application.



 Objective

The main objective of this task is to test a web application and identify common security issues such as SQL Injection, Cross-Site Scripting (XSS), and security misconfigurations.



 Tools Used

 OWASP Juice Shop  
 OWASP ZAP  
 Docker  
 Web Browser  



 Testing Performed

 SQL Injection
 The login page was tested using SQL Injection payloads.
 The application detected the malicious input and blocked the request.
 This shows how improper input handling can lead to authentication issues.

 Cross-Site Scripting (XSS)
 An XSS payload was tested through the search functionality.
 The script was not executed, which indicates that the input was sanitized.


 OWASP ZAP Scan

An automated scan was performed using OWASP ZAP on the application running locally at:

http://localhost:3000

The scan reported the following issues:
 Content Security Policy (CSP) Header Not Set  
 Information Disclosure  
Cross-Domain Misconfiguration  

These findings mainly relate to missing security headers and configuration weaknesses.


Repository Contents

 Report folder containing the security testing report  
 Screenshots folder containing evidence of testing and scan results  



 Conclusion

This task helped me understand how web application vulnerabilities are tested using both manual methods and automated tools. It also highlighted the importance of secure coding and proper security configurations.



Task 1 successfully completed.

