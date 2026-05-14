# Security References

Comprehensive security standards and references for Boot.dev learning journey.

## OWASP Top 10 (2021)

Primary focus for mapping Boot.dev concepts to web application security risks.

### A01: Broken Access Control
**Description:** Users can act outside of their intended permissions.
**Boot.dev Connections:**
- Authorization logic in backend APIs
- Role-based access control
- Session management
**Portfolio Application:** Secure authentication systems, permission checks

### A02: Cryptographic Failures
**Description:** Failures related to cryptography (or lack thereof).
**Boot.dev Connections:**
- Hash functions (for file integrity)
- Secure data storage
- Password handling
**Portfolio Application:** File integrity monitor, secure credential storage

### A03: Injection
**Description:** Untrusted data is sent to an interpreter as part of a command or query.
**Boot.dev Connections:**
- Input validation (Python functions)
- SQL queries (later in curriculum)
- String handling
**Portfolio Application:** Input validation libraries, secure query builders

### A04: Insecure Design
**Description:** Flaws in design and architecture (not implementation).
**Boot.dev Connections:**
- Software architecture patterns
- Secure design principles
- Threat modeling basics
**Portfolio Application:** Security-focused project designs

### A05: Security Misconfiguration
**Description:** Improper implementation of controls intended to keep application secure.
**Boot.dev Connections:**
- Error handling (safe error messages)
- Configuration management
- Default settings
**Portfolio Application:** Secure configuration templates

### A06: Vulnerable and Outdated Components
**Description:** Using components with known vulnerabilities.
**Boot.dev Connections:**
- Dependency management
- Version control
- Package updates
**Portfolio Application:** Dependency scanning tools

### A07: Identification and Authentication Failures
**Description:** User identity confirmation, session management, authentication.
**Boot.dev Connections:**
- Dictionary operations (event counting)
- Session tracking
- Authentication logic
**Portfolio Application:** Failed login analyzers, session managers

### A08: Software and Data Integrity Failures
**Description:** Code and infrastructure without integrity protection.
**Boot.dev Connections:**
- File integrity checking
- Hash verification
- Code signing concepts
**Portfolio Application:** File integrity monitor

### A09: Security Logging and Monitoring Failures
**Description:** Insufficient logging and monitoring of security events.
**Boot.dev Connections:**
- File handling (log parsing)
- Loops (log iteration)
- Dictionaries (event counting)
**Portfolio Application:** Security log analyzer, SIEM tools

### A10: Server-Side Request Forgery (SSRF)
**Description:** Server fetches a remote resource without validating the URL.
**Boot.dev Connections:**
- HTTP clients (later in curriculum)
- URL validation
- Request handling
**Portfolio Application:** Secure HTTP client libraries

## OWASP ASVS (Application Security Verification Standard)

Secondary focus for secure backend/API project verification.

### Version 4.0.3 Structure

**V1: Architecture**
- Design security into application architecture
- Threat modeling
- Secure communication channels

**V2: Authentication**
- Multi-factor authentication
- Password policies
- Session management

**V3: Session Management**
- Secure session handling
- Timeout configuration
- Session fixation prevention

**V4: Access Control**
- Role-based access control
- Principle of least privilege
- Authorization checks

**V5: Validation**
- Input validation
- Output encoding
- Type checking

**V6: Stored Cryptography**
- Encryption algorithms
- Key management
- Random number generation

**V7: Error Handling and Logging**
- Secure error messages
- Comprehensive logging
- Incident response

**V8: Data Protection**
- Sensitive data handling
- Data in transit protection
- Data at rest protection

**V9: Communications**
- TLS configuration
- Secure headers
- Certificate validation

**V10: Malicious Code**
- Code review practices
- Static analysis
- Dynamic analysis

**V11: Business Logic**
- Workflow security
- Process integrity
- Fraud prevention

**V12: File System**
- Secure file handling
- Upload restrictions
- Path traversal prevention

**V13: API Security**
- API authentication
- Rate limiting
- API versioning

**V14: Configuration**
- Secure defaults
- Hardening guidelines
- Environment separation

## NIST SSDF (Secure Software Development Framework)

Advanced focus for secure SDLC and professional practices.

### SP 800-218 Categories

**POAM: Prepare the Organization (PO)**
- PO.1: Ensure the organization's software security is governed
- PO.2: Populate the organization's secure software development knowledge
- PO.3: Train people in the organization on secure software development
- PO.4: Establish and maintain the organization's secure development infrastructure
- PO.5: Establish and maintain the organization's secure development processes
- PO.6: Establish and maintain the organization's secure development tools
- PO.7: Acquire and prepare tools and technologies for secure development

**POWM: Protect the Software (PW)**
- PW.1: Protect the software during development
- PW.2: Protect the software during delivery
- PW.3: Protect the software during operation
- PW.4: Prepare to respond to vulnerabilities

**ID: Identify Vulnerabilities (ID)**
- ID.1: Identify vulnerabilities in the software
- ID.2: Identify vulnerabilities in the software's dependencies
- ID.3: Identify vulnerabilities in the software's environment

**RV: Respond to Vulnerabilities (RV)**
- RV.1: Respond to vulnerabilities in the software
- RV.2: Respond to vulnerabilities in the software's dependencies
- RV.3: Respond to vulnerabilities in the software's environment

**RE: Recover from Vulnerabilities (RE)**
- RE.1: Recover from vulnerabilities in the software
- RE.2: Recover from vulnerabilities in the software's dependencies
- RE.3: Recover from vulnerabilities in the software's environment

## Integration Roadmap

### Phase 1: OWASP Top 10 (Current)
- Map every Boot.dev concept to relevant Top 10 category
- Document in security-mapping.md files
- Build projects demonstrating mitigations

### Phase 2: OWASP ASVS (After Phase 3)
- Use ASVS as checklist for backend/API projects
- Document ASVS compliance in project READMEs
- Create asvs-mapping.md for each project

### Phase 3: NIST SSDF (During Phase 4)
- Map DevSecOps practices to SSDF categories
- Document secure development lifecycle
- Create ssdf-mapping.md for CI/CD workflows

## Additional Resources

### Learning Resources
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/)
- [NIST SSDF](https://csrc.nist.gov/publications/detail/sp/800-218/final)

### Tools
- OWASP ZAP (Web application security scanner)
- OWASP Dependency-Check (Dependency vulnerability scanner)
- Bandit (Python security linter)
- Safety (Python dependency checker)

### Communities
- OWASP chapters
- DevSecOps communities
- Security-focused Discord/Slack groups
