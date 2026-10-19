# CS 305 – Software Security Portfolio

## Artemis Financial: Practices for Secure Software

### 1. Client and Software Requirements
Artemis Financial is a financial consulting company that provides individualized financial planning services. The company needed to improve the security of its software application to protect sensitive financial information, strengthen data integrity, and secure communications. My role was to implement security improvements and evaluate the application for vulnerabilities.

### 2. Identifying Vulnerabilities and the Importance of Secure Coding
I used OWASP Dependency-Check to identify vulnerabilities in the application's third-party dependencies. The scan reported 16 vulnerable dependencies and 295 vulnerabilities, although a Sonatype OSS Index authentication error limited the completeness of the analysis. Secure coding is essential because it protects sensitive information, reduces security risks, and helps organizations maintain customer trust.

### 3. Challenges and Lessons Learned
One challenging aspect was interpreting dependency scan findings and understanding how third-party libraries can introduce security risks. The assessment helped me understand the importance of reviewing dependencies, prioritizing vulnerabilities, and recognizing limitations in security scanning tools.

### 4. Increasing Layers of Security
I implemented SHA-256 hashing using Java's MessageDigest class to generate checksums for data integrity verification. I also generated a self-signed certificate using Java Keytool and configured HTTPS on port 8443. In future projects, I would use OWASP Dependency-Check, vulnerability databases, and secure coding guidelines to select appropriate mitigation strategies.

### 5. Functional and Security Testing
After implementing the security changes, I tested the Spring Boot application and confirmed that the /hash endpoint returned an HTTP 200 response with the expected SHA-256 checksum. I also ran dependency scanning to identify remaining security concerns. Because vulnerabilities remained, additional dependency remediation and repeated security testing would be necessary before production deployment.

### 6. Tools, Resources, and Coding Practices
I used Java, Spring Boot, Maven, Java Keytool, SHA-256, HTTPS, PKCS12 keystores, and OWASP Dependency-Check. These tools helped me develop skills in cryptographic hashing, secure communications, dependency analysis, application testing, and technical documentation.

### 7. Skills Demonstrated to Future Employers
This project demonstrates my ability to implement application security improvements, configure HTTPS, generate cryptographic checksums, conduct vulnerability assessments, and validate application functionality. My completed Artemis Financial Practices for Secure Software Report provides evidence of my technical problem-solving, cybersecurity knowledge, and secure software development skills.

## Portfolio Artifact
Artemis Financial – Practices for Secure Software Report (Project Two).
