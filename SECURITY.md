# Security Policy

## Reporting a Vulnerability

We take the security of Boston Open Dev's repository and infrastructure seriously. If you discover a security vulnerability, please report it responsibly using GitHub's **Private Vulnerability Reporting** feature.

1. **DO NOT** create a public GitHub issue to report vulnerabilities.
2. Use the **GitHub Security Advisories** feature to submit your report privately. For guidance, refer to GitHub's Documentation on Private Vulnerability Reporting.

All reports will be reviewed and triaged based on their severity by the project maintainers, led by Security Manager Sooraj Sathyanarayanan.

When submitting a report, include:
* A clear description of the vulnerability
* Steps to reproduce the issue (if applicable)
* The potential impact or risk of the vulnerability

## Response Process

* We aim to review reports as quickly as possible, typically within 5-7 business days
* High-severity issues will be prioritized and addressed as quickly as possible
* For medium- and low-severity issues, resolution timelines may vary depending on complexity and impact
* The reporter will receive updates throughout the process and be informed when the issue is resolved
* We request a 90-day period to respond and address vulnerabilities before any public disclosure

## What to Report

Please report any vulnerabilities that fall into the following categories:
* Cross-site scripting (XSS) vulnerabilities
* Exposed sensitive information within the repository or related infrastructure
* Issues with authentication or access control (if applicable)
* Problems with data handling or processing
* Any other security-related flaws directly affecting this repository

## Scope

The following is considered **In Scope**:
* This repository and its contents
* Deployment scripts, configuration files, and associated code within the repository
* Infrastructure directly managed by Boston Open Dev for this project

The following is considered **Out of Scope**:
* Third-party services linked from this repository
* Personal websites or projects of individual contributors
* Hypothetical attack scenarios
* Social engineering attempts

## Security Best Practices for Contributors

To maintain a secure repository, we recommend that all contributors:
1. Review all code and changes thoroughly before committing
2. Avoid committing sensitive information such as API keys, passwords, or tokens
3. Keep all dependencies up to date to mitigate risks from known vulnerabilities
4. Use secure protocols (e.g., HTTPS) when adding external resources or links

## Attribution

We support responsible disclosure and are happy to credit researchers who report valid vulnerabilities, provided they wish to be credited.

## Policy Updates

This policy may be updated periodically to reflect evolving security needs. All changes will be documented in the Git history of this file.

**Security Manager**: Sooraj Sathyanarayanan  
**Last Updated**: November 2024  
