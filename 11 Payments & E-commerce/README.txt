11 PAYMENTS & E-COMMERCE
========================

Skills for taking money online: Stripe (integration, Connect, upgrades, apps), PayPal, billing
automation, pricing, paywalls, PCI compliance and Shopify.

16 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - billing-automation
  - connect-recommend
  - connect-required-verification-information
  - paypal-integration
  - paywalls
  - pci-compliance
  - post-purchase-upsell-flow
  - pricing
  - shopify-review-triage
  - stripe-apps
  - stripe-best-practices
  - stripe-directory
  - stripe-docs
  - stripe-integration
  - stripe-projects
  - upgrade-stripe

SKILL DETAILS
-------------

[billing-automation]
    Source: agents (bundle)
    What it does: Builds automated billing systems that handle recurring payments, invoicing,
    subscription changes, and chasing failed payments.
    When to use: You sell subscriptions and want billing to run itself.
    Search terms: subscription billing, recurring payments, invoicing, dunning, failed payments,
    automate billing, saas billing, stripe
    Original description: Build automated billing systems for recurring payments, invoicing,
    subscription lifecycle, and dunning management. Use when implementing subscription billing,
    automating invoicing, or managing recurring payment systems.

[connect-recommend]
    Source: stripe ai
    What it does: Recommends how to set up Stripe Connect for marketplaces and platforms,
    including how charges flow and how sellers or vendors get paid.
    When to use: You run a marketplace or platform and need to pay out to multiple sellers
    through Stripe.
    Search terms: stripe connect, marketplace payments, pay sellers, payouts, multi-vendor,
    split payments, platform payments, stripe
    Original description: Use this skill when the user asks about Stripe Connect configuration,
    charge patterns, Dashboard access, or how to get started with Connect, is building a
    marketplace, platform, multi-vendor store, gig platform, or subscription platform, needs to
    pay out sellers, vendors, or providers, mentions split payments, revenue sharing, multi-
    party payments, or similar payment distribution concepts, provides a company URL or business
    description for a recommendation, builds SaaS that routes money between parties (for
    example, POS, booking, invoicing — not operational SaaS without payment routing), asks …

[connect-required-verification-information]
    Source: stripe ai
    What it does: Explains what identity and business information Stripe Connect accounts must
    provide for verification and onboarding, and compares requirements across setups.
    When to use: You need to know what documents your sellers must submit to get paid through
    Stripe.
    Search terms: stripe connect, kyc, verification, onboarding requirements, seller
    verification, identity documents, compliance, stripe
    Original description: Use this skill when the user asks what information a Stripe Connect
    connected account must provide for verification, onboarding, KYC, or account requirements;
    when they need to compare requirements between connected-account setups; or when they ask
    which verification fields, documents, or business details are required for a particular
    platform country, account country, business type, dashboard, service agreement, or
    capability.

[paypal-integration]
    Source: agents (bundle)
    What it does: Adds PayPal payment processing to a website or app, including express
    checkout, subscriptions, and refunds.
    When to use: You want customers to be able to pay with PayPal.
    Search terms: paypal, accept payments, checkout, online payments, subscriptions, refunds,
    ecommerce, payment integration
    Original description: Integrate PayPal payment processing with support for express checkout,
    subscriptions, and refund management. Use when implementing PayPal payments, processing
    online transactions, or building e-commerce checkout flows.

[paywalls]
    Source: coreyhaines31 marketingskills
    What it does: Designs or improves in-app paywalls, upgrade screens, and feature gates to
    convert more free users into paying customers.
    When to use: Too few of your free users are upgrading to a paid plan.
    Search terms: paywall, upgrade screen, freemium, free to paid, upsell, feature gate, trial
    expired, conversion, app monetization
    Original description: When the user wants to create or optimize in-app paywalls, upgrade
    screens, upsell modals, or feature gates. Also use when the user mentions "paywall,"
    "upgrade screen," "upgrade modal," "upsell," "feature gate," "convert free to paid,"
    "freemium conversion," "trial expiration screen," "limit reached screen," "plan upgrade
    prompt," "in-app pricing," "free users won't upgrade," "trial to paid conversion," or "how
    do I get users to pay." Use this for any in-product moment where you're asking users to
    upgrade. Distinct from public pricing pages (see cro) — this focuses on in-product upgrade
    momen…

[pci-compliance]
    Source: agents (bundle)
    What it does: Implements the PCI DSS security requirements for handling credit card data
    safely in your payment systems.
    When to use: You process card payments and need to meet PCI compliance rules.
    Search terms: pci compliance, pci dss, credit card security, payment security, card data,
    compliance, secure payments, audit
    Original description: Implement PCI DSS compliance requirements for secure handling of
    payment card data and payment systems. Use when securing payment processing, achieving PCI
    compliance, or implementing payment card security measures.

[post-purchase-upsell-flow]
    Source: autonnel
    What it does: Designs one-click upsell and downsell offers shown right after checkout to
    raise average order value without hurting the main sale.
    When to use: You want customers to spend more per order after they have already bought.
    Search terms: upsell, post-purchase, average order value, aov, one-click upsell, thank you
    page, cross-sell, ecommerce, shopify
    Original description: Design and implement one-click post-purchase upsells and downsells
    that raise average order value without hurting the main conversion rate. Use when asked to
    increase AOV, add an upsell, cross-sell or downsell after checkout, build a one-click upsell
    flow, monetize the thank-you page, or when someone asks how to make more revenue per
    customer from the same ad spend.

[pricing]
    Source: coreyhaines31 marketingskills
    What it does: Advises on pricing and packaging decisions: tiers, free trials versus
    freemium, price increases, what to charge, and measuring willingness to pay.
    When to use: You are unsure how much to charge or how to structure your plans.
    Search terms: pricing, pricing tiers, how much to charge, freemium, free trial, price
    increase, packaging, monetization, saas pricing
    Original description: When the user wants help with pricing decisions, packaging, or
    monetization strategy. Also use when the user mentions 'pricing,' 'pricing tiers,'
    'freemium,' 'free trial,' 'packaging,' 'price increase,' 'value metric,' 'Van Westendorp,'
    'willingness to pay,' 'monetization,' 'how much should I charge,' 'my pricing is wrong,'
    'pricing page,' 'annual vs monthly,' 'per seat pricing,' 'should I offer a free plan,'
    'pricing page teardown,' 'pricing page audit,' 'is my pricing page AI-readable,' or 'can AI
    read my pricing.' Use this whenever someone is figuring out what to charge, how to structure
    th…

[shopify-review-triage]
    Source: awesome-copilot
    What it does: Sorts and prioritizes public Shopify App Store reviews and merchant feedback,
    groups them into themes, and turns them into a product or support brief.
    When to use: You want to know what to fix first based on what merchants are saying about
    your Shopify app.
    Search terms: shopify app reviews, customer feedback, review analysis, app store reviews,
    prioritize fixes, feedback triage, shopify, merchant complaints
    Original description: Use this skill when someone wants public Shopify App Store reviews,
    low-star reviews, or merchant feedback triaged, prioritized, clustered, or turned into a
    product or support brief. Trigger for prompts like "triage these app store reviews", "what
    should we fix first from this feedback", "cluster our 1-star reviews", or "write a weekly
    low-star review brief", for a single Shopify app or a portfolio plus watched competitors.
    Produces a P0-P3 brief covering incident risk, repeated friction, pricing confusion, feature
    requests, and an explicit needs-human-read bucket, where every item keeps its p…

[stripe-apps]
    Source: stripe ai
    What it does: Builds and reviews Stripe Apps that add custom panels to the Stripe Dashboard,
    react to Stripe events, or connect your service to Stripe without sharing API keys.
    When to use: You want to customize your Stripe Dashboard or build an integration that lives
    inside Stripe.
    Search terms: stripe apps, stripe dashboard, customize stripe, stripe integration, stripe
    events, stripe extension, payments
    Original description: Use when building, modifying, or reviewing a Stripe App — or when the
    user describes something that implies one (e.g. "add a panel to the customer page",
    "customize my Stripe Dashboard", "react to Stripe events from my app", "connect my service
    to Stripe without sharing API keys"). Covers the full app development workflow (scaffold,
    preview, upload, versioning), UI extension architecture (sandboxed iframe, Stripe UI
    toolkit, viewports), extension types (UI extensions, backend-only, extension interfaces,
    embedded apps), authentication (platform keys, OAuth, restricted API keys), stripe-app.yaml…

[stripe-best-practices]
    Source: stripe ai
    What it does: Guides Stripe integration choices: which checkout approach to use, how to set
    up Connect, subscriptions, tax, Treasury accounts, and more.
    When to use: You are building on Stripe and want to make the right setup decisions from the
    start.
    Search terms: stripe, stripe checkout, payment intents, subscriptions, stripe tax, stripe
    connect, accept payments, best practices
    Original description: Guides Stripe integration decisions across API selection (Checkout
    Sessions vs PaymentIntents), Connect platform setup (Accounts v2, controller properties),
    billing/subscriptions, tax and registrations (Stripe Tax, automatic_tax, product tax codes),
    Treasury financial accounts, integration options (Checkout, Payment Element), migrating from
    deprecated Stripe APIs, and security best practices (API key management, restricted keys,
    webhooks, OAuth). Use when building, modifying, or reviewing any Stripe integration,
    including accepting payments, building marketplaces, integrating Stripe, processin…

[stripe-directory]
    Source: stripe ai
    What it does: Finds and shortlists businesses, software, service providers, or partners that
    fit a specific industry, need, or job to be done, using the Stripe Directory. Can also be
    used to buy or consume a listed service directly.
    When to use: You need a short list of vendors, tools, or partners for a particular business
    problem.
    Search terms: find a vendor, software recommendations, service providers, stripe directory,
    partner search, tool shortlist, buy a service, compare suppliers, stripe
    Original description: Use when the user wants to find businesses, software, service
    providers, or partners for a specific industry, workflow, pain point, capability, or job to
    be done. Also use when the agent needs to programmatically purchase or consume a service.
    Use Stripe Directory to build a short relevant shortlist, even if the user does not mention
    Stripe Directory explicitly.

[stripe-docs]
    Source: stripe ai
    What it does: Looks up and reads Stripe's official documentation and API reference so
    answers about Stripe features and setup are accurate and current.
    When to use: You have a question about how something in Stripe works or how to set it up.
    Search terms: stripe docs, stripe help, stripe api, how does stripe work, stripe
    documentation, payment setup, stripe reference, stripe
    Original description: Use when the user or agent needs to read, search, or look up Stripe
    documentation or API reference. Prefer this over curl or WebFetch for any docs.stripe.com
    content.

[stripe-integration]
    Source: agents (bundle)
    What it does: Builds Stripe payment processing into a website or app, including secure
    checkout pages, subscription billing, and the webhooks that keep orders and payments in
    sync.
    When to use: You want to start accepting card payments or recurring subscriptions through
    Stripe.
    Search terms: accept payments, stripe checkout, subscriptions, recurring billing, online
    payments, stripe integration, payment gateway, webhooks, pci compliance, stripe
    Original description: Implement Stripe payment processing for robust, PCI-compliant payment
    flows including checkout, subscriptions, and webhooks. Use when integrating Stripe payments,
    building subscription systems, or implementing secure checkout flows.

[stripe-projects]
    Source: stripe ai
    What it does: Provisions infrastructure and third-party services (databases, hosting, email
    sending, authentication, monitoring, AI model access and more) through the Stripe Projects
    catalog, and manages the resulting credentials and resources.
    When to use: You need a database, hosting, an API key, or another backend service set up
    quickly without signing up manually.
    Search terms: stripe projects, provision services, get an api key, set up database, hosting,
    email sending service, sign up for a service, cloud services, credentials, projects.dev,
    stripe
    Original description: Use when the user wants to provision infrastructure or third-party
    services using Stripe Projects. Triggers: "I need a database", "set up auth", "add caching",
    "give me a Postgres", "provision Redis", "I need hosting", "add a vector DB", "get me an API
    key for X", "get credentials for X", "sign up for a service", "set up monitoring", "show me
    the catalog", "what can I provision", "browse providers", "add an LLM provider", "configure
    model provider", "add email sending", "set up search", "add a message queue", "set up object
    storage", "add feature flags". Also trigger when the user asks how to …

[upgrade-stripe]
    Source: stripe ai
    What it does: Guides you through upgrading your Stripe API version and software libraries
    safely, flagging breaking changes along the way.
    When to use: Your Stripe integration is on an old version and you want to update it without
    breaking payments.
    Search terms: upgrade stripe, stripe api version, stripe sdk update, update payment code,
    stripe migration, breaking changes, stripe
    Original description: Guide for upgrading Stripe API versions and SDKs
