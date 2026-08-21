09 FRONTEND & WEB DEVELOPMENT
=============================

Skills for building websites and web apps: React/Next.js patterns, performance, Core Web Vitals,
browser testing with Playwright/DevTools, TypeScript and web quality audits.

40 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - angular-migration
  - best-practices
  - browser-testing-with-devtools
  - chrome-devtools
  - gsap-framer-scroll-animation
  - higgsfield-websites
  - javascript-typescript-jest
  - latchshot-page-capture
  - migrate-to-shoehorn
  - modern-javascript-patterns
  - next-intl-add-language
  - nextjs-app-router-patterns
  - performance
  - playwright-automation-fill-in-form
  - playwright-explore-website
  - playwright-generate-test
  - react-audit-grep-patterns
  - react-container-presentation-component
  - react-modernization
  - react-native-architecture
  - react-state-management
  - react-vite-dashboard
  - react18-batching-patterns
  - react18-dep-compatibility
  - react18-enzyme-to-rtl
  - react18-legacy-context
  - react18-lifecycle-patterns
  - react18-string-refs
  - react19-concurrent-patterns
  - react19-source-patterns
  - react19-test-patterns
  - setup-ts-deep-modules
  - typescript-advanced-types
  - ui-screenshots
  - unit-test-vue-pinia
  - web-artifacts-builder
  - web-perf
  - web-quality-audit
  - webapp-testing (anthropic skills)
  - webapp-testing (awesome-copilot)

SKILL DETAILS
-------------

[angular-migration]
    Source: agents (bundle)
    What it does: Upgrades an old AngularJS web application to modern Angular step by step,
    without rebuilding everything at once.
    When to use: Your website or app runs on outdated AngularJS and you want to modernize it
    safely.
    Search terms: angularjs, angular upgrade, legacy app, modernize website, framework
    migration, outdated code, app rewrite, web app update
    Original description: Migrate from AngularJS to Angular using hybrid mode, incremental
    component rewriting, and dependency injection updates. Use when upgrading AngularJS
    applications, planning framework migrations, or modernizing legacy Angular code.

[best-practices]
    Source: web-quality
    What it does: Reviews website code for security holes, outdated techniques, and quality
    problems, and applies modern best practices.
    When to use: You want a security check or general quality review of your website's code.
    Search terms: security audit, website security, code review, vulnerabilities, modernize
    code, best practices, code quality, website check
    Original description: Apply modern web development best practices for security,
    compatibility, and code quality. Use when asked to "apply best practices", "security audit",
    "modernize code", "code quality review", or "check for vulnerabilities".

[browser-testing-with-devtools]
    Source: agent-skills
    What it does: Tests and debugs websites in a real Chrome browser, checking for errors, slow
    network requests, and visual problems using live data.
    When to use: Something on your website behaves oddly and you want it checked in a real
    browser.
    Search terms: test my website, chrome, browser testing, website errors, debug website, page
    not loading, console errors, website bugs
    Original description: Tests in real browsers via Chrome DevTools MCP. Use when building or
    debugging anything that runs in a browser. Use when you need to inspect the DOM, capture
    console errors, analyze network requests, profile performance, or verify visual output with
    real runtime data. Requires the chrome-devtools MCP server to be configured.

[chrome-devtools]
    Source: awesome-copilot
    What it does: Automates Chrome to interact with web pages, take screenshots, inspect network
    traffic, and measure performance.
    When to use: You want a browser to click through your site, capture screenshots, or diagnose
    slowness.
    Search terms: chrome, browser automation, screenshots, website speed, network traffic, debug
    website, devtools, page performance
    Original description: Expert-level browser automation, debugging, and performance analysis
    using Chrome DevTools MCP. Use for interacting with web pages, capturing screenshots,
    analyzing network traffic, and profiling performance.

[gsap-framer-scroll-animation]
    Source: awesome-copilot
    What it does: Builds scroll-driven animations for websites, such as fade-ins, parallax
    effects, pinned sections, and Apple-style scrolling, using GSAP or Framer Motion.
    When to use: You want your website to animate as visitors scroll down the page.
    Search terms: scroll animation, parallax, animate on scroll, fade in, website animation,
    sticky section, gsap, framer motion, fancy website effects
    Original description: Use this skill whenever the user wants to build scroll animations,
    scroll effects, parallax, scroll-triggered reveals, pinned sections, horizontal scroll, text
    animations, or any motion tied to scroll position — in vanilla JS, React, or Next.js. Covers
    GSAP ScrollTrigger (pinning, scrubbing, snapping, timelines, horizontal scroll,
    ScrollSmoother, matchMedia) and Framer Motion / Motion v12 (useScroll, useTransform,
    useSpring, whileInView, variants). Use this skill even if the user just says "animate on
    scroll", "fade in as I scroll", "make it scroll like Apple", "parallax effect", "sticky
    secti…

[higgsfield-websites]
    Source: higgsfield skills
    What it does: Builds, edits, and publishes complete websites, web apps, and multiplayer
    games through the Higgsfield platform, including game artwork and sound.
    When to use: You want a website, landing page, web app, or simple online game built and put
    live.
    Search terms: build a website, landing page, web app, make a game, deploy site, publish
    website, saas dashboard, portfolio site, higgsfield
    Original description: Build, edit, and deploy full-stack websites, apps and games via the
    Higgsfield CLI (`higgsfield website …`). Each is a React 19 + TanStack Start SSR app in one
    Cloudflare Worker (D1/R2/KV/DO/Containers). THREE product types, picked via `--type` on
    create: `website` (standalone, no Higgsfield integration — references/website-flow.md),
    `app` (Sign in with Higgsfield + fnf SDK, Quanta — references/app-flow.md), `game` (realtime
    multiplayer rooms — references/game-flow.md). Routes to the right flow; each carries its own
    rules and deploy/publish gates. Use when: "build me a website", "make a landin…

[javascript-typescript-jest]
    Source: awesome-copilot
    What it does: Writes reliable automated tests for JavaScript and TypeScript code using the
    Jest testing tool.
    When to use: You want automated checks so your web app's code keeps working after changes.
    Search terms: jest, javascript testing, unit tests, typescript tests, automated testing,
    test my code, mocking, qa
    Original description: Best practices for writing JavaScript/TypeScript tests using Jest,
    including mocking strategies, test structure, and common patterns.

[latchshot-page-capture]
    Source: awesome-copilot
    What it does: Takes screenshots, thumbnails, full-page captures, or PDFs of any public web
    page and saves them as files.
    When to use: You need a picture or PDF of a web page for a report, archive, or social
    preview.
    Search terms: screenshot website, web page to pdf, website thumbnail, full page capture,
    save web page, page snapshot, latchshot, archive website
    Original description: Use this skill when a user needs a screenshot, website thumbnail,
    full-page capture, or PDF of a public HTTP(S) webpage saved as a local artifact through
    Latchshot, including report, QA, archive, and social-preview workflows. Do not use it for
    private or authenticated pages, raw HTML, scraping or extraction, arbitrary browser actions,
    CAPTCHA or anti-bot bypass, or local-file capture.

[migrate-to-shoehorn]
    Source: mattpocock skills
    What it does: Cleans up TypeScript test files by replacing loose type shortcuts with the
    shoehorn library for safer partial test data.
    When to use: Your TypeScript tests are full of 'as' casts and you want them tidier and
    safer.
    Search terms: shoehorn, typescript tests, type assertions, test data, clean up tests,
    typescript, refactor tests
    Original description: Migrate test files from `as` type assertions to @total-
    typescript/shoehorn. Use when user mentions shoehorn, wants to replace `as` in tests, or
    needs partial test data.

[modern-javascript-patterns]
    Source: agents (bundle)
    What it does: Modernizes JavaScript code using current language features like async/await,
    destructuring, and modules for cleaner, faster programs.
    When to use: You have older JavaScript that needs refreshing or you want it written the
    modern way.
    Search terms: javascript, modern javascript, es6, refactor code, async await, clean code,
    legacy javascript, code modernization
    Original description: Master ES6+ features including async/await, destructuring, spread
    operators, arrow functions, promises, modules, iterators, generators, and functional
    programming patterns for writing clean, efficient JavaScript code. Use when refactoring
    legacy code, implementing modern patterns, or optimizing JavaScript applications.

[next-intl-add-language]
    Source: awesome-copilot
    What it does: Adds a new language to a Next.js website that uses next-intl for translations.
    When to use: You want your Next.js site available in another language.
    Search terms: add language, translate website, multilingual site, next.js, next-intl,
    localization, internationalization, i18n
    Original description: Add new language to a Next.js + next-intl application

[nextjs-app-router-patterns]
    Source: agents (bundle)
    What it does: Builds fast Next.js websites using the modern App Router, server components,
    and smart data loading.
    When to use: You're building or improving a website on Next.js and want it done the current
    recommended way.
    Search terms: next.js, nextjs, react website, server components, app router, fast website,
    ssr, web development
    Original description: Master Next.js 14+ App Router with Server Components, streaming,
    parallel routes, and advanced data fetching. Use when building Next.js applications,
    implementing SSR/SSG, or optimizing React Server Components.

[performance]
    Source: web-quality
    What it does: Speeds up websites by finding and fixing what makes pages load slowly.
    When to use: Your website feels slow and you want it to load faster.
    Search terms: website speed, speed up my site, slow website, page load time, performance
    audit, faster loading, optimize website, core web vitals
    Original description: Optimize web performance for faster loading and better user
    experience. Use when asked to "speed up my site", "optimize performance", "reduce load
    time", "fix slow loading", "improve page speed", or "performance audit".

[playwright-automation-fill-in-form]
    Source: awesome-copilot
    What it does: Automatically fills in and submits online forms using the Playwright browser
    tool.
    When to use: You need a web form filled out repeatedly or tested automatically.
    Search terms: fill in form, form automation, playwright, browser automation, auto fill,
    submit form, web forms, testing forms
    Original description: Automate filling in a form using Playwright MCP

[playwright-explore-website]
    Source: awesome-copilot
    What it does: Browses through a website automatically to map out its pages and behavior in
    preparation for testing.
    When to use: You want a quick automated tour of a site to see what's there before writing
    tests.
    Search terms: explore website, site map, playwright, website testing, browser automation,
    crawl site, qa, check pages
    Original description: Website exploration for testing using Playwright MCP

[playwright-generate-test]
    Source: awesome-copilot
    What it does: Turns a described user scenario into an automated browser test using
    Playwright.
    When to use: You want an automated test that checks a specific flow on your website, like
    signing up or checking out.
    Search terms: playwright, automated test, browser test, end to end test, test checkout, test
    signup, website qa, regression test
    Original description: Generate a Playwright test based on a scenario using Playwright MCP

[react-audit-grep-patterns]
    Source: awesome-copilot
    What it does: Provides ready-made search commands to find outdated or risky code in a React
    app before upgrading to React 18 or 19.
    When to use: You're planning a React upgrade and want to find everything that might break.
    Search terms: react upgrade, react 18, react 19, audit code, deprecated, migration check,
    find old code, react
    Original description: Provides the complete, verified grep scan command library for auditing
    React codebases before a React 18.3.1 or React 19 upgrade. Use this skill whenever running a
    migration audit - for both the react18-auditor and react19-auditor agents. Contains every
    grep pattern needed to find deprecated APIs, removed APIs, unsafe lifecycle methods,
    batching vulnerabilities, test file issues, dependency conflicts, and React 19 specific
    removals. Always use this skill when writing audit scan commands - do not rely on memory for
    grep syntax, especially for the multi-line async setState patterns which require…

[react-container-presentation-component]
    Source: awesome-copilot
    What it does: Scaffolds a new React component split into logic and display parts, following
    the project's TypeScript, Storybook, and styling conventions.
    When to use: You want a new React component created in a specific, consistent structure.
    Search terms: react component, scaffold component, container presentation, storybook,
    typescript, new component, react, boilerplate
    Original description: Create a React component using the Container/Presentation pattern in
    src/components by asking for the component name and type (ui or features), then scaffold
    files that follow this repository's TypeScript, Storybook, and SCSS conventions. Use when
    the user explicitly asks for a Container/Presentation-based component or runs /react-
    container-presentation-component.

[react-modernization]
    Source: agents (bundle)
    What it does: Upgrades React apps to the latest version, converting old class components to
    hooks and adopting newer features.
    When to use: Your React app is built on older patterns and needs bringing up to date.
    Search terms: react upgrade, modernize react, class to hooks, react hooks, legacy react,
    update react version, react, refactor
    Original description: Upgrade React applications to latest versions, migrate from class
    components to hooks, and adopt concurrent features. Use when modernizing React codebases,
    migrating to React Hooks, or upgrading to latest React versions.

[react-native-architecture]
    Source: agents (bundle)
    What it does: Builds production-quality mobile apps for iPhone and Android with React Native
    and Expo, including navigation, offline support, and native features.
    When to use: You want a mobile app built for both iOS and Android from one codebase.
    Search terms: mobile app, react native, expo, ios app, android app, build an app, cross
    platform, offline app
    Original description: Build production React Native apps with Expo, navigation, native
    modules, offline sync, and cross-platform patterns. Use when developing mobile apps,
    implementing native integrations, or architecting React Native projects.

[react-state-management]
    Source: agents (bundle)
    What it does: Sets up how a React app stores and shares data between screens using tools
    like Redux Toolkit, Zustand, Jotai, or React Query.
    When to use: Your React app's data handling is getting messy and you need a clean approach.
    Search terms: react state, redux, zustand, react query, app data, global state, react, state
    management
    Original description: Master modern React state management with Redux Toolkit, Zustand,
    Jotai, and React Query. Use when setting up global state, managing server state, or choosing
    between state management solutions.

[react-vite-dashboard]
    Source: stitch
    What it does: Converts Stitch design files into working React dashboards with live data
    loading, accessible styling, and optional crypto wallet support.
    When to use: You have a dashboard design in Stitch and want it turned into a working web
    app.
    Search terms: dashboard, stitch design, react, vite, design to code, admin panel, web3,
    build dashboard
    Original description: Convert Stitch designs into production React + Vite dashboards with
    TanStack Query, accessible tokens from DESIGN.md, and Web3-ready patterns (ethers/viem).

[react18-batching-patterns]
    Source: awesome-copilot
    What it does: Diagnoses and fixes state update timing bugs that appear in older React class
    components after upgrading to React 18.
    When to use: Your app started behaving strangely after a React 18 upgrade and you suspect
    state updates.
    Search terms: react 18, batching, setstate, flushsync, react bug, upgrade issues, class
    components, react
    Original description: Provides exact patterns for diagnosing and fixing automatic batching
    regressions in React 18 class components. Use this skill whenever a class component has
    multiple setState calls in an async method, inside setTimeout, inside a Promise .then() or
    .catch(), or in a native event handler. Use it before writing any flushSync call - the
    decision tree here prevents unnecessary flushSync overuse. Also use this skill when fixing
    test failures caused by intermediate state assertions that break after React 18 upgrade.

[react18-dep-compatibility]
    Source: awesome-copilot
    What it does: Lists which third-party packages work with React 18.3 and React 19 so upgrades
    don't break dependencies.
    When to use: You're upgrading React and need to know which libraries are compatible.
    Search terms: react 18, react 19, compatibility, dependencies, package versions, upgrade
    react, npm packages, react
    Original description: React 18.3.1 and React 19 dependency compatibility matrix.

[react18-enzyme-to-rtl]
    Source: awesome-copilot
    What it does: Rewrites old Enzyme tests as React Testing Library tests, focusing on what
    users see rather than internal details.
    When to use: Your React tests use Enzyme and need converting for a React 18 upgrade.
    Search terms: enzyme, react testing library, rtl, migrate tests, react 18, test conversion,
    react tests, testing
    Original description: Provides exact Enzyme → React Testing Library migration patterns for
    React 18 upgrades. Use this skill whenever Enzyme tests need to be rewritten - shallow,
    mount, wrapper.find(), wrapper.simulate(), wrapper.prop(), wrapper.state(),
    wrapper.instance(), Enzyme configure/Adapter calls, or any test file that imports from
    enzyme. This skill covers the full API mapping and the philosophy shift from implementation
    testing to behavior testing. Always read this skill before rewriting Enzyme tests - do not
    translate Enzyme APIs 1:1, that produces brittle RTL tests.

[react18-legacy-context]
    Source: awesome-copilot
    What it does: Migrates React's old context API to the modern createContext approach,
    updating providers and consumers together.
    When to use: Your React app uses legacy context and warnings are appearing during an
    upgrade.
    Search terms: react context, legacy context, createcontext, react 18, migration, class
    components, react, upgrade
    Original description: Provides the complete migration pattern for React legacy context API
    (contextTypes, childContextTypes, getChildContext) to the modern createContext API. Use this
    skill whenever migrating legacy context in class components - this is always a cross-file
    migration requiring the provider AND all consumers to be updated together. Use it before
    touching any contextTypes or childContextTypes code, because migrating only the provider
    without the consumers (or vice versa) will cause a runtime failure. Always read this skill
    before writing any context migration - the cross-file coordination steps here p…

[react18-lifecycle-patterns]
    Source: awesome-copilot
    What it does: Replaces unsafe React lifecycle methods in class components with their modern
    equivalents for React 18.
    When to use: You're seeing UNSAFE_ lifecycle warnings in your React app.
    Search terms: react lifecycle, componentwillmount, unsafe warnings, react 18, class
    components, migration, react, deprecated methods
    Original description: Provides exact before/after migration patterns for the three unsafe
    class component lifecycle methods - componentWillMount, componentWillReceiveProps, and
    componentWillUpdate - targeting React 18.3.1. Use this skill whenever a class component
    needs its lifecycle methods migrated, when deciding between getDerivedStateFromProps vs
    componentDidUpdate, when adding getSnapshotBeforeUpdate, or when fixing React 18 UNSAFE_
    lifecycle warnings. Always use this skill before writing any lifecycle migration code - do
    not guess the pattern from memory, the decision trees here prevent the most common migrat…

[react18-string-refs]
    Source: awesome-copilot
    What it does: Converts old-style string refs in React class components to createRef,
    including tricky cases like lists of refs.
    When to use: Your React app uses string refs and they're warning or breaking after an
    upgrade.
    Search terms: string refs, createref, react refs, react 18, react 19, migration, class
    components, react
    Original description: Provides exact migration patterns for React string refs (ref="name" +
    this.refs.name) to React.createRef() in class components. Use this skill whenever migrating
    string ref usage - including single element refs, multiple refs in a component, refs in
    lists, callback refs, and refs passed to child components. Always use this skill before
    writing any ref migration code - the multiple-refs-in-list pattern is particularly tricky
    and this skill prevents the most common mistakes. Use it for React 18.3.1 migration (string
    refs warn) and React 19 migration (string refs removed).

[react19-concurrent-patterns]
    Source: awesome-copilot
    What it does: Preserves existing concurrent features and adopts new React 19 APIs like
    useOptimistic, Actions, and use() during an upgrade.
    When to use: You're moving to React 19 and want to use its new features correctly.
    Search terms: react 19, usetransition, suspense, useoptimistic, actions, react upgrade,
    concurrent, react
    Original description: Preserve React 18 concurrent patterns and adopt React 19 APIs
    (useTransition, useDeferredValue, Suspense, use(), useOptimistic, Actions) during migration.

[react19-source-patterns]
    Source: awesome-copilot
    What it does: Provides before-and-after code patterns for updating source files to React 19,
    covering API changes, refs, and context.
    When to use: You're updating React components for React 19 and need the exact changes.
    Search terms: react 19, migration, api changes, refs, context, upgrade react, react, code
    patterns
    Original description: Reference for React 19 source-file migration patterns, including API
    changes, ref handling, and context updates.

[react19-test-patterns]
    Source: awesome-copilot
    What it does: Shows how to update test files for React 19, including act() imports, removed
    Simulate helpers, and StrictMode changes.
    When to use: Your tests broke after upgrading to React 19.
    Search terms: react 19, tests failing, act, strictmode, test migration, react tests, testing
    library, react
    Original description: Provides before/after patterns for migrating test files to React 19
    compatibility, including act() imports, Simulate removal, and StrictMode call count changes.

[setup-ts-deep-modules]
    Source: mattpocock skills
    What it does: Configures dependency-cruiser in a TypeScript project so each package hides
    its internals and exposes only clean entry points.
    When to use: You want to enforce clean module boundaries in a TypeScript codebase.
    Search terms: typescript, module boundaries, dependency cruiser, architecture, monorepo,
    code organization, entry points, enforce structure
    Original description: Wire dependency-cruiser into a TypeScript repo so each package is a
    deep module — implementation hidden in subfolders, reachable only through its entry-point
    files. User-invoked.

[typescript-advanced-types]
    Source: agents (bundle)
    What it does: Uses TypeScript's advanced type features like generics, conditional types, and
    mapped types to catch bugs before code runs.
    When to use: You need complex, reusable types in a TypeScript project.
    Search terms: typescript, generics, advanced types, type safety, conditional types, utility
    types, typescript help, type errors
    Original description: Master TypeScript's advanced type system including generics,
    conditional types, mapped types, template literals, and utility types for building type-safe
    applications. Use when implementing complex type logic, creating reusable type utilities, or
    ensuring compile-time type safety in TypeScript projects.

[ui-screenshots]
    Source: awesome-copilot
    What it does: Captures screenshots of a web app during development, including specific
    states and cropped regions, without slow re-captures.
    When to use: You want pictures of your app's screens for docs, reviews, or bug reports.
    Search terms: screenshots, ui screenshots, capture app, playwright, web app images, full
    page screenshot, crop screenshot, documentation
    Original description: Capture screenshots of web apps during development using Playwright
    and PIL. Supports full-page captures, interactive states, and an iterate-on-crop workflow
    that avoids slow re-screenshots.

[unit-test-vue-pinia]
    Source: awesome-copilot
    What it does: Writes and reviews automated tests for Vue 3 apps that use Pinia stores,
    Vitest, and TypeScript.
    When to use: You need tests for a Vue application's components or data stores.
    Search terms: vue, vue 3, pinia, vitest, unit tests, vue testing, automated tests, frontend
    testing
    Original description: Write and review unit tests for Vue 3 + TypeScript + Vitest + Pinia
    codebases. Use when creating or updating tests for components, composables, and stores;
    mocking Pinia with createTestingPinia; applying Vue Test Utils patterns; and enforcing
    black-box assertions over implementation details.

[web-artifacts-builder]
    Source: anthropic skills
    What it does: Builds complex, multi-part interactive web pages in claude.ai using React,
    Tailwind CSS, and shadcn/ui components.
    When to use: You want a rich interactive tool or mini-app built as a Claude artifact.
    Search terms: claude artifact, interactive web page, react app, tailwind, shadcn, mini app,
    web tool, prototype
    Original description: Suite of tools for creating elaborate, multi-component claude.ai HTML
    artifacts using modern frontend web technologies (React, Tailwind CSS, shadcn/ui). Use for
    complex artifacts requiring state management, routing, or shadcn/ui components - not for
    simple single-file HTML/JSX artifacts.

[web-perf]
    Source: cloudflare skills
    What it does: Measures a website's Core Web Vitals and other speed metrics in Chrome, then
    pinpoints what's slowing it down.
    When to use: You want to improve your Lighthouse score or understand why pages load slowly.
    Search terms: website speed, core web vitals, lighthouse, page speed, slow website,
    performance audit, lcp, site optimization
    Original description: Analyzes web performance using Chrome DevTools MCP. Measures Core Web
    Vitals (LCP, INP, CLS) and supplementary metrics (FCP, TBT, Speed Index), identifies render-
    blocking resources, network dependency chains, layout shifts, caching issues, and
    accessibility gaps. Use when asked to audit, profile, debug, or optimize page load
    performance, Lighthouse scores, or site speed. Biases towards retrieval from current
    documentation over pre-trained knowledge.

[web-quality-audit]
    Source: web-quality
    What it does: Runs a full website check covering speed, accessibility, search engine
    friendliness, and best practices, with fixes prioritized.
    When to use: You want an overall health report for your website.
    Search terms: website audit, lighthouse, seo check, accessibility check, website speed, page
    quality, optimize website, site review
    Original description: Comprehensive web quality audit covering performance, accessibility,
    SEO, and best practices. Use when asked to "audit my site", "review web quality", "run
    lighthouse audit", "check page quality", or "optimize my website".

[webapp-testing (anthropic skills)]
    Source: anthropic skills
    What it does: Tests web applications running on your computer using Playwright, verifying
    features, capturing screenshots, and reading browser logs.
    When to use: You want to check that a web app works correctly before it goes live.
    Search terms: test web app, playwright, browser testing, qa, screenshots, debug ui, local
    testing, website bugs
    Original description: Toolkit for interacting with and testing local web applications using
    Playwright. Supports verifying frontend functionality, debugging UI behavior, capturing
    browser screenshots, and viewing browser logs.

[webapp-testing (awesome-copilot)]
    Source: awesome-copilot
    What it does: Tests web applications running on your computer using Playwright, verifying
    features, capturing screenshots, and reading browser logs.
    When to use: You want to check that a web app works correctly before it goes live.
    Search terms: test web app, playwright, browser testing, qa, screenshots, debug ui, local
    testing, website bugs
    Original description: Toolkit for interacting with and testing local web applications using
    Playwright. Supports verifying frontend functionality, debugging UI behavior, capturing
    browser screenshots, and viewing browser logs.
