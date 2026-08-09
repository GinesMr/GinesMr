<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:050816,45:4c1d95,100:06b6d4&text=Gin%C3%A9s%20Mart%C3%ADnez%20Ruiz&fontColor=ffffff&fontSize=42&fontAlignY=36&desc=AI%20Systems%20%C2%B7%20Agentic%20Engineering%20%C2%B7%20Local%20AI&descAlignY=58&animation=fadeIn" alt="Ginés Martínez Ruiz" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2600&pause=900&color=22D3EE&center=true&vCenter=true&width=760&lines=Building+the+system+around+the+model;Agents+%C2%B7+Context+%C2%B7+Tools+%C2%B7+Data+%C2%B7+Infrastructure;Private+AI+that+gets+real+work+done" alt="Typing introduction" /></a>

**Building AI systems that connect models with real software, private data and enterprise infrastructure.**

`LLMs` · `AI Agents` · `MCP` · `RAG` · `Local AI` · `.NET` · `Python` · `Go`

<br>

<img src="https://media1.tenor.com/m/N9tfR3_w9uYAAAAd/gojo-satoru-hollow-purple.gif" width="560" alt="Hollow Purple animation" />

</div>

<img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%" alt="Animated divider" />

## `> whoami`

I'm a software engineer focused on **AI systems and agentic architectures**.

I work on the layer between **LLMs and the real world**: orchestration, tools, MCP servers, RAG pipelines, vector databases, enterprise integrations and local inference.

My background is in backend and application development, so I approach AI as an **engineering problem**, not just a prompting problem.

> **I don't just want models that can talk.**<br>
> **I want models that can understand context, use tools, interact with systems and get real work done.**

```yaml
focus:
  - agentic AI systems
  - local and privacy-first LLM infrastructure
  - MCP, RAG and semantic retrieval
  - tool calling and multi-agent orchestration
  - ERP / SAP-connected agents
  - local inference and edge AI
```

---

## `> architecture`

### Agentic systems

Systems where the model is only one component of a larger architecture.

```text
                         ┌──────────────────┐
                         │       USER       │
                         └────────┬─────────┘
                                  │
                                  ▼
                    ┌──────────────────────────┐
                    │    AGENT ORCHESTRATOR    │
                    │                          │
                    │  reasoning · context     │
                    │  routing · tool calling  │
                    └────────────┬─────────────┘
                                 │
             ┌───────────────────┼───────────────────┐
             │                   │                   │
             ▼                   ▼                   ▼
      ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
      │     MCP     │     │     RAG     │     │    TOOLS    │
      │   Servers   │     │  Knowledge  │     │ APIs / DBs  │
      └──────┬──────┘     └──────┬──────┘     └──────┬──────┘
             │                   │                   │
             ▼                   ▼                   ▼
        ERP / SAP          PostgreSQL           External
        Services            pgvector             Systems
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │        LOCAL LLM         │
                    │  Ollama · LM Studio      │
                    │  llama.cpp · GGUF        │
                    └──────────────────────────┘
```

<div align="center">

### Give models context, memory, tools and controlled access to real systems.

</div>

### Local-first AI

I have a strong interest in running AI **locally and privately**: Ollama, LM Studio, llama.cpp, GGUF quantization, local embeddings, local RAG and on-device inference.

I believe a lot of business AI will run much closer to where the data lives—especially when that data is private, operational or sensitive.

### Enterprise AI

```text
Enterprise Data → ERP / SAP / SQL / APIs → Integration Layer
       → MCP + Tools + RAG → Agent Orchestration → LLM
```

Not replacing existing systems. **Building an intelligent layer on top of them.**

---

## `> tech --stack`

<div align="center">

<img src="https://skillicons.dev/icons?i=dotnet,python,go,flutter,postgres,mongodb,docker,kubernetes,linux,git,github,nginx&perline=12" alt="Technology stack" />

<br><br>

![AI](https://img.shields.io/badge/AI-LLMs_%C2%B7_Agents_%C2%B7_RAG-7c3aed?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-Tools_%C2%B7_Context-0891b2?style=for-the-badge)
![Local AI](https://img.shields.io/badge/Local_AI-Ollama_%C2%B7_llama.cpp-111827?style=for-the-badge)
![Data](https://img.shields.io/badge/Data-pgvector_%C2%B7_HANA-2563eb?style=for-the-badge)

</div>

<table>
<tr>
<td valign="top" width="25%">

### AI

LLMs · AI Agents · MCP · RAG · Embeddings · Vector Search · Tool Calling · Local Inference

</td>
<td valign="top" width="25%">

### Backend

C# / .NET · Python · Go · REST · gRPC · Dapper · JWT · Microservices

</td>
<td valign="top" width="25%">

### Data

PostgreSQL · pgvector · SQL Server · SAP HANA · MongoDB · Semantic Search

</td>
<td valign="top" width="25%">

### Systems

Docker · Linux · Nginx · SAP Business One · Flutter · Git · CI/CD · Local Infrastructure

</td>
</tr>
</table>

---

## `> ls selected-work/`

### [`AI Basic Studio`](https://github.com/GinesMr/GoAiBasicStudio)

**Local LLM terminal environment written in Go.** Terminal UI for interacting with local Ollama models through model discovery, contextual conversations and streamed generation.

`Go` · `Bubble Tea` · `Ollama` · `Local LLMs`

### `AI Agent Infrastructure`

Architectures where an orchestrator connects a language model to MCP servers, enterprise databases, ERP systems, RAG knowledge bases, external APIs and local models—with a strong focus on **privacy, modularity and controlled write operations**.

### [`Orbit Wallet`](https://github.com/GinesMr/crypto_app) · [`Backend`](https://github.com/GinesMr/OrbitWalletBackend)

Non-custodial Ethereum wallet built with Flutter and Go, including wallet generation, blockchain interaction, transaction management and a dedicated backend architecture.

`Flutter` · `Go` · `Ethereum` · `REST`

### `TerraEsphere`

IoT soil-monitoring system built with embedded hardware and sensors. **Winner of Spain's 2024 National Telecommunications Olympiad.**

One of the experiences that pushed me toward systems where software, hardware and intelligence interact with the real world.

---

## `> cat philosophy.txt`

```text
AI should be useful.
AI should have context.
AI should use tools.
AI should integrate with existing systems.
AI should respect private data.
AI should survive outside the demo.
```

I care about architecture, maintainability and building things that can become **real products**, not isolated experiments.

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
