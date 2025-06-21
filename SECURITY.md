# Security Policy

## 🛡️ Supported Versions

We actively support the following versions of Metaphor: ReFantazio Offline Setup Assistant:

| Version | Supported          |
| ------- | ------------------ |
| 2.1.x   | ✅ Yes             |
| 2.0.x   | ✅ Yes             |
| 1.9.x   | ⚠️ Limited support |
| < 1.9   | ❌ No              |

## 🚨 Reporting a Vulnerability

The security of our gaming community is important to us. If you discover a security vulnerability, please follow these steps:

### 📧 Contact Information

**Primary Contact**: security@metaphor-offline.com
**GPG Key**: [Available here](https://metaphor-refantazio-offline.github.io/pgp-key.asc)

### 🔍 What to Include

When reporting a vulnerability, please include:

- **Description**: Clear description of the vulnerability
- **Impact**: Potential impact on users and the gaming experience
- **Steps to Reproduce**: Detailed reproduction steps
- **Proof of Concept**: Code or screenshots (if applicable)
- **Environment**: OS, version, configuration details
- **Severity Assessment**: Your assessment of severity level

### ⏱️ Response Timeline

- **Acknowledgment**: Within 24 hours
- **Initial Assessment**: Within 72 hours
- **Regular Updates**: Every 7 days until resolution
- **Resolution**: Varies by severity (see below)

### 🎯 Severity Levels

#### 🔴 Critical (24-48 hours)
- Remote code execution
- Unauthorized access to game files
- User data exposure
- System compromise

#### 🟠 High (3-7 days)
- Privilege escalation
- Authentication bypass
- Sensitive information disclosure
- Denial of service

#### 🟡 Medium (2-4 weeks)
- Input validation issues
- Information leakage
- Configuration vulnerabilities
- Limited DoS

#### 🟢 Low (1-3 months)
- Minor information disclosure
- Low-impact configuration issues
- Cosmetic security issues

## 🔐 Security Best Practices

### For Users

#### Download Safety
- ✅ Always download from official sources
- ✅ Verify checksums/signatures
- ✅ Use antivirus software
- ❌ Don't download from unofficial sites

#### Installation Security
- ✅ Run with minimal required permissions
- ✅ Keep software updated
- ✅ Use official configuration files
- ❌ Don't run as administrator unless necessary

#### Configuration Security
- ✅ Use strong, unique passwords
- ✅ Enable available security features
- ✅ Regular backup of configurations
- ❌ Don't share configuration files with sensitive data

### For Developers

#### Code Security
- ✅ Input validation and sanitization
- ✅ Secure coding practices
- ✅ Regular dependency updates
- ✅ Code review process

#### Build Security
- ✅ Secure build pipeline
- ✅ Signed releases
- ✅ Vulnerability scanning
- ✅ Secure storage of secrets

## 🏆 Responsible Disclosure

We believe in responsible disclosure and work with security researchers to protect our users. 

### 🎁 Recognition Program

While we don't offer monetary rewards, we recognize security researchers who help us improve:

- **Hall of Fame**: Recognition on our security page
- **Special Thanks**: Acknowledgment in release notes
- **Community Status**: Special role in our Discord
- **Early Access**: Beta access to new features

### 📋 Disclosure Process

1. **Report**: Submit vulnerability through secure channels
2. **Validate**: We confirm and assess the issue
3. **Fix**: Develop and test the fix
4. **Coordinate**: Work with reporter on disclosure timing
5. **Release**: Public disclosure after fix deployment
6. **Recognition**: Credit reporter (if desired)

## 🛠️ Security Measures

### Current Protections

#### Application Security
- Input validation on all user inputs
- Secure file handling and permissions
- Sandboxed execution environment
- Regular security audits

#### Communication Security
- HTTPS for all web communications
- Certificate pinning where applicable
- Secure update mechanisms
- Encrypted configuration storage

#### Build Security
- Automated security scanning
- Dependency vulnerability checks
- Signed releases with verification
- Secure CI/CD pipeline

### Planned Improvements

- Enhanced encryption for sensitive data
- Additional sandboxing mechanisms
- Improved audit logging
- Multi-factor authentication support

## 📚 Security Resources

### Documentation
- [Security Architecture](docs/security-architecture.md)
- [Threat Model](docs/threat-model.md)
- [Incident Response Plan](docs/incident-response.md)

### Tools & References
- [OWASP Gaming Security](https://owasp.org/www-project-top-10-for-gaming/)
- [Common Vulnerabilities Database](https://cve.mitre.org/)
- [Security Headers](https://securityheaders.com/)

## 🚫 Out of Scope

The following are typically **not** considered security vulnerabilities:

### Expected Behavior
- Features working as designed
- Performance issues
- UI/UX concerns
- Compatibility problems

### Third-Party Issues
- Game-specific bugs or vulnerabilities
- OS-level security issues
- Hardware-related problems
- Network configuration issues

### Low-Impact Issues
- Theoretical attacks without practical impact
- Issues requiring physical access
- Social engineering vectors
- Cosmetic issues

## 📞 Emergency Contact

For **critical security issues** requiring immediate attention:

- **Discord**: @security-team in our server
- **Email**: emergency@metaphor-offline.com
- **Phone**: Available upon request for verified researchers

## 📄 Legal

### Safe Harbor

We will not pursue legal action against security researchers who:
- Make good faith efforts to avoid privacy violations
- Don't access, modify, or delete user data
- Don't perform attacks against our infrastructure
- Don't violate any applicable laws

### Confidentiality

All security reports are treated as confidential until public disclosure is agreed upon.

---

Thank you for helping keep the Metaphor: ReFantazio community safe! 🎮🛡️ 