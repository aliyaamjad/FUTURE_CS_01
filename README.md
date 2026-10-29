
#FUTURE_CS_01

Cyber Security Internship — Task 1: Vulnerability Assessment Report

Project Overview

This project documents a preliminary, passive review of the OWASP Juice Shop web application as part of the Future Interns Cyber Security Internship.

Assessment Target: "OWASP Juice Shop" (https://juice-shop.github.io/)

Assessment Type: preliminary, passive browser review.

Assessment Date: 23 October 2026

Target Limitation: The project information page was accessible during the review. The shopping application previously displayed its welcome, catalogue, registration, and login pages, but a later visit returned a Heroku application error. The exact application URL needs to be verified before further assessment.

Methodology

The review was conducted using a mobile web browser and publicly available project information. Screenshots document the welcome page, product catalogue, registration page, and login page observed during earlier visits. A subsequent attempt to access the application returned an application error. No active vulnerability testing, port scanning, or automated security scanning was performed during this preliminary review.

Findings Summary

The report documents three informational observations:

1. Project Information Page
2. Homepage Accessibility
3. Challenges Information Page

These observations do not independently confirm security vulnerabilities.

Recommendations

- Review authentication and access-control protections during authorized testing.
- Check secure handling of sensitive information.
- Review input validation and output encoding.
- Review security-related HTTP headers.
- Document any verified issues with reproducible evidence.

Limitations

This is a preliminary passive assessment. It does not establish the absence or presence of vulnerabilities beyond the observations documented in the report. Further checks require appropriate authorization and supporting evidence.

Project Files

- "Vulnerability Assessment Report" (vulnerability-assessment-report.md)
- "Evidence Folder" (evidence/)

Evidence

Four browser screenshots are stored in the "evidence" folder:

- Evidence 1 — Welcome
- Evidence 2 — Product Catalogue
- Evidence 3 — Registration
- Evidence 4 — Login

References

- "OWASP" (https://owasp.org/)
- "OWASP Juice Shop Project" (https://owasp.org/www-project-juice-shop/)
- "OWASP Juice Shop Companion Guide" (https://pwning.owasp-juice.shop/)

---

This repository was prepared for the Future Interns Cyber Security Internship, Task 1.
