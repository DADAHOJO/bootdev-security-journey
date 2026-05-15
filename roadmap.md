# Boot.dev Security Roadmap

## Overview

This roadmap documents my complete learning journey from hardware security to software security, AppSec, and DevSecOps through Boot.dev.

## Phase 1: Foundation (Current)

### Learn to Code in Python
**Status:** ✅ Completed (May 4-7, 2026)
**Security Mapping:** OWASP Top 10 - Input validation, error handling, file operations

**Chapters:**
- [x] Hello World
- [x] Variables
- [x] Functions
- [x] Loops
- [x] Dictionaries
- [x] File Handling
- [x] Error Handling
- [x] Debugging

**Security Connections:**
- Functions → Reusable validation logic (OWASP A03: Injection)
- Dictionaries → Event counting for monitoring (OWASP A07: Identification and Authentication Failures)
- File handling → Log parsing (OWASP A09: Security Logging and Monitoring Failures)
- Error handling → Safe failure behavior (OWASP A05: Security Misconfiguration)

### Learn Linux
**Status:** 🔄 Not Started
**Security Mapping:** File permissions, least privilege, system hardening
**Planned Security Connections:**
- Permissions → Least privilege principle
- File system → Access control review
- Processes → Service hardening

### Learn Git
**Status:** 🔄 Not Started
**Security Mapping:** Secure SDLC, commit hygiene, secret scanning
**Planned Security Connections:**
- Branching → Secure development workflow
- Commits → Change tracking and audit trails
- Hooks → Automated security checks

### Build a Bookbot
**Status:** 🔄 Not Started
**Security Mapping:** Input validation, file operations, error handling
**Planned Security Connections:**
- Text processing → Input sanitization
- File operations → Secure file handling
- CLI tools → Secure argument parsing

## Phase 2: Software Engineering

### Object-Oriented Programming
**Status:** 🔄 Not Started
**Security Mapping:** Secure class design, encapsulation of security logic
**Planned Security Connections:**
- Classes → Security context objects
- Inheritance → Reusable security components
- Polymorphism → Flexible security policies

### Functional Programming
**Status:** 🔄 Not Started
**Security Mapping:** Immutable data, pure functions for validation
**Planned Security Connections:**
- Immutability → Prevent data tampering
- Pure functions → Predictable security checks
- Higher-order functions → Composable security rules

### Data Structures and Algorithms
**Status:** 🔄 Not Started
**Security Mapping:** Efficient security checks, algorithm analysis for DoS prevention
**Planned Security Connections:**
- Hash tables → Fast lookups for blacklists
- Trees → Hierarchical permission structures
- Graphs → Attack path analysis

### Memory Management in C
**Status:** 🔄 Not Started
**Security Mapping:** Buffer overflows, memory safety, secure coding
**Planned Security Connections:**
- Pointers → Memory corruption prevention
- Allocation → Secure memory handling
- Strings → Buffer overflow prevention

## Phase 3: Backend and AppSec Foundation

### Go or TypeScript
**Status:** 🔄 Not Started
**Security Mapping:** Type safety, secure API development
**Planned Security Connections:**
- Type system → Compile-time security checks
- Error handling → Explicit error propagation
- Modules → Secure dependency management

### HTTP Clients
**Status:** 🔄 Not Started
**Security Mapping:** Secure communication, certificate validation
**Planned Security Connections:**
- HTTPS → Transport layer security
- Headers → Security header configuration
- Authentication → Secure credential handling

### SQL
**Status:** 🔄 Not Started
**Security Mapping:** SQL injection prevention, secure database access
**Planned Security Connections:**
- Queries → Parameterized statements
- Transactions → Atomic security operations
- Schema → Secure data design

### HTTP Servers
**Status:** 🔄 Not Started
**Security Mapping:** Secure API design, authentication, authorization
**Planned Security Connections:**
- Routing → Secure endpoint design
- Middleware → Security filters
- Error handling → Safe error responses

### Docker
**Status:** 🔄 Not Started
**Security Mapping:** Container security, image hardening
**Planned Security Connections:**
- Images → Minimal attack surface
- Containers → Isolation and sandboxing
- Networks → Secure communication

### Web Security
**Status:** 🔄 Not Started
**Security Mapping:** OWASP Top 10 comprehensive coverage
**Planned Security Connections:**
- Authentication → OWASP A07
- Authorization → OWASP A01
- Validation → OWASP A03
- Logging → OWASP A09

## Phase 4: DevSecOps

### Docker Advanced
**Status:** 🔄 Not Started
**Security Mapping:** Container orchestration security, secrets management
**Planned Security Connections:**
- Compose → Multi-container security
- Networks → Service mesh security
- Secrets → Secure secret injection

### Kubernetes
**Status:** 🔄 Not Started
**Security Mapping:** Cluster security, pod security, RBAC
**Planned Security Connections:**
- Pods → Runtime security
- Services → Network policies
- RBAC → Role-based access control

### AWS
**Status:** 🔄 Not Started
**Security Mapping:** Cloud security, IAM, network security
**Planned Security Connections:**
- IAM → Identity and access management
- VPC → Network isolation
- S3 → Secure object storage

### CI/CD
**Status:** 🔄 Not Started
**Security Mapping:** Secure pipeline, automated security testing
**Planned Security Connections:**
- Pipelines → Automated security checks
- Artifacts → Secure artifact management
- Deployments → Secure release process

### Logging and Observability
**Status:** 🔄 Not Started
**Security Mapping:** Security monitoring, incident response
**Planned Security Connections:**
- Logs → Security event correlation
- Metrics → Attack detection
- Tracing → Incident investigation

## Milestones

### Short-term (1-3 months)
- [ ] Complete Learn Linux
- [ ] Complete Learn Git
- [ ] Build Bookbot project
- [ ] Start Object-Oriented Programming
- [ ] Build Python Log Analyzer (Project 1)

### Mid-term (3-6 months)
- [ ] Complete Phase 2 (Software Engineering)
- [ ] Build File Integrity Monitor (Project 2)
- [ ] Build Vulnerability Triage Tool (Project 3)
- [ ] Start Phase 3 (Backend and AppSec)

### Long-term (6-12 months)
- [ ] Complete Phase 3
- [ ] Build Secure Backend API (Project 4)
- [ ] Start Phase 4 (DevSecOps)
- [ ] Build Containerized Security Toolkit (Project 5)

## Security Standards Integration

### OWASP Top 10
- **Primary focus** during Phase 1 and 3
- Map every concept to relevant category
- Build projects demonstrating mitigations

### OWASP ASVS
- **Secondary focus** during Phase 3 and 4
- Use as checklist for project requirements
- Document ASVS compliance in projects

### NIST SSDF
- **Advanced focus** during Phase 4
- Map DevSecOps practices to SSDF categories
- Document secure development lifecycle

---

## Alternate Detailed Roadmap View

# Boot.dev Security Engineering Roadmap

## Phase 1 — Foundation

### Boot.dev Courses

- Learn to Code in Python
- Learn Linux
- Learn Git
- Build a Bookbot

### Goals

- Build strong programming fundamentals using Python
- Understand Linux basics (files, permissions, processes)
- Learn Git workflow for version control
- Start consistent daily commits

### Security Mapping

| Boot.dev Concept | Security Connection |
|-----------------|-------------------|
| Functions       | Reusable validation logic |
| Strings         | Input validation awareness |
| Loops           | Log/event processing |
| File handling   | Log parsing |
| Linux permissions | Least privilege |
| Git             | Secure SDLC workflow |

### Portfolio Work

- Start **Python Security Log Analyzer**

---

## Phase 2 — Software Engineering

### Boot.dev Courses

- Object-Oriented Programming
- Functional Programming
- Data Structures & Algorithms

### Goals

- Write clean, modular, maintainable code
- Understand software design patterns
- Improve debugging and problem-solving

### Security Mapping

| Concept | Security Use |
|--------|-------------|
| OOP | Secure design patterns |
| Functional programming | Predictable, testable logic |
| Data structures | Efficient analysis tools |
| Algorithms | Scalable security tooling |
| Error handling | Safe failure behavior |

### Portfolio Work

- Build **File Integrity Monitor**

---

## Phase 3 — Backend & Application Security

### Boot.dev Courses

- Go or TypeScript
- HTTP Clients
- SQL
- HTTP Servers
- Docker

### Goals

- Understand backend systems and APIs
- Build backend services
- Learn container basics

### Security Mapping

| Concept | Security Use |
|--------|-------------|
| HTTP | Request/response security |
| SQL | SQL injection prevention |
| APIs | Authentication & authorization |
| Error handling | Secure error responses |
| Docker | Container security basics |

### Security References

- OWASP Top 10 → https://owasp.org/www-project-top-ten/
- OWASP ASVS → https://owasp.org/www-project-application-security-verification-standard/
- NIST SSDF → https://csrc.nist.gov/pubs/sp/800/218/final

### Portfolio Work

- Vulnerability Triage Tool
- Start Secure Backend API

---

## Phase 4 — DevSecOps

### Boot.dev Courses

- Docker (advanced)
- Kubernetes
- AWS
- CI/CD
- Logging and Observability

### Goals

- Understand deployment pipelines
- Learn container orchestration
- Build cloud fundamentals

### Security Mapping

| Concept | Security Use |
|--------|-------------|
| CI/CD | Pipeline security |
| Docker | Image hardening |
| Kubernetes | Workload security |
| AWS | IAM and cloud security |
| Logging | Detection and monitoring |

### Portfolio Work

- Containerized Security Toolkit
- Extend Secure Backend API

---

## Phase 5 — Advanced Security / Specialization

### Focus Areas

- Application Security (AppSec)
- Secure Code Review
- Threat Modeling
- Vulnerability Assessment
- DevSecOps Engineering
- Software Supply Chain Security

---

### Key Topics to Learn

#### Application Security

- OWASP Top 10 deep dive
- Secure API design
- Input validation & output encoding
- Authentication & authorization
- Cryptography basics

---

#### Threat Modeling

- STRIDE model
- Attack surface analysis
- Data flow diagrams
- Abuse cases

---

#### Vulnerability Analysis

- Static Analysis (SAST)
- Dynamic Analysis (DAST)
- Manual code review
- Bug classes:
  - Injection
  - Broken access control
  - Security misconfiguration

---

#### Secure SDLC

- NIST SSDF practices
- Secure design principles
- Secure coding guidelines
- Code review processes

---

#### Supply Chain Security

- Dependency vulnerabilities
- SBOM (Software Bill of Materials)
- Secure package management
- Signing and verification

---

### Security Mapping

| Concept | Security Use |
|--------|-------------|
| APIs | Attack surface analysis |
| Code | Secure coding & auditing |
| CI/CD | Pipeline hardening |
| Dependencies | Supply chain security |
| Logging | Detection & incident response |

---

### Portfolio Work (Advanced Projects)

**AppSec Review Project**
- Take your Secure Backend API
- Identify vulnerabilities
- Map to OWASP Top 10
- Fix issues
- Document findings

---

**Threat Modeling Project**
- Create architecture diagram
- Identify risks using STRIDE
- Document mitigations

---

**Secure Code Review Repo**
- Collect code snippets
- Document:
  - insecure example
  - secure fix
  - explanation

---

**DevSecOps Pipeline**

- Add GitHub Actions:
  - linting
  - dependency scanning
- Add security checks
- Document pipeline

---

### Expected Outcomes

By completing Phase 5, you will:

- Understand real-world application security risks
- Perform secure code reviews
- Design secure systems
- Build DevSecOps pipelines
- Demonstrate security engineering capability

---

## Final Outcome

```text
Hardware Security Engineer
→ Software Engineering Foundations
→ Application Security / Secure Backend / DevSecOps Engineer
```
