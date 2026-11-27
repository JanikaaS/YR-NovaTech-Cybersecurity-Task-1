Cyber Security Fundamentals & Security Assessment

Internship Task 1 – YR NovaTech

Project Overview

This project involves performing a basic security assessment of OWASP Juice Shop, an intentionally vulnerable web application used for cybersecurity learning and practice.

Objective

- Understand basic cybersecurity concepts.
- Perform a security assessment on a safe test application.
- Identify common security risks.
- Document findings and provide recommendations.

Tools Used

- OWASP Juice Shop
- Docker Desktop
- Google Chrome Developer Tools
- Windows 11

Assessment Activities

1. Application page inspection.
2. HTTP security header inspection.
3. Network traffic inspection.
4. API response inspection.
5. Basic input validation testing.
6. Registration and password policy assessment.

Key Findings

- Content-Security-Policy header was not observed.
- Permissions-Policy header was not observed.
- Password minimum length was 5 characters.
- Uppercase letters, numbers and special characters were not required.
- Wildcard CORS configuration was observed and requires further review.

Recommendations

- Implement an appropriate Content-Security-Policy.
- Improve password policy.
- Configure Permissions-Policy.
- Review CORS settings.

Evidence

Screenshots and the final security assessment report are included in this repository.

Disclaimer

This assessment was conducted on a locally hosted OWASP Juice Shop training application for educational purposes only.
