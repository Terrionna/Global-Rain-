# Global-Rain-

Artemis Financial is a consulting company that creates personalized financial plans for savings, retirement, investments, and insurance. The company wanted to modernize its operations and secure client data transfers by adding file verification to its web application.

When reviewing the code, I identified vulnerabilities and resolved them using SHA-256 checksums, SSL encryption, and stronger error handling. Secure coding is important because it protects sensitive financial data, builds customer trust, ensures compliance, and reduces the risk of costly breaches.

The most challenging part of the vulnerability assessment was configuring HTTPS with self-signed certificates and setting up SSL. This was helpful for understanding how security layers work together to protect an application.

I increased security by adding encryption, file verification, and better error handling. In the future, I would use OWASP Dependency Check and manual reviews to identify vulnerabilities and apply layered defenses.

I confirmed the application was functional and secure by testing after each change, checking HTTPS endpoints, and running dependency scans to make sure no new vulnerabilities were introduced.

The main tools and practices I used were Java’s MessageDigest class, Spring Boot security configurations, Keytool for certificates, and OWASP guidelines. These will be useful in future projects.

From this assignment, I could show future employers my ability to assess vulnerabilities, implement encryption, configure secure communication, and follow secure coding best practices in financial applications.
