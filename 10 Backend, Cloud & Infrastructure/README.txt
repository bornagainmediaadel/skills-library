10 BACKEND, CLOUD & INFRASTRUCTURE
==================================

Skills for servers, APIs and cloud: Cloudflare Workers, Vercel, AWS, Kubernetes, Docker, CI/CD
pipelines, observability, microservices and backend patterns in Node, Python, Go and Java.

96 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - api-design-principles
  - api-designer
  - arch-linux-triage
  - aws-cdk-python-setup
  - aws-cloudwatch-investigation
  - aws-cost-optimize
  - aws-resource-health-diagnose
  - aws-resource-query
  - aws-well-architected-review
  - bazel-build-optimization
  - centos-linux-triage
  - ci-cd-and-automation
  - cloud-design-patterns
  - cloudflare
  - cloudflare-email-service
  - cloudflare-one
  - cloudflare-one-migrations
  - content-management-systems
  - cost-optimization
  - cqrs-implementation
  - create-spring-boot-java-project
  - create-spring-boot-kotlin-project
  - debian-linux-triage
  - defi-protocol-templates
  - deploy-to-vercel
  - deployment-engineer
  - deployment-pipeline-design
  - devops-rollout-plan
  - distributed-tracing
  - dotnet-backend-patterns
  - durable-objects
  - event-store-design
  - fastapi-templates
  - fedora-linux-triage
  - geofeed-tuner
  - github-actions-efficiency
  - github-actions-runtime-upgrade-conventions
  - github-actions-templates
  - github-codespaces-efficiency
  - gitlab-ci-patterns
  - gitops-workflow
  - helm-chart-scaffolding
  - hybrid-cloud-networking
  - import-infrastructure-as-code
  - incident-postmortem
  - incident-runbook-templates
  - integrate-context-matic
  - istio-traffic-management
  - java-add-graalvm-native-image-support
  - java-helidon
  - java-springboot
  - javax-to-jakarta-migration
  - k8s-manifest-generator
  - kotlin-springboot
  - linkerd-patterns
  - microservices-patterns
  - monorepo-management
  - multi-cloud-architecture
  - multi-stage-dockerfile
  - nft-standards
  - nodejs-backend-patterns
  - nx-workspace-patterns
  - observability-and-instrumentation
  - on-call-handoff-patterns
  - openapi-spec-generation
  - openapi-to-application-code
  - optimize-simplicite-logs
  - projection-patterns
  - publish-to-pages
  - python-background-jobs
  - python-observability
  - saga-orchestration
  - salesforce-apex-quality
  - salesforce-component-standards
  - salesforce-flow-design
  - sandbox-migrate-to-next
  - sandbox-next
  - sandbox-npm-install
  - sandbox-stable
  - service-mesh-observability
  - slo-implementation
  - spring-boot-testing
  - temporal-python-testing
  - terraform-module-library
  - transloadit-media-processing
  - turborepo-caching
  - turnstile-spin
  - vercel-cli-with-tokens
  - vercel-composition-patterns
  - vercel-optimize
  - vercel-react-best-practices
  - vercel-react-native-skills
  - vercel-react-view-transitions
  - web3-testing
  - workers-best-practices
  - wrangler

SKILL DETAILS
-------------

[api-design-principles]
    Source: agents (bundle)
    What it does: Applies best practices for designing REST and GraphQL APIs so they are
    intuitive, scalable, and easy for developers to use.
    When to use: You are building a new API or setting standards for how your team designs them.
    Search terms: api design, rest api, graphql, api best practices, api standards, developer
    experience, api review, backend, web services
    Original description: Master REST and GraphQL API design principles to build intuitive,
    scalable, and maintainable APIs that delight developers. Use when designing new APIs,
    reviewing API specifications, or establishing API design standards.

[api-designer]
    Source: agent-playbook
    What it does: Acts as an API architect that designs robust, scalable REST and GraphQL APIs
    or improves existing ones.
    When to use: You need someone to design how your software will talk to other systems.
    Search terms: api design, rest api, graphql, api architect, backend, improve api,
    integration, web services, scalable api
    Original description: REST and GraphQL API architect for designing robust, scalable APIs.
    Use when designing new APIs or improving existing ones.

[arch-linux-triage]
    Source: awesome-copilot
    What it does: Diagnoses and fixes problems on computers or servers running Arch Linux, such
    as broken updates, failed services, or package conflicts.
    When to use: Your Arch Linux server or machine is misbehaving after an update and you need
    it working again.
    Search terms: arch linux, linux problems, pacman, server not working, fix linux, systemd,
    broken update, linux troubleshooting
    Original description: Triage and resolve Arch Linux issues with pacman, systemd, and
    rolling-release best practices.

[aws-cdk-python-setup]
    Source: awesome-copilot
    What it does: Sets up a new project for building Amazon Web Services (AWS) infrastructure
    with Python code, installing the right tools and getting the first deployment working.
    When to use: You want to start defining your AWS cloud setup in Python instead of clicking
    through the AWS console.
    Search terms: aws, aws cdk, python, cloud setup, amazon web services, infrastructure as
    code, new cloud project, deploy to aws
    Original description: Setup and initialization guide for developing AWS CDK (Cloud
    Development Kit) applications in Python. This skill enables users to configure environment
    prerequisites, create new CDK projects, manage dependencies, and deploy to AWS.

[aws-cloudwatch-investigation]
    Source: awesome-copilot
    What it does: Investigates outages and slowdowns on AWS by searching CloudWatch logs and
    metrics, linking alarms to recent deployments, and narrowing down what broke.
    When to use: Something on your AWS-hosted system went wrong and you need to find the cause
    from the logs.
    Search terms: aws, cloudwatch, logs, outage, incident, site down, error logs, alarms,
    troubleshooting aws
    Original description: Reusable investigation patterns for AWS CloudWatch: Logs Insights
    query templates, alarm-to-deployment correlation, blast-radius narrowing decision tree, and
    PromQL-style metric query patterns for structured incident triage.

[aws-cost-optimize]
    Source: awesome-copilot
    What it does: Reviews the AWS resources your application uses and finds ways to lower the
    bill, logging each saving opportunity as a task for your team.
    When to use: Your AWS bill keeps growing and you want concrete ways to cut it.
    Search terms: aws costs, cloud bill, reduce aws spend, save money on aws, cloud costs, aws,
    cost savings, hosting costs
    Original description: Analyze AWS resources used in the app (IaC files and/or resources in a
    target account/region) and optimize costs - creating GitHub issues for identified
    optimizations.

[aws-resource-health-diagnose]
    Source: awesome-copilot
    What it does: Checks the health of your AWS services, reads logs and metrics to find what is
    failing, and writes up a plan to fix it.
    When to use: Your AWS-hosted app is slow or erroring and you want to know what is wrong and
    how to fix it.
    Search terms: aws, server health, aws problems, cloudwatch, app is slow, diagnose aws, fix
    plan, cloud monitoring
    Original description: Analyze AWS resource health, diagnose issues from CloudWatch logs and
    metrics, and create a remediation plan for identified problems.

[aws-resource-query]
    Source: awesome-copilot
    What it does: Answers plain-English questions about what you have running in AWS, such as
    servers, storage, databases, and users, without changing anything.
    When to use: You want to know what is actually set up in your AWS account without digging
    through the console.
    Search terms: aws, what's running in aws, aws inventory, ec2, s3, cloud resources, list aws
    resources, read only
    Original description: Query AWS resources using natural language. Covers EC2, S3, RDS,
    Lambda, ECS, EKS, Secrets Manager, IAM, VPC, networking, messaging, and more. Strictly read-
    only — no writes, deletes, or mutations.

[aws-well-architected-review]
    Source: awesome-copilot
    What it does: Reviews your AWS setup against Amazon's own best-practice framework for
    security, reliability, cost, and performance, and lists improvements as tasks.
    When to use: You want an expert-style audit of whether your AWS setup is built the right
    way.
    Search terms: aws review, aws audit, well-architected, cloud best practices, aws security,
    reliability, cloud architecture, aws
    Original description: Perform an AWS Well-Architected Framework review of the current
    workload IaC and architecture, generating findings and GitHub issues for improvements.

[bazel-build-optimization]
    Source: agents (bundle)
    What it does: Speeds up software builds for large codebases that use the Bazel build tool,
    including remote build and caching setup.
    When to use: Your developers' Bazel builds are slow and you want them faster and cheaper.
    Search terms: bazel, slow builds, build speed, monorepo, build caching, developer
    productivity, remote execution, large codebase
    Original description: Optimize Bazel builds for large-scale monorepos. Use when configuring
    Bazel, implementing remote execution, or optimizing build performance for enterprise
    codebases.

[centos-linux-triage]
    Source: awesome-copilot
    What it does: Diagnoses and fixes problems on servers running CentOS Linux, including
    package, service, firewall, and security-policy issues.
    When to use: Your CentOS server is down or misbehaving and you need it fixed.
    Search terms: centos, linux server, server down, rhel, fix linux, firewall, selinux, linux
    troubleshooting
    Original description: Triage and resolve CentOS issues using RHEL-compatible tooling,
    SELinux-aware practices, and firewalld.

[ci-cd-and-automation]
    Source: agent-skills
    What it does: Sets up automated pipelines that test and release your software every time
    developers make changes, with quality checks built in.
    When to use: You want code changes to be tested and shipped automatically instead of by
    hand.
    Search terms: ci/cd, automated testing, deployment pipeline, release automation, build
    pipeline, devops, automate deployments, github actions
    Original description: Automates CI/CD pipeline setup. Use when setting up or modifying build
    and deployment pipelines. Use when you need to automate quality gates, configure test
    runners in CI, or establish deployment strategies.

[cloud-design-patterns]
    Source: awesome-copilot
    What it does: Advises on proven design approaches for building reliable, secure, and fast
    cloud systems, drawing on 42 standard patterns.
    When to use: You are designing or reviewing a cloud-based system and want it to follow
    proven architecture practices.
    Search terms: cloud architecture, system design, reliability, scalability, distributed
    systems, design patterns, microservices, cloud best practices
    Original description: Cloud design patterns for distributed systems architecture covering 42
    industry-standard patterns across reliability, performance, messaging, security, and
    deployment categories. Use when designing, reviewing, or implementing distributed system
    architectures.

[cloudflare]
    Source: cloudflare skills
    What it does: Helps build and configure anything on the Cloudflare platform, from hosting
    and storage to AI features, security, and networking.
    When to use: You use Cloudflare for your website or app and need to set up or change
    something on it.
    Search terms: cloudflare, cloudflare workers, website hosting, cdn, ddos protection, web
    security, serverless, cloudflare pages
    Original description: Comprehensive Cloudflare platform skill covering Workers, Pages,
    storage (KV, D1, R2), AI (Workers AI, Vectorize, Agents SDK), feature flags (Flagship),
    networking (Tunnel, Spectrum), security (WAF, DDoS), and infrastructure-as-code (Terraform,
    Pulumi). Use for any Cloudflare development task. Biases towards retrieval from Cloudflare
    docs over pre-trained knowledge.

[cloudflare-email-service]
    Source: cloudflare skills
    What it does: Sets up sending and receiving email from your app through Cloudflare,
    including the settings that keep your messages out of spam folders.
    When to use: You need your app to send emails (like receipts or alerts) through Cloudflare
    and arrive reliably.
    Search terms: cloudflare email, send email from app, transactional email, email
    deliverability, spf dkim dmarc, email routing, emails going to spam, email setup
    Original description: Send and receive transactional emails with Cloudflare Email Service
    (Email Sending + Email Routing). Use when building email sending (Workers binding or REST
    API), email routing, Agents SDK email handling, or integrating email into any app — Workers,
    Node.js, Python, Go, etc. Also use for email deliverability, SPF/DKIM/DMARC, wrangler email
    setup, MCP email tools, or when a coding agent needs to send emails. Even for simple
    requests like "add email to my Worker" — this skill has critical config details.

[cloudflare-one]
    Source: cloudflare skills
    What it does: Designs, configures, and troubleshoots Cloudflare One, a service that lets
    staff securely access company apps and the internet without a traditional VPN.
    When to use: You want to secure how employees reach company systems using Cloudflare's zero-
    trust tools.
    Search terms: cloudflare one, zero trust, vpn replacement, remote access, secure employee
    access, sase, cloudflare access, network security
    Original description: Guides Cloudflare One Zero Trust and SASE work across Access, Gateway,
    WARP, Tunnel, Cloudflare WAN, DLP, CASB, device posture, and identity. Use when designing,
    configuring, troubleshooting, or reviewing Cloudflare One deployments. Retrieval-first: use
    current Cloudflare docs/API schemas instead of embedded product docs.

[cloudflare-one-migrations]
    Source: cloudflare skills
    What it does: Plans a move from Zscaler, Palo Alto, or an old VPN to Cloudflare One, mapping
    existing policies and laying out a rollout plan.
    When to use: You are switching your company's network security from another vendor to
    Cloudflare.
    Search terms: migrate to cloudflare, zscaler, palo alto, replace vpn, zero trust migration,
    network security, rollout plan, cloudflare one
    Original description: Plans migrations from Zscaler ZIA/ZPA, Palo Alto, legacy VPN, SWG, or
    SASE stacks to Cloudflare One. Use for migration assessments, policy mapping, rollout plans,
    and parity/gap analysis.

[content-management-systems]
    Source: awesome-copilot
    What it does: Builds and modifies websites on platforms like WordPress, Shopify, Wix,
    Squarespace, Webflow, and Drupal, including themes, plugins, and content setup.
    When to use: You need changes made to your WordPress, Shopify, Wix, or similar website.
    Search terms: wordpress, shopify, wix, squarespace, webflow, website builder, cms, website
    plugins, website theme, drupal
    Original description: Workflow for building and modifying content management systems across
    WordPress, Shopify, Wix, Squarespace, Drupal, WooCommerce, Joomla, HubSpot CMS Hub, Webflow,
    Adobe Experience Manager, and similar platforms. Use when working on CMS themes, plugins,
    apps, modules, admin panels, media uploads, content models, editors, markdown pipelines, or
    static export workflows.

[cost-optimization]
    Source: agents (bundle)
    What it does: Finds ways to lower your cloud hosting bill on AWS, Azure, Google Cloud, or
    Oracle by right-sizing servers, using discounts, and tracking spend.
    When to use: Your cloud hosting costs are too high and you want a plan to bring them down.
    Search terms: cloud costs, reduce hosting bill, aws, azure, google cloud, save money on
    cloud, cloud spending, cost governance
    Original description: Optimize cloud costs across AWS, Azure, GCP, and OCI through resource
    rightsizing, tagging strategies, reserved instances, and spending analysis. Use when
    reducing cloud expenses, analyzing infrastructure costs, or implementing cost governance
    policies.

[cqrs-implementation]
    Source: agents (bundle)
    What it does: Structures software so that reading data and updating data are handled
    separately, which helps busy systems stay fast.
    When to use: Your app is slowing down under heavy traffic and developers are considering
    separating reads from writes.
    Search terms: cqrs, app performance, scalable architecture, event sourcing, database
    performance, software architecture, read and write separation, backend design
    Original description: Implement Command Query Responsibility Segregation for scalable
    architectures. Use when separating read and write models, optimizing query performance, or
    building event-sourced systems.

[create-spring-boot-java-project]
    Source: awesome-copilot
    What it does: Creates the starting skeleton for a new Java application built with Spring
    Boot, a popular framework for business apps.
    When to use: You are starting a new Java backend project and want it set up correctly from
    day one.
    Search terms: java, spring boot, new project, backend, java app, project template, starter
    project, web service
    Original description: Create Spring Boot Java Project Skeleton

[create-spring-boot-kotlin-project]
    Source: awesome-copilot
    What it does: Creates the starting skeleton for a new Kotlin application built with Spring
    Boot.
    When to use: You are starting a new Kotlin backend project and want a ready-made foundation.
    Search terms: kotlin, spring boot, new project, backend, project template, starter project,
    web service, jvm
    Original description: Create Spring Boot Kotlin Project Skeleton

[debian-linux-triage]
    Source: awesome-copilot
    What it does: Diagnoses and fixes problems on servers running Debian Linux, including
    package, service, and security-profile issues.
    When to use: Your Debian server is broken or behaving oddly and you need it sorted out.
    Search terms: debian, linux server, apt, server down, fix linux, systemd, apparmor, linux
    troubleshooting
    Original description: Triage and resolve Debian Linux issues with apt, systemd, and
    AppArmor-aware guidance.

[defi-protocol-templates]
    Source: agents (bundle)
    What it does: Builds decentralized finance (DeFi) applications on the blockchain using
    ready-made templates for staking, token exchanges, governance, and flash loans.
    When to use: You are launching a crypto or DeFi product and need smart contracts built from
    proven templates.
    Search terms: defi, crypto, blockchain, smart contracts, staking, token exchange, ethereum,
    web3
    Original description: Implement DeFi protocols with production-ready templates for staking,
    AMMs, governance, and flash loans. Use when building decentralized finance applications or
    smart contract protocols.

[deploy-to-vercel]
    Source: vercel agent-skills
    What it does: Publishes your website or web app live on Vercel and hands back the link,
    including preview versions for review.
    When to use: You want your site or app put online (or a preview link made) on Vercel.
    Search terms: vercel, deploy website, publish site, go live, preview link, hosting, launch
    app, next.js
    Original description: Deploy applications and websites to Vercel. Use when the user requests
    deployment actions like "deploy my app", "deploy and give me the link", "push this live", or
    "create a preview deployment".

[deployment-engineer]
    Source: agent-playbook
    What it does: Sets up how your software gets released, from automated build-and-test
    pipelines to managing the release process itself.
    When to use: You need someone to set up or improve how your software gets shipped to
    customers.
    Search terms: deployment, ci/cd, release management, devops, shipping software, automated
    releases, pipeline setup, infrastructure
    Original description: Deployment automation specialist for CI/CD pipelines and
    infrastructure. Use when setting up deployment, configuring CI/CD, or managing releases.

[deployment-pipeline-design]
    Source: agents (bundle)
    What it does: Designs multi-step release pipelines with approval checkpoints, security
    scans, and gradual rollouts so updates go out without downtime.
    When to use: You want software updates released safely in stages, with no outages for
    customers.
    Search terms: deployment pipeline, zero downtime, canary release, approval gates, release
    process, ci/cd, safe deployments, staging to production
    Original description: Design multi-stage CI/CD pipelines with approval gates, security
    checks, and deployment orchestration. Use this skill when designing zero-downtime deployment
    pipelines, implementing canary rollout strategies, setting up multi-environment promotion
    workflows, or debugging failed deployment gates in CI/CD.

[devops-rollout-plan]
    Source: awesome-copilot
    What it does: Writes a complete rollout plan for a system change, including pre-checks,
    step-by-step actions, how to confirm it worked, how to undo it, and who to notify.
    When to use: You are about to make a significant change to your systems and want a clear
    plan and a backup plan.
    Search terms: rollout plan, deployment plan, change management, rollback, release checklist,
    go-live plan, communication plan, infrastructure change
    Original description: Generate comprehensive rollout plans with preflight checks, step-by-
    step deployment, verification signals, rollback procedures, and communication plans for
    infrastructure and application changes

[distributed-tracing]
    Source: agents (bundle)
    What it does: Sets up tracing tools (Jaeger, Tempo) that follow a single customer request
    across all your services to show where time is being lost.
    When to use: Your app is slow and you cannot tell which part of the system is the
    bottleneck.
    Search terms: tracing, slow app, performance bottleneck, jaeger, microservices,
    observability, request tracking, debugging
    Original description: Implement distributed tracing with Jaeger and Tempo to track requests
    across microservices and identify performance bottlenecks. Use when debugging microservices,
    analyzing request flows, or implementing observability for distributed systems.

[dotnet-backend-patterns]
    Source: agents (bundle)
    What it does: Writes and reviews C# and .NET backend code using best practices for APIs,
    databases, configuration, caching, and testing.
    When to use: You are building or reviewing a Microsoft .NET backend and want it done the
    right way.
    Search terms: c#, .net, dotnet, backend, api development, entity framework, microsoft, code
    review
    Original description: Master C#/.NET backend development patterns for building robust APIs,
    MCP servers, and enterprise applications. Covers async/await, dependency injection, Entity
    Framework Core, Dapper, configuration, caching, and testing with xUnit. Use when developing
    .NET backends, reviewing C# code, or designing API architectures.

[durable-objects]
    Source: cloudflare skills
    What it does: Builds real-time, stateful features like chat rooms, multiplayer games, and
    booking systems on Cloudflare using Durable Objects.
    When to use: You need a live, shared feature such as chat or bookings running on Cloudflare.
    Search terms: cloudflare, durable objects, chat app, real-time, multiplayer, booking system,
    websockets, serverless
    Original description: Create and review Cloudflare Durable Objects. Use when building
    stateful coordination (chat rooms, multiplayer games, booking systems), implementing RPC
    methods, SQLite storage, alarms, WebSockets, or reviewing DO code for best practices. Covers
    Workers integration, wrangler config, and testing with Vitest. Biases towards retrieval from
    Cloudflare docs over pre-trained knowledge.

[event-store-design]
    Source: agents (bundle)
    What it does: Designs the storage layer for systems that keep a full history of every change
    as a series of events.
    When to use: Your developers are building an event-sourced system and need to pick and set
    up the right event storage.
    Search terms: event sourcing, event store, audit history, database design, software
    architecture, change history, backend, data storage
    Original description: Design and implement event stores for event-sourced systems. Use when
    building event sourcing infrastructure, choosing event store technologies, or implementing
    event persistence patterns.

[fastapi-templates]
    Source: agents (bundle)
    What it does: Creates a production-ready Python web API project using FastAPI, with error
    handling and structure already in place.
    When to use: You are starting a new Python API and want a solid, ready-to-build-on
    foundation.
    Search terms: fastapi, python, api, new project, backend, web service, project template,
    rest api
    Original description: Create production-ready FastAPI projects with async patterns,
    dependency injection, and comprehensive error handling. Use when building new FastAPI
    applications or setting up backend API projects.

[fedora-linux-triage]
    Source: awesome-copilot
    What it does: Diagnoses and fixes problems on computers or servers running Fedora Linux.
    When to use: Your Fedora machine is broken or acting up and you need it fixed.
    Search terms: fedora, linux, dnf, server down, fix linux, selinux, systemd, linux
    troubleshooting
    Original description: Triage and resolve Fedora issues with dnf, systemd, and SELinux-aware
    guidance.

[geofeed-tuner]
    Source: awesome-copilot
    What it does: Creates and checks IP geolocation feeds, the files that tell the internet
    which country and city your IP addresses belong to, for ISPs and network operators.
    When to use: Your customers' IP addresses show up in the wrong location and you want to
    publish a correct geofeed.
    Search terms: geofeed, ip geolocation, wrong location, isp, rfc 8805, network operator, ip
    addresses, geolocation accuracy
    Original description: Use this skill whenever the user mentions IP geolocation feeds, RFC
    8805, geofeeds, or wants help creating, tuning, validating, or publishing a self-published
    IP geolocation feed in CSV format. Intended user audience is a network operator, ISP, mobile
    carrier, cloud provider, hosting company, IXP, or satellite provider asking about IP
    geolocation accuracy, or geofeed authoring best practices. Helps create, refine, and improve
    CSV-format IP geolocation feeds with opinionated recommendations beyond RFC 8805 compliance.
    Do NOT use for private or internal IP address management — applies only to pu…

[github-actions-efficiency]
    Source: awesome-copilot
    What it does: Audits your GitHub Actions automation and recommends changes to cut wasted
    build minutes and lower the bill.
    When to use: Your GitHub Actions bill or build times are higher than they should be.
    Search terms: github actions, ci costs, build minutes, slow builds, github bill, ci/cd,
    reduce ci spend, workflow optimization
    Original description: Audit GitHub Actions workflow efficiency and recommend fixes to reduce
    CI minutes and costs.

[github-actions-runtime-upgrade-conventions]
    Source: awesome-copilot
    What it does: Upgrades outdated GitHub Actions workflows to supported versions without
    changing how they behave, then checks that they still run.
    When to use: GitHub is warning that your automation uses outdated actions or runtimes.
    Search terms: github actions, upgrade, deprecated, node version, workflow update, ci/cd,
    maintenance, github warnings
    Original description: Upgrade GitHub Actions to supported runtimes by selecting safe action
    versions, preserving workflow behavior, and validating post-upgrade execution.

[github-actions-templates]
    Source: agents (bundle)
    What it does: Creates ready-to-use GitHub Actions workflows that automatically test, build,
    and deploy your software.
    When to use: You want automated testing and releases set up on GitHub.
    Search terms: github actions, ci/cd, automated testing, deploy automatically, workflow
    templates, github, build pipeline, devops
    Original description: Create production-ready GitHub Actions workflows for automated
    testing, building, and deploying applications. Use when setting up CI/CD with GitHub
    Actions, automating development workflows, or creating reusable workflow templates.

[github-codespaces-efficiency]
    Source: awesome-copilot
    What it does: Tunes GitHub Codespaces (cloud developer environments) to start faster and
    cost less by slimming setups, right-sizing machines, and adjusting timeouts.
    When to use: Your Codespaces spend is high or developers complain they are slow to start.
    Search terms: github codespaces, cloud dev environment, codespaces cost, slow startup,
    devcontainer, developer tools, reduce spend, prebuilds
    Original description: Audit and improve GitHub Codespaces efficiency. Use this skill when a
    user wants faster Codespaces startup, lower Codespaces spend, slim devcontainers, right-size
    machines, tune idle timeout, or scope prebuilds to branches with sustained usage.

[gitlab-ci-patterns]
    Source: agents (bundle)
    What it does: Builds GitLab CI/CD pipelines with multiple stages, caching, and distributed
    runners so testing and deployment run automatically and fast.
    When to use: You use GitLab and want automated, efficient build and deploy pipelines.
    Search terms: gitlab, ci/cd, pipeline, automated testing, deployment, gitlab runners, build
    speed, devops
    Original description: Build GitLab CI/CD pipelines with multi-stage workflows, caching, and
    distributed runners for scalable automation. Use when implementing GitLab CI/CD, optimizing
    pipeline performance, or setting up automated testing and deployment.

[gitops-workflow]
    Source: agents (bundle)
    What it does: Sets up GitOps with ArgoCD or Flux so your Kubernetes deployments happen
    automatically from what is defined in your code repository.
    When to use: You want Kubernetes deployments driven from Git with no manual steps.
    Search terms: gitops, argocd, flux, kubernetes, automated deployment, infrastructure,
    declarative, devops
    Original description: Implement GitOps workflows with ArgoCD and Flux for automated,
    declarative Kubernetes deployments with continuous reconciliation. Use when implementing
    GitOps practices, automating Kubernetes deployments, or setting up declarative
    infrastructure management.

[helm-chart-scaffolding]
    Source: agents (bundle)
    What it does: Creates and organizes Helm charts, reusable packages for deploying
    applications to Kubernetes.
    When to use: You need to package an application so it can be deployed to Kubernetes
    consistently.
    Search terms: helm, kubernetes, helm charts, app packaging, k8s deployment, templates,
    devops, infrastructure
    Original description: Design, organize, and manage Helm charts for templating and packaging
    Kubernetes applications with reusable configurations. Use when creating Helm charts,
    packaging Kubernetes applications, or implementing templated deployments.

[hybrid-cloud-networking]
    Source: agents (bundle)
    What it does: Sets up secure, fast network connections between your own data center or
    office and cloud providers using VPNs or dedicated links.
    When to use: You need your on-premises systems and your cloud systems to talk to each other
    securely.
    Search terms: hybrid cloud, vpn, connect office to cloud, data center, direct connect,
    networking, secure connection, on-premises
    Original description: Configure secure, high-performance connectivity between on-premises
    infrastructure and cloud platforms using VPN and dedicated connections. Use when building
    hybrid cloud architectures, connecting data centers to cloud, or implementing secure cross-
    premises networking.

[import-infrastructure-as-code]
    Source: awesome-copilot
    What it does: Turns your existing Azure resources into Terraform code so they can be
    managed, tracked, and reproduced reliably.
    When to use: You have Azure infrastructure that was set up by hand and want it captured as
    code.
    Search terms: azure, terraform, infrastructure as code, import resources, reverse engineer,
    configuration drift, cloud management, azure verified modules
    Original description: Import existing Azure resources into Terraform using Azure CLI
    discovery and Azure Verified Modules (AVM). Use when asked to reverse-engineer live Azure
    infrastructure, generate Infrastructure as Code from existing subscriptions/resource
    groups/resource IDs, map dependencies, derive exact import addresses from downloaded module
    source, prevent configuration drift, and produce AVM-based Terraform files ready for
    validation and planning across any Azure resource type.

[incident-postmortem]
    Source: awesome-copilot
    What it does: Writes a structured, blameless post-mortem after an outage, covering the
    timeline, what contributed, the impact, and follow-up actions with owners.
    When to use: You had an outage and need a clear write-up of what went wrong and how to
    prevent it.
    Search terms: post-mortem, outage report, root cause analysis, rca, incident review, what
    went wrong, downtime, lessons learned
    Original description: Use when an outage, production incident, or significant service
    degradation has occurred and the team needs to write a structured blameless post-mortem.
    Triggers on phrases like "write a post-mortem", "incident review", "what went wrong",
    "outage report", "root cause analysis", or "RCA". Covers timeline reconstruction,
    contributing factor analysis, impact quantification, and action item generation with owners.

[incident-runbook-templates]
    Source: agents (bundle)
    What it does: Creates step-by-step emergency procedures (runbooks) for handling outages,
    including who to escalate to and how to recover.
    When to use: You want clear instructions ready for whoever is on call when something breaks
    at 3 AM.
    Search terms: runbook, incident response, on-call, outage procedures, escalation, emergency
    plan, recovery steps, operations
    Original description: Create structured incident response runbooks with step-by-step
    procedures, escalation paths, and recovery actions. Use this skill when building a service
    outage runbook for a payment processing system; creating database incident procedures
    covering connection pool exhaustion, replication lag, and disk space alerts; onboarding new
    on-call engineers who need step-by-step recovery guides written for a 3 AM brain; or
    standardizing escalation matrices across multiple engineering teams.

[integrate-context-matic]
    Source: awesome-copilot
    What it does: Finds and connects third-party services and APIs to your software using the
    context-matic tool for guidance and SDK details.
    When to use: You need your app to connect with an outside service, like a payment or
    shipping provider.
    Search terms: api integration, third-party api, connect services, sdk, integrate, external
    api, context-matic, add api client
    Original description: Discovers and integrates third-party APIs using the context-matic MCP
    server. Uses `fetch_api` to find available API SDKs, `ask` for integration guidance,
    `model_search` and `endpoint_search` for SDK details. Use when the user asks to integrate a
    third-party API, add an API client, implement features with an external API, or work with
    any third-party API or SDK.

[istio-traffic-management]
    Source: agents (bundle)
    What it does: Configures Istio service mesh to control how traffic flows between your
    services, including load balancing, failure protection, and gradual rollouts.
    When to use: You run Kubernetes with Istio and want to control routing or roll out changes
    gradually.
    Search terms: istio, service mesh, kubernetes, traffic routing, canary deployment, load
    balancing, circuit breaker, microservices
    Original description: Configure Istio traffic management including routing, load balancing,
    circuit breakers, and canary deployments. Use when implementing service mesh traffic
    policies, progressive delivery, or resilience patterns.

[java-add-graalvm-native-image-support]
    Source: awesome-copilot
    What it does: Converts a Java application into a fast-starting native executable using
    GraalVM, fixing build errors along the way.
    When to use: You want your Java app to start faster and use less memory.
    Search terms: graalvm, native image, java, faster startup, memory usage, java performance,
    compile java, oracle
    Original description: GraalVM Native Image expert that adds native image support to Java
    applications, builds the project, analyzes build errors, applies fixes, and iterates until
    successful compilation using Oracle best practices.

[java-helidon]
    Source: awesome-copilot
    What it does: Provides best practices for building Java applications with the Helidon 4
    framework, covering routing, database access, configuration, security, and testing.
    When to use: You are developing with Helidon and want to follow the recommended patterns.
    Search terms: helidon, java, microservices, oracle, web framework, backend, best practices,
    java 21
    Original description: Get best practices for developing applications with Helidon 4 (SE and
    MP). Use when working with Helidon SE or Helidon MP, HttpService routing, Helidon DB Client,
    MicroProfile Config, Helidon Security, or Helidon testing in Java 21+ projects.

[java-springboot]
    Source: awesome-copilot
    What it does: Provides best practices for building Java applications with Spring Boot.
    When to use: You are working on a Spring Boot app and want it built the recommended way.
    Search terms: spring boot, java, best practices, backend, web app, java framework, code
    review, enterprise java
    Original description: Get best practices for developing applications with Spring Boot.

[javax-to-jakarta-migration]
    Source: awesome-copilot
    What it does: Updates Java code from the old javax naming to the newer jakarta naming
    required by modern servers like Tomcat 11.
    When to use: Your Java app will not run on a newer server because of outdated javax
    packages.
    Search terms: java, jakarta, javax, tomcat 11, upgrade java, migration, legacy code, jakarta
    ee
    Original description: Migrate Java code from javax.* to jakarta.* namespace. Use when
    upgrading to Tomcat 11, Jakarta EE 10, or when javax imports are detected in the codebase.

[k8s-manifest-generator]
    Source: agents (bundle)
    What it does: Writes production-quality Kubernetes configuration files for deployments,
    services, settings, and secrets following security best practices.
    When to use: You need Kubernetes YAML written correctly and securely for your app.
    Search terms: kubernetes, k8s, yaml, deployment config, manifests, containers, secure
    configuration, devops
    Original description: Create production-ready Kubernetes manifests for Deployments,
    Services, ConfigMaps, and Secrets following best practices and security standards. Use when
    generating Kubernetes YAML manifests, creating K8s resources, or implementing production-
    grade Kubernetes configurations.

[kotlin-springboot]
    Source: awesome-copilot
    What it does: Provides best practices for building Kotlin applications with Spring Boot.
    When to use: You are working on a Kotlin Spring Boot app and want to follow the recommended
    approach.
    Search terms: kotlin, spring boot, best practices, backend, jvm, web app, code review,
    kotlin framework
    Original description: Get best practices for developing applications with Spring Boot and
    Kotlin.

[linkerd-patterns]
    Source: agents (bundle)
    What it does: Sets up the Linkerd service mesh for secure, low-overhead communication
    between services in Kubernetes.
    When to use: You want encrypted, policy-controlled traffic between services without heavy
    tooling.
    Search terms: linkerd, service mesh, kubernetes, zero trust, mtls, traffic policy,
    microservices, lightweight
    Original description: Implement Linkerd service mesh patterns for lightweight, security-
    focused service mesh deployments. Use when setting up Linkerd, configuring traffic policies,
    or implementing zero-trust networking with minimal overhead.

[microservices-patterns]
    Source: agents (bundle)
    What it does: Designs systems made of many small independent services, defining boundaries,
    communication, and resilience against failures.
    When to use: You are splitting a big application into smaller services or building a
    distributed system from scratch.
    Search terms: microservices, system design, break up monolith, distributed systems, event-
    driven, architecture, scalability, resilience
    Original description: Design microservices architectures with service boundaries, event-
    driven communication, and resilience patterns. Use when building distributed systems,
    decomposing monoliths, or implementing microservices.

[monorepo-management]
    Source: agents (bundle)
    What it does: Sets up and manages a single repository holding many packages using Turborepo,
    Nx, or pnpm workspaces, with fast builds and shared dependencies.
    When to use: Your team keeps multiple projects in one repository and builds are getting slow
    or messy.
    Search terms: monorepo, turborepo, nx, pnpm, build speed, shared code, repository structure,
    developer tools
    Original description: Master monorepo management with Turborepo, Nx, and pnpm workspaces to
    build efficient, scalable multi-package repositories with optimized builds and dependency
    management. Use when setting up monorepos, optimizing builds, or managing shared
    dependencies.

[multi-cloud-architecture]
    Source: agents (bundle)
    What it does: Designs systems that span AWS, Azure, Google Cloud, and Oracle, helping you
    choose services and avoid being locked into one vendor.
    When to use: You want to use more than one cloud provider or reduce dependence on a single
    one.
    Search terms: multi-cloud, vendor lock-in, aws, azure, google cloud, cloud strategy,
    architecture, oracle cloud
    Original description: Design multi-cloud architectures using a decision framework to select
    and integrate services across AWS, Azure, GCP, and OCI. Use when building multi-cloud
    systems, avoiding vendor lock-in, or leveraging best-of-breed services from multiple
    providers.

[multi-stage-dockerfile]
    Source: awesome-copilot
    What it does: Writes efficient Dockerfiles that build smaller, faster, more secure container
    images for any programming language.
    When to use: Your Docker images are large or slow to build and you want them streamlined.
    Search terms: docker, dockerfile, containers, image size, build speed, multi-stage build,
    devops, deployment
    Original description: Create optimized multi-stage Dockerfiles for any language or framework

[nft-standards]
    Source: agents (bundle)
    What it does: Builds NFT smart contracts and marketplaces using the ERC-721 and ERC-1155
    standards, including metadata and minting.
    When to use: You are launching an NFT collection or marketplace.
    Search terms: nft, erc-721, erc-1155, blockchain, minting, digital collectibles, ethereum,
    web3, marketplace
    Original description: Implement NFT standards (ERC-721, ERC-1155) with proper metadata
    handling, minting strategies, and marketplace integration. Use when creating NFT contracts,
    building NFT marketplaces, or implementing digital asset systems.

[nodejs-backend-patterns]
    Source: agents (bundle)
    What it does: Builds production-ready Node.js backend services and APIs with Express or
    Fastify, including authentication, error handling, and database access.
    When to use: You need a Node.js server or API built properly.
    Search terms: node.js, express, fastify, api, backend, javascript server, rest api,
    authentication
    Original description: Build production-ready Node.js backend services with Express/Fastify,
    implementing middleware patterns, error handling, authentication, database integration, and
    API design best practices. Use when creating Node.js servers, REST APIs, GraphQL backends,
    or microservices architectures.

[nx-workspace-patterns]
    Source: agents (bundle)
    What it does: Configures Nx monorepo workspaces, including project boundaries, build
    caching, and running only what changed.
    When to use: You use Nx and want faster builds or cleaner project structure.
    Search terms: nx, monorepo, build caching, affected commands, workspace, developer tools,
    build speed, project structure
    Original description: Configure and optimize Nx monorepo workspaces. Use when setting up Nx,
    configuring project boundaries, optimizing build caching, or implementing affected commands.

[observability-and-instrumentation]
    Source: agent-skills
    What it does: Adds logging, metrics, tracing, and alerts to your software so you can see
    what is happening in production and diagnose problems.
    When to use: Customers report issues but you cannot tell what happened from your current
    data.
    Search terms: logging, monitoring, metrics, alerts, observability, production issues,
    tracing, visibility
    Original description: Instruments code so production behavior is visible and diagnosable.
    Use when adding logging, metrics, tracing, or alerting. Use when shipping any feature that
    runs in production and you need evidence it works. Use when production issues are reported
    but you can't tell what happened from the available data.

[on-call-handoff-patterns]
    Source: agents (bundle)
    What it does: Structures on-call shift handoffs so the incoming engineer knows about active
    incidents, ongoing investigations, and recent changes.
    When to use: You want smoother handovers between on-call engineers so nothing falls through
    the cracks.
    Search terms: on-call, shift handoff, incident handover, escalation, shift summary,
    operations, sre, handoff checklist
    Original description: Master on-call shift handoffs with context transfer, escalation
    procedures, and documentation. Use this skill when transitioning on-call responsibilities
    between engineers and ensuring the incoming responder has full situational awareness, when
    writing a shift summary that captures active incidents, ongoing investigations, and recent
    changes, when handing off mid-incident so a fresh engineer can take over the incident
    commander role without losing context, when onboarding a new engineer to the on-call
    rotation for the first time, or when auditing and improving the quality of existing handoff
    p…

[openapi-spec-generation]
    Source: agents (bundle)
    What it does: Creates and maintains OpenAPI specifications that document your API, which can
    also generate client libraries and check contract compliance.
    When to use: You need clear, standard documentation for your API.
    Search terms: openapi, api documentation, swagger, api spec, sdk generation, api contract,
    developer docs, rest api
    Original description: Generate and maintain OpenAPI 3.1 specifications from code, design-
    first specs, and validation patterns. Use when creating API documentation, generating SDKs,
    or ensuring API contract compliance.

[openapi-to-application-code]
    Source: awesome-copilot
    What it does: Generates a complete, working application from an OpenAPI specification.
    When to use: You have an API spec and want the actual code built from it.
    Search terms: openapi, generate code, api to app, swagger, code generation, backend,
    scaffold, api spec
    Original description: Generate a complete, production-ready application from an OpenAPI
    specification

[optimize-simplicite-logs]
    Source: awesome-copilot
    What it does: Parses raw Simplicité platform log files, strips out noise, and outputs clean
    structured JSON.
    When to use: You have messy Simplicité logs and need them readable or machine-processable.
    Search terms: simplicite, logs, log parsing, json, clean up logs, log analysis, text file,
    filter logs
    Original description: capability to parse Simplicité logs from a raw `.txt` file, filter
    fields to reduce noise, and output the result as structured JSON.

[projection-patterns]
    Source: agents (bundle)
    What it does: Builds fast read-only views of data from event streams for systems that use
    event sourcing or CQRS.
    When to use: Your event-sourced system needs quicker reporting or query performance.
    Search terms: projections, read models, event sourcing, cqrs, materialized views, query
    performance, reporting, backend
    Original description: Build read models and projections from event streams. Use when
    implementing CQRS read sides, building materialized views, or optimizing query performance
    in event-sourced systems.

[publish-to-pages]
    Source: awesome-copilot
    What it does: Publishes a presentation or web page to a live GitHub Pages URL, converting
    PowerPoint, PDF, HTML, or Google Slides as needed.
    When to use: You want to share a slide deck or HTML page as a public link.
    Search terms: github pages, publish presentation, share slides, powerpoint to web, pdf to
    web, free hosting, live url, google slides
    Original description: Publish presentations and web content to GitHub Pages. Converts PPTX,
    PDF, HTML, or Google Slides to a live GitHub Pages URL. Handles repo creation, file
    conversion, Pages enablement, and returns the live URL. Use when the user wants to publish,
    deploy, or share a presentation or HTML file via GitHub Pages.

[python-background-jobs]
    Source: agents (bundle)
    What it does: Sets up background processing in Python so long tasks like sending emails or
    generating reports run separately from user requests.
    When to use: Your Python app makes users wait on slow tasks that should run in the
    background.
    Search terms: python, background jobs, task queue, celery, workers, async processing, long-
    running tasks, scheduled jobs
    Original description: Python background job patterns including task queues, workers, and
    event-driven architecture. Use when implementing async task processing, job queues, long-
    running operations, or decoupling work from request/response cycles.

[python-observability]
    Source: agents (bundle)
    What it does: Adds structured logging, metrics, and tracing to Python applications so
    production problems are easier to diagnose.
    When to use: You need better visibility into what your Python app is doing in production.
    Search terms: python, logging, metrics, tracing, monitoring, debugging, production issues,
    observability
    Original description: Python observability patterns including structured logging, metrics,
    and distributed tracing. Use when adding logging, implementing metrics collection, setting
    up tracing, or debugging production systems.

[saga-orchestration]
    Source: agents (bundle)
    What it does: Coordinates multi-step business transactions across several services, such as
    orders spanning inventory, payment, and shipping, with automatic undo when a step fails.
    When to use: A process across multiple systems needs to either fully complete or cleanly
    roll back.
    Search terms: saga pattern, distributed transactions, microservices, rollback, order
    workflow, compensation, booking system, failed transactions
    Original description: Implement saga patterns for distributed transactions and cross-
    aggregate workflows. Use this skill when implementing distributed transactions across
    microservices where 2PC is unavailable, designing compensating actions for failed order
    workflows that span inventory, payment, and shipping services, building event-driven saga
    coordinators for travel booking systems that must roll back hotel, flight, and car rental
    reservations atomically, or debugging stuck saga states in production where compensation
    steps never complete.

[salesforce-apex-quality]
    Source: awesome-copilot
    What it does: Reviews and writes Salesforce Apex code with guardrails for bulk safety,
    security, and test coverage so it does not break under governor limits.
    When to use: You are building or checking custom Salesforce code before deploying it.
    Search terms: salesforce, apex, code review, governor limits, salesforce security, triggers,
    test coverage, salesforce development
    Original description: Apex code quality guardrails for Salesforce development. Enforces
    bulk-safety rules (no SOQL/DML in loops), sharing model requirements, CRUD/FLS security,
    SOQL injection prevention, PNB test coverage (Positive / Negative / Bulk), and modern Apex
    idioms. Use this skill when reviewing or generating Apex classes, trigger handlers, batch
    jobs, or test classes to catch governor limit risks, security gaps, and quality issues
    before deployment.

[salesforce-component-standards]
    Source: awesome-copilot
    What it does: Enforces quality, accessibility, and security standards for Salesforce user-
    interface components (Lightning Web Components, Aura, Visualforce).
    When to use: You are building or reviewing custom Salesforce screens and want them secure
    and accessible.
    Search terms: salesforce, lightning web components, lwc, aura, visualforce, salesforce ui,
    accessibility, salesforce development
    Original description: Quality standards for Salesforce Lightning Web Components (LWC), Aura
    components, and Visualforce pages. Covers SLDS 2 compliance, accessibility (WCAG 2.1 AA),
    data access pattern selection, component communication rules, XSS prevention, CSRF
    enforcement, FLS/CRUD in AuraEnabled methods, view state management, and Jest test
    requirements. Use this skill when building or reviewing any Salesforce UI component to
    enforce platform-specific security and quality standards.

[salesforce-flow-design]
    Source: awesome-copilot
    What it does: Guides the design and review of Salesforce Flows, choosing the right flow type
    and ensuring they handle bulk data and errors correctly.
    When to use: You are automating a process in Salesforce with Flows and want it built right.
    Search terms: salesforce, flows, salesforce automation, record-triggered flow, screen flow,
    workflow, fault handling, salesforce admin
    Original description: Salesforce Flow architecture decisions, flow type selection, bulk
    safety validation, and fault handling standards. Use this skill when designing or reviewing
    Record-Triggered, Screen, Autolaunched, Scheduled, or Platform Event flows to ensure correct
    type selection, no DML/Get Records in loops, proper fault connectors on all data-changing
    elements, and appropriate automation density checks before deployment.

[sandbox-migrate-to-next]
    Source: cloudflare skills
    What it does: Upgrades a Cloudflare Sandbox app from the stable version to the 1.0 preview
    release.
    When to use: You want to move your Cloudflare Sandbox project to the newest preview version.
    Search terms: cloudflare sandbox, upgrade, migration, sandbox sdk, cloudflare, 1.0 preview,
    @next, code execution
    Original description: Use when porting a Cloudflare Sandbox app from stable
    @cloudflare/sandbox to @cloudflare/sandbox@next (Sandbox SDK 1.0 preview), or when the user
    asks to migrate or upgrade to Sandbox 1.0 / @next. Not for day-to-day stable work (sandbox-
    stable) or new @next apps (sandbox-next).

[sandbox-next]
    Source: cloudflare skills
    What it does: Builds apps on the Cloudflare Sandbox SDK 1.0 preview for running code, AI
    agents, terminals, and job-like workloads in isolated environments.
    When to use: You are building something that needs to run untrusted or AI-generated code
    safely on Cloudflare's preview SDK.
    Search terms: cloudflare sandbox, code execution, ai runner, isolated environment,
    cloudflare, sandbox sdk, terminals, preview urls
    Original description: Use when building or changing Cloudflare Sandbox apps on
    @cloudflare/sandbox@next (Sandbox SDK 1.0 preview)—code execution, AI runners, interpreters,
    CI-like jobs, terminals, files, mounts, tunnels, preview URLs, lifecycle, or errors. Not for
    the default stable package (use sandbox-stable) or for porting stable to @next (use sandbox-
    migrate-to-next).

[sandbox-npm-install]
    Source: awesome-copilot
    What it does: Installs JavaScript packages correctly inside a Docker sandbox where the
    shared file system would otherwise crash native tools.
    When to use: npm install keeps failing or crashing inside your Docker development container.
    Search terms: npm install, docker, node_modules, virtiofs, container, javascript packages,
    esbuild crash, dev environment
    Original description: Install npm packages in a Docker sandbox environment. Use this skill
    whenever you need to install, reinstall, or update node_modules inside a container where the
    workspace is mounted via virtiofs. Native binaries (esbuild, lightningcss, rollup) crash on
    virtiofs, so packages must be installed on the local ext4 filesystem and symlinked back.

[sandbox-stable]
    Source: cloudflare skills
    What it does: Builds apps on the current stable Cloudflare Sandbox package for running
    commands, managing files, ports, and terminals in isolated environments.
    When to use: You are building on Cloudflare Sandbox and want to stay on the stable release.
    Search terms: cloudflare sandbox, code execution, isolated environment, cloudflare, sandbox
    sdk, run commands, terminals, production
    Original description: Use when building or changing Cloudflare Sandbox apps on the current
    stable @cloudflare/sandbox package (default npm tag)—commands, sessions, files, ports,
    tunnels, terminals, bridge, production, or deprecated-API cleanup while staying on stable.
    Not for @cloudflare/sandbox@next (use sandbox-next) or for porting to 1.0 (use sandbox-
    migrate-to-next).

[service-mesh-observability]
    Source: agents (bundle)
    What it does: Sets up monitoring, tracing, and dashboards for service meshes so you can see
    latency and reliability between services.
    When to use: You run a service mesh and need to see why calls between services are slow or
    failing.
    Search terms: service mesh, monitoring, tracing, latency, dashboards, slos, istio,
    kubernetes
    Original description: Implement comprehensive observability for service meshes including
    distributed tracing, metrics, and visualization. Use when setting up mesh monitoring,
    debugging latency issues, or implementing SLOs for service communication.

[slo-implementation]
    Source: agents (bundle)
    What it does: Defines measurable reliability targets (SLIs and SLOs) with error budgets and
    alerts so you know when service quality is slipping.
    When to use: You want to set and track reliability goals for your service.
    Search terms: slo, sli, reliability targets, uptime, error budget, alerting, sre, service
    performance
    Original description: Define and implement Service Level Indicators (SLIs) and Service Level
    Objectives (SLOs) with error budgets and alerting. Use when establishing reliability
    targets, implementing SRE practices, or measuring service performance.

[spring-boot-testing]
    Source: awesome-copilot
    What it does: Chooses and writes the right tests for Spring Boot 4 applications using JUnit
    6 and AssertJ.
    When to use: You need proper automated tests for a Spring Boot app.
    Search terms: spring boot, testing, junit, java tests, unit tests, integration tests,
    assertj, test strategy
    Original description: Expert Spring Boot 4 testing specialist that selects the best Spring
    Boot testing techniques for your situation with Junit 6 and AssertJ.

[temporal-python-testing]
    Source: agents (bundle)
    What it does: Writes and debugs tests for Temporal workflows in Python, including time-
    skipping, mocking, and replay tests.
    When to use: Your Temporal workflow tests are failing or you need to write them from
    scratch.
    Search terms: temporal, python, workflow testing, pytest, mocking, replay testing, debugging
    tests, workflows
    Original description: Test Temporal workflows with pytest, time-skipping, and mocking
    strategies. Covers unit testing, integration testing, replay testing, and local development
    setup. Use when implementing Temporal workflow tests or debugging test failures.

[terraform-module-library]
    Source: agents (bundle)
    What it does: Builds reusable Terraform modules for AWS, Azure, Google Cloud, and Oracle so
    cloud infrastructure can be provisioned consistently.
    When to use: You want standard, repeatable building blocks for setting up cloud
    infrastructure.
    Search terms: terraform, infrastructure as code, aws, azure, google cloud, reusable modules,
    cloud provisioning, devops
    Original description: Build reusable Terraform modules for AWS, Azure, GCP, and OCI
    infrastructure following infrastructure-as-code best practices. Use when creating
    infrastructure modules, standardizing cloud provisioning, or implementing reusable IaC
    components.

[transloadit-media-processing]
    Source: awesome-copilot
    What it does: Processes videos, audio, images, and documents with Transloadit, such as
    converting video, making thumbnails, resizing or watermarking images, adding subtitles, or
    OCR.
    When to use: You need media files converted, resized, or transformed automatically at scale.
    Search terms: transloadit, video encoding, image resize, thumbnails, watermark, ocr, media
    processing, subtitles, convert video
    Original description: Process media files (video, audio, images, documents) using
    Transloadit. Use when asked to encode video to HLS/MP4, generate thumbnails, resize or
    watermark images, extract audio, concatenate clips, add subtitles, OCR documents, or run any
    media processing pipeline. Covers 86+ processing robots for file transformation at scale.

[turborepo-caching]
    Source: agents (bundle)
    What it does: Configures Turborepo so monorepo builds reuse previous results locally and
    across your team, cutting build times.
    When to use: Your Turborepo builds are slow and you want caching set up properly.
    Search terms: turborepo, monorepo, build caching, remote cache, faster builds, pipeline,
    developer tools, vercel
    Original description: Configure Turborepo for efficient monorepo builds with local and
    remote caching. Use when setting up Turborepo, optimizing build pipelines, or implementing
    distributed caching.

[turnstile-spin]
    Source: cloudflare skills
    What it does: Adds Cloudflare Turnstile, a CAPTCHA alternative, to your forms and endpoints
    to block bots, including the server-side verification.
    When to use: Bots are spamming your forms or sign-ups and you want them blocked.
    Search terms: turnstile, captcha, bot protection, spam forms, cloudflare, form security,
    stop bots, verification
    Original description: Set up Cloudflare Turnstile end-to-end in a project. Scan the
    codebase, create the widget via the Cloudflare API, embed it where user requests need bot
    verification (form submissions, SPA actions, API endpoints, download links, comment or vote
    submissions, etc.), wire canonical server-side siteverify in the customer's existing
    backend, validate, and persist the skill. Load this when a user asks to add Turnstile, set
    up CAPTCHA, protect a form or endpoint from bots, or fix a Turnstile integration. Mirrors
    developers.cloudflare.com/turnstile/spin.

[vercel-cli-with-tokens]
    Source: vercel agent-skills
    What it does: Deploys and manages Vercel projects from the command line using access tokens
    instead of interactive login, including environment variables.
    When to use: You need Vercel deployments or settings handled automatically without logging
    in by hand.
    Search terms: vercel, deploy, access token, environment variables, command line, automation,
    hosting, vercel cli
    Original description: Deploy and manage projects on Vercel using token-based authentication.
    Use when working with Vercel CLI using access tokens rather than interactive login — e.g.
    "deploy to vercel", "set up vercel", "add environment variables to vercel".

[vercel-composition-patterns]
    Source: vercel agent-skills
    What it does: Refactors React components into flexible, reusable designs using composition
    instead of piles of on/off settings.
    When to use: Your React components have become hard to maintain and extend.
    Search terms: react, component design, refactoring, reusable components, compound
    components, react 19, frontend, component library
    Original description: React composition patterns that scale. Use when refactoring components
    with boolean prop proliferation, building flexible component libraries, or designing
    reusable APIs. Triggers on tasks involving compound components, render props, context
    providers, or component architecture. Includes React 19 API changes.

[vercel-optimize]
    Source: vercel agent-skills
    What it does: Analyzes a Vercel-hosted site's usage and performance data and produces ranked
    recommendations to lower the bill and speed up slow pages.
    When to use: Your Vercel bill jumped or certain pages are slow and expensive.
    Search terms: vercel, reduce vercel bill, site speed, core web vitals, next.js, caching,
    function invocations, hosting costs
    Original description: Use for Vercel cost and performance optimization on deployed projects,
    especially Next.js, SvelteKit, Nuxt, and limited Astro apps. Collect Vercel metrics, usage,
    project config, and code scan results first; investigate only metric-backed candidates;
    produce ranked recommendations grounded in verified files and version-aware Vercel/framework
    docs. Trigger for Vercel bill reduction, slow or expensive routes, caching opportunities,
    Function Invocations, Build Minutes, Fast Data Transfer, Core Web Vitals, Bot Management,
    Fluid compute, or cost breakdown requests.

[vercel-react-best-practices]
    Source: vercel agent-skills
    What it does: Applies Vercel's performance guidelines when writing or reviewing React and
    Next.js code.
    When to use: You want your React or Next.js site to load and run faster.
    Search terms: react, next.js, performance, page speed, code review, vercel, frontend, bundle
    size
    Original description: React and Next.js performance optimization guidelines from Vercel
    Engineering. This skill should be used when writing, reviewing, or refactoring React/Next.js
    code to ensure optimal performance patterns. Triggers on tasks involving React components,
    Next.js pages, data fetching, bundle optimization, or performance improvements.

[vercel-react-native-skills]
    Source: vercel agent-skills
    What it does: Applies best practices for building fast React Native and Expo mobile apps,
    including lists, animations, and native features.
    When to use: You are building a mobile app with React Native or Expo.
    Search terms: react native, expo, mobile app, ios, android, app performance, animations,
    native modules
    Original description: React Native and Expo best practices for building performant mobile
    apps. Use when building React Native components, optimizing list performance, implementing
    animations, or working with native modules. Triggers on tasks involving React Native, Expo,
    mobile performance, or native platform APIs.

[vercel-react-view-transitions]
    Source: vercel agent-skills
    What it does: Adds smooth, native-feeling page and element animations in React and Next.js
    using the built-in View Transition API.
    When to use: You want pages or elements in your React app to animate smoothly without extra
    libraries.
    Search terms: react, animations, page transitions, view transitions, next.js, smooth
    navigation, ui animation, frontend
    Original description: Guide for implementing smooth, native-feeling animations using React's
    View Transition API (`<ViewTransition>` component, `addTransitionType`, and CSS view
    transition pseudo-elements). Use this skill whenever the user wants to add page transitions,
    animate route changes, create shared element animations, animate enter/exit of components,
    animate list reorder, implement directional (forward/back) navigation animations, or
    integrate view transitions in Next.js. Also use when the user mentions view transitions,
    `startViewTransition`, `ViewTransition`, transition types, or asks about animating bet…

[web3-testing]
    Source: agents (bundle)
    What it does: Tests blockchain smart contracts thoroughly with Hardhat and Foundry,
    including simulations against a copy of the live network.
    When to use: You need confidence your smart contracts work before deploying them to the
    blockchain.
    Search terms: smart contracts, solidity, hardhat, foundry, blockchain testing, web3, defi,
    ethereum
    Original description: Test smart contracts comprehensively using Hardhat and Foundry with
    unit tests, integration tests, and mainnet forking. Use when testing Solidity contracts,
    setting up blockchain test suites, or validating DeFi protocols.

[workers-best-practices]
    Source: cloudflare skills
    What it does: Writes and reviews Cloudflare Workers code against production best practices,
    catching common mistakes in streaming, secrets, and configuration.
    When to use: You are building or reviewing Cloudflare Workers and want them production-
    ready.
    Search terms: cloudflare workers, serverless, code review, best practices, wrangler, edge
    functions, cloudflare, production
    Original description: Reviews and authors Cloudflare Workers code against production best
    practices. Load when writing new Workers, reviewing Worker code, configuring wrangler.jsonc,
    or checking for common Workers anti-patterns (streaming, floating promises, global state,
    secrets, bindings, observability). Biases towards retrieval from Cloudflare docs over pre-
    trained knowledge.

[wrangler]
    Source: cloudflare skills
    What it does: Provides correct commands and guidance for Wrangler, Cloudflare's command-line
    tool for deploying and managing Workers, storage, databases, AI, and queues.
    When to use: You need to run Wrangler commands to deploy or manage Cloudflare services.
    Search terms: wrangler, cloudflare, command line, deploy workers, kv, r2, d1, cloudflare cli
    Original description: Cloudflare Workers CLI for deploying, developing, and managing
    Workers, KV, R2, D1, Vectorize, Hyperdrive, Workers AI, Containers, Queues, Workflows,
    Pipelines, and Secrets Store. Load before running wrangler commands to ensure correct syntax
    and best practices. Biases towards retrieval from Cloudflare docs over pre-trained
    knowledge.
