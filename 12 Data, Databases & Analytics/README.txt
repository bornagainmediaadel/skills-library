12 DATA, DATABASES & ANALYTICS
==============================

Skills for data work: SQL and PostgreSQL, vector databases (Qdrant, Pinecone), RAG, ML training
and evaluation, data pipelines, dashboards and Oracle-to-Postgres migrations.

93 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - airflow-dag-patterns
  - arize-ai-provider-integration
  - arize-annotation
  - arize-dataset
  - arize-evaluator
  - arize-experiment
  - arize-instrumentation
  - arize-link
  - arize-prompt-optimization
  - arize-trace
  - backtesting-frameworks
  - bigquery-pipeline-audit
  - checkpoint-promotion
  - cosmosdb-datamodeling
  - creating-oracle-to-postgres-master-migration-plan
  - creating-oracle-to-postgres-migration-bug-report
  - creating-oracle-to-postgres-migration-integration-tests
  - data-quality-frameworks
  - data-storytelling
  - data-visualization
  - database-migration
  - dataset-curation
  - dbt-transformation-patterns
  - efcore-d2-db-diagram
  - embedding-strategies
  - eval-driven-dev
  - eval-engineering
  - eval-harness-first
  - evaluation-methodology
  - finetuning-method-selection
  - grafana-dashboards
  - grpo-rlvr-training
  - hybrid-search-implementation
  - kpi-dashboard-design
  - langchain-rag
  - langsmith-online-eval-engineering
  - llm-evaluation
  - lora-qlora-recipes
  - migrating-oracle-to-postgres-data-access-code
  - migrating-oracle-to-postgres-stored-procedures
  - ml-pipeline-workflow
  - phoenix-cli
  - phoenix-evals
  - phoenix-tracing
  - pinecone-rag
  - planning-oracle-to-postgres-migration-integration-testing
  - postgresql-code-review
  - postgresql-optimization
  - postgresql-table-design
  - preference-optimization
  - prometheus-configuration
  - qdrant-clients-sdk
  - qdrant-deployment-options
  - qdrant-horizontal-scaling
  - qdrant-indexing-performance-optimization
  - qdrant-memory-usage-optimization
  - qdrant-minimize-latency
  - qdrant-model-migration
  - qdrant-monitoring
  - qdrant-monitoring-debugging
  - qdrant-monitoring-setup
  - qdrant-performance-optimization
  - qdrant-scaling
  - qdrant-scaling-data-volume
  - qdrant-scaling-qps
  - qdrant-scaling-query-volume
  - qdrant-search-quality
  - qdrant-search-quality-diagnosis
  - qdrant-search-speed-optimization
  - qdrant-search-strategies
  - qdrant-sliding-time-window
  - qdrant-tenant-scaling
  - qdrant-version-upgrade
  - qdrant-vertical-scaling
  - quantized-export
  - rag-implementation
  - recsys-pipeline-architect
  - reviewing-oracle-to-postgres-migration
  - scaffolding-oracle-to-postgres-migration-test-project
  - shuffle-json-data
  - similarity-search-patterns
  - snowflake-semanticview
  - spark-environment-setup
  - spark-memory-thermal-ops
  - spark-optimization
  - spark-training-gotchas
  - sql-code-review
  - sql-optimization
  - sql-optimization-patterns
  - sql-server-table-reconciliation
  - trace-to-training-data
  - vector-index-tuning
  - vision-sft

SKILL DETAILS
-------------

[airflow-dag-patterns]
    Source: agents (bundle)
    What it does: Builds scheduled data pipelines in Apache Airflow following best practices for
    reliability, testing, and deployment.
    When to use: You need to automate recurring data jobs or workflows with Airflow.
    Search terms: airflow, data pipeline, scheduled jobs, workflow automation, etl, batch jobs,
    data engineering, dag, orchestration, automate data tasks
    Original description: Build production Apache Airflow DAGs with best practices for
    operators, sensors, testing, and deployment. Use when creating data pipelines, orchestrating
    workflows, or scheduling batch jobs.

[arize-ai-provider-integration]
    Source: awesome-copilot
    What it does: Connects AI providers like OpenAI or Anthropic to Arize by creating and
    managing the stored credentials that its evaluation features use.
    When to use: You use Arize to monitor AI apps and need to add or update an AI provider's API
    key.
    Search terms: arize, api keys, openai integration, anthropic integration, llm provider, ai
    monitoring, connect ai provider, credentials, ai observability, evaluators
    Original description: Creates, reads, updates, and deletes Arize AI integrations that store
    LLM provider credentials used by evaluators and other Arize features. Supports any LLM
    provider (e.g. OpenAI, Anthropic, Azure OpenAI, AWS Bedrock, Vertex AI, Gemini, NVIDIA NIM).
    Use when the user mentions AI integration, LLM provider credentials, create integration,
    list integrations, update credentials, delete integration, or connecting an LLM provider to
    Arize.

[arize-annotation]
    Source: awesome-copilot
    What it does: Sets up human review workflows in Arize, defining label types and review
    queues and applying people's feedback to AI outputs.
    When to use: You want humans to review and label your AI's responses in Arize to judge
    quality.
    Search terms: arize, human review, labeling, annotation, human feedback, quality review, ai
    outputs, review queue, rate ai responses, ai monitoring
    Original description: Creates and manages annotation configs (categorical, continuous,
    freeform label schemas) and annotation queues (human review workflows) on Arize. Applies
    human annotations to project spans via the Python SDK. Use when the user mentions annotation
    config, annotation queue, label schema, human feedback, bulk annotate spans,
    update_annotations, labeling queue, annotate record, or human review.

[arize-dataset]
    Source: awesome-copilot
    What it does: Creates and manages test datasets in Arize, including adding examples,
    exporting data, and building datasets from files.
    When to use: You need a set of test examples to evaluate your AI app in Arize.
    Search terms: arize, test data, dataset, golden dataset, evaluation examples, test set,
    export data, ai testing, ai monitoring, sample data
    Original description: Creates, manages, and queries Arize datasets and examples. Covers
    dataset CRUD, appending examples, exporting data, and file-based dataset creation using the
    ax CLI. Use when the user needs test data, evaluation examples, or mentions create dataset,
    list datasets, export dataset, append examples, dataset version, golden dataset, or test
    set.

[arize-evaluator]
    Source: awesome-copilot
    What it does: Builds and runs AI-based graders in Arize that score your AI app's responses
    for things like accuracy, relevance, and made-up answers, with ongoing monitoring.
    When to use: You want to automatically grade how well your AI app is answering in Arize.
    Search terms: arize, ai grading, llm judge, hallucination, accuracy, relevance, ai quality,
    evaluation, ai monitoring, score responses
    Original description: Handles LLM-as-judge evaluation workflows on Arize including
    creating/updating evaluators, running evaluations on spans or experiments, managing tasks,
    trigger-run operations, column mapping, and continuous monitoring. Use when the user
    mentions create evaluator, LLM judge, hallucination, faithfulness, correctness, relevance,
    run eval, score spans, score experiment, trigger-run, column mapping, continuous monitoring,
    or improve evaluator prompt.

[arize-experiment]
    Source: awesome-copilot
    What it does: Runs and compares experiments in Arize to see which AI model or prompt
    performs better.
    When to use: You want to test two versions of your AI setup against each other and measure
    which is more accurate.
    Search terms: arize, a/b test, compare models, experiment, benchmark, model performance, ai
    testing, evaluate ai, accuracy, ai monitoring
    Original description: Creates, runs, and analyzes Arize experiments for evaluating and
    comparing model performance. Covers experiment CRUD, exporting runs, comparing results, and
    evaluation workflows using the ax CLI. Use when the user mentions create experiment, run
    experiment, compare models, model performance, evaluate AI, experiment results, benchmark,
    A/B test models, or measure accuracy.

[arize-instrumentation]
    Source: awesome-copilot
    What it does: Adds tracing to an AI application so Arize can record what it does, first
    analyzing your code and then making the changes after you approve.
    When to use: You want to start monitoring your AI app in Arize and need the tracking code
    added.
    Search terms: arize, ai monitoring, tracing, llm observability, opentelemetry, track ai app,
    set up monitoring, ai logging, debug ai, instrumentation
    Original description: Adds Arize AX tracing to an LLM application for the first time.
    Follows a two-phase agent-assisted flow to analyze the codebase then implement
    instrumentation after user confirmation. Use when the user wants to instrument their app,
    add tracing from scratch, set up LLM observability, integrate OpenTelemetry or
    openinference, or get started with Arize tracing.

[arize-link]
    Source: awesome-copilot
    What it does: Generates shareable links to specific traces, datasets, evaluators, and other
    items in the Arize dashboard.
    When to use: You want to send a teammate a direct link to something in Arize.
    Search terms: arize, share link, deep link, trace url, ai monitoring, dashboard link, share
    with team, open in arize, session link, dataset link
    Original description: Generates deep links to the Arize UI for traces, spans, sessions,
    datasets, labeling queues, evaluators, and annotation configs. Produces clickable URLs for
    sharing Arize resources with team members. Use when the user wants to link to or open a
    trace, span, session, dataset, evaluator, or annotation config in the Arize UI.

[arize-prompt-optimization]
    Source: awesome-copilot
    What it does: Improves your AI prompts using real usage data and evaluation results from
    Arize, iterating until the outputs get better.
    When to use: Your AI app gives mediocre answers and you want to improve the instructions it
    runs on.
    Search terms: arize, improve prompt, prompt engineering, better ai answers, prompt tuning,
    system prompt, ai output quality, optimize prompt, ai monitoring, fix ai responses
    Original description: Optimizes, improves, and debugs LLM prompts using production trace
    data, evaluations, and annotations. Extracts prompts from spans, gathers performance signal,
    and runs a data-driven optimization loop using the ax CLI. Use when the user mentions
    optimize prompt, improve prompt, make AI respond better, improve output quality, prompt
    engineering, prompt tuning, or system prompt improvement.

[arize-trace]
    Source: awesome-copilot
    What it does: Downloads and inspects recorded activity from your AI app in Arize to
    understand what it did or track down errors.
    When to use: Your AI app did something unexpected and you want to see exactly what happened.
    Search terms: arize, traces, debug ai, ai logs, export traces, investigate errors, ai
    monitoring, what is my ai doing, root cause, spans
    Original description: Downloads, exports, and inspects existing Arize traces and spans to
    understand what an LLM app is doing or debug runtime issues. Covers exporting traces by ID,
    spans by ID, sessions by ID, and root-cause investigation using the ax CLI. Use when the
    user wants to look at existing trace data, see what their LLM app is doing, export traces,
    download spans, investigate errors, or analyze behavior regressions.

[backtesting-frameworks]
    Source: agents (bundle)
    What it does: Builds systems to test trading strategies against historical data while
    avoiding common mistakes like peeking at future prices or ignoring fees.
    When to use: You have a trading idea and want to see how it would have performed in the past
    before risking money.
    Search terms: backtesting, trading strategy, algorithmic trading, historical data, stock
    trading, quant, trading bot, strategy testing, investment strategy, finance
    Original description: Build robust backtesting systems for trading strategies with proper
    handling of look-ahead bias, survivorship bias, and transaction costs. Use when developing
    trading algorithms, validating strategies, or building backtesting infrastructure.

[bigquery-pipeline-audit]
    Source: awesome-copilot
    What it does: Audits Python code that uses Google BigQuery for runaway costs, safe re-
    running, and production readiness, reporting exactly where to fix things.
    When to use: Your BigQuery bills are high or you want to check a data pipeline before
    relying on it.
    Search terms: bigquery, google cloud, data pipeline, cloud costs, audit code, python, data
    engineering, reduce bigquery cost, production ready, code review
    Original description: Audits Python + BigQuery pipelines for cost safety, idempotency, and
    production readiness. Returns a structured report with exact patch locations.

[checkpoint-promotion]
    Source: agents (bundle)
    What it does: Checks whether a newly trained AI model version is good enough to ship by
    comparing it against the previous one and testing it hasn't forgotten earlier skills.
    When to use: You've just fine-tuned an AI model and need to decide whether to release it.
    Search terms: fine tuning, model release, ai model testing, model quality, ship model,
    regression check, machine learning, custom ai model, model comparison, training
    Original description: Gate fine-tuned checkpoints with drift budgets, paired comparison, and
    forgetting checks before promotion. Use after a training run produces a checkpoint, when
    deciding whether a tuned model ships, or when a promoted model needs re-gating against
    updated goldens.

[cosmosdb-datamodeling]
    Source: awesome-copilot
    What it does: Walks through your app's data needs and produces an Azure Cosmos DB database
    design with written requirements and model documents.
    When to use: You're building an app on Azure Cosmos DB and need to design how the data is
    stored.
    Search terms: cosmos db, azure, database design, nosql, data model, azure database, app
    database, schema design, cloud database, microsoft azure
    Original description: Step-by-step guide for capturing key application requirements for
    NoSQL use-case and produce Azure Cosmos DB Data NoSQL Model design using best practices and
    common patterns, artifacts_produced: "cosmosdb_requirements.md" file and
    "cosmosdb_data_model.md" file

[creating-oracle-to-postgres-master-migration-plan]
    Source: awesome-copilot
    What it does: Scans a .NET solution, identifies which projects depend on Oracle, and
    produces a master plan for moving them to PostgreSQL.
    When to use: You're starting a move from Oracle to PostgreSQL across a .NET codebase and
    need an inventory and plan.
    Search terms: oracle to postgres, database migration, postgresql, oracle, dotnet, migration
    plan, .net, switch databases, move off oracle, c#
    Original description: Discovers all projects in a .NET solution, classifies each for Oracle-
    to-PostgreSQL migration eligibility, and produces a persistent master migration plan. Use
    when starting a multi-project Oracle-to-PostgreSQL migration, creating a migration
    inventory, or assessing which .NET projects contain Oracle dependencies.

[creating-oracle-to-postgres-migration-bug-report]
    Source: awesome-copilot
    What it does: Writes clear bug reports for problems found while moving from Oracle to
    PostgreSQL, with severity, root cause, and how to fix.
    When to use: Something behaves differently after moving a database from Oracle to PostgreSQL
    and you need to document it.
    Search terms: oracle to postgres, bug report, database migration, postgresql, oracle,
    defect, migration issues, document bugs, dotnet, root cause
    Original description: Creates structured bug reports for defects found during Oracle-to-
    PostgreSQL migration. Use when documenting behavioral differences between Oracle and
    PostgreSQL as actionable bug reports with severity, root cause, and remediation steps.

[creating-oracle-to-postgres-migration-integration-tests]
    Source: awesome-copilot
    What it does: Writes tests that capture how your .NET app's database code behaves on Oracle,
    to serve as the baseline before migrating to PostgreSQL.
    When to use: You're early in an Oracle-to-PostgreSQL migration and need tests that record
    current Oracle behavior.
    Search terms: oracle to postgres, integration tests, database migration, dotnet, oracle,
    postgresql, testing, baseline tests, c#, data access
    Original description: Creates integration test cases targeting Oracle for .NET data access
    artifacts. Tests capture Oracle expected behavior as the authoritative baseline; they are
    written once and later ported to PostgreSQL by migrating the test project in Phase 6. Use
    only during Phase 3, before any PostgreSQL migration work has begun. Do not invoke during
    Phase 6 or against a project that has already been migrated.

[data-quality-frameworks]
    Source: agents (bundle)
    What it does: Sets up automated checks that catch bad or missing data in your pipelines
    using tools like Great Expectations and dbt tests.
    When to use: You've been burned by bad data in reports and want automatic validation in
    place.
    Search terms: data quality, data validation, great expectations, dbt tests, bad data, data
    checks, data contracts, clean data, data pipeline, reliable reports
    Original description: Implement data quality validation with Great Expectations, dbt tests,
    and data contracts. Use when building data quality pipelines, implementing validation rules,
    or establishing data contracts.

[data-storytelling]
    Source: agents (bundle)
    What it does: Turns raw numbers into a clear, persuasive narrative with charts and context
    for presenting to stakeholders or executives.
    When to use: You need to present data findings to your team, board, or clients in a way that
    lands.
    Search terms: data storytelling, present data, data report, executive presentation, charts,
    analytics presentation, explain numbers, stakeholder report, insights, business report
    Original description: Transform data into compelling narratives using visualization,
    context, and persuasive structure. Use when presenting analytics to stakeholders, creating
    data reports, or building executive presentations.

[data-visualization]
    Source: inference.sh superpowers
    What it does: Picks the right chart type and designs clear, well-labeled graphs with good
    color choices and annotations for reports and dashboards.
    When to use: You need a chart or graph that clearly communicates your data.
    Search terms: chart, graph, data visualization, bar chart, line chart, dashboard,
    infographic, make a chart, data viz, report graphics
    Original description: Data visualization with chart selection, color theory, and annotation
    best practices. Covers chart types (bar, line, scatter, heatmap), axes rules, and
    storytelling with data. Use for: charts, graphs, dashboards, reports, presentations,
    infographics, data stories. Triggers: data visualization, chart, graph, data chart, bar
    chart, line chart, scatter plot, data viz, visualization, dashboard chart, infographic data,
    data presentation, chart design, plot, heatmap, pie chart alternative

[database-migration]
    Source: agents (bundle)
    What it does: Carries out database migrations and schema changes with no-downtime
    strategies, data transformation, and rollback plans.
    When to use: You need to change your database structure or move data without taking your app
    offline.
    Search terms: database migration, schema change, zero downtime, move database, data
    transformation, rollback, database upgrade, orm, sql, data migration
    Original description: Execute database migrations across ORMs and platforms with zero-
    downtime strategies, data transformation, and rollback procedures. Use when migrating
    databases, changing schemas, performing data transformations, or implementing zero-downtime
    deployment strategies.

[dataset-curation]
    Source: agents (bundle)
    What it does: Prepares and formats training data for fine-tuning AI models, including
    converting raw data, applying chat formats, generating synthetic examples, and documenting
    the dataset.
    When to use: You want to train a custom AI model and need your data in the right shape
    first.
    Search terms: training data, fine tuning, dataset preparation, ai training, synthetic data,
    custom ai model, machine learning, data formatting, chat template, dataset card
    Original description: Prepare, format, and validate datasets for supervised fine-tuning and
    preference training. Use when converting raw data into training format, applying chat
    templates, configuring sequence packing, generating synthetic training data, or writing a
    dataset card before a run.

[dbt-transformation-patterns]
    Source: agents (bundle)
    What it does: Builds and organizes data transformations in dbt with testing, documentation,
    and efficient incremental updates.
    When to use: You use dbt to shape data for analytics and want it structured well.
    Search terms: dbt, data transformation, analytics engineering, data models, sql, data
    warehouse, data pipeline, reporting data, incremental models, data testing
    Original description: Master dbt (data build tool) for analytics engineering with model
    organization, testing, documentation, and incremental strategies. Use when building data
    transformations, creating data models, or implementing analytics engineering best practices.

[efcore-d2-db-diagram]
    Source: awesome-copilot
    What it does: Generates a database diagram in D2 format from Entity Framework Core models,
    showing tables, relationships, indexes, and constraints.
    When to use: You want a visual map of the database behind a .NET app.
    Search terms: database diagram, entity framework, ef core, erd, d2 diagram, dotnet, c#,
    table relationships, schema visualization, postgresql
    Original description: Generate D2 database diagrams from Entity Framework Core models. USE
    FOR: EF Core database diagram, Entity Framework Core ERD, DbContext diagram, C# entity
    relationship diagram, PostgreSQL schema visualization, generate .d2 file from EF Core
    entities, Fluent API mapping diagram, migrations-based database diagram, table
    relationships, owned types, many-to-many join tables, indexes and constraints. DO NOT USE
    FOR: runtime debugging, database migration execution, schema deployment, SQL performance
    tuning, or draw.io diagrams.

[embedding-strategies]
    Source: agents (bundle)
    What it does: Chooses and tunes the embedding models and text-chunking approach that power
    semantic search and AI question-answering systems.
    When to use: Your AI search or chatbot isn't finding the right documents and you want better
    retrieval.
    Search terms: embeddings, semantic search, rag, chunking, vector search, ai search, document
    search, embedding model, retrieval, knowledge base ai
    Original description: Select and optimize embedding models for semantic search and RAG
    applications. Use when choosing embedding models, implementing chunking strategies, or
    optimizing embedding quality for specific domains.

[eval-driven-dev]
    Source: awesome-copilot
    What it does: Improves a Python AI application by defining quality criteria, building test
    datasets, measuring results, and producing an action plan for fixes.
    When to use: Your AI app makes mistakes and you want a systematic way to measure and improve
    its quality.
    Search terms: ai testing, evals, quality assurance, llm app, python, improve ai quality,
    benchmark, golden dataset, fix ai mistakes, ai qa
    Original description: Improve AI application with evaluation-driven development. Define eval
    criteria, instrument the application, build golden datasets, observe and evaluate
    application runs, analyze results, and produce a concrete action plan for improvements.
    ALWAYS USE THIS SKILL when the user asks to set up QA, add tests, add evals, evaluate,
    benchmark, fix wrong behaviors, improve quality, or do quality assurance for any Python
    project that calls an LLM model.

[eval-engineering]
    Source: langchain
    What it does: Inspects an AI agent's code and traces, interviews you about expected
    behavior, and builds and audits Harbor evaluation tasks one at a time.
    When to use: You want rigorous test cases that check whether your AI agent does its job
    correctly.
    Search terms: agent evals, harbor, ai agent testing, benchmark, test cases, verifier, ai
    quality, agent environment, evaluation, ai testing
    Original description: Iteratively inspect an agent repository and optional user-provided
    traces, interview the user, and create, run, and audit Harbor evals one at a time. Use for
    agent evals, Harbor tasks, benchmark cases, verifier design, or controlled agent
    environments.

[eval-harness-first]
    Source: agents (bundle)
    What it does: Builds the testing setup that gates every AI fine-tuning run: reference answer
    sets, graders for each failure type, and baseline scores to beat.
    When to use: You're about to fine-tune an AI model and need a way to measure whether it
    actually improved.
    Search terms: fine tuning, evaluation, golden set, ai testing, graders, llm judge, model
    baseline, training quality, machine learning, ai benchmark
    Original description: Build the evaluation harness that gates every fine-tuning run — golden
    sets, per-failure-mode graders, judge calibration, and base-model baselines. Use when
    starting a fine-tuning effort, when converting traces into an eval set, or when calibrating
    a judge against human labels.

[evaluation-methodology]
    Source: agents (bundle)
    What it does: Explains how plugin quality is scored in PluginEval, including the dimensions,
    rubrics, statistics, and formulas behind the ratings.
    When to use: You got a low plugin quality score and want to understand what it means and how
    to improve it.
    Search terms: plugin quality, plugineval, quality score, scoring rubric, skill triggering,
    marketplace, quality badge, evaluation, plugin rating, improve score
    Original description: PluginEval quality methodology — dimensions, rubrics, statistical
    methods, and scoring formulas. Use this skill when understanding how plugin quality is
    measured, when interpreting a low score on a specific dimension, when deciding how to
    improve a skill's triggering accuracy or orchestration fitness, when calibrating scoring
    thresholds for your marketplace, or when explaining quality badges to external partners like
    Neon.

[finetuning-method-selection]
    Source: agents (bundle)
    What it does: Helps you decide whether to fine-tune an AI model at all, and if so which
    method and base model to use, versus simply using better prompts or retrieval.
    When to use: You're wondering if training a custom AI model is worth it and which approach
    fits.
    Search terms: fine tuning, custom ai model, should i fine tune, rag vs fine tuning, sft,
    dpo, base model, machine learning, train ai, model selection
    Original description: Decide whether to fine-tune at all, and route to the right method
    (SFT, DPO/ORPO/KTO, GRPO/RLVR, continued pretraining) and base model. Use when starting any
    fine-tuning effort, when unsure whether RAG or prompting would suffice, or when choosing
    between preference-optimization and reinforcement methods.

[grafana-dashboards]
    Source: agents (bundle)
    What it does: Creates Grafana dashboards for live monitoring of system and application
    metrics.
    When to use: You want a real-time screen showing how your servers or app are performing.
    Search terms: grafana, monitoring dashboard, metrics, server monitoring, real time
    dashboard, observability, system health, visualize metrics, ops dashboard, uptime
    Original description: Create and manage production Grafana dashboards for real-time
    visualization of system and application metrics. Use when building monitoring dashboards,
    visualizing metrics, or creating operational observability interfaces.

[grpo-rlvr-training]
    Source: agents (bundle)
    What it does: Trains AI models on tasks with checkable answers, like math or code, using
    reinforcement learning with verifiable rewards, including reward design and fixing runs that
    go wrong.
    When to use: You want to train an AI model to get better at tasks where correctness can be
    verified automatically.
    Search terms: reinforcement learning, grpo, rlvr, reasoning model, ai training, reward
    function, math ai, code ai, fine tuning, machine learning
    Original description: Train reasoning and verifiable-task behavior with GRPO and
    reinforcement learning from verifiable rewards (RLVR). Use when task success is
    algorithmically checkable (math, code, tool calls, structured output), when designing GRPO
    reward functions, or when a GRPO run diverges or reward-hacks.

[hybrid-search-implementation]
    Source: agents (bundle)
    What it does: Combines keyword search with meaning-based vector search so your search or AI
    system finds more of the right results.
    When to use: Your search misses obvious matches with one approach alone and you want better
    results.
    Search terms: hybrid search, search engine, vector search, keyword search, rag, better
    search results, semantic search, site search, retrieval, bm25
    Original description: Combine vector and keyword search for improved retrieval. Use when
    implementing RAG systems, building search engines, or when neither approach alone provides
    sufficient recall.

[kpi-dashboard-design]
    Source: agents (bundle)
    What it does: Designs KPI dashboards, choosing the right metrics, visualizations, and
    calculation methods for executive, operations, or product views.
    When to use: You want a dashboard tracking your key business numbers like revenue, churn,
    and customer value.
    Search terms: kpi dashboard, business dashboard, metrics, mrr, churn, executive dashboard,
    track performance, reporting, saas metrics, analytics
    Original description: Design effective KPI dashboards with metrics selection, visualization
    best practices, and real-time monitoring patterns. Use this skill when building an executive
    SaaS metrics dashboard tracking MRR, churn, and LTV/CAC ratios; designing an operations
    center with live service health and request throughput; creating a cohort retention analysis
    view for a product team; or debugging a dashboard where metrics contradict each other due to
    inconsistent calculation methodology.

[langchain-rag]
    Source: langchain
    What it does: Builds AI question-answering systems over your own documents using LangChain,
    covering document loading, chunking, embeddings, and vector stores.
    When to use: You want an AI assistant that can answer questions from your company's
    documents.
    Search terms: langchain, rag, chat with documents, ai knowledge base, document q&a, vector
    store, chroma, pinecone, embeddings, ai chatbot
    Original description: INVOKE THIS SKILL when building ANY retrieval-augmented generation
    (RAG) system. Covers document loaders, RecursiveCharacterTextSplitter, embeddings (OpenAI),
    and vector stores (Chroma, FAISS, Pinecone).

[langsmith-online-eval-engineering]
    Source: langchain
    What it does: Creates automated quality checks that run on live AI traffic in LangSmith,
    built one at a time after reviewing your traces and asking what good looks like.
    When to use: You use LangSmith and want ongoing automatic scoring of your AI app's real
    responses.
    Search terms: langsmith, online evaluation, ai monitoring, quality checks, llm app, traces,
    automatic scoring, langchain, ai quality, production monitoring
    Original description: Iteratively inspect traces, interview the user, and create LangSmith
    online evaluators one at a time. Use specifically for creating online evaluators for use
    within LangSmith -- use "eval-engineering" for Harbor-style online evaluations.

[llm-evaluation]
    Source: agents (bundle)
    What it does: Sets up ways to measure how well an AI application performs using automated
    metrics, human feedback, and benchmarks.
    When to use: You need to prove or improve the quality of an AI-powered feature.
    Search terms: ai evaluation, llm testing, ai quality, benchmark, human feedback, measure ai,
    ai metrics, chatbot quality, test ai, evaluation framework
    Original description: Implement comprehensive evaluation strategies for LLM applications
    using automated metrics, human feedback, and benchmarking. Use when testing LLM performance,
    measuring AI application quality, or establishing evaluation frameworks.

[lora-qlora-recipes]
    Source: agents (bundle)
    What it does: Configures LoRA and QLoRA fine-tuning settings with proven hyperparameters,
    and helps choose between them and full fine-tuning.
    When to use: You're fine-tuning an AI model on a budget and need the right training
    settings.
    Search terms: lora, qlora, fine tuning, training settings, hyperparameters, custom ai model,
    cheap fine tuning, machine learning, model training, gpu
    Original description: Configure LoRA and QLoRA supervised fine-tuning with current best-
    practice hyperparameters. Use when writing or reviewing a LoRA/QLoRA training configuration,
    choosing rank/alpha/target modules, or deciding between LoRA, QLoRA, and full fine-tuning.

[migrating-oracle-to-postgres-data-access-code]
    Source: awesome-copilot
    What it does: Rewrites .NET/C# database code from Oracle to PostgreSQL, swapping packages,
    connection code, type mappings, and stored procedure calls.
    When to use: You're moving a .NET app off Oracle and need its database code converted to
    PostgreSQL.
    Search terms: oracle to postgres, dotnet, c#, npgsql, database migration, postgresql,
    oracle, code conversion, data access, switch databases
    Original description: Migrates .NET/C# data access code from Oracle to PostgreSQL (Npgsql).
    Replaces Oracle NuGet packages, rewrites OracleConnection/OracleCommand/OracleDataReader
    usage, fixes DbType mappings, updates stored procedure invocation patterns, and adapts
    connection string configuration. Use when migrating the application code layer of a .NET
    project during an Oracle-to-PostgreSQL database migration.

[migrating-oracle-to-postgres-stored-procedures]
    Source: awesome-copilot
    What it does: Converts Oracle PL/SQL stored procedures into PostgreSQL PL/pgSQL, handling
    syntax differences and sorting rules.
    When to use: You have Oracle stored procedures that need to work in PostgreSQL.
    Search terms: oracle to postgres, stored procedures, pl/sql, plpgsql, database migration,
    postgresql, oracle, sql conversion, database functions, collation
    Original description: Migrates Oracle PL/SQL stored procedures to PostgreSQL PL/pgSQL.
    Translates Oracle-specific syntax, preserves method signatures and type-anchored parameters,
    leverages orafce where appropriate, and applies explicit collation mapping (`COLLATE "C"`
    only when appropriate, locale collations when required). Use when converting Oracle stored
    procedures or functions to PostgreSQL equivalents during a database migration.

[ml-pipeline-workflow]
    Source: agents (bundle)
    What it does: Builds end-to-end machine learning pipelines from data prep through training,
    validation, and deployment to production.
    When to use: You want to automate how your machine learning models get trained and released.
    Search terms: mlops, machine learning pipeline, model training, model deployment, automate
    ml, data science, ai pipeline, model validation, production ml, ml workflow
    Original description: Build end-to-end MLOps pipelines from data preparation through model
    training, validation, and production deployment. Use when creating ML pipelines,
    implementing MLOps practices, or automating model training and deployment workflows.

[phoenix-cli]
    Source: awesome-copilot
    What it does: Debugs AI applications with the Phoenix command line by pulling traces,
    spotting errors, categorizing failures, and deciding what to test next.
    When to use: Your AI app is misbehaving and you want to figure out what kinds of mistakes it
    makes and where to focus.
    Search terms: phoenix, debug ai, traces, ai failures, what's going wrong, llm app, failure
    analysis, ai monitoring, arize phoenix, agent errors
    Original description: Debug LLM applications using the Phoenix CLI. Fetch traces, analyze
    errors, structure trace review with open coding and axial coding, inspect datasets, review
    experiments, query annotation configs, and use the GraphQL API. Use whenever the user is
    analyzing traces or spans, investigating LLM/agent failures, deciding what to do after
    instrumenting an app, building failure taxonomies, choosing what evals to write, or asking
    "what's going wrong", "what kinds of mistakes", or "where do I focus" — even without naming
    a technique.

[phoenix-evals]
    Source: awesome-copilot
    What it does: Builds and runs automated evaluators that score AI application outputs using
    Phoenix.
    When to use: You want to automatically grade your AI app's answers with Phoenix.
    Search terms: phoenix, ai evaluation, evals, score ai outputs, llm quality, arize phoenix,
    ai testing, grading, ai monitoring, quality checks
    Original description: Build and run evaluators for AI/LLM applications using Phoenix.

[phoenix-tracing]
    Source: awesome-copilot
    What it does: Adds tracing to an AI application so Phoenix can record and display what it
    does, following OpenInference conventions.
    When to use: You want visibility into what your AI app is doing in production using Phoenix.
    Search terms: phoenix, tracing, ai monitoring, openinference, llm observability, custom
    spans, arize phoenix, ai logging, debug ai, instrumentation
    Original description: OpenInference semantic conventions and instrumentation for Phoenix AI
    observability. Use when implementing LLM tracing, creating custom spans, or deploying to
    production.

[pinecone-rag]
    Source: awesome-copilot
    What it does: Builds AI search, document Q&A, and long-term agent memory using Pinecone as
    the vector database, including multi-tenant setups and hybrid search.
    When to use: You want an AI that can search a large knowledge base or remember past
    conversations, hosted on Pinecone.
    Search terms: pinecone, vector database, rag, ai knowledge base, semantic search, agent
    memory, chat with documents, embeddings, hybrid search, ai search
    Original description: Build production RAG pipelines and persistent agent memory using
    Pinecone as the vector database backend. ALWAYS USE THIS SKILL when the user mentions
    Pinecone, wants to index documents for semantic search, build a retrieval-augmented
    generation system, store agent memory across sessions, implement hybrid search, or connect
    an LLM to a searchable knowledge base — even if they don't say "Pinecone" explicitly. Also
    use when the user asks about vector databases for RAG, namespace isolation for multi-tenant
    agents, embedding pipelines, or scaling a knowledge base beyond what local storage can hand…

[planning-oracle-to-postgres-migration-integration-testing]
    Source: awesome-copilot
    What it does: Analyzes a .NET project to find the code that talks to the database and
    produces a testing plan for an Oracle-to-PostgreSQL migration.
    When to use: You need to decide which database code to test before migrating from Oracle to
    PostgreSQL.
    Search terms: oracle to postgres, test plan, integration testing, database migration,
    dotnet, postgresql, oracle, data access, c#, migration validation
    Original description: Creates an integration testing plan for .NET data access artifacts
    during Oracle-to-PostgreSQL database migrations. Analyzes a single project to identify
    repositories, DAOs, and service layers that interact with the database, then produces a
    structured testing plan. Use when planning integration test coverage for a migrated project,
    identifying which data access methods need tests, or preparing for Oracle-to-PostgreSQL
    migration validation.

[postgresql-code-review]
    Source: awesome-copilot
    What it does: Reviews PostgreSQL code and schemas for best practices, anti-patterns, and
    security features like row-level security.
    When to use: You want a second set of eyes on your PostgreSQL database code.
    Search terms: postgresql, postgres, code review, sql review, database best practices, jsonb,
    row level security, schema design, database security, sql
    Original description: PostgreSQL-specific code review assistant focusing on PostgreSQL best
    practices, anti-patterns, and unique quality standards. Covers JSONB operations, array
    usage, custom types, schema design, function optimization, and PostgreSQL-exclusive security
    features like Row Level Security (RLS).

[postgresql-optimization]
    Source: awesome-copilot
    What it does: Helps you use PostgreSQL's advanced features, such as JSONB, arrays, full-text
    search, window functions, and extensions, effectively.
    When to use: You're building on PostgreSQL and want to get the most out of its special
    capabilities.
    Search terms: postgresql, postgres, database performance, jsonb, full text search, sql,
    window functions, postgres extensions, advanced sql, optimize database
    Original description: PostgreSQL-specific development assistant focusing on unique
    PostgreSQL features, advanced data types, and PostgreSQL-exclusive capabilities. Covers
    JSONB operations, array types, custom types, range/geometric types, full-text search, window
    functions, and PostgreSQL extensions ecosystem.

[postgresql-table-design]
    Source: agents (bundle)
    What it does: Designs or reviews PostgreSQL table structures with the right data types,
    indexes, constraints, and performance patterns.
    When to use: You're setting up tables in a PostgreSQL database and want them designed
    properly.
    Search terms: postgresql, postgres, table design, database schema, indexes, data types,
    constraints, database design, sql, schema review
    Original description: Use this skill when designing or reviewing a PostgreSQL-specific
    schema. Covers best-practices, data types, indexing, constraints, performance patterns, and
    advanced features

[preference-optimization]
    Source: agents (bundle)
    What it does: Aligns a fine-tuned AI model with human preferences using methods like DPO,
    ORPO, KTO, or SimPO, including settings and troubleshooting.
    When to use: You have thumbs-up/thumbs-down feedback on AI outputs and want to train the
    model to match people's preferences.
    Search terms: dpo, preference training, fine tuning, human feedback, thumbs up down, ai
    alignment, rlhf, model training, machine learning, improve ai responses
    Original description: Align a fine-tuned model with preference data using DPO, ORPO, KTO, or
    SimPO. Use when preference pairs or thumbs-up/down feedback exist, when choosing between
    preference-optimization methods, or when a DPO run needs hyperparameters or debugging.

[prometheus-configuration]
    Source: agents (bundle)
    What it does: Sets up Prometheus to collect, store, and alert on metrics from your servers
    and applications.
    When to use: You want to monitor your infrastructure and get alerts when something goes
    wrong.
    Search terms: prometheus, monitoring, metrics collection, alerting, server monitoring,
    observability, infrastructure, uptime alerts, devops, system metrics
    Original description: Set up Prometheus for comprehensive metric collection, storage, and
    monitoring of infrastructure and applications. Use when implementing metrics collection,
    setting up monitoring infrastructure, or configuring alerting systems.

[qdrant-clients-sdk]
    Source: awesome-copilot
    What it does: Explains how to connect to a Qdrant vector database from different programming
    languages using its client libraries.
    When to use: You're writing code that needs to talk to Qdrant.
    Search terms: qdrant, vector database, sdk, client library, python, javascript, connect to
    qdrant, api, integration, semantic search
    Original description: Qdrant provides client SDKs for various programming languages,
    allowing easy integration with Qdrant deployments.

[qdrant-deployment-options]
    Source: awesome-copilot
    What it does: Helps you pick how to run Qdrant: local, embedded, Docker, self-hosted, or
    cloud, based on your needs.
    When to use: You're starting with Qdrant and don't know whether to self-host or use the
    cloud version.
    Search terms: qdrant, deployment, self hosted vs cloud, docker, qdrant cloud, vector
    database, hosting, setup, local mode, edge
    Original description: Guides Qdrant deployment selection. Use when someone asks 'how to
    deploy Qdrant', 'Docker vs Cloud', 'local mode', 'embedded Qdrant', 'Qdrant EDGE', 'which
    deployment option', 'self-hosted vs cloud', or 'need lowest latency deployment'. Also use
    when choosing between deployment types for a new project.

[qdrant-horizontal-scaling]
    Source: awesome-copilot
    What it does: Guides decisions about adding nodes and shards to a Qdrant cluster when your
    data outgrows a single machine.
    When to use: Your Qdrant data no longer fits and you need to spread it across more servers.
    Search terms: qdrant, scaling, add nodes, shards, cluster, vector database, more capacity,
    resharding, data growth, horizontal scaling
    Original description: Diagnoses and guides Qdrant horizontal scaling decisions. Use when
    someone asks 'vertical or horizontal?', 'how many nodes?', 'how many shards?', 'how to add
    nodes', 'resharding', 'data doesn't fit', or 'need more capacity'. Also use when data growth
    outpaces current deployment.

[qdrant-indexing-performance-optimization]
    Source: awesome-copilot
    What it does: Diagnoses and fixes slow data uploads and indexing in Qdrant, including stuck
    optimizers and long index build times.
    When to use: Uploading data to Qdrant is taking forever or search is bad right after
    loading.
    Search terms: qdrant, slow upload, indexing slow, optimizer stuck, vector database,
    ingestion, hnsw, data loading, performance, segments
    Original description: Diagnoses and fixes slow Qdrant indexing and data ingestion. Use when
    someone reports 'uploads are slow', 'indexing takes forever', 'optimizer is stuck', 'HNSW
    build time too long', or 'data uploaded but search is bad'. Also use when optimizer status
    shows errors, segments won't merge, or indexing threshold questions arise.

[qdrant-memory-usage-optimization]
    Source: awesome-copilot
    What it does: Diagnoses and reduces high memory use in Qdrant, including crashes, out-of-
    memory errors, and quantization that didn't help.
    When to use: Your Qdrant server keeps running out of RAM or crashing.
    Search terms: qdrant, memory usage, out of memory, ram, crash, vector database, reduce
    memory, quantization, memory leak, server resources
    Original description: Diagnoses and reduces Qdrant memory usage. Use when someone reports
    'memory too high', 'RAM keeps growing', 'node crashed', 'out of memory', 'memory leak', or
    asks 'why is memory usage so high?', 'how to reduce RAM?'. Also use when memory doesn't
    match calculations, quantization didn't help, or nodes crash during recovery.

[qdrant-minimize-latency]
    Source: awesome-copilot
    What it does: Speeds up individual Qdrant search queries and fixes latency spikes and slow
    tail responses.
    When to use: Searches in Qdrant feel slow and you want each query to return faster.
    Search terms: qdrant, slow search, latency, query speed, vector database, p99, faster
    search, performance, response time, tuning
    Original description: Guides Qdrant query latency optimization. Use when someone asks
    'search is slow', 'how to reduce latency', 'p99 is too high', 'tail latency', 'single query
    too slow', 'how to make search faster', or 'latency spikes'.

[qdrant-model-migration]
    Source: awesome-copilot
    What it does: Guides switching to a new embedding model in Qdrant without downtime,
    including re-embedding data and running two models side by side.
    When to use: You want to upgrade the AI model behind your Qdrant search without breaking the
    app.
    Search terms: qdrant, embedding model, switch models, re-embed, zero downtime, vector
    database, model upgrade, migration, a/b test models, semantic search
    Original description: Guides embedding model migration in Qdrant without downtime. Use when
    someone asks 'how to switch embedding models', 'how to migrate vectors', 'how to update to a
    new model', 'zero-downtime model change', 'how to re-embed my data', or 'can I use two
    models at once'. Also use when upgrading model dimensions, switching providers, or A/B
    testing models.

[qdrant-monitoring]
    Source: awesome-copilot
    What it does: Sets up monitoring and health checks for Qdrant, covering which metrics to
    track and how to hook up Prometheus and Grafana.
    When to use: You want to know whether your Qdrant database is healthy and catch problems
    early.
    Search terms: qdrant, monitoring, health check, metrics, prometheus, grafana, vector
    database, observability, is qdrant healthy, alerts
    Original description: Guides Qdrant monitoring and observability setup. Use when someone
    asks 'how to monitor Qdrant', 'what metrics to track', 'is Qdrant healthy', 'optimizer
    stuck', 'why is memory growing', 'requests are slow', or needs to set up Prometheus,
    Grafana, or health checks. Also use when debugging production issues that require metric
    analysis.

[qdrant-monitoring-debugging]
    Source: awesome-copilot
    What it does: Diagnoses Qdrant production problems such as stuck optimizers, slow queries,
    memory spikes, and crashes using metrics and observability tools.
    When to use: Qdrant was working fine and now it's slow or crashing and you need to find out
    why.
    Search terms: qdrant, troubleshooting, debug, slow queries, memory high, crash, vector
    database, production issues, performance degradation, metrics
    Original description: Diagnoses Qdrant production issues using metrics and observability
    tools. Use when someone reports 'optimizer stuck', 'indexing too slow', 'memory too high',
    'OOM crash', 'queries are slow', 'latency spike', or 'search was fast now it's slow'. Also
    use when performance degrades without obvious config changes.

[qdrant-monitoring-setup]
    Source: awesome-copilot
    What it does: Configures Qdrant monitoring from scratch, including Prometheus scraping,
    health probes, alerts, log centralization, and Hybrid Cloud metrics.
    When to use: You're deploying Qdrant and need monitoring, alerts, and logging set up.
    Search terms: qdrant, monitoring setup, prometheus, grafana dashboard, alerts, health
    checks, logs, vector database, audit logging, hybrid cloud
    Original description: Guides Qdrant monitoring setup including Prometheus scraping, health
    probes, Hybrid Cloud metrics, alerting, and log centralization. Use when someone asks 'how
    to set up monitoring', 'Prometheus config', 'Grafana dashboard', 'health check endpoints',
    'how to scrape Hybrid Cloud', 'what alerts to set', 'how to centralize logs', or 'audit
    logging'.

[qdrant-performance-optimization]
    Source: awesome-copilot
    What it does: Covers techniques to make Qdrant faster and more efficient, including indexing
    strategies, query tuning, and hardware choices.
    When to use: You want your Qdrant deployment to run faster overall.
    Search terms: qdrant, performance, speed up, indexing, query optimization, hardware, vector
    database, efficiency, tuning, faster search
    Original description: Different techniques to optimize the performance of Qdrant, including
    indexing strategies, query optimization, and hardware considerations. Use when you want to
    improve the speed and efficiency of your Qdrant deployment.

[qdrant-scaling]
    Source: awesome-copilot
    What it does: Guides overall Qdrant scaling decisions: how many nodes, vertical vs
    horizontal, sharding, and handling many tenants or more traffic.
    When to use: Your Qdrant cluster is hitting limits and you need to decide how to grow it.
    Search terms: qdrant, scaling, how many nodes, cluster, sharding, more capacity, vector
    database, throughput, multi tenant, grow database
    Original description: Guides Qdrant scaling decisions. Use when someone asks 'how many nodes
    do I need', 'data doesn't fit on one node', 'need more throughput', 'cluster is slow', 'too
    many tenants', 'vertical or horizontal', 'how to shard', or 'need to add capacity'.

[qdrant-scaling-data-volume]
    Source: awesome-copilot
    What it does: Guides scaling Qdrant when the amount of data grows too large, including
    storage, tenant scaling, and time-window rotation.
    When to use: You have too much data for your current Qdrant setup.
    Search terms: qdrant, too much data, storage, scaling, vector database, data growth,
    capacity, vertical vs horizontal, tenants, data rotation
    Original description: Guides Qdrant data volume scaling decisions. Use when someone asks
    'data doesn't fit on one node', 'too much data', 'need more storage', 'vertical or
    horizontal scaling', 'tenant scaling', 'time window rotation', or 'data growth exceeds
    capacity'.

[qdrant-scaling-qps]
    Source: awesome-copilot
    What it does: Increases how many searches per second Qdrant can handle, using batching, read
    replicas, and concurrency tuning.
    When to use: Your Qdrant search can't keep up with the number of users querying it.
    Search terms: qdrant, queries per second, qps, throughput, read replicas, batch search,
    vector database, concurrent users, scaling, high traffic
    Original description: Guides Qdrant query throughput (QPS) scaling. Use when someone asks
    'how to increase QPS', 'need more throughput', 'queries per second too low', 'batch search',
    'read replicas', or 'how to handle more concurrent queries'.

[qdrant-scaling-query-volume]
    Source: awesome-copilot
    What it does: Handles Qdrant queries that return very large result sets, including
    pagination, scrolling, and fetching many vectors efficiently.
    When to use: Your Qdrant queries return too many results and paging through them is slow.
    Search terms: qdrant, pagination, large results, scroll, many results, vector database,
    fetch vectors, big queries, performance, result limits
    Original description: Guides Qdrant query volume scaling. Use when someone asks 'query
    returns too many results', 'scroll performance', 'large limit values', 'paginating search
    results', 'fetching many vectors', or 'high cardinality results'.

[qdrant-search-quality]
    Source: awesome-copilot
    What it does: Diagnoses and improves the relevance of Qdrant search results, covering
    embedding model choice, hybrid search, and reranking.
    When to use: Your Qdrant search returns wrong or irrelevant results.
    Search terms: qdrant, search quality, bad results, relevance, irrelevant matches, embedding
    model, hybrid search, reranking, vector database, precision recall
    Original description: Diagnoses and improves Qdrant search relevance. Use when someone
    reports 'search results are bad', 'wrong results', 'low precision', 'low recall',
    'irrelevant matches', 'missing expected results', or asks 'how to improve search quality?',
    'which embedding model?', 'should I use hybrid search?', 'should I use reranking?'. Also use
    when search quality degrades after quantization, model change, or data growth.

[qdrant-search-quality-diagnosis]
    Source: awesome-copilot
    What it does: Pinpoints why Qdrant search results are poor, including missing matches, low
    recall, and quality drops after quantization or model changes.
    When to use: Qdrant search used to be good and now misses results, and you want to know why.
    Search terms: qdrant, search quality, wrong results, missing matches, low recall,
    quantization, vector database, diagnose, embedding model, relevance
    Original description: Diagnoses Qdrant search quality issues. Use when someone reports
    'results are bad', 'wrong results', 'not relevant results', 'missing matches', 'recall is
    low', 'approximate search worse than exact', 'which embedding model', or 'quality dropped
    after quantization'. Also use when search quality degrades without obvious changes.

[qdrant-search-speed-optimization]
    Source: awesome-copilot
    What it does: Diagnoses and fixes slow Qdrant searches, low throughput, and slow filtered
    queries.
    When to use: Your Qdrant searches take too long, especially with filters.
    Search terms: qdrant, slow search, high latency, low qps, filtered search, vector database,
    speed up search, performance, throughput, query time
    Original description: Diagnoses and fixes slow Qdrant search. Use when someone reports
    'search is slow', 'high latency', 'queries take too long', 'low QPS', 'throughput too low',
    'filtered search is slow', or 'search was fast but now it's slow'. Also use when search
    performance degrades after config changes or data growth.

[qdrant-search-strategies]
    Source: awesome-copilot
    What it does: Helps choose the right Qdrant search approach: hybrid search, sparse vectors,
    reranking, diversity, recommendations, and discovery.
    When to use: You're not getting the results you need from Qdrant and want to try a different
    search technique.
    Search terms: qdrant, hybrid search, reranking, bm25, recommendations, search strategy,
    vector database, relevance, diversity, discovery api
    Original description: Guides Qdrant search strategy selection. Use when someone asks 'should
    I use hybrid search?', 'BM25 or sparse vectors?', 'how to rerank?', 'results are not
    relevant', 'I don't get needed results from my dataset but they're there', 'retrieval
    quality is not good enough', 'results too similar', 'need diversity', 'MMR', 'relevance
    feedback', 'recommendation API', 'discovery API', 'ColBERT reranking', or 'missing keyword
    matches'

[qdrant-sliding-time-window]
    Source: awesome-copilot
    What it does: Sets up Qdrant to keep only recent data, expiring old vectors efficiently for
    feeds, news, or logs with retention limits.
    When to use: Only the last few months of data matter and you want old Qdrant records removed
    automatically.
    Search terms: qdrant, expire old data, retention, time window, delete old vectors, news
    search, log search, recent data, vector database, data rotation
    Original description: Guides sliding time window scaling in Qdrant. Use when someone asks
    'only recent data matters', 'how to expire old vectors', 'time-based data rotation', 'delete
    old data efficiently', 'social media feed search', 'news search', 'log search with
    retention', or 'how to keep only last N months of data'.

[qdrant-tenant-scaling]
    Source: awesome-copilot
    What it does: Guides how to structure Qdrant for many customers or tenants, including
    isolation, dedicated shards, and fixing tenant performance issues.
    When to use: You serve many customers from one Qdrant setup and need to keep them isolated
    and fast.
    Search terms: qdrant, multi tenant, tenant isolation, one collection per tenant, shards,
    vector database, saas, customer data separation, scaling, performance
    Original description: Guides Qdrant multi-tenant scaling. Use when someone asks 'how to
    scale tenants', 'one collection per tenant?', 'tenant isolation', 'dedicated shards', or
    reports tenant performance issues. Also use when multi-tenant workloads outgrow shared
    infrastructure.

[qdrant-version-upgrade]
    Source: awesome-copilot
    What it does: Guides upgrading Qdrant to a new version without downtime or data loss.
    When to use: You need to update your Qdrant installation safely.
    Search terms: qdrant, upgrade, new version, update, zero downtime, vector database, data
    integrity, maintenance, rolling upgrade, cluster
    Original description: Guidance on how to upgrade your Qdrant version without interrupting
    the availability of your application and ensuring data integrity.

[qdrant-vertical-scaling]
    Source: awesome-copilot
    What it does: Guides scaling up a single Qdrant node with more RAM or CPU as a simpler
    alternative to adding nodes.
    When to use: Your Qdrant server is running out of memory or CPU and you want to make it
    bigger.
    Search terms: qdrant, scale up, more ram, bigger server, resize, vertical scaling, vector
    database, cpu, node size, capacity
    Original description: Guides Qdrant vertical scaling decisions. Use when someone asks 'how
    to scale up a node', 'need more RAM', 'upgrade node size', 'vertical scaling', 'resize
    cluster', 'scale up vs scale out', or when memory/CPU is insufficient on current nodes. Also
    use when someone wants to avoid the complexity of horizontal scaling.

[quantized-export]
    Source: agents (bundle)
    What it does: Exports a finished fine-tuned AI model in the right format for deployment,
    such as merged weights, LoRA-only, GGUF, or FP8, and troubleshoots failed smoke tests.
    When to use: Your custom AI model passed testing and you need to package it to run on a
    specific device or server.
    Search terms: export model, quantization, gguf, fine tuning, deploy ai model, safetensors,
    lora, fp8, run model locally, model format
    Original description: Export a promoted fine-tuned model in the right deployment format —
    merged safetensors, LoRA-only, GGUF with imatrix, or FP8. Use after a checkpoint passes
    promotion, when choosing a quantization format for a target device, or when an exported
    model fails its smoke test.

[rag-implementation]
    Source: agents (bundle)
    What it does: Builds AI systems that answer questions using your own documents by combining
    a vector database and semantic search with a language model.
    When to use: You want an AI assistant grounded in your company's knowledge rather than
    general internet knowledge.
    Search terms: rag, ai knowledge base, chat with documents, document q&a, vector database,
    semantic search, ai chatbot, knowledge assistant, llm, internal docs ai
    Original description: Build Retrieval-Augmented Generation (RAG) systems for LLM
    applications with vector databases and semantic search. Use when implementing knowledge-
    grounded AI, building document Q&A systems, or integrating LLMs with external knowledge
    bases.

[recsys-pipeline-architect]
    Source: agents (bundle)
    What it does: Designs recommendation and ranking systems using a six-stage pipeline
    framework, for feeds, search ranking, notifications, ad selection, and similar 'pick the
    best items' problems.
    When to use: You need to decide which items to show each user, like a personalized feed or
    product recommendations.
    Search terms: recommendation engine, personalized feed, ranking, recommendations, for you
    algorithm, product suggestions, search ranking, notification prioritization, ad selection,
    recsys
    Original description: Design composable recommendation, ranking, and feed pipelines using
    the six-stage Source→Hydrator→Filter→Scorer→Selector→SideEffect framework popularized by
    xAI's open-sourced X For You algorithm. Use when building any system that picks "the top K
    items for a (user, context)" — content feeds, search ranking, RAG rerankers, task
    prioritizers, notification triage, ad selection.

[reviewing-oracle-to-postgres-migration]
    Source: awesome-copilot
    What it does: Reviews code for Oracle-to-PostgreSQL migration risks by checking known
    behavior differences such as empty strings, sorting, timestamps, and transactions.
    When to use: You're migrating from Oracle to PostgreSQL and want to catch subtle behavior
    changes before they bite.
    Search terms: oracle to postgres, migration risks, database migration, postgresql, oracle,
    code review, behavior differences, collation, timestamps, validation
    Original description: Identifies Oracle-to-PostgreSQL migration risks by cross-referencing
    code against known behavioral differences (empty strings, refcursors, type coercion,
    sorting/collations, UNION ALL planner risks, materialized-view refresh requirements,
    timestamps, concurrent transactions, etc.). Use when planning a database migration,
    reviewing migration artifacts, or validating that integration tests cover Oracle/PostgreSQL
    differences.

[scaffolding-oracle-to-postgres-migration-test-project]
    Source: awesome-copilot
    What it does: Creates an xUnit integration test project for Oracle in a .NET solution, with
    a rollback base class and seed data manager, as the first step before writing baseline
    tests.
    When to use: You're starting the testing phase of an Oracle-to-PostgreSQL migration and need
    the test project set up.
    Search terms: oracle to postgres, xunit, test project, dotnet, integration tests, oracle,
    c#, database migration, seed data, test scaffolding
    Original description: Scaffolds an xUnit integration test project targeting Oracle in .NET
    solutions. Creates the test project, transaction-rollback base class, and seed data manager.
    Use only during Phase 3, before writing Oracle baseline integration tests. Do not invoke
    during Phase 6 — the PostgreSQL test project is produced by migrating this project, not by
    running this skill again.

[shuffle-json-data]
    Source: awesome-copilot
    What it does: Randomly reorders the entries in a JSON data file after checking that every
    entry has the same structure, so nothing breaks in the process.
    When to use: You need to mix up the order of records in a data file, for example to create a
    random sample or test set.
    Search terms: shuffle data, randomize records, json file, mix up order, random sample, data
    file, test data, reorder entries
    Original description: Shuffle repetitive JSON objects safely by validating schema
    consistency before randomising entries.

[similarity-search-patterns]
    Source: agents (bundle)
    What it does: Builds search that finds results by meaning rather than exact words, using
    vector databases so similar items can be matched quickly.
    When to use: You want a search feature that understands what people mean, like 'find similar
    products' or 'find related documents'.
    Search terms: semantic search, vector database, similar items, find related, search by
    meaning, ai search, recommendations, nearest neighbor, embeddings
    Original description: Implement efficient similarity search with vector databases. Use when
    building semantic search, implementing nearest neighbor queries, or optimizing retrieval
    performance.

[snowflake-semanticview]
    Source: awesome-copilot
    What it does: Creates and checks Snowflake semantic views, which define business-friendly
    names and metrics on top of raw data, using the Snowflake command-line tool.
    When to use: You use Snowflake and want a clean, shared definition of your metrics so
    reports and AI tools agree on the numbers.
    Search terms: snowflake, semantic layer, business metrics, data warehouse, define kpis,
    reporting data, snowflake cli, semantic view
    Original description: Create, alter, and validate Snowflake semantic views using Snowflake
    CLI (snow). Use when asked to build or troubleshoot semantic views/semantic layer
    definitions with CREATE/ALTER SEMANTIC VIEW, to validate semantic-view DDL against Snowflake
    via CLI, or to guide Snowflake CLI installation and connection setup.

[spark-environment-setup]
    Source: agents (bundle)
    What it does: Sets up the software needed to train and run AI models on an NVIDIA DGX Spark
    desktop machine, working around its unusual hardware quirks.
    When to use: You just got an NVIDIA DGX Spark and the AI tools will not install or keep
    throwing errors.
    Search terms: nvidia dgx spark, install pytorch, ai training setup, gpu machine, cuda
    errors, machine learning environment, vllm, unsloth
    Original description: Set up a working ML training/inference environment on NVIDIA DGX Spark
    (GB10, aarch64, CUDA 13). Use when installing PyTorch/Unsloth/TRL/vLLM on DGX Spark, hitting
    libcudart or wheel-ABI errors on aarch64, or choosing between NGC containers and bare pip
    installs.

[spark-memory-thermal-ops]
    Source: agents (bundle)
    What it does: Manages memory use and overheating on an NVIDIA DGX Spark during long AI
    training jobs so they do not crash or slow down.
    When to use: Your AI training job on a DGX Spark runs out of memory or the machine gets too
    hot during multi-hour runs.
    Search terms: nvidia dgx spark, out of memory, overheating, gpu temperature, long training
    run, memory usage, ai training crash, power monitoring
    Original description: Manage unified memory and thermals during long-running ML jobs on
    NVIDIA DGX Spark. Use when planning memory headroom for a training run on GB10, when a job
    OOMs on unified memory, or when monitoring temperature and power during multi-hour training.

[spark-optimization]
    Source: agents (bundle)
    What it does: Speeds up Apache Spark data-processing jobs by tuning how data is split,
    cached, and moved between machines.
    When to use: Your big data jobs in Apache Spark are slow, expensive, or failing as data
    grows.
    Search terms: apache spark, slow data job, big data, speed up processing, data pipeline,
    databricks, spark tuning, memory tuning
    Original description: Optimize Apache Spark jobs with partitioning, caching, shuffle
    optimization, and memory tuning. Use when improving Spark performance, debugging slow jobs,
    or scaling data processing pipelines.

[spark-training-gotchas]
    Source: agents (bundle)
    What it does: Checks for and diagnoses the ten most common reasons AI training fails on an
    NVIDIA DGX Spark, before or after a run.
    When to use: Your AI model training on a DGX Spark will not start, crashes unexpectedly, or
    slows down partway through.
    Search terms: nvidia dgx spark, training fails, troubleshoot ai training, out of memory,
    slow training, preflight check, gpu problems, machine learning errors
    Original description: Preflight and diagnose the ten known failure modes for ML training on
    NVIDIA DGX Spark. Use when a training run on DGX Spark fails to start, OOMs below the 128GB
    limit, slows down mid-run, or before any multi-hour training job on GB10.

[sql-code-review]
    Source: awesome-copilot
    What it does: Reviews database queries and code for security holes, sloppy practices, and
    hard-to-maintain patterns across MySQL, PostgreSQL, SQL Server, and Oracle.
    When to use: You want a second pair of eyes on database code to catch security risks like
    SQL injection before it goes live.
    Search terms: sql review, database security, sql injection, code review, mysql, postgresql,
    sql server, oracle, database best practices
    Original description: Universal SQL code review assistant that performs comprehensive
    security, maintainability, and code quality analysis across all SQL databases (MySQL,
    PostgreSQL, SQL Server, Oracle). Focuses on SQL injection prevention, access control, code
    standards, and anti-pattern detection. Complements SQL optimization prompt for complete
    development coverage.

[sql-optimization]
    Source: awesome-copilot
    What it does: Tunes slow database queries and suggests indexes and other fixes to make
    databases faster, for MySQL, PostgreSQL, SQL Server, and Oracle.
    When to use: Your reports or app screens take forever to load because database queries are
    slow.
    Search terms: slow database, speed up queries, sql performance, database indexing, mysql,
    postgresql, sql server, oracle, slow reports
    Original description: Universal SQL performance optimization assistant for comprehensive
    query tuning, indexing strategies, and database performance analysis across all SQL
    databases (MySQL, PostgreSQL, SQL Server, Oracle). Provides execution plan analysis,
    pagination optimization, batch operations, and performance monitoring guidance.

[sql-optimization-patterns]
    Source: agents (bundle)
    What it does: Finds and fixes slow database queries using indexing strategies and query-plan
    analysis, and helps design faster database structures.
    When to use: Your app is slow and you suspect the database queries or table design are the
    bottleneck.
    Search terms: slow queries, database performance, indexing, sql tuning, explain plan,
    database design, speed up app, slow database
    Original description: Master SQL query optimization, indexing strategies, and EXPLAIN
    analysis to dramatically improve database performance and eliminate slow queries. Use when
    debugging slow queries, designing database schemas, or optimizing application performance.

[sql-server-table-reconciliation]
    Source: awesome-copilot
    What it does: Compares tables between two SQL Server databases and reports rows or
    structures that do not match, useful after data moves or nightly loads.
    When to use: You moved or copied data between SQL Server systems and need proof that nothing
    was lost or changed.
    Search terms: sql server, compare tables, data migration check, reconciliation report,
    production vs staging, data mismatch, etl verification, data validation
    Original description: Use when: comparing SQL Server tables across instances, data migration
    validation, ETL verification, row mismatch detection, schema drift, reconciliation report,
    production vs staging comparison. Uses mssql-python driver with Apache Arrow for fast
    columnar data transfer and comparison.

[trace-to-training-data]
    Source: agents (bundle)
    What it does: Turns logged examples of good and bad AI responses into training data that can
    be used to improve the AI model.
    When to use: You have a pile of rated AI chat logs and want to use them to make your AI
    assistant better.
    Search terms: ai training data, fine-tuning, improve ai model, chat logs, good and bad
    examples, preference pairs, model training, ai quality
    Original description: Convert evaluation traces and production logs into SFT examples and
    preference pairs. Use when graded traces or failure examples exist and need to become
    training data, when applying rejection sampling to model outputs, or when building DPO pairs
    from passing and failing runs.

[vector-index-tuning]
    Source: agents (bundle)
    What it does: Tunes the settings of a vector search index to balance speed, accuracy, and
    memory use as your search data grows.
    When to use: Your AI-powered search is getting slow, inaccurate, or expensive to run at
    scale.
    Search terms: vector search, search speed, semantic search, ai search performance, hnsw,
    vector database, memory usage, search accuracy
    Original description: Optimize vector index performance for latency, recall, and memory. Use
    when tuning HNSW parameters, selecting quantization strategies, or scaling vector search
    infrastructure.

[vision-sft]
    Source: agents (bundle)
    What it does: Trains AI models that understand both images and text on your own picture-and-
    caption data, and troubleshoots when training is not working.
    When to use: You want an AI model to recognize or describe images specific to your business,
    like product photos or forms.
    Search terms: image ai, fine-tune vision model, train ai on photos, image recognition,
    vision language model, lora, custom image model, ai training
    Original description: Fine-tune vision-language models (VLMs) with supervised learning on
    image+text data. Use when adapting a VLM to a visual domain or task, configuring frozen-
    vision-tower LoRA, or debugging a VLM fine-tune that trains without learning.
