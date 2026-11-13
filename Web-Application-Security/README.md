# Web Application Security Project

## Project Overview
For this project, I tested the OWASP Juice Shop web application to identify and understand common security vulnerabilities.

The aim was to investigate how these vulnerabilities work, understand their risks and recommend ways to prevent them.

## Tools and Technologies
- OWASP Juice Shop
- Burp Suite
- Browser Developer Tools
- HTTP Requests and Responses
- OWASP Top 10

## What I Did
I investigated the application using manual testing and Burp Suite. I completed five security challenges.

### 1. DOM Cross-Site Scripting (XSS)
I tested user input fields and demonstrated how JavaScript could execute in the browser because of insufficient input handling.

### 2. Password Strength
I investigated weak password security and demonstrated how password guessing could allow access to an administrator account.

### 3. Reset Jim's Password
I tested the password recovery feature and identified weaknesses in security-question-based authentication.

### 4. Login Bender
I investigated an authentication bypass vulnerability that allowed access to a user account without the correct credentials.

### 5. Forged Review
I used Burp Suite to intercept and modify an HTTP request, demonstrating how weak server-side access controls allowed a product review to be submitted under another user's identity.

## Testing and Results
- Completed five OWASP Juice Shop security challenges.
- Demonstrated DOM-based XSS.
- Identified weak authentication and password recovery controls.
- Demonstrated an authentication bypass.
- Confirmed broken access control in the product review feature.
- Documented the vulnerabilities and recommended security improvements.

## Security Recommendations
- Apply appropriate input handling and output encoding.
- Use stronger authentication and password policies.
- Implement rate limiting and multi-factor authentication.
- Verify user identity on the server side.
- Improve access control and session management.

## Skills Developed
- Web application security testing
- Burp Suite
- HTTP request analysis
- Vulnerability identification
- Authentication and access control testing
- Security reporting

## Project Evidence
My project report contains screenshots of completed OWASP Juice Shop challenges, testing results and vulnerability analysis.

A reviewed version of the report will be added after sensitive session information has been removed.
