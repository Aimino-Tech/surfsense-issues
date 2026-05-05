# Security Policy

## Supported Versions

We apply security patches to the latest release of SurfSense. If you are using an older version, please upgrade to the latest release to receive security fixes.

## Reporting a Vulnerability

We take security vulnerabilities seriously. Please do **not** file a public GitHub issue for security vulnerabilities.

### Disclosure Process

1. **Report via email**: Send details of the vulnerability to **security@surfsense.ai**
2. **Encrypt if possible**: If the vulnerability is sensitive, please use our PGP key (available on request)
3. **Include**:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if any)

### What to Expect

- **Acknowledgment**: We will acknowledge your report within 24 hours
- **Assessment**: We will assess and validate the vulnerability within 5 business days
- **Fix timeline**: Depending on severity, we aim to release a fix within:
  - **Critical**: 24-48 hours
  - **High**: 5 business days
  - **Medium**: 14 days
  - **Low**: Next release cycle
- **Disclosure**: We will coordinate disclosure with you once the fix is released

### Scope

We are interested in vulnerabilities in:
- SurfSense web application and API
- SurfSense desktop application
- SurfSense browser extension
- SurfSense Obsidian plugin
- Authentication and authorization mechanisms
- Data storage and transmission

### Out of Scope

- Issues in third-party dependencies (report to the respective project)
- Self-XSS or issues requiring victim to modify local files
- Social engineering attacks
- Denial of service attacks that require network-level mitigation

## Security Best Practices for Self-Hosted Instances

If you self-host SurfSense:
- Keep your deployment updated to the latest version
- Use strong, unique passwords for all user accounts
- Configure HTTPS for production deployments
- Restrict network access to your PostgreSQL database
- Regularly review access logs

## Recognition

We maintain a hall of fame for security researchers who responsibly disclose vulnerabilities. With your permission, we will acknowledge your contribution in our release notes.

Thank you for helping keep SurfSense and its users safe.
