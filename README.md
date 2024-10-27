# SoftwareSecurity
This Github is to practice software security

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?   
  Artemis Financial, a financial consulting firm, required updates to secure its web application for client data protection   and modernized operational practices.The company needed secure data transfer and a file verification mechanism to prevent unauthorized access or tampering.
  
What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
  When assessing vulnerabilities, I identified areas for data integrity and secure communications. Implementing HTTPS with SSL/TLS and SHA-256 checksums for verification addressed these needs well. Coding securely is vital as it minimizes data breach risks, protects client information, and ensures legal compliance. This enhances Artemis Financial’s reputation and operational resilience.

Which part of the vulnerability assessment was challenging or helpful to you?
  Identifying false positives from the dependency checks was challenging because dependency scanners, like OWASP Dependency-Check, sometimes flag non-critical vulnerabilities or issues in libraries that don’t directly affect the application. This required a careful review of flagged vulnerabilities to determine which posed actual risks and which could be safely ignored or suppressed. Learning to distinguish true vulnerabilities from false positives is essential, as it prevents unnecessary remediation efforts while ensuring focus on genuine security threats. This experience has underscored the importance of thorough analysis in dependency management and vulnerability assessment.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  I layered security with SSL/TLS encryption for secure data transfer, checksum-based data verification for integrity, and OWASP Dependency-Check for identifying library vulnerabilities. For future vulnerability assessments, I would rely on automated tools like SAST (Static Application Security Testing) for code analysis and use CVE databases to guide vulnerability prioritization and mitigation.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  After refactoring, I tested the application to verify that all changes, including secure communications and data integrity, were functional. Running OWASP Dependency-Check after refactoring confirmed no new vulnerabilities were introduced.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  Tools like OWASP Dependency-Check, Java Keytool, and SHA-256 hashing were effective in this assignment and will be valuable for future tasks. Following best practices for secure coding, such as input validation and dependency scanning, proved beneficial. For future employers, I would highlight my ability to identify and address security vulnerabilities, implement encryption and data verification techniques, and ensure compliance with secure coding practices. This project demonstrates my skills in creating secure, client-centered applications.
