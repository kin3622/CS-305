# CS-305

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

  Artemis Financial is a consulting company that develops individualized financial plans involving savings, retirement, investments, and insurance. The company wanted to modernize its operations and use effective software security to protect its RESTful web API from external threats. Global Rain was asked to assess the   application for security vulnerabilities and recommend improvements.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

  I identified areas that needed additional security and added a SHA-256 checksum using Java's MessageDigest class. Secure coding helps protect sensitive data, prevent unauthorized access, maintain customer trust, and reduce the risk of security incidents.

Which part of the vulnerability assessment was challenging or helpful to you?

  The most challenging part was understanding the vulnerabilities found by Dependency-Check. It was helpful because it showed me how vulnerability scanners can identify known security issues.  
  
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

  I added multiple layers of security by using a SHA-256 checksum for data integrity. I also updated the application to use HTTPS for secure communication and a certificate with a keystore for a secure connection. I also used Dependency-Check and manual testing. In the future, I would use vulnerability checks, static     analysis, code reviews, and secure coding practices to help reduce vulnerabilities.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

  I compiled and ran the refactored application, verified that it started on HTTPS port 8443, and tested the hash endpoint. I also used Dependency-Check and manually reviewed the code to check for syntactical, logical, and security issues after refactoring.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

  Some useful tools I used was Java's MessageDigest, SHA-256, Java Keytool, and Dependency-Check. These tools helped me understand how to identify and address security concerns in an application.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

  This project shows my knowledge with Java, Spring Boot, SHA-256 checksums, HTTPS, certificates, keystores, vulnerability scanning, and software testing. I could use it to show employers how I would approach implementing and testing security improvements.
