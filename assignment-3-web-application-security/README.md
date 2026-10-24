Assignment 3: Attack and Defend Web Applications

Overview

This project focused on testing common web application vulnerabilities and implementing defensive controls using ModSecurity and the OWASP Core Rule Set (CRS).

Objectives

* Demonstrate SQL injection and cross-site scripting (XSS) in a controlled lab.
* Configure a Web Application Firewall (WAF).
* Validate whether the WAF blocks tested malicious requests.
* Collect screenshots and log evidence.
* Document security findings and recommended improvements.

Tools Used

* Kali Linux
* Docker
* Damn Vulnerable Web Application (DVWA)
* ModSecurity
* OWASP Core Rule Set (CRS)
* Apache

Methodology

1. Deployed DVWA in a Docker container.
2. Tested SQL injection and XSS with the application’s security level set to low.
3. Deployed a ModSecurity WAF in front of DVWA.
4. Created a custom ModSecurity rule file.
5. Checked the Apache configuration and confirmed that the syntax check returned Syntax OK.
6. Repeated the SQL injection and XSS tests through the WAF.
7. Observed blocked requests and reviewed available logs.

Results

The initial SQL injection test returned multiple user records, and the XSS test triggered a browser popup. After configuring the WAF, both tested attack types were blocked during re-testing.

Screenshots and relevant log excerpts will be added as supporting evidence.

Defensive Measures

* Use parameterized queries to prevent SQL injection.
* Apply context-aware output encoding to mitigate XSS.
* Keep the WAF rules and application software updated.
* Review WAF logs for suspicious activity and false positives.
* Perform additional testing to confirm protection without disrupting legitimate requests.

Lessons Learned

This exercise demonstrated the importance of validating security controls through repeat testing. It also provided practical experience with Docker, ModSecurity configuration, custom rules, and web application defense.

Scope

All attack simulations were performed against an intentionally vulnerable application in a controlled educational lab environment.