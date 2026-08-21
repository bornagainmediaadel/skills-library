08 DOCUMENTS, SLIDES & FILES
============================

Skills for producing and converting files: Word, PowerPoint, Excel, PDF, HTML presentations,
diagrams and markdown conversions.

27 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - code-review-excellence
  - convert-excel-to-md
  - convert-pdf-to-md
  - convert-plaintext-to-md
  - convert-word-to-md
  - docx
  - draw-io-diagram-generator
  - drawio
  - excalidraw-diagram-generator
  - file-conversion
  - html-ppt
  - markdown-to-html
  - markstream-install
  - md-to-docx
  - napkin
  - pdf
  - pdftk-server
  - pitch-deck-visuals
  - pptx
  - pptx-deck-context
  - pptx-quality-gates
  - pptx-reference-deck-analysis
  - pptx-slide-specification
  - pptx-visual-assets
  - screen-recording
  - slides
  - xlsx

SKILL DETAILS
-------------

[code-review-excellence]
    Source: agents (bundle)
    What it does: Guides giving constructive, effective code reviews that catch bugs early and
    share knowledge without hurting team morale.
    When to use: You are reviewing a colleague's code changes or setting review standards for
    your team.
    Search terms: code review, pull request, feedback, review standards, mentoring developers,
    catch bugs, team process, constructive feedback
    Original description: Master effective code review practices to provide constructive
    feedback, catch bugs early, and foster knowledge sharing while maintaining team morale. Use
    when reviewing pull requests, establishing review standards, or mentoring developers.

[convert-excel-to-md]
    Source: awesome-copilot
    What it does: Converts Excel spreadsheets into readable text so their contents can be
    summarized, searched, compared, or analyzed.
    When to use: You have an Excel file, budget, or tracker and want to ask questions about what
    is in it.
    Search terms: excel, spreadsheet, xlsx, read spreadsheet, summarize excel, budget file, data
    export, convert to text
    Original description: Converts Excel (.xlsx) workbooks into Markdown so their contents can
    be accurately analyzed, summarized, searched, or extracted from. Use this skill whenever the
    user shares, references, or asks about a .xlsx file — even if they don't say "convert" or
    "markdown" explicitly. This includes requests to "read", "summarize", "review", "extract
    data from", "compare", "chart", or "analyze" a spreadsheet, workbook, budget, data export,
    or tracker. Always run the bundled conversion script to produce Markdown first; do not
    attempt to parse .xlsx content directly or write ad-hoc extraction code. Also use…

[convert-pdf-to-md]
    Source: awesome-copilot
    What it does: Converts PDF documents into readable text so their contents can be summarized,
    searched, compared, or extracted.
    When to use: You have a PDF report, invoice, or contract and want to pull out or analyze its
    contents.
    Search terms: pdf, read pdf, extract text, summarize pdf, invoice, contract, scanned
    document, convert pdf
    Original description: Converts PDF (.pdf) documents into Markdown so their contents can be
    accurately analyzed, summarized, searched, or extracted from. Use this skill whenever the
    user shares, references, or asks about a .pdf file — even if they don't say "convert" or
    "markdown" explicitly. This includes requests to "read", "summarize", "review", "extract
    data from", "compare", or "analyze" a PDF report, paper, invoice, form, contract, or scanned
    document. Always run the bundled conversion script to produce Markdown first; do not attempt
    to parse PDF content directly or write ad-hoc extraction code. Also use this …

[convert-plaintext-to-md]
    Source: awesome-copilot
    What it does: Converts a plain text document into formatted Markdown following your
    instructions or a preset option.
    When to use: You have raw text and want it formatted with headings, lists, and structure.
    Search terms: plain text, markdown, format document, text to markdown, clean up text, add
    headings, convert text, document formatting
    Original description: Convert a text-based document to markdown following instructions from
    prompt, or if a documented option is passed, follow the instructions for that option.

[convert-word-to-md]
    Source: awesome-copilot
    What it does: Converts Word documents into readable text so their contents can be
    summarized, searched, compared, or extracted.
    When to use: You have a Word file such as a proposal, resume, or contract and want to
    analyze or summarize it.
    Search terms: word document, docx, read word file, summarize document, proposal, resume,
    contract, convert word
    Original description: Converts Word (.docx) documents into Markdown so their contents can be
    accurately analyzed, summarized, searched, or extracted from. Use this skill whenever the
    user shares, references, or asks about a .docx file — even if they don't say "convert" or
    "markdown" explicitly. This includes requests to "read", "summarize", "review", "extract
    data from", "compare", or "analyze" a Word document, resume, report, contract, or proposal.
    Always run the bundled conversion script to produce Markdown first; do not attempt to parse
    .docx content directly or write ad-hoc conversion code. Also use this skill …

[docx]
    Source: anthropic skills
    What it does: Creates, reads, and edits Word documents, including formatted reports,
    letters, templates, tables of contents, tracked changes, and images.
    When to use: You need a professional Word document produced or an existing one changed.
    Search terms: word document, docx, create report, letter, memo, word template, tracked
    changes, edit word file, table of contents
    Original description: Use this skill whenever the user wants to create, read, edit, or
    manipulate Word documents (.docx files) or Word templates (.dotx files). Triggers include:
    any mention of 'Word doc', 'word document', '.docx', '.dotx', or requests to produce
    professional documents with formatting like tables of contents, headings, page numbers, or
    letterheads. Also use when extracting or reorganizing content from .docx or .dotx files,
    inserting or replacing images in documents, performing find-and-replace in Word files,
    working with tracked changes or comments, or converting content into a polished Word
    documen…

[draw-io-diagram-generator]
    Source: awesome-copilot
    What it does: Creates and edits draw.io diagrams such as flowcharts, system architectures,
    org charts, and network maps as ready-to-open files.
    When to use: You need a professional diagram you can open and tweak in draw.io.
    Search terms: draw.io, diagrams.net, flowchart, org chart, architecture diagram, network
    diagram, process map, diagram file
    Original description: Use when creating, editing, or generating draw.io diagram files
    (.drawio, .drawio.svg, .drawio.png). Covers mxGraph XML authoring, shape libraries, style
    strings, flowcharts, system architecture, sequence diagrams, ER diagrams, UML class
    diagrams, network topology, layout strategy, the hediet.vscode-drawio VS Code extension, and
    the full agent workflow from request to a ready-to-open file.

[drawio]
    Source: awesome-copilot
    What it does: Generates draw.io diagram files and exports them to PNG, SVG, or PDF images
    with the editable diagram embedded.
    When to use: You want a diagram you can both share as an image and edit later in draw.io.
    Search terms: draw.io, diagram, flowchart, export png, export pdf, editable diagram, process
    diagram, visual chart
    Original description: Generate draw.io diagrams as .drawio files and export to PNG/SVG/PDF
    with embedded XML

[excalidraw-diagram-generator]
    Source: awesome-copilot
    What it does: Creates hand-drawn-style diagrams such as flowcharts, mind maps, and system
    sketches from plain descriptions, as Excalidraw files.
    When to use: You want a quick, sketchy-looking diagram to explain a process or idea.
    Search terms: excalidraw, flowchart, mind map, sketch diagram, visualize process, whiteboard
    style, system diagram, hand-drawn
    Original description: Generate Excalidraw diagrams from natural language descriptions. Use
    when asked to "create a diagram", "make a flowchart", "visualize a process", "draw a system
    architecture", "create a mind map", or "generate an Excalidraw file". Supports flowcharts,
    relationship diagrams, mind maps, and system architecture diagrams. Outputs .excalidraw JSON
    files that can be opened directly in Excalidraw.

[file-conversion]
    Source: agents (bundle)
    What it does: Converts files between nearly a thousand format pairs, including PDF to Word,
    HEIC to JPG, video to audio, and CSV to JSON, using a free online service.
    When to use: You have a file in the wrong format and need it in another one.
    Search terms: convert file, pdf to word, heic to jpg, mp4 to mp3, csv to json, file format,
    image converter, video converter, ebook
    Original description: Convert files between formats — PDF to Word, HEIC to JPG, MP4 to MP3,
    CSV to JSON, EPUB to MOBI, and 999 total routes across images, video, audio, documents,
    data, fonts, ebooks, and archives. Free via changethisfile.com, no API key or signup. Use
    when the user needs a file converted to a different format.

[html-ppt]
    Source: html-ppt
    What it does: Builds polished slide presentations as web pages with many styles, layouts,
    and animations, navigable by keyboard.
    When to use: You need a good-looking presentation or pitch deck that opens in any browser.
    Search terms: presentation, slides, pitch deck, slideshow, keynote, html slides, tech talk,
    deck design
    Original description: HTML PPT Studio — author professional static HTML presentations in
    many styles, layouts, and animations, all driven by templates. Use when the user asks for a
    presentation, PPT, slides, keynote, deck, slideshow, "幻灯片", "演讲稿", "做一份 PPT", "做一份 slides",
    a reveal-style HTML deck, a 小红书 图文, or any kind of multi-slide pitch/report/sharing document
    that should look tasteful and be usable with keyboard navigation. Triggers include keywords
    like "presentation", "ppt", "slides", "deck", "keynote", "reveal", "slideshow", "幻灯片",
    "演讲稿", "分享稿", "小红书图文", "talk slides", "pitch deck", "tech sharing", "technica…

[markdown-to-html]
    Source: awesome-copilot
    What it does: Converts Markdown text files into web pages, including within site generators
    like Jekyll or Hugo.
    When to use: You write content in Markdown and need it published as HTML on a website.
    Search terms: markdown to html, convert markdown, render markdown, static site, jekyll,
    hugo, web page from text, publish content
    Original description: Convert Markdown files to HTML similar to `marked.js`, `pandoc`,
    `gomarkdown/markdown`, or similar tools; or writing custom script to convert markdown to
    html and/or working on web template systems like `jekyll/jekyll`, `gohugoio/hugo`, or
    similar web templating systems that utilize markdown documents, converting them to html. Use
    when asked to "convert markdown to html", "transform md to html", "render markdown",
    "generate html from markdown", or when working with .md files and/or web a templating system
    that converts markdown to HTML output. Supports CLI and Node.js workflows with GFM, Commo…

[markstream-install]
    Source: awesome-copilot
    What it does: Installs and configures Markstream, a tool that displays streaming AI-style
    text nicely in Vue, React, Svelte, Angular, or Nuxt apps.
    When to use: You are building a chat-style app and want AI responses to render as formatted
    text while they stream in.
    Search terms: markstream, streaming text, markdown renderer, chat app, react, vue, svelte,
    angular, live text display
    Original description: Install and configure Markstream streaming Markdown renderers for Vue,
    React, Svelte, Angular, Nuxt, and Vue 2 applications. Use for package selection, minimal
    peer dependencies, CSS order, SSR boundaries, streaming mode, and renderer setup.

[md-to-docx]
    Source: awesome-copilot
    What it does: Converts Markdown files into nicely formatted Word documents with images
    included, with no extra software needed.
    When to use: You drafted something in Markdown and need to send it as a Word document.
    Search terms: markdown to word, docx, convert markdown, word document, formatted report,
    export to word, images, document conversion
    Original description: Convert Markdown files to professionally formatted Word (.docx)
    documents with embedded PNG images — pure JavaScript, no external tools required

[napkin]
    Source: awesome-copilot
    What it does: Opens an interactive whiteboard in your browser where you can draw, sketch,
    and add sticky notes, then shares it back to the AI for analysis and ideas.
    When to use: You think better by sketching and want to brainstorm visually with an AI.
    Search terms: whiteboard, sketch ideas, brainstorm, sticky notes, draw diagram, visual
    collaboration, napkin, copilot
    Original description: Visual whiteboard collaboration for Copilot CLI. Creates an
    interactive whiteboard that opens in your browser — draw, sketch, add sticky notes, then
    share everything back with Copilot. Copilot sees your drawings and text, and responds with
    analysis, suggestions, and ideas.

[pdf]
    Source: anthropic skills
    What it does: Handles any PDF task, including reading and extracting text or tables,
    merging, splitting, rotating, watermarking, form filling, encryption, and OCR on scanned
    files.
    When to use: You need to do anything with a PDF, from combining files to filling a form to
    making a scan searchable.
    Search terms: pdf, merge pdf, split pdf, fill pdf form, ocr, watermark, extract tables,
    password protect pdf, scanned pdf
    Original description: Use this skill whenever the user wants to do anything with PDF files.
    This includes reading or extracting text/tables from PDFs, combining or merging multiple
    PDFs into one, splitting PDFs apart, rotating pages, adding watermarks, creating new PDFs,
    filling PDF forms, encrypting/decrypting PDFs, extracting images, and OCR on scanned PDFs to
    make them searchable. If the user mentions a .pdf file or asks to produce one, use this
    skill.

[pdftk-server]
    Source: awesome-copilot
    What it does: Uses the pdftk command-line tool to merge, split, rotate, encrypt, watermark,
    stamp, repair, and fill PDF files.
    When to use: You need to process PDFs in bulk or from the command line.
    Search terms: pdftk, merge pdf, split pdf, rotate pages, encrypt pdf, fill pdf form,
    watermark, repair pdf, command line
    Original description: Skill for using the command-line tool pdftk (PDFtk Server) for working
    with PDF files. Use when asked to merge PDFs, split PDFs, rotate pages, encrypt or decrypt
    PDFs, fill PDF forms, apply watermarks, stamp overlays, extract metadata, burst documents
    into pages, repair corrupted PDFs, attach or extract files, or perform any PDF manipulation
    from the command line.

[pitch-deck-visuals]
    Source: inference.sh superpowers
    What it does: Structures an investor pitch deck slide by slide, with visual design rules,
    chart choices, team slide guidance, and common investor turn-offs to avoid.
    When to use: You are raising money and need a pitch deck that investors take seriously.
    Search terms: pitch deck, investor presentation, fundraising, startup pitch, demo day, seed
    round, series a, grant proposal, vc pitch
    Original description: Investor pitch deck structure with slide-by-slide framework, visual
    design rules, and data presentation. Covers the 12-slide framework, chart types, team
    slides, and common investor turn-offs. Use for: fundraising decks, investor presentations,
    startup pitch, demo day, grant proposals. Triggers: pitch deck, investor deck, startup
    pitch, fundraising deck, demo day, pitch presentation, investor presentation, seed deck,
    series a deck, pitch slides, startup presentation, vc pitch, investor meeting

[pptx]
    Source: anthropic skills
    What it does: Creates, reads, edits, combines, and splits PowerPoint presentations,
    including templates, layouts, and speaker notes.
    When to use: You need a PowerPoint deck made or changed, or text pulled out of one.
    Search terms: powerpoint, pptx, slides, presentation, pitch deck, edit slides, speaker
    notes, powerpoint template
    Original description: Use this skill any time a .pptx or .potx file is involved in any way —
    as input, output, or both. This includes: creating slide decks, pitch decks, or
    presentations; reading, parsing, or extracting text from any .pptx or .potx file (even if
    the extracted content will be used elsewhere, like in an email or summary); editing,
    modifying, or updating existing presentations; combining or splitting slide files; working
    with templates (.potx), layouts, speaker notes, or comments. Trigger whenever the user
    mentions "deck," "slides," "presentation," or references a .pptx or .potx filename,
    regardless o…

[pptx-deck-context]
    Source: agents (bundle)
    What it does: Gathers the storyline, source material, and design direction needed before
    building a new editable PowerPoint deck, so the slides have a clear narrative and consistent
    look.
    When to use: You're about to build a PowerPoint deck and want the story, facts, and visual
    style nailed down first.
    Search terms: powerpoint, pptx, slide deck, presentation outline, deck storyline,
    presentation planning, slides, pitch deck prep
    Original description: Use when preparing the narrative, sources, and design context for a
    new editable PPTX deck.

[pptx-quality-gates]
    Source: agents (bundle)
    What it does: Checks an editable PowerPoint deck for layout problems, accessibility issues,
    broken files, and missing sources, and repairs what it finds.
    When to use: You have a finished PowerPoint and want to make sure it opens cleanly, looks
    right, and is accessible before sending it out.
    Search terms: powerpoint, pptx, check my slides, fix presentation, slide layout problems,
    accessibility, broken powerpoint, deck review, quality check
    Original description: Use when validating or repairing an editable PPTX deck for geometry,
    accessibility, native editability, source lineage, and OOXML package integrity.

[pptx-reference-deck-analysis]
    Source: agents (bundle)
    What it does: Studies an existing PowerPoint file to document its structure, colors, fonts,
    and layouts so new decks can match the same style.
    When to use: You want new slides to look like an existing company template or reference
    deck.
    Search terms: powerpoint, pptx, match our template, brand template, slide design, analyze
    presentation, deck style, fonts and colors, existing deck
    Original description: Use when analyzing a reference PPTX for read-only structure, theme,
    typography, layout rhythm, diagnostics, derived template catalogs, or safe OOXML package
    inspection.

[pptx-slide-specification]
    Source: agents (bundle)
    What it does: Writes or repairs a detailed, slide-by-slide blueprint (with exact positions
    and sizes) that is then used to generate an editable PowerPoint deck.
    When to use: You need a precise plan for every slide element before a PowerPoint is
    generated automatically.
    Search terms: powerpoint, pptx, slide layout, slide plan, presentation blueprint, deck spec,
    slide positions, generate slides
    Original description: Use when authoring or repairing a coordinate-explicit JSON
    specification for an editable PPTX deck.

[pptx-visual-assets]
    Source: agents (bundle)
    What it does: Chooses and places approved icons, images, diagrams, and infographics into an
    editable PowerPoint deck so slides look polished and on-brand.
    When to use: Your slides are mostly text and you want suitable visuals added in the right
    spots.
    Search terms: powerpoint, pptx, slide images, icons, infographics, diagrams, presentation
    visuals, make slides look better, stock images
    Original description: Use when selecting and placing approved supporting icons, images,
    SVGs, diagrams, or infographics in an editable PPTX deck.

[screen-recording]
    Source: awesome-copilot
    What it does: Creates annotated animated GIF demos and screen recordings to show how
    software works, for documentation or code review.
    When to use: You want a short animated demo of a feature or bug to include in documentation
    or a pull request.
    Search terms: screen recording, animated gif, demo video, screen capture, product demo, gif
    maker, annotate screenshots, documentation
    Original description: Create annotated animated GIF demos and screen recordings for pull
    requests and documentation. Covers frame capture, timing, imageio-based GIF creation, and
    per-frame annotation workflows.

[slides]
    Source: ui-ux-pro-max
    What it does: Builds polished web-based presentations with charts, responsive layouts, and
    persuasive slide copy tailored to the audience and purpose.
    When to use: You need a sharp presentation quickly and are happy for it to live in a browser
    rather than PowerPoint.
    Search terms: presentation, slides, html slides, slide deck, pitch deck, charts in slides,
    web presentation, keynote alternative
    Original description: Create strategic HTML presentations with Chart.js, design tokens,
    responsive layouts, copywriting formulas, and contextual slide strategies.

[xlsx]
    Source: anthropic skills
    What it does: Opens, creates, edits, cleans, and converts spreadsheet files such as Excel
    and CSV, including adding formulas, charts, formatting, and tidying messy data.
    When to use: You have a spreadsheet you need built, fixed, cleaned up, or converted to
    another format.
    Search terms: excel, spreadsheet, xlsx, csv, formulas, clean up data, pivot, charts in
    excel, convert csv, fix spreadsheet, google sheets export
    Original description: Use this skill any time a spreadsheet file is the primary input or
    output. This means any task where the user wants to: open, read, edit, or fix an existing
    .xlsx, .xlsm, .xltx, .csv, or .tsv file (e.g., adding columns, computing formulas,
    formatting, charting, cleaning messy data); create a new spreadsheet from scratch or from
    other data sources; or convert between tabular file formats. Trigger especially when the
    user references a spreadsheet file by name or path — even casually (like "the xlsx in my
    downloads") — and wants something done to it or produced from it. Also trigger for cleaning
    …
