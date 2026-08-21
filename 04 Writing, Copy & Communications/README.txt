04 WRITING, COPY & COMMUNICATIONS
=================================

Skills for writing and editing words: marketing copy, emails, documentation, READMEs,
changelogs, meeting minutes, internal comms and long-form articles. Also includes de-AI-ifying
prose.

47 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - add-educational-comments
  - api-documenter
  - brag-sheet
  - changelog-automation
  - code-tour
  - comment-code-generate-a-tutorial
  - copy-editing
  - copywriting
  - create-architectural-decision-record
  - create-readme
  - create-tldr-page
  - doc-and-modernize
  - doc-coauthoring
  - documentation-and-adrs
  - documentation-engineer
  - documentation-writer
  - domain-modeling
  - em-dash
  - email-drafter
  - finnish-humanizer
  - grill-with-docs
  - internal-comms
  - java-docs
  - meeting-minutes
  - mkdocs-translations
  - oo-component-documentation
  - performance-review-writer
  - postmortem-writing
  - product-changelog
  - readme-blueprint-generator
  - readout
  - repo-story-time
  - scan
  - signal-write
  - steno-mode
  - technical-blog-writing
  - tldr-prompt
  - update-markdown-file-index
  - write
  - write-feature-docs
  - write-product-spec
  - write-tech-spec
  - writing-beats
  - writing-for-agents
  - writing-fragments
  - writing-guidelines
  - writing-shape

SKILL DETAILS
-------------

[add-educational-comments]
    Source: awesome-copilot
    What it does: Adds explanatory comments to a code file so that someone learning can
    understand what each part does.
    When to use: You want code annotated for teaching or onboarding purposes.
    Search terms: code comments, explain code, educational, teaching, beginner friendly,
    annotate code, onboarding
    Original description: Add educational comments to the file specified, or prompt asking for
    file to comment if one is not provided.

[api-documenter]
    Source: agent-playbook
    What it does: Writes documentation for software interfaces (APIs) using the OpenAPI/Swagger
    standard.
    When to use: You need clear documentation for an API your team built.
    Search terms: api documentation, openapi, swagger, rest api, graphql, developer docs,
    technical writing
    Original description: API documentation specialist for OpenAPI/Swagger specifications. Use
    when documenting REST or GraphQL APIs.

[brag-sheet]
    Source: awesome-copilot
    What it does: Turns half-remembered work into evidence-backed accomplishment statements for
    performance reviews, promotions, and status updates, digging through commit history, pull
    requests, and session logs to reconstruct what you did.
    When to use: You need to write a self-review or weekly update and cannot remember everything
    you accomplished.
    Search terms: performance review, self review, accomplishments, brag sheet, promotion,
    weekly update, status report, what did i do, impact statements
    Original description: Turn vague "what did I do?" into evidence-backed impact statements for
    performance reviews, self-reviews, promotion packets, and weekly updates. Uniquely mines
    Copilot CLI session logs to reconstruct forgotten work, plus git commits and GitHub PRs.
    Enforces a 3-part impact contract (action → result → evidence). Works standalone with zero
    dependencies. Trigger for: "brag", "log work", "what did I do", "backfill my work history",
    "performance review", "self-review", "self assessment", "write impact statement", "review
    prep", "promo packet", "promotion case", "weekly update", "status report", "ac…

[changelog-automation]
    Source: agents (bundle)
    What it does: Generates release notes and changelogs automatically from commits and pull
    requests in a standard format.
    When to use: You want release notes produced automatically each time you ship.
    Search terms: changelog, release notes, keep a changelog, commit conventions, release
    workflow, version history, automation
    Original description: Automate changelog generation from commits, PRs, and releases
    following Keep a Changelog format. Use when setting up release workflows, generating release
    notes, or standardizing commit conventions.

[code-tour]
    Source: awesome-copilot
    What it does: Creates guided, step-by-step walkthroughs of a codebase tailored to a specific
    audience, such as new hires, bug fixers, or reviewers.
    When to use: You want to help someone get oriented in a codebase quickly.
    Search terms: code tour, onboarding, walkthrough, codebase guide, new hire, architecture
    tour, explain how it works, contributor guide
    Original description: Use this skill to create CodeTour .tour files — persona-targeted,
    step-by-step walkthroughs that link to real files and line numbers. Trigger for: "create a
    tour", "make a code tour", "generate a tour", "onboarding tour", "tour for this PR", "tour
    for this bug", "RCA tour", "architecture tour", "explain how X works", "vibe check", "PR
    review tour", "contributor guide", "help someone ramp up", or any request for a structured
    walkthrough through code. Supports 20 developer personas (new joiner, bug fixer, architect,
    PR reviewer, vibecoder, security reviewer, and more), all CodeTour step types (f…

[comment-code-generate-a-tutorial]
    Source: awesome-copilot
    What it does: Refactors a Python script, adds clear teaching comments, and writes a complete
    beginner-friendly tutorial to go with it.
    When to use: You want to turn a script into a learning resource.
    Search terms: python tutorial, beginner, code comments, teaching, markdown tutorial,
    learning material, refactor
    Original description: Transform this Python script into a polished, beginner-friendly
    project by refactoring the code, adding clear instructional comments, and generating a
    complete markdown tutorial.

[copy-editing]
    Source: coreyhaines31 marketingskills
    What it does: Edits and polishes existing marketing copy, tightening wording, fixing awkward
    phrasing, and refreshing outdated content without starting over.
    When to use: You have marketing text that reads poorly or is out of date and want it
    improved.
    Search terms: copy editing, proofread, polish text, tighten copy, too wordy, content
    refresh, update page, content audit, marketing copy
    Original description: When the user wants to edit, review, or improve existing marketing
    copy, or refresh outdated content. Also use when the user mentions 'edit this copy,' 'review
    my copy,' 'copy feedback,' 'proofread,' 'polish this,' 'make this better,' 'copy sweep,'
    'tighten this up,' 'this reads awkwardly,' 'clean up this text,' 'too wordy,' 'sharpen the
    messaging,' 'refresh this content,' 'update this page,' 'this content is outdated,' or
    'content audit.' Use this when the user already has copy and wants it improved or refreshed
    rather than rewritten from scratch. For writing new copy, see copywriting.

[copywriting]
    Source: coreyhaines31 marketingskills
    What it does: Writes persuasive website copy for homepages, landing pages, pricing pages,
    and product pages, including headlines, taglines, and calls to action.
    When to use: You need website text that convinces visitors to buy or sign up.
    Search terms: copywriting, website copy, landing page, headline, tagline, call to action,
    value proposition, homepage text, marketing copy
    Original description: When the user wants to write, rewrite, or improve marketing copy for
    any page — including homepage, landing pages, pricing pages, feature pages, about pages, or
    product pages. Also use when the user says "write copy for," "improve this copy," "rewrite
    this page," "marketing copy," "headline help," "CTA copy," "value proposition," "tagline,"
    "subheadline," "hero section copy," "above the fold," "this copy is weak," "make this more
    compelling," or "help me describe my product." Use this whenever someone is working on
    website text that needs to persuade or convert. For email copy, see emails. For…

[create-architectural-decision-record]
    Source: awesome-copilot
    What it does: Writes a formal record of a technical decision, including context, options
    considered, and consequences, in a format that both people and AI tools can use.
    When to use: Your team made an important technical choice and wants it documented.
    Search terms: adr, decision record, architecture decision, documentation, technical
    decision, design rationale, engineering docs
    Original description: Create an Architectural Decision Record (ADR) document for AI-
    optimized decision documentation.

[create-readme]
    Source: awesome-copilot
    What it does: Writes a README file that introduces a project, explains what it does, and
    shows how to get started.
    When to use: Your project has no front-page documentation.
    Search terms: readme, project documentation, getting started, github readme, project
    overview, docs, setup instructions
    Original description: Create a README.md file for the project

[create-tldr-page]
    Source: awesome-copilot
    What it does: Creates a short, example-driven cheat sheet for a command-line tool from its
    documentation.
    When to use: You want a quick reference page for a command instead of reading full manuals.
    Search terms: tldr, cheat sheet, command reference, quick reference, cli docs, examples,
    documentation
    Original description: Create a tldr page from documentation URLs and command examples,
    requiring both URL and command name.

[doc-and-modernize]
    Source: awesome-copilot
    What it does: Produces a thorough architecture document of a codebase by reading its files,
    and can then plan a phased modernization or migration away from a legacy system.
    When to use: You need to understand or document an unfamiliar codebase, or plan how to
    modernize an old one.
    Search terms: architecture document, codebase documentation, onboarding doc, legacy system,
    modernize, migration plan, rewrite, system design
    Original description: Two related workflows for a locally-cloned codebase, in one skill.
    Documentation mode produces a single, comprehensive, verifiable architecture document
    primarily by reading files on disk (local-first) — use it whenever the user wants to
    understand, map, document, research, or onboard onto a codebase ("research this repo",
    "write up the architecture", "do an architecture deep dive", "document how this codebase
    works", "map the system design", "create an onboarding doc"). Modernization mode generates a
    phased plan to modernize, migrate, upgrade, or rewrite a legacy system ("modernize this",
    "pl…

[doc-coauthoring]
    Source: anthropic skills
    What it does: Guides you through writing documentation, proposals, or specs collaboratively,
    gathering context, iterating on drafts, and checking the result works for readers.
    When to use: You need to write a proposal, spec, or decision document and want structured
    help.
    Search terms: write documentation, proposal, technical spec, decision doc, co-author, draft
    document, writing help
    Original description: Guide users through a structured workflow for co-authoring
    documentation. Use when user wants to write documentation, proposals, technical specs,
    decision docs, or similar structured content. This workflow helps users efficiently transfer
    context, refine content through iteration, and verify the doc works for readers. Trigger
    when user mentions writing docs, creating proposals, drafting specs, or similar
    documentation tasks.

[documentation-and-adrs]
    Source: agent-skills
    What it does: Records architectural decisions and documentation so future engineers and AI
    agents understand why the code is the way it is.
    When to use: You are making a significant technical change and want the reasoning preserved.
    Search terms: adr, decision record, documentation, architecture, api changes, engineering
    context, knowledge capture
    Original description: Records decisions and documentation. Use when making architectural
    decisions, changing public APIs, shipping features, or when you need to record context that
    future engineers and agents will need to understand the codebase.

[documentation-engineer]
    Source: agent-playbook
    What it does: Writes clear, comprehensive technical documentation, READMEs, and code
    documentation.
    When to use: You need documentation written for software.
    Search terms: technical documentation, write docs, readme, document code, developer docs,
    user guide, technical writing
    Original description: Technical documentation expert for creating clear, comprehensive
    documentation. Use when user asks to write docs, create README, or document code.

[documentation-writer]
    Source: awesome-copilot
    What it does: Writes high-quality software documentation organized by the Diataxis framework
    into tutorials, how-to guides, reference, and explanation.
    When to use: You want well-structured documentation that serves learners and experts alike.
    Search terms: documentation, diataxis, tutorials, how-to guides, reference docs, technical
    writing, software docs
    Original description: Diátaxis Documentation Expert. An expert technical writer specializing
    in creating high-quality software documentation, guided by the principles and structure of
    the Diátaxis technical documentation authoring framework.

[domain-modeling]
    Source: mattpocock skills
    What it does: Builds and refines a shared vocabulary and model of the business concepts in a
    project, recording it in context files and decision records.
    When to use: Your team uses inconsistent terms for the same things and needs a shared
    language.
    Search terms: domain model, terminology, glossary, ubiquitous language, context.md, adr,
    business concepts
    Original description: Build and sharpen a project's domain model. Use when discussing
    codebase terminology, writing or editing a CONTEXT.md, or recording or editing an ADR.

[em-dash]
    Source: awesome-copilot
    What it does: Finds and replaces em and en dashes with plain hyphens in code, comments, and
    data files, and advises on correct punctuation.
    When to use: You want dashes standardized or removed from written text or code.
    Search terms: em dash, en dash, punctuation, hyphen, formatting, text cleanup, writing style
    Original description: Expert on the history, origin, and correct use of the em dash. Use
    when writing or reviewing code, comments, or data files to avoid em and en dashes,
    defaulting to never using them and replacing any found with a hyphen (-). Includes strong
    knowledge of punctuation marks and the proper usage of punctuation characters when writing
    comments.

[email-drafter]
    Source: awesome-copilot
    What it does: Drafts and reviews professional emails in your own writing style by studying
    your sent emails for tone, greetings, and sign-offs.
    When to use: You need to write or reply to an email that sounds like you.
    Search terms: draft email, write email, reply email, follow-up email, email tone,
    professional email, workiq, compose email
    Original description: Draft and review professional emails that match your personal writing
    style. Analyzes your sent emails for tone, greeting, structure, and sign-off patterns via
    WorkIQ, then generates context-aware drafts for any recipient. USE FOR: draft email, write
    email, compose email, reply email, follow-up email, analyze email tone, email style.

[finnish-humanizer]
    Source: awesome-copilot
    What it does: Edits Finnish text to remove telltale signs of AI writing so it reads like a
    native speaker wrote it.
    When to use: You have AI-generated Finnish text that sounds robotic.
    Search terms: finnish, humanize, remove ai feel, natural language, translation polish, ai
    detection, editing
    Original description: Detect and remove AI-generated markers from Finnish text, making it
    sound like a native Finnish speaker wrote it. Use when asked to "humanize", "naturalize", or
    "remove AI feel" from Finnish text, or when editing .md/.txt files containing Finnish
    content. Identifies 26 patterns (12 Finnish-specific + 14 universal) and 4 style markers.

[grill-with-docs]
    Source: mattpocock skills
    What it does: Interviews you relentlessly about a plan or design to expose gaps, while
    producing decision records and a glossary along the way.
    When to use: You want a plan stress-tested with hard questions before committing to it.
    Search terms: plan review, design interview, tough questions, adr, glossary, stress test
    idea, planning
    Original description: A relentless interview to sharpen a plan or design, which also creates
    docs (ADR's and glossary) as we go.

[internal-comms]
    Source: anthropic skills
    What it does: Writes internal company communications such as status reports, leadership
    updates, newsletters, FAQs, and incident reports in your company's preferred formats.
    When to use: You need to write an update or announcement for people inside your company.
    Search terms: internal communications, status report, leadership update, newsletter, faq,
    incident report, project update, company announcement
    Original description: A set of resources to help me write all kinds of internal
    communications, using the formats that my company likes to use. Claude should use this skill
    whenever asked to write some sort of internal communications (status reports, leadership
    updates, 3P updates, company newsletters, FAQs, incident reports, project updates, etc.).

[java-docs]
    Source: awesome-copilot
    What it does: Adds and checks Javadoc comments on Java code so every type is documented to
    best-practice standards.
    When to use: Your Java code lacks documentation comments.
    Search terms: java, javadoc, code documentation, comments, documentation standards, api docs
    Original description: Ensure that Java types are documented with Javadoc comments and follow
    best practices for documentation.

[meeting-minutes]
    Source: awesome-copilot
    What it does: Writes concise meeting minutes with attendees, agenda, decisions, action items
    with owners and due dates, and follow-ups.
    When to use: You just finished a meeting and need a clean record of what was decided.
    Search terms: meeting minutes, meeting notes, action items, decisions, meeting summary,
    follow-ups, attendees
    Original description: Generate concise, actionable meeting minutes for internal meetings.
    Includes metadata, attendees, agenda, decisions, action items (owner + due date), and
    follow-up steps.

[mkdocs-translations]
    Source: awesome-copilot
    What it does: Produces a translated version of documentation built with MkDocs.
    When to use: You want your MkDocs documentation site available in another language.
    Search terms: mkdocs, translation, localize docs, multilingual, documentation, language
    version
    Original description: Generate a language translation for a mkdocs documentation stack.

[oo-component-documentation]
    Source: awesome-copilot
    What it does: Creates or updates standardized documentation for software components using a
    shared template.
    When to use: You need consistent documentation across the components of a software system.
    Search terms: component documentation, software docs, template, object oriented, technical
    documentation, standardize docs
    Original description: Create or update standardized object-oriented component documentation
    using a shared template plus mode-specific guidance for new and existing docs.

[performance-review-writer]
    Source: awesome-copilot
    What it does: Drafts performance reviews, self-assessments, peer feedback, and upward
    feedback in your voice, drawing on your work history, emails, and meetings.
    When to use: Review season has arrived and you need to write an honest, impact-focused
    review.
    Search terms: performance review, self assessment, peer review, 360 feedback, annual review,
    upward feedback, star format, workiq
    Original description: Draft performance reviews, self-assessments, peer reviews, and upward
    feedback in your own voice. Analyzes your contributions, emails, and meeting history via
    WorkIQ, then produces honest, impact-focused drafts using the STAR format. USE FOR: write my
    performance review, draft self-assessment, peer review, 360 feedback, annual review, mid-
    year review, upward feedback, write review for colleague, performance appraisal.

[postmortem-writing]
    Source: agents (bundle)
    What it does: Writes blameless incident postmortems with timelines, root-cause analysis, and
    action items.
    When to use: Something went wrong and you need to document what happened and how to prevent
    it.
    Search terms: postmortem, incident review, root cause analysis, outage report, blameless,
    action items, incident response
    Original description: Write effective blameless postmortems with root cause analysis,
    timelines, and action items. Use when conducting incident reviews, writing postmortem
    documents, or improving incident response processes.

[product-changelog]
    Source: inference.sh superpowers
    What it does: Writes product release notes and changelogs in plain, user-friendly language
    that customers will actually read, with guidance on visuals and distribution.
    When to use: You are shipping an update and need to tell customers what is new.
    Search terms: release notes, changelog, product update, what's new, feature announcement,
    version notes, customer communication
    Original description: Product changelog and release notes that users actually read. Covers
    categorization, user-facing language, visuals, and distribution. Use for: release notes,
    changelogs, product updates, feature announcements, versioning. Triggers: changelog, release
    notes, product update, version notes, what's new, feature announcement, product changelog,
    update log, release announcement, version release, product release, ship notes

[readme-blueprint-generator]
    Source: awesome-copilot
    What it does: Analyzes a project's existing documentation and Copilot instructions to
    generate a comprehensive, well-structured README.
    When to use: You want a thorough README built from the documentation your project already
    has.
    Search terms: readme, project documentation, github, copilot instructions, tech stack,
    developer docs, generate docs
    Original description: Intelligent README.md generation prompt that analyzes project
    documentation structure and creates comprehensive repository documentation. Scans
    .github/copilot directory files and copilot-instructions.md to extract project information,
    technology stack, architecture, development workflow, coding standards, and testing
    approaches while generating well-structured markdown documentation with proper formatting,
    cross-references, and developer-focused content.

[readout]
    Source: warp common-skills
    What it does: Produces a polished, shareable HTML report summarizing findings from the
    current conversation or from fresh research into a codebase.
    When to use: You want a clean written document capturing what was learned or how something
    works.
    Search terms: readout, write up, report, shareable document, findings, html doc, explain how
    it works, summary
    Original description: Produce a polished, self-contained HTML "readout" document under
    ~/.readouts (with an auto-maintained index page), either by snapshotting the findings
    accumulated in the current conversation or — when invoked fresh, e.g. "/readout on how
    github webhook events are processed" — by sharpening scope with clarifying questions and
    researching the codebase before documenting. The work runs in a child agent so the main
    conversation's context stays clean. Use whenever the user invokes /readout, says "write this
    up", "turn this into a doc/page", "make a readout", or asks for a readable, shareable
    docume…

[repo-story-time]
    Source: awesome-copilot
    What it does: Summarizes a code repository and tells the story of how it evolved based on
    its commit history.
    When to use: You want a narrative overview of a project's history.
    Search terms: repository summary, commit history, project story, git history, narrative,
    codebase overview
    Original description: Generate a comprehensive repository summary and narrative story from
    commit history

[scan]
    Source: agents (bundle)
    What it does: Scans a codebase to generate project documentation and an AGENTS.md guide for
    AI agents, and detects drift on later runs.
    When to use: You are setting up a repo for AI-assisted work or refreshing its documentation
    after big changes.
    Search terms: agents.md, project documentation, codebase scan, ai agent setup, architecture
    docs, drift detection
    Original description: Scans the codebase to generate project-doc.md and AGENTS.md. Use when
    bootstrapping a new agent-driven repo, refreshing project documentation after architectural
    changes, or running a delta scan to detect drift. Runs a full scan on first use and a smart
    delta scan on subsequent runs. Uses understand-anything + context-mode when available, falls
    back to native tools otherwise. Only updates AGENTS.md on detected architectural changes
    with human confirmation.

[signal-write]
    Source: awesome-copilot
    What it does: Emits structured status signals from an AI agent, such as blocked, done, or
    checkpoint, to files for a dashboard to display.
    When to use: You are running agents and want them to report their status to a dashboard.
    Search terms: agent signals, status updates, dashboard, blocked, checkpoint, agent
    monitoring, json signals
    Original description: Emit structured agent signals — hands-up, blocked, done, checkpoint,
    partnership. Signals are written as JSON to .signals/ for dashboard consumption and noted in
    the journal for persistence.

[steno-mode]
    Source: awesome-copilot
    What it does: Switches responses to a compressed shorthand style that cuts roughly 40% of
    words while keeping technical details exact.
    When to use: You want shorter, denser answers to save time or tokens.
    Search terms: shorthand, concise responses, token reduction, brief output, compressed,
    steno, terse
    Original description: Shorthand-first response compression that cuts ~40% of response tokens
    while preserving technical precision and exact literals. Use when the user says "steno
    mode", "shorthand mode", "compressed responses", "token reduction", "brief structured
    output", or invokes /steno. Supports four compression levels: lite, brief, court, machine.
    Do not trigger for requests needing polished prose such as onboarding/tutorial content,
    stakeholder or customer-facing copy, or teaching-focused explanations.

[technical-blog-writing]
    Source: inference.sh superpowers
    What it does: Writes technical blog posts and developer tutorials with well-formatted code
    examples and the right depth for a developer audience.
    When to use: You want to publish an engineering blog post or coding tutorial.
    Search terms: technical blog, engineering blog, developer tutorial, tech article, code
    tutorial, developer content, technical writing
    Original description: Technical blog post writing with structure, code examples, and
    developer audience conventions. Covers post types, code formatting, explanation depth, and
    developer-specific engagement patterns. Use for: engineering blogs, dev tutorials, technical
    writing, developer content, documentation posts. Triggers: technical blog, dev blog,
    engineering blog, technical writing, developer tutorial, tech post, code tutorial,
    programming blog, developer content, technical article, engineering post, coding tutorial,
    technical content

[tldr-prompt]
    Source: awesome-copilot
    What it does: Creates short summaries of GitHub Copilot prompt files, agents, MCP servers,
    or documentation from URLs and queries.
    When to use: You want a quick digest of a Copilot resource or documentation page.
    Search terms: tldr, summary, github copilot, mcp server, documentation summary, quick
    overview
    Original description: Create tldr summaries for GitHub Copilot files (prompts, agents,
    instructions, collections), MCP servers, or documentation from URLs and queries.

[update-markdown-file-index]
    Source: awesome-copilot
    What it does: Updates a section of a markdown file with an index or table listing the files
    in a given folder.
    When to use: You want a markdown document to keep an up-to-date list of files in a folder.
    Search terms: markdown, file index, table of contents, folder listing, documentation, auto-
    generated index
    Original description: Update a markdown file section with an index/table of files from a
    specified folder.

[write]
    Source: waza
    What it does: Rewrites and polishes prose in Chinese or English, removes AI-sounding
    wording, and reviews localized product copy while keeping the original meaning.
    When to use: You need a draft, release note, or social post polished so it reads naturally.
    Search terms: rewrite, proofread, polish writing, remove ai wording, localization, chinese,
    english, release notes, social posts
    Original description: Rewrites and polishes prose in Chinese or English, removes AI-like
    wording, and reviews product localization copy while preserving intent for drafts, docs,
    release notes, launch copy, and social posts. Use when users ask in any language to draft,
    rewrite, proofread, localize, polish release notes, remove AI-like wording, or prepare
    launch and social copy. Not for code comments, commit messages, or inline docs.

[write-feature-docs]
    Source: warp common-skills
    What it does: Drafts a complete documentation page for a new Warp feature from its product
    or technical spec, researching the codebase if no spec exists.
    When to use: An engineer at Warp needs a first-pass docs page for a new feature.
    Search terms: feature documentation, warp, docs page, mdx, product spec, tech spec,
    developer docs
    Original description: Draft a complete documentation page for a new Warp feature from its
    PRODUCT.md and/or TECH.md spec. Use when an engineer has written a spec and needs to produce
    a first-pass MDX draft for the warpdotdev/docs repo. Also handles features without specs by
    researching the codebase first. Invoke this skill whenever an engineer mentions writing docs
    for a feature, drafting a docs page, creating feature documentation, starting the eng-docs
    workflow, or converting a spec into documentation. Works from warp-internal or warp-server.

[write-product-spec]
    Source: warp common-skills
    What it does: Writes a detailed product specification describing how a significant user-
    facing feature should behave and how to validate it.
    When to use: You need to define a feature's behavior before anyone builds it.
    Search terms: product spec, prd, feature behavior, requirements, product.md, warp,
    specification
    Original description: Write a PRODUCT.md spec for a significant user-facing feature in Warp,
    focused on detailed behavior and validation. Use when the user asks for a product spec,
    desired behavior doc, or PRD, wants to define feature behavior before implementation, or
    when the feature is substantial or behaviorally ambiguous enough that a written spec would
    improve implementation or review.

[write-tech-spec]
    Source: warp common-skills
    What it does: Writes a technical specification for a feature after researching the current
    codebase and its constraints.
    When to use: You have a product spec and need an implementation plan or architecture
    document.
    Search terms: tech spec, technical specification, implementation plan, architecture doc,
    tech.md, warp, engineering design
    Original description: Write a TECH.md spec for a significant Warp feature after researching
    the current codebase and implementation constraints. Use when the user asks for a technical
    spec, implementation plan, or architecture doc tied to a product spec.

[writing-beats]
    Source: mattpocock skills
    What it does: Assembles raw notes into a sequence of narrative beats, making sure each term
    is explained before the writing relies on it.
    When to use: You have rough material and want to turn it into a structured story arc.
    Search terms: writing, narrative structure, story beats, outline, drafting, organize notes,
    article structure
    Original description: Writing, exploit — assemble raw material into a journey of beats,
    grounding each term before a beat leans on it.

[writing-for-agents]
    Source: mattpocock skills
    What it does: Writes documents meant to be read by AI agents, such as skills, AGENTS.md, or
    CLAUDE.md files, in a way agents follow reliably.
    When to use: You are creating or editing instructions for an AI coding agent.
    Search terms: agents.md, claude.md, skill writing, ai instructions, prompt writing, agent
    docs, documentation for ai
    Original description: Writing documents for agents. Use when creating or editing skills, or
    modifying AGENTS.md or CLAUDE.md.

[writing-fragments]
    Source: mattpocock skills
    What it does: Mines rough ideas and raw fragments for a piece of writing without imposing
    any structure yet.
    When to use: You are at the very start of writing and just want to get ideas out.
    Search terms: brainstorm, writing, raw ideas, fragments, freewriting, explore ideas, early
    draft
    Original description: Writing, explore — mine raw fragments, no structure yet.

[writing-guidelines]
    Source: vercel agent-skills
    What it does: Reviews documentation and prose against a writing style handbook for voice,
    tone, and consistency.
    When to use: You want your docs checked against your house writing style.
    Search terms: writing style, style guide, review docs, voice and tone, prose audit,
    documentation review, consistency
    Original description: Review docs/prose for Writing Guidelines compliance. Use when asked to
    "review my docs", "check writing style", "audit prose", "review docs voice and tone", or
    "check this page against the writing handbook".

[writing-shape]
    Source: mattpocock skills
    What it does: Shapes raw material into a finished article, working through it paragraph by
    paragraph.
    When to use: You have notes and an outline and want them turned into a polished article.
    Search terms: writing, article, draft, paragraph, shape content, polish prose, essay
    Original description: Writing, exploit — shape raw material into an article, paragraph by
    paragraph.
