# Portfolio Projects

Security-focused projects evolving from Boot.dev learning exercises.

## Project Overview

These projects demonstrate the practical application of Boot.dev concepts to cybersecurity use cases. Each project evolves from simple exercises to portfolio-worthy tools through iterative development.

## Project 1: Python Security Log Analyzer

**Status:** 🔄 Planning
**Boot.dev Concepts:**
- Strings (parsing log lines)
- Loops (iterating through logs)
- Dictionaries (counting events by IP)
- File handling (reading log files)
- Functions (modular analysis)
- Debugging (error handling)

**OWASP Mapping:**
- A07: Identification and Authentication Failures (failed login detection)
- A09: Security Logging and Monitoring Failures (log analysis)

**Goal:**
- Parse sample authentication logs
- Count failed login attempts
- Identify repeated IP addresses (brute force detection)
- Generate basic security report
- Alert on suspicious patterns

**Features:**
- [ ] Parse common log formats (auth.log, sshd logs)
- [ ] Count failed login attempts per IP
- [ ] Identify IPs exceeding threshold
- [ ] Generate summary report
- [ ] Export results to CSV/JSON
- [ ] Command-line interface

**Evolution Path:**
1. Exercise: Simple dictionary counting
2. Prototype: Basic IP counter script
3. Project: Full log analyzer with reporting

**Portfolio Value:**
Demonstrates ability to build security monitoring tools using fundamental Python concepts.

## Project 2: File Integrity Monitor

**Status:** 🔄 Planning
**Boot.dev Concepts:**
- File handling (reading files)
- Functions (modular operations)
- Dictionaries (storing file hashes)
- Error handling (safe file operations)
- Hashing (integrity verification)

**OWASP Mapping:**
- A08: Software and Data Integrity Failures (integrity checking)
- A02: Cryptographic Failures (hash functions)

**Goal:**
- Calculate file hashes (SHA-256)
- Store baseline hashes in database
- Compare current hashes to baseline
- Report modified, added, deleted files
- Support recursive directory scanning

**Features:**
- [ ] Calculate SHA-256 hashes for files
- [ ] Store baseline in JSON/SQLite
- [ ] Compare current state to baseline
- [ ] Report changes (modified, new, deleted)
- [ ] Exclude certain files/directories
- [ ] Scheduled scanning support

**Evolution Path:**
1. Exercise: Simple hash calculation
2. Prototype: Single file integrity check
3. Project: Full directory integrity monitor

**Portfolio Value:**
Shows understanding of integrity verification and file system security.

## Project 3: Vulnerability Triage Tool

**Status:** 🔄 Planning
**Boot.dev Concepts:**
- Data structures (organizing CVE data)
- CLI input (interactive tool)
- JSON/CSV handling (import/export)
- Functions (CRUD operations)
- OOP (later enhancement)

**OWASP Mapping:**
- A06: Vulnerable and Outdated Components (dependency tracking)
- A09: Security Logging and Monitoring Failures (vulnerability tracking)

**Goal:**
- Track CVE IDs for components
- Record severity scores (CVSS)
- Track remediation status
- Assign ownership
- Generate triage reports
- Export to various formats

**Features:**
- [ ] Add CVE records
- [ ] Update CVE status
- [ ] Search/filter by severity
- [ ] Assign remediation owners
- [ ] Generate summary reports
- [ ] Export to CSV/JSON
- [ ] Import from CVE database APIs

**Evolution Path:**
1. Exercise: Simple dictionary-based tracker
2. Prototype: CLI tool with basic CRUD
3. Project: Full triage tool with reporting

**Portfolio Value:**
Demonstrates data structure skills and understanding of vulnerability management.

## Project 4: Secure Backend API

**Status:** 🔄 Planning (Phase 3)
**Boot.dev Concepts:**
- HTTP servers (API endpoints)
- SQL (database queries)
- Routing (endpoint design)
- Error handling (safe responses)
- Logging (security events)

**OWASP Mapping:**
- A01: Broken Access Control (authorization)
- A03: Injection (SQL injection prevention)
- A07: Identification and Authentication Failures (auth)
- A09: Security Logging and Monitoring Failures (logging)

**ASVS Mapping:**
- V2: Authentication
- V4: Access Control
- V5: Validation
- V7: Error Handling and Logging

**Goal:**
- Build simple REST API
- Implement input validation
- Add safe error handling
- Add structured logging
- Add authentication/authorization
- Demonstrate secure coding practices

**Features:**
- [ ] RESTful API design
- [ ] Input validation on all endpoints
- [ ] Parameterized SQL queries
- [ ] Secure error messages
- [ ] Structured security logging
- [ ] Basic authentication
- [ ] Rate limiting
- [ ] CORS configuration

**Evolution Path:**
1. Exercise: Simple HTTP server
2. Prototype: Basic API with one endpoint
3. Project: Full secure API with multiple endpoints

**Portfolio Value:**
Shows secure backend development skills and OWASP/ASVS knowledge.

## Project 5: Containerized Security Toolkit

**Status:** 🔄 Planning (Phase 4)
**Boot.dev Concepts:**
- Docker (containerization)
- Linux (container OS)
- CLI tooling (scripting)
- GitHub workflow (automation)

**OWASP Mapping:**
- A05: Security Misconfiguration (container hardening)
- A06: Vulnerable and Outdated Components (image scanning)

**NIST SSDF Mapping:**
- PW.3: Protect software during operation
- RV.2: Respond to vulnerabilities in dependencies

**Goal:**
- Dockerize Python security tools
- Create unified security toolkit
- Add usage instructions
- Document container security best practices
- Include hardening guidelines

**Features:**
- [ ] Containerize Log Analyzer
- [ ] Containerize File Integrity Monitor
- [ ] Containerize Vulnerability Triage Tool
- [ ] Create unified entrypoint
- [ ] Add health checks
- [ ] Document security hardening
- [ ] Include usage examples
- [ ] Add CI/CD pipeline

**Evolution Path:**
1. Exercise: Simple Dockerfile
2. Prototype: Single tool containerized
3. Project: Full toolkit with multiple tools

**Portfolio Value:**
Demonstrates DevSecOps skills and container security knowledge.

## Project Evolution Framework

### Stage 1: Exercise Connection
- Identify relevant Boot.dev exercise
- Note security application
- Document mapping to OWASP/ASVS

### Stage 2: Prototype Development
- Create minimal working example
- Apply to security use case
- Test with sample data
- Document approach

### Stage 3: Project Completion
- Expand to full-featured tool
- Add comprehensive README
- Include security considerations
- Add usage examples
- Create portfolio-worthy artifact

## Project Selection Criteria

Projects are selected based on:
1. **Relevance to Boot.dev curriculum** - Uses concepts being learned
2. **Security value** - Addresses real security concerns
3. **Portfolio impact** - Demonstrates marketable skills
4. **Complexity progression** - Builds from simple to complex
5. **Tool实用性** - Creates genuinely useful security tools

## Future Project Ideas

As learning progresses, additional projects may include:
- Secure password manager (Phase 2/3)
- Web application firewall concepts (Phase 3)
- SIEM log correlation tool (Phase 4)
- Security scanning automation (Phase 4)
- Incident response playbook tool (Phase 4)

## Project Timeline

### Q2 2026 (May-June)
- [ ] Project 1: Python Log Analyzer
- [ ] Project 2: File Integrity Monitor

### Q3 2026 (July-September)
- [ ] Project 3: Vulnerability Triage Tool
- [ ] Begin Phase 3 learning

### Q4 2026 (October-December)
- [ ] Project 4: Secure Backend API
- [ ] Complete Phase 3

### Q1 2027 (January-March)
- [ ] Project 5: Containerized Security Toolkit
- [ ] Begin Phase 4 learning

---

## Extended Project Details

### 🛠️ Portfolio Projects — Boot.dev Security Journey

## 🎯 Purpose

This document tracks the security-focused portfolio projects I will build while progressing through Boot.dev.

Boot.dev provides the software engineering foundation. I apply security engineering concepts using:

- OWASP Top 10
- OWASP ASVS
- NIST SSDF

The goal is to demonstrate my transition from:

```text
Hardware Security
→ Software Engineering
→ Software Security / AppSec / DevSecOps
```

---

## 🧭 Project Methodology

Each project follows this model:

```text
Problem → Boot.dev concepts → Security relevance → Implementation → Improvements
```

Each project should show:

- Practical coding ability
- Security awareness
- Clean documentation
- Real-world relevance
- Portfolio value for interviews

---

# 🔐 Project 1 — Python Security Log Analyzer

## 📌 Problem

Organizations generate large volumes of logs from systems, applications, and authentication services. Reviewing these logs manually is time-consuming and error-prone.

This project focuses on building a Python-based log analyzer that can detect suspicious login activity, such as repeated failed login attempts, suspicious IP addresses, and possible brute-force patterns.

---

## 🧠 Boot.dev Concepts Used

- Strings
- Loops
- Dictionaries
- Functions
- File handling
- Debugging
- Error handling

---

## 🔒 Security Relevance

This project connects basic Python programming to real-world defensive security work.

Security use cases include:

- Log analysis
- Brute-force detection
- Suspicious IP tracking
- Failed login monitoring
- Basic incident detection
- Security automation foundations

---

## ⚙️ Planned Implementation

The tool should be able to:

- Read a sample log file
- Parse each log line
- Extract usernames, IP addresses, timestamps, and event types
- Count failed login attempts
- Identify repeated failed login sources
- Generate a basic summary report

---

## 📁 Suggested Folder Structure

```text
python-log-analyzer/
├── README.md
├── logs/
│   └── sample-auth.log
├── src/
│   └── log_analyzer.py
├── reports/
│   └── sample-report.txt
└── notes.md
```

---

## 🧪 Example Output

```text
Security Log Analysis Report

Total failed login attempts: 24

Top suspicious IPs:
192.168.1.10 → 15 failed attempts
192.168.1.20 → 5 failed attempts
10.0.0.8 → 4 failed attempts

Potential brute-force source:
192.168.1.10
```

---

## 🔗 Security Mapping

```text
Boot.dev concept → Security connection → Portfolio application

Strings → parsing log lines → extracting usernames and IPs
Loops → processing many log entries → scanning security events
Dictionaries → counting repeated values → failed login counters
Functions → reusable logic → parsing and reporting helpers
File handling → reading logs → defensive monitoring tool
Debugging → troubleshooting parsing issues → reliable security automation
Error handling → safe failure behavior → robust CLI tool
```

---

## 🚀 Future Improvements

- Add timestamp-based analysis
- Add command-line arguments
- Export reports as JSON or CSV
- Add configurable threshold for suspicious IPs
- Add alerting output
- Add unit tests
- Add documentation explaining detection logic

---

# 📂 Project 2 — File Integrity Monitor

## 📌 Problem

Unauthorized file changes can indicate tampering, compromise, or accidental misconfiguration. Security teams often need a way to detect whether important files have changed.

This project focuses on building a Python-based File Integrity Monitor that creates file hashes, stores a trusted baseline, and compares current file states against that baseline.

---

## 🧠 Boot.dev Concepts Used

- File handling
- Functions
- Dictionaries
- Error handling
- Data structures
- Hashing with Python libraries

---

## 🔒 Security Relevance

This project demonstrates a foundational security monitoring concept: file integrity checking.

Security use cases include:

- Tamper detection
- Configuration monitoring
- Incident response support
- Change detection
- Basic host-based security monitoring

---

## ⚙️ Planned Implementation

The tool should be able to:

- Scan a target directory
- Generate SHA256 hashes for files
- Store baseline hashes
- Re-scan the directory later
- Compare current hashes with baseline hashes
- Report modified, added, or deleted files

---

## 📁 Suggested Folder Structure

```text
file-integrity-monitor/
├── README.md
├── src/
│   └── fim.py
├── test-files/
│   └── sample.txt
├── baseline/
│   └── hashes.json
├── reports/
│   └── integrity-report.txt
└── notes.md
```

---

## 🧪 Example Output

```text
File Integrity Report

Modified files:
- config.yaml

New files:
- suspicious_script.sh

Deleted files:
- old_config.txt
```

---

## 🔗 Security Mapping

```text
Boot.dev concept → Security connection → Portfolio application

File handling → reading files → monitoring file state
Functions → reusable hashing logic → file hash generator
Dictionaries → storing file/hash pairs → baseline comparison
Error handling → safe failures → handling missing files/directories
Hashing → integrity verification → tamper detection
```

---

## 🚀 Future Improvements

- Add recursive directory scanning
- Add scheduled scans
- Add JSON/CSV report export
- Add allowlist support
- Add real-time monitoring
- Add unit tests
- Dockerize the tool later

---

# 🧾 Project 3 — Vulnerability Triage Tool

## 📌 Problem

Security teams need a structured way to track vulnerabilities, affected components, severity, ownership, and remediation status.

This project focuses on building a simple vulnerability triage tool that can track vulnerability records and generate reports.

---

## 🧠 Boot.dev Concepts Used

- Lists
- Dictionaries
- Functions
- JSON/CSV handling
- CLI input
- Error handling
- Object-Oriented Programming later

---

## 🔒 Security Relevance

This project maps directly to practical vulnerability management workflows.

Security use cases include:

- CVE tracking
- Severity classification
- Remediation tracking
- Vulnerability lifecycle management
- Security reporting
- Risk prioritization

---

## ⚙️ Planned Implementation

The tool should be able to:

- Add vulnerability records
- Store CVE ID or vulnerability title
- Track severity
- Track affected component
- Track owner
- Track remediation status
- Generate a report

---

## 📁 Suggested Folder Structure

```text
vulnerability-triage-tool/
├── README.md
├── src/
│   └── triage.py
├── data/
│   └── vulnerabilities.json
├── reports/
│   └── triage-report.md
└── notes.md
```

---

## 🧪 Example Vulnerability Record

```text
CVE ID: CVE-2026-1234
Severity: High
Affected Component: Example API Service
Status: Open
Owner: Security Team
Remediation: Patch pending
```

---

## 🔗 Security Mapping

```text
Boot.dev concept → Security connection → Portfolio application

Dictionaries → structured records → vulnerability objects
Lists → multiple records → vulnerability database
Functions → reusable workflows → add/update/report actions
JSON/CSV → persistent storage → exportable reports
CLI input → interactive usage → security workflow tooling
OOP → structured design → vulnerability record classes later
```

---

## 🚀 Future Improvements

- Add CVSS score field
- Add filtering by severity/status
- Add CSV export
- Add web UI later
- Add database backend
- Add integration with public CVE APIs
- Add risk-based prioritization logic

---

# 🌐 Project 4 — Secure Backend API

## 📌 Problem

Backend APIs often handle user input, authentication, database operations, and sensitive data. Poorly designed APIs can introduce security risks such as injection, broken access control, insecure error handling, and information leakage.

This project focuses on building a simple backend API with security-aware design decisions.

---

## 🧠 Boot.dev Concepts Used

- HTTP servers
- Routing
- Request/response handling
- SQL
- Error handling
- Logging
- Authentication concepts later

---

## 🔒 Security Relevance

This project demonstrates practical application security and secure backend engineering.

Security use cases include:

- Input validation
- Secure error handling
- Authentication
- Authorization
- Logging and monitoring
- OWASP Top 10 mapping
- OWASP ASVS checklist usage

---

## ⚙️ Planned Implementation

The API should include:

- Basic REST endpoints
- Input validation
- Safe error responses
- Structured logging
- Basic database interaction
- Authentication added in a later version
- Authorization added in a later version

---

## 📁 Suggested Folder Structure

```text
secure-backend-api/
├── README.md
├── src/
│   ├── main.py
│   ├── routes.py
│   ├── validators.py
│   └── logging_config.py
├── tests/
├── docs/
│   ├── security-notes.md
│   └── owasp-mapping.md
└── notes.md
```

---

## 🧪 Example Safe Error Response

```json
{
  "error": "Invalid request"
}
```

Avoid exposing sensitive internal details such as:

```text
database stack traces
internal file paths
debug secrets
framework errors
```

---

## 🔗 Security Mapping

```text
Boot.dev concept → Security connection → Portfolio application

HTTP servers → API attack surface → secure backend service
SQL → database interaction → SQL injection prevention notes
Error handling → safe failure → generic error responses
Logging → detection support → structured security logs
Validation → input control → request validation helpers
Authentication → identity verification → controlled API access
Authorization → access control → role-based API behavior
```

---

## 🛡️ OWASP/NIST Mapping

Use this project to map concepts to:

### OWASP Top 10

- Broken Access Control
- Injection
- Security Misconfiguration
- Identification and Authentication Failures
- Software and Data Integrity Failures
- Security Logging and Monitoring Failures

### OWASP ASVS

- Input validation
- Authentication
- Authorization
- Logging
- Error handling
- Secure configuration

### NIST SSDF

- Secure design
- Secure implementation
- Vulnerability reduction
- Secure development practices
- Secure release process

---

## 🚀 Future Improvements

- Add authentication
- Add role-based authorization
- Add rate limiting
- Add database persistence
- Add unit and integration tests
- Add API documentation
- Add OWASP ASVS checklist
- Add Docker support
- Add CI/CD checks

---

# 🐳 Project 5 — Containerized Security Toolkit

## 📌 Problem

Security tools should be portable, reproducible, and easy to run across different environments. Containerization helps package tools and dependencies consistently.

This project focuses on containerizing the security tools built in earlier projects.

---

## 🧠 Boot.dev Concepts Used

- Docker
- Linux
- CLI tools
- Git workflow
- File handling
- Python scripting

---

## 🔒 Security Relevance

This project demonstrates DevSecOps thinking and secure tooling practices.

Security use cases include:

- Portable security tools
- Reproducible execution environments
- Containerized security automation
- DevSecOps workflow foundations
- Secure deployment awareness

---

## ⚙️ Planned Implementation

The toolkit should include:

- Dockerized Python Security Log Analyzer
- Dockerized File Integrity Monitor
- CLI-style usage
- Documentation for running tools
- Security notes for container usage

---

## 📁 Suggested Folder Structure

```text
containerized-security-toolkit/
├── README.md
├── Dockerfile
├── docker-compose.yml
├── tools/
│   ├── log-analyzer/
│   └── file-integrity-monitor/
├── docs/
│   └── container-security-notes.md
└── notes.md
```

---

## 🧪 Example Usage

```bash
docker run security-toolkit scan-logs logs/sample-auth.log
```

```bash
docker run security-toolkit check-integrity /target-directory
```

---

## 🔗 Security Mapping

```text
Boot.dev concept → Security connection → Portfolio application

Docker → reproducible environment → portable security toolkit
Linux → runtime environment → container basics
CLI tools → automation → repeatable security workflows
Git workflow → version control → secure development history
Documentation → operational clarity → portfolio-ready project
```

---

## 🛡️ DevSecOps Mapping

Use this project to document:

- Container hardening basics
- Avoiding secrets in images
- Minimal base image awareness
- Dependency management
- Image scanning notes
- CI/CD integration later

---

## 🚀 Future Improvements

- Add GitHub Actions
- Add dependency checks
- Add container image scanning
- Add Makefile or scripts for easier usage
- Add versioned releases
- Add secure configuration examples
- Add README badges later

---

# 🛡️ Advanced Projects — Phase 5

Phase 5 focuses on deeper software security specialization after completing the foundational Boot.dev learning phases.

The goal is to move beyond basic coding projects and demonstrate application security, secure code review, threat modeling, and DevSecOps capability.

---

# 🔍 Advanced Project 1 — AppSec Review Project

## 📌 Goal

Perform a full security review of the Secure Backend API.

This project takes the Secure Backend API built earlier and reviews it from an application security perspective.

---

## 🧠 Skills Demonstrated

- Application security testing
- OWASP Top 10 mapping
- Secure code review
- Vulnerability documentation
- Risk-based remediation

---

## ⚙️ Planned Tasks

- Review API endpoints
- Identify insecure patterns
- Map findings to OWASP Top 10
- Document each finding
- Apply fixes
- Re-test after fixes
- Write a final security review report

---

## 📁 Suggested Folder Structure

```text
appsec-review-project/
├── README.md
├── findings/
│   └── appsec-findings.md
├── fixes/
│   └── remediation-notes.md
├── docs/
│   ├── owasp-top10-mapping.md
│   └── final-review-report.md
└── notes.md
```

---

## 🧪 Example Finding Format

```text
Finding: Missing input validation
Risk: Medium
OWASP Mapping: Injection
Impact: Invalid input may affect application behavior
Recommendation: Validate and constrain all user-controlled input
Status: Fixed
```

---

## 🎯 Outcome

This project demonstrates real-world application security review capability.

---

# 🧠 Advanced Project 2 — Threat Modeling Project

## 📌 Goal

Analyze a system design and identify possible threats before implementation or deployment.

This project focuses on security design thinking using a structured threat modeling approach.

---

## 🧠 Skills Demonstrated

- Threat modeling
- System design review
- Attack surface analysis
- Risk identification
- Mitigation planning

---

## ⚙️ Planned Tasks

- Choose the Secure Backend API as the target system
- Create a simple architecture diagram
- Identify assets
- Identify trust boundaries
- Identify entry points
- Use STRIDE to identify threats
- Document mitigations

---

## 📁 Suggested Folder Structure

```text
threat-modeling-project/
├── README.md
├── diagrams/
│   └── architecture-diagram.png
├── docs/
│   ├── assets.md
│   ├── trust-boundaries.md
│   ├── stride-analysis.md
│   └── mitigations.md
└── notes.md
```

---

## 🧪 Example STRIDE Entry

```text
Threat Type: Spoofing
Component: API authentication
Risk: An attacker may attempt to impersonate a valid user
Mitigation: Add authentication and token validation
Status: Planned
```

---

## 🎯 Outcome

This project demonstrates secure design and architecture review capability.

---

# 📋 Advanced Project 3 — Secure Code Review Collection

## 📌 Goal

Create a collection of insecure code examples, secure fixes, and explanations.

This project helps demonstrate secure coding knowledge and the ability to identify risky implementation patterns.

---

## 🧠 Skills Demonstrated

- Secure coding
- Code review
- Vulnerability identification
- Remediation explanation
- Developer-friendly security communication

---

## ⚙️ Planned Tasks

- Create small insecure examples
- Explain the issue
- Provide a secure version
- Map the issue to OWASP or secure coding principles
- Document lessons learned

---

## 📁 Suggested Folder Structure

```text
secure-code-review-collection/
├── README.md
├── insecure/
│   ├── weak_input_validation.py
│   └── unsafe_error_handling.py
├── secure/
│   ├── strong_input_validation.py
│   └── safe_error_handling.py
├── explanations/
│   ├── input-validation.md
│   └── error-handling.md
└── notes.md
```

---

## 🧪 Example Review Format

```text
Issue: Unsafe error handling
Problem: The application exposes internal exception details
Risk: Attackers may learn internal paths, framework details, or database behavior
Secure Fix: Return generic user-facing errors and log technical details internally
```

---

## 🎯 Outcome

This project demonstrates secure code review and developer education capability.

---

# ⚙️ Advanced Project 4 — DevSecOps Pipeline Project

## 📌 Goal

Add security checks to a CI/CD workflow.

This project focuses on integrating security into the development lifecycle rather than treating security as a separate final step.

---

## 🧠 Skills Demonstrated

- DevSecOps workflow design
- CI/CD basics
- Secure development automation
- Dependency awareness
- Code quality checks

---

## ⚙️ Planned Tasks

- Add GitHub Actions workflow
- Add linting
- Add test execution
- Add dependency awareness
- Add security notes
- Document pipeline behavior

---

## 📁 Suggested Folder Structure

```text
devsecops-pipeline-project/
├── README.md
├── .github/
│   └── workflows/
│       └── security-checks.yml
├── docs/
│   ├── pipeline-overview.md
│   └── security-checks.md
└── notes.md
```

---

## 🧪 Example Pipeline Goals

```text
Run tests on every push
Run lint checks on pull requests
Document dependency review process
Avoid committing secrets
Keep build steps reproducible
```

---

## 🎯 Outcome

This project demonstrates DevSecOps awareness and secure SDLC thinking.

---

# 🔗 Security References

Use these references alongside all projects:

## OWASP Top 10

Use OWASP Top 10 to map backend/API lessons to common web application security risks.

Link:

```text
https://owasp.org/www-project-top-ten/
```

---

## OWASP ASVS

Use OWASP ASVS as a checklist for secure backend/API projects.

Link:

```text
https://owasp.org/www-project-application-security-verification-standard/
```

---

## NIST SSDF

Use NIST SSDF to understand secure SDLC and professional secure development practices.

Link:

```text
https://csrc.nist.gov/pubs/sp/800/218/final
```

---

# 🎯 Final Portfolio Outcome

This portfolio should demonstrate:

- Strong programming fundamentals
- Backend engineering capability
- Security-aware development mindset
- Practical security tooling
- Application security understanding
- DevSecOps readiness
- Secure SDLC awareness

---

# 🏁 Career Transition Goal

```text
Hardware Security
→ Software Engineering Foundations
→ Software Security / AppSec / DevSecOps
```

---

# 💡 Guiding Principle

```text
Build → Secure → Document → Improve
```

---

# 🔁 Portfolio Maintenance Rule

For each project:

```text
1. Build a small working version
2. Document what it does
3. Add security mapping
4. Improve iteratively
5. Keep commits small and meaningful
```

---

# ✅ Commit Message Examples

```text
Add initial log analyzer project structure
Add file integrity monitor baseline logic
Document OWASP mapping for secure backend API
Add threat modeling notes for backend API
Add DevSecOps pipeline project plan
Update portfolio project roadmap
```
