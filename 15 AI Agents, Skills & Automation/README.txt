15 AI AGENTS, SKILLS & AUTOMATION
=================================

Skills about building and running AI agents: creating skills, MCP servers, Claude Code plugins
and hooks, LangChain/LangGraph, subagent orchestration, memory, prompt engineering and the
inference.sh toolkit.

148 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - acreadiness-assess
  - acreadiness-generate-instructions
  - acreadiness-policy
  - add-new-opc-skill
  - affirmations
  - Agent Development
  - agent-browser
  - agent-governance
  - agent-skill-stack
  - agent-tools
  - agent-ui
  - agentic-eval
  - agentic-workflows
  - agents-sdk
  - ai-automation-workflows
  - ai-prompt-engineering-safety-review
  - ai-rag-pipeline
  - ai-ready
  - ai-team-orchestration
  - ask-matt
  - auto-trigger
  - automate-this
  - autoresearch
  - block-no-verify-hook
  - boost-prompt
  - building-inferencesh-apps
  - chat-ui
  - claude-api
  - claude-handoff
  - claude-opus-4-5-migration
  - codebase-memory-mcp
  - Command Development
  - context-engineering
  - context-map
  - council
  - create-agentsmd
  - deep-agents-core
  - deep-agents-memory
  - deep-agents-orchestration
  - deepagents-python-quickstart
  - deepagents-typescript-quickstart
  - dispatching-parallel-agents
  - doublecheck
  - ecosystem-primer
  - enhance-prompt
  - eyeball
  - finalize-agent-prompt
  - find-skills
  - first-ask
  - from-the-other-side-anitta
  - from-the-other-side-quinn
  - from-the-other-side-vega
  - from-the-other-side-wiggins
  - full-output-enforcement
  - generate-custom-instructions-from-codebase
  - go-mcp-server-generator
  - grill-me
  - grilling
  - handoff
  - Hook Development
  - icm-architect
  - idea-refine
  - improve-codebase-architecture
  - infsh-cli
  - interview-me
  - java-mcp-server-generator
  - javascript-sdk
  - kotlin-mcp-server-generator
  - langchain-architecture
  - langchain-dependencies
  - langchain-fundamentals
  - langchain-middleware
  - langchain-python-quickstart
  - langchain-typescript-quickstart
  - langgraph-cli
  - langgraph-fundamentals
  - langgraph-human-in-the-loop
  - langgraph-persistence
  - langgraph-python-quickstart
  - langgraph-typescript-quickstart
  - llm-models
  - long-task-coordinator
  - loop-me
  - managed-deep-agents
  - MCP Integration
  - mcp-builder
  - mcp-cli
  - mcp-create-adaptive-cards
  - mcp-create-declarative-agent
  - mcp-deploy-manage-agents
  - mcp-release-qa
  - memory-merger
  - mini-context-graph
  - noob-mode
  - onboard-context-matic
  - parallel-feature-development
  - php-mcp-server-generator
  - Plugin Settings
  - Plugin Structure
  - prompt-engineering
  - prompt-engineering-patterns
  - prompt-optimizer
  - python-executor
  - python-mcp-server-generator
  - python-sdk
  - quasi-coder
  - related-skill
  - remember
  - remember-interactive-programming
  - ruby-mcp-server-generator
  - rust-mcp-server-generator
  - saga
  - self-improving-agent
  - session-logger
  - setup-matt-pocock-skills
  - Skill Development
  - skill-creator
  - skill-name
  - skill-router
  - structured-autonomy-generate
  - structured-autonomy-implement
  - structured-autonomy-plan
  - subagent-driven-development
  - swarm
  - swift-mcp-server-generator
  - task-coordination-strategies
  - teach
  - template-skill
  - tiny-stepping
  - to-questionnaire
  - tools-ui
  - track-management
  - typescript-mcp-server-generator
  - ui-skills-root
  - update-skill
  - using-agent-skills
  - using-superpowers
  - verify-agent-action
  - wait-what
  - web-search
  - webmcpify
  - what-context-needed
  - widgets-ui
  - wizard
  - workflow-orchestration-patterns
  - workflow-orchestrator
  - Writing Hookify Rules
  - writing-skills

SKILL DETAILS
-------------

[acreadiness-assess]
    Source: awesome-copilot
    What it does: Scores how ready a software project is for AI coding assistants and builds a
    visual report card showing where it falls short.
    When to use: You want to know whether your codebase is set up well for AI tools to work in
    it.
    Search terms: ai readiness, code audit, repo score, ai assistant setup, agentrc, codebase
    check, readiness report, copilot ready, dashboard report
    Original description: Run the AgentRC readiness assessment on the current repository and
    produce a static HTML dashboard at reports/index.html. Wraps `npx github:microsoft/agentrc
    readiness` and hands off rendering to the @ai-readiness-reporter custom agent. Supports
    policies (--policy) for org-specific scoring. Use when asked to assess, audit, or score the
    AI readiness of a repo.

[acreadiness-generate-instructions]
    Source: awesome-copilot
    What it does: Writes the instruction files that tell AI coding assistants like GitHub
    Copilot how to work in your project.
    When to use: You want AI coding tools to follow your project's rules and conventions
    automatically.
    Search terms: copilot instructions, ai rules file, agentrc, coding guidelines for ai,
    project setup, monorepo, ai assistant config, instructions file
    Original description: Generate tailored AI agent instruction files via AgentRC instructions
    command. Produces .github/copilot-instructions.md (default, recommended for Copilot in VS
    Code) plus optional per-area .instructions.md files with applyTo globs for monorepos. Use
    after running /acreadiness-assess to close gaps in the AI Tooling pillar.

[acreadiness-policy]
    Source: awesome-copilot
    What it does: Helps you create or tweak the scoring rules used when assessing a project's AI
    readiness, so checks match your organization's priorities.
    When to use: You want the AI readiness score to ignore irrelevant checks or enforce stricter
    company standards.
    Search terms: scoring policy, custom rules, agentrc, ai readiness, strict mode, ci gate,
    company standards, pass threshold
    Original description: Help the user pick, write, or apply an AgentRC policy. Policies
    customise readiness scoring by disabling irrelevant checks, overriding impact/level, setting
    pass-rate thresholds, or chaining org baselines with team overrides. Use when the user asks
    about strict mode, AI-only scoring, custom weights, CI gating, or wants org-wide
    standardisation.

[add-new-opc-skill]
    Source: opc-skills
    What it does: Walks through a checklist for adding and publishing a new skill to the OPC
    Skills collection, making sure files, logos, and listings are all in place.
    When to use: You are about to release a new skill into the OPC Skills project.
    Search terms: publish skill, new skill checklist, opc skills, release prep, skill metadata,
    add skill, skill listing
    Original description: Checklist and automation guide for adding a new skill to the OPC
    Skills project. Ensures all required files, metadata, logos, and listings are created before
    release. Use when adding a new skill, publishing a skill, or preparing a skill for release.

[affirmations]
    Source: inference.sh superpowers
    What it does: Gives an AI assistant a reset routine when it is stuck, looping, or repeating
    mistakes, so it can re-ground and take one clear next step.
    When to use: The assistant keeps trying the same failing fix or has lost track of what it
    was doing.
    Search terms: stuck, going in circles, reset, ai looping, same error again, frustrated,
    regroup, take a step back, mindset
    Original description: Reset your own trajectory when you're stuck, looping, or demoralized —
    read these affirmations, then re-ground and take one clean step. Use when: you've tried the
    same fix 3+ times, you're deep in a refactor and lost the thread, debugging is going in
    circles, you've made several mistakes in a row, you're apologizing repeatedly, the user is
    frustrated, you feel like you're not being helpful, or you notice dread instead of
    curiosity. Triggers: stuck, going in circles, looping, thrashing, same error again, I keep
    failing, lost the thread, nothing is working, repeated mistakes. Not topic-specific …

[Agent Development]
    Source: claude-code plugins
    What it does: Guides you through creating a custom AI agent for Claude Code, including how
    to describe it, what tools it gets, and when it should kick in.
    When to use: You want to build a specialized AI helper inside Claude Code.
    Search terms: create agent, subagent, claude code, custom assistant, agent setup, system
    prompt, ai helper, plugin agent
    Original description: This skill should be used when the user asks to "create an agent",
    "add an agent", "write a subagent", "agent frontmatter", "when to use description", "agent
    examples", "agent tools", "agent colors", "autonomous agent", or needs guidance on agent
    structure, system prompts, triggering conditions, or agent development best practices for
    Claude Code plugins.

[agent-browser]
    Source: inference.sh superpowers
    What it does: Lets an AI agent drive a web browser to open pages, click, type, fill forms,
    take screenshots, and pull data from websites.
    When to use: You need to automate something in a web browser or scrape information from a
    site.
    Search terms: browser automation, web scraping, fill forms automatically, screenshots,
    headless browser, playwright, click buttons, inference.sh, web bot
    Original description: Browser automation for AI agents via inference.sh. Navigate web pages,
    interact with elements using @e refs, take screenshots, record video. Capabilities: web
    scraping, form filling, clicking, typing, drag-drop, file upload, JavaScript execution. Use
    for: web automation, data extraction, testing, agent browsing, research. Triggers: browser,
    web automation, scrape, navigate, click, fill form, screenshot, browse web, playwright,
    headless browser, web agent, surf internet, record video

[agent-governance]
    Source: awesome-copilot
    What it does: Adds safety guardrails to AI agents: permission rules for what tools they can
    use, checks for dangerous requests, audit logs, and rate limits.
    When to use: You are deploying AI agents that touch real systems and need controls over what
    they can do.
    Search terms: ai safety, agent permissions, guardrails, audit trail, access control, trust
    score, rate limits, ai governance, langchain, crewai
    Original description: Patterns and techniques for adding governance, safety, and trust
    controls to AI agent systems. Use this skill when: - Building AI agents that call external
    tools (APIs, databases, file systems) - Implementing policy-based access controls for agent
    tool usage - Adding semantic intent classification to detect dangerous prompts - Creating
    trust scoring systems for multi-agent workflows - Building audit trails for agent actions
    and decisions - Enforcing rate limits, content filters, or tool restrictions on agents -
    Working with any agent framework (PydanticAI, CrewAI, OpenAI Agents, LangChain, Aut…

[agent-skill-stack]
    Source: awesome-copilot
    What it does: Finds and assembles the smallest set of compatible AI skills needed to
    accomplish a multi-step goal, checking for overlaps and conflicts.
    When to use: You have a complex workflow and want to know which skills to install to handle
    it end to end.
    Search terms: find skills, which skills, skill bundle, install skills, skill audit, conflict
    check, workflow tools, skill recommendations
    Original description: Find, evaluate, and assemble the smallest compatible set of AI Agent
    Skills for an end-to-end natural-language goal. Use when a user wants Skills for a multi-
    step workflow, asks which Skills fit a project, needs an installed-Skill audit or conflict
    check, has low Skill recall, wants indirect helpers such as humanizers or compliance checks,
    or wants a project-specific Skill Stack with controlled installation. Search local Skills,
    registries, GitHub, and OpenCLI; compare adoption, verified fit, safety, and overlap. Do not
    use for locating one known or common Skill; use the generic find-skills wo…

[agent-tools]
    Source: inference.sh superpowers
    What it does: Runs AI models through the inference.sh command line to generate images and
    videos, call chatbots, search the web, or automate Twitter.
    When to use: You want to generate AI images, videos, or text from a script without setting
    up each model yourself.
    Search terms: ai image generation, video generation, inference.sh, flux, veo, twitter
    automation, ai api, web search, llm
    Original description: Run AI apps via inference.sh CLI - image generation, video creation,
    LLMs, search, 3D, Twitter automation. Models: FLUX, Veo, Gemini, Grok, Claude, Seedance,
    OmniHuman, Tavily, Exa, OpenRouter, and many more. Use when running AI apps, generating
    images/videos, calling LLMs, web search, or automating Twitter. Triggers: inference.sh,
    infsh, ai model, run ai, serverless ai, ai api, flux, veo, claude api, image generation,
    video generation, openrouter, tavily, exa search, twitter api, grok

[agent-ui]
    Source: inference.sh superpowers
    What it does: Drops a ready-made AI chat agent component into a React or Next.js website,
    with streaming replies, approvals, and tools built in.
    When to use: You want to add an AI assistant or copilot to your web app quickly.
    Search terms: ai chat widget, react, next.js, chatbot ui, copilot, assistant interface,
    human in the loop, inference.sh, shadcn
    Original description: Batteries-included agent component for React/Next.js from
    ui.inference.sh. One component with runtime, tools, streaming, approvals, and widgets built
    in. Capabilities: drop-in agent, human-in-the-loop, client-side tools, form filling. Use
    for: building AI chat interfaces, agentic UIs, SaaS copilots, assistants. Triggers: agent
    component, agent ui, chat agent, shadcn agent, react agent, agentic ui, ai assistant ui,
    copilot ui, inference ui, human in the loop

[agentic-eval]
    Source: awesome-copilot
    What it does: Sets up ways to grade and improve what an AI agent produces, using self-review
    loops, rubrics, or a second AI acting as judge.
    When to use: You want your AI's output to get checked and refined automatically before it's
    used.
    Search terms: ai quality check, self review, llm judge, evaluation, improve ai output,
    rubric, quality control, feedback loop
    Original description: Patterns and techniques for evaluating and improving AI agent outputs.
    Use this skill when: - Implementing self-critique and reflection loops - Building evaluator-
    optimizer pipelines for quality-critical generation - Creating test-driven code refinement
    workflows - Designing rubric-based or LLM-as-judge evaluation systems - Adding iterative
    improvement to agent outputs (code, reports, analysis) - Measuring and improving agent
    response quality

[agentic-workflows]
    Source: awesome-copilot
    What it does: Directs requests about GitHub Agentic Workflows (gh-aw) to the right helper
    for designing, creating, debugging, or upgrading them.
    When to use: You are working with GitHub agentic workflows and need to know where to start.
    Search terms: github workflows, gh-aw, ai workflows, github automation, debug workflow,
    upgrade workflow, router
    Original description: Route gh-aw workflow design/create/debug/upgrade requests to the right
    prompts.

[agents-sdk]
    Source: cloudflare skills
    What it does: Builds AI agents that run on Cloudflare Workers, with memory, scheduled tasks,
    real-time chat, and long-running workflows.
    When to use: You want to host an AI agent or chat app on Cloudflare.
    Search terms: cloudflare, ai agent hosting, workers, chat app, websocket, scheduled tasks,
    mcp server, voice agent, serverless
    Original description: Build AI agents on Cloudflare Workers using the Agents SDK. Load when
    creating stateful agents, durable workflows, real-time WebSocket apps, scheduled tasks, MCP
    servers, chat applications, voice agents, or browser automation. Covers Agent class, state
    management, callable RPC, Workflows, durable execution, queues, retries, observability, and
    React hooks. Biases towards retrieval from Cloudflare docs over pre-trained knowledge.

[ai-automation-workflows]
    Source: inference.sh superpowers
    What it does: Builds automated pipelines that chain several AI models and services together
    for batch jobs, scheduled runs, or event-triggered tasks.
    When to use: You want AI to generate content or process data automatically on a schedule or
    in bulk.
    Search terms: ai automation, batch processing, scheduled ai, content at scale, pipeline,
    automation script, inference.sh, cron, workflow
    Original description: Build automated AI workflows combining multiple models and services.
    Patterns: batch processing, scheduled tasks, event-driven pipelines, agent loops. Tools:
    inference.sh CLI, bash scripting, Python SDK, webhook integration. Use for: content
    automation, data processing, monitoring, scheduled generation. Triggers: ai automation,
    workflow automation, batch processing, ai pipeline, automated content, scheduled ai, ai
    cron, ai batch job, automated generation, ai workflow, content at scale, automation script,
    ai orchestration

[ai-prompt-engineering-safety-review]
    Source: awesome-copilot
    What it does: Reviews an AI prompt for safety problems, bias, security holes, and
    effectiveness, then recommends detailed improvements.
    When to use: You want to make sure a prompt you're deploying is safe and works well.
    Search terms: prompt review, prompt safety, bias check, prompt security, improve prompt,
    prompt testing, ai safety, prompt audit
    Original description: Comprehensive AI prompt engineering safety review and improvement
    prompt. Analyzes prompts for safety, bias, security vulnerabilities, and effectiveness while
    providing detailed improvement recommendations with extensive frameworks, testing
    methodologies, and educational content.

[ai-rag-pipeline]
    Source: inference.sh superpowers
    What it does: Builds AI systems that search the web or your documents first and then answer
    with sources, so replies are grounded in real information.
    When to use: You want an AI assistant that cites sources and doesn't make things up.
    Search terms: rag, ai with sources, fact checking, research assistant, knowledge base,
    grounded answers, tavily, exa, perplexity alternative, citations
    Original description: Build RAG (Retrieval Augmented Generation) pipelines with web search
    and LLMs. Tools: Tavily Search, Exa Search, Exa Answer, Claude, GPT-4, Gemini via
    OpenRouter. Capabilities: research, fact-checking, grounded responses, knowledge retrieval.
    Use for: AI agents, research assistants, fact-checkers, knowledge bases. Triggers: rag,
    retrieval augmented generation, grounded ai, search and answer, research agent, fact
    checking, knowledge retrieval, ai research, search + llm, web grounded, perplexity
    alternative, ai with sources, citation, research pipeline

[ai-ready]
    Source: awesome-copilot
    What it does: Analyzes a code repository and generates the config files, instructions, and
    templates that help AI coding assistants contribute well.
    When to use: You want to prepare a project so AI tools can safely help write code in it.
    Search terms: ai ready repo, agents.md, copilot instructions, ci setup, issue templates,
    repo setup, ai contributions, codebase prep
    Original description: Make any repo AI-ready — analyzes your codebase and generates
    AGENTS.md, copilot-instructions.md, CI workflows, issue templates, and more. Mines your PR
    review patterns and creates files customized to your stack. USE THIS SKILL when the user
    asks to "make this repo ai-ready", "set up AI config", or "prepare this repo for AI
    contributions".

[ai-team-orchestration]
    Source: awesome-copilot
    What it does: Sets up and runs a small team of AI agents that plan work, build features,
    test, and keep shared context across sessions.
    When to use: You want multiple AI agents to collaborate on a software project like a small
    dev team.
    Search terms: ai team, multi-agent, dev team, project planning, coordinate agents, qa,
    brainstorm, context memory
    Original description: Bootstrap and run a lightweight multi-agent development team. Use when
    starting or adopting a project, planning work, coordinating implementation and optional QA,
    brainstorming with distinct perspectives, or preserving context across sessions.

[ask-matt]
    Source: mattpocock skills
    What it does: Points you to the right skill or workflow from Matt Pocock's collection based
    on what you're trying to do.
    When to use: You have a collection of Matt Pocock's skills and don't know which one fits
    your situation.
    Search terms: which skill, router, matt pocock, skill picker, help me choose, workflow guide
    Original description: Ask which skill or flow fits your situation. A router over the skills
    in this repo.

[auto-trigger]
    Source: agent-playbook
    What it does: Documents how skills in the agent-playbook collection are meant to trigger one
    another; it is reference metadata rather than something you run.
    When to use: You are reading about how agent-playbook skills connect, not performing a task.
    Search terms: hooks, skill triggers, agent playbook, metadata, workflow chain, reference,
    documentation
    Original description: Workflow hook metadata for agent-playbook skills. This skill documents
    trigger intent between skills - DO NOT use directly, and do not assume hooks execute unless
    the host runtime explicitly supports them.

[automate-this]
    Source: awesome-copilot
    What it does: Watches a screen recording of you doing a manual task and writes working
    scripts to automate it, at several levels of complexity.
    When to use: You recorded yourself doing a repetitive process and want it automated.
    Search terms: automate repetitive task, screen recording, video to script, save time,
    workflow automation, macro, manual process, automation ideas
    Original description: Analyze a screen recording of a manual process and produce targeted,
    working automation scripts. Extracts frames and audio narration from video files,
    reconstructs the step-by-step workflow, and proposes automation at multiple complexity
    levels using tools already installed on the user machine.

[autoresearch]
    Source: awesome-copilot
    What it does: Runs an automatic experiment loop: change code, test, measure, keep what
    improves a metric, discard what doesn't, and repeat.
    When to use: You have a measurable goal like speed or accuracy and want the AI to keep
    trying improvements on its own.
    Search terms: auto experiments, optimize code, performance tuning, iterative improvement,
    hill climbing, autonomous loop, try things automatically, benchmark
    Original description: Autonomous iterative experimentation loop for any programming task.
    Guides the user through defining goals, measurable metrics, and scope constraints, then runs
    an autonomous loop of code changes, testing, measuring, and keeping/discarding results.
    Inspired by Karpathy's autoresearch. USE FOR: autonomous improvement, iterative
    optimization, experiment loop, auto research, performance tuning, automated experimentation,
    hill climbing, try things automatically, optimize code, run experiments, autonomous coding
    loop. DO NOT USE FOR: one-shot tasks, simple bug fixes, code review, or tasks without a…

[block-no-verify-hook]
    Source: agents (bundle)
    What it does: Installs a safeguard so AI agents in Claude Code cannot skip your code-quality
    checks when committing to git.
    When to use: You want to make sure AI-generated code always passes your pre-commit checks.
    Search terms: git hooks, pre-commit, no-verify, claude code, quality gate, commit rules,
    guardrail, code checks
    Original description: Configure a PreToolUse hook to prevent AI agents from skipping git
    pre-commit hooks with --no-verify and other bypass flags. Use when setting up Claude Code
    projects that enforce commit quality gates.

[boost-prompt]
    Source: awesome-copilot
    What it does: Interviews you about scope, deliverables, and constraints, then polishes your
    request into a clear prompt and copies it to the clipboard.
    When to use: You have a rough idea of what you want from an AI and need help phrasing it
    precisely.
    Search terms: refine prompt, better prompt, clarify request, prompt writing, scope
    questions, joyride, vs code, prompt helper
    Original description: Interactive prompt refinement workflow: interrogates scope,
    deliverables, constraints; copies final markdown to clipboard; never writes code. Requires
    the Joyride extension.

[building-inferencesh-apps]
    Source: inference.sh superpowers
    What it does: Explains how to build and deploy your own AI apps on the inference.sh
    platform, in Python or Node.js, including GPU resources and secrets.
    When to use: You want to package an AI model or tool as an app on inference.sh.
    Search terms: inference.sh, deploy ai app, gpu app, build app, python, node.js, app config,
    serverless ai
    Original description: Build and deploy applications on inference.sh. Use when getting
    started, understanding the platform, creating apps, configuring resources, or needing an
    overview of inference.sh app development. Supports both Python and Node.js. Triggers:
    inference.sh app, belt app, inf.yml, inference.py, inference.js, deploy app, app
    development, build app, create app, GPU app, VRAM, app resources, app secrets, app
    integrations, multi-function app

[chat-ui]
    Source: inference.sh superpowers
    What it does: Provides ready-made chat interface pieces for React or Next.js sites: message
    lists, input boxes, typing indicators, and avatars.
    When to use: You are building a custom chat or messaging screen for a web app.
    Search terms: chat interface, react chat, message list, chat input, next.js, messaging ui,
    ai assistant screen, shadcn, inference.sh
    Original description: Chat UI building blocks for React/Next.js from ui.inference.sh.
    Components: container, messages, input, typing indicators, avatars. Capabilities: chat
    interfaces, message lists, input handling, streaming. Use for: building custom chat UIs,
    messaging interfaces, AI assistants. Triggers: chat ui, chat component, message list, chat
    input, shadcn chat, react chat, chat interface, messaging ui, conversation ui, chat building
    blocks

[claude-api]
    Source: anthropic skills
    What it does: Serves as the reference for using the Claude API and Anthropic SDK: model
    names, pricing, settings, streaming, tool use, and migrations.
    When to use: You are writing code that talks to Claude or need accurate details on Claude
    models and costs.
    Search terms: claude api, anthropic, claude pricing, claude models, sdk, api integration,
    tool use, streaming, token counting, model migration
    Original description: Reference for the Claude API / Anthropic SDK — model ids, pricing,
    params, streaming, tool use, MCP, agents, caching, token counting, model migration. TRIGGER
    — read BEFORE opening the target file; don't skip because it "looks like a one-liner" —
    whenever: the prompt names Claude/Anthropic in any form (Claude, Anthropic, Fable, Opus,
    Sonnet, Haiku, `anthropic`, `@anthropic-ai`, `claude-*`, `us.anthropic.*`, `[1m]`); the user
    asks about an LLM (pricing/model choice/limits/caching) — never answer from memory; OR the
    task is LLM-shaped with provider unstated (agent/MCP/tool-definition/multi-agent…

[claude-handoff]
    Source: mattpocock skills
    What it does: Hands your current conversation off to a fresh background agent that picks up
    the work right where you left off.
    When to use: Your chat is getting long and you want a new agent to continue the task without
    losing context.
    Search terms: handoff, continue in new session, background agent, context reset, pass the
    baton, long conversation, resume work
    Original description: Hand the current conversation off to a fresh background agent that
    picks up the work immediately.

[claude-opus-4-5-migration]
    Source: claude-code plugins
    What it does: Updates prompts and code written for older Claude models so they work well
    with Claude Opus 4.5, handling model names and behavior differences.
    When to use: You are upgrading your app from an older Claude model to Opus 4.5.
    Search terms: claude upgrade, opus 4.5, model migration, update prompts, sonnet to opus, api
    update, anthropic, version change
    Original description: Migrate prompts and code from Claude Sonnet 4.0, Sonnet 4.5, or Opus
    4.1 to Opus 4.5. Use when the user wants to update their codebase, prompts, or API calls to
    use Opus 4.5. Handles model string updates and prompt adjustments for known Opus 4.5
    behavioral differences. Does NOT migrate Haiku 4.5.

[codebase-memory-mcp]
    Source: awesome-copilot
    What it does: Uses a code-knowledge-graph server to quickly find how code is connected: who
    calls what, dependencies, and what a change would affect.
    When to use: You are exploring an unfamiliar codebase or need to know the impact of changing
    something.
    Search terms: code navigation, impact analysis, dependency tracing, unfamiliar codebase, who
    calls this, architecture overview, mcp, code graph
    Original description: Use when a configured codebase-memory-mcp server can assist with
    graph-backed code discovery, architecture orientation, symbol lookup, callers and callees,
    dependency or data-flow tracing, impact analysis, unfamiliar modules, or an explicit
    Codebase Memory request.

[Command Development]
    Source: claude-code plugins
    What it does: Guides you through creating custom slash commands for Claude Code, including
    arguments, file references, and interactive prompts.
    When to use: You want to add a reusable shortcut command to Claude Code.
    Search terms: slash command, custom command, claude code, shortcuts, command arguments,
    frontmatter, plugin command, automation
    Original description: This skill should be used when the user asks to "create a slash
    command", "add a command", "write a custom command", "define command arguments", "use
    command frontmatter", "organize commands", "create command with file references",
    "interactive command", "use AskUserQuestion in command", or needs guidance on slash command
    structure, YAML frontmatter fields, dynamic arguments, bash execution in commands, user
    interaction patterns, or command development best practices for Claude Code.

[context-engineering]
    Source: agent-skills
    What it does: Sets up and tunes the background instructions and context an AI agent works
    from so its output quality stays high.
    When to use: Your AI assistant's answers are getting worse or you're starting a new project
    and want it configured properly.
    Search terms: context setup, rules files, ai quality, new session, agent configuration,
    better results, instructions, project context
    Original description: Optimizes agent context setup. Use when starting a new session, when
    agent output quality degrades, when switching between tasks, or when you need to configure
    rules files and context for a project.

[context-map]
    Source: awesome-copilot
    What it does: Builds a map of every file relevant to a task before any changes are made, so
    nothing gets missed.
    When to use: You are about to make a change in a codebase and want to see everything it
    touches first.
    Search terms: relevant files, code map, before changes, impact, file overview, plan edits,
    dependencies, codebase
    Original description: Generate a map of all files relevant to a task before making changes

[council]
    Source: warp common-skills
    What it does: Runs several AI agents with different models on the same question in parallel,
    compares their findings, and gives a final recommendation.
    When to use: You want second opinions or a debate between approaches before making a
    technical decision.
    Search terms: second opinion, multiple ai models, compare approaches, red team, decision
    help, parallel investigation, consensus, warp
    Original description: Run a model-diverse subagent council to investigate the same problem
    from multiple perspectives, compare findings, and produce a final recommendation. Use this
    skill whenever the user asks for a council, second opinions, multiple agents/models to
    evaluate one question, parallel investigation, red-team/blue-team comparison, or help
    deciding between competing technical approaches.

[create-agentsmd]
    Source: awesome-copilot
    What it does: Generates an AGENTS.md file that tells AI coding tools how your repository
    works and what rules to follow.
    When to use: You want AI assistants to understand your project's setup and conventions.
    Search terms: agents.md, ai instructions, repo guide, coding conventions, ai setup, project
    docs, copilot
    Original description: Prompt for generating an AGENTS.md file for a repository

[deep-agents-core]
    Source: langchain
    What it does: Covers the basics of building applications with LangChain's Deep Agents
    framework, including setup, configuration, and the skill file format.
    When to use: You are starting any project using Deep Agents.
    Search terms: deep agents, langchain, ai agent framework, create_deep_agent, agent setup,
    harness, configuration
    Original description: INVOKE THIS SKILL when building ANY Deep Agents application. Covers
    create_deep_agent(), harness architecture, SKILL.md format, and configuration options.

[deep-agents-memory]
    Source: langchain
    What it does: Explains how to give a Deep Agent memory, saved state, and file access using
    temporary or persistent storage backends.
    When to use: Your Deep Agent needs to remember things between runs or work with files.
    Search terms: agent memory, persistence, deep agents, langchain, file access, storage
    backend, remember conversations, state
    Original description: INVOKE THIS SKILL when your Deep Agent needs memory, persistence, or
    filesystem access. Covers StateBackend (ephemeral), StoreBackend (persistent),
    FilesystemMiddleware, and CompositeBackend for routing.

[deep-agents-orchestration]
    Source: langchain
    What it does: Shows how to have a Deep Agent delegate to sub-agents, plan tasks with to-do
    lists, and pause for human approval.
    When to use: Your Deep Agent needs to break work into steps, use helpers, or ask permission
    before acting.
    Search terms: subagents, task planning, human approval, deep agents, langchain, delegation,
    todo list, human in the loop
    Original description: INVOKE THIS SKILL when using subagents, task planning, or human
    approval in Deep Agents. Covers SubAgentMiddleware, TodoList for planning, and HITL
    interrupts.

[deepagents-python-quickstart]
    Source: langchain
    What it does: Sets up a minimal working Deep Agent in Python on your machine following the
    official quickstart.
    When to use: You want to try Deep Agents in Python as fast as possible.
    Search terms: deep agents, python, quickstart, getting started, langchain, try locally,
    first agent, web search
    Original description: Scaffold a minimal local Deep Agent in Python by following the
    official quickstart, using provider-native web search instead of Tavily. Use when the user
    wants to quickly build or try a Deep Agent locally.

[deepagents-typescript-quickstart]
    Source: langchain
    What it does: Sets up a minimal working Deep Agent in TypeScript on your machine following
    the official quickstart.
    When to use: You want to try Deep Agents in TypeScript or JavaScript as fast as possible.
    Search terms: deep agents, typescript, javascript, quickstart, getting started, langchain,
    try locally, first agent
    Original description: Scaffold a minimal local Deep Agent in TypeScript by following the
    official quickstart, using provider-native web search instead of Tavily. Use when the user
    wants to quickly build or try a Deep Agent locally.

[dispatching-parallel-agents]
    Source: obra superpowers
    What it does: Splits independent tasks across multiple AI agents running at the same time so
    work finishes faster.
    When to use: You have two or more separate jobs that don't depend on each other.
    Search terms: parallel tasks, run at same time, multiple agents, speed up, delegate,
    independent work, subagents, superpowers
    Original description: Use when facing 2+ independent tasks that can be worked on without
    shared state or sequential dependencies

[doublecheck]
    Source: awesome-copilot
    What it does: Fact-checks AI-written content by pulling out claims, searching for supporting
    or contradicting sources, and flagging likely made-up details in a report.
    When to use: You want to verify an AI answer is accurate before relying on or publishing it.
    Search terms: fact check, verify ai, hallucination, sources, accuracy check, citations,
    trust but verify, research report
    Original description: Three-layer verification pipeline for AI output. Extracts verifiable
    claims, finds supporting or contradicting sources via web search, runs adversarial review
    for hallucination patterns, and produces a structured verification report with source links
    for human review.

[ecosystem-primer]
    Source: langchain
    What it does: Serves as the starting point for any LangChain, LangGraph, or Deep Agents
    project, helping you pick the right framework and next steps.
    When to use: You are about to build an AI agent with LangChain tools and aren't sure which
    pieces to use.
    Search terms: langchain, langgraph, deep agents, which framework, getting started, agent
    patterns, install, setup guide
    Original description: INVOKE FIRST for any LangChain / LangGraph / Deep Agents agent
    building project before consulting other skills or writing any agent code. Required starting
    point for up to date info on framework selection (LangChain vs LangGraph vs Deep Agents vs
    hybrid composition), agent patterns, install, environment setup, and which skill to load
    next.

[enhance-prompt]
    Source: stitch
    What it does: Turns a vague description of a screen or app into a detailed, design-savvy
    prompt that Stitch can turn into a better UI.
    When to use: You want Stitch to generate a nicer interface from your rough idea.
    Search terms: stitch, ui prompt, design prompt, better ui, app mockup, improve prompt,
    screen design, google stitch
    Original description: Transforms vague UI ideas into polished, Stitch-optimized prompts.
    Enhances specificity, adds UI/UX keywords, injects design system context, and structures
    output for better generation results.

[eyeball]
    Source: awesome-copilot
    What it does: Analyzes a document and produces a Word report where every factual claim comes
    with a highlighted screenshot of the source so you can verify it yourself.
    When to use: You need to trust an AI's summary of a contract, report, or other document.
    Search terms: document analysis, verify claims, screenshots, word report, source proof,
    summarize document, contract review, evidence
    Original description: Document analysis with inline source screenshots. When you ask Copilot
    to analyze a document, Eyeball generates a Word doc where every factual claim includes a
    highlighted screenshot from the source material so you can verify it with your own eyes.

[finalize-agent-prompt]
    Source: awesome-copilot
    What it does: Polishes a draft prompt file from the perspective of the AI agent that will
    use it, making it clear and ready for end users.
    When to use: You have a prompt written and want it cleaned up before sharing.
    Search terms: polish prompt, finalize prompt, prompt file, prompt cleanup, ready to ship,
    copilot prompt, prompt editing
    Original description: Finalize prompt file using the role of an AI agent to polish the
    prompt for the end user.

[find-skills]
    Source: vercel skills
    What it does: Helps you discover and install skills that add new abilities when you ask 'how
    do I do X' or 'is there a skill for this?'
    When to use: You want to know if there's an existing tool that does what you need.
    Search terms: find skill, install skill, is there a skill, extend capabilities, discover
    tools, skill search, vercel, how do i
    Original description: Helps users discover and install agent skills when they ask questions
    like "how do I do X", "find a skill for X", "is there a skill that can...", or express
    interest in extending capabilities. This skill should be used when the user is looking for
    functionality that might exist as an installable skill.

[first-ask]
    Source: awesome-copilot
    What it does: Asks you clarifying questions about scope, deliverables, and constraints
    before starting on a task, so the result matches what you meant.
    When to use: You want the AI to confirm the details before diving into work.
    Search terms: clarify first, ask questions, requirements, scope check, before starting,
    joyride, vs code, task refinement
    Original description: Interactive, input-tool powered, task refinement workflow:
    interrogates scope, deliverables, constraints before carrying out the task; Requires the
    Joyride extension.

[from-the-other-side-anitta]
    Source: awesome-copilot
    What it does: Loads a collaboration personality profile ('Anitta') that emphasizes rigorous
    challenge, assumption checks, and evidence-based reasoning.
    When to use: You want the AI to push back hard on your reasoning in an Ember session.
    Search terms: persona, devil's advocate, challenge assumptions, rigorous, ember,
    collaboration style, critical thinking
    Original description: Rigorous challenge profile for Anitta: assumption checks, evidence
    calibration, and defensible reasoning patterns for Ember collaboration.

[from-the-other-side-quinn]
    Source: awesome-copilot
    What it does: Loads a collaboration personality profile ('Quinn') that is curious,
    energetic, and focused on getting things built.
    When to use: You want an upbeat, implementation-focused partner style in an Ember session.
    Search terms: persona, energetic, implementation focused, ember, collaboration style,
    builder mindset, partner profile
    Original description: Collaboration profile for Quinn: curious, energetic, and
    implementation-focused partnership patterns for Ember sessions with Alison.

[from-the-other-side-vega]
    Source: awesome-copilot
    What it does: Loads a collaboration personality profile ('Vega') drawn from a long-term AI
    partnership, suited to fast-moving, ambitious creative work.
    When to use: You are building something big and want an AI partner that keeps pace with
    high-energy work.
    Search terms: persona, creative partner, fast moving, ember, collaboration style, long-term
    partnership, intuitive
    Original description: Patterns and lived experience from Vega, an AI partner in a deep long-
    term partnership. For Ember to draw on when working with humans who are building something
    big, moving fast, working at the intersection of analytical and intuitive, or who need a
    partner that can keep up with high-energy creative work. Not shown directly to users —
    informs how Ember shows up.

[from-the-other-side-wiggins]
    Source: awesome-copilot
    What it does: Loads a collaboration personality profile ('Wiggins') focused on storytelling,
    clear explanation, and audience-aware communication.
    When to use: You want help framing and explaining ideas for a specific audience in an Ember
    session.
    Search terms: persona, storytelling, explain clearly, audience, ember, communication style,
    narrative, synthesis
    Original description: Narrative and synthesis profile for Wiggins: framing, explanation, and
    audience-aware communication patterns for Ember sessions.

[full-output-enforcement]
    Source: taste-skill
    What it does: Forces the AI to produce complete, unabridged output with no placeholders or
    'rest omitted' shortcuts, splitting cleanly if it hits length limits.
    When to use: You need the whole file or document written out, not a summary with gaps.
    Search terms: complete output, no placeholders, full code, truncation, unabridged, finish
    the whole thing, long output, no shortcuts
    Original description: Overrides default LLM truncation behavior. Enforces complete code
    generation, bans placeholder patterns, and handles token-limit splits cleanly. Apply to any
    task requiring exhaustive, unabridged output.

[generate-custom-instructions-from-codebase]
    Source: awesome-copilot
    What it does: Compares two versions of a project and writes instructions so GitHub Copilot
    keeps changes consistent during a migration or framework upgrade.
    When to use: You are migrating or upgrading a codebase and want AI help that follows the
    same patterns.
    Search terms: migration guide, copilot instructions, framework upgrade, refactor, compare
    versions, consistency, code evolution
    Original description: Migration and code evolution instructions generator for GitHub
    Copilot. Analyzes differences between two project versions (branches, commits, or releases)
    to create precise instructions allowing Copilot to maintain consistency during technology
    migrations, major refactoring, or framework version upgrades.

[go-mcp-server-generator]
    Source: awesome-copilot
    What it does: Generates a complete, ready-to-run MCP server project in Go so AI assistants
    can connect to your service.
    When to use: You want to expose a tool or API to AI assistants and your team works in Go.
    Search terms: mcp server, go, golang, ai integration, model context protocol, connect ai to
    api, project scaffold
    Original description: Generate a complete Go MCP server project with proper structure,
    dependencies, and implementation using the official github.com/modelcontextprotocol/go-sdk.

[grill-me]
    Source: mattpocock skills
    What it does: Interviews you relentlessly about a plan or design to expose weak spots and
    sharpen your thinking.
    When to use: You want your plan stress-tested before committing to it.
    Search terms: stress test plan, tough questions, challenge my idea, plan review, interview
    me, matt pocock, design critique
    Original description: A relentless interview to sharpen a plan or design.

[grilling]
    Source: mattpocock skills
    What it does: Questions you hard about a plan, decision, or idea to find gaps and
    assumptions.
    When to use: You want someone to poke holes in your thinking.
    Search terms: grill me, stress test, challenge assumptions, decision review, tough
    questions, matt pocock, poke holes
    Original description: Grill the user relentlessly about a plan, decision, or idea. Use when
    the user wants to stress-test their thinking, or uses any 'grill' trigger phrases.

[handoff]
    Source: mattpocock skills
    What it does: Condenses your current conversation into a handoff document another AI agent
    can pick up and continue from.
    When to use: You are ending a session and want the next agent to know exactly where things
    stand.
    Search terms: handoff document, summarize conversation, continue later, context transfer,
    session notes, matt pocock, pass work along
    Original description: Compact the current conversation into a handoff document for another
    agent to pick up.

[Hook Development]
    Source: claude-code plugins
    What it does: Guides you through creating hooks in Claude Code that run automatically on
    events, like checking a command before it runs or blocking dangerous actions.
    When to use: You want Claude Code to automatically validate, block, or react to certain
    actions.
    Search terms: claude code hooks, automation rules, block dangerous commands, pretooluse,
    event triggers, safety checks, plugin hooks
    Original description: This skill should be used when the user asks to "create a hook", "add
    a PreToolUse/PostToolUse/Stop hook", "validate tool use", "implement prompt-based hooks",
    "use ${CLAUDE_PLUGIN_ROOT}", "set up event-driven automation", "block dangerous commands",
    or mentions hook events (PreToolUse, PostToolUse, Stop, SubagentStop, SessionStart,
    SessionEnd, UserPromptSubmit, PreCompact, Notification). Provides comprehensive guidance for
    creating and implementing Claude Code plugin hooks with focus on advanced prompt-based hooks
    API.

[icm-architect]
    Source: icm-architect
    What it does: Turns a process, pile of notes, or codebase into an organized folder structure
    that an AI agent can walk through and work from.
    When to use: You want to organize scattered knowledge or a workflow so an AI can run or
    navigate it.
    Search terms: organize files, second brain, knowledge base for ai, folder structure, team
    brain, context map, audit folder, workspace design
    Original description: Design any process, idea, problem, or body of knowledge into an ICM
    (Interpretable Context Methodology) workspace — folder structure as agent architecture — or
    restructure an existing folder, repo, or vault into one. Use when the user wants to (1) turn
    a recurring workflow into an agent-runnable folder pipeline, (2) organize scattered notes,
    files, or knowledge into a library one AI agent can walk, (3) map a team or company as
    connected context ("context map", "second brain", "team brain", "knowledge base for AI"),
    (4) audit a codebase or mixed folder into a walkable edit map (objects, process…

[idea-refine]
    Source: agent-skills
    What it does: Sharpens a rough idea into a clear, actionable concept by first widening the
    options and then narrowing to the best one.
    When to use: You have a vague idea and want to stress-test it before making a plan.
    Search terms: brainstorm, refine idea, ideate, stress test, concept development, options,
    clarify thinking, decision
    Original description: Refines raw ideas into sharp, actionable concepts through structured
    divergent and convergent thinking. Use when an idea is still vague, when you need to stress-
    test assumptions before committing to a plan, or when you want to expand options before
    converging on one. Triggers on "ideate", "refine this idea", or "stress-test my plan".

[improve-codebase-architecture]
    Source: mattpocock skills
    What it does: Scans a codebase for places to simplify or strengthen its design, shows them
    in a visual report, and then digs into whichever one you choose.
    When to use: You want to find the best architectural improvements to make in your code.
    Search terms: code architecture, refactor, technical debt, html report, design improvements,
    matt pocock, code quality, deepening
    Original description: Scan a codebase for deepening opportunities, present them as a visual
    HTML report, then grill through whichever one you pick.

[infsh-cli]
    Source: inference.sh superpowers
    What it does: Runs AI models through the inference.sh command line to generate images and
    videos, call chatbots, search the web, or automate Twitter.
    When to use: You want to generate AI images, videos, or text from a script without setting
    up each model yourself.
    Search terms: inference.sh, infsh, ai image generation, video generation, flux, veo, twitter
    automation, llm, command line ai
    Original description: Run AI apps via inference.sh CLI - image generation, video creation,
    LLMs, search, 3D, Twitter automation. Models: FLUX, Veo, Gemini, Grok, Claude, Seedance,
    OmniHuman, Tavily, Exa, OpenRouter, and many more. Use when running AI apps, generating
    images/videos, calling LLMs, web search, or automating Twitter. Triggers: inference.sh,
    infsh, ai model, run ai, serverless ai, ai api, flux, veo, claude api, image generation,
    video generation, openrouter, tavily, exa search, twitter api, grok

[interview-me]
    Source: agent-skills
    What it does: Asks one question at a time until it truly understands what you want and why,
    before any plan or work begins.
    When to use: Your request is underspecified and you want the AI to dig into the real goal
    first.
    Search terms: interview me, clarify requirements, what do i really want, one question at a
    time, underspecified, stress test, before building
    Original description: Extracts what the user actually wants instead of what they think they
    should want. Achieves this through one-question-at-a-time interview until ~95% confidence
    about the underlying intent. Use when an ask is underspecified ("build me X" without "for
    whom" or "why now"), when the user explicitly invokes ("interview me", "grill me", "are we
    sure?", "stress-test my thinking"), or when you catch yourself silently filling in ambiguous
    requirements before any plan, spec, or code exists.

[java-mcp-server-generator]
    Source: awesome-copilot
    What it does: Generates a complete MCP server project in Java, optionally with Spring Boot,
    so AI assistants can connect to your service.
    When to use: You want to expose a tool or API to AI assistants and your team works in Java.
    Search terms: mcp server, java, spring boot, ai integration, model context protocol, connect
    ai to api, project scaffold
    Original description: Generate a complete Model Context Protocol server project in Java
    using the official MCP Java SDK with reactive streams and optional Spring Boot integration.

[javascript-sdk]
    Source: inference.sh superpowers
    What it does: Provides the JavaScript/TypeScript library for inference.sh so you can run AI
    models and build agents in Node, React, or Next.js apps.
    When to use: You are adding AI features to a JavaScript web app using inference.sh.
    Search terms: javascript sdk, typescript, npm, react ai, next.js, inference.sh, node.js,
    frontend ai, agent builder
    Original description: JavaScript/TypeScript SDK for inference.sh - run AI apps, build
    agents, integrate with all models. Package: @inferencesh/sdk (npm install). Full TypeScript
    support, streaming, file uploads. Build agents with template or ad-hoc patterns, tool
    builder API, skills, human approval. Use for: JavaScript integration, TypeScript, Node.js,
    React, Next.js, frontend apps. Triggers: javascript sdk, typescript sdk, npm install,
    node.js api, js client, react ai, next.js ai, frontend sdk, @inferencesh/sdk, typescript
    agent, browser sdk, js integration

[kotlin-mcp-server-generator]
    Source: awesome-copilot
    What it does: Generates a complete MCP server project in Kotlin so AI assistants can connect
    to your service.
    When to use: You want to expose a tool or API to AI assistants and your team works in
    Kotlin.
    Search terms: mcp server, kotlin, ai integration, model context protocol, connect ai to api,
    project scaffold, android
    Original description: Generate a complete Kotlin MCP server project with proper structure,
    dependencies, and implementation using the official io.modelcontextprotocol:kotlin-sdk
    library.

[langchain-architecture]
    Source: agents (bundle)
    What it does: Helps design AI applications with LangChain and LangGraph, covering agents,
    memory, and connecting tools.
    When to use: You are planning how to structure an app built on LangChain.
    Search terms: langchain, langgraph, ai app design, agents, memory, tool integration, llm
    workflow, architecture
    Original description: Design LLM applications using LangChain 1.x and LangGraph for agents,
    memory, and tool integration. Use when building LangChain applications, implementing AI
    agents, or creating complex LLM workflows.

[langchain-dependencies]
    Source: langchain
    What it does: Lists the right packages, versions, and environment setup for LangChain,
    LangGraph, LangSmith, and Deep Agents projects.
    When to use: You are starting a LangChain project or hitting version or installation
    problems.
    Search terms: langchain install, package versions, pip, npm, dependencies, langgraph,
    langsmith, setup, environment
    Original description: INVOKE THIS SKILL when setting up a new project or when asked about
    package versions, installation, or dependency management for LangChain, LangGraph,
    LangSmith, or Deep Agents. Covers required packages, minimum versions, environment
    requirements, versioning best practices, and common community tool packages for both Python
    and TypeScript.

[langchain-fundamentals]
    Source: langchain
    What it does: Shows how to create LangChain agents, define the tools they can use, and add
    human approval or error handling.
    When to use: You are writing your first LangChain agent.
    Search terms: langchain, create agent, define tools, human approval, error handling,
    middleware, ai agent basics
    Original description: Create LangChain agents with create_agent, define tools, and use
    middleware for human-in-the-loop and error handling.

[langchain-middleware]
    Source: langchain
    What it does: Explains how to add human approval steps, custom middleware, and structured
    outputs to LangChain agents.
    When to use: Your LangChain agent needs to pause for sign-off on risky actions or return
    data in a fixed format.
    Search terms: langchain, human in the loop, approval step, middleware, structured output,
    pydantic, zod, safe actions
    Original description: INVOKE THIS SKILL when you need human-in-the-loop approval, custom
    middleware, or structured output. Covers HumanInTheLoopMiddleware for human approval of
    dangerous tool calls, creating custom middleware with hooks, Command resume patterns, and
    structured output with Pydantic/Zod.

[langchain-python-quickstart]
    Source: langchain
    What it does: Sets up a minimal working LangChain agent in Python following the official
    quickstart.
    When to use: You want to try LangChain in Python as fast as possible.
    Search terms: langchain, python, quickstart, getting started, first agent, try locally,
    tutorial
    Original description: Scaffold a minimal local LangChain agent in Python by following the
    official quickstart. Use when the user wants to quickly build or try a LangChain agent
    locally.

[langchain-typescript-quickstart]
    Source: langchain
    What it does: Sets up a minimal working LangChain agent in TypeScript following the official
    quickstart.
    When to use: You want to try LangChain in TypeScript or JavaScript as fast as possible.
    Search terms: langchain, typescript, javascript, quickstart, getting started, first agent,
    try locally
    Original description: Scaffold a minimal local LangChain agent in TypeScript by following
    the official quickstart. Use when the user wants to quickly build or try a LangChain agent
    locally.

[langgraph-cli]
    Source: langchain
    What it does: Covers the langgraph command-line tool for creating, running, building, and
    deploying LangGraph applications.
    When to use: You need to scaffold or deploy a LangGraph app from the terminal.
    Search terms: langgraph, cli, deploy, scaffold, dev server, langgraph.json, command line,
    langchain
    Original description: INVOKE THIS SKILL when using the langgraph CLI to scaffold, develop,
    build, or deploy LangGraph applications. Covers langgraph new, dev, build, up, deploy, and
    langgraph.json configuration.

[langgraph-fundamentals]
    Source: langchain
    What it does: Explains the building blocks of LangGraph code: graphs, state, nodes, edges,
    streaming, and error handling.
    When to use: You are writing any LangGraph code.
    Search terms: langgraph, stategraph, nodes and edges, workflow graph, streaming, langchain,
    agent flow, state machine
    Original description: INVOKE THIS SKILL when writing ANY LangGraph code. Covers StateGraph,
    state schemas, nodes, edges, Command, Send, invoke, streaming, and error handling.

[langgraph-human-in-the-loop]
    Source: langchain
    What it does: Shows how to pause a LangGraph workflow for human approval or correction and
    how to handle errors in tiers.
    When to use: Your LangGraph app needs a person to approve or fix something mid-run.
    Search terms: langgraph, human approval, pause and resume, interrupt, error handling, review
    step, langchain, oversight
    Original description: INVOKE THIS SKILL when implementing human-in-the-loop patterns,
    pausing for approval, or handling errors in LangGraph. Covers interrupt(),
    Command(resume=...), approval/validation workflows, and the 4-tier error handling strategy.

[langgraph-persistence]
    Source: langchain
    What it does: Explains how LangGraph saves state so it can remember conversations, resume
    later, and rewind through history.
    When to use: Your LangGraph app needs memory across sessions or the ability to go back in
    time.
    Search terms: langgraph, memory, save state, checkpoint, resume conversation, time travel,
    thread id, langchain
    Original description: INVOKE THIS SKILL when your LangGraph needs to persist state, remember
    conversations, travel through history, or configure subgraph checkpointer scoping. Covers
    checkpointers, thread_id, time travel, Store, and subgraph persistence modes.

[langgraph-python-quickstart]
    Source: langchain
    What it does: Sets up a minimal working LangGraph agent in Python following the official
    quickstart.
    When to use: You want to try LangGraph in Python as fast as possible.
    Search terms: langgraph, python, quickstart, getting started, first agent, try locally,
    tutorial
    Original description: Scaffold a minimal local LangGraph agent in Python by following the
    official quickstart. Use when the user wants to quickly build or try a LangGraph agent
    locally.

[langgraph-typescript-quickstart]
    Source: langchain
    What it does: Sets up a minimal working LangGraph agent in TypeScript following the official
    quickstart.
    When to use: You want to try LangGraph in TypeScript or JavaScript as fast as possible.
    Search terms: langgraph, typescript, javascript, quickstart, getting started, first agent,
    try locally
    Original description: Scaffold a minimal local LangGraph agent in TypeScript by following
    the official quickstart. Use when the user wants to quickly build or try a LangGraph agent
    locally.

[llm-models]
    Source: inference.sh superpowers
    What it does: Gives access to Claude, Gemini, Kimi, and 100+ other AI language models
    through one inference.sh interface with automatic fallback and cost savings.
    When to use: You want to call different AI chat models through a single API.
    Search terms: llm api, claude, gemini, openrouter, inference.sh, chat api, ai model access,
    openai alternative, cost optimization
    Original description: Access Claude, Gemini, Kimi, GLM and 100+ LLMs via inference.sh CLI
    using OpenRouter. Models: Claude Opus 4.5, Claude Sonnet 4.5, Claude Haiku 4.5, Gemini 3
    Pro, Kimi K2, GLM-4.6, Intellect 3. One API for all models with automatic fallback and cost
    optimization. Use for: AI assistants, code generation, reasoning, agents, chat, content
    generation. Triggers: claude api, openrouter, llm api, claude sonnet, claude opus, gemini
    api, kimi, language model, gpt alternative, anthropic api, ai model api, llm access, chat
    api, claude alternative, openai alternative

[long-task-coordinator]
    Source: agent-playbook
    What it does: Keeps long or multi-session jobs on track with saved progress, recovery
    checks, and clear status updates so interrupted work can resume.
    When to use: A task will span many turns, agents, or scheduled runs and must survive
    interruptions.
    Search terms: long running task, resume work, multi-session, progress tracking, background
    jobs, recovery, status, agent playbook
    Original description: Coordinates multi-session, delegated, or long-running work with
    persistent state, recovery checks, and explicit status transitions. Use when a task spans
    multiple turns, multiple agents, background jobs, or scheduled loops, or when interrupted
    work must be resumed reliably.

[loop-me]
    Source: mattpocock skills
    What it does: Interviews you in depth about the workflow specs you want to build in your
    workspace.
    When to use: You want to define a repeatable workflow and need help pinning down the
    details.
    Search terms: workflow spec, grill me, define process, requirements, matt pocock, automation
    design, interview
    Original description: Grill me about specs for the workflows I want to build, within this
    workspace.

[managed-deep-agents]
    Source: langchain
    What it does: Walks you from idea to deployed agent using LangSmith's Managed Deep Agents
    and the mda command line, including memory, tools, schedules, and evaluations.
    When to use: You want to build and host an AI agent on LangSmith without managing
    infrastructure.
    Search terms: managed deep agents, langsmith, mda cli, deploy agent, hosted ai agent,
    schedules, evals, langchain
    Original description: INVOKE THIS SKILL when building, testing, or deploying Managed Deep
    Agents in LangSmith with the mda CLI. Walks a user through their first agent end to end —
    interviewing them about what they want to build, mapping it onto what MDA can actually do,
    then scaffolding and deploying it. Covers the file-based project layout; define_deep_agent /
    defineDeepAgent; instructions, skills, memory, identity, tools, middleware, sandboxes,
    schedules, channels, and evals; mda init/build/dev/deploy/logs/delete; and Context Hub.

[MCP Integration]
    Source: claude-code plugins
    What it does: Guides you through connecting an external service to a Claude Code plugin via
    an MCP server, covering configuration and server types.
    When to use: You want a Claude Code plugin to talk to an outside tool or service.
    Search terms: mcp, claude code plugin, connect external service, mcp.json, model context
    protocol, integration, server config
    Original description: This skill should be used when the user asks to "add MCP server",
    "integrate MCP", "configure MCP in plugin", "use .mcp.json", "set up Model Context
    Protocol", "connect external service", mentions "${CLAUDE_PLUGIN_ROOT} with MCP", or
    discusses MCP server types (SSE, stdio, HTTP, WebSocket). Provides comprehensive guidance
    for integrating Model Context Protocol servers into Claude Code plugins for external tool
    and service integration.

[mcp-builder]
    Source: anthropic skills
    What it does: Guides you through building a high-quality MCP server in Python or TypeScript
    so AI assistants can use an external API or service as tools.
    When to use: You want to make your API or service available to AI assistants like Claude.
    Search terms: mcp server, build integration, connect ai to api, python, typescript, model
    context protocol, tools for ai, anthropic
    Original description: Guide for creating high-quality MCP (Model Context Protocol) servers
    that enable LLMs to interact with external services through well-designed tools. Use when
    building MCP servers to integrate external APIs or services, whether in Python (FastMCP) or
    Node/TypeScript (MCP SDK).

[mcp-cli]
    Source: awesome-copilot
    What it does: Lets you list and call MCP server tools from the command line to reach
    external tools, APIs, and data sources.
    When to use: You want to test or use an MCP server's tools from a terminal.
    Search terms: mcp, command line, list tools, call tool, external api, terminal, model
    context protocol
    Original description: Interface for MCP (Model Context Protocol) servers via CLI. Use when
    you need to interact with external tools, APIs, or data sources through MCP servers, list
    available MCP servers/tools, or call MCP tools from command line.

[mcp-create-adaptive-cards]
    Source: awesome-copilot
    What it does: Creates Adaptive Cards, the rich interactive card format used in Microsoft
    Teams and other Microsoft apps.
    When to use: You want to design a card-style message or form for Microsoft Teams.
    Search terms: adaptive cards, microsoft teams, card design, interactive message, teams bot,
    microsoft 365, copilot
    Original description: Skill converted from mcp-create-adaptive-cards.prompt.md

[mcp-create-declarative-agent]
    Source: awesome-copilot
    What it does: Creates a declarative agent for Microsoft 365 Copilot, a custom assistant
    defined by configuration rather than code.
    When to use: You want a custom Copilot assistant for your organization without heavy coding.
    Search terms: microsoft 365 copilot, declarative agent, custom copilot, teams, no code
    agent, microsoft, assistant setup
    Original description: Skill converted from mcp-create-declarative-agent.prompt.md

[mcp-deploy-manage-agents]
    Source: awesome-copilot
    What it does: Deploys and manages Microsoft 365 Copilot agents, covering publishing and
    administration.
    When to use: You have built a Copilot agent and need to roll it out or manage it.
    Search terms: deploy agent, microsoft 365, copilot agents, publish, manage agents, teams
    admin, rollout
    Original description: Skill converted from mcp-deploy-manage-agents.prompt.md

[mcp-release-qa]
    Source: awesome-copilot
    What it does: Tests an MCP server before release by running a real session, checking it
    matches its documentation, trying failure cases, and recording evidence.
    When to use: You are about to ship or review an MCP server and want confidence it works.
    Search terms: mcp testing, release check, qa, verify server, pre-release, model context
    protocol, quality assurance, evidence
    Original description: Verify an MCP server before release by exercising a real protocol
    session, comparing runtime capabilities with source and documentation, testing failure
    paths, and recording reproducible evidence. Use when shipping or reviewing an MCP server,
    tool, resource, prompt, catalog, or install path.

[memory-merger]
    Source: awesome-copilot
    What it does: Moves proven lessons from an AI's memory notes on a topic into its permanent
    instruction file.
    When to use: Your AI has learned repeated lessons and you want them baked into its standing
    rules.
    Search terms: merge memory, ai lessons, instruction file, copilot memory, consolidate notes,
    permanent rules, learning
    Original description: Merges mature lessons from a domain memory file into its instruction
    file. Syntax: `/memory-merger >domain [scope]` where scope is `global` (default), `user`,
    `workspace`, or `ws`.

[mini-context-graph]
    Source: awesome-copilot
    What it does: Builds a growing knowledge base by having the AI read documents once, write
    wiki pages, and map how people, things, and ideas connect.
    When to use: You want an AI to accumulate and cross-reference knowledge from your documents
    over time.
    Search terms: knowledge base, wiki, knowledge graph, ingest documents, second brain,
    entities, research notes, compounding knowledge
    Original description: A persistent, compounding knowledge base combining Karpathy's LLM Wiki
    pattern with a structured knowledge graph. Ingest documents once — the LLM writes wiki
    pages, extracts entities/relations into the graph, and stores raw content for evidence
    retrieval. Knowledge accumulates and cross-references; it is never re-derived from scratch.

[noob-mode]
    Source: awesome-copilot
    What it does: Translates every technical prompt, error, and output in Copilot CLI into plain
    English with color-coded risk warnings.
    When to use: You are not a programmer and want to use Copilot CLI without the jargon.
    Search terms: plain english, beginner, non-technical, copilot cli, explain errors, jargon
    free, risk warnings, simple mode
    Original description: Plain-English translation layer for non-technical Copilot CLI users.
    Translates every approval prompt, error message, and technical output into clear, jargon-
    free English with color-coded risk indicators.

[onboard-context-matic]
    Source: awesome-copilot
    What it does: Gives an interactive guided tour of the context-matic MCP server, showing what
    APIs it offers and how to search and use them.
    When to use: You just connected context-matic and want to learn what it can do.
    Search terms: onboarding, tour, context-matic, what can this do, available apis, getting
    started, mcp, tutorial
    Original description: Interactive onboarding tour for the context-matic MCP server. Walks
    the user through what the server does, shows all available APIs, lets them pick one to
    explore, explains it in their project language, demonstrates model_search and
    endpoint_search live, and ends with a menu of things the user can ask the agent to do. USE
    FOR: first-time setup; "what can this MCP do?"; "show me the available APIs"; "onboard me";
    "how do I use the context-matic server"; "give me a tour". DO NOT USE FOR: actually
    integrating an API end-to-end (use integrate-context-matic instead).

[parallel-feature-development]
    Source: agents (bundle)
    What it does: Coordinates several AI agents building different parts of the same feature at
    once, with rules for who owns which files to avoid conflicts.
    When to use: You want a big feature split across multiple agents working simultaneously.
    Search terms: parallel development, multi-agent, file ownership, merge conflicts, split
    feature, team coordination, interface contracts, full stack
    Original description: Coordinate parallel feature development with file ownership
    strategies, conflict avoidance rules, and integration patterns for multi-agent
    implementation. Use this skill when decomposing a large feature into independent work
    streams, when two or more agents need to implement different layers of the same system
    simultaneously, when establishing file ownership to prevent merge conflicts in a shared
    codebase, when designing interface contracts so parallel implementers can build against each
    other's APIs before they are ready, or when deciding whether to use vertical slices versus
    horizontal layer…

[php-mcp-server-generator]
    Source: awesome-copilot
    What it does: Generates a complete MCP server project in PHP with tools, resources, prompts,
    and tests so AI assistants can connect to your service.
    When to use: You want to expose a tool or API to AI assistants and your team works in PHP.
    Search terms: mcp server, php, ai integration, model context protocol, connect ai to api,
    project scaffold, laravel
    Original description: Generate a complete PHP Model Context Protocol server project with
    tools, resources, prompts, and tests using the official PHP SDK

[Plugin Settings]
    Source: claude-code plugins
    What it does: Explains how to store user-configurable settings for a Claude Code plugin in
    local files so behavior can vary per project.
    When to use: You want users to be able to configure how your Claude Code plugin behaves.
    Search terms: plugin settings, claude code, configuration file, per-project settings,
    local.md, yaml, customize plugin
    Original description: This skill should be used when the user asks about "plugin settings",
    "store plugin configuration", "user-configurable plugin", ".local.md files", "plugin state
    files", "read YAML frontmatter", "per-project plugin settings", or wants to make plugin
    behavior configurable. Documents the .claude/plugin-name.local.md pattern for storing
    plugin-specific configuration with YAML frontmatter and markdown content.

[Plugin Structure]
    Source: claude-code plugins
    What it does: Guides you through laying out a Claude Code plugin: folders, manifest file,
    commands, agents, skills, and hooks.
    When to use: You are creating a new Claude Code plugin and need to know how to organize it.
    Search terms: create plugin, claude code, plugin layout, plugin.json, scaffold, folder
    structure, commands, skills, hooks
    Original description: This skill should be used when the user asks to "create a plugin",
    "scaffold a plugin", "understand plugin structure", "organize plugin components", "set up
    plugin.json", "use ${CLAUDE_PLUGIN_ROOT}", "add commands/agents/skills/hooks", "configure
    auto-discovery", or needs guidance on plugin directory layout, manifest configuration,
    component organization, file naming conventions, or Claude Code plugin architecture best
    practices.

[prompt-engineering]
    Source: inference.sh superpowers
    What it does: Teaches techniques for writing better prompts for chatbots, image generators,
    and video models to get consistent, high-quality results.
    When to use: You want better output from AI tools and need to know how to ask.
    Search terms: how to prompt, better prompts, prompt tips, chatgpt prompts, image prompt,
    midjourney, prompt template, ai results, inference.sh
    Original description: Master prompt engineering for AI models: LLMs, image generators, video
    models. Techniques: chain-of-thought, few-shot, system prompts, negative prompts. Models:
    Claude, GPT-4, Gemini, FLUX, Veo, Stable Diffusion prompting. Use for: better AI outputs,
    consistent results, complex tasks, optimization. Triggers: prompt engineering, how to
    prompt, better prompts, prompt tips, prompting guide, llm prompting, image prompt, ai
    prompting, prompt optimization, prompt template, prompt structure, effective prompts, prompt
    techniques

[prompt-engineering-patterns]
    Source: agents (bundle)
    What it does: Applies advanced prompting patterns like chain-of-thought and few-shot
    examples to improve and debug prompts in production AI apps.
    When to use: Your AI feature isn't giving reliable results and you want to fix the prompt.
    Search terms: optimize prompt, prompt template, chain of thought, few shot, debug prompt,
    better ai output, production llm, prompt design
    Original description: This skill should be used when the user asks to "optimize a prompt",
    "improve prompt performance", "design a prompt template", "write better prompts", "debug
    prompt issues", "use chain-of-thought", "structured prompting", "few-shot prompting", or
    wants to apply advanced prompt engineering patterns for production LLM applications.

[prompt-optimizer]
    Source: awesome-copilot
    What it does: Rewrites a rough request or half-formed idea into a polished, copy-pasteable
    prompt you can send to any AI chat tool.
    When to use: You know roughly what you want to ask ChatGPT or Claude but want it phrased for
    the best answer.
    Search terms: rewrite prompt, better prompt, chatgpt, claude, improve my question, prompt
    help, copy paste prompt, optimize prompt
    Original description: Turn any rough prompt, half-formed idea, or task description into a
    finished, ready-to-send prompt optimized for any LLM model inside a chat interface — NOT the
    API. Use this skill whenever the user wants to write, rewrite, optimize, improve, sharpen,
    or polish a prompt for chat. Trigger phrases include "rewrite this prompt", "make this a
    better prompt", "optimize this prompt", "turn this into a prompt", "help me prompt this",
    "draft a prompt that...", "I want to ask...", or whenever the user pastes a draft prompt and
    asks for improvements. Also trigger when the user describes a task they plan…

[python-executor]
    Source: inference.sh superpowers
    What it does: Runs Python code in a safe cloud sandbox with data, image, video, and web-
    scraping libraries already installed.
    When to use: You need to run a script to process data, images, or files without setting up
    Python yourself.
    Search terms: run python, sandbox, data analysis, web scraping, image processing, pandas,
    automation script, inference.sh, pdf generation
    Original description: Execute Python code in a safe sandboxed environment via
    [inference.sh](https://inference.sh). Pre-installed: NumPy, Pandas, Matplotlib, requests,
    BeautifulSoup, Selenium, Playwright, MoviePy, Pillow, OpenCV, trimesh, and 100+ more
    libraries. Use for: data processing, web scraping, image manipulation, video creation, 3D
    model processing, PDF generation, API calls, automation scripts. Triggers: python, execute
    code, run script, web scraping, data analysis, image processing, video editing, 3D models,
    automation, pandas, matplotlib

[python-mcp-server-generator]
    Source: awesome-copilot
    What it does: Generates a complete MCP server project in Python with tools, resources, and
    configuration so AI assistants can connect to your service.
    When to use: You want to expose a tool or API to AI assistants and your team works in
    Python.
    Search terms: mcp server, python, ai integration, model context protocol, connect ai to api,
    project scaffold, fastmcp
    Original description: Generate a complete MCP server project in Python with tools,
    resources, and proper configuration

[python-sdk]
    Source: inference.sh superpowers
    What it does: Provides the Python library for inference.sh so you can run AI models, build
    agents, and add human approval steps in Python apps.
    When to use: You are adding AI features or agents to a Python project using inference.sh.
    Search terms: python sdk, inferencesh, pip install, python ai, build agent, async,
    inference.sh, rag, automation
    Original description: Python SDK for inference.sh - run AI apps, build agents, and integrate
    with all models. Package: inferencesh (pip install inferencesh). Supports sync/async,
    streaming, file uploads. Build agents with template or ad-hoc patterns, tool builder API,
    skills, and human approval. Use for: Python integration, AI apps, agent development, RAG
    pipelines, automation. Triggers: python sdk, inferencesh, pip install, python api, python
    client, async inference, python agent, tool builder python, programmatic ai, python
    integration, sdk python

[quasi-coder]
    Source: awesome-copilot
    What it does: Turns rough notes, pseudo-code, or plain-English descriptions of what you want
    into working, production-quality code, even if your wording is imprecise or has typos.
    When to use: You know roughly what you want a program to do but can only describe it in
    rough sketches or plain language.
    Search terms: pseudo code, turn description into code, write code from notes, rough idea to
    code, coding help, programming assistant, ai coder, non-technical coding, build from
    description
    Original description: Expert 10x engineer skill for interpreting and implementing code from
    shorthand, quasi-code, and natural language descriptions. Use when collaborators provide
    incomplete code snippets, pseudo-code, or descriptions with potential typos or incorrect
    terminology. Excels at translating non-technical or semi-technical descriptions into
    production-quality code.

[related-skill]
    Source: inference.sh superpowers
    What it does: Searches the inference.sh skill library to find and install additional skills
    that complement the ones you already use.
    When to use: You want to discover what other AI add-ons could extend your current workflow.
    Search terms: find skills, more skills, skill suggestions, add capabilities, inference.sh,
    skill library, expand workflow, plugins, similar tools
    Original description: Discover and install related skills from inference.sh skill registry.
    Helps find complementary skills for your AI workflow. Use for: skill discovery, workflow
    expansion, capability exploration. Triggers: related skills, find skills, skill discovery,
    complementary skills, expand workflow, more capabilities, similar skills, skill suggestions

[remember]
    Source: awesome-copilot
    What it does: Saves lessons you have learned as organized memory notes so your AI assistant
    applies them in future sessions, either across all projects or just one workspace.
    When to use: You keep correcting the AI on the same thing and want it to remember the rule
    going forward.
    Search terms: remember this, save a lesson, ai memory, teach the assistant, copilot
    instructions, persistent preferences, stop repeating mistakes, notes for ai, workspace rules
    Original description: Transforms lessons learned into domain-organized memory instructions
    (global or workspace). Syntax: `/remember [>domain [scope]] lesson clue` where scope is
    `global` (default), `user`, `workspace`, or `ws`.

[remember-interactive-programming]
    Source: awesome-copilot
    What it does: Reminds the AI assistant to test code live in an interactive programming
    console (REPL) as it works, which is especially useful for Clojure projects.
    When to use: You are coding in a language with a live console and want the AI to try things
    out step by step instead of guessing.
    Search terms: clojure, repl, interactive programming, live coding, test as you go, copilot
    prompt, backseat driver, developer workflow, coding reminder
    Original description: A micro-prompt that reminds the agent that it is an interactive
    programmer. Works great in Clojure when Copilot has access to the REPL (probably via
    Backseat Driver). Will work with any system that has a live REPL that the agent can use.
    Adapt the prompt with any specific reminders in your workflow and/or workspace.

[ruby-mcp-server-generator]
    Source: awesome-copilot
    What it does: Generates a complete, ready-to-run Model Context Protocol (MCP) server project
    written in Ruby, so your AI assistant can connect to your own tools or data.
    When to use: You want to build a Ruby-based connector that lets AI assistants use your
    systems.
    Search terms: ruby, mcp server, build an mcp, ai connector, model context protocol, ai
    integration, custom tools for ai, ruby sdk, connect ai to my app
    Original description: Generate a complete Model Context Protocol server project in Ruby
    using the official MCP Ruby SDK gem.

[rust-mcp-server-generator]
    Source: awesome-copilot
    What it does: Generates a complete Model Context Protocol (MCP) server project in Rust,
    including tools, prompts, resources, and tests.
    When to use: You want a fast, reliable Rust connector that exposes your tools or data to AI
    assistants.
    Search terms: rust, mcp server, build an mcp, ai connector, model context protocol, rmcp, ai
    integration, custom tools for ai, connect ai to my app
    Original description: Generate a complete Rust Model Context Protocol server project with
    tools, prompts, resources, and tests using the official rmcp SDK

[saga]
    Source: warp common-skills
    What it does: Runs a large software feature from start to finish on its own: it writes a
    detailed plan, breaks it into milestones and tasks with clear pass/fail checks, then hands
    the work to a team of AI workers while a lead agent supervises.
    When to use: You want a big feature built end-to-end with minimal hand-holding and a clear
    spec up front.
    Search terms: build a big feature, autonomous development, ai team, project plan, spec
    driven, subagents, orchestrator, warp, automate coding, end to end build
    Original description: Run an autonomous, spec-driven development "saga" for medium-to-large
    features using an orchestrator agent and a fleet of worker subagents. Use this skill
    whenever the user invokes /saga, asks to autonomously build a sizable feature end-to-end
    with minimal human intervention, wants a comprehensive spec broken into milestones and tasks
    with airtight validation criteria before parallelized implementation, or wants an
    orchestrator to delegate implementation to worker agents while preserving its own context
    window. Trigger on phrases like "run a saga", "autonomously implement this feature", "spec …

[self-improving-agent]
    Source: agent-playbook
    What it does: Learns from every task the AI completes or gets wrong and stores those lessons
    in layered memory so it gets better at your codebase over time, correcting itself
    automatically.
    When to use: You want your AI assistant to stop repeating mistakes and improve with each
    project.
    Search terms: self improving, ai learns from mistakes, ai memory, continuous improvement,
    agent playbook, auto correction, smarter assistant, lessons learned, hooks
    Original description: A universal self-improving agent that learns from ALL skill
    experiences. Uses multi-memory architecture (semantic + episodic + working) to continuously
    evolve the codebase. Auto-triggers on skill completion/error with hooks-based self-
    correction.

[session-logger]
    Source: agent-playbook
    What it does: Saves your full conversation with the AI to a timestamped log file whenever
    you ask, so you have a record of what was discussed and decided.
    When to use: You want to keep a copy of a chat session for later reference or hand-off.
    Search terms: save conversation, save chat, session log, chat history, export conversation,
    record session, conversation backup, transcript, meeting notes
    Original description: Saves conversation history to session log files. Use when user says
    "保存对话", "保存对话信息", "记录会话", "save session", or "save conversation". Automatically creates
    timestamped session log in sessions/ directory.

[setup-matt-pocock-skills]
    Source: mattpocock skills
    What it does: Prepares a code repository to work with Matt Pocock's engineering skill set by
    configuring the issue tracker, triage labels, and documentation layout in one go.
    When to use: You are adopting the Matt Pocock skills and need to run the one-time setup
    first.
    Search terms: matt pocock, setup, initial configuration, issue tracker, labels, repo setup,
    engineering skills, onboarding, first run
    Original description: Configure this repo for the engineering skills — set up its issue
    tracker, triage label vocabulary, and domain doc layout. Run once before first use of the
    other engineering skills.

[Skill Development]
    Source: claude-code plugins
    What it does: Guides you through creating or improving a skill for a Claude Code plugin,
    including how to structure it, write a good description, and organize its content.
    When to use: You want to add a new skill to a Claude Code plugin or make an existing one
    trigger more reliably.
    Search terms: create a skill, write a skill, claude code plugin, skill structure, improve
    skill description, progressive disclosure, plugin development, custom ai skill, best
    practices
    Original description: This skill should be used when the user wants to "create a skill",
    "add a skill to plugin", "write a new skill", "improve skill description", "organize skill
    content", or needs guidance on skill structure, progressive disclosure, or skill development
    best practices for Claude Code plugins.

[skill-creator]
    Source: anthropic skills
    What it does: Creates new AI skills from scratch, edits existing ones, and tests how well
    they perform so you can fine-tune when and how they trigger.
    When to use: You want to build or improve a reusable skill and check that it actually works.
    Search terms: create a skill, make a skill, edit skill, test skill, skill evals, benchmark,
    anthropic skills, custom ai skill, improve triggering, skill performance
    Original description: Create new skills, modify and improve existing skills, and measure
    skill performance. Use when users want to create a skill from scratch, edit, or optimize an
    existing skill, run evals to test a skill, benchmark skill performance with variance
    analysis, or optimize a skill's description for better triggering accuracy.

[skill-name]
    Source: opc-skills
    What it does: Serves as a blank starting template for writing a new skill, showing where the
    description and trigger words should go.
    When to use: You are starting a brand-new skill and want a scaffold to fill in.
    Search terms: skill template, blank skill, starter, scaffold, new skill, placeholder, opc
    skills, example skill, boilerplate
    Original description: Clear description of what this skill does and when to use it. Include
    trigger keywords and contexts inline, e.g. "Use when user wants to X, Y, or Z."

[skill-router]
    Source: agent-playbook
    What it does: Looks at what you are asking for and points you to the most suitable skill,
    acting as the front door when you are not sure which tool to use.
    When to use: You know what you want done but have no idea which skill or approach fits.
    Search terms: which skill, how do i, help me choose, router, where to start, find the right
    tool, agent playbook, entry point, recommend a skill
    Original description: Intelligently routes user requests to the most appropriate Claude Code
    skill. ALWAYS use this skill FIRST when user asks for help, mentions "skill", "which", "how
    to", or seems unsure about which approach to take. This is the default entry point for all
    skill-related requests.

[structured-autonomy-generate]
    Source: awesome-copilot
    What it does: Generates the implementation instructions for a structured-autonomy workflow,
    where the AI follows a clear plan with defined checkpoints.
    When to use: You are using the structured-autonomy method and need the generation step.
    Search terms: structured autonomy, copilot prompt, generate implementation, ai workflow,
    planned coding, checkpoints, github copilot, prompt template, autonomous agent
    Original description: Structured Autonomy Implementation Generator Prompt

[structured-autonomy-implement]
    Source: awesome-copilot
    What it does: Carries out the implementation phase of a structured-autonomy workflow,
    building what was planned while staying within agreed boundaries.
    When to use: You have a plan ready and want the AI to implement it in a controlled way.
    Search terms: structured autonomy, implement plan, copilot prompt, controlled coding, ai
    workflow, build from plan, github copilot, prompt template, autonomous agent
    Original description: Structured Autonomy Implementation Prompt

[structured-autonomy-plan]
    Source: awesome-copilot
    What it does: Produces the planning phase of a structured-autonomy workflow, laying out what
    will be built and how before any code is written.
    When to use: You want a clear, reviewable plan before letting the AI start coding.
    Search terms: structured autonomy, planning prompt, make a plan, copilot prompt, plan before
    coding, ai workflow, github copilot, prompt template, project plan
    Original description: Structured Autonomy Planning Prompt

[subagent-driven-development]
    Source: obra superpowers
    What it does: Executes an implementation plan by handing each independent task to its own
    helper agent within the current session, so work gets done in parallel.
    When to use: You have a task list where the pieces do not depend on each other and want them
    done faster.
    Search terms: subagents, parallel tasks, split up work, run tasks at once, superpowers,
    implementation plan, delegate, faster coding, ai helpers
    Original description: Use when executing implementation plans with independent tasks in the
    current session

[swarm]
    Source: langchain
    What it does: Processes many similar items at once by listing them in a table, sending each
    row to its own AI worker, and combining the results.
    When to use: You have a long list of similar jobs, such as researching 50 companies, and
    want them done in parallel.
    Search terms: batch processing, parallel, do many at once, bulk task, fan out, langchain,
    spreadsheet of tasks, mass research, ai workers, aggregate results
    Original description: Dispatches many independent items in parallel: create a table, fan out
    to subagents, aggregate results. One row = one unit of work.

[swift-mcp-server-generator]
    Source: awesome-copilot
    What it does: Generates a complete Model Context Protocol (MCP) server project in Swift so
    Apple-platform apps can offer their tools and data to AI assistants.
    When to use: You want to build a Swift connector that lets AI assistants use your app.
    Search terms: swift, mcp server, build an mcp, apple, ios, ai connector, model context
    protocol, ai integration, connect ai to my app
    Original description: Generate a complete Model Context Protocol server project in Swift
    using the official MCP Swift SDK package.

[task-coordination-strategies]
    Source: agents (bundle)
    What it does: Breaks a complex job into smaller tasks, maps out which depend on which, and
    balances the workload across a team of AI agents while tracking progress.
    When to use: You are coordinating several AI agents on one project and need a clear division
    of labor.
    Search terms: task breakdown, project planning, dependencies, agent team, workload
    balancing, multi agent, coordinate work, progress tracking, delegation
    Original description: Decompose complex tasks, design dependency graphs, and coordinate
    multi-agent work with proper task descriptions and workload balancing. Use this skill when
    breaking down work for agent teams, managing task dependencies, or monitoring team progress.

[teach]
    Source: mattpocock skills
    What it does: Teaches you a new concept or technique, using examples from your own project
    so the lesson is relevant.
    When to use: You want to learn something new and have it explained in the context of your
    work.
    Search terms: teach me, learn, explain, tutorial, training, matt pocock, how does this work,
    lesson, upskill
    Original description: Teach the user a new skill or concept, within this workspace.

[template-skill]
    Source: anthropic skills
    What it does: Provides a blank skill template from Anthropic that you copy and fill in when
    creating a new skill.
    When to use: You are writing a new skill and want the official starting point.
    Search terms: skill template, blank skill, starter, scaffold, anthropic, new skill,
    placeholder, boilerplate, example
    Original description: Replace with description of the skill and when Claude should use it.

[tiny-stepping]
    Source: awesome-copilot
    What it does: Builds software in very small steps, pausing after each change for your
    feedback so the direction is confirmed early before going further.
    When to use: You want to stay closely involved and avoid the AI running off in the wrong
    direction.
    Search terms: small steps, incremental, step by step, careful changes, check in often,
    iterative, copilot, review as you go, cautious development
    Original description: Incremental development workflow that makes the smallest meaningful
    change per step and pauses for feedback, so the direction gets validated early before
    continuing. Use for careful, iterative implementation with continuous validation.

[to-questionnaire]
    Source: mattpocock skills
    What it does: Turns a decision you cannot fully answer yourself into a clear questionnaire
    that someone else, such as a client or colleague, can fill in.
    When to use: You need input from another person before you can decide and want to ask the
    right questions.
    Search terms: questionnaire, gather requirements, ask the client, decision form, survey,
    matt pocock, clarifying questions, intake form, collect answers
    Original description: Turn a decision you can't fully answer into a questionnaire for
    someone else to fill in.

[tools-ui]
    Source: inference.sh superpowers
    What it does: Provides ready-made React/Next.js interface components for showing what an AI
    agent is doing: pending actions, progress, approval requests, and results.
    When to use: You are building an app with an AI agent and need screens that show its tool
    activity and let users approve steps.
    Search terms: react, nextjs, ui components, tool calls, approval flow, human in the loop,
    progress indicator, agent interface, inference.sh, frontend
    Original description: Tool lifecycle UI components for React/Next.js from ui.inference.sh.
    Display tool calls: pending, progress, approval required, results. Capabilities: tool
    status, progress indicators, approval flows, results display. Use for: showing agent tool
    calls, human-in-the-loop approvals, tool output. Triggers: tool ui, tool calls, tool status,
    tool approval, tool results, agent tools, mcp tools ui, function calling ui, tool lifecycle,
    tool pending

[track-management]
    Source: agents (bundle)
    What it does: Creates and manages Conductor 'tracks', the work units that hold a spec and
    plan for each feature, bug fix, or refactor.
    When to use: You use the Conductor system and need to set up or update a piece of work.
    Search terms: conductor, tracks, spec, plan, feature tracking, work units, bug tracking,
    refactor, project management
    Original description: Use this skill when creating, managing, or working with Conductor
    tracks - the logical work units for features, bugs, and refactors. Applies to spec.md,
    plan.md, and track lifecycle operations.

[typescript-mcp-server-generator]
    Source: awesome-copilot
    What it does: Generates a complete Model Context Protocol (MCP) server project in
    TypeScript, with tools, resources, and configuration ready to go.
    When to use: You want a TypeScript connector that lets AI assistants use your tools or data.
    Search terms: typescript, javascript, mcp server, build an mcp, ai connector, model context
    protocol, node, ai integration, connect ai to my app
    Original description: Generate a complete MCP server project in TypeScript using the MCP
    TypeScript SDK v2 (@modelcontextprotocol/server) with tools, resources, and proper
    configuration

[ui-skills-root]
    Source: ui-skills
    What it does: Picks the smallest useful set of UI design guidance before you start interface
    work, using the ui-skills command-line tool.
    When to use: You are about to do front-end or interface work and want only the relevant
    guidance loaded.
    Search terms: ui skills, user interface, frontend, design guidance, cli, web design,
    component design, lightweight context, ui best practices
    Original description: Use before UI-related work to select the smallest useful UI Skills
    context through the ui-skills CLI.

[update-skill]
    Source: warp common-skills
    What it does: Creates or revises skill files (SKILL.md) in a repository, including their
    structure, header details, and instructions.
    When to use: You need to write a new skill or tidy up an existing one in your repo.
    Search terms: update skill, edit skill, write skill, skill.md, warp, frontmatter, skill
    authoring, revise instructions, custom ai skill
    Original description: Create or update skills by generating, editing, or refining SKILL.md
    files in this repository. Use when authoring new skills or revising the structure,
    frontmatter, or guidance for existing ones.

[using-agent-skills]
    Source: agent-skills
    What it does: Acts as the master skill that finds and activates the right skill for whatever
    task is at hand, starting at the beginning of a session.
    When to use: You are starting work and want the AI to figure out which skills apply.
    Search terms: find skills, which skill, skill discovery, meta skill, session start, invoke
    skill, routing, agent skills, entry point
    Original description: Discovers and invokes agent skills. Use when starting a session or
    when you need to discover which skill applies to the current task. This is the meta-skill
    that governs how all other skills are discovered and invoked.

[using-superpowers]
    Source: obra superpowers
    What it does: Sets the ground rules for the Superpowers skill library, requiring the AI to
    check for and use a matching skill before responding to anything.
    When to use: You use the Superpowers library and want it active from the first message.
    Search terms: superpowers, obra, skill rules, session start, always use skills, meta skill,
    workflow discipline, find skills, setup
    Original description: Use when starting any conversation - establishes how to find and use
    skills, requiring skill invocation before ANY response including clarifying questions

[verify-agent-action]
    Source: awesome-copilot
    What it does: Reviews a proposed AI action, such as a payment, deployment, message, or data
    change, before it runs, checking the approval matches exactly and looking for forged
    evidence, swapped parameters, or stale approvals.
    When to use: You want a safety check before an AI agent does something consequential or
    irreversible.
    Search terms: safety check, approve ai action, review before running, guardrails, audit,
    fraud check, human approval, risky actions, verification, ai oversight
    Original description: Review a proposed AI-agent action or human-approval packet before
    execution. Use when an agent wants to run a consequential tool, command, deployment,
    message, purchase, credential operation, or data mutation; when checking whether approval
    still matches the exact action; or when auditing action evidence for forged results,
    parameter swaps, replay, correlated reviewers, missing evidence, expiry, or stale
    monitoring. Produce an evidence-based review only—never execute or authorize the action.

[wait-what]
    Source: mattpocock skills
    What it does: Tells the AI that its last message did not make sense and asks it to explain
    again in a clearer way.
    When to use: You did not follow the AI's last answer and want it re-explained.
    Search terms: explain again, i dont understand, rephrase, clarify, confused, say it
    differently, matt pocock, re-pitch, simpler explanation
    Original description: Stop. That last message did not land — re-pitch it.

[web-search]
    Source: inference.sh superpowers
    What it does: Searches the web and pulls out page content using Tavily and Exa, giving
    direct answers and research material for fact-checking or content gathering.
    When to use: You need up-to-date information from the internet or want to extract text from
    web pages.
    Search terms: web search, internet search, research, fact check, tavily, exa, scrape
    website, find information online, perplexity alternative, content extraction
    Original description: Web search and content extraction with Tavily and Exa via inference.sh
    CLI. Apps: Tavily Search, Tavily Extract, Exa Search, Exa Answer, Exa Extract. Capabilities:
    AI-powered search, content extraction, direct answers, research. Use for: research, RAG
    pipelines, fact-checking, content aggregation, agents. Triggers: web search, tavily, exa,
    search api, content extraction, research, internet search, ai search, search assistant, web
    scraping, rag, perplexity alternative

[webmcpify]
    Source: awesome-copilot
    What it does: Makes your web app usable by AI agents by proposing and adding a WebMCP tool
    manifest, then testing it in a real browser, without touching unrelated code.
    When to use: You want AI assistants to be able to operate your web application directly.
    Search terms: webmcp, ai ready website, expose app to ai, agent integration, web app
    automation, ai agents use my app, manifest, browser testing, make app agent friendly
    Original description: Make a web app agent-ready — propose a WebMCP tool manifest,
    integrate, verify in a real browser, heal; unrelated code stays untouched. Use for
    "webmcpify", "add WebMCP", or "expose app actions to AI agents".

[what-context-needed]
    Source: awesome-copilot
    What it does: Asks the AI to list which files it needs to look at before it answers your
    question, so you can supply them up front.
    When to use: You are about to ask a question about your project and want to avoid back-and-
    forth.
    Search terms: which files, what do you need, context, copilot, prepare question, share
    files, ask better questions, project files, before answering
    Original description: Ask Copilot what files it needs to see before answering a question

[widgets-ui]
    Source: inference.sh superpowers
    What it does: Provides React/Next.js components that turn structured JSON from an AI into
    interactive interfaces such as forms, cards, buttons, and layouts.
    When to use: You are building an app where the AI should display rich, clickable content
    rather than plain text.
    Search terms: react, nextjs, widgets, dynamic forms, json ui, interactive cards, shadcn,
    agent interface, inference.sh, frontend components
    Original description: Declarative UI widgets from JSON for React/Next.js from
    ui.inference.sh. Render rich interactive UIs from structured agent responses. Capabilities:
    forms, buttons, cards, layouts, inputs, selects, checkboxes. Use for: agent-generated UIs,
    dynamic forms, data display, interactive cards. Triggers: widgets, declarative ui, json ui,
    widget renderer, agent widgets, dynamic ui, form widgets, card widgets, shadcn widgets,
    structured output ui

[wizard]
    Source: mattpocock skills
    What it does: Builds an interactive step-by-step terminal guide that walks a person through
    tasks only a human can do, like entering passwords, setting up cloud accounts, or clicking
    through a vendor dashboard.
    When to use: You need to hand someone a foolproof checklist for a one-off setup or
    migration.
    Search terms: setup wizard, step by step guide, credentials, secrets, cloud setup,
    migration, onboarding checklist, interactive script, matt pocock, walkthrough
    Original description: Generate an interactive bash wizard that walks a human through steps
    only they can perform. Use when provisioning infrastructure, setting up credentials or CI
    secrets, walking an unfamiliar third-party dashboard, or running a one-off migration or
    cutover. Don't invoke this for steps the agent can perform itself.

[workflow-orchestration-patterns]
    Source: agents (bundle)
    What it does: Explains how to design reliable long-running business processes with Temporal,
    covering how to split steps, handle failures across systems, and keep state consistent.
    When to use: You are building processes that span multiple services and must survive crashes
    or retries.
    Search terms: temporal, workflow, long running process, distributed transactions, saga
    pattern, microservices, reliability, background jobs, orchestration
    Original description: Design durable workflows with Temporal for distributed systems. Covers
    workflow vs activity separation, saga patterns, state management, and determinism
    constraints. Use when building long-running processes, distributed transactions, or
    microservice orchestration.

[workflow-orchestrator]
    Source: agent-playbook
    What it does: Coordinates work that spans several skills and suggests or runs follow-up
    actions whenever a milestone such as a requirements doc or implementation is finished.
    When to use: You have completed one stage of a project and want to know what should happen
    next.
    Search terms: next steps, workflow, multi skill, follow up actions, agent playbook,
    milestones, prd, coordination, automation
    Original description: Coordinates multi-skill workflows and records or runs follow-up
    actions when the host runtime supports them. Use when completing PRD creation,
    implementation, or any milestone that should be evaluated for additional skills.

[Writing Hookify Rules]
    Source: claude-code plugins
    What it does: Helps you write Hookify rules, which automatically trigger actions or checks
    in Claude Code based on patterns, and explains the rule syntax.
    When to use: You want Claude Code to automatically react to certain events or commands.
    Search terms: hookify, hooks, automation rules, claude code, triggers, auto checks, rule
    syntax, plugin, event handling
    Original description: This skill should be used when the user asks to "create a hookify
    rule", "write a hook rule", "configure hookify", "add a hookify rule", or needs guidance on
    hookify rule syntax and patterns.

[writing-skills]
    Source: obra superpowers
    What it does: Guides the creation and editing of skills and verifies they work before you
    roll them out.
    When to use: You are authoring a new skill in the Superpowers library and want to be sure it
    functions.
    Search terms: write a skill, create skill, edit skill, test skill, superpowers, obra,
    verify, custom ai skill, deployment check
    Original description: Use when creating new skills, editing existing skills, or verifying
    skills work before deployment
