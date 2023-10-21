# SQLi
# Introduction to SQL Injection
- SQL Injection is a web application **injection** vulnerability that occurs when an attacker inject malicious SQL statements into an application's input field.
- This occurs when a web application **does not properly validate** user input, allowing an attacker to inject SQL code/queries that can manipulate the database or gain access to sensitive information.
- For example, suppose a website has a login form that accepts a username and password. If the websites does not properly validate the user's input, an attacker could enter a malicious SQL statement into the username field that would allow them to bypass the login process and gain access to the website's database
- SQL Injection attacks can have serious consequences, including the theft of sensitive data, unauthorized access to sensitive system. and even full system compromise.
- Context Managemnet Systems(CMSs), as well as simple web pages, can connect to relational database such as MySQL, MSSQL,SQL Server,Oracle,PostgreSQL,and others.
- To interact with databases, entities such as systems operators, programmers, applications and web applications use the Structure Query Language(SQL).
#SQL Injection Impact
- Confidentiality - Since SQL databases generally hold sensitive data, loss of confidentiality is a frequent problem with SQL Injection vulnerabilites.
- Integrity - Just as it may be possible to read sensitive information, it is also possible to make changes or even delete this information with a SQL Injection attack.
- Authentication - If poor SQL commands are used to check user names and passwords, it may be possible to connect to a system as another user with no previous knowledge of the password
- Availabilty - SQL Injection attacks can affect the availabity of a web application and database and could take the website down due to loss/damage of data.
#SQL Injection Consequences
- Sensitive data exposure/ data breaches - SQL injection attack can result in unauthorized access to sensitive data stored in a database. Attacker may be able to view or steal confidential information, such as customer data, financial information, and intellectual property.
- Data manipulation - Attacker may be able to modify or delete data stored in a database, potentially causing data loss or corruption.
- Code execution - If a database user has administrative privilenges, an attacker can gain access to the target system using malicious code.
- Business disruption - Successful SQL Injection attacks can lead to business disruption, as organizations work to restore services and prevent futher attacks.
