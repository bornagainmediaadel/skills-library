13 SECURITY & COMPLIANCE
========================

Skills for keeping systems safe: security reviews, threat modelling, OWASP, secrets management,
GDPR, MCP/agent security audits and hardening.

34 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - agent-owasp-compliance
  - agent-supply-chain
  - anti-reversing-techniques
  - attack-tree-construction
  - audit-integrity
  - auth-implementation-patterns
  - binary-analysis-patterns
  - codeql
  - data-breach-blast-radius
  - dependabot
  - gdpr-compliant
  - gdpr-data-handling
  - github-actions-hardening
  - k8s-security-policies
  - mcp-implementation-security-review
  - mcp-security-audit
  - memory-forensics
  - mtls-configuration
  - protect-mcp-setup
  - protocol-reverse-engineering
  - sast-configuration
  - secret-scanning
  - secrets-management
  - security-and-hardening
  - security-auditor
  - security-requirement-extraction
  - security-review
  - session-guard
  - signed-audit-trails-recipe
  - solidity-security
  - stride-analysis-patterns
  - threat-mitigation-mapping
  - threat-model-analyst
  - tm7-threat-model

SKILL DETAILS
-------------

[agent-owasp-compliance]
    Source: awesome-copilot
    What it does: Checks an AI agent's codebase against the OWASP Agentic Security Top 10 risks
    and produces a compliance report mapping your controls to each risk.
    When to use: You are about to put an AI agent into production and want a security compliance
    check.
    Search terms: ai agent security, owasp, agentic security, compliance report, security audit,
    ai risks, asi top 10, agent safety, security review
    Original description: Check any AI agent codebase against the OWASP Agentic Security
    Initiative (ASI) Top 10 risks. Use this skill when: - Evaluating an agent system's security
    posture before production deployment - Running a compliance check against OWASP ASI 2026
    standards - Mapping existing security controls to the 10 agentic risks - Generating a
    compliance report for security review or audit - Comparing agent framework security features
    against the standard - Any request like "is my agent OWASP compliant?", "check ASI
    compliance", or "agentic security audit"

[agent-supply-chain]
    Source: awesome-copilot
    What it does: Verifies the integrity of AI agent plugins, tools, and dependencies by
    generating and checking SHA-256 manifests, detecting tampered files, and auditing version
    pinning and provenance.
    When to use: You want to confirm your installed agent plugins and tools haven't been
    tampered with.
    Search terms: plugin integrity, supply chain security, verify plugins, tampered files,
    checksum manifest, dependency pinning, provenance, sign plugin, ai tools security
    Original description: Verify supply chain integrity for AI agent plugins, tools, and
    dependencies. Use this skill when: - Generating SHA-256 integrity manifests for agent
    plugins or tool packages - Verifying that installed plugins match their published manifests
    - Detecting tampered, modified, or untracked files in agent tool directories - Auditing
    dependency pinning and version policies for agent components - Building provenance chains
    for agent plugin promotion (dev → staging → production) - Any request like "verify plugin
    integrity", "generate manifest", "check supply chain", or "sign this plugin"

[anti-reversing-techniques]
    Source: agents (bundle)
    What it does: Explains anti-reversing, obfuscation, anti-debugging, and environment-
    detection techniques used to protect software or evade analysis, for malware analysis, CTF
    challenges, and security research.
    When to use: You are analyzing protected or packed software and need to understand the
    protections in play.
    Search terms: reverse engineering, obfuscation, anti-debugging, malware analysis, packed
    binaries, ctf, software protection, evasion techniques, security research
    Original description: Understand anti-reversing, obfuscation, and protection techniques
    encountered during software analysis. Use this skill when analyzing malware evasion
    techniques, when implementing anti-debugging protections for CTF challenges, when reverse
    engineering packed binaries, or when building security research tools that need to detect
    virtualized environments.

[attack-tree-construction]
    Source: agents (bundle)
    What it does: Builds attack trees that map out how an attacker could reach a goal, revealing
    defense gaps and making security risks easy to explain to stakeholders.
    When to use: You need to map out how your system could be attacked and where the gaps are.
    Search terms: attack tree, threat modeling, security risks, attack scenarios, defense gaps,
    risk visualization, security planning, explain risks to stakeholders
    Original description: Build comprehensive attack trees to visualize threat paths. Use when
    mapping attack scenarios, identifying defense gaps, or communicating security risks to
    stakeholders.

[audit-integrity]
    Source: awesome-copilot
    What it does: Provides a shared quality framework for security-analysis agents: anti-
    rationalization guards, self-critique loops, retry rules, scored quality gates, and lesson
    tracking so audits stay honest and improve over time.
    When to use: You are running AI-driven security audits and want them held to a consistent
    quality standard.
    Search terms: security audit quality, appsec, audit framework, self-critique, quality gates,
    security analysis, honest reporting, agent governance
    Original description: Shared audit integrity framework for all AppSec agents — enforces
    output quality, intellectual honesty, and continuous improvement through anti-
    rationalization guards, self-critique loops, retry protocols, non-negotiable behaviors,
    self-reflection quality gates (1-10 scoring, ≥8 threshold), and a self-learning system with
    lesson/memory governance for security analysis agents.

[auth-implementation-patterns]
    Source: agents (bundle)
    What it does: Implements secure login and access control using patterns like JWT, OAuth2,
    session management, and role-based permissions.
    When to use: You are building or fixing user login, API security, or permission systems.
    Search terms: user login, authentication, authorization, oauth, jwt, single sign-on, role-
    based access, secure api, session management, permissions
    Original description: Master authentication and authorization patterns including JWT,
    OAuth2, session management, and RBAC to build secure, scalable access control systems. Use
    when implementing auth systems, securing APIs, or debugging security issues.

[binary-analysis-patterns]
    Source: agents (bundle)
    What it does: Analyzes compiled executables using disassembly, decompilation, control flow
    analysis, and code pattern recognition to understand what a program does.
    When to use: You need to understand a compiled program without its source code.
    Search terms: binary analysis, disassembly, decompile, reverse engineering, executable
    analysis, static analysis, control flow, malware, compiled code
    Original description: Master binary analysis patterns including disassembly, decompilation,
    control flow analysis, and code pattern recognition. Use when analyzing executables,
    understanding compiled code, or performing static analysis on binaries.

[codeql]
    Source: awesome-copilot
    What it does: Sets up and configures CodeQL code scanning via GitHub Actions or the command
    line, including workflow files, SARIF output, and troubleshooting.
    When to use: You want automated security scanning of your code on GitHub.
    Search terms: codeql, code scanning, github security, github actions, find vulnerabilities,
    security analysis, sarif, static analysis, github advanced security
    Original description: Comprehensive guide for setting up and configuring CodeQL code
    scanning via GitHub Actions workflows and the CodeQL CLI. This skill should be used when
    users need help with code scanning configuration, CodeQL workflow files, CodeQL CLI
    commands, SARIF output, security analysis setup, or troubleshooting CodeQL analysis.

[data-breach-blast-radius]
    Source: awesome-copilot
    What it does: Inventories the sensitive data your system holds (personal, health, payment,
    credentials), traces where it flows, scores exposure, and reports the regulatory fine ranges
    and costs a breach could trigger under GDPR, CCPA, and HIPAA.
    When to use: You want to know how bad a data breach would be for your business before one
    happens.
    Search terms: data breach impact, what data could be exposed, gdpr fines, hipaa, ccpa,
    sensitive data inventory, breach readiness, data risk report, pii, worst case breach
    Original description: Pre-breach impact analysis: inventories sensitive data (PII, PHI, PCI-
    DSS, credentials), traces data flows, scores exposure vectors, and produces a regulatory
    blast radius report with fine ranges sourced verbatim from GDPR Art. 83, CCPA § 1798.155(a),
    and HIPAA 45 CFR § 160.404. Cost benchmarks from IBM Cost of a Data Breach Report (annually
    updated). All citations in references/SOURCES.md for verification. Use when asked: "assess
    breach impact", "what data could be exposed", "calculate blast radius", "data exposure
    analysis", "how bad would a breach be", "quantify data risk", "sensitive data …

[dependabot]
    Source: awesome-copilot
    What it does: Configures and manages GitHub Dependabot for automatic dependency updates and
    security fixes, including grouped updates, monorepo setups, auto-triage rules, and pre-
    commit vulnerability scanning.
    When to use: You want your project's software dependencies kept up to date and free of known
    vulnerabilities automatically.
    Search terms: dependabot, dependency updates, security updates, vulnerable packages, github,
    dependabot.yml, supply chain security, automatic updates, outdated libraries
    Original description: Comprehensive guide for configuring and managing GitHub Dependabot.
    Use this skill when users ask about creating or optimizing dependabot.yml files, managing
    Dependabot pull requests, configuring dependency update strategies, setting up grouped
    updates, monorepo patterns, multi-ecosystem groups, security update configuration, auto-
    triage rules, or any GitHub Advanced Security (GHAS) supply chain security topic related to
    Dependabot. For pre-commit dependency vulnerability scanning in AI coding agents via the
    GitHub MCP Server, this skill references the Advanced Security plugin (`advanced-secur…

[gdpr-compliant]
    Source: awesome-copilot
    What it does: Applies GDPR-compliant engineering practices when handling personal data: data
    models, authentication, logging, retention and deletion, encryption, anonymization, data
    exports, breach response, and privacy reviews of code.
    When to use: You handle EU customer data and want to be sure your software follows GDPR.
    Search terms: gdpr, privacy compliance, personal data, data protection, cookies, right to
    deletion, data retention, encryption, is this gdpr compliant, eu privacy law
    Original description: Apply GDPR-compliant engineering practices across your codebase. Use
    this skill whenever you are designing APIs, writing data models, building authentication
    flows, implementing logging, handling user data, writing retention/deletion jobs, designing
    cloud infrastructure, or reviewing pull requests for privacy compliance. Trigger this skill
    for any task involving personal data, user accounts, cookies, analytics, emails, audit logs,
    encryption, pseudonymization, anonymization, data exports, breach response, CI/CD pipelines
    that process real data, or any question framed as "is this GDPR-compliant…

[gdpr-data-handling]
    Source: agents (bundle)
    What it does: Sets up how your software collects, stores, and deletes personal data so it
    complies with Europe's GDPR privacy law, including consent tracking and handling customer
    data requests.
    When to use: You handle data from EU customers and need your system to follow GDPR privacy
    rules.
    Search terms: gdpr, privacy law, eu customers, consent, data privacy, personal data, right
    to be forgotten, privacy compliance, cookie consent, data protection
    Original description: Implement GDPR-compliant data handling with consent management, data
    subject rights, and privacy by design. Use when building systems that process EU personal
    data, implementing privacy controls, or conducting GDPR compliance reviews.

[github-actions-hardening]
    Source: awesome-copilot
    What it does: Reviews your GitHub automation workflows for security holes like leaked
    secrets, untrusted code running with elevated access, and over-broad permissions, then shows
    how to lock them down.
    When to use: You want to make sure your automated build and deploy scripts on GitHub can't
    be abused by outsiders.
    Search terms: github actions, ci security, workflow security, secure pipeline, github
    permissions, lock down github, pin actions, build automation safety, devops security
    Original description: Security hardening reviewer for GitHub Actions workflow files
    (.github/workflows/*.yml). Reasons about the Actions threat model that pattern matchers and
    general code linters miss — untrusted-input script injection, privileged triggers running
    fork code, mutable action references, and over-scoped tokens. Use this skill when asked to
    review, audit, harden, or secure a GitHub Actions workflow, when writing a new workflow, or
    for any request like "is this workflow safe?", "review my CI for security issues", "why is
    pull_request_target dangerous here?", "pin my actions", or "lock down GITHUB_TOKEN…

[k8s-security-policies]
    Source: agents (bundle)
    What it does: Sets up security rules for Kubernetes server clusters, controlling which
    services can talk to each other and who is allowed to do what.
    When to use: You run apps on Kubernetes and need to tighten access and network isolation.
    Search terms: kubernetes, k8s, cluster security, network policy, rbac, container security,
    access control, server hardening, cloud security
    Original description: Implement Kubernetes security policies including NetworkPolicy,
    PodSecurityPolicy, and RBAC for production-grade security. Use when securing Kubernetes
    clusters, implementing network isolation, or enforcing pod security standards.

[mcp-implementation-security-review]
    Source: awesome-copilot
    What it does: Audits the source code of AI tool connectors (MCP servers and clients) for
    security weaknesses like missing authentication, weak input checks, and ways an attacker
    could run commands.
    When to use: You built or are adopting an MCP connector for an AI assistant and want its
    code checked for security problems.
    Search terms: mcp, mcp server, ai tool security, code audit, security review, claude tools,
    ai connector, authentication check, vulnerability scan
    Original description: Review the implementation source code of MCP (Model Context Protocol)
    servers, clients, and tool handlers against a security baseline — authentication, sessions,
    rate limiting, input-schema validation, official-SDK usage, RCE vectors, and the OWASP MCP
    Top 10 — producing a report with file/line evidence. Use this skill when: - Reviewing an MCP
    server implementation for security before release - Checking a server against the baseline
    controls (MCP-01 to MCP-05) and the OWASP MCP Top 10 - Auditing tools for RCE vectors
    (command/code injection, unsafe deserialization, path traversal, SSTI, depend…

[mcp-security-audit]
    Source: awesome-copilot
    What it does: Checks the configuration files that connect AI assistants to external tools
    for risks like hardcoded passwords, unsafe commands, and unpinned versions.
    When to use: You want to confirm your AI assistant's tool connections are configured safely
    before rolling them out.
    Search terms: mcp config, mcp json, ai tool settings, hardcoded secrets, security audit,
    claude setup, ai integrations, config review, leaked passwords
    Original description: Audit MCP (Model Context Protocol) server configurations for security
    issues. Use this skill when: - Reviewing .mcp.json files for security risks - Checking MCP
    server args for hardcoded secrets or shell injection patterns - Validating that MCP servers
    use pinned versions (not @latest) - Detecting unpinned dependencies in MCP server
    configurations - Auditing which MCP servers a project registers and whether they're on an
    approved list - Checking for environment variable usage vs. hardcoded credentials in MCP
    configs - Any request like "is my MCP config secure?", "audit my MCP servers", or "che…

[memory-forensics]
    Source: agents (bundle)
    What it does: Guides the analysis of a computer's memory snapshot to uncover running
    malware, hidden processes, and evidence after a security incident.
    When to use: Your computer may have been hacked and you need to investigate what was running
    on it.
    Search terms: memory forensics, malware analysis, hacked computer, incident response,
    volatility, ram dump, digital forensics, security investigation, cyber attack
    Original description: Master memory forensics techniques including memory acquisition,
    process analysis, and artifact extraction using Volatility and related tools. Use when
    analyzing memory dumps, investigating incidents, or performing malware analysis from RAM
    captures.

[mtls-configuration]
    Source: agents (bundle)
    What it does: Sets up mutual TLS so that internal services prove their identity to each
    other with certificates before exchanging data.
    When to use: You want your internal systems to only trust and talk to each other through
    verified, encrypted connections.
    Search terms: mtls, mutual tls, certificates, zero trust, encrypted connections, service
    security, ssl, internal network security, certificate management
    Original description: Configure mutual TLS (mTLS) for zero-trust service-to-service
    communication. Use when implementing zero-trust networking, certificate management, or
    securing internal service communication.

[protect-mcp-setup]
    Source: agents (bundle)
    What it does: Configures policy rules and tamper-proof signed receipts for every action an
    AI coding assistant takes, creating an audit trail for compliance.
    When to use: You need provable records of what your AI assistant did and want to block
    actions that break policy.
    Search terms: audit trail, ai governance, claude code policy, compliance evidence, signed
    receipts, cedar policy, agent controls, tool call logging, ai oversight
    Original description: Configure Cedar policy enforcement and Ed25519 signed receipts for
    Claude Code tool calls. Use when setting up projects that need cryptographic audit trails,
    policy-gated tool execution, or compliance-ready evidence of agent actions.

[protocol-reverse-engineering]
    Source: agents (bundle)
    What it does: Helps decode and document how devices or programs communicate over a network
    when no documentation exists, by analyzing captured traffic.
    When to use: You need to understand or connect to a system whose communication format is
    undocumented.
    Search terms: reverse engineering, network traffic, packet analysis, wireshark, proprietary
    protocol, decode messages, network debugging, undocumented api, sniffing
    Original description: Master network protocol reverse engineering including packet analysis,
    protocol dissection, and custom protocol documentation. Use when analyzing network traffic,
    understanding proprietary protocols, or debugging network communication.

[sast-configuration]
    Source: agents (bundle)
    What it does: Sets up automatic code-scanning tools that find security flaws in your
    software every time developers make changes.
    When to use: You want security problems caught automatically in code before they reach
    customers.
    Search terms: code scanning, sast, security scanner, automated security testing, devsecops,
    find vulnerabilities, static analysis, secure coding, ci security checks
    Original description: Configure Static Application Security Testing (SAST) tools for
    automated vulnerability detection in application code. Use when setting up security
    scanning, implementing DevSecOps practices, or automating code vulnerability detection.

[secret-scanning]
    Source: awesome-copilot
    What it does: Configures GitHub's secret scanning and push protection so passwords and API
    keys are caught before they get committed, and guides cleanup when one leaks.
    When to use: You want to stop developers from accidentally publishing passwords or keys in
    your code.
    Search terms: secret scanning, leaked api keys, github security, push protection, exposed
    passwords, credential leak, github advanced security, key rotation, code secrets
    Original description: Guide for configuring and managing GitHub secret scanning, push
    protection, custom patterns, and secret alert remediation. For pre-commit secret scanning in
    AI coding agents via the GitHub MCP Server, this skill references the Advanced Security
    plugin (`advanced-security@copilot-plugins`). Use this skill when enabling secret scanning,
    setting up push protection, defining custom patterns, triaging alerts, resolving blocked
    pushes, or when an agent needs to scan code for secrets before committing.

[secrets-management]
    Source: agents (bundle)
    What it does: Sets up secure storage and rotation of passwords, API keys, and certificates
    used by your build and deployment systems, using tools like Vault or AWS Secrets Manager.
    When to use: You need a safe way to store and rotate credentials your automated systems
    depend on.
    Search terms: secrets management, api keys, vault, aws secrets manager, password storage,
    credential rotation, ci cd secrets, secure credentials, key management
    Original description: Implement secure secrets management for CI/CD pipelines using Vault,
    AWS Secrets Manager, or native platform solutions. Use when handling sensitive credentials,
    rotating secrets, or securing CI/CD environments.

[security-and-hardening]
    Source: agent-skills
    What it does: Strengthens code against attacks whenever it handles user input, logins,
    stored data, or outside services, applying proven protections as features are built.
    When to use: You are building a feature that handles customer data or logins and want it
    secure from the start.
    Search terms: secure code, hardening, user input validation, login security, data
    protection, prevent hacking, secure by design, authentication, third party integrations
    Original description: Hardens code against vulnerabilities. Use when handling user input,
    authentication, data storage, or external integrations. Use when building any feature that
    accepts untrusted data, manages user sessions, or interacts with third-party services. Use
    when personal data or privacy compliance (GDPR, CCPA) is involved.

[security-auditor]
    Source: agent-playbook
    What it does: Audits code for the most common security weaknesses (the OWASP Top 10) such as
    injection attacks, broken access control, and exposed data.
    When to use: You want an expert-style security check of your application's code.
    Search terms: security audit, owasp, vulnerability check, code security, penetration
    testing, find security bugs, app security, sql injection, security review
    Original description: Security vulnerability expert covering OWASP Top 10 and common
    security issues. Use when conducting security audits or reviewing code for vulnerabilities.

[security-requirement-extraction]
    Source: agents (bundle)
    What it does: Turns identified threats and business context into concrete security
    requirements, user stories, and test cases your team can build against.
    When to use: You know the risks your system faces and need them written up as clear,
    buildable requirements.
    Search terms: security requirements, threat model, security user stories, compliance
    requirements, risk to requirements, security testing, security planning, acceptance criteria
    Original description: Derive security requirements from threat models and business context.
    Use when translating threats into actionable requirements, creating security user stories,
    or building security test cases.

[security-review]
    Source: awesome-copilot
    What it does: Scans an entire codebase the way a security researcher would, tracing how data
    moves through the system to find vulnerabilities that simple pattern-matching tools miss.
    When to use: You want a deep security scan of your software before launch or after a scare.
    Search terms: security scan, codebase security, vulnerability hunt, data flow, security
    researcher, find exploits, app security check, security assessment, code audit
    Original description: AI-powered codebase security scanner that reasons about code like a
    security researcher — tracing data flows, understanding component interactions, and catching
    vulnerabilities that pattern-matching tools miss. Use this skill when asked to scan code for
    security vulnerabilities, find bugs, check for SQL injection, XSS, command injection,
    exposed API keys, hardcoded secrets, insecure dependencies, access control issues, or any
    request like "is my code secure?", "review for security issues", "audit this codebase", or
    "check for vulnerabilities". Covers injection flaws, authentication and access …

[session-guard]
    Source: agents (bundle)
    What it does: Keeps an AI assistant on track during long, complex work sessions by catching
    when it starts ignoring earlier rules or its output quality slips.
    When to use: Your AI assistant has been working a long time and seems to be drifting from
    instructions.
    Search terms: ai drift, long session, keep ai on track, quality degradation, context loss,
    agent consistency, follow the rules, claude memory, compaction
    Original description: Use when working on complex multi-step tasks, when a session is
    getting long (40+ tool calls), when the agent starts ignoring rules it followed earlier,
    when conventions drift, when output quality seems to degrade, or after any context
    compaction event. Prevents long-session corruption AND context compaction amnesia through
    behavioral self-enforcement.

[signed-audit-trails-recipe]
    Source: agents (bundle)
    What it does: Walks through, step by step, how cryptographically signed audit logs for AI
    assistant actions work, so you can evaluate the approach before adopting it.
    When to use: You are considering tamper-proof logging of AI actions and want to understand
    it before committing.
    Search terms: audit log, signed records, ai accountability, compliance, tamper proof, cedar
    policy, claude code hooks, tutorial, proof of actions
    Original description: Step-by-step cookbook for setting up cryptographically signed audit
    trails on Claude Code tool calls. Use when explaining, evaluating, or demonstrating the
    pattern before committing to the protect-mcp runtime hooks. Covers Cedar policy, Ed25519
    receipts, offline verification, tamper detection, CI/CD integration, and SLSA composition.

[solidity-security]
    Source: agents (bundle)
    What it does: Applies smart-contract security best practices to prevent common blockchain
    vulnerabilities when writing or auditing Solidity code.
    When to use: You are building or reviewing an Ethereum smart contract and want to avoid
    costly exploits.
    Search terms: solidity, smart contract, blockchain security, ethereum, crypto audit,
    reentrancy, web3, defi security, contract audit
    Original description: Master smart contract security best practices to prevent common
    vulnerabilities and implement secure Solidity patterns. Use when writing smart contracts,
    auditing existing contracts, or implementing security measures for blockchain applications.

[stride-analysis-patterns]
    Source: agents (bundle)
    What it does: Uses the STRIDE method to systematically list the ways a system could be
    attacked, from spoofing and tampering to data leaks and denial of service.
    When to use: You want a structured way to brainstorm what could go wrong security-wise in a
    system.
    Search terms: threat modeling, stride, security risks, what could go wrong, attack
    scenarios, security planning, risk analysis, security documentation
    Original description: Apply STRIDE methodology to systematically identify threats. Use when
    analyzing system security, conducting threat modeling sessions, or creating security
    documentation.

[threat-mitigation-mapping]
    Source: agents (bundle)
    What it does: Matches each identified security threat to the controls and fixes that address
    it, helping prioritize where to spend security effort.
    When to use: You have a list of threats and need to decide which protections to invest in
    first.
    Search terms: security controls, mitigation plan, threat mapping, risk prioritization,
    remediation plan, security budget, which fixes first, security roadmap
    Original description: Map identified threats to appropriate security controls and
    mitigations. Use when prioritizing security investments, creating remediation plans, or
    validating control effectiveness.

[threat-model-analyst]
    Source: awesome-copilot
    What it does: Produces a full threat model of a software system, including architecture
    overviews, data-flow diagrams, a ranked list of threats, and recommended fixes, and can
    update it as the system changes.
    When to use: You need a complete security risk analysis of an application, either fresh or
    refreshed after changes.
    Search terms: threat model, stride, security analysis, data flow diagram, risk report,
    architecture review, security assessment, app risks, prioritized threats
    Original description: Full STRIDE-A threat model analysis and incremental update skill for
    repositories and systems. Supports two modes: (1) Single analysis — full STRIDE-A threat
    model of a repository, producing architecture overviews, DFD diagrams, STRIDE-A analysis,
    prioritized findings, and executive assessments. (2) Incremental analysis — takes a previous
    threat model report as baseline, compares the codebase at the latest (or a given commit),
    and produces an updated report with change tracking (new, resolved, still-present threats),
    STRIDE heatmap, findings diff, and an embedded HTML comparison. Only activate…

[tm7-threat-model]
    Source: awesome-copilot
    What it does: Creates threat model files that open in Microsoft's Threat Modeling Tool, so
    security analysis can be shared in the standard format.
    When to use: Your team uses Microsoft Threat Modeling Tool and you need a model file
    generated or updated.
    Search terms: microsoft threat modeling tool, tm7, threat model file, stride, security
    diagram, microsoft security, threat modeling, security documentation
    Original description: Creates valid Microsoft Threat Modeling Tool (.tm7) files compatible
    with the Microsoft Threat Modeling Tool v7.3+. Use this skill whenever asked to create,
    generate, or modify a .tm7 threat model file, or when performing STRIDE threat modeling that
    should output a .tm7 file that opens cleanly in the Microsoft Threat Modeling Tool.
