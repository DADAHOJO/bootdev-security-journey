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
