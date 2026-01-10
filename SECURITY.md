# Security Policy

## Supported Versions

We provide security updates for the following versions of the project:

| Version | Supported | Notes |
| ------- | --------- | ----- |
| Latest release (main branch) | ✔️ | Actively supported |
| Previous minor release | ✔️ | Security fixes only |
| Older versions | ❌ | Please upgrade to a supported version |

---

## Reporting a Vulnerability

We take security issues seriously and appreciate responsible disclosure.

If you discover a vulnerability, please **do not open a public GitHub issue**. Instead, report it privately using one of the following methods:

- **GitHub Security Advisories**  
  Go to the repository’s **Security → Advisories → Report a vulnerability** and submit details there.

- **Email**  
  `peter.ritchie@outlook.com`  

Please include:

- A clear description of the issue  
- Steps to reproduce  
- Potential impact  
- Any suggested fixes or mitigations

We aim to acknowledge reports within **48 hours** and provide a
resolution timeline within **5 business days**.

---

## Scope

This security policy covers:

- The project’s source code  
- Distributed NuGet packages  
- Configuration guidance provided in documentation  
- Build and deployment scripts included in the repo  

It does **not** cover:

- Third‑party dependencies  
- User‑specific deployment environments  
- Forks or unofficial builds  

---

## Security Best Practices for Users

To keep your applications secure when using this project:

- Always use the **latest stable version** of the NuGet package  
- Enable **.NET security features** such as:
  - Nullable reference types  
  - Code analysis (CA rules)  
  - HTTPS enforcement  
- Keep your .NET runtime and OS patched  
- Review configuration examples before deploying to production  

---

## Handling of Reported Vulnerabilities

When a vulnerability is confirmed:

1. We create a private GitHub Security Advisory  
2. A fix is developed and reviewed  
3. A patched release is published  
4. The advisory is made public with CVE details (if applicable)  

We follow responsible disclosure practices and will coordinate publication with the reporter.
