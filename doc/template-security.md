<!-- 
TEMPLATE: Security Policy
VERSION: 1.0.0
UPDATED: 2025-08-15
AUTHOR: DePalma Workwear Limited

INSTRUCTIONS:
1. Save as "SECURITY.md" in repository root
2. Update contact information and timelines
3. GitHub will display this in the Security tab
4. Remove these HTML comments before committing
-->

# Security Policy

## 🔒 Reporting Security Vulnerabilities

We take the security of [Project Name] seriously. If you believe you have found a security vulnerability, please report it to us as described below.

## Supported Versions

We release patches for security vulnerabilities for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| [1.x.x] | :white_check_mark: |
| [0.x.x] | :x:                |

## Reporting a Vulnerability

**⚠️ Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them via one of the following methods:

### Option 1: Email
Send an email to **[security@example.com]** with:
- Type of issue (e.g., buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the issue
- Location of affected source code (tag/branch/commit or direct URL)
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit it

### Option 2: GitHub Security Advisory
[Create a security advisory](https://github.com/[organization]/[repository]/security/advisories/new) in this repository.

## Response Timeline

- **Initial Response**: Within 48 hours
- **Status Update**: Within 5 business days
- **Resolution Target**: Based on severity
  - Critical: 7 days
  - High: 14 days
  - Medium: 30 days
  - Low: 60 days

## What to Expect

1. **Acknowledgment**: We'll acknowledge receipt of your report
2. **Investigation**: We'll investigate and validate the issue
3. **Communication**: We'll keep you informed of our progress
4. **Resolution**: We'll work on a fix and coordinate disclosure
5. **Recognition**: With your permission, we'll acknowledge your contribution

## Disclosure Policy

- We ask that you give us reasonable time to address the issue before public disclosure
- We'll coordinate with you on the disclosure timeline
- We'll credit you for the discovery (unless you prefer to remain anonymous)

## Security Best Practices

When using [Project Name], we recommend:

- **Keep dependencies updated**: Regularly update all dependencies
- **Use environment variables**: Never commit sensitive data
- **Enable 2FA**: Use two-factor authentication where available
- **Review permissions**: Regularly audit access controls
- **Monitor logs**: Check logs for suspicious activity

## Security Features

[Project Name] includes the following security features:

- [Feature 1: e.g., Input validation]
- [Feature 2: e.g., Rate limiting]
- [Feature 3: e.g., Encrypted storage]
- [Feature 4: e.g., Audit logging]

## Additional Resources

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Security Best Practices Guide](docs/security-guide.md)
- [Dependency Security Policy](docs/dependencies.md)

## Acknowledgments

We thank the following individuals for responsibly disclosing security issues:

- [Name/Handle] - [Issue type] ([Date])
- [Contributors will be listed here]

---

**Last Updated**: [Date]  
**Contact**: [security@example.com]  
**PGP Key**: [Optional: Link to PGP key]