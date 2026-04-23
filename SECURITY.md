# Security Policy

- Supported Versions

We currently provide security updates for the latest stable version only.

| Version | Supported |
|--------|----------|
| Latest (main) | Yes |



- Reporting a Vulnerability

If you discover a security vulnerability, please report it responsibly.

- How to Report

- Open a **GitHub Security Advisory** (preferred)
- Or email: security@example.com *(maintainers should update this)*

- Please **do not create public issues** for security vulnerabilities.



- Scope

This project may be affected by security issues related to:

- Unsafe handling of user or external input  
- Injection vulnerabilities (XSS, HTML injection, etc.)  
- Misuse of configuration data in UI rendering  
- Third-party library integrations  



- Example Risk

Improper handling of configuration values can lead to issues like:

js
flatpickr(element, {
  nextArrow: config.nextArrow
});
