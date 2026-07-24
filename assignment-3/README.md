# Assignment 3 - Securing Software

[Back to main README](../README.md)

## Topics Covered

Phishing, Code Injection, Cross-Site Scripting (XSS) - Reflected and Stored, Character Escapes, SQL Injection, Prepared Statements, Command Injection, `system`, `eval`, Developer Tools, Client-Side Validation, Server-Side Validation, Cross-Site Request Forgery (CSRF), GET, POST, OWASP, Arbitrary Code Execution (ACE), Remote Code Execution (RCE), Buffer Overflow, Stack Overflow, Cracking, Reverse Engineering, Malware Analysis, Open-Source vs Closed-Source Software, App Stores, Package Managers, Operating Systems, Bug Bounty Programs, CVE, CVSS, EPSS, KEV.

## Summary

This assignment examines vulnerabilities introduced at the software and application level. It covers injection-based attacks, including SQL injection, command injection, and cross-site scripting, along with the input validation and prepared statement techniques used to prevent them. It also introduces CSRF as a distinct attack vector, buffer and stack overflows as memory-level exploits, and the standardized frameworks (OWASP, CVE, CVSS, EPSS, KEV) used to classify and prioritize vulnerabilities.

## Key Takeaways

- Client-side validation improves user experience but provides no real security; all validation must be enforced server-side.
- Prepared statements neutralize SQL injection by separating query logic from user-supplied data.
- Reflected and stored XSS differ in persistence and delivery, but both stem from insufficient output encoding of user input.
- CSRF exploits an authenticated session without needing to steal credentials, making token-based protections necessary.
- CVE, CVSS, EPSS, and KEV together form a practical pipeline for identifying, scoring, and prioritizing which vulnerabilities to remediate first.

## Status

Project complete.
