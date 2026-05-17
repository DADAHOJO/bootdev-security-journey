# Boot.dev Security Roadmap

## Overview

This roadmap documents my complete learning journey from hardware security to software security, AppSec, and DevSecOps through Boot.dev.

## Phase 1: Foundation (Current)

### Learn to Code in Python
**Status:** 🔄 In Progress (May 4, 2026 - May 17, 2026)
**Security Mapping:** OWASP Top 10

**Chapters:**
- [x] Introduction
- [x] Variables
- [x] Functions
- [x] Scope
- [x] Testing and Debugging
- [x] Computing
- [x] Comparisons
- [x] Loops
- [x] Lists
- [x] Dictionaries

**Security Connections:**
- Introduction → OWASP Top 10: A04: Insecure Design; secure coding begins with deterministic logic and predictable execution understanding (A04: Insecure Design)
- Variables → OWASP Top 10: A05: Security Misconfiguration; weak type assumptions and inconsistent state handling create brittle, misconfigured logic paths (A05: Security Misconfiguration)
- Functions → OWASP Top 10: A03: Injection; reusable validation/sanitization functions reduce copy-paste mistakes and input injection risk (A03: Injection)
- Scope → OWASP Top 10: A05: Security Misconfiguration; uncontrolled global state can leak or corrupt security-critical values (A05: Security Misconfiguration)
- Testing and Debugging → OWASP Top 10: A05: Security Misconfiguration; poor debugging and untested error paths often leak internals and weaken fail-safe behavior (A05: Security Misconfiguration)
- Computing → OWASP Top 10: A08: Software and Data Integrity Failures; low-level computing clarity supports robust encoding, boundary handling, and integrity-aware logic (A08: Software and Data Integrity Failures)
- Comparisons → OWASP Top 10: A01: Broken Access Control; condition logic drives authorization outcomes and event classification (A01: Broken Access Control)
- Loops → OWASP Top 10: A09: Security Logging and Monitoring Failures; robust loop design is essential for scanning large event streams without dropped logic paths (A09: Security Logging and Monitoring Failures)
- Lists → OWASP Top 10: A09: Security Logging and Monitoring Failures; list operations power event collection, filtering, deduplication, and triage workflows (A09: Security Logging and Monitoring Failures)
- Dictionaries → OWASP Top 10: OWASP A09: Security Logging and Monitoring Failures; chapter concepts are mapped to this OWASP area for practical secure coding behavior

### Learn Linux
**Status:** ⏳ Not Started
**Security Mapping:** File permissions, least privilege, system hardening
**Planned Security Connections:**
- Permissions → Least privilege principle
- File system → Access control review
- Processes → Service hardening

### Learn Git
**Status:** ⏳ Not Started
**Security Mapping:** Secure SDLC, commit hygiene, secret scanning
**Planned Security Connections:**
- Branching → Secure development workflow
- Commits → Change tracking and audit trails
- Hooks → Automated security checks

### Build a Bookbot
**Status:** ⏳ Not Started
**Security Mapping:** Input validation, file operations, error handling
**Planned Security Connections:**
- Text processing → Input sanitization
- File operations → Secure file handling
- CLI tools → Secure argument parsing

### Portfolio Work
- Start **Python Security Log Analyzer**


## Phase 2: Software Engineering

### Functional Programming
**Status:** ⏳ Not Started
**Security Mapping:** Immutable data, pure functions for validation
**Planned Security Connections:**
- Immutability → Prevent data tampering
- Pure functions → Predictable security checks
- Higher-order functions → Composable security rules

### Memory Management in C
**Status:** ⏳ Not Started
**Security Mapping:** Buffer overflows, memory safety, secure coding
**Planned Security Connections:**
- Pointers → Memory corruption prevention
- Allocation → Secure memory handling
- Strings → Buffer overflow prevention

## Phase 3: Backend and AppSec Foundation

### Go or TypeScript
**Status:** ⏳ Not Started
**Security Mapping:** Type safety, secure API development
**Planned Security Connections:**
- Type system → Compile-time security checks
- Error handling → Explicit error propagation
- Modules → Secure dependency management

### SQL
**Status:** ⏳ Not Started
**Security Mapping:** SQL injection prevention, secure database access
**Planned Security Connections:**
- Queries → Parameterized statements
- Transactions → Atomic security operations
- Schema → Secure data design

### Docker
**Status:** ⏳ Not Started
**Security Mapping:** Container security, image hardening
**Planned Security Connections:**
- Images → Minimal attack surface
- Containers → Isolation and sandboxing
- Networks → Secure communication

### Portfolio Work

- Vulnerability Triage Tool
- Start Secure Backend API


## Phase 4: DevSecOps

### Docker Advanced
**Status:** ⏳ Not Started
**Security Mapping:** Container orchestration security, secrets management
**Planned Security Connections:**
- Compose → Multi-container security
- Networks → Service mesh security
- Secrets → Secure secret injection

### Kubernetes
**Status:** ⏳ Not Started
**Security Mapping:** Cluster security, pod security, RBAC
**Planned Security Connections:**
- Pods → Runtime security
- Services → Network policies
- RBAC → Role-based access control

### AWS
**Status:** ⏳ Not Started
**Security Mapping:** Cloud security, IAM, network security
**Planned Security Connections:**
- IAM → Identity and access management
- VPC → Network isolation
- S3 → Secure object storage

### Logging and Observability
**Status:** ⏳ Not Started
**Security Mapping:** Security monitoring, incident response
**Planned Security Connections:**
- Logs → Security event correlation
- Metrics → Attack detection
- Tracing → Incident investigation

## Phase 5 — Advanced Security / Specialization

### Focus Areas

- Application Security (AppSec)
- Secure Code Review
- Threat Modeling
- Vulnerability Assessment
- DevSecOps Engineering
- Software Supply Chain Security

### Security Mapping

| Concept | Security Use |
|--------|-------------|
| APIs | Attack surface analysis |
| Code | Secure coding & auditing |
| CI/CD | Pipeline hardening |
| Dependencies | Supply chain security |
| Logging | Detection & incident response |

### Portfolio Work (Advanced Projects)

**AppSec Review Project**
- Take your Secure Backend API
- Identify vulnerabilities
- Map to OWASP Top 10
- Fix issues
- Document findings

**Threat Modeling Project**
- Create architecture diagram
- Identify risks using STRIDE
- Document mitigations

**Secure Code Review Repo**
- Collect code snippets
- Document:
  - insecure example
  - secure fix
  - explanation

**DevSecOps Pipeline**

- Add GitHub Actions:
  - linting
  - dependency scanning
- Add security checks
- Document pipeline

### Expected Outcomes

By completing Phase 5, I will:

- Understand real-world application security risks
- Perform secure code reviews
- Design secure systems
- Build DevSecOps pipelines
- Demonstrate security engineering capability


## Milestones

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

### OWASP ASVS
- **Secondary focus** during Phase 3 and 4
- Use as checklist for project requirements
- Document ASVS compliance in projects

