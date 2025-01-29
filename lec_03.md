# Lecture 3

## SQL Injection

* A SQL injection attack consists of insertion or "injection" of a SQL query via **the input** data from the client to the application
* A successful SQL injection expoloit can read sensitive data from the database, modify database data, execute administration operations on the database, recover the content of a file present on the DBMS file system

* SQL injection is mostly known as an attack vector for websites but can be used to attack any type of SQL database
* The Open Web Application Security Project (OWASP) ranks **Injection** as the #1 web security risk

### SQLi Detection

* Source Code Review (cost/imperfect/doesn't scale)
* Source Code Analysis Tools (Free vs Paid)
* Dynamic Analysis Tools (e.g., sqlmap)

### SQLi Remediation

* Use of Prepared Statements
  * Define all SQL code and pass in each parameter to the query later
  * Allows DB to distingusih between code and data regardless of what input is supplied 
* Use of Stored Procedures
  * A stored procedure is defiend and stored in the database itself, and then called from the application 
* Whitelist Input Validation
  * Make sure unvalidated user input doesn't end up in the query
  * Names of tables or columns should come from the code and not from user parameters 
* Escaping All User Supplied Input
  * Escape user input before putting it in a query
 
### Cross-Site Scripting (XSS)

* Cross-Site Scripting (XSS) is a web-based application performed on vulnerable web applications
* Attackeds embed malicious JavaScript code in a page that gets executed on the client-side (in the user's web browser) rather than on the server side
* In XSS attacks, the **victim is the user** and not the application

* Attackers can display arbitrary content in a victim's user browser
* Attackers can execute arbitrary commands in a victim's user browser
* Attackers can exfiltrate sensitive information from the victim's machines

### Cross Site Scriptime Remediation

& --> &amp
< --> &lt
> --> &gt
" --> &quot
' --> &#x27
/ --> &#x2F
