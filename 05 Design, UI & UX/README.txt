05 DESIGN, UI & UX
==================

Skills for designing interfaces that look and feel premium: design systems, UI polish, animation
and motion, accessibility, Stitch/Figma workflows, taste/anti-slop guides and mobile design.

72 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - accessibility
  - accessibility-compliance
  - animate
  - animation-vocabulary
  - anti-ui-slop
  - apple-design
  - ask-sonner
  - baseline-ui
  - create-design-md
  - design
  - design-md
  - design-system
  - design-system-patterns
  - design-taste-frontend
  - design-taste-frontend-v1
  - emil-design-eng
  - extract-design-system
  - figma-designer
  - find-animation-opportunities
  - fixing-accessibility
  - fixing-motion-performance
  - frontend-design
  - frontend-ui-engineering
  - gpt-taste
  - high-end-visual-design
  - image-annotations
  - image-to-code
  - imagegen-frontend-mobile
  - imagegen-frontend-web
  - impeccable
  - improve-animations
  - improve-ui
  - industrial-brutalist-ui
  - interaction-design
  - interface-design
  - minimalist-ui
  - mobile-android-design
  - mobile-ios-design
  - penpot-uiux-design
  - pick-ui-library
  - plantuml-ascii
  - premium-frontend-ui
  - prototype (emilkowalski skills)
  - prototype (mattpocock skills)
  - react-native-design
  - redesign-existing-projects
  - responsive-design
  - review-animations
  - screen-reader-testing
  - shadcn-ui
  - stitch-code-to-design
  - stitch-design-taste
  - stitch-extract-design-md
  - stitch-extract-static-html
  - stitch-generate-design
  - stitch-loop
  - stitch-manage-design-system
  - stitch-react-components
  - stitch-react-native
  - stitch-upload-to-stitch
  - tailwind-design-system
  - taste-design
  - theme-factory
  - ui
  - ui-styling
  - ui-ux-pro-max
  - visual-design-foundations
  - visual-edit-precision
  - wcag-audit-patterns
  - web-component-design
  - web-design-guidelines
  - web-design-reviewer

SKILL DETAILS
-------------

[accessibility]
    Source: web-quality
    What it does: Audits a website for accessibility problems against the WCAG 2.2 standard and
    fixes them so people with disabilities can use it.
    When to use: You want your website to work for screen-reader and keyboard-only users, or
    need to meet accessibility requirements.
    Search terms: accessibility, wcag, screen reader, ada compliance, keyboard navigation,
    disability access, a11y, website accessibility audit
    Original description: Audit and improve web accessibility following WCAG 2.2 guidelines. Use
    when asked to "improve accessibility", "a11y audit", "WCAG compliance", "screen reader
    support", "keyboard navigation", or "make accessible".

[accessibility-compliance]
    Source: agents (bundle)
    What it does: Builds websites and mobile screens that meet the WCAG 2.2 accessibility
    standard, with support for screen readers and assistive technology.
    When to use: You are building a new app or site and want it to be accessible to everyone
    from the start.
    Search terms: accessibility, wcag, inclusive design, screen reader, aria, mobile
    accessibility, ada compliance, assistive technology
    Original description: Implement WCAG 2.2 compliant interfaces with mobile accessibility,
    inclusive design patterns, and assistive technology support. Use when auditing
    accessibility, implementing ARIA patterns, building for screen readers, or ensuring
    inclusive user experiences.

[animate]
    Source: emilkowalski skills
    What it does: Designs and builds a single animation or transition for a web interface,
    deciding whether it should move at all and then how fast, how smoothly, and how it ends.
    When to use: You want a button, menu, or page element on your site to move or transition in
    a way that feels polished.
    Search terms: animation, add motion, transition effect, website animation, smooth effect,
    micro-interaction, ui animation, make it feel alive
    Original description: Build an animation from scratch, making the decisions in the order
    that determines whether it feels right — should it animate at all, what purpose, which tool,
    which properties, which curve and duration, how it interrupts, how it exits. Writes the
    implementation. Use when asked to animate something, add motion, make a component feel
    alive, or build a transition. For critiquing existing motion use review-animations; for
    auditing a whole codebase use improve-animations.

[animation-vocabulary]
    Source: emilkowalski skills
    What it does: Tells you the proper name for a web animation effect when you can only
    describe what it looks like.
    When to use: You saw a motion effect on a site and want to know what it is called so you can
    ask a designer or AI for it.
    Search terms: what's it called, animation name, motion effect, bounce effect, rubber band
    scroll, ui terms, design vocabulary, transition name
    Original description: Reverse-lookup glossary that turns a vague description of a web
    animation or motion effect into its exact term ("the bouncy thing when a popover opens" →
    Pop in; "the iOS rubber-band scroll" → Rubber-banding). Use when the user asks "what's it
    called when…", or describes a motion effect without knowing its name and wants the right
    word to prompt an AI or designer with. For naming an effect, not designing or building one.

[anti-ui-slop]
    Source: awesome-copilot
    What it does: Stops AI coding tools from producing bland, generic-looking screens by pulling
    design ideas from a catalogue of 800,000 real web and mobile app screens.
    When to use: Your AI-built website or app looks like every other AI-built website and you
    want it to look like a real product.
    Search terms: generic design, looks ai generated, better ui, design inspiration, real app
    screens, uizze, ios design, web design quality
    Original description: Stop Codex, GitHub Copilot, Claude Code, and Cursor from shipping
    generic UI. Use UIZZE’s public catalogue of 800,000+ real web and iOS screens to extract
    product-specific design decisions and enforce a hard finish gate for web and iOS interfaces.

[apple-design]
    Source: emilkowalski skills
    What it does: Applies Apple's approach to interface design and smooth, physical-feeling
    motion to websites, covering gestures, springs, depth, and typography.
    When to use: You want your site or web app to feel as smooth and polished as an iPhone app.
    Search terms: apple style, ios feel, smooth animation, swipe gestures, spring animation,
    polished interface, apple design, fluid motion
    Original description: Apple's approach to interface design and fluid, physical motion,
    translated for the web. Use when building or reviewing gesture-driven UI, spring animations,
    drag/swipe/sheet interactions, momentum and interruptible transitions, translucent materials
    and depth, typography (optical sizing, tracking, leading), reduced-motion, or the design
    foundations (feedback, spatial consistency, restraint) behind Apple-style interfaces.

[ask-sonner]
    Source: emilkowalski skills
    What it does: Sets up and troubleshoots Sonner, a tool that shows small pop-up notification
    messages (toasts) in React websites.
    When to use: Your website's pop-up notifications are missing, duplicated, misstyled, or
    hidden behind other windows.
    Search terms: sonner, toast notifications, pop-up message, react, notification not showing,
    dark mode, alert banner, ui notifications
    Original description: Guide to Sonner, the React toast library — install and wire up the
    Toaster, pick the right toast() call, promise and loading toasts, updating, dismissing and
    persisting toasts, styling, theming and icons, positioning and multiple toasters. Use when
    working with Sonner or troubleshooting it — toasts that don't appear, appear twice, lose
    their styles, ignore Tailwind classes, sit behind a modal, or don't follow dark mode.

[baseline-ui]
    Source: ui-skills
    What it does: Quickly tidies up a web interface by fixing spacing, text sizes, visual
    hierarchy, and small layout problems.
    When to use: Your screen works but looks messy or amateurish and needs a fast polish.
    Search terms: clean up design, polish ui, spacing, fonts, layout fix, looks messy, quick
    design fix, typography
    Original description: Quickly deslop UI code by fixing spacing, hierarchy, typography, and
    small layout issues. Use when the interface needs a fast cleanup or polish pass.

[create-design-md]
    Source: ui-skills
    What it does: Documents the look and feel of an existing website or app (colors, fonts,
    spacing, patterns) in a DESIGN.md file that AI tools can follow later.
    When to use: You want AI tools to keep new pages consistent with the design of your existing
    site.
    Search terms: design guide, brand style document, design tokens, consistent look, document
    design, style guide, design.md, extract design
    Original description: Create or update a DESIGN.md from an existing product repository or
    public website. Use when asked to document an interface's design language, reconstruct its
    visual system, extract design tokens and guidance from current evidence, or give coding
    agents persistent UI context. Do not modify product source or promote accidental
    implementation patterns into design decisions.

[design]
    Source: ui-ux-pro-max
    What it does: Creates brand identity assets end to end, including logos, corporate identity
    kits, banners, icons, social media images, and slide presentations.
    When to use: You need a logo, banner, social graphics, or a full brand kit made for your
    business.
    Search terms: logo design, brand identity, social media images, banner design, icons, brand
    kit, presentation slides, corporate identity, facebook, instagram, linkedin
    Original description: Comprehensive design skill: brand identity, design tokens, UI styling,
    logo generation (55 styles, Gemini AI), corporate identity program (50 deliverables, CIP
    mockups), HTML presentations (Chart.js), banner design (22 styles, social/ads/web/print),
    icon design (15 styles, SVG, Gemini 3.1 Pro), social photos (HTML→screenshot, multi-
    platform). Actions: design logo, create CIP, generate mockups, build slides, design banner,
    generate icon, create social photos, social media images, brand identity, design system.
    Platforms: Facebook, Twitter, LinkedIn, YouTube, Instagram, Pinterest, TikTok, Thread…

[design-md]
    Source: stitch
    What it does: Analyzes Google Stitch design projects and writes up their design system in a
    DESIGN.md file.
    When to use: You built screens in Google Stitch and want a written guide to the colors,
    fonts, and rules they use.
    Search terms: stitch, google stitch, design system, design document, design.md, style guide,
    design tokens, ui consistency
    Original description: Analyze Stitch projects and synthesize a semantic design system into
    DESIGN.md files

[design-system]
    Source: ui-ux-pro-max
    What it does: Defines a reusable set of design rules (colors, spacing, type scales,
    component specs) and builds on-brand slide decks from them.
    When to use: You want every page, app, and presentation your business produces to look
    consistent and on-brand.
    Search terms: design system, brand colors, design tokens, consistent design, component
    specs, branded slides, style guide, css variables
    Original description: Token architecture, component specifications, and slide generation.
    Three-layer tokens (primitive→semantic→component), CSS variables, spacing/typography scales,
    component specs, strategic slide creation. Use for design tokens, systematic design, brand-
    compliant presentations.

[design-system-patterns]
    Source: agents (bundle)
    What it does: Builds a scalable design system with shared tokens, light/dark themes, and a
    reusable component library.
    When to use: Your product has grown and you need one consistent set of building blocks for
    all its screens.
    Search terms: design system, component library, theme switching, dark mode, design tokens,
    consistent ui, reusable components, branding
    Original description: Build scalable design systems with design tokens, theming
    infrastructure, and component architecture patterns. Use when creating design tokens,
    implementing theme switching, building component libraries, or establishing design system
    foundations.

[design-taste-frontend]
    Source: taste-skill
    What it does: Designs and builds landing pages, portfolios, and redesigns that look custom
    rather than templated, auditing the existing design first when redesigning.
    When to use: You want a landing page or website that does not look like it came from a
    template or an AI.
    Search terms: landing page, website redesign, portfolio site, custom design, not generic,
    good taste, frontend design, premium look
    Original description: Anti-slop frontend skill for landing pages, portfolios, and redesigns.
    The agent reads the brief, infers the right design direction, and ships interfaces that do
    not look templated. Real design systems when applicable, audit-first on redesigns, strict
    pre-flight check.

[design-taste-frontend-v1]
    Source: taste-skill
    What it does: Provides the older first version of the design-taste-frontend skill for
    projects that depend on its exact behavior.
    When to use: You used the original taste-skill on a project and need the same results as
    before.
    Search terms: landing page, website design, legacy version, taste skill, frontend design,
    backward compatibility, v1, custom design
    Original description: The original v1 taste-skill, preserved for projects depending on its
    exact behavior. The current default is `design-taste-frontend` (v2 experimental), which is a
    substantial rewrite. Use this v1 install name only if you need exact backward compatibility.

[emil-design-eng]
    Source: emilkowalski skills
    What it does: Applies designer Emil Kowalski's philosophy on polish, component design, and
    subtle animation details to make software feel great.
    When to use: You want your interface to have the refined, invisible details that make
    premium software feel good to use.
    Search terms: ui polish, design details, emil kowalski, animation decisions, component
    design, premium feel, software craft, interface quality
    Original description: This skill encodes Emil Kowalski's philosophy on UI polish, component
    design, animation decisions, and the invisible details that make software feel great.

[extract-design-system]
    Source: extract-design-system
    What it does: Pulls colors, fonts, spacing, and other design basics from any public website
    and turns them into starter style files for your project.
    When to use: You like the look of a website and want to base your own project's styling on
    it.
    Search terms: copy website style, design tokens, extract colors, fonts from website, style
    starter, design system, brand colors, website look
    Original description: Extract design primitives from a public website and generate starter
    token files for your project.

[figma-designer]
    Source: agent-playbook
    What it does: Reads Figma designs or design screenshots and writes a detailed build
    specification developers can implement from.
    When to use: You have a Figma mockup and need clear instructions for turning it into a
    working site or app.
    Search terms: figma, design to code, design spec, mockup, build from design, prd, design
    handoff, screenshots
    Original description: Analyzes Figma designs and generates implementation-ready PRDs with
    detailed visual specifications. Use when user provides Figma link or uploads design
    screenshots. Requires Figma MCP server connection.

[find-animation-opportunities]
    Source: emilkowalski skills
    What it does: Scans a website or app for places that would benefit from motion and proposes
    exact animation values, without making changes.
    When to use: You feel your site is static and lifeless and want suggestions for where to add
    movement.
    Search terms: animation ideas, make it feel alive, add motion, ui suggestions, where to
    animate, micro-interactions, design review, website feel
    Original description: Search a codebase or UI for places that don't animate but should, and
    reject everything that shouldn't. Read-only; it proposes motion with exact values, it does
    not implement it. Use when the user asks "what could be animated here?" or wants to "make
    this feel more alive". For fixing existing animations, use improve-animations or review-
    animations instead.

[fixing-accessibility]
    Source: ui-skills
    What it does: Audits and fixes accessibility problems in web pages, including labels,
    keyboard navigation, focus, color contrast, and form errors.
    When to use: You are adding forms, dialogs, or buttons and want them to work for people
    using screen readers or keyboards.
    Search terms: accessibility, wcag, keyboard navigation, color contrast, screen reader, form
    errors, aria labels, ada
    Original description: Audit and fix HTML accessibility issues including ARIA labels,
    keyboard navigation, focus management, color contrast, and form errors. Use when adding
    interactive controls, forms, dialogs, or reviewing WCAG compliance.

[fixing-motion-performance]
    Source: ui-skills
    What it does: Finds and fixes animations that stutter or lag on a website by correcting the
    underlying performance problems.
    When to use: Your site's animations or scrolling feel choppy, especially on phones.
    Search terms: choppy animation, laggy website, stuttering, smooth scrolling, animation
    performance, janky, slow transitions, website speed
    Original description: Audit and fix animation performance issues including layout thrashing,
    compositor properties, scroll-linked motion, and blur effects. Use when animations stutter,
    transitions jank, or reviewing CSS/JS animation performance.

[frontend-design]
    Source: anthropic skills
    What it does: Guides distinctive visual design choices (aesthetic direction, typography,
    layout) when building or reshaping a user interface so it does not look like a default
    template.
    When to use: You are building a new page or app and want it to look intentional and
    memorable rather than generic.
    Search terms: website design, visual style, typography, look and feel, not generic,
    frontend, aesthetic, ui design
    Original description: Guidance for distinctive, intentional visual design when building new
    UI or reshaping an existing one. Helps with aesthetic direction, typography, and making
    choices that don't read as templated defaults.

[frontend-ui-engineering]
    Source: agent-skills
    What it does: Builds production-quality web interfaces that are accessible, responsive on
    all devices, and look professionally made.
    When to use: You need pages or components built that look and work like a real product, not
    a rough AI draft.
    Search terms: build website, responsive design, accessible ui, web pages, components,
    production quality, frontend, layout
    Original description: Builds production-quality, accessible, responsive user-facing UIs. Use
    when building or modifying interfaces and pages, creating components, implementing layouts,
    meeting WCAG accessibility requirements, managing state, or when the output needs to look
    and feel production-quality rather than AI-generated.

[gpt-taste]
    Source: taste-skill
    What it does: Builds bold, editorial-style landing pages with large typography, tightly
    packed grids, and scroll-driven animations using GSAP.
    When to use: You want a dramatic, magazine-style landing page with big type and scroll
    effects.
    Search terms: landing page, scroll animation, gsap, bold typography, bento grid, editorial
    design, aida, website design
    Original description: Elite UX/UI & Advanced GSAP Motion Engineer. Enforces Python-driven
    true randomization for layout variance, strict AIDA page structure, wide editorial
    typography (bans 6-line wraps), gapless bento grids, strict GSAP ScrollTriggers (pinning,
    stacking, scrubbing), inline micro-images, and massive section spacing.

[high-end-visual-design]
    Source: taste-skill
    What it does: Makes websites look expensive by enforcing specific fonts, spacing, shadows,
    card layouts, and animations, and blocking common cheap-looking defaults.
    When to use: Your website looks cheap or generic and you want it to feel like a high-end
    agency built it.
    Search terms: premium website, expensive look, agency quality, fonts, spacing, shadows,
    luxury design, not generic
    Original description: Teaches the AI to design like a high-end agency. Defines the exact
    fonts, spacing, shadows, card structures, and animations that make a website feel expensive.
    Blocks all the common defaults that make AI designs look cheap or generic.

[image-annotations]
    Source: awesome-copilot
    What it does: Adds callout boxes, arrows, labels, and highlights to screenshots and
    diagrams, including animated GIFs with controlled timing.
    When to use: You need to mark up a screenshot for a tutorial, support reply, or bug report.
    Search terms: annotate screenshot, add arrows, highlight image, markup picture, tutorial
    images, callouts, gif annotation, labels on image
    Original description: Annotate screenshots, diagrams, and images with callout rectangles,
    arrows, labels, and color-coded highlights using PIL. Includes rules for animated GIF
    annotations with timing and pacing.

[image-to-code]
    Source: taste-skill
    What it does: Generates design images for a website first, studies them closely, and then
    builds the site to match them as faithfully as possible.
    When to use: You want a website built from a polished visual design rather than straight
    from a text description.
    Search terms: design to code, website mockup, build from image, landing page, visual design,
    hero section, ai website design, codex
    Original description: Elite website image-to-code skill for Codex. For visually important
    web tasks, it must first generate the design image(s) itself, deeply analyze them, then
    implement the website to match them as closely as possible. In Codex, it must prefer large,
    readable, section-specific images instead of tiny compressed boards, generate fresh
    standalone images for sections or detail views instead of cropping old ones, avoid lazy
    under-generation, avoid cards-inside-cards-inside-cards UI, and keep the hero clean,
    spacious, readable, and visible on a small laptop.

[imagegen-frontend-mobile]
    Source: taste-skill
    What it does: Generates premium-looking concept images of mobile app screens, shown inside a
    phone frame, with consistent style across multiple screens.
    When to use: You want to visualize what your mobile app could look like before anyone writes
    code.
    Search terms: app mockup, mobile app design, iphone mockup, app screens, concept images, ios
    design, android design, app idea visual
    Original description: Elite mobile app image-generation skill for creating premium, app-
    native screen concepts and flows. Designed for iOS, Android, and cross-platform mobile
    products. Prioritizes clean hierarchy, comfortably readable text, strong multi-screen
    consistency, controlled color palettes, non-generic creative direction, textured surfaces,
    image-led composition, tasteful custom iconography, and clean phone mockup framing. By
    default, screens should be shown inside a subtle premium iPhone or similar phone mockup with
    a visible frame, while the main focus stays on the app content itself. This skill generate…

[imagegen-frontend-web]
    Source: taste-skill
    What it does: Generates one polished reference image per section of a website so designers
    or developers can recreate the design accurately.
    When to use: You want to see what each part of your new website should look like before it
    is built.
    Search terms: website mockup, design reference, landing page design, section images, hero
    design, marketing site, visual concept, website inspiration
    Original description: Elite frontend image-direction skill for generating premium,
    conversion-aware website design references. CRITICAL OUTPUT RULE — generate ONE separate
    horizontal image FOR EVERY section. A landing page with 8 sections produces 8 images. Never
    compress multiple sections into one image. Enforces composition variety (not always left-
    text / right-image), background-image freedom, varied CTAs, varied hero scales (giant / mid
    / mini minimalist), narrative concept spine, second-read moments, and a single consistent
    palette across all images. Optimized for landing pages, marketing sites, and product co…

[impeccable]
    Source: impeccable
    What it does: Designs, reviews, and improves any web interface, from landing pages to
    dashboards, covering layout, color, typography, motion, accessibility, copy, and
    responsiveness.
    When to use: You want to make an existing or new interface clearer, more polished, bolder,
    or quieter.
    Search terms: improve website, ui review, redesign, polish interface, dashboard design,
    landing page, ux audit, accessibility, typography, colors
    Original description: Use when the user wants to design, redesign, shape, critique, audit,
    polish, clarify, distill, harden, optimize, adapt, animate, colorize, extract, or otherwise
    improve a frontend interface. Covers websites, landing pages, dashboards, product UI, app
    shells, components, forms, settings, onboarding, and empty states. Handles UX review, visual
    hierarchy, information architecture, cognitive load, accessibility, performance, responsive
    behavior, theming, anti-patterns, typography, fonts, spacing, layout, alignment, color,
    motion, micro-interactions, UX copy, error states, edge cases, i18n, and reu…

[improve-animations]
    Source: emilkowalski skills
    What it does: Surveys all animations in a website or app and produces a prioritized list of
    improvements with ready-to-follow plans, without changing code itself.
    When to use: You want a roadmap for making your app's motion feel better across the board.
    Search terms: animation audit, improve animations, motion review, make app feel better, ui
    polish plan, transitions, animation roadmap, design review
    Original description: Survey a codebase's animation and motion code as a senior motion
    advisor, then produce a prioritized audit and self-contained implementation plans for other
    agents (or cheaper models) to execute. Read-only on source code — it plans improvements, it
    does not apply them. Use when the user asks to "improve the animations", "audit the motion",
    "make this app feel better", or wants a roadmap of animation fixes rather than a review of a
    single diff.

[improve-ui]
    Source: ui-skills
    What it does: Reviews an existing product screen against its own design standards, lists
    verified problems, and writes fix plans for someone else to carry out, without touching
    code.
    When to use: You want a professional critique of your app's screens and a clear to-do list
    for fixing them.
    Search terms: ui review, design audit, improve interface, design consistency, design
    handoff, ui problems, clean up design, fix plan
    Original description: Audit an existing product surface against its own design evidence,
    identify verified UI problems, and write self-contained implementation plans for another
    agent. Strictly read-only on product source. Use when asked to review, refine, improve, or
    clean up an interface without replacing its identity; investigate design-system drift; or
    prepare a design handoff.

[industrial-brutalist-ui]
    Source: taste-skill
    What it does: Designs raw, mechanical-looking interfaces with rigid grids, extreme type
    contrast, and a military-terminal or blueprint feel.
    When to use: You want a dashboard, portfolio, or editorial site with an edgy, industrial
    look.
    Search terms: brutalist design, industrial look, terminal style, blueprint aesthetic, swiss
    typography, edgy website, dashboard design, portfolio style
    Original description: Raw mechanical interfaces fusing Swiss typographic print with military
    terminal aesthetics. Rigid grids, extreme type scale contrast, utilitarian color, analog
    degradation effects. For data-heavy dashboards, portfolios, or editorial sites that need to
    feel like declassified blueprints.

[interaction-design]
    Source: agents (bundle)
    What it does: Designs and builds small interactive touches like hover effects, loading
    states, transitions, and feedback so an interface feels responsive and pleasant.
    When to use: You want your app to feel more polished with little animations and clear
    feedback when users act.
    Search terms: micro-interactions, loading states, hover effects, transitions, user feedback,
    ui polish, delightful ux, motion design
    Original description: Design and implement microinteractions, motion design, transitions,
    and user feedback patterns. Use when adding polish to UI interactions, implementing loading
    states, or creating delightful user experiences.

[interface-design]
    Source: interface-design
    What it does: Designs and refines product interfaces such as dashboards, admin panels,
    settings pages, and data tools with careful layout, hierarchy, and consistency.
    When to use: You are building or improving the working screens of a software product, not a
    marketing page.
    Search terms: dashboard design, admin panel, saas app design, settings page, data interface,
    product ui, design review, layout hierarchy
    Original description: Craft-first interface design for dashboards, admin panels, SaaS apps,
    tools, settings pages, data interfaces, and interactive products. Use when designing,
    building, reviewing, auditing, or refining product UI where visual craft, layout hierarchy,
    tokens, states, visual direction, or design-system consistency matter. Not for marketing
    pages, landing pages, campaigns, or brand-only work.

[minimalist-ui]
    Source: taste-skill
    What it does: Designs clean, editorial-style interfaces with warm neutral colors, strong
    typography, and flat grid layouts, avoiding gradients and heavy shadows.
    When to use: You want a calm, minimal look for your site or app.
    Search terms: minimalist design, clean website, simple ui, editorial style, neutral colors,
    flat design, muted pastels, typography
    Original description: Clean editorial-style interfaces. Warm monochrome palette, typographic
    contrast, flat bento grids, muted pastels. No gradients, no heavy shadows.

[mobile-android-design]
    Source: agents (bundle)
    What it does: Designs Android app screens following Google's Material Design 3 guidelines
    and builds them with Jetpack Compose.
    When to use: You are building an Android app and want it to look and behave like a proper
    Google-style app.
    Search terms: android app, material design, jetpack compose, android ui, google design
    guidelines, mobile app design, native android, app screens
    Original description: Master Material Design 3 and Jetpack Compose patterns for building
    native Android apps. Use when designing Android interfaces, implementing Compose UI, or
    following Google's Material Design guidelines.

[mobile-ios-design]
    Source: agents (bundle)
    What it does: Designs iPhone and iPad app screens following Apple's Human Interface
    Guidelines and builds them with SwiftUI.
    When to use: You are building an iOS app and want it to feel native and pass Apple's design
    expectations.
    Search terms: ios app, iphone app design, swiftui, apple guidelines, native ios, mobile app
    design, app store, ipad app
    Original description: Master iOS Human Interface Guidelines and SwiftUI patterns for
    building native iOS apps. Use when designing iOS interfaces, implementing SwiftUI views, or
    ensuring apps follow Apple's design principles.

[penpot-uiux-design]
    Source: awesome-copilot
    What it does: Creates professional app and website designs in Penpot, an open-source design
    tool, including design systems, dashboards, forms, and landing pages.
    When to use: You want UI mockups designed in Penpot rather than Figma.
    Search terms: penpot, ui design, mockups, design system, dashboard design, landing page
    design, open source figma, accessible design
    Original description: Comprehensive guide for creating professional UI/UX designs in Penpot
    using MCP tools. Use this skill when: (1) Creating new UI/UX designs for web, mobile, or
    desktop applications, (2) Building design systems with components and tokens, (3) Designing
    dashboards, forms, navigation, or landing pages, (4) Applying accessibility standards and
    best practices, (5) Following platform guidelines (iOS, Android, Material Design), (6)
    Reviewing or improving existing Penpot designs for usability. Triggers: "design a UI",
    "create interface", "build layout", "design dashboard", "create form", "design landin…

[pick-ui-library]
    Source: emilkowalski skills
    What it does: Recommends the best ready-made code library for a specific interface need,
    such as charts, drag-and-drop, toasts, or number inputs, from a curated list.
    When to use: You need a chart, command menu, or similar feature and want to know which
    library to use rather than build it yourself.
    Search terms: which library, ui library, charts, drag and drop, toast notifications, react
    components, otp input, recommend tool
    Original description: Pick the right library for a given frontend task from a curated,
    opinionated list — numbers, OTP inputs, charts, command menus, virtualization, drag and
    drop, toasts, state, styling, and more. Only runs when explicitly invoked; it does not
    trigger on its own.

[plantuml-ascii]
    Source: awesome-copilot
    What it does: Generates text-only diagrams (flowcharts, sequence diagrams, class diagrams)
    that display in plain text editors and terminals using PlantUML.
    When to use: You need a diagram that can live inside a plain text document, email, or code
    comment.
    Search terms: ascii diagram, text diagram, plantuml, flowchart in text, terminal diagram,
    sequence diagram, plain text chart, ascii art
    Original description: Generate ASCII art diagrams using PlantUML text mode. Use when user
    asks to create ASCII diagrams, text-based diagrams, terminal-friendly diagrams, or mentions
    plantuml ascii, text diagram, ascii art diagram. Supports: Converting PlantUML diagrams to
    ASCII art, Creating sequence diagrams, class diagrams, flowcharts in ASCII format,
    Generating Unicode-enhanced ASCII art with -utxt flag

[premium-frontend-ui]
    Source: awesome-copilot
    What it does: Guides building immersive, high-performance websites with advanced motion,
    typography, and well-structured code.
    When to use: You want a standout marketing website with rich animation and premium feel.
    Search terms: premium website, immersive design, advanced animation, typography, high-end
    web, motion design, github copilot, landing page
    Original description: A comprehensive guide for GitHub Copilot to craft immersive, high-
    performance web experiences with advanced motion, typography, and architectural
    craftsmanship.

[prototype (emilkowalski skills)]
    Source: emilkowalski skills
    What it does: Builds several genuinely different versions of a UI element and shows them
    side by side in a picker so you can choose the one that feels right.
    When to use: You cannot decide how a component should look and want to compare real options
    live.
    Search terms: compare designs, ui variations, a/b options, prototype, design options, pick a
    version, component design, try alternatives
    Original description: Build multiple genuinely different versions of a UI piece you
    describe, rendered behind a visual picker so you can flip through them live and promote the
    one that feels right. Only runs when explicitly invoked; it does not trigger on its own.

[prototype (mattpocock skills)]
    Source: mattpocock skills
    What it does: Builds a quick throwaway prototype to test whether an idea, flow, or screen
    design works before committing to it.
    When to use: You want to sanity-check how a feature should behave or look before building it
    properly.
    Search terms: quick prototype, mockup, test an idea, proof of concept, throwaway demo,
    design question, sketch a screen, explore ui
    Original description: Build a throwaway prototype to answer a design question. Use when the
    user wants to sanity-check whether a state model or logic feels right, or explore what a UI
    should look like.

[react-native-design]
    Source: agents (bundle)
    What it does: Builds cross-platform mobile apps with React Native, covering styling, screen
    navigation, and smooth animations.
    When to use: You want one mobile app that runs on both iPhone and Android.
    Search terms: react native, mobile app, cross-platform app, iphone and android, app
    navigation, app animations, expo, mobile design
    Original description: Master React Native styling, navigation, and Reanimated animations for
    cross-platform mobile development. Use when building React Native apps, implementing
    navigation patterns, or creating performant animations.

[redesign-existing-projects]
    Source: taste-skill
    What it does: Upgrades an existing website or app to a premium look by auditing its design,
    removing generic patterns, and applying high-end standards without breaking features.
    When to use: Your current site works fine but looks dated or generic and you want a
    facelift.
    Search terms: website redesign, facelift, modernize site, premium look, upgrade design,
    looks generic, css, app redesign
    Original description: Upgrades existing websites and apps to premium quality. Audits current
    design, identifies generic AI patterns, and applies high-end design standards without
    breaking functionality. Works with any CSS framework or vanilla CSS.

[responsive-design]
    Source: agents (bundle)
    What it does: Builds layouts that adapt cleanly to any screen size, from phones to large
    monitors, using modern CSS techniques.
    When to use: Your website looks wrong on phones or tablets and needs to work on every
    device.
    Search terms: mobile friendly, responsive website, works on phone, screen sizes, fluid
    layout, css grid, tablet layout, adaptive design
    Original description: Implement modern responsive layouts using container queries, fluid
    typography, CSS Grid, and mobile-first breakpoint strategies. Use when building adaptive
    interfaces, implementing fluid layouts, or creating component-level responsive behavior.

[review-animations]
    Source: emilkowalski skills
    What it does: Critiques animation code against a high craft standard and flags anything that
    feels off, approving only what truly earns it.
    When to use: You added animations and want an expert opinion on whether they feel right.
    Search terms: animation review, motion critique, ui feedback, transition quality, animation
    code review, feels off, polish check, design engineering
    Original description: Reviews animation and motion code against a high craft bar derived
    from Emil Kowalski's design engineering philosophy. Default to flagging; approval is earned.

[screen-reader-testing]
    Source: agents (bundle)
    What it does: Tests a website with screen readers such as VoiceOver, NVDA, and JAWS to
    confirm it works for blind and low-vision users.
    When to use: You want to verify your site is usable with a screen reader before launch or an
    audit.
    Search terms: screen reader, voiceover, nvda, jaws, accessibility testing, blind users,
    assistive technology, wcag
    Original description: Test web applications with screen readers including VoiceOver, NVDA,
    and JAWS. Use when validating screen reader compatibility, debugging accessibility issues,
    or ensuring assistive technology support.

[shadcn-ui]
    Source: stitch
    What it does: Helps find, install, and customize shadcn/ui components, a popular set of
    ready-made building blocks for web apps.
    When to use: You are building a web app and want good-looking buttons, forms, and dialogs
    without designing from scratch.
    Search terms: shadcn, ui components, react components, tailwind, ready-made ui, component
    library, buttons and forms, web app design
    Original description: Expert guidance for integrating and building applications with
    shadcn/ui components, including component discovery, installation, customization, and best
    practices.

[stitch-code-to-design]
    Source: stitch
    What it does: Moves an existing website or app built in React, Vue, Angular, or similar into
    Google Stitch as an editable design, preserving its styles and assets.
    When to use: You want to bring a site you already have into Stitch so you can redesign it
    visually.
    Search terms: stitch, google stitch, import website, code to design, migrate to stitch, save
    design, react, vue, angular
    Original description: Convert frontend code (Vite, React, Angular, Vue, etc.) to a Stitch
    Design by chaining static HTML extraction, design system extraction, and file upload.
    **ALWAYS** use this skill when the user's intent is to move existing web apps or
    React/Angular/Vue components into Stitch (e.g., requests to "save", "migrate", or "upload").
    You must use this skill even for simple "save" operations, as it is the only way to ensure
    the design system is extracted and assets are properly linked.

[stitch-design-taste]
    Source: taste-skill
    What it does: Writes DESIGN.md style guides for Google Stitch that push designs toward
    premium, non-generic results with strict typography, color, and motion rules.
    When to use: You use Google Stitch and want its output to look high-end instead of generic.
    Search terms: stitch, google stitch, design guide, premium design, design.md, anti-generic,
    style rules, ui standards
    Original description: Semantic Design System Skill for Google Stitch. Generates agent-
    friendly DESIGN.md files that enforce premium, anti-generic UI standards — strict
    typography, calibrated color, asymmetric layouts, perpetual micro-motion, and hardware-
    accelerated performance.

[stitch-extract-design-md]
    Source: stitch
    What it does: Reverse-engineers the design system of an existing codebase (colors, fonts,
    spacing, components) into a DESIGN.md document compatible with Google Stitch.
    When to use: You want to understand or document what your existing app looks like from its
    code.
    Search terms: extract design, design system from code, what does this app look like, design
    tokens, stitch, style audit, tailwind config, design.md
    Original description: Extract a comprehensive design system (DESIGN.md) directly from
    frontend source code — React, Vue, Svelte, Angular, plain HTML/CSS, or any web framework.
    Analyzes component files, stylesheets, Tailwind configs, theme definitions, and design
    tokens to produce a rich, Stitch-compatible design system document. Use this skill whenever
    the user wants to reverse-engineer a design system from an existing codebase, audit the
    visual language of a project, extract design tokens from source files, or understand the
    styling patterns in a frontend repo — even if they just say "what does this app look like?…

[stitch-extract-static-html]
    Source: stitch
    What it does: Captures a single self-contained HTML snapshot of a web page, with styles and
    images baked in, for sharing or uploading to Stitch.
    When to use: You need a frozen copy of a page exactly as it looks right now.
    Search terms: save html, page snapshot, static copy, capture web page, export page, stitch
    upload, mock the view, share page
    Original description: Extract self-contained static HTML from a built web application or
    React components by inlining CSS and images. Use this skill whenever you need to capture a
    specific UI state, share a static version of a page, or prepare assets for Stitch upload,
    even if the user just asks to 'save the HTML' or 'mock the view'.

[stitch-generate-design]
    Source: stitch
    What it does: Generates new app or website screens from text or images in Google Stitch,
    edits existing screens, and creates design variants.
    When to use: You want to quickly produce screen designs by describing them in words.
    Search terms: stitch, google stitch, generate screens, ai design, mockups from text, design
    variants, edit design, ui generation
    Original description: Generate new screens from text prompts or images, edit existing
    screens with prompts and design system tokens, and generate design variants using Stitch
    MCP. Includes prompt enhancement pipeline, design mappings, professional UI/UX terminology,
    design tokens and theme system capabilities.

[stitch-loop]
    Source: stitch
    What it does: Builds a website step by step in Google Stitch using an automated loop where
    each pass hands off to the next.
    When to use: You want an AI to iteratively build out a whole site in Stitch with minimal
    supervision.
    Search terms: stitch, google stitch, build website, automated design, iterative, website
    builder, ai loop, autonomous
    Original description: Teaches agents to iteratively build websites using Stitch with an
    autonomous baton-passing loop pattern

[stitch-manage-design-system]
    Source: stitch
    What it does: Creates, updates, and applies design systems inside Google Stitch, and
    retrieves their assets.
    When to use: You want all your Stitch screens to share one consistent set of colors, fonts,
    and components.
    Search terms: stitch, google stitch, design system, apply theme, brand consistency, design
    assets, update styles, ui consistency
    Original description: Manage design systems in Stitch using MCP tools. Includes retrieval of
    assets, creating/updating design systems in Stitch, and applying them to screens.

[stitch-react-components]
    Source: stitch
    What it does: Converts Google Stitch designs into working React components, or updates
    existing components to match the latest designs.
    When to use: You designed screens in Stitch and want real code for your web app.
    Search terms: stitch, design to code, react components, vite, sync design, build from
    design, web app code, frontend
    Original description: Converts Stitch designs into modular Vite and React components, or
    syncs/updates existing React components to align with the latest Stitch designs, using
    system-level networking and AST-based validation.

[stitch-react-native]
    Source: stitch
    What it does: Converts Google Stitch designs into React Native mobile app components, or
    keeps existing components in sync with design updates.
    When to use: You designed mobile screens in Stitch and want them turned into an iPhone and
    Android app.
    Search terms: stitch, react native, design to code, mobile app, sync design, iphone and
    android, app components, frontend
    Original description: Convert Stitch HTML designs to React Native components, or
    syncs/updates existing native components to align with the latest Stitch designs, using
    StyleSheet.

[stitch-upload-to-stitch]
    Source: stitch
    What it does: Uploads images, mockups, HTML pages, and design documents from your computer
    into a Google Stitch project, even large files.
    When to use: You have design files on your computer and need them in Stitch.
    Search terms: stitch, upload files, google stitch, mockups, images, design docs, html
    upload, project assets
    Original description: Upload local assets (images, mockups, extracted HTML, design markdown)
    to a Stitch project. ALWAYS use this skill when you need to upload visual assets, HTML
    pages, or design docs to Stitch, particularly when direct MCP tool calls fail or truncate
    due to base64 token limits.

[tailwind-design-system]
    Source: agents (bundle)
    What it does: Builds a consistent design system and component library using Tailwind CSS v4
    with shared tokens and responsive patterns.
    When to use: You use Tailwind and want a standardized set of styles and components across
    your product.
    Search terms: tailwind, design system, component library, css framework, consistent styling,
    design tokens, responsive, ui standards
    Original description: Build scalable design systems with Tailwind CSS v4, design tokens,
    component libraries, and responsive patterns. Use when creating component libraries,
    implementing design systems, or standardizing UI patterns.

[taste-design]
    Source: stitch
    What it does: Writes DESIGN.md style guides for Google Stitch that enforce premium, non-
    generic design standards for typography, color, layout, and motion.
    When to use: You use Google Stitch and want its designs to look high-end rather than
    templated.
    Search terms: stitch, google stitch, design guide, premium design, design.md, style rules,
    anti-generic, ui standards
    Original description: Semantic Design System Skill for Google Stitch. Generates agent-
    friendly DESIGN.md files that enforce premium, anti-generic UI standards — strict
    typography, calibrated color, asymmetric layouts, perpetual micro-motion, and hardware-
    accelerated performance.

[theme-factory]
    Source: anthropic skills
    What it does: Applies one of ten ready-made color-and-font themes, or a custom theme made on
    the spot, to slides, documents, reports, or web pages.
    When to use: You have a deck or document and want it to look polished and consistent with a
    few clicks.
    Search terms: theme, color scheme, fonts, style my slides, branded look, document styling,
    presentation design, quick makeover
    Original description: Toolkit for styling artifacts with a theme. These artifacts can be
    slides, docs, reportings, HTML landing pages, etc. There are 10 pre-set themes with
    colors/fonts that you can apply to any artifact that has been creating, or can generate a
    new theme on-the-fly.

[ui]
    Source: waza
    What it does: Produces distinctive, professional-grade web pages and components, including
    typography and screenshot-based polish, in any language.
    When to use: Your screen looks unclear, ugly, or inconsistent and you want it fixed to a
    professional standard.
    Search terms: ui design, fix ugly screen, web page design, components, typography, looks
    wrong, frontend, visual polish
    Original description: Produces distinctive, production-grade UI for pages, components,
    visual interfaces, typography, and screenshot-driven polish. Use when users ask in any
    language for UI, page, component, frontend, typography, screenshot-grounded visual polish,
    or complaints that a screen looks unclear, ugly, inconsistent, or visually wrong. Not for
    backend logic or data pipelines.

[ui-styling]
    Source: ui-ux-pro-max
    What it does: Builds attractive, accessible interfaces with shadcn/ui components and
    Tailwind CSS, including dark mode, themes, responsive layouts, and poster-style visuals.
    When to use: You want good-looking, consistent styling for a web app without designing every
    piece yourself.
    Search terms: shadcn, tailwind, ui styling, dark mode, responsive layout, accessible
    components, theme colors, web app design
    Original description: Create beautiful, accessible user interfaces with shadcn/ui components
    (built on Radix UI + Tailwind), Tailwind CSS utility-first styling, and canvas-based visual
    designs. Use when building user interfaces, implementing design systems, creating responsive
    layouts, adding accessible components (dialogs, dropdowns, forms, tables), customizing
    themes and colors, implementing dark mode, generating visual designs and posters, or
    establishing consistent styling patterns across applications.

[ui-ux-pro-max]
    Source: ui-ux-pro-max
    What it does: Provides a searchable library of design styles, color palettes, font pairings,
    UX guidelines, icons, and chart types to design, build, or fix interfaces for web, mobile,
    and desktop.
    When to use: You want expert design guidance and ready-made style choices for any screen you
    are building.
    Search terms: ui design, ux guidelines, color palette, font pairing, design styles, charts,
    accessibility, design library, mobile design
    Original description: UI/UX design intelligence for web, mobile, and desktop. This skill
    should be used when designing, building, reviewing, or fixing interfaces, including pages,
    components, design systems, accessibility, interaction, responsive layout, typography,
    color, charts, and stack-specific UI implementation. Searchable local data: 79 searchable
    styles (50 active), 192 product palettes and reasoning profiles, 74 font pairings, 119 UX
    guidelines, 105 icons, 17 GSAP presets, 25 chart types, and 22 stacks.

[visual-design-foundations]
    Source: agents (bundle)
    What it does: Applies core visual design principles, including typography, color theory,
    spacing, and icons, to make designs cohesive and easy to read.
    When to use: You want to set up a style guide or fix a design that feels inconsistent or
    hard to scan.
    Search terms: typography, color theory, spacing, style guide, visual hierarchy, icons,
    design basics, consistent look
    Original description: Apply typography, color theory, spacing systems, and iconography
    principles to create cohesive visual designs. Use when establishing design tokens, building
    style guides, or improving visual hierarchy and consistency.

[visual-edit-precision]
    Source: agents (bundle)
    What it does: Makes precise interface changes based on visual cues such as screenshots,
    drawn annotations, or elements you point at on screen.
    When to use: You want to say 'change this part' by showing it rather than describing it in
    words.
    Search terms: edit from screenshot, point and change, visual edits, annotated screenshot, ui
    tweaks, select element, frontend changes, design fix
    Original description: Use when making UI/frontend changes guided by visual context, when the
    user selects elements visually, draws annotations, or provides screenshots alongside change
    requests. Also use when editing components where spatial context (element identity, DOM
    references, layout data) supplements text instructions.

[wcag-audit-patterns]
    Source: agents (bundle)
    What it does: Runs full WCAG 2.2 accessibility audits combining automated scans and manual
    checks, and gives step-by-step fix guidance.
    When to use: You need a formal accessibility audit of your website, for compliance or before
    launch.
    Search terms: accessibility audit, wcag, ada compliance, accessibility report, fix
    violations, screen reader, website compliance, a11y
    Original description: Conduct WCAG 2.2 accessibility audits with automated testing, manual
    verification, and remediation guidance. Use when auditing websites for accessibility, fixing
    WCAG violations, or implementing accessible design patterns.

[web-component-design]
    Source: agents (bundle)
    What it does: Designs reusable interface components in React, Vue, or Svelte with clean
    structure and styling so they can be shared across a product.
    When to use: You are building a library of buttons, cards, and widgets that many pages will
    reuse.
    Search terms: react components, vue, svelte, component library, reusable ui, design system,
    css-in-js, frontend architecture
    Original description: Master React, Vue, and Svelte component patterns including CSS-in-JS,
    composition strategies, and reusable component architecture. Use when building UI component
    libraries, designing component APIs, or implementing frontend design systems.

[web-design-guidelines]
    Source: vercel agent-skills
    What it does: Reviews website code against a checklist of web interface best practices for
    usability, accessibility, and design quality.
    When to use: You want a quick best-practices review of your site before it goes live.
    Search terms: ui review, check accessibility, design audit, ux review, best practices,
    website checklist, vercel, frontend review
    Original description: Review UI code for Web Interface Guidelines compliance. Use when asked
    to "review my UI", "check accessibility", "audit design", "review UX", or "check my site
    against best practices".

[web-design-reviewer]
    Source: awesome-copilot
    What it does: Visually inspects a live or local website, spots layout, responsiveness,
    consistency, and accessibility problems, and fixes them in the code.
    When to use: Something looks broken or off on your website and you want it found and fixed.
    Search terms: fix layout, website looks broken, design review, responsive issues, check the
    ui, visual bugs, accessibility, design problems
    Original description: This skill enables visual inspection of websites running locally or
    remotely to identify and fix design issues. Triggers on requests like "review website
    design", "check the UI", "fix the layout", "find design problems". Detects issues with
    responsive design, accessibility, visual consistency, and layout breakage, then performs
    fixes at the source code level.
