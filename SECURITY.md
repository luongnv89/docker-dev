# Security Policy

## Supported Versions

The following versions of docker-dev are currently being supported with security updates:

| Version | Supported |
|---------|-----------|
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

We take the security of docker-dev seriously. If you believe you have found a security vulnerability, please report it responsibly.

### How to Report

1. **Do NOT** open a public issue
2. Email your report to: **luongnv89@outlook.com**
3. Include as much detail as possible:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Any proposed fixes (if you have them)

### What to Expect

After submitting your report:

1. **Acknowledgment**: You will receive an acknowledgment within 24-48 hours
2. **Assessment**: We will assess the vulnerability and its severity
3. **Update**: We will keep you informed of the progress
4. **Credit**: With your permission, you will be credited in the security advisory

### Scope

This policy applies to:
- The Docker images published in this repository
- CI/CD workflows
- GitHub Actions configurations
- Shell scripts in the repository

### Out of Scope

- Vulnerabilities in third-party base images (Ubuntu, Node.js, Python, etc.)
- Vulnerabilities in upstream packages (report to respective maintainers)
- Social engineering attacks

## Security Best Practices

When using these Docker images:

1. **Use specific tags**: Pin to specific version tags instead of `latest`
2. **Scan images**: Run security scans on images before deployment
3. **Minimal privileges**: Run containers with minimal required privileges
4. **Keep updated**: Regularly pull the latest versions

## Related Resources

- [GitHub Security Advisories](https://docs.github.com/en/code-security/security-advisories/working-with-repository-security-advisories)
- [Docker Security](https://docs.docker.com/engine/security/)
- [Trivy Scanner](https://github.com/aquasecurity/trivy)
