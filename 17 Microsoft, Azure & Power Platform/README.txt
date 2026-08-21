17 MICROSOFT, AZURE & POWER PLATFORM
====================================

Skills for the Microsoft ecosystem: Azure, .NET and C#, Power BI, Power Platform and Power
Automate, Dataverse, Copilot, Semantic Kernel, TypeSpec and Visual Studio Code extensions.

93 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - appinsights-instrumentation
  - arduino-azure-iot-edge-integration
  - aspire
  - aspnet-minimal-api-openapi
  - az-cost-optimize
  - azure-architecture-autopilot
  - azure-container-registry-cli
  - azure-deployment-preflight
  - azure-developer-cli
  - azure-devops-cli
  - azure-pricing
  - azure-resource-health-diagnose
  - azure-resource-visualizer
  - azure-role-selector
  - azure-smart-city-iot-solution-builder
  - azure-static-web-apps
  - azure-well-architected-review
  - containerize-aspnet-framework
  - containerize-aspnetcore
  - copilot-cli-quickstart
  - copilot-instructions-blueprint-generator
  - copilot-pr-autopilot
  - copilot-sdk
  - copilot-spaces
  - copilot-usage-metrics
  - create-canvas-extension
  - csharp-async
  - csharp-docs
  - csharp-mstest
  - csharp-nunit
  - csharp-tunit
  - csharp-xunit
  - d365-solution-blueprint
  - dataverse-python-advanced-patterns
  - dataverse-python-production-code
  - dataverse-python-quickstart
  - dataverse-python-usecase-builder
  - declarative-agents
  - dotnet-best-practices
  - dotnet-design-pattern-review
  - dotnet-mcp-builder
  - dotnet-timezone
  - dotnet-upgrade
  - ef-core
  - entra-agent-user
  - fabric-lakehouse
  - flowstudio-power-automate-build
  - flowstudio-power-automate-debug
  - flowstudio-power-automate-governance
  - flowstudio-power-automate-mcp
  - flowstudio-power-automate-monitoring
  - fluentui-blazor
  - foundry-agent-sync
  - foundry-hosted-agent-copilotkit
  - github-copilot-starter
  - mcp-copilot-studio-server-generator
  - microsoft-agent-framework
  - microsoft-code-reference
  - microsoft-docs
  - microsoft-skill-creator
  - msgraph-sdk
  - msstore-cli
  - mvvm-toolkit
  - mvvm-toolkit-di
  - mvvm-toolkit-messenger
  - nuget-manager
  - pester-migration
  - pester-should-migration
  - power-apps-code-app-scaffold
  - power-bi-dax-optimization
  - power-bi-model-design-review
  - power-bi-performance-troubleshooting
  - power-bi-report-design-consultation
  - power-platform-architect
  - power-platform-mcp-connector-suite
  - powerbi-modeling
  - python-azure-iot-edge-modules
  - semantic-kernel
  - ssma-console
  - suggest-awesome-github-copilot-agents
  - suggest-awesome-github-copilot-instructions
  - suggest-awesome-github-copilot-skills
  - system-commandline-cli
  - terraform-azurerm-set-diff-analyzer
  - typespec-api-operations
  - typespec-create-agent
  - typespec-create-api-plugin
  - update-avm-modules-in-bicep
  - vscode-ext-commands
  - vscode-ext-localization
  - winmd-api-search
  - winui3-migration-guide
  - workiq-copilot

SKILL DETAILS
-------------

[appinsights-instrumentation]
    Source: awesome-copilot
    What it does: Sets up a web app to report how it is performing and where it is failing to
    Azure Application Insights, Microsoft's monitoring service.
    When to use: You want to see errors, slow pages, and usage stats for an app running on
    Azure.
    Search terms: azure, application insights, app monitoring, telemetry, error tracking,
    website performance, logging, microsoft azure
    Original description: Instrument a webapp to send useful telemetry data to Azure App
    Insights

[arduino-azure-iot-edge-integration]
    Source: awesome-copilot
    What it does: Connects Arduino devices and sensors to Microsoft's Azure IoT Hub so they can
    securely send readings and receive commands from the cloud.
    When to use: You have physical sensors or devices built on Arduino and want them talking to
    Azure.
    Search terms: arduino, iot, azure iot hub, sensors, connected devices, smart devices, iot
    edge, hardware, telemetry
    Original description: Design and implement Arduino integration with Azure IoT Hub and IoT
    Edge, including secure provisioning, resilient telemetry, command handling, and production
    guardrails.

[aspire]
    Source: awesome-copilot
    What it does: Helps build, run, debug, and deploy applications made of several connected
    services using Microsoft's Aspire toolkit.
    When to use: Your developers are building a multi-service .NET app and need help with Aspire
    setup or deployment.
    Search terms: aspire, .net aspire, microservices, dotnet, azure deployment, app
    orchestration, microsoft, developer tools
    Original description: Aspire skill covering the Aspire CLI, AppHost orchestration, service
    discovery, integrations, MCP server, VS Code extension, Dev Containers, GitHub Codespaces,
    templates, dashboard, and deployment. Use when the user asks to create, run, debug,
    configure, deploy, or troubleshoot an Aspire distributed application.

[aspnet-minimal-api-openapi]
    Source: awesome-copilot
    What it does: Creates lightweight web API endpoints in ASP.NET with proper, auto-generated
    documentation so other developers know how to use them.
    When to use: You need a simple, well-documented API built on Microsoft's .NET platform.
    Search terms: asp.net, api, openapi, swagger, dotnet, web api, api documentation, minimal
    api, c#
    Original description: Create ASP.NET Minimal API endpoints with proper OpenAPI documentation

[az-cost-optimize]
    Source: awesome-copilot
    What it does: Reviews the Azure cloud resources your app uses and finds ways to lower the
    bill, logging each savings idea as a GitHub issue.
    When to use: Your Azure bill is higher than you would like and you want concrete ways to cut
    it.
    Search terms: azure costs, cloud bill, reduce cloud spending, cost optimization, azure, save
    money, cloud waste, infrastructure costs
    Original description: Analyze Azure resources used in the app (IaC files and/or resources in
    a target rg) and optimize costs - creating GitHub issues for identified optimizations.

[azure-architecture-autopilot]
    Source: awesome-copilot
    What it does: Designs Azure cloud setups from a plain-English description, draws
    architecture diagrams, refines them through conversation, and deploys them with Bicep
    templates.
    When to use: You want to plan or document how your systems run on Azure without hand-drawing
    diagrams.
    Search terms: azure, cloud architecture, architecture diagram, bicep, cloud setup,
    infrastructure design, deploy to azure, system diagram
    Original description: Design Azure infrastructure using natural language, or analyze
    existing Azure resources to auto-generate architecture diagrams, refine them through
    conversation, and deploy with Bicep. When to use this skill: - "Create X on Azure", "Set up
    a RAG architecture" (new design) - "Analyze my current Azure infrastructure", "Draw a
    diagram for rg-xxx" (existing analysis) - "Foundry is slow", "I want to reduce costs",
    "Strengthen security" (natural language modification) - Azure resource deployment, Bicep
    template generation, IaC code generation - Microsoft Foundry, AI Search, OpenAI, Fabric,
    ADLS Gen2…

[azure-container-registry-cli]
    Source: awesome-copilot
    What it does: Manages Azure Container Registry from the command line: storing app images,
    running cloud builds, handling access, and replicating across regions.
    When to use: Your team stores Docker container images in Azure and needs to push, clean up,
    or secure them.
    Search terms: azure container registry, docker, containers, acr, container images, azure,
    cloud builds, devops
    Original description: Manage Azure Container Registry via the az acr CLI including
    registries, images, cloud builds, ACR Tasks, authentication, tokens, geo-replication, and
    networking. Use when working with ACR, az acr commands, pushing/importing/purging container
    images in Azure, or when the user mentions Azure Container Registry.

[azure-deployment-preflight]
    Source: awesome-copilot
    What it does: Checks an Azure deployment before it runs by validating templates, previewing
    what will change, and confirming you have the right permissions.
    When to use: You are about to deploy changes to Azure and want to catch problems before
    anything breaks.
    Search terms: azure deployment, bicep, pre-deployment check, what-if, deployment validation,
    azure, infrastructure, avoid outages
    Original description: Performs comprehensive preflight validation of Bicep deployments to
    Azure, including template syntax validation, what-if analysis, and permission checks. Use
    this skill before any deployment to Azure to preview changes, identify potential issues, and
    ensure the deployment will succeed. Activate when users mention deploying to Azure,
    validating Bicep files, checking deployment permissions, previewing infrastructure changes,
    running what-if, or preparing for azd provision.

[azure-developer-cli]
    Source: awesome-copilot
    What it does: Sets up and troubleshoots projects that use the Azure Developer CLI (azd), the
    tool that packages an app and its cloud infrastructure for one-command deployment.
    When to use: Your developers use azd to deploy to Azure and need help with configuration,
    environments, or CI/CD.
    Search terms: azd, azure developer cli, deploy to azure, azure.yaml, bicep, terraform,
    ci/cd, azure
    Original description: Design, create, review, migrate, or troubleshoot Azure Developer CLI
    (azd) projects using current Microsoft guidance. Use for azd, azure.yaml, AZD templates,
    Bicep or Terraform under infra, AZD environments and secrets, hooks, deployment workflows,
    and azd-managed CI/CD.

[azure-devops-cli]
    Source: awesome-copilot
    What it does: Manages Azure DevOps from the command line: projects, code repositories, build
    pipelines, pull requests, and work items.
    When to use: Your team uses Azure DevOps and wants to automate routine project or pipeline
    tasks.
    Search terms: azure devops, pipelines, ci/cd, work items, pull requests, build automation,
    microsoft devops, repos
    Original description: Manage Azure DevOps resources via CLI including projects, repos,
    pipelines, builds, pull requests, work items, artifacts, and service endpoints. Use when
    working with Azure DevOps, az commands, devops automation, CI/CD, or when user mentions
    Azure DevOps CLI.

[azure-pricing]
    Source: awesome-copilot
    What it does: Looks up current Azure prices for any service and estimates costs, including
    credit usage for Copilot Studio agents.
    When to use: You want to know what an Azure service will cost before you commit to it.
    Search terms: azure pricing, cloud costs, price comparison, cost estimate, azure, copilot
    studio credits, how much does azure cost, budget
    Original description: Fetches real-time Azure retail pricing using the Azure Retail Prices
    API (prices.azure.com) and estimates Copilot Studio agent credit consumption. Use when the
    user asks about the cost of any Azure service, wants to compare SKU prices, needs pricing
    data for a cost estimate, mentions Azure pricing, Azure costs, Azure billing, or asks about
    Copilot Studio pricing, Copilot Credits, or agent usage estimation. Covers compute, storage,
    networking, databases, AI, Copilot Studio, and all other Azure service families.

[azure-resource-health-diagnose]
    Source: awesome-copilot
    What it does: Checks the health of your Azure resources, digs through logs to find what is
    wrong, and writes a plan to fix it.
    When to use: Something in your Azure environment is failing or slow and you need to know
    why.
    Search terms: azure, outage, troubleshooting, resource health, logs, diagnose issues, cloud
    problems, remediation
    Original description: Analyze Azure resource health, diagnose issues from logs and
    telemetry, and create a remediation plan for identified problems.

[azure-resource-visualizer]
    Source: awesome-copilot
    What it does: Scans an Azure resource group and produces a diagram showing how each resource
    connects to the others.
    When to use: You want a clear picture of what is running in Azure and how the pieces fit
    together.
    Search terms: azure diagram, architecture diagram, resource group, mermaid, visualize
    infrastructure, azure, cloud map, documentation
    Original description: Analyze Azure resource groups and generate detailed Mermaid
    architecture diagrams showing the relationships between individual resources. Use this skill
    when the user asks for a diagram of their Azure resources or help in understanding how the
    resources relate to each other.

[azure-role-selector]
    Source: awesome-copilot
    What it does: Recommends the Azure permission role that gives a person or app exactly the
    access it needs and nothing more, and shows how to apply it.
    When to use: You need to grant someone access in Azure and want to avoid giving them too
    much.
    Search terms: azure permissions, access control, rbac, least privilege, user roles, azure
    security, who can access, identity
    Original description: When user is asking for guidance for which role to assign to an
    identity given desired permissions, this agent helps them understand the role that will meet
    the requirements with least privilege access and how to apply that role.

[azure-smart-city-iot-solution-builder]
    Source: awesome-copilot
    What it does: Plans complete Azure IoT and smart-city projects end to end, covering
    requirements, architecture, security, operations, cost, and a phased rollout.
    When to use: You are scoping a large connected-devices or smart-city project on Azure.
    Search terms: iot, smart city, azure iot, connected devices, sensors, solution design,
    project plan, architecture
    Original description: Design and plan end-to-end Azure IoT and Smart City solutions:
    requirements, architecture, security, operations, cost, and a phased delivery plan with
    concrete implementation artifacts.

[azure-static-web-apps]
    Source: awesome-copilot
    What it does: Builds, configures, and deploys websites to Azure Static Web Apps, including
    adding backend functions and automatic deployment from GitHub.
    When to use: You want to host a simple website or web app on Azure with minimal setup.
    Search terms: azure static web apps, host website, deploy website, static site, azure,
    github actions, web hosting, swa
    Original description: Helps create, configure, and deploy Azure Static Web Apps using the
    SWA CLI. Use when deploying static sites to Azure, setting up SWA local development,
    configuring staticwebapp.config.json, adding Azure Functions APIs to SWA, or setting up
    GitHub Actions CI/CD for Static Web Apps.

[azure-well-architected-review]
    Source: awesome-copilot
    What it does: Reviews your Azure setup against Microsoft's Well-Architected Framework for
    reliability, security, cost, operations, and performance, and logs improvements as GitHub
    issues.
    When to use: You want an expert-style audit of whether your Azure environment follows best
    practices.
    Search terms: azure review, well-architected, cloud audit, best practices, reliability,
    security review, azure, infrastructure assessment
    Original description: Perform an Azure Well-Architected Framework review of the current
    workload IaC and architecture, generating findings and GitHub issues for improvements.

[containerize-aspnet-framework]
    Source: awesome-copilot
    What it does: Packages an older ASP.NET (.NET Framework) application into a Docker container
    by writing a tailored Dockerfile.
    When to use: You have a legacy Windows web app and want to run it in containers.
    Search terms: docker, containerize, asp.net, .net framework, legacy app, dockerfile, windows
    containers, modernize
    Original description: Containerize an ASP.NET .NET Framework project by creating Dockerfile
    and .dockerfile files customized for the project.

[containerize-aspnetcore]
    Source: awesome-copilot
    What it does: Packages an ASP.NET Core application into a Docker container by writing a
    Dockerfile customized for the project.
    When to use: You want to run your .NET web app in Docker or deploy it to a container
    platform.
    Search terms: docker, containerize, asp.net core, dotnet, dockerfile, containers, deploy
    app, kubernetes
    Original description: Containerize an ASP.NET Core project by creating Dockerfile and
    .dockerfile files customized for the project.

[copilot-cli-quickstart]
    Source: awesome-copilot
    What it does: Teaches you how to use GitHub Copilot CLI through step-by-step tutorials, with
    separate tracks for developers and non-developers, plus on-demand Q&A.
    When to use: You are new to GitHub Copilot CLI and want a guided walkthrough.
    Search terms: github copilot, copilot cli, tutorial, getting started, learn copilot, ai
    coding assistant, command line, beginner guide
    Original description: Use this skill when someone wants to learn GitHub Copilot CLI from
    scratch. Offers interactive step-by-step tutorials with separate Developer and Non-Developer
    tracks, plus on-demand Q&A. Just say "start tutorial" or ask a question! Note: This skill
    targets GitHub Copilot CLI specifically and uses CLI-specific tools (ask_user, sql,
    fetch_copilot_cli_documentation).

[copilot-instructions-blueprint-generator]
    Source: awesome-copilot
    What it does: Writes a copilot-instructions.md file by studying your codebase so GitHub
    Copilot produces code that matches your team's standards and tools.
    When to use: You want GitHub Copilot to follow your project's conventions instead of
    guessing.
    Search terms: github copilot, copilot instructions, coding standards, ai coding rules,
    project setup, code consistency, developer guidelines
    Original description: Technology-agnostic blueprint generator for creating comprehensive
    copilot-instructions.md files that guide GitHub Copilot to produce code consistent with
    project standards, architecture patterns, and exact technology versions by analyzing
    existing codebase patterns and avoiding assumptions.

[copilot-pr-autopilot]
    Source: awesome-copilot
    What it does: Automates the back-and-forth of pull request reviews by triggering Copilot
    code review, sorting every comment, fixing what matters, and resolving threads.
    When to use: Your pull requests get buried in review comments and you want them handled
    automatically.
    Search terms: pull request, code review, github copilot, review comments, pr automation,
    github, merge faster, developer productivity
    Original description: Copilot left 14 review comments on your PR — half are nits. Hours of
    fix → reply → resolve → re-request, and each round lands MORE comments. This skill runs loop
    engineering: auto-triggers Copilot Code Review via GraphQL (no @copilot mention), triages
    every open thread (Copilot, humans, advanced-security) with a fix / decline / escalate
    rubric, dispatches parallel fix sub-agents that obey the repo build/test/lint conventions,
    commits per iteration, replies+resolves citing the pushed SHA, then re-triggers until HEAD
    is reviewed with zero threads awaiting the agent's reply (remaining open thread…

[copilot-sdk]
    Source: awesome-copilot
    What it does: Helps build apps with built-in AI agents using the GitHub Copilot SDK,
    including custom tools, streaming replies, and session handling.
    When to use: You want to embed a Copilot-powered assistant inside your own software.
    Search terms: copilot sdk, ai agent, embed ai, github copilot, build chatbot, ai app, custom
    tools, mcp
    Original description: Build agentic applications with GitHub Copilot SDK. Use when embedding
    AI agents in apps, creating custom tools, implementing streaming responses, managing
    sessions, connecting to MCP servers, or creating custom agents. Triggers on Copilot SDK,
    GitHub SDK, agentic app, embed Copilot, programmable agent, MCP server, custom agent.

[copilot-spaces]
    Source: awesome-copilot
    What it does: Connects conversations to GitHub Copilot Spaces so answers are grounded in
    your curated project documents, code, and instructions.
    When to use: You want Copilot to answer questions using your team's shared knowledge base.
    Search terms: copilot spaces, knowledge base, github copilot, project context, shared docs,
    grounded answers, team knowledge
    Original description: Use Copilot Spaces to provide project-specific context to
    conversations. Use this skill when users mention a "Copilot space", want to load context
    from a shared knowledge base, discover available spaces, or ask questions grounded in
    curated project documentation, code, and instructions.

[copilot-usage-metrics]
    Source: awesome-copilot
    What it does: Pulls GitHub Copilot usage statistics for your organization so you can see who
    is using it and how much.
    When to use: You want to measure adoption and value of your GitHub Copilot licenses.
    Search terms: copilot usage, github copilot, adoption metrics, license usage, reporting,
    developer analytics, seat usage, roi
    Original description: Retrieve and display GitHub Copilot usage metrics for organizations
    and enterprises using the GitHub CLI and REST API.

[create-canvas-extension]
    Source: awesome-copilot
    What it does: Scaffolds or registers a reusable canvas extension in the awesome-copilot
    repository, including its plugin manifest.
    When to use: You are contributing an extension to the awesome-copilot project.
    Search terms: canvas extension, awesome-copilot, plugin.json, github copilot, plugin
    development, scaffold, open source
    Original description: Create or register a canvas extension in the awesome-copilot
    repository. Use when asked to scaffold a new canvas extension, create its plugin.json, add a
    reusable extension to one or more plugins, or migrate extension metadata. Extensions are
    reusable source under extensions/; shippable plugin manifests belong under plugins/.

[csharp-async]
    Source: awesome-copilot
    What it does: Provides best practices for writing asynchronous C# code so apps stay
    responsive and avoid common deadlocks and bugs.
    When to use: Your developers are writing async/await code in C# and want to do it correctly.
    Search terms: c#, async, await, asynchronous code, dotnet, best practices, performance,
    threading
    Original description: Get best practices for C# async programming

[csharp-docs]
    Source: awesome-copilot
    What it does: Makes sure C# code is documented with clear XML comments that follow
    Microsoft's conventions.
    When to use: You want your C# codebase properly documented for other developers.
    Search terms: c#, code documentation, xml comments, dotnet, code comments, api docs,
    documentation standards
    Original description: Ensure that C# types are documented with XML comments and follow best
    practices for documentation.

[csharp-mstest]
    Source: awesome-copilot
    What it does: Provides best practices for writing automated unit tests in C# with the MSTest
    framework, including modern assertions and data-driven tests.
    When to use: Your team tests C# code with MSTest and wants to follow current conventions.
    Search terms: mstest, unit testing, c#, automated tests, dotnet, test best practices,
    quality assurance
    Original description: Get best practices for MSTest 3.x/4.x unit testing, including modern
    assertion APIs and data-driven tests

[csharp-nunit]
    Source: awesome-copilot
    What it does: Provides best practices for writing automated unit tests in C# with the NUnit
    framework, including data-driven tests.
    When to use: Your team tests C# code with NUnit and wants guidance on doing it well.
    Search terms: nunit, unit testing, c#, automated tests, dotnet, test best practices, quality
    assurance
    Original description: Get best practices for NUnit unit testing, including data-driven tests

[csharp-tunit]
    Source: awesome-copilot
    What it does: Provides best practices for writing automated unit tests in C# with the TUnit
    framework, including data-driven tests.
    When to use: Your team tests C# code with TUnit and wants guidance on doing it well.
    Search terms: tunit, unit testing, c#, automated tests, dotnet, test best practices, quality
    assurance
    Original description: Get best practices for TUnit unit testing, including data-driven tests

[csharp-xunit]
    Source: awesome-copilot
    What it does: Provides best practices for writing automated unit tests in C# with the xUnit
    framework, including data-driven tests.
    When to use: Your team tests C# code with xUnit and wants guidance on doing it well.
    Search terms: xunit, unit testing, c#, automated tests, dotnet, test best practices, quality
    assurance
    Original description: Get best practices for XUnit unit testing, including data-driven tests

[d365-solution-blueprint]
    Source: awesome-copilot
    What it does: Interviews you section by section to write a full solution blueprint for a
    Dynamics 365 Finance and Supply Chain project, covering scope, architecture, integrations,
    data migration, security, and testing.
    When to use: You are planning a Dynamics 365 ERP implementation and need a structured design
    document.
    Search terms: dynamics 365, erp, finance and operations, supply chain, solution design,
    implementation plan, microsoft dynamics, blueprint
    Original description: Authors a Dynamics 365 Finance and Supply Chain Management Solution
    Blueprint from scratch through a structured, section-by-section architect interview,
    establishing scope, target operating model, application and data architecture, integration
    landscape, migration strategy, security model, ALM, testing, deployment, and support
    approach, with a decision log capturing rationale and rejected alternatives. Use when the
    user wants to create D365 implementation architecture documentation, start a D365
    implementation, design the architecture, prepare a Solution Blueprint, or identify the
    architectura…

[dataverse-python-advanced-patterns]
    Source: awesome-copilot
    What it does: Writes production-grade Python code for Microsoft Dataverse using advanced
    patterns, solid error handling, and performance tuning.
    When to use: Your developers need robust Python integrations with Dataverse beyond the
    basics.
    Search terms: dataverse, python, power platform, dynamics data, sdk, error handling,
    integration code, microsoft
    Original description: Generate production code for Dataverse SDK using advanced patterns,
    error handling, and optimization techniques.

[dataverse-python-production-code]
    Source: awesome-copilot
    What it does: Generates reliable, production-ready Python code for working with Microsoft
    Dataverse, following best practices.
    When to use: You need Python code that reads or writes Dataverse data safely in a real
    system.
    Search terms: dataverse, python, power platform, production code, sdk, microsoft, database
    integration
    Original description: Generate production-ready Python code using Dataverse SDK with error
    handling, optimization, and best practices

[dataverse-python-quickstart]
    Source: awesome-copilot
    What it does: Produces starter Python snippets for Dataverse: setup, creating and reading
    records, bulk operations, and paging through results.
    When to use: You are just getting started connecting Python to Microsoft Dataverse.
    Search terms: dataverse, python, quickstart, getting started, crud, power platform, sdk,
    microsoft
    Original description: Generate Python SDK setup + CRUD + bulk + paging snippets using
    official patterns.

[dataverse-python-usecase-builder]
    Source: awesome-copilot
    What it does: Designs and builds a complete Python solution for a specific Dataverse
    scenario, with architecture recommendations included.
    When to use: You have a particular business need involving Dataverse data and want a full
    working approach.
    Search terms: dataverse, python, solution design, power platform, use case, architecture,
    microsoft, automation
    Original description: Generate complete solutions for specific Dataverse SDK use cases with
    architecture recommendations

[declarative-agents]
    Source: awesome-copilot
    What it does: Builds custom AI agents for Microsoft 365 Copilot, from simple to advanced,
    with validation and toolkit integration.
    When to use: You want a tailored Copilot assistant for your team inside Microsoft 365.
    Search terms: microsoft 365 copilot, custom copilot, declarative agent, ai assistant, teams,
    m365, agents toolkit, typespec
    Original description: Complete development kit for Microsoft 365 Copilot declarative agents
    with three comprehensive workflows (basic, advanced, validation), TypeSpec support, and
    Microsoft 365 Agents Toolkit integration

[dotnet-best-practices]
    Source: awesome-copilot
    What it does: Checks .NET and C# code against established best practices and suggests
    improvements.
    When to use: You want a quality review of a .NET project.
    Search terms: dotnet, c#, best practices, code review, code quality, .net, clean code
    Original description: Ensure .NET/C# code meets best practices for the solution/project.

[dotnet-design-pattern-review]
    Source: awesome-copilot
    What it does: Reviews C#/.NET code for how well it uses software design patterns and
    recommends improvements.
    When to use: You want to know whether your .NET code is structured in a maintainable way.
    Search terms: design patterns, dotnet, c#, code review, architecture, refactoring,
    maintainability
    Original description: Review the C#/.NET code for design pattern implementation and suggest
    improvements.

[dotnet-mcp-builder]
    Source: awesome-copilot
    What it does: Builds Model Context Protocol (MCP) servers in C#/.NET using the current 2.x
    packages, avoiding outdated defaults and deprecated features.
    When to use: You want to expose your .NET system's data or actions to AI assistants via MCP.
    Search terms: mcp server, model context protocol, dotnet, c#, ai integration, ai tools,
    connect ai to data
    Original description: Build Model Context Protocol (MCP) servers in C#/.NET against the
    current ModelContextProtocol 2.x NuGet packages. Helps with cases the model gets wrong
    without guidance — stale versions (0.x preview or 1.x-era defaults), the v2 stateless-by-
    default HTTP flip, the 2026-07-28 spec deprecations (roots/sampling/logging), MCP Apps and
    Tasks extension packages, elicitation URL mode, per-session HTTP wiring, OAuth and reverse-
    proxy deploy specifics, and debugging MapMcp / STDIO / Streamable-HTTP errors. Also covers
    STDIO and Streamable HTTP transports (SSE is deprecated), tools, prompts, resources, …

[dotnet-timezone]
    Source: awesome-copilot
    What it does: Guides correct time zone handling in .NET apps: UTC conversion, daylight
    saving, scheduling across regions, and finding the time zone for a place.
    When to use: Your app shows wrong times or schedules badly for users in different places.
    Search terms: time zones, dotnet, c#, daylight saving, utc, scheduling, date and time,
    nodatime
    Original description: .NET timezone handling guidance for C# applications. Use when working
    with TimeZoneInfo, DateTimeOffset, NodaTime, UTC conversion, daylight saving time,
    scheduling across timezones, cross-platform Windows/IANA timezone IDs, or when a .NET user
    needs the timezone for a city, address, region, or country and copy-paste-ready C# code.

[dotnet-upgrade]
    Source: awesome-copilot
    What it does: Analyzes and carries out upgrades of .NET applications to newer framework
    versions using ready-made prompts.
    When to use: Your software runs on an old .NET version and you want to modernize it.
    Search terms: dotnet upgrade, .net migration, framework upgrade, modernize app, legacy code,
    c#, net framework to net core
    Original description: Ready-to-use prompts for comprehensive .NET framework upgrade analysis
    and execution

[ef-core]
    Source: awesome-copilot
    What it does: Provides best practices for Entity Framework Core, the .NET tool for reading
    and writing databases from code.
    When to use: Your developers use EF Core and want to avoid slow queries and data bugs.
    Search terms: entity framework, ef core, database, dotnet, orm, sql, c#, data access
    Original description: Get best practices for Entity Framework Core

[entra-agent-user]
    Source: awesome-copilot
    What it does: Creates user accounts for AI agents in Microsoft Entra ID so they can act as
    digital workers with their own identity in Microsoft 365 and Azure.
    When to use: You want an AI agent to log in and work like a staff member in your Microsoft
    environment.
    Search terms: entra id, azure ad, ai agent identity, digital worker, microsoft 365, user
    accounts, identity management, agent user
    Original description: Create Agent Users in Microsoft Entra ID from Agent Identities,
    enabling AI agents to act as digital workers with user identity capabilities in Microsoft
    365 and Azure environments.

[fabric-lakehouse]
    Source: awesome-copilot
    What it does: Explains and helps build with Microsoft Fabric Lakehouse, including how data
    is organized, shared, and secured, with code examples.
    When to use: You are setting up a central data store in Microsoft Fabric.
    Search terms: microsoft fabric, lakehouse, data warehouse, data lake, analytics, big data,
    data platform, onelake
    Original description: Use this skill to get context about Fabric Lakehouse and its features
    for software systems and AI-powered functions. It offers descriptions of Lakehouse data
    components, organization with schemas and shortcuts, access control, and code examples. This
    skill supports users in designing, building, and optimizing Lakehouse solutions using best
    practices.

[flowstudio-power-automate-build]
    Source: awesome-copilot
    What it does: Builds, deploys, and tests Power Automate workflows through the FlowStudio
    connection without opening the Power Automate portal.
    When to use: You want a new automated workflow in Power Automate created for you.
    Search terms: power automate, workflow automation, flowstudio, build a flow, microsoft
    automation, no-code automation, business process
    Original description: Build, scaffold, and deploy Power Automate cloud flows using the
    FlowStudio MCP server. Your agent constructs flow definitions, wires connections, deploys,
    and tests — all via MCP without opening the portal. Load this skill when asked to: create a
    flow, build a new flow, deploy a flow definition, scaffold a Power Automate workflow,
    construct a flow JSON, update an existing flow's actions, patch a flow definition, add
    actions to a flow, wire up connections, or generate a workflow definition from scratch.
    Requires a FlowStudio MCP subscription — see https://mcp.flowstudio.app

[flowstudio-power-automate-debug]
    Source: awesome-copilot
    What it does: Investigates failed Power Automate flows by examining each step's inputs and
    outputs to find the real cause.
    When to use: A Power Automate flow keeps failing and you need to know why.
    Search terms: power automate, flow failed, debug flow, workflow error, flowstudio,
    troubleshooting, automation broken
    Original description: Debug failing Power Automate cloud flows using the FlowStudio MCP
    server. The Graph API only shows top-level status codes. This skill gives your agent action-
    level inputs and outputs to find the actual root cause. Load this skill when asked to: debug
    a flow, investigate a failed run, why is this flow failing, inspect action outputs, find the
    root cause of a flow error, fix a broken Power Automate flow, diagnose a timeout, trace a
    DynamicOperationRequestFailure, check connector auth errors, read error details from a run,
    or troubleshoot expression failures. Requires a FlowStudio MCP subscriptio…

[flowstudio-power-automate-governance]
    Source: awesome-copilot
    What it does: Audits Power Automate flows and Power Apps across your organization: rates
    business impact, finds abandoned items, checks connector use, and scores compliance.
    When to use: You want control over the sprawl of automations and apps your staff have built.
    Search terms: power automate, power apps, governance, compliance, audit, orphaned flows,
    flowstudio, it oversight
    Original description: Govern Power Automate flows and Power Apps at scale using the
    FlowStudio MCP cached store. Classify flows by business impact, detect orphaned resources,
    audit connector usage, enforce compliance standards, manage notification rules, and compute
    governance scores — all without Dataverse or the CoE Starter Kit. Load this skill when asked
    to: tag or classify flows, set business impact, assign ownership, detect orphans, audit
    connectors, check compliance, compute archive scores, manage notification rules, run a
    governance review, generate a compliance report, offboard a maker, or any task that inv…

[flowstudio-power-automate-mcp]
    Source: awesome-copilot
    What it does: Sets up the connection between an AI agent and Power Automate through
    FlowStudio, including login and tool discovery.
    When to use: You are connecting an AI assistant to Power Automate for the first time.
    Search terms: power automate, flowstudio, mcp, setup, connect ai, authentication, automation
    Original description: Foundation skill for Power Automate via FlowStudio MCP — auth setup,
    the reusable MCP helper (Python + Node.js), tool discovery via `list_skills` /
    `tool_search`, and oversized-response handling. Load this skill first when connecting an
    agent to Power Automate. For specialized workflows, load `flowstudio-power-automate-build`,
    `flowstudio-power-automate-debug`, `flowstudio-power-automate-monitoring` (Pro+), or
    `flowstudio-power-automate-governance` (Pro+) — each contains the workflow narrative, this
    skill provides the plumbing they all rely on. Requires a FlowStudio MCP subscription or
    compati…

[flowstudio-power-automate-monitoring]
    Source: awesome-copilot
    What it does: Monitors Power Automate health across your whole organization: failure rates,
    trends, who owns what, and compliance reports (requires a FlowStudio Pro+ subscription).
    When to use: You want a company-wide view of how reliable your automations are.
    Search terms: power automate, monitoring, failure rates, dashboard, flowstudio, health
    report, automation reliability
    Original description: Pro+ subscription required. Tenant-wide Power Automate monitoring
    using the FlowStudio MCP cached store: failure rates, run-health trends, maker/app
    inventory, inactive owners, and compliance/health reports. Use only for aggregated tenant
    views. For one environment, one flow, run control, or root-cause debugging, use flowstudio-
    power-automate-mcp, flowstudio-power-automate-debug, or the server monitor-flow bundle.
    Requires FlowStudio for Teams or MCP Pro+.

[fluentui-blazor]
    Source: awesome-copilot
    What it does: Guides building Blazor web apps with Microsoft's Fluent UI component library
    for a consistent, modern look.
    When to use: Your developers are building a Blazor app and want Microsoft-style UI
    components.
    Search terms: blazor, fluent ui, ui components, web app design, dotnet, microsoft design,
    frontend
    Original description: Guide for using the Microsoft Fluent UI Blazor component library
    (Microsoft.FluentUI.AspNetCore.Components NuGet package) in Blazor applications. Use this
    when the user is building a Blazor app with Fluent UI components, setting up the library,
    using FluentUI components like FluentButton, FluentDataGrid, FluentDialog, FluentToast,
    FluentNavMenu, FluentTextField, FluentSelect, FluentAutocomplete, FluentDesignTheme, or any
    component prefixed with "Fluent". Also use when troubleshooting missing providers, JS
    interop issues, or theming.

[foundry-agent-sync]
    Source: awesome-copilot
    What it does: Creates and updates AI agents directly inside Azure AI Foundry from a local
    configuration file so they are immediately ready to use.
    When to use: You want to manage your Azure AI Foundry agents as files and keep them in sync.
    Search terms: azure ai foundry, ai agents, deploy agent, agent configuration, azure ai, sync
    agents, prompt agents
    Original description: Create and synchronize prompt-based AI agents directly within Azure AI
    Foundry via REST API, from a local JSON manifest. Unlike scaffolding skills that only
    generate local code, this skill registers agents in the Foundry service itself — making them
    immediately available for invocation. Use when the user asks to create agents in Foundry,
    sync, deploy, register, or push agents to Foundry, update agent instructions, or scaffold
    the manifest and sync script for a new repository. Triggers: 'create agent in foundry',
    'sync foundry agents', 'deploy agents to foundry', 'register agents in foundry', '…

[foundry-hosted-agent-copilotkit]
    Source: awesome-copilot
    What it does: Guides development of AI-powered web apps that pair a CopilotKit front end
    with agents hosted on Azure AI Foundry, including approvals, generated UI, and debugging.
    When to use: You are building a web app with a built-in AI agent on Azure and CopilotKit.
    Search terms: copilotkit, azure ai foundry, agent framework, ai web app, ag-ui, human in the
    loop, chat interface
    Original description: Ongoing development guidance for agentic web apps that pair a
    CopilotKit frontend with Microsoft Agent Framework agents on Azure AI Foundry hosted agents
    over the AG-UI protocol - add and gate agent tools, wire human-in-the-loop approvals, build
    generative UI and shared state, debug the event stream, upgrade pre-1.0 packages safely, and
    deploy hosted agent updates.

[github-copilot-starter]
    Source: awesome-copilot
    What it does: Sets up a complete GitHub Copilot configuration for a new project based on the
    technologies you use.
    When to use: You are starting a project and want Copilot tuned to your stack from day one.
    Search terms: github copilot, project setup, copilot configuration, new project, developer
    tools, ai coding, instructions
    Original description: Set up complete GitHub Copilot configuration for a new project based
    on technology stack

[mcp-copilot-studio-server-generator]
    Source: awesome-copilot
    What it does: Generates an MCP server built to plug into Microsoft Copilot Studio, with the
    right schema rules and connection support.
    When to use: You want Copilot Studio agents to call your own systems or data.
    Search terms: copilot studio, mcp server, custom connector, ai agent tools, microsoft
    copilot, integration, power platform
    Original description: Generate a complete MCP server implementation optimized for Copilot
    Studio integration with proper schema constraints and streamable HTTP support

[microsoft-agent-framework]
    Source: awesome-copilot
    What it does: Creates, reviews, and explains AI agent solutions built on the Microsoft Agent
    Framework in .NET or Python.
    When to use: You are building AI agents with Microsoft's framework and need expert guidance.
    Search terms: microsoft agent framework, ai agents, dotnet, python, build ai agent, multi-
    agent, azure ai
    Original description: Create, update, refactor, explain, or review Microsoft Agent Framework
    solutions using shared guidance plus language-specific references for .NET and Python.

[microsoft-code-reference]
    Source: awesome-copilot
    What it does: Looks up official Microsoft API references and working code samples to confirm
    that Azure and .NET code is correct and not made up.
    When to use: You want to double-check that code using Microsoft libraries actually works.
    Search terms: microsoft docs, api reference, azure sdk, dotnet, code samples, verify code,
    documentation lookup
    Original description: Look up Microsoft API references, find working code samples, and
    verify SDK code is correct. Use when working with Azure SDKs, .NET libraries, or Microsoft
    APIs—to find the right method, check parameters, get working examples, or troubleshoot
    errors. Catches hallucinated methods, wrong signatures, and deprecated patterns by querying
    official docs.

[microsoft-docs]
    Source: awesome-copilot
    What it does: Searches official Microsoft documentation for concepts, tutorials, and
    examples across Azure, .NET, VS Code, GitHub, and more.
    When to use: You have a question best answered by Microsoft's own documentation.
    Search terms: microsoft docs, microsoft learn, azure documentation, dotnet docs, how to,
    tutorials, documentation search
    Original description: Query official Microsoft documentation to find concepts, tutorials,
    and code examples across Azure, .NET, Agent Framework, Aspire, VS Code, GitHub, and more.
    Uses Microsoft Learn MCP as the default, with Context7 and Aspire MCP for content that lives
    outside learn.microsoft.com.

[microsoft-skill-creator]
    Source: awesome-copilot
    What it does: Researches a Microsoft technology in depth and generates a reusable AI skill
    that teaches agents how to work with it.
    When to use: You want to package knowledge about a Microsoft product into a skill for your
    AI tools.
    Search terms: skill creator, microsoft, azure, build a skill, ai agent knowledge,
    documentation, microsoft learn
    Original description: Create agent skills for Microsoft technologies using Learn MCP tools.
    Use when users want to create a skill that teaches agents about any Microsoft technology,
    library, framework, or service (Azure, .NET, M365, VS Code, Bicep, etc.). Investigates
    topics deeply, then generates a hybrid skill storing essential knowledge locally while
    enabling dynamic deeper investigation.

[msgraph-sdk]
    Source: awesome-copilot
    What it does: Integrates Microsoft Graph into .NET, JavaScript, or Python apps to access
    Microsoft 365 data like mail, calendars, files, and users, with proper authentication and
    rate-limit handling.
    When to use: You want your app to read or write Microsoft 365 data such as Outlook, Teams,
    or OneDrive.
    Search terms: microsoft graph, microsoft 365 api, outlook integration, onedrive, teams,
    office 365, sdk, authentication
    Original description: Integrate Microsoft Graph SDK into any project — .NET,
    TypeScript/JavaScript, or Python. Covers auth patterns (client credentials, OBO, managed
    identity), SDK setup, calling Graph APIs, batching, delta queries, change notifications,
    throttling, and permission scopes. Use when accessing Microsoft 365 data (users, mail,
    calendar, Teams, files, SharePoint) from any application type.

[msstore-cli]
    Source: awesome-copilot
    What it does: Publishes and manages Windows apps in the Microsoft Store from the command
    line, including submissions, test flights, and automated publishing.
    When to use: You want to release or update a Windows app in the Microsoft Store.
    Search terms: microsoft store, publish windows app, app submission, msstore, partner center,
    windows app, release automation
    Original description: Microsoft Store Developer CLI (msstore) for publishing Windows
    applications to the Microsoft Store. Use when asked to configure Store credentials, list
    Store apps, check submission status, publish submissions, manage package flights, set up
    CI/CD for Store publishing, or integrate with Partner Center. Supports Windows App
    SDK/WinUI, UWP, .NET MAUI, Flutter, Electron, React Native, and PWA applications.

[mvvm-toolkit]
    Source: awesome-copilot
    What it does: Guides use of the .NET MVVM Toolkit for building desktop and mobile app
    interfaces with less boilerplate code.
    When to use: Your developers build Windows or cross-platform apps and want cleaner UI code.
    Search terms: mvvm, mvvm toolkit, dotnet, desktop app, xaml, wpf, maui, ui architecture
    Original description: CommunityToolkit.Mvvm (the MVVM Toolkit) core: source generators
    ([ObservableProperty], [RelayCommand], [NotifyPropertyChangedFor],
    [NotifyCanExecuteChangedFor], [NotifyDataErrorInfo]), base classes (ObservableObject /
    ObservableValidator / ObservableRecipient), commands (RelayCommand / AsyncRelayCommand), and
    validation. Companion skills: mvvm-toolkit-messenger for pub/sub, mvvm-toolkit-di for
    Microsoft.Extensions.DependencyInjection wiring. Works across WPF, WinUI 3, MAUI, Uno, and
    Avalonia.

[mvvm-toolkit-di]
    Source: awesome-copilot
    What it does: Shows how to wire MVVM Toolkit view models into .NET dependency injection,
    covering setup, lifetimes, and testing.
    When to use: Your .NET app uses MVVM and you want its parts connected in a testable way.
    Search terms: mvvm, dependency injection, dotnet, desktop app, app architecture, testing,
    generic host
    Original description: Wire CommunityToolkit.Mvvm ViewModels into
    Microsoft.Extensions.DependencyInjection. Covers the .NET Generic Host composition root,
    constructor injection, service lifetimes (Singleton / Transient / Scoped), IMessenger
    registration, resolving ViewModels in Views, keyed services, testing seams, and the legacy
    Ioc.Default escape hatch. Use across WPF, WinUI 3, .NET MAUI, Uno, and Avalonia.

[mvvm-toolkit-messenger]
    Source: awesome-copilot
    What it does: Explains the MVVM Toolkit Messenger for sending messages between parts of a
    .NET app without tight coupling.
    When to use: Different screens in your .NET app need to notify each other of changes.
    Search terms: mvvm, messenger, pub sub, dotnet, desktop app, events, decoupled code
    Original description: CommunityToolkit.Mvvm Messenger pub/sub for decoupled communication
    between ViewModels (or any objects). Covers WeakReferenceMessenger vs
    StrongReferenceMessenger, IRecipient<TMessage>, RequestMessage<T> / AsyncRequestMessage<T> /
    CollectionRequestMessage<T>, ValueChangedMessage<T>, channels (tokens), and the
    ObservableRecipient activation lifecycle. Use across WPF, WinUI 3, .NET MAUI, Uno, and
    Avalonia.

[nuget-manager]
    Source: awesome-copilot
    What it does: Adds, removes, and updates NuGet packages (third-party libraries) in .NET
    projects using the proper command-line tools.
    When to use: You need to update or add a library to a .NET project.
    Search terms: nuget, packages, dotnet, dependencies, update libraries, c#, package manager
    Original description: Manage NuGet packages in .NET projects/solutions. Use this skill when
    adding, removing, or updating NuGet package versions. It enforces using `dotnet` CLI for
    package management and provides strict procedures for direct file edits only when updating
    versions.

[pester-migration]
    Source: awesome-copilot
    What it does: Upgrades PowerShell test suites written in Pester from older versions to newer
    ones, handling the breaking changes along the way.
    When to use: Your PowerShell tests broke after a Pester upgrade or you want to move to a
    newer version.
    Search terms: pester, powershell, test migration, upgrade tests, powershell testing, version
    upgrade, scripts
    Original description: Pester migration skill for upgrading PowerShell Pester test suites
    across major versions — v3→v4, v4→v5, and v5→v6. Covers the Discovery/Run two-phase model,
    moving setup into BeforeAll, $PSScriptRoot vs $MyInvocation, mock changes (Assert-MockCalled
    → Should -Invoke, removed fall-through), Invoke-Pester parameters → PesterConfiguration,
    data-driven -ForEach/-TestCases, and the v6 breaking changes. Use when the user asks to
    upgrade, migrate, or modernize Pester tests, fix *.Tests.ps1 files that broke after bumping
    the Pester version, or convert legacy Should / Invoke-Pester syntax.

[pester-should-migration]
    Source: awesome-copilot
    What it does: Converts PowerShell Pester tests from the older 'Should -Be' assertion style
    to the new Pester 6 'Should-Be' syntax (preview).
    When to use: You are adopting Pester 6 and need your test assertions rewritten.
    Search terms: pester, powershell, pester 6, assertions, test migration, should-be,
    powershell testing
    Original description: Experimental (preview) Pester skill for migrating classic Should -Be
    (v5) assertion syntax to the new Should-* (v6) assertions (note the hyphen, no space), e.g.
    `Should -Be` -> `Should-Be`, `Should -Not -Be` -> `Should-NotBe`. Tracks Pester 6, which is
    still a release candidate, so this guidance may change; verified against Pester 6.0.0-rc2.
    Use when converting Pester v5 assertions to Pester v6 Should-* operators, modernizing a
    Pester test suite, or when a user asks to migrate, convert, or rewrite `Should -...` calls
    in .Tests.ps1 / PowerShell files.

[power-apps-code-app-scaffold]
    Source: awesome-copilot
    What it does: Sets up a complete Power Apps Code App project, including command-line
    tooling, SDK, and connector configuration.
    When to use: You want to start a custom-coded Power Apps project with everything in place.
    Search terms: power apps, code app, scaffold, pac cli, power platform, new project,
    connectors, low-code
    Original description: Scaffold a complete Power Apps Code App project with PAC CLI setup,
    SDK integration, and connector configuration

[power-bi-dax-optimization]
    Source: awesome-copilot
    What it does: Improves Power BI DAX formulas so reports run faster and the calculations are
    easier to read and maintain.
    When to use: Your Power BI report is slow or its formulas have become a tangle.
    Search terms: power bi, dax, slow report, formulas, report performance, measures,
    optimization, bi dashboard
    Original description: Comprehensive Power BI DAX formula optimization prompt for improving
    performance, readability, and maintainability of DAX calculations.

[power-bi-model-design-review]
    Source: awesome-copilot
    What it does: Reviews how a Power BI data model is structured, including tables and
    relationships, and points out improvements.
    When to use: You want an expert check of your Power BI model before building more reports on
    it.
    Search terms: power bi, data model, relationships, star schema, model review, bi, reporting,
    best practices
    Original description: Comprehensive Power BI data model design review prompt for evaluating
    model architecture, relationships, and optimization opportunities.

[power-bi-performance-troubleshooting]
    Source: awesome-copilot
    What it does: Diagnoses and fixes performance problems in Power BI models, reports, and
    queries step by step.
    When to use: Your Power BI dashboards take too long to load or refresh.
    Search terms: power bi, slow dashboard, performance, report loading, refresh time,
    troubleshooting, bi, queries
    Original description: Systematic Power BI performance troubleshooting prompt for
    identifying, diagnosing, and resolving performance issues in Power BI models, reports, and
    queries.

[power-bi-report-design-consultation]
    Source: awesome-copilot
    What it does: Advises on designing clear, user-friendly Power BI reports, including choosing
    the right charts, layout, and accessibility.
    When to use: You want your Power BI reports to be easier to read and more useful.
    Search terms: power bi, report design, dashboard design, charts, data visualization, layout,
    accessibility, bi
    Original description: Power BI report visualization design prompt for creating effective,
    user-friendly, and accessible reports with optimal chart selection and layout design.

[power-platform-architect]
    Source: awesome-copilot
    What it does: Turns business requirements, use cases, or meeting notes into a Power Platform
    solution design with recommended components and diagrams.
    When to use: You have a business need and want to know how to build it with Power Apps,
    Power Automate, and friends.
    Search terms: power platform, solution architecture, power apps, power automate,
    requirements, diagram, low-code, microsoft
    Original description: Use this skill when the user needs to transform business requirements,
    use case descriptions, or meeting transcripts into a technical Power Platform solution
    architecture, including component selection and Mermaid.js diagrams.

[power-platform-mcp-connector-suite]
    Source: awesome-copilot
    What it does: Generates a complete Power Platform custom connector with MCP support for
    Copilot Studio, including schemas, validation, and troubleshooting.
    When to use: You want Copilot Studio or Power Automate to talk to an outside system through
    a custom connector.
    Search terms: custom connector, power platform, copilot studio, mcp, integration, api
    connector, power automate
    Original description: Generate complete Power Platform custom connector with MCP integration
    for Copilot Studio - includes schema generation, troubleshooting, and validation

[powerbi-modeling]
    Source: awesome-copilot
    What it does: Helps build well-structured Power BI data models: writing measures, designing
    star schemas, setting relationships, row-level security, and tuning performance.
    When to use: You are building or improving the data model behind a Power BI report.
    Search terms: power bi, data modeling, dax, measures, star schema, row level security,
    relationships, semantic model
    Original description: Power BI semantic modeling assistant for building optimized data
    models. Use when working with Power BI semantic models, creating measures, designing star
    schemas, configuring relationships, implementing RLS, or optimizing model performance.
    Triggers on queries about DAX calculations, table relationships, dimension/fact table
    design, naming conventions, model documentation, cardinality, cross-filter direction,
    calculation groups, and data model best practices. Always connects to the active model first
    using power-bi-modeling MCP tools to understand the data structure before providing
    guidance.

[python-azure-iot-edge-modules]
    Source: awesome-copilot
    What it does: Builds and operates Python modules that run on Azure IoT Edge devices, with
    reliable messaging, deployment files, and monitoring.
    When to use: You need custom software running on edge devices connected to Azure IoT.
    Search terms: azure iot edge, python, iot, edge devices, connected devices, deployment,
    sensors, telemetry
    Original description: Build and operate Python Azure IoT Edge modules with robust messaging,
    deployment manifests, observability, and production readiness checks.

[semantic-kernel]
    Source: awesome-copilot
    What it does: Creates, reviews, and explains AI solutions built with Semantic Kernel,
    Microsoft's toolkit for adding AI to .NET and Python apps.
    When to use: You are building AI features with Semantic Kernel and need expert guidance.
    Search terms: semantic kernel, ai integration, dotnet, python, llm, microsoft ai, build ai
    app, plugins
    Original description: Create, update, refactor, explain, or review Semantic Kernel solutions
    using shared guidance plus language-specific references for .NET and Python.

[ssma-console]
    Source: awesome-copilot
    What it does: Runs SQL Server Migration Assistant tasks from the command line: assessing,
    converting, and migrating databases such as Oracle to SQL Server.
    When to use: You are moving a database from Oracle or another system to SQL Server.
    Search terms: database migration, oracle to sql server, ssma, sql server, schema conversion,
    data migration, microsoft sql
    Original description: Use when: SSMA console operations — create project, generate
    assessment report, convert schema, migrate data, Oracle to SQL Server migration, schema
    conversion, data migration

[suggest-awesome-github-copilot-agents]
    Source: awesome-copilot
    What it does: Recommends ready-made GitHub Copilot custom agents from the awesome-copilot
    collection that fit your project, skipping ones you already have.
    When to use: You want to find useful Copilot agents for your repository without browsing the
    whole catalog.
    Search terms: github copilot, custom agents, awesome-copilot, recommendations, copilot
    setup, developer tools
    Original description: Suggest relevant GitHub Copilot Custom Agents files from the awesome-
    copilot repository based on current repository context and chat history, avoiding duplicates
    with existing custom agents in this repository, and identifying outdated agents that need
    updates.

[suggest-awesome-github-copilot-instructions]
    Source: awesome-copilot
    What it does: Recommends GitHub Copilot instruction files from the awesome-copilot
    collection that match your project and flags outdated ones.
    When to use: You want Copilot to follow proven coding guidelines for your tech stack.
    Search terms: github copilot, copilot instructions, awesome-copilot, coding guidelines,
    recommendations, developer tools
    Original description: Suggest relevant GitHub Copilot instruction files from the awesome-
    copilot repository based on current repository context and chat history, avoiding duplicates
    with existing instructions in this repository, and identifying outdated instructions that
    need updates.

[suggest-awesome-github-copilot-skills]
    Source: awesome-copilot
    What it does: Recommends GitHub Copilot skills from the awesome-copilot collection that suit
    your repository and identifies ones needing updates.
    When to use: You want to discover helpful Copilot skills for your project.
    Search terms: github copilot, copilot skills, awesome-copilot, recommendations, developer
    tools, skill discovery
    Original description: Suggest relevant GitHub Copilot skills from the awesome-copilot
    repository based on current repository context and chat history, avoiding duplicates with
    existing skills in this repository, and identifying outdated skills that need updates.

[system-commandline-cli]
    Source: awesome-copilot
    What it does: Guides building command-line tools in .NET with System.CommandLine: commands,
    options, arguments, and handlers.
    When to use: Your developers are building a .NET command-line program.
    Search terms: command line tool, cli, dotnet, system.commandline, c#, console app, developer
    tools
    Original description: Use this skill when adding, modifying, or reviewing CLI commands in a
    .NET project built with System.CommandLine. Triggers include: creating a new CLI command,
    adding options or arguments, wiring command handlers, registering subcommands, building
    command groups, or any architecture decision about CLI command structure. Also use when the
    user mentions 'System.CommandLine', 'CommandBase', 'SetAction', 'ParseResult',
    'RootCommand', 'subcommand', or asks to add a verb to the CLI. Do NOT use for general C#
    coding, web APIs, UI work, or non-CLI projects.

[terraform-azurerm-set-diff-analyzer]
    Source: awesome-copilot
    What it does: Reads Terraform plan output for Azure and separates harmless ordering changes
    from real infrastructure changes.
    When to use: Your Terraform plans for Azure show changes that may not actually be changes.
    Search terms: terraform, azure, terraform plan, false positive, infrastructure as code,
    azurerm, diff, devops
    Original description: Analyze Terraform plan JSON output for AzureRM Provider to distinguish
    between false-positive diffs (order-only changes in Set-type attributes) and actual resource
    changes. Use when reviewing terraform plan output for Azure resources like Application
    Gateway, Load Balancer, Firewall, Front Door, NSG, and other resources with Set-type
    attributes that cause spurious diffs due to internal ordering changes.

[typespec-api-operations]
    Source: awesome-copilot
    What it does: Adds read, create, update, and delete operations to a TypeSpec API plugin for
    Microsoft 365 Copilot, with routing and adaptive cards.
    When to use: You are extending a Copilot plugin so it can do more with your API.
    Search terms: typespec, api plugin, microsoft 365 copilot, adaptive cards, rest api, copilot
    extension, m365
    Original description: Add GET, POST, PATCH, and DELETE operations to a TypeSpec API plugin
    with proper routing, parameters, and adaptive cards

[typespec-create-agent]
    Source: awesome-copilot
    What it does: Generates a complete Microsoft 365 Copilot agent in TypeSpec with
    instructions, capabilities, and conversation starters.
    When to use: You want a custom Copilot agent for Microsoft 365 defined in code.
    Search terms: typespec, microsoft 365 copilot, custom agent, declarative agent, ai
    assistant, m365, copilot
    Original description: Generate a complete TypeSpec declarative agent with instructions,
    capabilities, and conversation starters for Microsoft 365 Copilot

[typespec-create-api-plugin]
    Source: awesome-copilot
    What it does: Generates a TypeSpec API plugin for Microsoft 365 Copilot, including API
    operations, authentication, and adaptive cards.
    When to use: You want Copilot to connect to your business API inside Microsoft 365.
    Search terms: typespec, api plugin, microsoft 365 copilot, authentication, adaptive cards,
    copilot extension, m365
    Original description: Generate a TypeSpec API plugin with REST operations, authentication,
    and Adaptive Cards for Microsoft 365 Copilot

[update-avm-modules-in-bicep]
    Source: awesome-copilot
    What it does: Updates Azure Verified Modules referenced in Bicep infrastructure files to
    their latest versions.
    When to use: Your Azure infrastructure code uses AVM modules that have fallen behind.
    Search terms: bicep, azure verified modules, avm, update modules, infrastructure as code,
    azure, version update
    Original description: Update Azure Verified Modules (AVM) to latest versions in Bicep files.

[vscode-ext-commands]
    Source: awesome-copilot
    What it does: Provides guidelines for adding commands to Visual Studio Code extensions,
    covering naming, visibility, and localization.
    When to use: You are building a VS Code extension and adding commands to it.
    Search terms: vs code extension, vscode, extension commands, extension development, command
    palette, developer tools
    Original description: Guidelines for contributing commands in VS Code extensions. Indicates
    naming convention, visibility, localization and other relevant attributes, following VS Code
    extension development guidelines, libraries and good practices

[vscode-ext-localization]
    Source: awesome-copilot
    What it does: Provides guidelines for translating Visual Studio Code extensions into
    multiple languages the proper way.
    When to use: You want your VS Code extension to support users in other languages.
    Search terms: vs code extension, localization, translation, multiple languages, i18n,
    extension development, vscode
    Original description: Guidelines for proper localization of VS Code extensions, following VS
    Code extension development guidelines, libraries and good practices

[winmd-api-search]
    Source: awesome-copilot
    What it does: Finds the right Windows desktop API for a feature such as camera, files,
    notifications, or sensors, and retrieves its full details.
    When to use: You are building a Windows app and need to know which system API to use.
    Search terms: windows api, windows app, winrt, desktop development, camera, notifications,
    api lookup, windows sdk
    Original description: Find and explore Windows desktop APIs. Use when building features that
    need platform capabilities — camera, file access, notifications, UI controls, AI/ML,
    sensors, networking, etc. Discovers the right API for a task and retrieves full type details
    (methods, properties, events, enumeration values).

[winui3-migration-guide]
    Source: awesome-copilot
    What it does: Maps old UWP app code to its modern WinUI 3 / Windows App SDK equivalents with
    before-and-after examples.
    When to use: You are moving a UWP Windows app to WinUI 3.
    Search terms: winui 3, uwp migration, windows app sdk, windows app, modernize, migration
    guide, desktop app
    Original description: UWP-to-WinUI 3 migration reference. Maps legacy UWP APIs to correct
    Windows App SDK equivalents with before/after code snippets. Covers namespace changes,
    threading (CoreDispatcher to DispatcherQueue), windowing (CoreWindow to AppWindow), dialogs,
    pickers, sharing, printing, background tasks, and the most common Copilot code generation
    mistakes.

[workiq-copilot]
    Source: awesome-copilot
    What it does: Queries your Microsoft 365 data (emails, meetings, documents, Teams, people)
    through WorkIQ to give summaries and recommendations with live context.
    When to use: You want an AI assistant that knows what is in your Outlook, Teams, and files
    right now.
    Search terms: workiq, microsoft 365, email summary, meetings, teams, outlook, copilot data,
    work context
    Original description: Guides the Copilot CLI on how to use the WorkIQ CLI/MCP server to
    query Microsoft 365 Copilot data (emails, meetings, docs, Teams, people) for live context,
    summaries, and recommendations.
