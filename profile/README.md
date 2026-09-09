# Hi there 👋
🙋‍♀️ **[iyulab](https://iyulab.com)** is a tech company based in Korea.

## 🚀 Our Services

### 🏭 Enterprise & Manufacturing Platforms
On-premises AI platforms for industrial and enterprise operations.
- **[Forge Tools](https://www.forge-tools.work)** - Local AI Desktop Tools for Industrial Professionals (SPC, FMEA, 8D, DOE, Lens, SOP)
- **[U-Sphere](https://marketplace.microsoft.com/en-us/product/iyulab1591071412301.u_sphere_app)** - E2E Unified AI Knowledge Service Platform
- **[U-MES](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/iyulab1591071412301.u_mes?tab=Overview)** - Manufacturing Execution System
- **[U-CMMS](https://iyulab.com/solutions/u-cmms)** - Computerized Maintenance Management System
- **[U-Vision](https://github.com/iyulab/U-Vision)** - Universal AI vision inspection PWA — VLM triages from day one, a dedicated ML model progressively takes over verdicts via a reliability flywheel; on-premises, zero external egress
- **[U-Board](https://github.com/iyulab/U-Board)** - Spatial dashboard authoring middleware — build data-bound views on a floor plan, network diagram, or map and embed them anywhere on the web, against any source system through its adapter surface

### 🗂️ Personal & Productivity Apps
Local-first apps with AI built in — for individuals and teams.
- **[Filer](https://www.filer-ai.com)** - AI-Powered File Management Utility
- **[Textree](https://www.textree.me)** ([repo](https://github.com/iyulab/textree)) - A pretty, free, local-first note app — free AI built in, one-click to the web.

## 💻 Open Source Projects

### 🧠 AI Agent Framework — ironhive Ecosystem
Core framework for building LLM-powered agent applications in .NET.
- **[ironhive](https://github.com/iyulab/ironhive)** - .NET pipeline framework for enterprise AI applications — multi-provider LLM integration, RAG pipelines, and multi-agent orchestration with a fluent builder API
- **[ironhive-host](https://github.com/iyulab/ironhive-host)** - Universal AI agent host for .NET — CLI, HTTP/SSE server, and embeddable SDK surfaces over one agent core
- **[ironbees](https://github.com/iyulab/ironbees)** - GitOps-style declarative AI agent management — define agents with YAML and Markdown, orchestrate multi-agent workflows, and track costs via TokenMeter
- **[ironhive-agent](https://github.com/iyulab/ironhive-agent)** - Reusable .NET agent engine with streaming loop, smart context compaction, MCP plugin integration, and built-in safety permission rules
- **[ironhive-flux](https://github.com/iyulab/ironhive-flux)** - Bridge SDK connecting IronHive with the Flux ecosystem for embedding generation, text completion, image-to-text, and RAG chatbot development

### 🔧 LLM Developer Tools
Utilities and SDKs for working with large language models.
- **[lm-supply](https://github.com/iyulab/lm-supply)** - On-demand local AI model inference for .NET — lazy loading, hardware-aware GPU/CPU selection, 10 task types including embeddings, generation, vision, and audio
- **[iron-prow](https://github.com/iyulab/iron-prow)** - Safe-inference gateway for .NET — provider selection (frontier/LAN), guardrails, and resilience, delivered as a standard `Microsoft.Extensions.AI` `IChatClient`
- **[memory-indexer](https://github.com/iyulab/memory-indexer)** - MCP server and .NET SDK implementing a 3-axis memory system (type × scope × tier) for LLM context management beyond finite context windows
- **[index-thinking](https://github.com/iyulab/index-thinking)** - .NET building block for LLM integration — truncation recovery, reasoning extraction, sliding-window context, and token budget monitoring
- **[ToolCallParser](https://github.com/iyulab/ToolCallParser)** - Unified .NET parser for LLM tool calls across 20+ providers with auto-detection and extensible custom parser support
- **[TokenMeter](https://github.com/iyulab/TokenMeter)** - Token counting, cost calculation, and session-based usage tracking across 12 LLM providers
- **[FluxGuard](https://github.com/iyulab/FluxGuard)** - 3-layer .NET guardrail library for LLM apps — covers prompt injection, jailbreaks, toxicity, PII masking, and format validation
- **[Loopai](https://github.com/iyulab/Loopai)** - Framework that compiles natural language specs into locally executable programs for cost-efficient, privacy-preserving AI task processing

### ⚡ AI Runtime & Automation
Execution environments and automation platforms for AI-integrated workflows.
- **[code-beaker](https://github.com/iyulab/code-beaker)** - Multi-runtime sandboxed code execution platform supporting Docker, Deno, Bun, Node.js, and Python via WebSocket and JSON-RPC 2.0
- **[Pulsa](https://github.com/iyulab/Pulsa)** - File-watching automation platform that chains audio conversion, speech-to-text, and LLM processing into document pipelines with MCP server integration
- **[momos](https://github.com/iyulab/momos)** - Autonomous inspection agent for runtime and UX defects static analysis misses — interacts with the running application in a sandbox and reports only reproduced findings, with the evidence

### 🧬 Ontology & Runtime Change
Ontology-driven storage, schema, and inference layers — including making an application's data model, and the UI over it, changeable at runtime.
- **[MorphDB](https://github.com/iyulab/MorphDB)** - Runtime-flexible PostgreSQL service with dynamic schema management, multi-protocol access (REST/GraphQL/OData), and multi-tenant support
- **[Formbase](https://github.com/iyulab/Formbase)** - Raw-first document engine — store data before designing its schema, then project a typed, queryable structure once you declare one. Built on MorphDB
- **[Eyu](https://github.com/iyulab/Eyu)** - Source-agnostic ontology inference engine — turns declared structure and raw records into proposed entities, relations, and grounded claims that cite the records backing them
- **[Formology](https://github.com/iyulab/Formology)** - Form-first development — treat the document as the domain model so a paper record's entities and relationships survive into the software instead of collapsing into CRUD tables
- **[vivarium](https://github.com/iyulab/vivarium)** - Sandboxed runtime for AI-generated UI — render untrusted generated code safely, with stable element identity and inspection built in. Changeset contract, agent harness, and lifecycle staging live in the sibling `vivarium-*` repositories
- **[saem](https://github.com/iyulab/saem)** - On-premises cross-system intelligence layer — connects data scattered across existing line-of-business systems into one ontology and answers with cited paths, read-only, ownership staying with the source systems

### 📄 RAG Pipeline — Flux Ecosystem
End-to-end Retrieval-Augmented Generation pipeline: Ingest → Parse → Preprocess → Index → Search.
- **[FluxFeed](https://github.com/iyulab/FluxFeed)** - .NET document ingestion pipeline for RAG — tracks a folder of files in a git-backed vault, extracts and chunks them, and keeps a vector index in sync
- **[FileFlux](https://github.com/iyulab/FileFlux)** - Transform PDF, DOCX, HWP, and more into RAG-optimized chunks via a 5-stage pipeline with Rust-based FFI readers
- **[WebFlux](https://github.com/iyulab/WebFlux)** - Crawl, extract, and chunk web content into RAG-ready formats with interface-based AI service integration
- **[FluxCurator](https://github.com/iyulab/FluxCurator)** - Zero-dependency text preparation for RAG — multilingual cleaning, PII masking, content filtering, and semantic chunking across 14 languages
- **[FluxImprover](https://github.com/iyulab/FluxImprover)** - LLM-powered quality layer for RAG pipelines — enriches chunks with summaries, keywords, QA pairs, and multi-stage quality scoring
- **[FluxIndex](https://github.com/iyulab/FluxIndex)** - Hybrid vector + keyword search with multi-backend storage (SQLite, PostgreSQL, Neo4j, Qdrant) and MCP server integration

### 📑 Document Parsing (Rust)
High-performance document extraction libraries written in Rust.
- **[unpdf](https://github.com/iyulab/unpdf)** - PDF extraction to Markdown/JSON with CJK/RTL support, multi-column layout detection, and Python/.NET/CLI bindings
- **[undoc](https://github.com/iyulab/undoc)** - Extract DOCX, XLSX, and PPTX into Markdown, plain text, or JSON with CJK support and .NET/Python bindings
- **[unhwp](https://github.com/iyulab/unhwp)** - Convert Korean HWP/HWPX documents to Markdown, plain text, and JSON with streaming API and .NET/Python bindings
- **[unrefine](https://github.com/iyulab/unrefine)** - Lossless, idempotent markdown shape-refinement pass for the un\* document extraction family
- **[uncad](https://github.com/iyulab/uncad)** - Parse, render (SVG/PNG), and write CAD DWG/DXF files — safe Rust FFI bindings over LibreDWG
- **[pageseer](https://github.com/iyulab/pageseer)** - Rasterize PDF, Office, and HWP/HWPX documents into per-page PNG/JPEG images via a unified pipeline

### ⚙️ High-Performance Industrial Libraries
Domain-agnostic optimization and analytics libraries for manufacturing and logistics.
- **[u-numflow](https://github.com/iyulab/u-numflow)** — Foundational mathematical, statistical, and probabilistic primitives with no external dependencies
- **[u-metaheur](https://github.com/iyulab/u-metaheur)** — Metaheuristic framework — GA, BRKGA, Simulated Annealing, ALNS, and Constraint Programming with trait-based domain separation
- **[u-geometry](https://github.com/iyulab/u-geometry)** — 2D/3D geometric primitives, polygon operations, collision detection, Minkowski sums, and spatial indexing
- **[u-analytics](https://github.com/iyulab/u-analytics)** — SPC control charts, process capability indices, Weibull reliability, change detection, and hypothesis testing
- **[u-insight](https://github.com/iyulab/u-insight)** — Statistical analysis engine with C FFI, C#, and WASM bindings — clustering, anomaly detection, PCA, regression, and data profiling
- **[u-schedule](https://github.com/iyulab/u-schedule)** — Job-shop scheduling framework combining dispatching rules, genetic algorithms, and constraint programming
- **[U-APS](https://github.com/iyulab/U-APS)** — Production scheduling system pairing Rust optimization algorithms with a C# SDK
- **[u-nesting](https://github.com/iyulab/u-nesting)** — 2D polygon nesting and 3D bin packing using GA, SA, and ALNS with No-Fit Polygon collision detection
- **[u-routing](https://github.com/iyulab/u-routing)** — Vehicle routing optimization (TSP, CVRP, VRPTW) with multiple solvers and WASM/npm support
- **[u-doe](https://github.com/iyulab/u-doe)** — Statistical Design of Experiments — factorial/RSM/Taguchi designs, ANOVA, power analysis, and multi-response optimization
- **[formulab](https://github.com/iyulab/formulab)** — 174 research-backed industrial engineering formulas across 14 domains with zero dependencies (TypeScript)
- **[online-tools](https://online-tools.work)** — 197 free, fast, and accurate calculators for engineering professionals

### 📊 ML & Data
Machine learning tooling and data management.
- **[MLoop](https://github.com/iyulab/MLoop)** - ML.NET CLI tool for automated model training with AutoML, dynamic scripting, and 15 task types from tabular classification to deep learning ([MCP server](https://github.com/iyulab/mloop-mcp))
- **[HoneAI](https://github.com/iyulab/HoneAI)** - Provenance-first predictions for .NET — layered ML+LLM reasoning with confidence-gated escalation and human-in-the-loop review
- **[DataLens](https://github.com/iyulab/DataLens)** - Exploratory data analysis library — profiles datasets with clustering, outlier detection, PCA, correlation, and changepoint detection
- **[Schemorph](https://github.com/iyulab/Schemorph)** - Declarative, SQL-first database schema management — diff desired-state SQL files against a live database and apply the reviewed plan, with procedures, functions, and versioned data migrations first-class (SQL Server, PostgreSQL)
- **[FilePrepper](https://github.com/iyulab/FilePrepper)** - Data preprocessing library and CLI — 30 transformation tasks with 67–90% I/O reduction via pipeline chaining
- **[DocuChef](https://github.com/iyulab/DocuChef)** - Template-driven document generation for Excel, PowerPoint, and Word with variable binding, collections, and custom functions

### 🖥️ Frontend & UI Components
Web components and UI libraries.
- **[formdown](https://github.com/iyulab/formdown)** - Markdown-like syntax for building interactive HTML forms — framework-agnostic web components with real-time validation ([formdown.dev](https://formdown.dev))
- **[u-widgets](https://github.com/iyulab/u-widgets)** - Declarative, data-driven web component library for data visualization — charts, KPIs, gauges, and tables with AI/MCP integration
- **[flex-table](https://github.com/iyulab/flex-table)** - Schema-agnostic data grid web component — virtual scrolling for 100k+ rows, inline editing, and Excel-compatible clipboard
- **[canvas-kit](https://github.com/iyulab/canvas-kit)** - Framework-neutral canvas library for visual editing — drag/resize/rotate, undo/redo, Konva.js designer, and lightweight HTML viewer
- **[Declart](https://github.com/iyulab/declart)** - Prose-first diagram library — declare structure in TOML/JSON, get publication-ready SVG output via Rust/WASM engine with VS Code live preview

### 📝 Docs & Publishing
- **[canopy](https://github.com/iyulab/canopy)** - Publishing renderer that turns a tree of markdown notes into a static website — stateless, app-agnostic, self-hostable
- **[canopy-page](https://github.com/iyulab/canopy-page)** - Authoring pipeline for documentation sites: one settings file, integrity checks, and a build

### 🛠️ Developer Tools
General-purpose libraries and utilities for developers across languages.
- **[m3l](https://github.com/iyulab/m3l)** - Markdown-based data modeling language — define schemas in plain Markdown, parsed into AST with models, enums, interfaces, inheritance, and multi-file imports
- **[mdd-booster](https://github.com/iyulab/mdd-booster)** - Model-driven code generator — one Markdown-based M3L data model becomes SQL schema files, EF Core entities and DbContext, and OData/GraphQL registration code
- **[docket](https://github.com/iyulab/docket)** - Work-queue service for headless workers — pull-model coordination for agent sessions spread across machines and repositories
- **[BareChat](https://github.com/iyulab/BareChat)** - Ultra-lightweight, embeddable chat module for .NET — single-DLL, in-process, zero-infra. Slack-style channel chat mounted with one line of middleware; embedded UI reused across web/PWA and WPF (WebView2), with SignalR realtime and VAPID web push
- **[cronex](https://github.com/iyulab/cronex)** - Extended cron expressions for .NET — timezone, interval, one-shot, jitter, stagger, window, and expiry in a single string, plus a minimal trigger engine. Zero-dependency core
- **[KoreanHolidays.NET](https://github.com/iyulab/KoreanHolidays.NET)** - Korean public holidays (including substitute holidays) for .NET — dependency-free (BCL only), multi-targets net8/9/10
- **[oops](https://github.com/iyulab/oops)** - Single-file version control tool — snapshot, diff, and restore any file without Git, powered by an embedded go-git library
- **[git-fresh](https://github.com/iyulab/git-fresh)** - Bring a git repo and all its submodules, recursively, to a fresh, up-to-date state against their remotes, stopping immediately on anything that could lose local work
- **[DollarSignEngine](https://github.com/iyulab/DollarSignEngine)** - Runtime C# expression evaluator powered by Roslyn — dynamic string interpolation, LINQ support, and expression caching
- **[FunctionX](https://github.com/iyulab/FunctionX)** - Excel-compatible formula engine — 38 built-in functions, Roslyn-powered compilation, and sandboxed async execution
- **[json-collection](https://github.com/iyulab/json-collection)** - JSON collection pipeline library that mimics MongoDB's aggregation pipeline syntax
- **[http-test](https://github.com/iyulab/http-test)** - API testing library that executes .http files with OAuth2, JSONPath assertions, JSON Schema validation, and concurrent test runs
- **[FastFind.NET](https://github.com/iyulab/FastFind.NET)** - Ultra-high performance file search — SIMD-optimized matching, direct NTFS MFT access, SQLite FTS5 indexing, and real-time monitoring
- **[WebLookup](https://github.com/iyulab/WebLookup)** - Lightweight URL discovery library — concurrent multi-provider web search (DuckDuckGo, Google, Tavily) with sitemap/robots.txt exploration
- **[ChildProcessGuard](https://github.com/iyulab/ChildProcessGuard)** - Cross-platform library guaranteeing child process termination when the parent exits — Windows Job Objects, Linux /proc, macOS native APIs
- **[system-harness](https://github.com/iyulab/system-harness)** - Unified computer-control library — shell execution, screen capture, OCR, input simulation, UI automation, and MCP server with 163 commands
- **[FlexiPane.WPF](https://github.com/iyulab/FlexiPane.WPF)** - Dynamic resizable and dockable pane management for WPF — interactive split overlays, nested layouts, and layout serialization
- **[TextDiff](https://github.com/iyulab/TextDiff)** - C# library for parsing and applying unified diffs — sync/async/streaming APIs, DiffX multi-file format, and LLM-generated diff tolerance
- **[vs-tools](https://github.com/iyulab/vs-tools)** - Visual Studio extension utilities — copy folder trees, extract text from selected files, and streamline clipboard operations on project items
- **[ObjectPath](https://github.com/iyulab/ObjectPath)** - .NET library for retrieving values from objects using string path expressions — dot notation, bracket indexing, and reflection caching
- **[shell-tunnel](https://github.com/iyulab/shell-tunnel)** - Single-binary tool exposing remote terminal access via REST and WebSocket API with cross-platform PTY support and API key authentication

### 🔐 Auth & Infrastructure
- **[Authway](https://github.com/iyulab/Authway)** - Standards-compliant OAuth 2.0 / OIDC platform built on Ory Hydra — multi-tenancy, PKCE, passwordless flows, TypeScript SDKs for vanilla JS, React, and Next.js
- **[Sendway](https://github.com/iyulab/Sendway)** - Unified .NET backend for transactional messaging — one API over email, SMS, push, and chat channels, with per-channel delivery, retries, and history handled for you
- **[OrbitMesh](https://github.com/iyulab/OrbitMesh)** - .NET infrastructure SDK for distributed systems — abstracts WebSocket connectivity, message reliability, job orchestration, and state synchronization via SignalR
- **[system-coroner](https://github.com/iyulab/system-coroner)** - Automated server intrusion forensics — collects evidence via PowerShell/Bash, applies Sigma rules, and generates LLM-powered HTML reports with MITRE ATT&CK mapping

👉 [View all repositories](https://github.com/orgs/iyulab/repositories)

---

## 🌈 Contribution Guidelines
We welcome community contributions! Feel free to open issues, submit PRs, or join our discussions.

## 👩‍💻 Useful Resources
- 📚 Check out our [documentation](../../../wiki)
- 💬 Join [discussions](../../../discussions) for questions and ideas
- 🔗 Visit our website: [iyulab.com](https://iyulab.com)
