# SQLi with Burp Suite, WebGoat
From: [Understanding SQL Injection, Identification and Prevention](https://www.varonis.com/blog/sql-injection-identification-and-prevention-part-1)

SQL (Standardized Query Language- pronounced "SEE-quil") is a programming language, often used for databases. Data is inserted, fitered, and retrieved using this language. 

  * SQL injection attacks can:
    * extract user data
    * discover user credentials
    * reset user credentials
    * launch other attacks on the network.

SQL has largely unchanged since the 1970s.


## Questions for further understanding
1. What is SQL injection?
  * Sending queries to a DB that command it to do something other than intended by design.
2. Can you give an example of how a hacker could use SQL injection to gain unauthorized access?
  * send a request directly to the database to return usernames or password resets
  * SQL string concatenation
3. What are some ways to prevent SQL injection attacks on a web server? 
  * Input Sanitization 
