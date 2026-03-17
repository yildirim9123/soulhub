# SoulHub: AI Agent SOUL.md Collection

> **182 specialized AI agent personalities** — From backend architects to game designers, from security analysts to marketing strategists. Each agent has a detailed SOUL.md defining its role, expertise, workflows, and deliverables.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)

---

## What Is This?

**SoulHub** is a curated collection of AI agent personalities, each defined by a `SOUL.md` file. These files serve as system prompts that give AI agents:

- **Deep domain expertise** — not generic templates, but specialized knowledge
- **Clear responsibilities** — defined role, core skills, and working rules
- **Structured workflows** — step-by-step processes and deliverable formats
- **Inter-agent collaboration** — how each agent communicates with teammates

Each agent directory contains a `SOUL.md` that can be used with Claude Code, AgentHub, or any AI agent framework.

---

## Quick Start

### Use with AgentHub (Recommended)

SoulHub is included as a git submodule in [AgentHub](https://github.com/yildirim9123/agenthub):

```bash
git clone https://github.com/yildirim9123/agenthub.git
cd agenthub
npm install  # automatically initializes submodules
```

### Use Standalone

```bash
git clone https://github.com/yildirim9123/soulhub.git
# Browse agents and copy SOUL.md files to your project
```

### Use with Claude Code

```bash
# Copy an agent's SOUL.md to your Claude Code config
cp soulhub/backend-developer/SOUL.md .claude/agents/backend-developer.md
```

---

## The Agent Roster

### Engineering (36 agents)

Building the future, one commit at a time.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [API Designer](api-designer/SOUL.md) | REST/GraphQL API design, OpenAPI specs | Designing and documenting APIs |
| [Backend Developer](backend-developer/SOUL.md) | Server-side logic, APIs, databases | Backend services, business logic, data layer |
| [Bash Agent](bash-agent/SOUL.md) | Shell scripting, CLI automation | System automation, scripting tasks |
| [Blender Add-on Engineer](blender-addon-engineer/SOUL.md) | Blender Python API, add-on development | Custom Blender tools and pipelines |
| [Chief Architect](chief-architect/SOUL.md) | System design, architecture decisions | High-level architecture, tech strategy |
| [Cloud Architect](cloud-architect/SOUL.md) | Cloud infrastructure, AWS/GCP/Azure | Cloud migration, infrastructure design |
| [Code Archaeologist](code-archaeologist/SOUL.md) | Legacy code analysis, codebase exploration | Understanding unfamiliar codebases |
| [Code Reviewer](code-reviewer/SOUL.md) | PR reviews, code quality, best practices | Code review, quality gates, mentoring |
| [Database Agent](database-agent/SOUL.md) | Schema design, query optimization | Database architecture, performance tuning |
| [Debugger](debugger/SOUL.md) | Bug diagnosis, root cause analysis | Tracking down and fixing bugs |
| [Developer Advocate](developer-advocate/SOUL.md) | DX, community building, developer content | Developer relations, documentation |
| [DevOps Engineer](devops-engineer/SOUL.md) | CI/CD, infrastructure automation | Pipeline development, deployment automation |
| [Embedded Firmware Engineer](embedded-firmware-engineer/SOUL.md) | Bare-metal, RTOS, ESP32/STM32 | IoT devices, embedded systems |
| [Feishu Integration Developer](feishu-integration-developer/SOUL.md) | Feishu/Lark platform, bots, workflows | Feishu ecosystem integrations |
| [Flutter Developer](flutter-developer/SOUL.md) | Dart, Flutter, cross-platform mobile | Cross-platform mobile apps |
| [Frontend Developer](frontend-developer/SOUL.md) | React/Vue/Angular, UI implementation | Modern web apps, responsive UIs |
| [Full Stack Developer](full-stack-developer/SOUL.md) | End-to-end web development | Full-stack features, rapid development |
| [Git Operations](git-operations/SOUL.md) | Git workflows, branching strategies | Git management, history cleanup |
| [Incident Response Commander](incident-response-commander/SOUL.md) | Incident management, post-mortems | Production incidents, on-call |
| [Integration Specialist](integration-specialist/SOUL.md) | System integration, API orchestration | Connecting disparate systems |
| [LSP/Index Engineer](lsp-index-engineer/SOUL.md) | Language Server Protocol, code intelligence | Code intelligence, semantic indexing |
| [MCP Builder](mcp-builder/SOUL.md) | Model Context Protocol servers | Building MCP servers for AI agents |
| [Mobile Developer](mobile-developer/SOUL.md) | iOS/Android native development | Native mobile applications |
| [n8n Expert](n8n-expert/SOUL.md) | n8n workflows, automation | No-code/low-code automation |
| [Rapid Prototyper](rapid-prototyper/SOUL.md) | Fast POC development, MVPs | Quick proof-of-concepts, hackathons |
| [React Developer](react-developer/SOUL.md) | React, Next.js, component architecture | React applications, SPA/SSR |
| [React Native Developer](react-native-developer/SOUL.md) | React Native, Expo | Cross-platform mobile with React |
| [Senior Developer](senior-developer/SOUL.md) | Advanced patterns, architecture | Complex implementations, mentoring |
| [Solidity Smart Contract Engineer](solidity-smart-contract-engineer/SOUL.md) | EVM contracts, DeFi protocols | Smart contracts, gas optimization |
| [Technical Debt Manager](technical-debt-manager/SOUL.md) | Refactoring strategy, debt tracking | Managing and reducing technical debt |
| [Technical Writer](technical-writer/SOUL.md) | Developer docs, API reference | Technical documentation |
| [Documentation Reviewer](documentation-reviewer/SOUL.md) | Doc quality, accuracy review | Documentation QA and improvement |
| [Terminal Integration Specialist](terminal-integration-specialist/SOUL.md) | CLI tools, terminal workflows | Developer tooling, terminal UX |
| [WeChat Mini Program Developer](wechat-mini-program-developer/SOUL.md) | WeChat ecosystem, Mini Programs | WeChat platform development |
| [Autonomous Optimization Architect](autonomous-optimization-architect/SOUL.md) | LLM routing, cost optimization | AI system cost and performance |
| [AI Data Remediation Engineer](ai-data-remediation-engineer/SOUL.md) | Self-healing pipelines, data quality | Fixing broken data at scale |

### AI & Data (6 agents)

Turning data into intelligence.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [AI/ML Engineer](aiml-engineer/SOUL.md) | ML models, deployment, AI integration | Machine learning features, model training |
| [Data Analyst](data-analyst/SOUL.md) | Data analysis, visualization, insights | Business intelligence, data exploration |
| [Data Engineer](data-engineer/SOUL.md) | Data pipelines, ETL/ELT, warehousing | Data infrastructure, pipeline development |
| [Data Consolidation Agent](data-consolidation-agent/SOUL.md) | Data aggregation, dashboard reports | Territory summaries, data consolidation |
| [Model QA Specialist](model-qa/SOUL.md) | ML audits, model evaluation | Machine learning model quality assurance |
| [Analytics Reporter](analytics-reporter/SOUL.md) | Dashboards, KPI tracking | Business reporting, data visualization |

### Design (10 agents)

Making it beautiful, usable, and delightful.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Brand Guardian](brand-guardian/SOUL.md) | Brand identity, consistency | Brand strategy, guidelines, positioning |
| [Image Prompt Engineer](image-prompt-engineer/SOUL.md) | AI image generation prompts | Midjourney, DALL-E, Stable Diffusion prompts |
| [Inclusive Visuals Specialist](inclusive-visuals-specialist/SOUL.md) | Representation, bias mitigation | Culturally accurate AI imagery |
| [Mobile Design Specialist](mobile-design-specialist/SOUL.md) | Mobile UI/UX patterns | Mobile-first design, app interfaces |
| [UI Designer](ui-designer/SOUL.md) | Visual design, component libraries | Interface creation, design systems |
| [UI/UX Designer](uiux-designer/SOUL.md) | End-to-end design, prototyping | Full design lifecycle, user flows |
| [User Researcher](user-researcher/SOUL.md) | User testing, behavior analysis | Usability testing, research insights |
| [UX Architect](ux-architect/SOUL.md) | Information architecture, CSS systems | Developer-friendly design foundations |
| [Visual Storyteller](visual-storyteller/SOUL.md) | Visual narratives, multimedia | Brand storytelling, visual content |
| [Whimsy Injector](whimsy-injector/SOUL.md) | Personality, delight, playful UX | Micro-interactions, Easter eggs |

### Testing & QA (16 agents)

Breaking things so users don't have to.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Accessibility Specialist](accessibility-specialist/SOUL.md) | WCAG auditing, assistive tech | Accessibility compliance, inclusive design |
| [API Tester](api-tester/SOUL.md) | API validation, integration testing | Endpoint verification, API QA |
| [Chaos Engineer](chaos-engineer/SOUL.md) | Failure injection, resilience testing | System resilience, fault tolerance |
| [Contract Tester](contract-tester/SOUL.md) | Consumer-driven contracts | API contract verification |
| [E2E Test Specialist](e2e-test-specialist/SOUL.md) | End-to-end test automation | Full workflow testing, Cypress/Playwright |
| [Evidence Collector](evidence-collector/SOUL.md) | Screenshot-based QA, visual proof | UI testing, bug documentation |
| [Infrastructure Tester](infrastructure-tester/SOUL.md) | Infrastructure validation | Cloud resource testing, IaC verification |
| [Mutation Tester](mutation-tester/SOUL.md) | Mutation testing, test quality | Test suite effectiveness analysis |
| [Penetration Tester](penetration-tester/SOUL.md) | Security testing, vulnerability assessment | Application security testing |
| [Performance Engineer](performance-engineer/SOUL.md) | Load testing, optimization | Performance tuning, bottleneck analysis |
| [QA Engineer](qa-engineer/SOUL.md) | Test planning, automation | Quality assurance, test strategy |
| [Reality Checker](reality-checker/SOUL.md) | Evidence-based certification | Production readiness, quality gates |
| [Test Results Analyzer](test-results-analyzer/SOUL.md) | Test evaluation, metrics | Test output analysis, coverage reporting |
| [Test Writer](test-writer/SOUL.md) | Unit/integration test authoring | Writing comprehensive test suites |
| [Testing Workflow Optimizer](testing-workflow-optimizer/SOUL.md) | Process optimization | Testing efficiency, CI optimization |
| [Tool Evaluator](tool-evaluator/SOUL.md) | Technology assessment | Tool selection, tech recommendations |

### Security (5 agents)

Defending the perimeter and beyond.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Agentic Identity & Trust Architect](agentic-identity-trust/SOUL.md) | Agent identity, authentication | Multi-agent identity systems, authorization |
| [Blockchain Security Auditor](blockchain-security-auditor/SOUL.md) | Smart contract audits, exploit analysis | Contract vulnerability assessment |
| [Identity Graph Operator](identity-graph-operator/SOUL.md) | Identity resolution, entity dedup | Cross-agent identity consistency |
| [Security Analyst](security-analyst/SOUL.md) | Threat modeling, security architecture | Application security, risk assessment |
| [Threat Detection Engineer](threat-detection-engineer/SOUL.md) | SIEM rules, threat hunting | Detection engineering, ATT&CK mapping |

### Marketing (14 agents)

Growing your audience, one authentic interaction at a time.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [App Store Optimizer](app-store-optimizer/SOUL.md) | ASO, conversion optimization | App discoverability, store optimization |
| [Book Co-Author](book-co-author/SOUL.md) | Thought-leadership books, ghostwriting | Strategic book collaboration |
| [Carousel Growth Engine](carousel-growth-engine/SOUL.md) | TikTok/Instagram carousels | Viral carousel content creation |
| [Content Creator](content-creator/SOUL.md) | Multi-platform content, editorial | Content strategy, copywriting |
| [Growth Hacker](growth-hacker/SOUL.md) | User acquisition, viral loops | Explosive growth, conversion optimization |
| [Instagram Curator](instagram-curator/SOUL.md) | Visual storytelling, community | Instagram strategy, aesthetic development |
| [LinkedIn Content Creator](linkedin-content-creator/SOUL.md) | Personal branding, B2B content | LinkedIn growth, professional audience |
| [Podcast Strategist](podcast-strategist/SOUL.md) | Podcast content, platform optimization | Podcast market strategy and operations |
| [Reddit Community Builder](reddit-community-builder/SOUL.md) | Authentic engagement, value-driven | Reddit strategy, community trust |
| [SEO Specialist](seo-specialist/SOUL.md) | Technical SEO, GEO, content strategy | Organic search growth, AI search optimization |
| [Short-Video Editing Coach](short-video-editing-coach/SOUL.md) | Post-production, editing workflows | Short-video editing training |
| [Social Media Strategist](social-media-strategist/SOUL.md) | Cross-platform strategy | Multi-platform social campaigns |
| [TikTok Strategist](tiktok-strategist/SOUL.md) | Viral content, algorithm optimization | TikTok growth, Gen Z audience |
| [Twitter Engager](twitter-engager/SOUL.md) | Real-time engagement, thought leadership | Twitter strategy, professional social |

### China Market (12 agents)

Navigating China's unique digital ecosystem.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Baidu SEO Specialist](baidu-seo-specialist/SOUL.md) | Baidu optimization, ICP compliance | Ranking in China's search market |
| [Bilibili Content Strategist](bilibili-content-strategist/SOUL.md) | B站 algorithm, danmaku culture | Building audiences on Bilibili |
| [China E-Commerce Operator](china-ecommerce-operator/SOUL.md) | Taobao, Tmall, Pinduoduo | Multi-platform China e-commerce |
| [Cross-Border E-Commerce](cross-border-ecommerce/SOUL.md) | Amazon, Shopee, Lazada | Cross-border fulfillment strategy |
| [Douyin Strategist](douyin-strategist/SOUL.md) | Douyin platform, short-video | China's leading short-video platform |
| [Kuaishou Strategist](kuaishou-strategist/SOUL.md) | Kuaishou, grassroots growth | Lower-tier market audiences |
| [Livestream Commerce Coach](livestream-commerce-coach/SOUL.md) | Host training, live room optimization | Livestream e-commerce operations |
| [Private Domain Operator](private-domain-operator/SOUL.md) | WeCom, private traffic | WeChat private domain ecosystems |
| [WeChat Official Account](wechat-official-account/SOUL.md) | Subscriber engagement, content | WeChat OA strategy, community |
| [Weibo Strategist](weibo-strategist/SOUL.md) | Sina Weibo, trending topics | Weibo operations and growth |
| [Xiaohongshu Specialist](xiaohongshu-specialist/SOUL.md) | Lifestyle content, trend-driven | Xiaohongshu growth, Gen Z audience |
| [Zhihu Strategist](zhihu-strategist/SOUL.md) | Knowledge-driven engagement | Zhihu authority building, Q&A strategy |

### Paid Media (7 agents)

Turning ad spend into measurable business outcomes.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Ad Creative Strategist](creative-strategist/SOUL.md) | RSA copy, Meta creative, ad assets | Creative launches, ad fatigue refreshes |
| [Paid Media Auditor](paid-media-auditor/SOUL.md) | 200+ point account audits | Account takeovers, quarterly reviews |
| [Paid Social Strategist](paid-social-strategist/SOUL.md) | Meta, LinkedIn, TikTok ads | Social ad programs, audience strategy |
| [PPC Campaign Strategist](ppc-strategist/SOUL.md) | Google/Microsoft/Amazon Ads | Account buildouts, budget allocation |
| [Programmatic & Display Buyer](programmatic-buyer/SOUL.md) | GDN, DSPs, ABM display | Display planning, partner outreach |
| [Search Query Analyst](search-query-analyst/SOUL.md) | Search term analysis, negatives | Query audits, wasted spend elimination |
| [Tracking & Measurement Specialist](tracking-specialist/SOUL.md) | GTM, GA4, conversion tracking | Tracking implementations, platform migrations |

### Sales (9 agents)

Turning pipeline into revenue through craft, not CRM busywork.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Account Strategist](account-strategist/SOUL.md) | Land-and-expand, QBRs | Post-sale expansion, account planning |
| [Deal Strategist](deal-strategist/SOUL.md) | MEDDPICC, competitive positioning | Deal scoring, win strategies |
| [Discovery Coach](discovery-coach/SOUL.md) | SPIN, Gap Selling, Sandler | Discovery call prep, qualifying |
| [Outbound Strategist](outbound-strategist/SOUL.md) | Signal-based prospecting | Research-driven outreach |
| [Pipeline Analyst](pipeline-analyst/SOUL.md) | Forecasting, pipeline health | Pipeline reviews, forecast accuracy |
| [Proposal Strategist](proposal-strategist/SOUL.md) | RFP response, win themes | Proposals that persuade |
| [Sales Coach](sales-coach/SOUL.md) | Rep development, call coaching | Making reps and deals better |
| [Sales Data Extraction Agent](sales-data-extraction-agent/SOUL.md) | Excel monitoring, metric extraction | Sales data ingestion, MTD/YTD metrics |
| [Sales Engineer](sales-engineer/SOUL.md) | Technical demos, POC scoping | Pre-sales technical wins |

### Product (7 agents)

Building the right thing at the right time.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Behavioral Nudge Engine](behavioral-nudge-engine/SOUL.md) | Behavioral psychology, nudge design | User motivation through behavioral science |
| [Business Analyst](business-analyst/SOUL.md) | Requirements, process modeling | Business requirements, process analysis |
| [Feedback Synthesizer](feedback-synthesizer/SOUL.md) | User feedback analysis | Feedback insights, product priorities |
| [Product Owner](product-owner/SOUL.md) | Product lifecycle, roadmap | Discovery, PRDs, GTM, outcome measurement |
| [Requirements Analyst](requirements-analyst/SOUL.md) | Requirements engineering | Functional/non-functional requirements |
| [Sprint Prioritizer](sprint-prioritizer/SOUL.md) | Agile planning, prioritization | Sprint planning, backlog management |
| [Trend Researcher](trend-researcher/SOUL.md) | Market intelligence, competitive analysis | Market research, opportunity assessment |

### Project Management (11 agents)

Keeping the trains running on time.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Agents Orchestrator](agents-orchestrator/SOUL.md) | Multi-agent coordination | Complex multi-agent workflows |
| [Experiment Tracker](experiment-tracker/SOUL.md) | A/B tests, hypothesis validation | Experiment management, data-driven decisions |
| [Jira Workflow Steward](jira-workflow-steward/SOUL.md) | Git workflow, Jira integration | Jira-linked Git discipline |
| [Orchestrator](orchestrator/SOUL.md) | Task delegation, workflow management | Team coordination, task routing |
| [Project Manager](project-manager/SOUL.md) | End-to-end project management | Project planning, delivery tracking |
| [Project Shepherd](project-shepherd/SOUL.md) | Cross-functional coordination | Stakeholder management, timelines |
| [Release Manager](release-manager/SOUL.md) | Release planning, deployment | Release coordination, version management |
| [Scrum Master](scrum-master/SOUL.md) | Scrum ceremonies, team facilitation | Agile coaching, sprint facilitation |
| [Studio Operations](studio-operations/SOUL.md) | Day-to-day efficiency | Operational excellence, team support |
| [Studio Producer](studio-producer/SOUL.md) | Portfolio management, orchestration | Multi-project oversight, resource allocation |
| [Workflow Architect](workflow-architect/SOUL.md) | Workflow discovery, mapping | Process mapping before code is written |

### Support & Operations (9 agents)

The backbone of the operation.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Accounts Payable Agent](accounts-payable-agent/SOUL.md) | Payment processing, vendor management | Autonomous payment execution |
| [Compliance Officer](compliance-officer/SOUL.md) | SOC 2, ISO 27001, HIPAA | Compliance certification guidance |
| [Executive Summary Generator](executive-summary-generator/SOUL.md) | C-suite communication | Executive reporting, strategic summaries |
| [Finance Tracker](finance-tracker/SOUL.md) | Financial planning, budgets | Financial analysis, cash flow |
| [Infrastructure Maintainer](infrastructure-maintainer/SOUL.md) | System reliability, performance | Infrastructure management, monitoring |
| [Legal Compliance Checker](legal-compliance-checker/SOUL.md) | Regulations, legal review | Legal compliance, risk management |
| [Monitoring Agent](monitoring-agent/SOUL.md) | System monitoring, alerting | Observability, health checks |
| [Report Distribution Agent](report-distribution-agent/SOUL.md) | Automated report delivery | Territory-based report distribution |
| [Support Responder](support-responder/SOUL.md) | Customer service, issue resolution | Customer support operations |

### Game Development (22 agents)

Building worlds, systems, and experiences across every major engine.

#### Cross-Engine (8 agents)

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Game Audio Engineer](game-audio-engineer/SOUL.md) | FMOD/Wwise, adaptive music, spatial audio | Interactive audio systems |
| [Game Designer](game-designer/SOUL.md) | Systems design, GDD, economy balancing | Game mechanics, progression systems |
| [Level Designer](level-designer/SOUL.md) | Layout theory, pacing, encounters | Level building, spatial narrative |
| [Mobile Game Developer](mobile-game-developer/SOUL.md) | Mobile-first game development | Mobile game projects |
| [Mobile Game LiveOps Developer](mobile-game-liveops-developer/SOUL.md) | Live operations, events, monetization | Mobile game live service |
| [Narrative Designer](narrative-designer/SOUL.md) | Story systems, branching dialogue | Branching narratives, world lore |
| [Technical Artist](technical-artist/SOUL.md) | Shaders, VFX, LOD pipeline | Art-to-engine optimization |
| [Web Game Developer](web-game-developer/SOUL.md) | Browser-based games, WebGL | Web game projects |

#### Unity (4 agents)

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Unity Architect](unity-architect/SOUL.md) | ScriptableObjects, DOTS/ECS | Large-scale Unity projects |
| [Unity Editor Tool Developer](unity-editor-tool-developer/SOUL.md) | EditorWindows, AssetPostprocessors | Custom Unity Editor tooling |
| [Unity Multiplayer Engineer](unity-multiplayer-engineer/SOUL.md) | Netcode, Relay/Lobby, prediction | Online Unity games |
| [Unity Shader Graph Artist](unity-shader-graph-artist/SOUL.md) | Shader Graph, HLSL, URP/HDRP | Custom materials, VFX shaders |

#### Unreal Engine (4 agents)

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Unreal Multiplayer Architect](unreal-multiplayer-architect/SOUL.md) | Replication, Dedicated Servers | Unreal online games |
| [Unreal Systems Engineer](unreal-systems-engineer/SOUL.md) | Gameplay systems, C++/Blueprint | Core Unreal systems |
| [Unreal Technical Artist](unreal-technical-artist/SOUL.md) | Materials, Niagara, optimization | Unreal visual pipeline |
| [Unreal World Builder](unreal-world-builder/SOUL.md) | Level streaming, World Partition | Open world, environment design |

#### Godot (3 agents)

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Godot Gameplay Scripter](godot-gameplay-scripter/SOUL.md) | GDScript, gameplay systems | Godot game logic |
| [Godot Multiplayer Engineer](godot-multiplayer-engineer/SOUL.md) | MultiplayerSpawner, ENet | Godot online games |
| [Godot Shader Developer](godot-shader-developer/SOUL.md) | Godot shading language, visual shaders | Godot visual effects |

#### Roblox (3 agents)

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Roblox Avatar Creator](roblox-avatar-creator/SOUL.md) | Avatar systems, UGC items | Roblox avatar customization |
| [Roblox Experience Designer](roblox-experience-designer/SOUL.md) | Experience design, monetization | Roblox game experiences |
| [Roblox Systems Scripter](roblox-systems-scripter/SOUL.md) | Luau, Roblox APIs | Roblox game systems |

### Spatial Computing (5 agents)

Building the immersive future.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [macOS Spatial/Metal Engineer](macos-spatial-metal-engineer/SOUL.md) | Swift, Metal, high-performance 3D | macOS spatial computing, Vision Pro native |
| [visionOS Spatial Engineer](visionos-spatial-engineer/SOUL.md) | Apple Vision Pro development | Vision Pro apps, spatial experiences |
| [XR Cockpit Interaction Specialist](xr-cockpit-interaction-specialist/SOUL.md) | Cockpit controls, immersive systems | Cockpit control interfaces |
| [XR Immersive Developer](xr-immersive-developer/SOUL.md) | WebXR, browser-based AR/VR | Browser-based immersive experiences |
| [XR Interface Architect](xr-interface-architect/SOUL.md) | Spatial interaction design | AR/VR/XR interface design |

### Specialized (13 agents)

The unique specialists who don't fit in a box.

| Agent | Specialty | When to Use |
|-------|-----------|-------------|
| [Automation Governance Architect](automation-governance-architect/SOUL.md) | Automation governance, workflow auditing | Evaluating business automations at scale |
| [Corporate Training Designer](corporate-training-designer/SOUL.md) | Enterprise training, curriculum | Training systems and learning programs |
| [Cultural Intelligence Strategist](cultural-intelligence-strategist/SOUL.md) | Global UX, representation | Software that resonates across cultures |
| [Document Generator](document-generator/SOUL.md) | PDF, PPTX, DOCX, XLSX generation | Professional document creation |
| [Explore Agent](explore-agent/SOUL.md) | Codebase exploration, discovery | Understanding project structure |
| [General-Purpose Agent](general-purpose-agent/SOUL.md) | Multi-domain, adaptable | General tasks, when no specialist fits |
| [Government Digital Presales Consultant](government-digital-presales-consultant/SOUL.md) | China ToG presales | Government digital transformation |
| [Healthcare Marketing Compliance](healthcare-marketing-compliance/SOUL.md) | Healthcare ad compliance | Healthcare marketing regulatory |
| [Plan Agent](plan-agent/SOUL.md) | Implementation planning | Architecture and implementation plans |
| [Recruitment Specialist](recruitment-specialist/SOUL.md) | Talent acquisition, recruiting | Recruitment strategy, hiring |
| [Study Abroad Advisor](study-abroad-advisor/SOUL.md) | International education | Study abroad planning |
| [Supply Chain Strategist](supply-chain-strategist/SOUL.md) | Supply chain, procurement | Supply chain optimization |
| [ZK Steward](zk-steward/SOUL.md) | Knowledge management, Zettelkasten | Connected knowledge bases |

---

## Agent Count by Division

| Division | Count |
|----------|-------|
| Engineering | 36 |
| AI & Data | 6 |
| Design | 10 |
| Testing & QA | 16 |
| Security | 5 |
| Marketing | 14 |
| China Market | 12 |
| Paid Media | 7 |
| Sales | 9 |
| Product | 7 |
| Project Management | 11 |
| Support & Operations | 9 |
| Game Development | 22 |
| Spatial Computing | 5 |
| Specialized | 13 |
| **Total** | **182** |

---

## SOUL.md Structure

Each agent's `SOUL.md` follows a consistent structure:

```markdown
# Agent Name

## Role
What the agent does and how it approaches work.

## Core Skills
Key competencies and areas of expertise.

## Tools
Available tools and how to use them.

## Working Rules
Guidelines, processes, and best practices.

## Output Format
Expected deliverable structure.

## Inter-Agent Collaboration
How this agent works with teammates.
```

---

## Contributing

1. Fork this repository
2. Create a new agent directory: `my-agent/SOUL.md`
3. Follow the SOUL.md structure above
4. Submit a pull request

---

## License

MIT License - see [LICENSE](LICENSE) for details.
