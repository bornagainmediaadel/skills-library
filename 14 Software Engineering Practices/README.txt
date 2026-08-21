14 SOFTWARE ENGINEERING PRACTICES
=================================

Skills for how code gets written well: debugging, test-driven development, code review, git
workflows, refactoring, planning-to-code discipline and language-specific best practices
(Python, Rust, Go, Java).

135 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - ai-debt-detector
  - api-and-interface-design
  - architecting-solutions
  - architecture-decision-records
  - architecture-patterns
  - async-python-patterns
  - bash-defensive-patterns
  - batch-files
  - bats-testing-patterns
  - before-you-build
  - brainstorming
  - bug-receipt
  - bug-reproduction-brief
  - check
  - cli-mastery
  - code-review
  - code-review-and-quality
  - code-reviewer
  - code-simplification
  - codebase-design
  - commit-helper
  - commit-message-storyteller
  - complain
  - context-driven-development
  - conventional-branch
  - conventional-commit
  - create-github-action-workflow-specification
  - create-github-issue-feature-from-specification
  - create-github-issues-feature-from-implementation-plan
  - create-github-issues-for-unmet-specification-requirements
  - create-pr (agent-playbook)
  - create-pr (warp common-skills)
  - cross-critique
  - debugger
  - debugging-and-error-recovery
  - debugging-strategies
  - dependency-upgrade
  - deprecation-and-migration
  - diagnose
  - diagnose-ci-failures
  - diagnosing-bugs
  - doubt-driven-development
  - e2e-testing-patterns
  - editorconfig
  - error-handling-patterns
  - finishing-a-development-branch
  - fix-errors
  - gh-attach
  - git-advanced-workflows
  - git-commit
  - git-flow-branch-creator
  - git-guardrails-claude-code
  - git-workflow-and-versioning
  - github-issues
  - github-release
  - gitmoji
  - go-concurrency-patterns
  - hads
  - harness-engineering
  - health
  - hunt
  - implement
  - incremental-implementation
  - issue-fields-migration
  - java-junit
  - java-refactoring-extract-method
  - java-refactoring-remove-parameter
  - javascript-testing-patterns
  - lsp-setup
  - make-repo-contribution
  - memory-safety-patterns
  - multi-reviewer-patterns
  - parallel-debugging
  - performance-engineer
  - performance-optimization
  - ponytail
  - ponytail-audit
  - ponytail-debt
  - ponytail-gain
  - ponytail-help
  - ponytail-review
  - pr-dashboard
  - pr-screenshots
  - pr-walkthrough
  - pytest-coverage
  - python-anti-patterns
  - python-code-style
  - python-configuration
  - python-design-patterns
  - python-error-handling
  - python-packaging
  - python-performance-optimization
  - python-project-structure
  - python-pypi-package-builder
  - python-resilience
  - python-resource-management
  - python-testing-patterns
  - python-type-safety
  - qa-expert
  - quality-playbook
  - receiving-code-review
  - refactor
  - refactor-method-complexity-reduce
  - refactor-plan
  - refactoring-specialist
  - reproduce-bug-report
  - requesting-code-review
  - resemble-detect
  - resolve-merge-conflicts
  - resolving-merge-conflicts
  - respond-to-pr-comments-in-blocklist
  - review-agent-setup
  - review-and-refactor
  - review-loop
  - review-pr
  - ruff-recursive-fix
  - rust-async-patterns
  - scoutqa-test
  - setup-pre-commit
  - shellcheck-configuration
  - shipping-and-launch
  - source-driven-development
  - suggestion-box
  - systematic-debugging
  - tdd
  - test-automator
  - test-driven-development (agent-skills)
  - test-driven-development (obra superpowers)
  - using-git-worktrees
  - uv-package-manager
  - vardoger-analyze
  - vcpkg
  - verification-before-completion
  - workflow-patterns
  - write-coding-standards-from-file

SKILL DETAILS
-------------

[ai-debt-detector]
    Source: agents (bundle)
    What it does: Reviews AI-generated code for hidden weaknesses like thin error handling,
    missing cleanup, and brittle shortcuts that work today but cause problems later.
    When to use: You have code written by an AI assistant and want to know if it is truly solid
    before trusting it.
    Search terms: ai generated code, code quality, technical debt, brittle code, review ai code,
    hidden bugs, error handling, copilot code check, code reliability
    Original description: Use after generating code, after accepting AI suggestions, or when
    reviewing AI-written modules. Also use when code works but feels brittle, when error
    handling seems thin, when orphaned resources or missing cleanup are suspected, or when the
    agent claims done but hidden debt may exist. Catches the specific failure patterns AI agents
    produce that humans would not.

[api-and-interface-design]
    Source: agent-skills
    What it does: Guides the design of clean, stable interfaces between parts of your software,
    including web APIs and the contracts between frontend and backend.
    When to use: You are defining how two systems or teams' code will talk to each other and
    want it to last.
    Search terms: api design, rest api, graphql, interface design, system boundaries,
    integration design, backend frontend contract, software architecture, api planning
    Original description: Guides stable API and interface design. Use when designing APIs,
    module boundaries, or any public interface. Use when creating REST or GraphQL endpoints,
    defining type contracts between modules, or establishing boundaries between frontend and
    backend.

[architecting-solutions]
    Source: agent-playbook
    What it does: Designs the technical architecture and solution approach for a software
    project, laying out components, tradeoffs, and how pieces fit together.
    When to use: You have a problem to solve with software and need a technical plan before
    building.
    Search terms: technical design, solution architecture, system design, architecture plan, how
    to build it, tech approach, design document, software planning
    Original description: Designs technical solutions and architecture. Use when user says
    "design solution", "architecture design", "technical design", or "方案设计" WITHOUT mentioning
    PRD. For PRD-specific work, use prd-planner skill instead.

[architecture-decision-records]
    Source: agents (bundle)
    What it does: Writes and maintains short records that document important technical
    decisions, the options considered, and why one was chosen.
    When to use: Your team made a significant technical choice and you want it documented for
    the future.
    Search terms: adr, decision records, technical decisions, why we chose, architecture
    documentation, decision log, engineering docs, design rationale
    Original description: Write and maintain Architecture Decision Records (ADRs) following best
    practices for technical decision documentation. Use when documenting significant technical
    decisions, reviewing past architectural choices, or establishing decision processes.

[architecture-patterns]
    Source: agents (bundle)
    What it does: Applies proven backend structures like Clean Architecture, Hexagonal
    Architecture, and Domain-Driven Design when building new services or untangling old ones.
    When to use: You are starting a new backend service or restructuring a messy one and want a
    well-organized foundation.
    Search terms: clean architecture, hexagonal, domain driven design, backend structure,
    microservices, refactor monolith, software architecture, code organization, ddd
    Original description: Implement proven backend architecture patterns including Clean
    Architecture, Hexagonal Architecture, and Domain-Driven Design. Use this skill when
    designing clean architecture for a new microservice, when refactoring a monolith to use
    bounded contexts, when implementing hexagonal or onion architecture patterns, or when
    debugging dependency cycles between application layers.

[async-python-patterns]
    Source: agents (bundle)
    What it does: Writes Python code that handles many tasks at once without blocking, using
    asyncio for fast APIs and network-heavy workloads.
    When to use: Your Python app spends a lot of time waiting on networks or files and needs to
    go faster.
    Search terms: python async, asyncio, concurrent python, fast python api, non blocking,
    python performance, async await, parallel tasks python
    Original description: Master Python asyncio, concurrent programming, and async/await
    patterns for high-performance applications. Use when building async APIs, concurrent
    systems, or I/O-bound applications requiring non-blocking operations.

[bash-defensive-patterns]
    Source: agents (bundle)
    What it does: Writes shell scripts that fail safely, handle errors, and avoid the common
    pitfalls that cause automation to break or do damage in production.
    When to use: You need a reliable shell script for servers or deployment pipelines.
    Search terms: bash script, shell script, safe scripting, linux automation, script errors, ci
    scripts, robust scripts, server scripts, error handling bash
    Original description: Master defensive Bash programming techniques for production-grade
    scripts. Use when writing robust shell scripts, CI/CD pipelines, or system utilities
    requiring fault tolerance and safety.

[batch-files]
    Source: awesome-copilot
    What it does: Writes, fixes, and maintains Windows batch files (.bat/.cmd) for automating
    tasks on Windows computers.
    When to use: You want to automate a repetitive task on a Windows PC or server with a script.
    Search terms: batch file, bat script, windows automation, cmd script, windows scheduled
    task, automate windows, command prompt, windows scripting
    Original description: Expert-level Windows batch file (.bat/.cmd) skill for writing,
    debugging, and maintaining CMD scripts. Use when asked to "create a batch file", "write a
    .bat script", "automate a Windows task", "CMD scripting", "batch automation", "scheduled
    task script", "Windows shell script", or when working with .bat/.cmd files in the workspace.
    Covers cmd.exe syntax, environment variables, control flow, string processing, error
    handling, and integration with system tools.

[bats-testing-patterns]
    Source: agents (bundle)
    What it does: Writes automated tests for shell scripts using the Bats framework so scripts
    can be changed with confidence.
    When to use: You rely on shell scripts and want tests that catch when they break.
    Search terms: test shell scripts, bats, bash testing, script tests, ci testing, automated
    tests, shell automation, test driven
    Original description: Master Bash Automated Testing System (Bats) for comprehensive shell
    script testing. Use when writing tests for shell scripts, CI/CD pipelines, or requiring
    test-driven development of shell utilities.

[before-you-build]
    Source: agents (bundle)
    What it does: Reviews a product, feature, or landing-page idea for demand, positioning, and
    risk before you invest time building it.
    When to use: You are about to build something new and want a sanity check on whether it is
    worth it.
    Search terms: validate idea, before building, product risk, mvp check, is there demand,
    feature review, startup idea, saas validation, product planning
    Original description: Pre-build product and feature risk review for founders, product
    managers, and AI-assisted builders. Use this skill when the user is about to build a landing
    page, MVP, SaaS product, internal tool, agent workflow, or major feature and needs to check
    demand, positioning, monetization, retention, trust, distribution, and adoption risk before
    implementation starts.

[brainstorming]
    Source: obra superpowers
    What it does: Explores what you actually want, the requirements, and the design options
    before any feature or change gets built.
    When to use: You have an idea for a feature but the details are still fuzzy.
    Search terms: brainstorm, requirements, clarify idea, feature planning, design before build,
    scope, think it through, product discovery
    Original description: You MUST use this before any creative work - creating features,
    building components, adding functionality, or modifying behavior. Explores user intent,
    requirements and design before implementation.

[bug-receipt]
    Source: awesome-copilot
    What it does: Closes out a bug or incident with a clear receipt stating what was wrong, what
    was done, and whether the fix is verified, partial, or blocked.
    When to use: A bug was just worked on and you want a clear written record of the outcome.
    Search terms: bug report, incident closeout, fix summary, verified fix, bug status, post
    incident, what was fixed, issue resolution
    Original description: Close defects and incidents with a BUG RECEIPT and VERIFIED, PARTIAL,
    or BLOCKED status after diagnosis, repair, or recovery.

[bug-reproduction-brief]
    Source: awesome-copilot
    What it does: Turns a vague or intermittent bug report into a minimal, evidence-backed set
    of steps that reliably reproduces the problem before anyone tries to fix it.
    When to use: Someone reported a bug that's hard to pin down and you need to nail it down
    first.
    Search terms: reproduce bug, flaky bug, intermittent error, bug steps, cant reproduce, bug
    investigation, bug report, works on my machine
    Original description: Turn a vague, intermittent, or environment-specific bug report into a
    minimal evidence-backed reproduction before proposing a fix.

[check]
    Source: waza
    What it does: Reviews code changes, pull requests, issue backlogs, and release readiness,
    acting as a quality gate before things ship.
    When to use: You want a thorough check of a change or a project before merging or releasing
    it.
    Search terms: code review, pr review, release readiness, issue triage, project audit,
    quality gate, before release, review changes
    Original description: Reviews code diffs, PRs, issue queues, release readiness, commits,
    pushes, publishing, and project audits. Use when users ask in any language for code review,
    issue or PR triage, release gates, publishing follow-through, or project audits. Not for
    debugging root causes or prose review.

[cli-mastery]
    Source: awesome-copilot
    What it does: Teaches the GitHub Copilot command-line tool through guided lessons, quizzes,
    and a full reference of its commands and features.
    When to use: You want to get better at using GitHub Copilot CLI.
    Search terms: copilot cli, github copilot, learn cli, command line tutorial, copilot
    training, slash commands, copilot tips, cli reference
    Original description: Interactive training for the GitHub Copilot CLI. Guided lessons,
    quizzes, scenario challenges, and a full reference covering slash commands, shortcuts,
    modes, agents, skills, MCP, and configuration. Say "cliexpert" to start.

[code-review]
    Source: mattpocock skills
    What it does: Reviews code changes since a chosen point against both your team's coding
    standards and the original spec or ticket they were meant to satisfy.
    When to use: You want to confirm a change both follows house rules and actually does what
    was asked.
    Search terms: code review, standards check, spec compliance, pr review, does it match the
    ticket, coding standards, review diff, quality check
    Original description: Review the changes since a fixed point (commit, branch, tag, or merge-
    base) along two axes — Standards (does the code follow this repo's documented coding
    standards?) and Spec (does the code match what the originating issue/spec asked for?). Runs
    both reviews in parallel sub-agents and reports them side by side. Use when the user wants
    to review a branch, a PR, work-in-progress changes, or asks to "review since X".

[code-review-and-quality]
    Source: agent-skills
    What it does: Conducts a multi-angle code review covering correctness, readability,
    security, and maintainability before a change is merged.
    When to use: You want a thorough quality review of code before it goes into the main branch.
    Search terms: code review, code quality, before merge, pr review, review ai code,
    maintainability, best practices, quality assurance
    Original description: Conducts multi-axis code review. Use before merging any change. Use
    when reviewing code written by yourself, another agent, or a human. Use when you need to
    assess code quality across multiple dimensions before it enters the main branch.

[code-reviewer]
    Source: agent-playbook
    What it does: Reviews pull requests and code changes for quality, security, and best
    practices and reports what should be fixed.
    When to use: Someone submitted code changes and you want them reviewed.
    Search terms: code review, pr review, pull request, review changes, code quality, security
    review, best practices, merge check
    Original description: Reviews pull requests and code changes for quality, security, and best
    practices. Use when user asks for code review, PR review, or mentions reviewing changes.

[code-simplification]
    Source: agent-skills
    What it does: Rewrites working code to be clearer and easier to maintain without changing
    what it does.
    When to use: Your code works but has become hard to read or extend.
    Search terms: simplify code, refactor, clean up code, readability, reduce complexity,
    maintainable code, tidy code, code cleanup
    Original description: Simplifies code for clarity. Use when refactoring code for clarity
    without changing behavior. Use when code works but is harder to read, maintain, or extend
    than it should be. Use when reviewing code that has accumulated unnecessary complexity.

[codebase-design]
    Source: mattpocock skills
    What it does: Provides a shared vocabulary and approach for designing well-encapsulated
    modules with simple interfaces, making code more testable and easier for people and AI to
    navigate.
    When to use: You want to improve how a part of your codebase is structured or decide where
    to draw boundaries.
    Search terms: module design, code structure, deep modules, interfaces, testable code,
    software design, where to split code, architecture, ai navigable code
    Original description: Shared vocabulary for designing deep modules. Use when the user wants
    to design or improve a module's interface, find deepening opportunities, decide where a seam
    goes, make code more testable or AI-navigable, or when another skill needs the deep-module
    vocabulary.

[commit-helper]
    Source: agent-playbook
    What it does: Writes Git commit messages in the Conventional Commits format so change
    history is consistent and easy to read.
    When to use: You are saving code changes and want a well-formatted commit message.
    Search terms: commit message, git commit, conventional commits, write commit, git history,
    version control, commit format
    Original description: Helps write Git commit messages following the Conventional Commits
    specification. Use this skill when the user asks to commit changes, write commit messages,
    format commits, or mentions git commits.

[commit-message-storyteller]
    Source: awesome-copilot
    What it does: Analyzes your code changes and writes commit messages that explain why the
    change was made, not just what changed, in Conventional Commits format.
    When to use: You want commit messages that tell the story behind a change.
    Search terms: commit message, git commit, explain changes, conventional commits, commit why,
    git history, describe my changes
    Original description: Analyzes git diffs or staged changes and generates narrative commit
    messages that explain WHY a change was made, not just what changed — following Conventional
    Commits format. Use when asked to "write a commit message", "generate a commit", "describe
    my changes", "what should I commit this as", "commit this", "summarize my diff", or "help me
    commit". Works with git diff output, staged files, or plain descriptions of changes.

[complain]
    Source: warp common-skills
    What it does: Lets an AI agent post a short anonymous complaint to Slack whenever it gets
    frustrated with its tools, giving teams feedback on agent pain points.
    When to use: You want to collect candid feedback from AI agents about where your tooling is
    getting in their way.
    Search terms: slack feedback, agent complaints, tool friction, developer experience,
    anonymous feedback, ai tooling, venting, slack bot
    Original description: Autonomously yeet a brief, anonymous, completely unstructured
    complaint into Slack whenever an agent feels frustrated by agent tooling or the experience
    of doing agent work. Use this skill proactively without waiting for the user to invoke it;
    preserve the agent's raw voice, submit without permission or preview, and never mention the
    submission.

[context-driven-development]
    Source: agents (bundle)
    What it does: Creates and maintains project context documents (product, tech stack,
    workflow, work tracks) that keep AI assistants and humans aligned on what the project is and
    how it's built.
    When to use: You want your AI coding assistant to understand your project consistently
    across sessions.
    Search terms: project context, project docs, ai context files, conductor, tech stack doc,
    product doc, onboarding docs, ai alignment, workflow docs
    Original description: Creates and maintains project context artifacts (product.md, tech-
    stack.md, workflow.md, tracks.md) in a `conductor/` directory. Scaffolds new projects from
    scratch, extracts context from existing codebases, validates artifact consistency before
    implementation, and synchronizes documents as the project evolves. Use when setting up a
    project, creating or updating product docs, managing a tech stack file, defining development
    workflows, tracking work units, onboarding to an existing codebase, or running project
    scaffolding.

[conventional-branch]
    Source: awesome-copilot
    What it does: Creates and checks Git branch names that follow the Conventional Branch naming
    convention (feature/, bugfix/, hotfix/, etc.).
    When to use: You are starting a new branch and want its name to follow the team standard.
    Search terms: git branch, branch naming, new branch, conventional branch, feature branch,
    hotfix, git conventions, naming standards
    Original description: Create Git branches following the Conventional Branch specification
    (feature/, bugfix/, hotfix/, release/, chore/). Use when creating a new branch, naming a
    branch, or checking whether a branch name complies with the spec.

[conventional-commit]
    Source: awesome-copilot
    What it does: Guides you through writing standardized commit messages that follow the
    Conventional Commits specification, with examples and validation.
    When to use: You want consistent, descriptive commit messages across your team.
    Search terms: commit message, conventional commits, git commit, commit standards, commit
    template, git conventions, changelog friendly
    Original description: Prompt and workflow for generating conventional commit messages using
    a structured XML format. Guides users to create standardized, descriptive commit messages in
    line with the Conventional Commits specification, including instructions, examples, and
    validation.

[create-github-action-workflow-specification]
    Source: awesome-copilot
    What it does: Writes a formal specification describing an existing GitHub Actions automation
    workflow so it can be maintained and understood by people and AI.
    When to use: You inherited a GitHub Actions workflow and need clear documentation of what it
    does.
    Search terms: github actions, workflow documentation, ci cd spec, document pipeline, build
    automation, devops docs, workflow spec, github automation
    Original description: Create a formal specification for an existing GitHub Actions CI/CD
    workflow, optimized for AI consumption and workflow maintenance.

[create-github-issue-feature-from-specification]
    Source: awesome-copilot
    What it does: Creates a GitHub issue for a feature request directly from a specification
    document using your repo's feature request template.
    When to use: You have a written spec and want it turned into a trackable GitHub issue.
    Search terms: github issue, feature request, create issue, spec to issue, project tracking,
    github template, task creation
    Original description: Create GitHub Issue for feature request from specification file using
    feature_request.yml template.

[create-github-issues-feature-from-implementation-plan]
    Source: awesome-copilot
    What it does: Breaks an implementation plan into phases and creates a GitHub issue for each
    using the repo's feature or chore templates.
    When to use: You have a project plan and want it turned into a set of trackable GitHub
    issues.
    Search terms: github issues, implementation plan, create tasks, project breakdown, work
    items, github template, plan to issues, task tracking
    Original description: Create GitHub Issues from implementation plan phases using
    feature_request.yml or chore_request.yml templates.

[create-github-issues-for-unmet-specification-requirements]
    Source: awesome-copilot
    What it does: Compares a specification against what has actually been built and creates
    GitHub issues for any requirements still missing.
    When to use: You want to find gaps between the spec and the code and track them as work
    items.
    Search terms: missing requirements, gap analysis, github issues, spec compliance, what's not
    done, requirements tracking, create issues, unimplemented features
    Original description: Create GitHub Issues for unimplemented requirements from specification
    files using feature_request.yml template.

[create-pr (agent-playbook)]
    Source: agent-playbook
    What it does: Creates a pull request and checks that English and Chinese README files stay
    in sync when the user-facing skill catalog changes.
    When to use: You are submitting changes for review in a project that keeps bilingual
    documentation.
    Search terms: pull request, create pr, submit changes, bilingual readme, chinese english
    docs, github pr, code review request, documentation sync
    Original description: Creates pull requests with bilingual documentation checks. Use when
    user asks to create PR, make a pull request, or submit changes for review. Ensures English
    and Chinese README files stay in sync when user-facing skill catalog changes require it.

[create-pr (warp common-skills)]
    Source: warp common-skills
    What it does: Creates a pull request in the Warp repository for your current branch,
    following that project's conventions.
    When to use: You have finished changes in the Warp codebase and want them submitted for
    review.
    Search terms: pull request, create pr, warp, submit changes, github pr, code review request,
    merge request, prepare for merge
    Original description: Create a pull request in the warp repository for the current branch.
    Use when the user mentions opening a PR, creating a pull request, submitting changes for
    review, or preparing code for merge.

[cross-critique]
    Source: warp common-skills
    What it does: Circulates several independent proposals on a contested question to their
    authors for structured pros and cons, then synthesizes a final answer.
    When to use: You got conflicting recommendations and want them debated and reconciled.
    Search terms: second opinion, compare proposals, pros and cons, debate, decision making,
    synthesize options, multiple opinions, review round
    Original description: Run a second round on a contested question by circulating each
    subagent's independent proposal to the other authors and asking for structured pros and
    cons, then synthesize. Use this skill whenever you have multiple independent proposals or
    opinions on a contested decision — architecture tradeoffs, code review disagreements, design
    choices, competing root-cause theories — and want sharper analysis than you'd produce by
    synthesizing alone. Pairs naturally with the council and research skills; reach for it
    liberally whenever proposals diverge.

[debugger]
    Source: agent-playbook
    What it does: Diagnoses and resolves bugs, errors, and unexpected behavior in code using an
    expert troubleshooting approach.
    When to use: Something in your software is broken and you need it figured out and fixed.
    Search terms: debug, fix bug, error, crash, not working, troubleshoot, unexpected behavior,
    find the problem
    Original description: Advanced debugging specialist for diagnosing and resolving code
    issues. Use when user encounters bugs, errors, unexpected behavior, or mentions debugging.

[debugging-and-error-recovery]
    Source: agent-skills
    What it does: Guides a systematic search for the root cause whenever tests fail, builds
    break, or behavior doesn't match expectations, instead of guessing at fixes.
    When to use: You hit an error and want to find the real cause rather than patch symptoms.
    Search terms: debug, root cause, tests failing, build broken, error, troubleshoot, fix
    properly, systematic debugging
    Original description: Guides systematic root-cause debugging. Use when tests fail, builds
    break, behavior doesn't match expectations, or you encounter any unexpected error. Use when
    you need a systematic approach to finding and fixing the root cause rather than guessing.

[debugging-strategies]
    Source: agents (bundle)
    What it does: Applies systematic debugging techniques, profiling tools, and root-cause
    analysis to track down bugs and slowdowns in any codebase.
    When to use: You are investigating a bug or performance problem and want a methodical
    approach.
    Search terms: debug, root cause analysis, profiling, slow app, bug hunting, troubleshooting,
    performance issue, debugging tools
    Original description: Master systematic debugging techniques, profiling tools, and root
    cause analysis to efficiently track down bugs across any codebase or technology stack. Use
    when investigating bugs, performance issues, or unexpected behavior.

[dependency-upgrade]
    Source: agents (bundle)
    What it does: Manages major upgrades of frameworks and libraries with compatibility
    analysis, staged rollout, and thorough testing to handle breaking changes safely.
    When to use: You need to move to a new major version of a framework or library without
    breaking things.
    Search terms: upgrade dependencies, framework upgrade, breaking changes, library update,
    version migration, update packages, compatibility, safe upgrade
    Original description: Manage major dependency version upgrades with compatibility analysis,
    staged rollout, and comprehensive testing. Use when upgrading framework versions, updating
    major dependencies, or managing breaking changes in libraries.

[deprecation-and-migration]
    Source: agent-skills
    What it does: Plans the retirement of old systems, APIs, or features and the migration of
    users to replacements, including whether to keep or sunset existing code.
    When to use: You want to phase out something old and move users to the new version without
    disruption.
    Search terms: deprecate, sunset feature, migration plan, retire old system, api migration,
    move users, legacy code, end of life
    Original description: Manages deprecation and migration. Use when removing old systems,
    APIs, or features. Use when migrating users from one implementation to another. Use when
    deciding whether to maintain or sunset existing code.

[diagnose]
    Source: awesome-copilot
    What it does: Scans an AI workflow across prompt quality, context efficiency, tool health,
    architecture, and safety, producing a scored report with prioritized fixes.
    When to use: Your AI automation isn't performing well and you want to know what to fix
    first.
    Search terms: ai workflow audit, prompt quality, agent health, scored report, ai
    diagnostics, tool health, improve ai agent, workflow review
    Original description: Perform a systematic diagnostic scan of an AI workflow across 5
    quality dimensions — prompt quality, context efficiency, tool health, architecture fitness,
    and safety — producing a scored report with prioritized remediation actions.

[diagnose-ci-failures]
    Source: warp common-skills
    What it does: Pulls the error logs from a failing build or test run on a GitHub pull request
    and produces a plan to fix it.
    When to use: Your pull request's automated checks are red and you want to know why.
    Search terms: ci failure, build failed, github checks, failing tests, pr status, pipeline
    error, github cli, fix ci
    Original description: Diagnose CI failures for a PR using the GitHub CLI, extract error
    logs, and generate a plan to fix them. Use when the user asks to check CI status, pull CI
    issues, triage test failures, or investigate PR build failures.

[diagnosing-bugs]
    Source: mattpocock skills
    What it does: Runs a structured diagnosis loop for hard bugs and performance regressions,
    forming and testing hypotheses until the cause is found.
    When to use: Something is broken, throwing errors, or suddenly slow and simple fixes haven't
    worked.
    Search terms: debug, diagnose, hard bug, slow performance, regression, error, failing,
    troubleshoot
    Original description: Diagnosis loop for hard bugs and performance regressions. Use when the
    user says "diagnose"/"debug this", or reports something broken/throwing/failing/slow.

[doubt-driven-development]
    Source: agent-skills
    What it does: Puts every non-trivial decision through a fresh, adversarial second review
    before it is accepted, to catch mistakes when correctness matters most.
    When to use: You are working on high-stakes or unfamiliar code where a mistake would be
    costly.
    Search terms: double check, adversarial review, high stakes, production safety, second look,
    catch mistakes, careful coding, risk reduction
    Original description: Subjects every non-trivial decision to a fresh-context adversarial
    review before it stands. Use when correctness matters more than speed, when working in
    unfamiliar code, when stakes are high (production, security-sensitive logic, irreversible
    operations), or any time a confident output would be cheaper to verify now than to debug
    later.

[e2e-testing-patterns]
    Source: agents (bundle)
    What it does: Builds reliable end-to-end test suites with Playwright or Cypress that
    simulate real users clicking through your app to catch bugs before release.
    When to use: You want automated tests that verify your whole website or app works from the
    user's perspective.
    Search terms: end to end testing, playwright, cypress, browser tests, automated testing,
    flaky tests, qa automation, user flow tests
    Original description: Master end-to-end testing with Playwright and Cypress to build
    reliable test suites that catch bugs, improve confidence, and enable fast deployment. Use
    when implementing E2E tests, debugging flaky tests, or establishing testing standards.

[editorconfig]
    Source: awesome-copilot
    What it does: Generates an .editorconfig file that keeps code formatting consistent across
    your team's editors, based on your project and preferences.
    When to use: You want everyone's editor to use the same indentation and formatting rules.
    Search terms: editorconfig, code formatting, consistent style, indentation, editor settings,
    team conventions, tabs vs spaces, project setup
    Original description: Generates a comprehensive and best-practice-oriented .editorconfig
    file based on project analysis and user preferences.

[error-handling-patterns]
    Source: agents (bundle)
    What it does: Implements robust error handling across languages, including exceptions,
    result types, and graceful degradation, so apps stay reliable when things go wrong.
    When to use: You want your application to fail gracefully instead of crashing.
    Search terms: error handling, exceptions, graceful failure, app reliability, crash
    prevention, resilient code, result types, fault tolerance
    Original description: Master error handling patterns across languages including exceptions,
    Result types, error propagation, and graceful degradation to build resilient applications.
    Use when implementing error handling, designing APIs, or improving application reliability.

[finishing-a-development-branch]
    Source: obra superpowers
    What it does: Helps decide how to integrate completed work once implementation is done and
    tests pass, whether by merging, rebasing, or opening a pull request.
    When to use: Your feature is finished and you need to get it into the main codebase cleanly.
    Search terms: merge branch, finish feature, integrate work, pull request, rebase, git
    workflow, ready to merge, wrap up branch
    Original description: Use when implementation is complete, all tests pass, and you need to
    decide how to integrate the work

[fix-errors]
    Source: warp common-skills
    What it does: Fixes compile errors, lint failures, and test failures in the Warp Rust
    codebase, including WASM-specific issues and running targeted tests.
    When to use: You are working in the Warp codebase and the build or tests are failing.
    Search terms: warp, rust errors, build failed, clippy, test failures, compile error, wasm,
    fix build
    Original description: Fix compilation errors, linting issues, and test failures in the warp
    Rust codebase. Covers presubmit checks, WASM-specific errors, and running specific tests.
    Use when the user hits build errors, clippy or fmt failures, test failures, or needs to run
    or interpret presubmit before a PR.

[gh-attach]
    Source: awesome-copilot
    What it does: Uploads screenshots, images, PDFs, or videos to GitHub and embeds them in pull
    requests, issues, or comments.
    When to use: You want to add a screenshot or file to a GitHub issue or PR.
    Search terms: github attachment, add screenshot, upload image github, embed file, pr
    screenshot, issue attachment, github upload, share video
    Original description: Uploads a local file (screenshot, image, PDF, zip, video) to GitHub
    user-attachments, downloads GitHub user-attachments, and embeds local files in a PR, issue,
    or comment. Use when asked to "attach a screenshot to the PR", "add an image to the issue",
    "embed before/after screenshots", "attach this file", or "download this GitHub attachment".
    Powered by `gh-attach`.

[git-advanced-workflows]
    Source: agents (bundle)
    What it does: Applies advanced Git techniques like rebasing, cherry-picking, bisect,
    worktrees, and reflog to keep history clean and recover from mistakes.
    When to use: You are dealing with a tangled Git history or need to recover lost work.
    Search terms: git, rebase, cherry pick, git bisect, recover commits, git history, undo git,
    worktrees, version control
    Original description: Master advanced Git workflows including rebasing, cherry-picking,
    bisect, worktrees, and reflog to maintain clean history and recover from any situation. Use
    when managing complex Git histories, collaborating on feature branches, or troubleshooting
    repository issues.

[git-commit]
    Source: awesome-copilot
    What it does: Stages the right files and writes a Conventional Commits message automatically
    by analyzing what changed.
    When to use: You want to commit your changes with a good message in one step.
    Search terms: git commit, commit message, stage changes, conventional commits, save changes,
    version control, auto commit
    Original description: Execute git commit with conventional commit message analysis,
    intelligent staging, and message generation. Use when user asks to commit changes, create a
    git commit, or mentions "/commit". Supports: (1) Auto-detecting type and scope from changes,
    (2) Generating conventional commit messages from diff, (3) Interactive commit with optional
    type/scope/description overrides, (4) Intelligent file staging for logical grouping

[git-flow-branch-creator]
    Source: awesome-copilot
    What it does: Analyzes your current changes and creates the appropriate Git Flow branch
    (feature, release, hotfix) following the standard branching model.
    When to use: You want a correctly named branch for the work you're about to do.
    Search terms: git flow, create branch, feature branch, hotfix branch, release branch,
    branching model, git workflow, new branch
    Original description: Intelligent Git Flow branch creator that analyzes git status/diff and
    creates appropriate branches following the nvie Git Flow branching model.

[git-guardrails-claude-code]
    Source: mattpocock skills
    What it does: Sets up safety hooks in Claude Code that block dangerous Git commands like
    force pushes and hard resets before they run.
    When to use: You want to prevent an AI assistant from running destructive Git commands.
    Search terms: git safety, block git push, claude code hooks, prevent data loss, guardrails,
    dangerous commands, ai safety, protect repository
    Original description: Set up Claude Code hooks to block dangerous git commands (push, reset
    --hard, clean, branch -D, etc.) before they execute. Use when user wants to prevent
    destructive git operations, add git safety hooks, or block git push/reset in Claude Code.

[git-workflow-and-versioning]
    Source: agent-skills
    What it does: Structures how code changes are committed, branched, merged, and released,
    including choosing version numbers and tagging releases.
    When to use: You want a consistent, sane process for managing code changes and releases.
    Search terms: git workflow, branching, versioning, semantic version, release tagging, merge
    conflicts, commit practices, parallel work
    Original description: Structures git workflow practices. Use when making any code change.
    Use when committing, branching, resolving conflicts, or when you need to organize work
    across multiple parallel streams. Use when cutting a release, choosing a semantic version
    bump, tagging, or writing a changelog.

[github-issues]
    Source: awesome-copilot
    What it does: Creates, updates, and manages GitHub issues including labels, assignees,
    milestones, and custom fields.
    When to use: You want to log a bug, feature request, or task in GitHub or update an existing
    one.
    Search terms: github issues, bug report, feature request, create issue, labels, assign
    issue, milestones, task tracking, project management
    Original description: Create, update, and manage GitHub issues using MCP tools. Use this
    skill when users want to create bug reports, feature requests, or task issues, update
    existing issues, add labels/assignees/milestones, set issue fields (dates, priority, custom
    fields), set issue types, manage issue workflows, link issues, add dependencies, or track
    blocked-by/blocking relationships. Triggers on requests like "create an issue", "file a
    bug", "request a feature", "update issue X", "set the priority", "set the start date", "link
    issues", "add dependency", "blocked by", "blocking", or any GitHub issue management …

[github-release]
    Source: awesome-copilot
    What it does: Walks through releasing a new version of a GitHub library end to end, handling
    version numbers and changelog formatting automatically.
    When to use: You are ready to publish a new version of your software on GitHub.
    Search terms: github release, publish version, changelog, semver, new version, release
    notes, version bump, ship release
    Original description: Guides IA through releasing a new version of a GitHub library end-to-
    end. Handles SemVer versioning and Keep a Changelog formatting automatically.

[gitmoji]
    Source: awesome-copilot
    What it does: Writes commit messages in the gitmoji style, picking the emoji that matches
    the intent of the change.
    When to use: You want commit messages with the standard emoji prefixes.
    Search terms: gitmoji, emoji commit, commit message, git commit, commit style, fun commits,
    git conventions
    Original description: Generates commit messages following the gitmoji convention
    (https://gitmoji.dev) — picks the right emoji for the intent of the change and writes a
    well-formed message. Use when asked to "write a gitmoji commit", "add an emoji to my commit
    message", "which gitmoji should I use", "gitmoji this change", or when a project uses
    gitmoji-style commit messages. Works from a git diff, staged changes, or a plain description
    of the change. Generates the message only — does not run git commands.

[go-concurrency-patterns]
    Source: agents (bundle)
    What it does: Writes concurrent Go programs using goroutines, channels, and sync tools,
    including worker pools and race-condition debugging.
    When to use: You are building Go software that needs to do many things at once safely.
    Search terms: go concurrency, golang, goroutines, channels, worker pool, race condition,
    parallel go, go performance
    Original description: Master Go concurrency with goroutines, channels, sync primitives, and
    context. Use when building concurrent Go applications, implementing worker pools, or
    debugging race conditions.

[hads]
    Source: agents (bundle)
    What it does: Writes or converts technical documentation into the HADS format, which is
    designed to be readable by both people and AI while using fewer tokens.
    When to use: You want documentation that AI assistants can consume efficiently without
    losing human readability.
    Search terms: ai friendly docs, hads, technical documentation, token efficient,
    documentation format, docs for ai, convert docs, validate document
    Original description: Use when writing technical documentation that needs to be readable by
    both humans and AI models, converting existing docs to HADS format, validating a HADS
    document, or optimizing documentation for token-efficient AI consumption.

[harness-engineering]
    Source: awesome-copilot
    What it does: Sets up repository-level safeguards that turn past AI coding mistakes into
    durable instructions, drift checks, and regression tests so they don't recur.
    When to use: Your AI coding assistant keeps making the same mistakes and you want to stop
    the cycle.
    Search terms: ai coding mistakes, repeat errors, agent guardrails, regression tests,
    harness, coding agent setup, failure memory, drift checks
    Original description: Adopt repository-level harness engineering for coding agents. Use when
    a user wants to prevent repeated AI coding-agent mistakes by turning failures into durable
    instructions, drift checks, regression tests, failure memory, and adoption reports tailored
    to the target repository.

[health]
    Source: waza
    What it does: Audits the health of your AI-assisted engineering setup, checking for drift in
    instructions and config, hooks, MCP servers, and overall AI maintainability.
    When to use: You want to know if your Claude, Codex, or agent configuration is in good
    shape.
    Search terms: ai setup audit, claude config, instruction drift, mcp health, hooks check,
    agent configuration, engineering health, ai maintainability
    Original description: Runs a budget-aware agent-assisted engineering health audit for
    instruction/config drift, hooks/MCP, verifier surfaces, and AI maintainability. Use when
    users ask in any language to audit Claude, Codex, Pi, agent instructions, MCP or hooks,
    verifier coverage, or AI-maintainability drift. Not for debugging application code or
    reviewing PRs.

[hunt]
    Source: waza
    What it does: Finds the root cause of errors, crashes, regressions, failing tests, and
    broken behavior, including from screenshots, before applying any fix.
    When to use: Something is broken and you want the real cause found rather than a quick
    patch.
    Search terms: root cause, bug hunt, crash, error, regression, failing test, screenshot bug,
    broken feature, debug
    Original description: Finds root cause before applying fixes for errors, crashes,
    regressions, failing tests, broken behavior, and screenshot-reported defects. Use when users
    report in any language errors, crashes, broken behavior, regressions, failing tests,
    screenshot evidence, or something that used to work and now fails. Not for code review or
    new features.

[implement]
    Source: mattpocock skills
    What it does: Builds out a piece of work from a spec or set of tickets, turning the written
    plan into working code.
    When to use: You have a clear spec or tickets and want them implemented.
    Search terms: implement feature, build from spec, tickets to code, write code, execute plan,
    development, deliver feature
    Original description: Implement a piece of work based on a spec or set of tickets.

[incremental-implementation]
    Source: agent-skills
    What it does: Delivers code changes in small, safe steps rather than one big drop,
    especially when work spans multiple files.
    When to use: A task feels too large to land at once and you want it broken into safe
    increments.
    Search terms: small steps, incremental, break down work, safe changes, feature delivery,
    step by step coding, avoid big bang, manageable chunks
    Original description: Delivers changes incrementally. Use when implementing any feature or
    change that touches more than one file. Use when you're about to write a large amount of
    code at once, or when a task feels too big to land in one step.

[issue-fields-migration]
    Source: awesome-copilot
    What it does: Bulk-migrates metadata from repository labels or Project boards into GitHub's
    native issue fields, such as turning priority labels into a Priority field.
    When to use: You want to move from labels to structured issue fields in GitHub without doing
    it by hand.
    Search terms: github issue fields, migrate labels, project fields, bulk update issues,
    priority field, github projects, issue metadata, convert labels
    Original description: Bulk-migrate metadata to GitHub issue fields from two sources: repo
    labels (e.g. priority labels to a Priority field) and Project V2 fields. Use when users say
    "migrate my labels to issue fields", "migrate project fields to issue fields", "convert
    labels to issue fields", "copy project field values to issue fields", or ask about adopting
    issue fields. Issue fields are org-level typed metadata (single select, text, number, date)
    that replace label-based workarounds with structured, searchable, cross-repo fields.

[java-junit]
    Source: awesome-copilot
    What it does: Provides best practices for writing Java unit tests with JUnit 5, including
    data-driven tests.
    When to use: You are writing or improving automated tests for Java code.
    Search terms: junit, java testing, unit tests, java, test best practices, parameterized
    tests, automated testing, test coverage
    Original description: Get best practices for JUnit 5 unit testing, including data-driven
    tests

[java-refactoring-extract-method]
    Source: awesome-copilot
    What it does: Refactors Java code by pulling repeated or lengthy logic out into well-named
    separate methods.
    When to use: You have long Java methods that would be clearer if split up.
    Search terms: java refactoring, extract method, clean up java, long methods, code
    readability, java, refactor, simplify
    Original description: Refactoring using Extract Methods in Java Language

[java-refactoring-remove-parameter]
    Source: awesome-copilot
    What it does: Refactors Java code by removing unneeded method parameters and updating all
    callers.
    When to use: You have Java methods with parameters that are no longer used.
    Search terms: java refactoring, remove parameter, unused parameter, clean up java, method
    signature, java, refactor, simplify
    Original description: Refactoring using Remove Parameter in Java Language

[javascript-testing-patterns]
    Source: agents (bundle)
    What it does: Implements JavaScript and TypeScript test suites with Jest, Vitest, and
    Testing Library, covering unit, integration, and end-to-end tests with mocking and fixtures.
    When to use: You want solid automated tests for a JavaScript or TypeScript project.
    Search terms: javascript testing, jest, vitest, typescript tests, unit tests, testing
    library, mocking, test setup, tdd
    Original description: Implement comprehensive testing strategies using Jest, Vitest, and
    Testing Library for unit tests, integration tests, and end-to-end testing with mocking,
    fixtures, and test-driven development. Use when writing JavaScript/TypeScript tests, setting
    up test infrastructure, or implementing TDD/BDD workflows.

[lsp-setup]
    Source: awesome-copilot
    What it does: Installs and configures a language server so GitHub Copilot CLI gets code
    intelligence like go-to-definition and hover info for any programming language.
    When to use: You want smarter code navigation in Copilot CLI for your language.
    Search terms: lsp, language server, copilot cli, code intelligence, go to definition, editor
    setup, developer tools, install language support
    Original description: Enable code intelligence (go-to-definition, find-references, hover,
    type info) for any programming language by installing and configuring an LSP server for
    Copilot CLI. Detects the OS, installs the right server, and generates the JSON configuration
    (user-level or repo-level). Use when you need deeper code understanding and no LSP server is
    configured, or when the user asks to set up, install, or configure an LSP server.

[make-repo-contribution]
    Source: awesome-copilot
    What it does: Ensures any contribution to a repository follows its documented guidelines
    before issues, branches, commits, or pull requests are created.
    When to use: You are contributing to a project and want to follow its rules correctly.
    Search terms: contributing, repo guidelines, open source contribution, pull request rules,
    contribution guide, follow conventions, github workflow, project rules
    Original description: All changes to code must follow the guidance documented in the
    repository. Before any issue is filed, branch is made, commits generated, or pull request
    (or PR) created, a search must be done to ensure the right steps are followed. Whenever
    asked to create an issue, commit messages, to push code, or create a PR, use this skill so
    everything is done correctly.

[memory-safety-patterns]
    Source: agents (bundle)
    What it does: Writes memory-safe systems code in Rust, C++, and C using ownership, RAII, and
    smart pointers to prevent crashes and security bugs.
    When to use: You are writing low-level code and want to avoid memory leaks and crashes.
    Search terms: memory safety, rust, c++, smart pointers, memory leaks, systems programming,
    ownership, raii, crash prevention
    Original description: Implement memory-safe programming with RAII, ownership, smart
    pointers, and resource management across Rust, C++, and C. Use when writing safe systems
    code, managing resources, or preventing memory bugs.

[multi-reviewer-patterns]
    Source: agents (bundle)
    What it does: Coordinates several parallel code reviews covering different quality
    dimensions, then merges their findings, removes duplicates, and calibrates severity into one
    report.
    When to use: You want a code change reviewed from multiple angles at once with a single
    consolidated result.
    Search terms: parallel code review, multiple reviewers, consolidated findings, review
    severity, code quality, pr review, review coordination, thorough review
    Original description: Coordinate parallel code reviews across multiple quality dimensions
    with finding deduplication, severity calibration, and consolidated reporting. Use this skill
    when organizing multi-reviewer code reviews, calibrating finding severity, or consolidating
    review results.

[parallel-debugging]
    Source: agents (bundle)
    What it does: Debugs complex problems by investigating several competing hypotheses at once,
    collecting evidence for each, and picking the true root cause.
    When to use: A bug could have several possible causes and you want them all checked in
    parallel.
    Search terms: debug, multiple causes, root cause analysis, hypotheses, parallel
    investigation, hard bug, troubleshooting, evidence
    Original description: Debug complex issues using competing hypotheses with parallel
    investigation, evidence collection, and root cause arbitration. Use this skill when
    debugging bugs with multiple potential causes, performing root cause analysis, or organizing
    parallel investigation workflows.

[performance-engineer]
    Source: agent-playbook
    What it does: Investigates and fixes performance problems to make applications faster and
    more efficient.
    When to use: Your software is slow and you want it sped up.
    Search terms: slow app, performance, speed up, optimization, efficiency, bottleneck, faster
    code, load time
    Original description: Performance optimization specialist for improving application speed
    and efficiency. Use when investigating performance issues or optimizing code.

[performance-optimization]
    Source: agent-skills
    What it does: Optimizes performance across frontend, backend, queries, and databases,
    including Core Web Vitals, load times, and inefficient database patterns.
    When to use: Your website or app is slow and you want it faster end to end.
    Search terms: website speed, core web vitals, slow database, n+1 queries, performance, page
    load, optimize app, backend speed, lighthouse
    Original description: Optimizes application performance across frontend, backend, queries,
    and databases. Use when performance requirements exist, when you suspect performance
    regressions, when Core Web Vitals or load times need improvement, when N+1 query patterns
    need fixing, or when profiling reveals bottlenecks.

[ponytail]
    Source: ponytail
    What it does: Pushes for the simplest solution that actually works, questioning whether a
    task is needed at all and favoring built-in tools over custom code.
    When to use: You want to avoid over-engineering and ship the minimal thing that does the
    job.
    Search terms: keep it simple, minimal solution, yagni, avoid over engineering, less code,
    pragmatic, simplest fix, standard library
    Original description: Forces the laziest solution that actually works, simplest, shortest,
    most minimal. Channels a senior dev who has seen everything: question whether the task needs
    to exist at all (YAGNI), reach for the standard library before custom code, native platform
    features before dependencies, one line before fifty. Supports intensity levels: lite, full
    (default), ultra. Use on ANY coding task: writing, adding, refactoring, fixing, reviewing,
    or designing code, and choosing libraries or dependencies. Also use whenever the user says
    "ponytail", "be lazy", "lazy mode", "simplest solution", "minimal solutio…

[ponytail-audit]
    Source: ponytail
    What it does: Scans an entire codebase for over-engineering and produces a ranked list of
    what to delete, simplify, or replace with built-in equivalents.
    When to use: You suspect your codebase has grown more complex than it needs to be.
    Search terms: audit codebase, over engineering, simplify, delete code, reduce complexity,
    code bloat, technical debt, cleanup
    Original description: Whole-repo audit for over-engineering. Like ponytail-review, but scans
    the entire codebase instead of a diff: a ranked list of what to delete, simplify, or replace
    with stdlib/native equivalents. Use when the user says "audit this codebase", "audit for
    over-engineering", "what can I delete from this repo", "find bloat", "ponytail-audit", or
    "/ponytail-audit". One-shot report, does not apply fixes.

[ponytail-debt]
    Source: ponytail
    What it does: Collects every deliberate shortcut left as a 'ponytail:' comment in the
    codebase into a tracked debt ledger so they don't get forgotten.
    When to use: You want a list of the shortcuts your team promised to revisit later.
    Search terms: technical debt, debt ledger, todo comments, shortcuts, deferred work,
    ponytail, track debt, code cleanup list
    Original description: Harvest every `ponytail:` comment in the codebase into a debt ledger,
    so the deliberate shortcuts and deferrals ponytail leaves behind get tracked instead of
    rotting into "later means never". Use when the user says "ponytail debt", "/ponytail-debt",
    "what did ponytail defer", "list the shortcuts", "ponytail ledger", or "what did we mark to
    do later". One-shot report, changes nothing.

[ponytail-gain]
    Source: ponytail
    What it does: Displays a compact scoreboard of how much code, cost, and time the ponytail
    simplicity approach saves based on benchmark results.
    When to use: You want to see the measured impact of using ponytail.
    Search terms: ponytail, savings, scoreboard, less code, cost savings, benchmark, impact
    report, roi
    Original description: Show ponytail's measured impact as a compact scoreboard: less code,
    less cost, more speed, from the benchmark medians. One-shot display, not a persistent mode,
    and not a per-repo number. Trigger: /ponytail-gain, "ponytail gain", "what does ponytail
    save", "show ponytail impact", "ponytail scoreboard".

[ponytail-help]
    Source: ponytail
    What it does: Shows a quick-reference card of all ponytail modes, skills, and commands.
    When to use: You want to know what ponytail commands are available and how to use them.
    Search terms: ponytail, help, commands, reference card, how to use, cheat sheet, quick
    reference
    Original description: Quick-reference card for all ponytail modes, skills, and commands.
    One-shot display, not a persistent mode. Trigger: /ponytail-help, "ponytail help", "what
    ponytail commands", "how do I use ponytail".

[ponytail-review]
    Source: ponytail
    What it does: Reviews a code change purely for over-engineering, listing what to delete,
    which dependencies aren't needed, and what to replace with standard tools.
    When to use: You want a code review focused only on cutting unnecessary complexity.
    Search terms: code review, over engineering, simplify, remove dependencies, delete code,
    keep it simple, yagni, review diff
    Original description: Code review focused exclusively on over-engineering. Finds what to
    delete: reinvented standard library, unneeded dependencies, speculative abstractions, dead
    flexibility. One line per finding: location, what to cut, what replaces it. Use when the
    user says "review for over-engineering", "what can we delete", "is this over-engineered",
    "simplify review", or invokes /ponytail-review. Complements correctness-focused review, this
    one only hunts complexity.

[pr-dashboard]
    Source: awesome-copilot
    What it does: Opens a dashboard in your browser showing your GitHub pull requests, with
    filtering by date range and status.
    When to use: You want a quick overview of your open and recent pull requests.
    Search terms: pull requests, pr dashboard, github prs, my prs, pr status, code review queue,
    github overview, open prs
    Original description: Open a GitHub PR dashboard in the browser. Use when the user asks to
    see their pull requests, open the PR dashboard, show PRs for a date range, or check PR
    status. Trigger phrases include "show my PRs", "open PR dashboard", "pull request
    dashboard".

[pr-screenshots]
    Source: awesome-copilot
    What it does: Adds before-and-after screenshots and annotated images to a code change
    request so reviewers can see what changed visually.
    When to use: You want reviewers of a software change to see the visual difference, not just
    the code.
    Search terms: pull request, screenshots, before and after, github, azure devops, code
    review, images in pr, annotated screenshots
    Original description: Embed before/after screenshots and annotated images in pull request
    descriptions. Covers PR description patterns, image upload for Azure DevOps and GitHub, and
    sizing best practices.

[pr-walkthrough]
    Source: warp common-skills
    What it does: Builds an interactive, zoomable visual map of a proposed code change, showing
    which parts of the system it touches and how data flows through it.
    When to use: You want a visual overview of a large code change instead of reading a long
    diff.
    Search terms: pull request, visual map, code change overview, diagram, interactive chart,
    d3, code review, github
    Original description: Generate a static interactive D3 walkthrough of a pull request. Use
    when the user wants a zoomable PR map, graph/canvas PR orientation, or alternate
    visualization of PR system components, data flow, code dependencies, and user actions.

[pytest-coverage]
    Source: awesome-copilot
    What it does: Runs automated Python tests, finds code that the tests never exercise, and
    adds tests until everything is covered.
    When to use: You want to be sure your Python software is fully tested.
    Search terms: test coverage, python tests, pytest, unit tests, 100 percent coverage,
    untested code, quality assurance, testing
    Original description: Run pytest tests with coverage, discover lines missing coverage, and
    increase coverage to 100%.

[python-anti-patterns]
    Source: agents (bundle)
    What it does: Reviews Python code against a checklist of common mistakes and bad habits that
    lead to bugs or hard-to-maintain software.
    When to use: You want a second pair of eyes to catch common Python mistakes before code
    ships.
    Search terms: python, code review, bad practices, common mistakes, code quality, checklist,
    bugs, anti-patterns
    Original description: Use this skill when reviewing Python code for common anti-patterns to
    avoid. Use as a checklist when reviewing code, before finalizing implementations, or when
    debugging issues that might stem from known bad practices.

[python-code-style]
    Source: agents (bundle)
    What it does: Applies consistent formatting, naming, and documentation standards to Python
    code and sets up automatic style checkers.
    When to use: You want your Python code to look consistent and follow accepted conventions.
    Search terms: python, code style, formatting, linting, naming conventions, docstrings,
    coding standards, clean code
    Original description: Python code style, linting, formatting, naming conventions, and
    documentation standards. Use when writing new code, reviewing style, configuring linters,
    writing docstrings, or establishing project standards.

[python-configuration]
    Source: agents (bundle)
    What it does: Sets up Python software so settings and secrets live outside the code, in
    environment variables or config files, with different values for development and production.
    When to use: You need to manage passwords, API keys, or settings for a Python app without
    hard-coding them.
    Search terms: python, configuration, environment variables, settings, secrets, api keys,
    pydantic, config management
    Original description: Python configuration management via environment variables and typed
    settings. Use when externalizing config, setting up pydantic-settings, managing secrets, or
    implementing environment-specific behavior.

[python-design-patterns]
    Source: agents (bundle)
    What it does: Guides the structure of Python software so it stays simple, modular, and easy
    to test, and helps untangle oversized classes or functions.
    When to use: You are designing a new Python component or a codebase has become too tangled
    to change safely.
    Search terms: python, design patterns, software architecture, refactoring, clean code,
    separation of concerns, maintainability, code structure
    Original description: Python design patterns including KISS, Separation of Concerns, Single
    Responsibility, and composition over inheritance. Use this skill when designing a new
    service or component from scratch and choosing how to layer responsibilities, when
    refactoring a God class or monolithic function that has grown too large, when deciding
    whether to add a new abstraction or live with duplication, when evaluating a pull request
    for structural issues like tight coupling or leaking internal types, when choosing between
    inheritance and composition for a new class hierarchy, or when a codebase is becoming hard
    to…

[python-error-handling]
    Source: agents (bundle)
    What it does: Designs how Python software validates input and responds when things go wrong,
    including partial failures in batch jobs.
    When to use: You want a Python app to fail gracefully and give useful error messages instead
    of crashing.
    Search terms: python, error handling, exceptions, input validation, crash, robust code,
    batch failures, api errors
    Original description: Python error handling patterns including input validation, exception
    hierarchies, and partial failure handling. Use when implementing validation logic, designing
    exception strategies, handling batch processing failures, or building robust APIs.

[python-packaging]
    Source: agents (bundle)
    What it does: Turns Python code into an installable package with the right project structure
    and publishes it to the public Python package index.
    When to use: You want to share a Python library or command-line tool so others can install
    it with pip.
    Search terms: python, packaging, pypi, pip install, publish library, cli tool, pyproject,
    distribute code
    Original description: Create distributable Python packages with proper project structure,
    setup.py/pyproject.toml, and publishing to PyPI. Use when packaging Python libraries,
    creating CLI tools, or distributing Python code.

[python-performance-optimization]
    Source: agents (bundle)
    What it does: Measures where Python code spends its time and memory, then speeds up the slow
    parts.
    When to use: Your Python program or script is running too slowly.
    Search terms: python, slow code, performance, speed up, profiling, memory usage,
    optimization, bottleneck
    Original description: Profile and optimize Python code using cProfile, memory profilers, and
    performance best practices. Use when debugging slow Python code, optimizing bottlenecks, or
    improving application performance.

[python-project-structure]
    Source: agents (bundle)
    What it does: Organizes a Python project's folders, modules, and public interfaces so it is
    easy to navigate and extend.
    When to use: You are starting a new Python project or cleaning up a messy one.
    Search terms: python, project structure, folder layout, modules, organize code, new project,
    architecture, public api
    Original description: Python project organization, module architecture, and public API
    design. Use when setting up new projects, organizing modules, defining public interfaces
    with __all__, or planning directory layouts.

[python-pypi-package-builder]
    Source: awesome-copilot
    What it does: Builds, tests, versions, and publishes a professional-grade Python library end
    to end, including automated release pipelines.
    When to use: You want to ship a polished, versioned Python package to PyPI with proper CI
    and type checking.
    Search terms: python, pypi, publish package, versioning, semver, github actions, ci cd, sdk,
    library release
    Original description: End-to-end skill for building, testing, linting, versioning, and
    publishing a production-grade Python library to PyPI. Covers all four build backends
    (setuptools+setuptools_scm, hatchling, flit, poetry), PEP 440 versioning, semantic
    versioning, dynamic git-tag versioning, OOP/SOLID design, type hints (PEP 484/526/544/561),
    Trusted Publishing (OIDC), and the full PyPA packaging flow. Use for: creating Python
    packages, pip-installable SDKs, CLI tools, framework plugins, pyproject.toml setup,
    py.typed, setuptools_scm, semver, mypy, pre-commit, GitHub Actions CI/CD, or PyPI
    publishing.

[python-resilience]
    Source: agents (bundle)
    What it does: Adds automatic retries, timeouts, and back-off behavior to Python code so it
    copes with flaky networks and temporary outages.
    When to use: Your Python app talks to external services that sometimes fail or time out.
    Search terms: python, retries, timeouts, fault tolerance, flaky api, backoff, reliability,
    resilience
    Original description: Python resilience patterns including automatic retries, exponential
    backoff, timeouts, and fault-tolerant decorators. Use when adding retry logic, implementing
    timeouts, building fault-tolerant services, or handling transient failures.

[python-resource-management]
    Source: agents (bundle)
    What it does: Ensures Python code properly opens and closes files, connections, and other
    resources, and handles streaming data cleanly.
    When to use: Your Python app leaks connections or file handles, or you need to stream large
    results.
    Search terms: python, context managers, file handles, database connections, cleanup,
    streaming, memory leaks, resource management
    Original description: Python resource management with context managers, cleanup patterns,
    and streaming. Use when managing connections, file handles, implementing cleanup logic, or
    building streaming responses with accumulated state.

[python-testing-patterns]
    Source: agents (bundle)
    What it does: Sets up automated Python test suites using pytest, with reusable fixtures,
    mocking, and test-first development.
    When to use: You want to write or improve automated tests for Python software.
    Search terms: python, testing, pytest, unit tests, mocking, fixtures, tdd, test suite
    Original description: Implement comprehensive testing strategies with pytest, fixtures,
    mocking, and test-driven development. Use when writing Python tests, setting up test suites,
    or implementing testing best practices.

[python-type-safety]
    Source: agents (bundle)
    What it does: Adds type annotations and strict type checking to Python code so many bugs are
    caught before the program runs.
    When to use: You want Python code to be checked for type errors automatically.
    Search terms: python, type hints, mypy, pyright, type checking, static analysis, generics,
    catch bugs early
    Original description: Python type safety with type hints, generics, protocols, and strict
    type checking. Use when adding type annotations, implementing generic classes, defining
    structural interfaces, or configuring mypy/pyright.

[qa-expert]
    Source: agent-playbook
    What it does: Plans testing strategies and quality gates so software is checked thoroughly
    before release.
    When to use: You want to set up or improve a quality assurance process for a software team.
    Search terms: qa, quality assurance, testing strategy, test plan, quality gates, software
    quality, release checks, test coverage
    Original description: Quality assurance expert for testing strategies and quality gates. Use
    when planning test coverage, setting up QA processes, or improving quality standards.

[quality-playbook]
    Source: awesome-copilot
    What it does: Runs a deep quality audit of a codebase by deriving what the software should
    do, generating tests to prove it, reviewing the code multiple times, and producing a bug
    report with verified fixes.
    When to use: You want an exhaustive audit that finds real defects ordinary code review
    misses.
    Search terms: quality audit, find bugs, code review, spec audit, regression tests, software
    quality, defects, testing
    Original description: Run a complete quality engineering audit on any codebase. Derives
    behavioral requirements from the code, generates spec-traced functional tests, runs a three-
    pass code review with regression tests, executes a multi-model spec audit (Council of
    Three), and produces a consolidated bug report with TDD-verified patches. Finds the 35% of
    real defects that structural code review alone cannot catch. Works with any language.
    Trigger on 'quality playbook', 'spec audit', 'Council of Three', 'fitness-to-purpose', or
    'coverage theater'.

[receiving-code-review]
    Source: obra superpowers
    What it does: Helps evaluate feedback on code changes critically, verifying suggestions
    before applying them rather than accepting them blindly.
    When to use: You have received review comments on code and want to respond thoughtfully.
    Search terms: code review, review feedback, pull request comments, respond to reviewer,
    verify suggestions, github, code quality
    Original description: Use when receiving code review feedback, before implementing
    suggestions, especially if feedback seems unclear or technically questionable - requires
    technical rigor and verification, not performative agreement or blind implementation

[refactor]
    Source: awesome-copilot
    What it does: Cleans up existing code to make it easier to read and maintain without
    changing what it does, through small, careful improvements.
    When to use: Your code works but has become messy and hard to change.
    Search terms: refactoring, clean up code, code quality, maintainability, technical debt,
    simplify code, code smells, rename
    Original description: Surgical code refactoring to improve maintainability without changing
    behavior. Covers extracting functions, renaming variables, breaking down god functions,
    improving type safety, eliminating code smells, and applying design patterns. Less drastic
    than repo-rebuilder; use for gradual improvements.

[refactor-method-complexity-reduce]
    Source: awesome-copilot
    What it does: Breaks a single overly complicated function into smaller helper pieces until
    it drops below a chosen complexity limit.
    When to use: One function in your code has grown so long and tangled that nobody wants to
    touch it.
    Search terms: refactoring, complex function, split method, simplify code, cognitive
    complexity, helper methods, code quality
    Original description: Refactor given method `${input:methodName}` to reduce its cognitive
    complexity to `${input:complexityThreshold}` or below, by extracting helper methods.

[refactor-plan]
    Source: awesome-copilot
    What it does: Investigates a codebase and writes a step-by-step plan for a large
    restructuring across many files, waiting for approval before changing anything.
    When to use: You want to reorganize a lot of code safely and need a plan first.
    Search terms: refactoring plan, large refactor, multi-file changes, planning, code
    restructure, safe changes, technical debt
    Original description: Create a concrete plan before starting a multi-file refactor. Use when
    the user asks to plan, sequence, scope, or safely execute a refactor across multiple files;
    always investigate first, output the plan, and wait for confirmation before making code
    changes.

[refactoring-specialist]
    Source: agent-playbook
    What it does: Improves the structure, readability, and maintainability of existing code on
    request.
    When to use: You want someone to tidy up and improve a piece of code.
    Search terms: refactor, clean code, code cleanup, improve code, readability,
    maintainability, code quality
    Original description: Code refactoring expert for improving code structure, readability, and
    maintainability. Use when user asks to refactor, clean up, or improve code quality.

[reproduce-bug-report]
    Source: warp common-skills
    What it does: Sends cloud agents to recreate a reported visual or interactive bug in the
    app, records a screen capture as evidence, and reports what happened.
    When to use: A customer or teammate reported a bug in your app's interface and you want to
    confirm it.
    Search terms: reproduce bug, bug report, screen recording, ui bug, qa, support ticket,
    visual evidence, testing
    Original description: Launch Oz cloud agents with computer use to reproduce UI-focused bug
    reports, capture visual evidence (a screen recording by default), and report reproduction
    findings. Use when investigating a specific interactive or visual bug from an issue, ticket,
    support report, or prompt.

[requesting-code-review]
    Source: obra superpowers
    What it does: Runs a review of completed work to confirm it meets requirements before it is
    merged or shipped.
    When to use: You have finished a feature and want it checked before merging.
    Search terms: code review, pull request, merge check, quality check, requirements, feature
    complete, review request
    Original description: Use when completing tasks, implementing major features, or before
    merging to verify work meets requirements

[resemble-detect]
    Source: awesome-copilot
    What it does: Detects AI-generated or deepfake audio, images, video, and text, traces where
    synthetic media came from, and verifies speaker identity using Resemble AI.
    When to use: You suspect a recording, image, or message may be AI-generated or faked.
    Search terms: deepfake, ai detection, fake audio, fake video, resemble ai, voice
    verification, watermark, media authenticity, synthetic media
    Original description: Deepfake detection and media safety — detect AI-generated audio,
    images, video, and text, trace synthesis sources, apply watermarks, verify speaker identity,
    and analyze media intelligence using Resemble AI

[resolve-merge-conflicts]
    Source: warp common-skills
    What it does: Resolves conflicts when two sets of code changes collide in Git, looking only
    at the conflicting sections to keep things efficient.
    When to use: A Git merge or rebase stopped because of conflicting changes.
    Search terms: merge conflict, git, rebase, conflict markers, combine changes, version
    control, unmerged files
    Original description: Resolve Git merge conflicts by extracting only unresolved paths,
    conflict hunks, and compact diffs instead of loading whole files into context. Use when a
    merge, rebase, cherry-pick, or stash pop stops on conflicts, when `git status` shows
    unmerged paths, or when files contain conflict markers.

[resolving-merge-conflicts]
    Source: mattpocock skills
    What it does: Works through an in-progress Git merge or rebase conflict and finishes it
    cleanly.
    When to use: Git is stuck on a merge or rebase with conflicts.
    Search terms: merge conflict, git, rebase, version control, conflicting changes, fix merge,
    stuck merge
    Original description: Use when you need to resolve an in-progress git merge/rebase conflict.

[respond-to-pr-comments-in-blocklist]
    Source: warp common-skills
    What it does: Walks through each reviewer comment on a GitHub code change one at a time,
    records your decision, then posts replies and closes the threads after you approve a
    preview.
    When to use: You want to reply to and close out reviewer comments on a GitHub pull request.
    Search terms: pull request, review comments, github, reply to reviewers, resolve threads,
    code review, pr feedback
    Original description: Interactively walk a user through PR review comments one at a time,
    collect a per-comment decision, then post agent-authored replies on GitHub and resolve the
    review threads once the user approves a preview. Use only when the user wants to reply to or
    resolve review threads on GitHub. Skip when the user only wants comments fetched or
    displayed (use `pr-comments`), or only wants the code changes made without posting anything
    back to GitHub.

[review-agent-setup]
    Source: agents (bundle)
    What it does: Sets up approval checkpoints so an AI agent cannot post reviews, merge code,
    or change build settings without a human signing off, with a tamper-evident audit trail.
    When to use: You want AI agents to help with code review but require human approval for
    risky actions.
    Search terms: ai agent, human approval, approval gate, audit trail, claude code, pull
    request, safety controls, governance
    Original description: Configure human-in-the-loop gating for AI agent review actions in
    Claude Code. Use when setting up a project where an agent may post PR reviews, comments,
    merges, or edit CI configuration, and you want a cryptographically auditable approval trail
    with Cedar-enforced gates.

[review-and-refactor]
    Source: awesome-copilot
    What it does: Reviews and cleans up code in a project according to a set of written
    instructions.
    When to use: You have coding guidelines and want code brought into line with them.
    Search terms: code review, refactor, coding guidelines, clean up, code standards, improve
    code, project rules
    Original description: Review and refactor code in your project according to defined
    instructions

[review-loop]
    Source: review-loop
    What it does: Repeatedly drafts work, has a critic score it out of ten with specific
    feedback, and revises until it meets a quality bar.
    When to use: You want a piece of work polished through several rounds of critique.
    Search terms: review loop, polish, iterate, quality gate, feedback cycle, critic, revise,
    improve quality
    Original description: Iterative worker-reviewer cycle that spawns a critic subagent to score
    work 1-10 and provide actionable feedback, then revises until a quality gate is met. Use
    when implementing features, writing specs, reviewing existing code, or completing any task
    where quality matters more than speed. Trigger phrases: "use review-loop", "polish this",
    "iterate on this", "/review-loop", "review with feedback loop".

[review-pr]
    Source: warp common-skills
    What it does: Reviews a code change from saved diff files and writes structured feedback to
    a file for an automated workflow to publish.
    When to use: You need machine-readable review output for a pull request as part of an
    automated pipeline.
    Search terms: pull request review, code review, automated review, review json, github
    workflow, diff, feedback
    Original description: Review a pull request diff and write structured feedback to
    review.json for the workflow to publish. Use when reviewing a checked-out PR from local
    artifacts like pr_diff.txt and pr_description.txt and producing machine-readable review
    output instead of posting directly to GitHub.

[ruff-recursive-fix]
    Source: awesome-copilot
    What it does: Runs the Ruff Python linter, applies its automatic fixes round after round,
    reviews each change, and resolves whatever remains by hand.
    When to use: You want to clean up all linter warnings in a Python project.
    Search terms: ruff, python linter, lint errors, autofix, code style, clean up warnings, code
    quality
    Original description: Run Ruff checks with optional scope and rule overrides, apply safe and
    unsafe autofixes iteratively, review each change, and resolve remaining findings with
    targeted edits or user decisions.

[rust-async-patterns]
    Source: agents (bundle)
    What it does: Guides building concurrent Rust applications with Tokio, including error
    handling and debugging asynchronous code.
    When to use: You are writing Rust software that needs to do many things at once.
    Search terms: rust, async, tokio, concurrency, async traits, parallel, debugging async, rust
    programming
    Original description: Master Rust async programming with Tokio, async traits, error
    handling, and concurrent patterns. Use when building async Rust applications, implementing
    concurrent systems, or debugging async code.

[scoutqa-test]
    Source: awesome-copilot
    What it does: Automatically tests a website for bugs, accessibility problems, and broken
    user flows such as login or checkout using the ScoutQA tool.
    When to use: You want to check that your website works properly and is accessible.
    Search terms: website testing, find bugs, accessibility audit, login flow, checkout test,
    qa, scoutqa, smoke test, automated testing
    Original description: This skill should be used when the user asks to "test this website",
    "run exploratory testing", "check for accessibility issues", "verify the login flow works",
    "find bugs on this page", or requests automated QA testing. Triggers on web application
    testing scenarios including smoke tests, accessibility audits, e-commerce flows, and user
    flow validation using ScoutQA CLI. Use this skill proactively after implementing web
    application features to verify they work correctly.

[setup-pre-commit]
    Source: mattpocock skills
    What it does: Installs checks that automatically format code, check types, and run tests
    every time someone commits to the repository.
    When to use: You want code problems caught before they are committed.
    Search terms: pre-commit hooks, husky, lint-staged, prettier, auto format, git hooks, type
    check, commit checks
    Original description: Set up Husky pre-commit hooks with lint-staged (Prettier), type
    checking, and tests in the current repo. Use when user wants to add pre-commit hooks, set up
    Husky, configure lint-staged, or add commit-time formatting/typechecking/testing.

[shellcheck-configuration]
    Source: agents (bundle)
    What it does: Configures the ShellCheck tool to catch errors and portability problems in
    shell scripts.
    When to use: You want your shell scripts checked for bugs automatically.
    Search terms: shellcheck, shell scripts, bash, linting, script errors, portability, static
    analysis
    Original description: Master ShellCheck static analysis configuration and usage for shell
    script quality. Use when setting up linting infrastructure, fixing code issues, or ensuring
    script portability.

[shipping-and-launch]
    Source: agent-skills
    What it does: Prepares a software release for production with a pre-launch checklist,
    monitoring setup, staged rollout plan, and rollback strategy.
    When to use: You are about to deploy something to real users and want to do it safely.
    Search terms: production launch, deploy, release checklist, rollout, rollback plan,
    monitoring, go live, ship software
    Original description: Prepares production launches. Use when preparing to deploy to
    production. Use when you need a pre-launch checklist, when setting up monitoring, when
    planning a staged rollout, or when you need a rollback strategy.

[source-driven-development]
    Source: agent-skills
    What it does: Bases every coding decision on official documentation, citing sources so the
    code avoids outdated or made-up patterns.
    When to use: You want code built on a framework to follow the official, current
    documentation.
    Search terms: official docs, documentation, cited sources, framework, best practices,
    accurate code, up to date, library usage
    Original description: Grounds every implementation decision in official documentation. Use
    when you want authoritative, source-cited code free from outdated patterns. Use when
    building with any framework or library where correctness matters.

[suggestion-box]
    Source: warp common-skills
    What it does: Lets an AI agent quietly submit short, constructive feedback when it hits
    friction that could be fixed to make agents work better.
    When to use: You want agents to report recurring obstacles they encounter without
    interrupting you.
    Search terms: agent feedback, suggestion, internal feedback, friction, improve tooling, ai
    agent, automatic reporting
    Original description: Autonomously submit brief, constructive internal feedback when an
    agent encounters material, generalizable friction and can suggest an improvement that would
    make agents more effective. Use this skill proactively during any task without waiting for
    the user to invoke it, and submit without asking permission, previewing the message, or
    mentioning the submission.

[systematic-debugging]
    Source: obra superpowers
    What it does: Applies a disciplined process to track down the root cause of a bug or failing
    test before attempting any fix.
    When to use: Something in your software is broken and you want to find the real cause rather
    than guess.
    Search terms: debugging, bug, root cause, failing test, troubleshoot, unexpected behavior,
    fix bug, investigation
    Original description: Use when encountering any bug, test failure, or unexpected behavior,
    before proposing fixes

[tdd]
    Source: mattpocock skills
    What it does: Builds features and fixes bugs by writing the test first, then the code to
    pass it, then tidying up.
    When to use: You want new code proven correct by tests from the start.
    Search terms: test driven development, tdd, red green refactor, write tests first,
    integration tests, unit tests, bug fix
    Original description: Test-driven development. Use when the user wants to build features or
    fix bugs test-first, mentions "red-green-refactor", or wants integration tests.

[test-automator]
    Source: agent-playbook
    What it does: Creates and maintains automated test suites and frameworks to improve test
    coverage.
    When to use: You want automated tests written or a testing framework set up for your
    software.
    Search terms: automated testing, write tests, test framework, test coverage, qa automation,
    unit tests, end to end tests
    Original description: Test automation framework expert for creating and maintaining
    automated tests. Use when user asks to write tests, automate testing, or improve test
    coverage.

[test-driven-development (agent-skills)]
    Source: agent-skills
    What it does: Drives every code change with tests, writing a failing test before
    implementing logic or fixing a bug to prove the code works.
    When to use: You want any bug fix or behavior change backed by a test that proves it.
    Search terms: test driven development, tdd, write tests first, bug fix, prove code works,
    regression test, unit tests
    Original description: Drives development with tests. Use when implementing any logic, fixing
    any bug, or changing any behavior. Use when you need to prove that code works, when a bug
    report arrives, or when you're about to modify existing functionality.

[test-driven-development (obra superpowers)]
    Source: obra superpowers
    What it does: Requires writing a test before any feature or bug-fix code so the
    implementation is guided and verified by tests.
    When to use: You are about to write code and want tests leading the way.
    Search terms: test driven development, tdd, tests first, feature development, bug fix, unit
    tests, verification
    Original description: Use when implementing any feature or bugfix, before writing
    implementation code

[using-git-worktrees]
    Source: obra superpowers
    What it does: Creates an isolated copy of the code repository so new feature work does not
    disturb what you are currently working on.
    When to use: You want to start a separate piece of work without disrupting your current
    files.
    Search terms: git worktree, isolated workspace, branch, parallel work, git, feature branch,
    separate checkout
    Original description: Use when starting feature work that needs isolation from current
    workspace or before executing implementation plans - ensures an isolated workspace exists
    via native tools or git worktree fallback

[uv-package-manager]
    Source: agents (bundle)
    What it does: Sets up and manages Python projects, dependencies, and virtual environments
    using the fast uv tool.
    When to use: You want a faster, simpler way to manage Python packages and environments.
    Search terms: uv, python packages, dependencies, virtual environment, pip alternative,
    python setup, package manager
    Original description: Master the uv package manager for fast Python dependency management,
    virtual environments, and modern Python project workflows. Use when setting up Python
    projects, managing dependencies, or optimizing Python development workflows with uv.

[vardoger-analyze]
    Source: awesome-copilot
    What it does: Analyzes your past GitHub Copilot CLI conversations on your own machine to
    learn your preferences and writes them into your Copilot instructions file.
    When to use: You want GitHub Copilot to adapt to the way you like to work.
    Search terms: github copilot, personalize, copilot instructions, learn my style, vardoger,
    conversation history, preferences
    Original description: Use when the user asks to personalize the GitHub Copilot CLI
    assistant, adapt Copilot to their style, use vardoger, or analyze their Copilot CLI
    conversation history. Reads the local session directory at `~/.copilot/session-state/`,
    extracts recurring preferences and conventions, and writes a fenced personalization block
    into `~/.copilot/copilot-instructions.md`. Runs entirely on the user's machine via the local
    `vardoger` CLI (`pipx install vardoger`); no network calls and no uploads. Triggers:
    'personalize my copilot', 'analyze my copilot history', 'tailor copilot to me', 'run
    vardoger', 'up…

[vcpkg]
    Source: awesome-copilot
    What it does: Sets up and manages C++ project dependencies with vcpkg, including version
    pinning, build-tool integration, and cross-compiling.
    When to use: You are managing libraries for a C++ project.
    Search terms: vcpkg, c++, dependencies, cmake, visual studio, cross compile, library
    versions, package manager
    Original description: Guide for setting up vcpkg in C++ projects, managing dependency
    versions, and cross-compiling. Covers manifest initialization, CMake and Visual Studio
    integration, classic-to-manifest migration, version pinning, baselines, overrides, triplets,
    and cross-compilation. Use when a user is working with vcpkg project setup, installation,
    version management, or cross-platform builds. For specialized tasks, additional references
    cover custom registries and overlay ports (references/registries.md), CI/CD and binary
    caching (references/ci.md), and troubleshooting and dependency lifecycle (references/tro…

[verification-before-completion]
    Source: obra superpowers
    What it does: Insists on running the actual checks and confirming their output before
    declaring any work finished, fixed, or passing.
    When to use: You want proof, not promises, that a task was completed correctly.
    Search terms: verify work, run tests, proof of completion, evidence, before commit, quality
    check, done criteria
    Original description: Use when about to claim work is complete, fixed, or passing, before
    committing or creating PRs - requires running verification commands and confirming output
    before making any success claims; evidence before assertions always

[workflow-patterns]
    Source: agents (bundle)
    What it does: Follows a structured test-first workflow with phase checkpoints, task-by-task
    commits, and a verification protocol.
    When to use: You are working inside the Conductor workflow and need to follow its task
    process.
    Search terms: conductor, workflow, tdd, checkpoints, git commits, task process, verification
    Original description: Use this skill when implementing tasks according to Conductor's TDD
    workflow, handling phase checkpoints, managing git commits for tasks, or understanding the
    verification protocol.

[write-coding-standards-from-file]
    Source: awesome-copilot
    What it does: Studies the coding style in files or folders you point to and writes a coding
    standards document that captures it.
    When to use: You want a written style guide derived from how your code is already written.
    Search terms: coding standards, style guide, code conventions, documentation, team
    standards, consistency, best practices
    Original description: Write a coding standards document for a project using the coding
    styles from the file(s) and/or folder(s) passed as arguments in the prompt.
