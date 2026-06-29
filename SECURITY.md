# Security Policy

## Reporting Security Vulnerabilities

If you discover a security vulnerability in this project, please report it responsibly by emailing **jonathan.lisam@securetech.local** instead of using the public issue tracker.

### What to Include in Your Report

- **Description:** Clear explanation of the vulnerability
- **Steps to Reproduce:** How to replicate the issue
- **Impact:** Potential security implications
- **Suggested Fix:** If available

### Response Timeline

- **Acknowledgment:** Within 24 hours
- **Investigation:** 5-7 business days
- **Resolution:** Prioritized based on severity

## Security Considerations for Users

### For Scripts

All PowerShell and shell scripts in this repository should be reviewed before execution in a production environment. Follow these security practices:

1. **Code Review:** Always review scripts for your specific environment
2. **Testing:** Test in a non-production sandbox first
3. **Least Privilege:** Run scripts with minimum required permissions
4. **Audit:** Enable command-line auditing and logging

### For Policies

The security policies included are templates. Customize them for your organization's:
- Risk profile
- Regulatory requirements
- Industry standards
- Business objectives

## Compliance & Standards

This project implements controls aligned with:

- **NIST Cybersecurity Framework 2.0**
- **ISO/IEC 27001:2022**
- **CIS Controls v8**
- **Nigeria Data Protection Act (NDPA)**
- **NIST SP 800-61** (Incident Handling)
- **NIST SP 800-53** (Security Controls)

## Security Maturity Model

| Phase | Status | Focus |
|-------|--------|-------|
| **Foundation** | ✅ Complete | Basic controls, policies, awareness |
| **Development** | 🔄 In Progress | Advanced detection, automation |
| **Optimization** | ⏳ Planned | Predictive analytics, optimization |

## Vulnerability Disclosure Program

We follow a 90-day responsible disclosure timeline:

1. **Day 0:** Vulnerability reported
2. **Day 1-7:** Initial assessment and reproduction
3. **Day 8-30:** Development of security patch
4. **Day 31-90:** Public disclosure after patch release

## Security Best Practices for Contributors

- Never commit passwords, API keys, or sensitive credentials
- Use `.gitignore` to exclude sensitive files
- Sign commits with GPG when possible
- Follow the principle of least privilege
- Document security assumptions in code comments

## Compliance Verification

Security controls in this project are verified through:

- **Policy Review:** Manual verification against standards
- **Configuration Audit:** Compliance checking scripts
- **Risk Assessment:** Quarterly risk register updates
- **Incident Simulation:** Tabletop exercises and drills

## Contact Information

**Security Lead:** Jonathan Lisam  
**Organization:** SecureTech Solutions Ltd. (Educational Simulation)  
**Project Type:** Capstone Cybersecurity Implementation Plan  
**Programme:** 3MTT Cybersecurity NextGen Cohort

For security concerns: jonathan.lisam@securetech.local  
For project inquiries: project-team@securetech.local

---

*Last Updated: 2026-06-29*  
*Next Review: 2026-09-29*
