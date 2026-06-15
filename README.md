<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Justin%20Stevenson%20Theodorus&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%E2%80%A2%20AI%2FML%20Researcher%20%E2%80%A2%20Full-Stack%20Builder&descAlignY=60&descSize=16" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3500&pause=800&color=A78BFA&center=true&vCenter=true&multiline=false&width=700&lines=CS+%40+NUS;ICLR+2025+Workshop+Co-Author;1st+Place+%E2%80%A2+PINUS+Hack+2026;Building+Systems+That+Scale" alt="Typing SVG" />
</a>

<br/>

![NUS](https://img.shields.io/badge/NUS-Computer%20Science-6D28D9?style=flat-square&logo=academia&logoColor=white)
![SMU](https://img.shields.io/badge/SMU-Dean's%20List%20AY24%2F25-4F46E5?style=flat-square&logo=academia&logoColor=white)
![Location](https://img.shields.io/badge/Singapore-SG-8B5CF6?style=flat-square&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-justintheodorus.com-6D28D9?style=for-the-badge&logo=vercel&logoColor=white)](https://justintheodorus.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/justin-theodorus)
[![Email](https://img.shields.io/badge/Email-Contact-7C3AED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:justin.theodorus@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-8B5CF6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/justin-theodorus)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=justin-theodorus&color=7C3AED&style=flat-square&label=Profile+Views)
![GitHub Followers](https://img.shields.io/github/followers/justin-theodorus?color=6D28D9&label=Followers&logo=github&style=flat-square)
![GitHub Stars](https://img.shields.io/github/stars/justin-theodorus?color=4F46E5&label=Total+Stars&logo=github&style=flat-square)

</div>

---

## ◈ About

<img alt="Coding" src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="360" align="right"/>

I'm a **Software Engineer and AI/ML Engineer** pursuing a Bachelor of Computing in Computer Science (Database Systems Specialization, Minor: Quantitative Finance + Mathematics) at the **National University of Singapore**. I transferred from SMU with a **Dean's List** recognition.

My engineering work spans production full-stack systems, agentic AI pipelines, and mechanistic interpretability research. I've built platforms serving **1,000+ active users**, co-authored a paper accepted to the **ICLR 2025 Workshop on Building Trust in Language Models**, and placed in competitive hackathons across Singapore.

I approach engineering with a product mindset: I care about systems that scale, code that ships, and AI that behaves reliably. Whether I'm designing microservices architectures, tuning RAG pipelines for latency, or conducting SAE activation analysis on large language models, I build with intention.

Currently targeting **Software Engineering internships for 2027** across SWE, AI/ML, and full-stack tracks.

**Open to:** SWE Internships · AI/ML Engineering · Research Collaborations · Open Source

<br clear="right"/>

---

## ◈ Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,ts,js,go,java,cpp,bash,html,css&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,redux,expo&theme=dark" />

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,postgres,supabase,neo4j,redis&theme=dark" />

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=aws,gcp,docker,jenkins,github,linux,vercel&theme=dark" />

</div>

---

## ◈ AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|---|:---:|---|
| RAG Pipelines | ████████░░ Advanced | pgvector, text-embedding-3-small, chunking strategies, prompt compression |
| LLM Engineering | ████████░░ Advanced | Multi-model routing, prompt chaining, fine-tuning, response caching |
| Mechanistic Interpretability | ███████░░░ Proficient | Sparse Autoencoders, SAELens, Gemma-2B activation analysis |
| Agentic Systems | ███████░░░ Proficient | LangGraph multi-agent, MCP tool servers, escalation routing |
| ML Modeling | ███████░░░ Proficient | Gradient Boosting, Scikit-learn, feature importance, hyperparameter search |
| NLP / Transformers | ██████░░░░ Intermediate | FinBERT, HuggingFace Transformers, sentiment extraction, CoT analysis |
| Computer Vision | █████░░░░░ Intermediate | DeepFace emotion detection, AR camera integration |

</div>

---

## ◈ Featured Projects

<details>
<summary><b>🔬 Algoverse — Finding Sparse Autoencoder Representations of Errors in CoT Prompting</b></summary>
<br/>

> Published at the **ICLR 2025 Workshop on Building Trust in Language Models and Applications**

Applied Sparse Autoencoders (SAEs) and SAELens to 1,000 annotated chain-of-thought samples generated by Gemma-2B on the GSM8K dataset. Mapped neuron-level activations to 9 distinct reasoning error types — including hallucination, arithmetic errors, and coherency failures — contributing a novel methodology for interpretable CoT debugging.

| Attribute | Details |
|---|---|
| **Stack** | Python · PyTorch · SAELens · Transformers · Pandas · Seaborn |
| **Model** | Gemma-2B (2 billion parameters) |
| **Dataset** | 1,000 annotated CoT samples from GSM8K |
| **Error Taxonomy** | 9 categories derived from ROSCOE metrics |
| **Impact** | Published — ICLR 2025 Workshop Tiny Paper |
| **Repository** | [OpenReview Paper](https://openreview.net/pdf?id=oCprwPRqwW) |

Designed an end-to-end analysis pipeline: activation capture at consistent transformer layers, SAE feature extraction, correlation analysis between sparse features and error labels, cluster analysis via k-means, and classifier training to assess whether sparsification enhances interpretability over raw embeddings.

<br/>
</details>

<details>
<summary><b>🏆 SABI — AI Tutoring Platform · Top 5 Dell InnovateDash 2026</b></summary>
<br/>

> **Top 5 Finalist** at Dell InnovateDash 2026

A 10-service microservices AI tutoring platform with LLM-powered NPC dialogue, rules-based persona classification, and real-time emotion detection. Stress-tested under concurrent load with production-grade observability.

| Attribute | Details |
|---|---|
| **Stack** | TypeScript · Python · Next.js · FastAPI · Docker · Redis · Claude · DeepFace |
| **Architecture** | 10 microservices via Docker Compose + Kong Gateway |
| **Scale** | 20+ concurrent users stress-tested via Locust |
| **Performance** | 97.7% request success rate · 500ms DeepFace emotion detection intervals |
| **AI** | LLM NPC dialogue · 3-profile persona classifier · 5-dimension Claude scoring pipeline · 7 emotion classes |
| **Repository** | [github.com/justin-theodorus/sabi](https://github.com/justin-theodorus/sabi) |

Implemented Kong API Gateway for inter-service routing, DeepFace emotion detection at 500ms polling intervals, and a Claude evaluation pipeline scoring five distinct learner competence dimensions across two adaptive learning modes.

<br/>
</details>

<details>
<summary><b>🎨 ArtMatch — AI Art Discovery App · 1st Place PINUS Hack 2026</b></summary>
<br/>

> **1st Place** at PINUS Hack 2026

A mobile art discovery app combining Tinder-style swipe UI, AR in-room artwork preview, and Claude-powered natural language gallery search — built end-to-end in a hackathon setting.

| Attribute | Details |
|---|---|
| **Stack** | TypeScript · Python · React Native · FastAPI · Supabase · Claude AI · Expo Camera · Scikit-learn |
| **AI** | Claude natural language gallery search · Hybrid collaborative filtering recommendation engine |
| **AR** | Real-time in-room artwork placement via Expo Camera |
| **Catalog** | 55+ artworks indexed |
| **Award** | 🥇 1st Place — PINUS Hack 2026 |
| **Repository** | [github.com/justin-theodorus/artmatch](https://github.com/justin-theodorus/artmatch) |

Architected the full-stack system with hybrid collaborative filtering using Scikit-learn, AR camera integration for real-time placement, and a swipe-based preference engine seeding the recommendation model from user interactions.

<br/>
</details>

<details>
<summary><b>🚢 Cargill Ocean Transportation Datathon — Vessel Allocation Optimizer · 2nd Place</b></summary>
<br/>

> **2nd Place** at Cargill Ocean Transportation Datathon 2026

A vessel-cargo allocation optimization system analyzing 165 voyage combinations to maximize fleet profitability, with a GPT-4 natural language querying interface.

| Attribute | Details |
|---|---|
| **Stack** | Python · Gradient Boosting · GPT-4 · Jupyter Notebook |
| **Scale** | 165 voyage combinations analyzed |
| **Performance** | Gradient Boosting Risk Model, R² = 0.99 |
| **Financial Impact** | $3.7M simulated portfolio profit |
| **AI** | GPT-4 conversational interface for NL querying |
| **Award** | 🥈 2nd Place — Cargill Ocean Transportation Datathon 2026 |

Implemented freight rate calculations, TCE optimization, and FFA market pricing analysis. Built ML risk model with Gradient Boosting (R² = 0.99) for feature importance analysis, identifying key profitability drivers across 165 voyage combinations to inform cargo allocation decisions.

<br/>
</details>

<details>
<summary><b>🌿 Embege — Agentic Kitchen Co-Pilot · Most Social Impact, AWS Forge the Future 2026</b></summary>
<br/>

> **Most Social Impact Award** at AWS Forge the Future Hackathon 2026

An agentic kitchen co-pilot built on AWS Bedrock and Elastic Agent Builder, autonomously chaining tools across a 5,000+ recipe knowledge base.

| Attribute | Details |
|---|---|
| **Stack** | JavaScript · ReactJS · AWS Bedrock · Elasticsearch |
| **AI** | Claude Sonnet via AWS Bedrock · Elastic Agent Builder |
| **Scale** | 5,000+ recipes · 4 Elasticsearch indices |
| **Agentic Depth** | 4+ ES\|QL tools chained per session |
| **Award** | 🏅 Most Social Impact — AWS Forge the Future Hackathon 2026 |
| **Repository** | [github.com/justin-theodorus/embege](https://github.com/justin-theodorus/embege) |

Designed proactive pantry briefing workflows where the agent autonomously determines ingredient availability, suggests recipes, and chains Elasticsearch tool calls without explicit user prompts per step.

<br/>
</details>

<details>
<summary><b>🤖 BayMini — Voice-First AI Care Companion · Synapxe IMDA AI Innovation Challenge 2026</b></summary>
<br/>

> Submitted to the **Synapxe IMDA AI Innovation Challenge 2026**

A multilingual, voice-first AI care companion with a 3-agent LangGraph system, RAG-grounded clinical responses, and a deterministic safety escalation gate.

| Attribute | Details |
|---|---|
| **Stack** | TypeScript · Python · Next.js · FastAPI · LangGraph · pgvector |
| **AI** | 3-agent LangGraph architecture · 5 MCP tool servers · RAG clinical grounding |
| **Voice** | Deepgram STT · Azure TTS · 4 language support |
| **Safety** | Deterministic safety gate · 4 escalation paths |
| **Repository** | [github.com/justin-theodorus/baymax](https://github.com/justin-theodorus/baymax) |

Implemented RAG-grounded clinical response generation with pgvector, a deterministic safety routing layer classifying input severity across four escalation paths, and multilingual voice I/O via Deepgram and Azure Cognitive Services.

<br/>
</details>

<details>
<summary><b>📋 Student Founder OS — AI Capacity Management · 1st Runner-Up NTU Product Club × Notion Ideathon 2026</b></summary>
<br/>

> **1st Runner-Up** at NTU Product Club × Notion Ideathon 2026

An AI-governed capacity management system that prevents student founder overcommitment through deterministic validation and AI-negotiated tradeoff prompts.

| Attribute | Details |
|---|---|
| **Stack** | Node.js · TypeScript · Anthropic · Notion |
| **AI** | Claude-negotiated tradeoff prompts · adaptive constraint tuning |
| **Core Logic** | Deterministic capacity validation intercepting task additions |
| **Award** | 🥈 1st Runner-Up — NTU Product Club × Notion Ideathon 2026 |
| **Repository** | [github.com/justin-theodorus/student-founder-mcp](https://github.com/justin-theodorus/student-founder-mcp) |

Built a deterministic capacity validation layer that intercepts every task addition, calculates cumulative workload against weekly limits, blocks overcommitment, and triggers AI-negotiated tradeoff prompts — logging decision patterns for adaptive constraint tuning over time.

<br/>
</details>

---

## ◈ Experience

**Incoming Artificial Intelligence Engineer Intern** · Alpha Z · Singapore
`Aug 2026 – Dec 2026`

`Incoming`

---

**Software Engineer Intern** · Computing for Voluntary Welfare Organisations (partnered with GIC) · Singapore
`May 2026 – Aug 2026`

Engineered features for Cornerstone, a Go and React/TypeScript case management platform serving 5 social service agencies in Singapore. Extended the Custom Module with new field types and entity association relationships across 8 architectural layers — from cardinality-enforced PostgreSQL schemas to reusable frontend components — enabling no-code configurations. Onboarded Signpost Collective by migrating 200+ peddler profiles and 1,000+ case records across 5 regional teams, translating stakeholder requirements into an ERD and data migration plan. Resolved 10 critical full-stack bugs across GORM query caching, transaction boundaries, and Redux state management, eliminating silent failures.

`Go` `React` `TypeScript` `PostgreSQL` `Redux` `GORM` `Docker`

---

**Chief Technology Officer** · ElevatEd · Jakarta, Indonesia
`Aug 2025 – Jan 2026`

Scaled ElevAI to 1,000+ active users across Indonesia by identifying LLM routing as a single point of failure and architecting a load-balanced cloud deployment with per-service horizontal scaling, shipping 3 major feature releases in 5 months. Reduced LLM operational costs by 30% by architecting a semantic caching layer and a syllabus-constrained RAG pipeline using Redis and asynchronous worker pools.

`Next.js` `FastAPI` `Supabase` `RAG` `Redis` `OpenAI` `Vercel` `Git`

---

**Software Engineering Resident** · Headstarter · USA (Remote)
`Jul 2025 – Jan 2026`

Built and deployed 5 projects including AI-powered full-stack applications on AWS and Vercel. Developed a RAG-based Q&A system achieving 40% query response time reduction via multi-step prompt chaining. Engineered a multi-model LLM routing platform supporting 3 providers (Claude Haiku, GPT-4o Mini, Gemini Flash 2.5) with a configurable weighted scoring system balancing cost, quality, and latency per request.

`Python` `TypeScript` `AWS` `Next.js` `FastAPI` `React` `Vercel` `LLM Routing`

---

**Cybersecurity Engineer Intern** · Halodoc · Jakarta, Indonesia
`May 2025 – Jul 2025`

Reduced manual account management overhead by 20% across Google Workspace provisioning and deprovisioning by diagnosing a broken Jenkins-Python pipeline and re-engineering API calls with asynchronous execution and retry logic. Accelerated threat response by 70% by designing an AWS Lambda-based threat prioritization pipeline ingesting alerts from SOCRadar and SIEM sources, applying priority scoring logic for real-time routing to Slack.

`Python` `Jenkins` `AWS Lambda` `GitLab` `Google Workspace` `SOCRadar`

---

**Teaching Assistant** (COR-IS1704: Computational Thinking & Programming) · Singapore Management University
`Jan 2025 – May 2025`

Supported 60+ students in Python fundamentals through weekly consultations and cohort-wide grading. Developed additional practice problem sets and conducted targeted review sessions for underperforming students.

`Python` `Teaching` `Curriculum Support`

---

**Machine Learning Researcher** · Algoverse · USA (Remote)
`Nov 2024 – Mar 2025`

Analyzed 1,000 annotated chain-of-thought samples using Sparse Autoencoders on Gemma-2B. Mapped neuron activations to 9 distinct reasoning error types and co-authored a paper accepted to the ICLR 2025 Workshop on Building Trust in Language Models.

`Python` `PyTorch` `SAELens` `Transformers` `Pandas` `Seaborn` `Research`

---

## ◈ Achievements

<div align="center">

| Recognition | Details |
|:---:|---|
| 🥇 1st Place | PINUS Hack 2026 — ArtMatch |
| 🥈 2nd Place | Cargill Ocean Transportation Datathon 2026 — $3.7M portfolio profit |
| 🏅 Top 5 Finalist | Dell InnovateDash 2026 — SABI |
| 🏅 Most Social Impact | AWS Forge the Future Hackathon 2026 — Embege |
| 🥈 1st Runner-Up | NTU Product Club × Notion Ideathon 2026 — Student Founder OS |
| 📄 ICLR 2025 Workshop | Co-author — Building Trust in Language Models, Algoverse AI Research |
| 🎓 Dean's List | SMU SCIS AY 2024/2025 — GPA 4.0/4.0 |

</div>

---

## ◈ GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=justin-theodorus&show_icons=true&theme=algolia&include_all_commits=true&count_private=true&title_color=A78BFA&icon_color=7C3AED&bg_color=0D0D0D&border_color=0D0D0D"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=justin-theodorus&layout=compact&langs_count=8&theme=midnight-purple&hide_border=true&bg_color=0D0D0D&title_color=A78BFA&text_color=C4B5FD&hide=php"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=justin-theodorus&theme=midnight-purple&hide_border=true&background=0D0D0D&ring=7C3AED&fire=A78BFA&currStreakLabel=C4B5FD&sideLabels=C4B5FD&currStreakNum=A78BFA&sideNums=C4B5FD&dates=6D28D9" alt="GitHub Streak"/>

</div>

---

## ◈ GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=justin-theodorus&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=7&title_color=A78BFA" alt="GitHub Trophies"/>

</div>

---

## ◈ Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=justin-theodorus&bg_color=0D0D0D&color=A78BFA&line=7C3AED&point=C4B5FD&area=true&area_color=4F46E5&hide_border=true&theme=react-dark" width="100%" alt="Contribution Graph"/>

</div>

---

## ◈ Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/justin-theodorus/justin-theodorus/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/justin-theodorus/justin-theodorus/output/github-snake.svg" />
  <img alt="github snake" src="https://raw.githubusercontent.com/justin-theodorus/justin-theodorus/output/github-snake-dark.svg" />
</picture>

</div>

---

## ◈ Current Focus

```yaml
justin_theodorus:
  role: CS Undergraduate @ NUS | SWE Intern Candidate 2027
  location: Singapore, SG

  learning:
    - Advanced database internals (Database Systems Specialization)
    - Quantitative methods (Minor: Quantitative Finance)
    - System design for distributed, high-throughput services

  building:
    - CVWO: Cornerstone case management platform (Go + React/TypeScript)
    - RAG-based AI chatbot companion for personal website
    - Open source contributions

  exploring:
    - System design at scale
    - CI/CD in trading and quant-adjacent, low-latency infrastructure

  open_to:
    - Software Engineering Internships (SWE, AI/ML, Full-Stack)
    - ML Research Collaborations
    - Hackathon Teams building something ambitious
```

---

## ◈ Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-justin.theodorus%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:justin.theodorus@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-justin--theodorus-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/justin-theodorus)
[![GitHub](https://img.shields.io/badge/GitHub-justin--theodorus-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/justin-theodorus)

</div>

---

<div align="center">

*"The best engineers don't just write code — they build systems that outlast the sprint."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer" width="100%"/>

</div>
