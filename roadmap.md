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
``
