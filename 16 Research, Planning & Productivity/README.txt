16 RESEARCH, PLANNING & PRODUCTIVITY
====================================

Skills for thinking before doing: research workflows, specs and PRDs, task breakdown, planning
files, daily focus boards, interviews that sharpen ideas and learning/teaching.

54 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - acquire-codebase-knowledge
  - architecture-blueprint-generator
  - archive
  - bench-read
  - breakdown-epic-arch
  - breakdown-epic-pm
  - breakdown-feature-implementation
  - breakdown-feature-prd
  - breakdown-plan
  - breakdown-test
  - build-evidence-map
  - check-impl-against-spec
  - code-exemplars-blueprint-generator
  - create-implementation-plan
  - create-specification
  - create-technical-spike
  - daily-focus-board
  - daily-prep
  - desk-journal
  - desk-open
  - exam-ready
  - executing-plans
  - folder-structure-blueprint-generator
  - gen-specs-as-issues
  - implement-specs
  - learn
  - mentoring-juniors
  - planning-and-task-breakdown
  - planning-with-files
  - prd
  - prd-implementation-precheck
  - prd-planner
  - project-workflow-analysis-blueprint-generator
  - read
  - research (mattpocock skills)
  - research (warp common-skills)
  - roundup
  - roundup-setup
  - scaffold-exercises
  - scan-new-specs
  - setup-my-iq
  - spec-driven-development
  - spec-driven-implementation
  - technology-stack-blueprint-generator
  - think
  - to-spec
  - to-tickets
  - triage
  - update-implementation-plan
  - update-specification
  - validate-changes-match-specs
  - wayfinder
  - workshop-create
  - writing-plans

SKILL DETAILS
-------------

[acquire-codebase-knowledge]
    Source: awesome-copilot
    What it does: Maps and documents an existing software codebase so new people can understand
    how it is organized and how it works.
    When to use: You want to onboard someone to a software project or get an overview of how an
    existing codebase is structured.
    Search terms: document codebase, onboard developer, map the code, software documentation,
    architecture overview, understand existing code, repo overview, codebase docs
    Original description: Use this skill when the user explicitly asks to map, document, or
    onboard into an existing codebase. Trigger for prompts like "map this codebase", "document
    this architecture", "onboard me to this repo", or "create codebase docs". Do not trigger for
    routine feature implementation, bug fixes, or narrow code edits unless the user asks for
    repository-level discovery.

[architecture-blueprint-generator]
    Source: awesome-copilot
    What it does: Analyzes a software project and produces detailed architecture documentation,
    including the technology stack, design patterns, and visual diagrams, to guide consistent
    future development.
    When to use: You want a clear architecture document for your software so your team builds on
    it consistently.
    Search terms: architecture document, software blueprint, system diagram, tech stack
    overview, architecture patterns, document my app, technical documentation, codebase analysis
    Original description: Comprehensive project architecture blueprint generator that analyzes
    codebases to create detailed architectural documentation. Automatically detects technology
    stacks and architectural patterns, generates visual diagrams, documents implementation
    patterns, and provides extensible blueprints for maintaining architectural consistency and
    guiding new development.

[archive]
    Source: opc-skills
    What it does: Saves lessons learned, bug fixes, and deployment notes into a dated, tagged,
    searchable archive so the knowledge can be reused in future work sessions.
    When to use: You just finished a tricky task or deployment and want to record what you
    learned for later.
    Search terms: archive notes, save learnings, session log, debugging notes, deployment log,
    knowledge archive, project memory, lessons learned
    Original description: Archive session learnings, debugging solutions, and deployment logs to
    .archive/yyyy-mm-dd/ as indexed markdown with searchable tags. Use when completing a
    significant task, resolving a tricky bug, deploying, or when the user says "archive this".
    Maintains .archive/MEMORY.md index for cross-session knowledge reuse.

[bench-read]
    Source: awesome-copilot
    What it does: Reads findings, verdicts, and work products that other AI work desks have left
    on a shared workspace so you can pick up where they left off.
    When to use: You want to review what other agents or sessions have produced in a shared
    workshop.
    Search terms: shared workspace, read findings, agent handoff, workshop bench, pick up where
    left off, review outputs, team workspace
    Original description: Read artifacts from the shared bench — the workspace where desks leave
    findings, verdicts, and work products for each other and the operator.

[breakdown-epic-arch]
    Source: awesome-copilot
    What it does: Drafts the high-level technical architecture for a large project initiative
    (an epic) based on its product requirements document.
    When to use: You have requirements for a big project and need a technical plan before
    breaking it into features.
    Search terms: technical architecture, epic planning, project architecture, prd to
    architecture, system design, big project plan, technical spec
    Original description: Prompt for creating the high-level technical architecture for an Epic,
    based on a Product Requirements Document.

[breakdown-epic-pm]
    Source: awesome-copilot
    What it does: Writes a product requirements document for a large project initiative (an
    epic), laying out goals, scope, and needs that later feed into technical planning.
    When to use: You are kicking off a big product initiative and need to define what it should
    achieve.
    Search terms: prd, product requirements, epic, project scope, product planning, requirements
    document, define a project, product manager
    Original description: Prompt for creating an Epic Product Requirements Document (PRD) for a
    new epic. This PRD will be used as input for generating a technical architecture
    specification.

[breakdown-feature-implementation]
    Source: awesome-copilot
    What it does: Creates a detailed step-by-step implementation plan for a single software
    feature, following a structured monorepo layout.
    When to use: You have a feature defined and need a concrete plan for how to build it.
    Search terms: implementation plan, feature plan, build a feature, development tasks,
    engineering plan, step by step build, project breakdown
    Original description: Prompt for creating detailed feature implementation plans, following
    Epoch monorepo structure.

[breakdown-feature-prd]
    Source: awesome-copilot
    What it does: Writes a product requirements document for an individual feature, derived from
    a larger project epic.
    When to use: You need to define exactly what a new feature should do before developers start
    building it.
    Search terms: feature requirements, prd, feature spec, product requirements, define a
    feature, user stories, feature planning
    Original description: Prompt for creating Product Requirements Documents (PRDs) for new
    features, based on an Epic.

[breakdown-plan]
    Source: awesome-copilot
    What it does: Generates a full project plan organized as epics, features, stories, and
    tests, with dependencies, priorities, and tracking set up automatically.
    When to use: You want to turn a project into an organized, trackable set of work items.
    Search terms: project plan, work breakdown, task hierarchy, epics and stories, project
    tracking, issue planning, github issues, priorities and dependencies
    Original description: Issue Planning and Automation prompt that generates comprehensive
    project plans with Epic > Feature > Story/Enabler > Test hierarchy, dependencies,
    priorities, and automated tracking.

[breakdown-test]
    Source: awesome-copilot
    What it does: Produces a test strategy and quality assurance plan, including task breakdowns
    and validation checkpoints for a software project.
    When to use: You want to make sure a project gets tested properly and need a plan for it.
    Search terms: test plan, qa strategy, quality assurance, testing checklist, software
    testing, validation plan, test tasks, github projects
    Original description: Test Planning and Quality Assurance prompt that generates
    comprehensive test strategies, task breakdowns, and quality validation plans for GitHub
    projects.

[build-evidence-map]
    Source: awesome-copilot
    What it does: Builds an organized map of supporting, contradicting, qualifying, and missing
    evidence for a contested decision, with exact source references, so disagreements are not
    glossed over.
    When to use: You are making a consequential or disputed decision and want the evidence on
    every side laid out clearly.
    Search terms: evidence map, decision evidence, pros and cons, research synthesis, weigh the
    evidence, proposal review, source citations, contested decision, due diligence
    Original description: Build an auditable evidence map for a contested technical choice,
    research synthesis, proposal review, or consequential decision. Use when Copilot must
    preserve supporting, contradicting, qualifying, and missing evidence with exact source
    regions instead of collapsing disagreement into prose.

[check-impl-against-spec]
    Source: warp common-skills
    What it does: Compares a code change against the written specification and flags any
    meaningful mismatches as part of a code review.
    When to use: You are reviewing a pull request and want to confirm it actually does what the
    spec said.
    Search terms: spec compliance, code review, pull request check, matches the spec,
    requirements check, review against spec, implementation mismatch
    Original description: Compare a pull request's implementation against spec context in
    spec_context.md and feed any material mismatches into review.json. Use during PR review when
    approved or repository spec context is available.

[code-exemplars-blueprint-generator]
    Source: awesome-copilot
    What it does: Scans a codebase to identify high-quality example code and documents it as a
    reference for coding standards across the team.
    When to use: You want to establish coding standards by pointing at the best existing
    examples in your project.
    Search terms: coding standards, code examples, best practice code, style guide, code
    consistency, team conventions, code quality reference
    Original description: Technology-agnostic prompt generator that creates customizable AI
    prompts for scanning codebases and identifying high-quality code exemplars. Supports
    multiple programming languages (.NET, Java, JavaScript, TypeScript, React, Angular, Python)
    with configurable analysis depth, categorization methods, and documentation formats to
    establish coding standards and maintain consistency across development teams.

[create-implementation-plan]
    Source: awesome-copilot
    What it does: Writes a new implementation plan document for building a feature, refactoring
    code, upgrading packages, or changing architecture or infrastructure.
    When to use: You are about to start a development effort and want a written plan first.
    Search terms: implementation plan, project plan, development roadmap, refactor plan, upgrade
    plan, plan before coding, engineering plan
    Original description: Create a new implementation plan file for new features, refactoring
    existing code or upgrading packages, design, architecture or infrastructure.

[create-specification]
    Source: awesome-copilot
    What it does: Writes a new specification document for a software solution, structured so AI
    tools can read and act on it reliably.
    When to use: You need a clear written spec for a system or feature that both people and AI
    assistants can follow.
    Search terms: write a spec, specification, requirements doc, technical spec, ai-readable
    spec, define the system, documentation
    Original description: Create a new specification file for the solution, optimized for
    Generative AI consumption.

[create-technical-spike]
    Source: awesome-copilot
    What it does: Creates a time-boxed research document for investigating and resolving a
    critical technical question before committing to implementation.
    When to use: You face an important technical decision and want to research it within a fixed
    time budget before building.
    Search terms: technical spike, research before building, feasibility study, proof of
    concept, time-boxed research, technical decision, investigate options
    Original description: Create time-boxed technical spike documents for researching and
    resolving critical development decisions before implementation.

[daily-focus-board]
    Source: awesome-copilot
    What it does: Sets up a personal daily focus board in your browser that you drive by talking
    to your AI assistant, tracking tasks, progress, priorities, and an end-of-day recap in a
    gentle, distraction-friendly way.
    When to use: You want to plan your day, stay focused, and track progress without overdue
    shaming.
    Search terms: daily planner, focus board, to-do list, task tracker, plan my day,
    productivity, adhd friendly, eisenhower matrix, pomodoro, daily goals
    Original description: Spin up a personal, motivating daily focus board that renders in a
    browser canvas and that the user drives by talking to their AI partner. Tasks track status
    (to-do → in progress → done) with timestamped progress notes and roll up into a "today's
    momentum" feed; numeric-goal tasks (pages, pomodoros, reps) render as progress-bar counters.
    Executive-function / neurodivergent-friendly by design: Focus mode, kind "not today"
    carryover (no overdue-shaming), a brain-dump box, reduced-motion, and gentle deadline
    countdowns. Add, reorder, and relabel tasks live, assign Eisenhower priority (Do first / …

[daily-prep]
    Source: awesome-copilot
    What it does: Prepares you for tomorrow by pulling your Outlook calendar, cross-checking
    open tasks, classifying meetings, spotting conflicts, finding deep-work slots, and producing
    a structured prep page with recommendations.
    When to use: You want to get ready for tomorrow's meetings and workload the evening before.
    Search terms: prepare for tomorrow, meeting prep, outlook calendar, daily schedule, calendar
    conflicts, deep work time, day planning, workiq
    Original description: Prepare for tomorrow's meetings and tasks. Pulls calendar from Outlook
    via WorkIQ, cross-references open tasks and workspace context, classifies meetings, detects
    conflicts and day-fit issues, finds learning and deep-work slots, and generates a structured
    HTML prep file with productivity recommendations.

[desk-journal]
    Source: awesome-copilot
    What it does: Writes, appends to, or reads a persistent work journal that records what was
    done, the current state, and the next step so work survives across sessions.
    When to use: You want to log progress so a future session can pick up exactly where this one
    left off.
    Search terms: work journal, progress log, session notes, persistent memory, what did i do,
    next steps, handoff notes
    Original description: Write, append, or read desk journal entries. The journal is persistent
    memory — what survives session boundaries. A good entry has: what was done, current state,
    next step.

[desk-open]
    Source: awesome-copilot
    What it does: Creates and opens a new work desk in a shared workshop, setting up its
    folders, initial journal, and identity so later sessions can find the trail.
    When to use: You are starting a new stream of work in a shared workshop and need its
    workspace set up.
    Search terms: new workspace, start a desk, workshop setup, project folder setup, work
    session, agent workspace, initialize desk
    Original description: Create and open a new desk in the workshop. Sets up the folder
    structure, initial journal, and desk identity so the next session that sits down finds the
    trail.

[exam-ready]
    Source: awesome-copilot
    What it does: Turns study material and a syllabus into exam prep: key definitions, important
    points, keywords, diagrams, exam-ready sentences, and practice questions drawn strictly from
    the provided material.
    When to use: You have notes or a PDF and an exam coming up and want focused revision
    material.
    Search terms: exam prep, study notes, practice questions, revision, study guide, summarize
    notes, flashcards, syllabus, student
    Original description: Activate this skill when a student provides study material (PDF or
    pasted notes) and a syllabus, and wants to prepare for an exam. Extracts key definitions,
    points, keywords, diagrams, exam-ready sentences, and practice questions strictly from the
    provided material.

[executing-plans]
    Source: obra superpowers
    What it does: Carries out a previously written implementation plan in a fresh session,
    pausing at review checkpoints so you can confirm progress before it continues.
    When to use: You already have a written plan and want it executed step by step with check-
    ins.
    Search terms: execute plan, follow the plan, implementation, review checkpoints, carry out
    tasks, build from plan, step by step execution
    Original description: Use when you have a written implementation plan to execute in a
    separate session with review checkpoints

[folder-structure-blueprint-generator]
    Source: awesome-copilot
    What it does: Analyzes and documents a project's folder layout, naming conventions, and file
    placement rules, producing a blueprint for keeping code organized consistently.
    When to use: You want everyone on the team to put files in the right place and follow the
    same structure.
    Search terms: folder structure, project organization, naming conventions, file layout,
    directory structure, code organization, project blueprint
    Original description: Comprehensive technology-agnostic prompt for analyzing and documenting
    project folder structures. Auto-detects project types (.NET, Java, React, Angular, Python,
    Node.js, Flutter), generates detailed blueprints with visualization options, naming
    conventions, file placement patterns, and extension templates for maintaining consistent
    code organization across diverse technology stacks.

[gen-specs-as-issues]
    Source: awesome-copilot
    What it does: Walks through finding missing features, prioritizing them, and writing
    detailed specifications for each as trackable issues.
    When to use: You want to figure out what your product is missing and turn those gaps into
    specced work items.
    Search terms: missing features, feature ideas, prioritize features, write specs, github
    issues, product gaps, feature backlog
    Original description: This workflow guides you through a systematic approach to identify
    missing features, prioritize them, and create detailed specifications for implementation.

[implement-specs]
    Source: warp common-skills
    What it does: Builds an approved feature from its product and technical spec documents,
    keeping the specs and code in sync within the same change.
    When to use: Your product and tech specs are approved and you are ready to build the
    feature.
    Search terms: implement feature, build from spec, product.md, tech.md, spec to code, feature
    development, keep specs updated
    Original description: Implement an approved feature from PRODUCT.md and TECH.md, keeping
    specs and code aligned in the same PR as implementation evolves. Use after the product and
    tech specs are approved and the next step is building the feature.

[learn]
    Source: waza
    What it does: Runs a structured six-phase research process that turns an unfamiliar subject
    or a pile of source material into a polished, publish-ready reference.
    When to use: You need to get up to speed on an unfamiliar topic or synthesize many sources
    into one coherent document.
    Search terms: research a topic, deep dive, learn about, synthesize sources, study material,
    compile research, reference guide, literature review
    Original description: Runs a six-phase research workflow that turns unfamiliar domains,
    source bundles, or collected material into publish-ready output. Use when users ask in any
    language to research, study, deep-dive, compile sources, synthesize unfamiliar material, or
    turn a source bundle into a coherent reference. Not for quick lookups or single-file reads.

[mentoring-juniors]
    Source: awesome-copilot
    What it does: Mentors beginner developers and AI newcomers through guided questions rather
    than direct answers, helping them reason through problems themselves.
    When to use: You are learning to code or are stuck and want to be coached to the answer
    instead of handed it.
    Search terms: coding mentor, learn to code, explain this code, im stuck, teach me, beginner
    help, walk me through, socratic, junior developer
    Original description: Socratic mentoring for junior developers and AI newcomers. Guides
    through questions, never answers. Triggers: "help me understand", "explain this code", "I'm
    stuck", "Im stuck", "I'm confused", "Im confused", "I don't understand", "I dont
    understand", "can you teach me", "teach me", "mentor me", "guide me", "what does this error
    mean", "why doesn't this work", "why does not this work", "I'm a beginner", "Im a beginner",
    "I'm learning", "Im learning", "I'm new to this", "Im new to this", "walk me through", "how
    does this work", "what's wrong with my code", "what's wrong", "can you break this do…

[planning-and-task-breakdown]
    Source: agent-skills
    What it does: Breaks a spec or clear set of requirements into an ordered list of doable
    tasks, helping estimate scope and spot work that can happen in parallel.
    When to use: A task feels too big to start and you need it split into manageable pieces.
    Search terms: break down tasks, task list, project planning, scope estimate, work breakdown,
    too big to start, parallel work, task ordering
    Original description: Breaks work into ordered tasks. Use when you have a spec or clear
    requirements and need to break work into implementable tasks. Use when a task feels too
    large to start, when you need to estimate scope, or when parallel work is possible.

[planning-with-files]
    Source: agent-playbook
    What it does: Uses persistent markdown files to plan multi-step work, track progress, and
    store knowledge so nothing is lost between sessions.
    When to use: You have a multi-step project or research effort and want a durable written
    plan and progress tracker.
    Search terms: project planning, progress tracking, planning files, markdown notes, multi-
    step task, organize work, knowledge storage, manus style
    Original description: Uses persistent markdown files for general planning, progress
    tracking, and knowledge storage (Manus-style workflow). Use for multi-step tasks, research
    projects, or general organization WITHOUT mentioning PRD. For PRD-specific work, use prd-
    planner skill instead.

[prd]
    Source: awesome-copilot
    What it does: Generates a high-quality product requirements document for software or AI-
    powered features, including executive summary, user stories, technical specs, and risk
    analysis.
    When to use: You need to define a new product or feature clearly before anyone starts
    building it.
    Search terms: prd, product requirements document, feature spec, user stories, product
    planning, requirements, risk analysis, executive summary
    Original description: Generate high-quality Product Requirements Documents (PRDs) for
    software systems and AI-powered features. Includes executive summaries, user stories,
    technical specifications, and risk analysis.

[prd-implementation-precheck]
    Source: agent-playbook
    What it does: Implements a PRD or feature spec only after a mandatory preflight review that
    raises questions about scope, consistency, and risks for you to confirm.
    When to use: You want a spec built but want potential problems surfaced before any code is
    written.
    Search terms: implement prd, spec review, preflight check, scope questions, build the spec,
    requirements review, risk check before coding
    Original description: Implement PRDs/specs with a mandatory precheck review before coding.
    Use when a user asks to implement a PRD/feature spec/requirements doc or says "implement
    PRD/spec". Perform a preflight review, raise questions on scope/consistency/risks, then
    implement after confirmation.

[prd-planner]
    Source: agent-playbook
    What it does: Creates product requirements documents using persistent planning files,
    combining PRD methodology with ongoing file-based tracking.
    When to use: You explicitly want a PRD written and kept up to date as a living document.
    Search terms: prd, product requirements document, write a prd, product spec, planning files,
    feature requirements, product planning
    Original description: Creates PRDs using persistent file-based planning. Use when user
    explicitly says "PRD", "product requirements document", or "产品需求文档". Combines PRD
    methodology with planning-with-files to avoid context switching.

[project-workflow-analysis-blueprint-generator]
    Source: awesome-copilot
    What it does: Documents how an application works end to end, from entry points through
    service layers, data access, error handling, and testing, producing detailed workflow
    blueprints.
    When to use: You want to understand or document how data and requests flow through your
    application.
    Search terms: application workflow, data flow, how the app works, end to end documentation,
    system blueprint, service layers, architecture analysis
    Original description: Comprehensive technology-agnostic prompt generator for documenting
    end-to-end application workflows. Automatically detects project architecture patterns,
    technology stacks, and data flow patterns to generate detailed implementation blueprints
    covering entry points, service layers, data access, error handling, and testing approaches
    across multiple technologies including .NET, Java/Spring, React, and microservices
    architectures.

[read]
    Source: waza
    What it does: Reads web pages and PDFs, returning a concise summary by default or clean
    Markdown when you want to convert, save, quote, or cite the content.
    When to use: You want a URL or PDF summarized, quoted, or converted to text.
    Search terms: read a url, summarize a webpage, read pdf, convert to markdown, save article,
    cite a source, fetch a link, summarize document
    Original description: Reads URLs and PDFs by fetching source content, defaulting to concise
    summaries for plain read requests and clean Markdown when asked to convert, save, quote,
    cite, or feed downstream work. Use when users ask in any language to read, fetch, check,
    summarize, quote, cite, convert, or save a URL or PDF. Not for local text files already in
    the repo.

[research (mattpocock skills)]
    Source: mattpocock skills
    What it does: Investigates a question against trustworthy primary sources and saves the
    findings as a Markdown file in your project.
    When to use: You want a topic, API, or documentation question researched and written up for
    later reference.
    Search terms: research, look into, find documentation, primary sources, research notes,
    background agent, api facts, write up findings
    Original description: Investigate a question against high-trust primary sources and capture
    the findings as a Markdown file in the repo. Use when the user wants a topic researched,
    docs or API facts gathered, or reading legwork delegated to a background agent.

[research (warp common-skills)]
    Source: warp common-skills
    What it does: Hands off noisy investigations (reading many files, long logs, big diffs) to
    helper agents and returns a distilled answer so your main conversation stays clean.
    When to use: Answering a question would require wading through lots of files or logs and you
    just want the answer.
    Search terms: investigate, how does this work, where is this used, root cause, summarize
    logs, codebase survey, delegate research, summarize pull request
    Original description: Delegate noisy investigation to one or more subagents so the
    orchestrator's context stays clean, then work from the distilled answer. Use this skill
    whenever answering a question would require reading many files, long logs, large diffs, or
    wide codebase surveys — i.e. when producing the answer generates far more noise than the
    answer itself. Use it for "how does X work", "where is Y used", "what's the root cause of
    Z", "summarize this PR/log" style questions, and reach for it liberally before reading a
    pile of files inline.

[roundup]
    Source: awesome-copilot
    What it does: Generates personalized status updates on demand by pulling from your connected
    sources (GitHub, email, Teams, Slack and more) and writing in your own voice for whatever
    audience you choose.
    When to use: You need to send a status update and want it drafted from what actually
    happened this week.
    Search terms: status update, weekly report, progress briefing, team update, write my update,
    slack summary, email summary, github activity
    Original description: Generate personalized status briefings on demand. Pulls from your
    configured data sources (GitHub, email, Teams, Slack, and more), synthesizes across them,
    and drafts updates in your own communication style for any audience you define.

[roundup-setup]
    Source: awesome-copilot
    What it does: Walks you through a setup interview that learns your writing style, audiences,
    and data sources so status briefings come out sounding like you.
    When to use: You are setting up automated status updates for the first time.
    Search terms: setup status updates, configure briefings, communication style, onboarding,
    connect data sources, personalize reports, roundup
    Original description: Interactive onboarding that learns your communication style,
    audiences, and data sources to configure personalized status briefings. Paste in examples of
    updates you already write, answer a few questions, and roundup calibrates itself to your
    workflow.

[scaffold-exercises]
    Source: mattpocock skills
    What it does: Creates the folder structure for course exercises, including sections,
    problems, solutions, and explainers that pass linting checks.
    When to use: You are building a coding course and need a new section of exercises stubbed
    out.
    Search terms: course exercises, scaffold, coding course, exercise stubs, lessons, problems
    and solutions, course section, teaching
    Original description: Create exercise directory structures with sections, problems,
    solutions, and explainers that pass linting. Use when user wants to scaffold exercises,
    create exercise stubs, or set up a new course section.

[scan-new-specs]
    Source: warp common-skills
    What it does: Scans Warp's repositories for recently merged product specs that lack
    documentation, auto-drafts a docs pull request when the spec is complete, and pings the
    engineer when it is too thin.
    When to use: You want documentation coverage kept up automatically as new product specs
    land.
    Search terms: docs coverage, auto generate docs, product specs, documentation gaps,
    scheduled agent, warp, docs pull request
    Original description: Scan warpdotdev/warp and warp-server for recently merged PRODUCT.md
    specs that don't yet have a corresponding docs PR in warpdotdev/docs. When a complete spec
    is found, auto-generates a full docs draft PR and tags the engineer. When a spec is too thin
    to draft from, pings the engineer directly. Designed to run as a scheduled Oz ambient agent
    (e.g., every 2-3 days). Use when setting up the automated docs trigger or running a manual
    docs coverage sweep.

[setup-my-iq]
    Source: awesome-copilot
    What it does: Creates or updates a personal context portfolio: structured files describing
    who you are, how you work, your team, stakeholders, and tool settings that other skills rely
    on.
    When to use: You are setting up your AI assistant for the first time or something about your
    team or role has changed.
    Search terms: personal context, set up my profile, my team, stakeholders, ado config,
    onboarding, update my info, work preferences
    Original description: Create, set up, or update the personal context portfolio: structured
    markdown files describing who you are, how you work, your teams, and your tool/ADO
    configuration. Runs the interview workflow for first-time setup and targeted edits for
    updates. Trigger this skill when the user asks to: set up their context, create or update
    their context portfolio, "create my IQ", "set up my IQ", edit their profile, add/remove a
    stakeholder, update ADO config, change team info, update pillars, or set up any plugin
    configuration. Trigger when another skill fails to find context (missing files or TODO
    markers…

[spec-driven-development]
    Source: agent-skills
    What it does: Writes specifications before any coding starts, turning vague ideas into clear
    requirements and breaking large requirements into a map of independently testable
    capabilities.
    When to use: You are starting a new project or feature and the requirements are still fuzzy.
    Search terms: write a spec, requirements first, specification, vague idea to plan,
    capability map, define requirements, spec before code, new project
    Original description: Creates specs before coding. Use when starting a new project, feature,
    or significant change and no specification exists yet. Use when requirements are unclear,
    ambiguous, or only exist as a vague idea. Use when a single requirement spans several
    independently testable capabilities and needs decomposing into a capability map of modules
    before specifying.

[spec-driven-implementation]
    Source: warp common-skills
    What it does: Runs a spec-first workflow for big features: writes a product spec, adds a
    technical spec when needed, and keeps both updated in source control as the build evolves.
    When to use: You are starting a significant feature and want product and tech specs checked
    in alongside the code.
    Search terms: product spec, tech spec, product.md, spec first, feature planning,
    documentation in repo, agent-driven development
    Original description: Drive a spec-first workflow for substantial features by writing
    PRODUCT.md before implementation, writing TECH.md when warranted, and keeping both specs
    updated as implementation evolves. Use when starting a significant feature, planning agent-
    driven implementation, or when the user wants product and tech specs checked into source
    control.

[technology-stack-blueprint-generator]
    Source: awesome-copilot
    What it does: Analyzes a codebase to document its full technology stack, versions, licenses,
    usage patterns, conventions, and diagrams, producing a blueprint for consistent development.
    When to use: You want a complete inventory and guide to the technologies your software uses.
    Search terms: tech stack, technology inventory, software licenses, architecture
    documentation, what is my app built with, coding conventions, stack overview
    Original description: Comprehensive technology stack blueprint generator that analyzes
    codebases to create detailed architectural documentation. Automatically detects technology
    stacks, programming languages, and implementation patterns across multiple platforms (.NET,
    Java, JavaScript, React, Python). Generates configurable blueprints with version
    information, licensing details, usage patterns, coding conventions, and visual diagrams.
    Provides implementation-ready templates and maintains architectural consistency for guided
    development.

[think]
    Source: waza
    What it does: Turns a rough idea into an approved, decision-complete plan, checking
    structure, feasibility, and whether the work is worth doing before any code is written.
    When to use: You have an idea and want to pressure-test and plan it before building.
    Search terms: plan an idea, is this worth doing, feasibility, architecture decision, design
    direction, think it through, planning, decision making
    Original description: Turns rough ideas into approved, decision-complete plans with
    validated structure before coding. Use when users ask in any language for planning,
    architecture, design direction, feasibility, value judgment, or whether a feature is worth
    doing before implementation. Not for bug fixes or small edits.

[to-spec]
    Source: mattpocock skills
    What it does: Turns the current conversation into a written spec and publishes it to your
    project issue tracker, with no extra interview required.
    When to use: You have talked through what you want and now want it captured as a spec.
    Search terms: conversation to spec, write it up, create issue, issue tracker, capture
    requirements, spec from chat, publish spec
    Original description: Turn the current conversation into a spec and publish it to the
    project issue tracker — no interview, just synthesis of what you've already discussed.

[to-tickets]
    Source: mattpocock skills
    What it does: Breaks a plan, spec, or conversation into a set of small end-to-end tickets,
    each noting what blocks it, and publishes them to your issue tracker.
    When to use: You have a plan and want it split into trackable tickets with dependencies.
    Search terms: create tickets, break into tasks, issue tracker, task dependencies, plan to
    tickets, github issues, linear, jira, work items
    Original description: Break a plan, spec, or the current conversation into a set of tracer-
    bullet tickets, each declaring its blocking edges, published to the configured tracker —
    edges as text in one file per ticket locally, or native blocking links on a real tracker.

[triage]
    Source: mattpocock skills
    What it does: Moves incoming issues and outside pull requests through a triage process:
    categorize, verify, question if needed, and write clear briefs ready for an agent to act on.
    When to use: Your issue queue is piling up and you want it sorted and made actionable.
    Search terms: triage issues, sort bug reports, categorize issues, pull request triage, issue
    queue, bug tracker, action briefs
    Original description: Move issues and external PRs through a state machine of triage roles —
    categorise, verify, grill if needed, and write agent-ready briefs.

[update-implementation-plan]
    Source: awesome-copilot
    What it does: Updates an existing implementation plan to reflect new or changed requirements
    for features, refactoring, upgrades, or infrastructure.
    When to use: Requirements shifted and your written plan needs to catch up.
    Search terms: update plan, revise plan, change requirements, implementation plan, plan
    changes, refactor plan, roadmap update
    Original description: Update an existing implementation plan file with new or update
    requirements to provide new features, refactoring existing code or upgrading packages,
    design, architecture or infrastructure.

[update-specification]
    Source: awesome-copilot
    What it does: Updates an existing specification document to reflect new requirements or
    changes in the code, keeping it readable for AI tools.
    When to use: Your spec is out of date with what the software now does or needs to do.
    Search terms: update spec, revise specification, requirements change, keep docs current,
    spec maintenance, documentation update
    Original description: Update an existing specification file for the solution, optimized for
    Generative AI consumption based on new requirements or updates to any existing code.

[validate-changes-match-specs]
    Source: warp common-skills
    What it does: Checks that a branch or pull request actually matches the product, technical,
    and security specs it introduced, and helps resolve any mismatches.
    When to use: You are finishing a spec-driven change and want to confirm code and specs
    agree.
    Search terms: spec validation, code matches spec, pull request review, requirements check,
    security spec, finish feature, mismatch
    Original description: Validate that a branch or pull request implementation matches
    introduced product, technical, security, and related specs. Use when reviewing or finishing
    a spec-driven change and resolving mismatches between checked-in specs and implementation.

[wayfinder]
    Source: mattpocock skills
    What it does: Plans a huge body of work, bigger than one session can hold, as a shared map
    of decision tickets on your issue tracker, then resolves them one at a time until the path
    is clear.
    When to use: You face a massive project with many open decisions and need a way to work
    through them methodically.
    Search terms: large project planning, decision tickets, roadmap, big initiative, issue
    tracker, open decisions, long-term plan, project map
    Original description: Plan a huge chunk of work — more than one agent session can hold — as
    a shared map of decision tickets on your issue tracker, and resolve them one at a time until
    the way to the destination is clear.

[workshop-create]
    Source: awesome-copilot
    What it does: Creates a new workshop workspace, either from an existing local folder or as a
    new private GitHub repository, without nesting repos inside each other.
    When to use: You are starting a new shared workshop for AI-assisted work and need its home
    set up.
    Search terms: new workshop, create repo, github repository, workspace setup, private repo,
    project folder, start workshop
    Original description: Create a new workshop or use an existing directory as one. Handles two
    paths: (A) use an existing local directory the operator points at, or (B) create a new
    private GitHub repo in the signed-in account. Never creates a repo inside another repo.

[writing-plans]
    Source: obra superpowers
    What it does: Writes a detailed implementation plan from a spec or requirements for a multi-
    step task before any code is touched.
    When to use: You have requirements in hand and want a plan before development starts.
    Search terms: write a plan, implementation plan, plan before coding, multi-step task,
    development plan, requirements to plan, task breakdown
    Original description: Use when you have a spec or requirements for a multi-step task, before
    touching code
