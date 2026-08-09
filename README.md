<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:050816,45:4c1d95,100:06b6d4&text=Gin%C3%A9s%20Mart%C3%ADnez%20Ruiz&fontColor=ffffff&fontSize=42&fontAlignY=36&desc=AI%20%2F%20Backend%20Engineer%20%C2%B7%20Agentic%20Systems&descAlignY=58&animation=fadeIn" alt="Ginés Martínez Ruiz — AI and Backend Engineer" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2600&pause=900&color=22D3EE&center=true&vCenter=true&width=760&lines=Building+the+system+around+the+model;Agents+%C2%B7+Context+%C2%B7+Tools+%C2%B7+Data+%C2%B7+Infrastructure;Private+AI+that+gets+real+work+done" alt="Typing introduction" /></a>

**Designing production AI systems that connect models with software, enterprise data and business operations.**

`.NET` · `AI Agents` · `MCP` · `RAG` · `Local AI` · `PostgreSQL` · `SAP`

<br>

<img src="https://media1.tenor.com/m/N9tfR3_w9uYAAAAd/gojo-satoru-hollow-purple.gif" width="560" alt="Hollow Purple animation" />

<img src="./assets/system-online.svg" width="760" alt="AI runtime system online" />

</div>

<img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%" alt="Animated divider" />

## `> whoami`

<div align="center">
<img src="https://media1.tenor.com/m/LkQzw7k5DV4AAAAd/anime-hacking.gif" width="480" alt="Anime hacker at work" />
</div>

I'm an **AI / Backend Engineer focused on agentic systems**.

I engineer the system around the model: backend APIs, orchestration, tools, MCP servers, RAG pipelines, memory, databases, enterprise integrations and local inference.

My main backend stack is **C# / .NET**, supported by Python for AI and inference and Go for lightweight services and developer tooling. I approach AI as an **engineering problem**, not a prompting exercise.

> **I don't just want models that can talk.**<br>
> **I want models that can understand context, use tools, interact with systems and get real work done.**

```yaml
focus:
  - production agentic systems
  - AI orchestration and tool calling
  - MCP and enterprise integrations
  - RAG, memory and semantic retrieval
  - local and privacy-first inference
  - SAP / ERP-connected agents
```

---

## `> architecture`

### The model is one component

Systems where the model is only one component of a larger architecture.

```mermaid
flowchart TB
    U([User]) --> API[Backend API]
    API --> O[AI Orchestrator]
    O --> A[Agent Runtime]
    A --> M[MCP Client]
    A --> R[RAG Pipeline]
    A --> T[Tool Registry]
    A <--> L[Model Provider]

    M --> S[SAP / ERP]
    M --> E[Enterprise Services]
    R --> P[(PostgreSQL + pgvector)]
    T --> X[APIs / Databases]
    L --> LOCAL[Ollama · LM Studio · llama.cpp]

    classDef core fill:#4c1d95,stroke:#a78bfa,color:#fff,stroke-width:2px;
    classDef ai fill:#083344,stroke:#22d3ee,color:#fff,stroke-width:2px;
    classDef data fill:#111827,stroke:#64748b,color:#fff;
    class O,A core;
    class M,R,T,L ai;
    class API,S,E,P,X,LOCAL data;
```

<div align="center">

### Models + Context + Agents + Tools + Data + Infrastructure

</div>

### Local-first AI

I have a strong interest in running AI **locally and privately**: Ollama, LM Studio, llama.cpp, GGUF quantization, local embeddings, local RAG and on-device inference.

I believe a lot of business AI will run much closer to where the data lives—especially when that data is private, operational or sensitive.

### Enterprise AI

```text
Enterprise Data → ERP / SAP / SQL / APIs → Integration Layer
       → MCP + Tools + RAG → Agent Orchestration → LLM
```

Not replacing existing systems. **Building an intelligent, controlled layer on top of them.**

---

## `> tech --stack`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,dotnet,go,postgres,docker,kubernetes,linux,git,github,nginx,azure&perline=12" alt="AI engineering stack" />

<br><br>

![AI](https://img.shields.io/badge/AI-LLMs_%C2%B7_Agents_%C2%B7_RAG-7c3aed?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-Tools_%C2%B7_Context-0891b2?style=for-the-badge)
![Local AI](https://img.shields.io/badge/Local_AI-Ollama_%C2%B7_llama.cpp-111827?style=for-the-badge)
![Data](https://img.shields.io/badge/Data-pgvector_%C2%B7_HANA-2563eb?style=for-the-badge)

</div>

<table>
<tr>
<td valign="top" width="25%">

### Agents

Agent runtimes · MCP · Tool Calling · Memory · Planning · Multi-agent Systems · Guardrails

</td>
<td valign="top" width="25%">

### Knowledge

RAG · Embeddings · Hybrid Search · Reranking · pgvector · Grounding · Citations

</td>
<td valign="top" width="25%">

### Inference

Local LLMs · Ollama · llama.cpp · GGUF · Quantization · Speech · Multimodal AI

</td>
<td valign="top" width="25%">

### Platform

Python · .NET · Go · PostgreSQL · Docker · Linux · Kubernetes · Observability

</td>
</tr>
</table>

---

## `> ./current_lab.sh`

```console
gines@local-ai:~$ ./current_lab.sh
[+] building GINESAI.API on .NET 10
[+] designing Ontelia's enterprise intelligence layer
[+] connecting agents to MCP, RAG, SAP and real tools
[+] keeping private inference close to company data
```

### GINESAI.API

Reusable backend foundation for private AI agents and AI applications.

```text
.NET 10 · Minimal APIs · PostgreSQL · pgvector · Dapper · JWT
```

```text
Api
 ├── Auth / Users / Sessions / Chat
 ├── Application Services
 ├── Domain Rules
 ├── AI Orchestration
 │    ├── Agents
 │    ├── Models
 │    ├── Tools
 │    ├── Memory
 │    └── RAG
 ├── MCP
 └── Integrations
      ├── SAP
      ├── Ollama
      └── LM Studio
```

The backend owns deterministic behavior and authorization. Agents reason. Tools perform controlled actions. Integrations communicate with external systems.

### Ontelia

Future AI company and platform for creating an **intelligent layer over company infrastructure**.

```text
                     ONTELIA
                        │
                  ORCHESTRATOR
                        │
          ┌─────────────┼─────────────┐
          ▼             ▼             ▼
         MCP           RAG          AGENTS
          │             │             │
          ▼             ▼             ▼
      ERP / SAP      Knowledge     Workflows
      Databases      Documents        APIs
```

Its direction is local-first enterprise AI for companies with sensitive data: private inference, business capabilities exposed as typed tools, and agents operating with explicit permissions.

### Engineering right now

- **Agent runtimes** — orchestration, routing, memory, structured output and confirmation flows.
- **MCP infrastructure** — narrow, typed and permission-aware business capabilities.
- **Private RAG** — PostgreSQL + pgvector, hybrid retrieval, reranking, tenant isolation and citations.
- **Local inference** — Ollama, LM Studio, llama.cpp, GGUF and hardware-aware quantization.
- **SAP agents** — controlled access to sales, inventory, operations and enterprise workflows.
- **Production visibility** — traces, model/tool latency, tokens, errors and audit logs.

### Current signal

```yaml
status: building
mode: local_first
obsession: useful_agents
next_frontier:
  - advanced_rag
  - multi_agent_systems
  - inference_optimization
  - multimodal_and_edge_ai
  - enterprise_semantic_layers
```

<details>
<summary><b>Previous projects / origin story</b></summary>
<br>

These projects show where I came from; they are not necessarily under active development.

- **[AI Basic Studio](https://github.com/GinesMr/GoAiBasicStudio)** — Local LLM terminal environment built with Go, Bubble Tea and Ollama.
- **[Orbit Wallet](https://github.com/GinesMr/crypto_app)** · **[Backend](https://github.com/GinesMr/OrbitWalletBackend)** — Non-custodial Ethereum wallet built with Flutter and Go.
- **TerraEsphere** — IoT soil-monitoring system and winner of Spain's 2024 National Telecommunications Olympiad.

</details>

---

## `> cat philosophy.txt`

```text
What is deterministic?       → Backend code
What requires reasoning?     → Agent / LLM
What performs an action?     → Typed tool
How is it exposed?           → MCP / Integration
What knowledge is required?  → RAG / Database / API
Where should data live?      → Local / Enterprise infrastructure
What can cause harm?         → Authorization / Confirmation / Audit
```

```text
READ  → execute when authorized
WRITE → validate, authorize, confirm when sensitive, then audit
```

Models never receive raw credentials or unrestricted SQL. Business capabilities should be narrow, typed, validated, permission-aware and observable.

I optimize for **correctness, maintainability, architecture clarity, security and developer experience**—then performance and elegance, except where inference, streaming or retrieval changes the order.

<div align="center">

### The model is not the product.
### The system around the model is the product.

</div>

---

## `> git activity`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=GinesMr&show_icons=true&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=22d3ee&text_color=c9d1d9&rank_icon=github" alt="Ginés's GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GinesMr&layout=compact&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&langs_count=8" alt="Most used languages" />

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=GinesMr&bg_color=0d1117&color=a78bfa&line=22d3ee&point=ffffff&area=true&hide_border=true" alt="Contribution graph" />

</div>

---

<div align="center">

### Build the system around the model.

**Agents · Context · Tools · Data · Infrastructure**

<a href="https://www.linkedin.com/in/gin%C3%A9s-mart%C3%ADnez-ruiz-696b45354/"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://github.com/GinesMr?tab=repositories"><img src="https://img.shields.io/badge/GitHub-explore-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>

<br><br>

<sub>AI is much more interesting when it can actually do something.</sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:06b6d4,55:4c1d95,100:050816" alt="Footer" />

</div>
