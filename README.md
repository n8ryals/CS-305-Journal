# CS-305-Journal
This repository contains my Project Two – Practices for Secure Software Report and the refactored code for Artemis Financial’s application. The project demonstrates how I added encryption, secure communication, and vulnerability testing to improve the security of a financial services application.

**Client and Requirements**
The client was Artemis Financial, described as a consulting company that provides personalized financial plans for customers. They wanted to modernize their software and protect sensitive client data. Specifically, they needed file verification with checksums and secure HTTPS communication added to their web application.

**What I Did Well**
I identified the security vulnerabilities in the base code and added new layers of protection, such implementing a checksum with SHA-256 and switching from HTTP to HTTPS. Secure coding is important because it protects sensitive customer information and helps a company maintain trust with its users. Strong software security adds value by preventing breaches, reduces risks, and helps comply with laws and regulations.

**Challenging and Helpful Parts**
The most challenging part for me was generating the self-signed SSL certificate. It was helpful to use the OWASP Dependency-Check plugin, since it gave me more confidence in how secure my code was.

**Adding Layers of Security**
I increased layers of security by adding HTTPS to encrypt communication, SHA-256 hashing, input escaping to manage error handling. For future projects, I would continue to use tools like the OWASP Dependency-Check as well as static code analysis.

**Ensuring Functionality and Security**
I made sure the code worked by running it locally, testing the /hash and /hash/verify endpoints in a browser, and confirming that HTTPS was active. After refactoring the code, I ran OWASP Dependency-Check to verify that I did not introduce any new vulnerabilities.

**Resources and Tools**
I used Spring Boot, Java Keytool, HTTPS configuration, SHA-256, and the OWASP Dependency-Check Maven plugin. These tools will also be useful in future projects because they are frequently used in real-world circumstances, so it is helpful to have a solid foundation in understanding these them.

**Portfolio Value**
Thanks to this project, I can show future employers my code refactoring skills and my ability to implement security best practices. The Practices for Secure Software Report showcases my ability to apply industry standards, integrate testing tools, and add encryption.
