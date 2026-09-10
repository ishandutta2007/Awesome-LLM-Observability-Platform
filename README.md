<div align="center">

<a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
<a href="https://github.com/ishandutta2007/Awesome-LLM-Observability-Platform/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-LLM-Observability-Platform?style=flat-square&color=yellow" alt="Stars"/></a>
<a href="https://github.com/ishandutta2007/Awesome-LLM-Observability-Platform/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-LLM-Observability-Platform?style=flat-square&color=blue" alt="Forks"/></a>
<a href="https://github.com/ishandutta2007/Awesome-LLM-Observability-Platform/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License"/></a>
<a href="https://github.com/ishandutta2007/Awesome-LLM-Observability-Platform/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"/></a>
<a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

<br/><br/>

<img src="assets/banner.svg" alt="Awesome LLM Observability Platform Banner" width="100%"/>

# 🚀 Awesome LLM Observability Platform

### *The Definitive Curated Guide to LLM Observability, Tracing, Evaluations, PromptOps, Guardrails & AI Agent Monitoring*

[![SEO Keywords](https://img.shields.io/badge/Focus-LLM%20Tracing%20%7C%20LLM%20Evals%20%7C%20PromptOps%20%7C%20Guardrails-blueviolet?style=flat-square)](#)
[![OpenTelemetry Compatible](https://img.shields.io/badge/Standards-OpenTelemetry%20%7C%20OTel-orange?style=flat-square)](#)
[![Updated](https://img.shields.io/badge/Last%20Updated-September%202026-brightgreen?style=flat-square)](#)

</div>

---

## 📖 Overview & Ecosystem Landscape

As Large Language Models (LLMs), AI Agents, and Retrieval-Augmented Generation (RAG) applications move into mission-critical production environments, **LLM Observability** and **LLMOps** have become foundational pillars of modern AI software engineering. 

This repository provides an exhaustively researched, regularly updated catalog of both enterprise **SaaS Platforms** and leading **Open-Source Repositories** for:
- ⚡ **LLM & Multi-Agent Tracing**: Distributed tracing of complex agent workflows, chains, and tool invocations.
- 🧪 **Automated LLM Evaluation**: LLM-as-a-judge, unit testing, deterministic regression checks, and hallucination scoring.
- 📝 **Prompt Engineering & Versioning**: Collaborative prompt hubs, semantic versioning, A/B testing, and playgrounds.
- 💰 **Cost, Token & Latency Monitoring**: Granular per-user, per-model, and per-tenant cost attribution.
- 🛡️ **Real-Time Guardrails & Security**: PII redaction, prompt injection defense, toxicity detection, and jailbreak prevention.
- 🌐 **OpenTelemetry Standards**: Standardized OTel-native instrumentation for seamless integration across existing APM stacks.

---

## 📑 Table of Contents

- [☁️ SaaS Observability Platforms](#️-saas-observability-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ Key Architectural Patterns](#️-key-architectural-patterns)
- [📈 Star History](#-star-history)
- [🤝 How to Contribute](#-how-to-contribute)
- [📜 License & Disclaimer](#-license--disclaimer)

---

## ☁️ SaaS Observability Platforms

> 📊 **Market Intelligence & Sector Dynamics**:
> The global AI & LLM Observability market is estimated at **$2.5B–$3.8B in 2026** and projected to exceed **$12B+ by 2030** (CAGR ~38%). The sector is currently **moderately to highly fragmented**, characterized by rapid innovation across specialized startups (tracing, prompt management, automated evaluation, guardrails) and traditional APM giants, preventing a single winner-take-all monopoly due to the strong leverage of open-source alternatives.

The table below is sorted by **Company Size (Valuation / Funding)** in descending order:

| Platform | Company Size (Valuation / Funding) | Description | Starting Tier Pricing | Free Tier Limits / Free Trial |
| :--- | :--- | :--- | :--- | :--- |
| **[Weights & Biases Weave](https://wandb.ai/site/weave)** | 🦄 **$1.25B Valuation**<br>*(~$250M+ Raised; Acquired by CoreWeave)* | LLM and agent tracing, dataset management, prompt versioning, and evaluation tracking integrated with the W&B MLOps platform. | **$60 / user / month** (Pro Plan; includes 100 GB storage and 1.5 GB/month Weave data ingestion) | **Free Forever**: 1 user seat, 5 GB storage, 1 GB/month Weave trace ingestion |
| **[LangSmith](https://www.langchain.com/langsmith)** | 🦄 **$1.25B Valuation**<br>*(~$160M Raised; Series B)* | Native LLM & agent tracing, evaluation framework, prompt playground, and debugging suite for LangChain/LangGraph and general AI apps. | **$39 / seat / month** (Plus Plan; includes 10,000 base traces/month, $0.005/extra trace) | **Free Forever**: 1 seat, 5,000 base traces/month, 14-day data retention, 100 eval cell runs/month |
| **[Patronus AI](https://www.patronus.ai/)** | 📈 **~$450M Valuation**<br>*(~$70M Raised; Series B)* | Automated evaluation platform specialized in LLM testing, automated scoring, enterprise guardrails, and hallucination detection (Lynx). | **$0.005 / evaluation** (Self-serve pay-as-you-go rate); Custom enterprise quotes | **$5 Free Platform Credits** upon signup (~500–1,000 evaluations) + free 45-min evaluation strategy session |
| **[Fiddler AI](https://www.fiddler.ai/)** | 📈 **~$300M Valuation**<br>*(~$100M Raised; Series C)* | Enterprise LLM observability, real-time guardrails (PII, toxicity, hallucination detection), and predictive model performance monitoring. | **$0.002 / trace** (Developer Plan; includes unified AI observability and RBAC) | **Free Plan**: Real-time guardrails (<80ms latency); or **30-Day Free Trial** on AWS Marketplace (up to 5 models) |
| **[Galileo AI](https://www.galileo.ai/)** | 📈 **~$200M Valuation**<br>*(~$68M Raised; Series B)* | End-to-end LLM observability, agent analytics, prompt evaluation, hallucination detection, and real-time guardrails. | **$100 / month** (Pro Plan, billed yearly; includes 50,000 traces/month, standard RBAC) | **Free Forever**: 5,000 traces/month, unlimited user seats, unlimited custom evaluators |
| **[WhyLabs](https://whylabs.ai/)** | 💼 **~$100M Valuation**<br>*(~$14M Raised; Acquired / Open Source)* | AI observability and guardrail platform with real-time drift, quality monitoring, and security tracking powered by LangKit and whylogs. | **$0 / month** (Open-source Apache 2.0 self-hosted platform; legacy SaaS starter was $125/mo) | **Free Forever**: Unlimited self-hosted traces & models under Apache 2.0 (hosted starter was 2 models, 10M profiles/mo) |
| **[HoneyHive](https://www.honeyhive.ai/)** | 🌱 **~$25M–$35M Valuation**<br>*(~$7.4M Raised; Seed)* | LLM observability, production monitoring, user feedback tracking, automated evaluations, and CI/CD prompt versioning. | **$0.003 / event** (Usage-based Developer overage) / **$500 / month** (Team/Enterprise starting tier) | **Free Forever**: 10,000 events/month, 1,000 RPM, up to 5 user seats, 30-day data retention |
| **[Keywords AI (Respan)](https://www.respan.ai/)** | 🌱 **~$20M–$30M Valuation**<br>*(~$5M Raised; Seed)* | LLM gateway and observability platform offering real-time logging, user analytics, prompt management, and model cost optimization. | **$39 / month** (Pro Tier) / **$199 / month** (Team Tier, billed yearly; +$8 per 100k extra logs) | **Free Forever**: 10,000 traces/month (100k logs), 1,000 scores, 5 datasets, 2 evaluators, 5 prompts |
| **[PromptLayer](https://www.promptlayer.com/)** | 🌱 **~$15M–$25M Valuation**<br>*(~$4.8M Raised; Seed)* | Prompt management, visual LLM request logging, prompt version control, collaboration playground, and automated evals. | **$49 / month** (Pro Plan; includes unlimited playgrounds/workspaces, 150MB max dataset size) | **Free Forever**: 5 users, 2,500 requests/month, 1 workspace, 250 eval cell runs/month, 10MB dataset limit |

---

## 💻 Open-Source GitHub Projects

The open-source LLM observability ecosystem provides enterprise-grade, self-hosted, and OpenTelemetry-native solutions. The list below is sorted by **GitHub Star Count** (descending) with direct links to repo stargazers:

- **[Langfuse](https://github.com/langfuse/langfuse)** [![GitHub_Stars](https://img.shields.io/github/stars/langfuse/langfuse?style=social&color=white)](https://github.com/langfuse/langfuse/stargazers)  
  Leading open-source LLM engineering platform (MIT) — tracing, prompt management, evaluations, datasets, metrics, and playground. Fully self-hostable with cloud option.

- **[Promptfoo](https://github.com/promptfoo/promptfoo)** [![GitHub_Stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=social&color=white)](https://github.com/promptfoo/promptfoo/stargazers)  
  CLI and CI/CD security, quality, and red-teaming evaluation framework for LLMs and AI applications.

- **[Comet Opik](https://github.com/comet-ml/opik)** [![GitHub_Stars](https://img.shields.io/github/stars/comet-ml/opik?style=social&color=white)](https://github.com/comet-ml/opik/stargazers)  
  Open-source tracing and evaluation platform that runs standalone or integrates seamlessly with Comet ML.

- **[DeepEval](https://github.com/confident-ai/deepeval)** [![GitHub_Stars](https://img.shields.io/github/stars/confident-ai/deepeval?style=social&color=white)](https://github.com/confident-ai/deepeval/stargazers)  
  Open-source LLM evaluation framework with unit-testing style evaluation for prompt and output regression checks.

- **[Ragas](https://github.com/explodinggradients/ragas)** [![GitHub_Stars](https://img.shields.io/github/stars/explodinggradients/ragas?style=social&color=white)](https://github.com/explodinggradients/ragas/stargazers)  
  Supercharged evaluation framework for Retrieval Augmented Generation (RAG) and LLM pipelines.

- **[Portkey AI Gateway](https://github.com/portkey-ai/gateway)** [![GitHub_Stars](https://img.shields.io/github/stars/portkey-ai/gateway?style=social&color=white)](https://github.com/portkey-ai/gateway/stargazers)  
  Blazing fast AI Gateway with integrated routing, fallbacks, load balancing, cost tracking, guardrails, and OpenTelemetry-compliant observability.

- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)** [![GitHub_Stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=social&color=white)](https://github.com/Arize-ai/phoenix/stargazers)  
  AI observability & evaluation platform from Arize — OpenTelemetry-native tracing, LLM-as-judge evals, datasets, and troubleshooting.

- **[Prompt flow](https://github.com/microsoft/promptflow)** [![GitHub_Stars](https://img.shields.io/github/stars/microsoft/promptflow?style=social&color=white)](https://github.com/microsoft/promptflow/stargazers)  
  Suite of development tools designed to streamline the end-to-end development cycle of LLM-based AI applications, from ideation to evaluation and production deployment.

- **[OpenLLMetry](https://github.com/traceloop/openllmetry)** [![GitHub_Stars](https://img.shields.io/github/stars/traceloop/openllmetry?style=social&color=white)](https://github.com/traceloop/openllmetry/stargazers)  
  OpenTelemetry-native instrumentation SDKs for LLM applications, enabling seamless trace forwarding to any OTEL backend.

- **[Helicone](https://github.com/Helicone/helicone)** [![GitHub_Stars](https://img.shields.io/github/stars/Helicone/helicone?style=social&color=white)](https://github.com/Helicone/helicone/stargazers)  
  Open-source LLM observability via smart caching proxy or SDK — simple drop-in logging, cost tracking, and analytics.

- **[AgentOps](https://github.com/AgentOps-AI/AgentOps)** [![GitHub_Stars](https://img.shields.io/github/stars/AgentOps-AI/AgentOps?style=social&color=white)](https://github.com/AgentOps-AI/AgentOps/stargazers)  
  Observability, session replays, and performance tracking purpose-built for multi-agent workflows and autonomous agents.

- **[TruLens](https://github.com/truera/trulens)** [![GitHub_Stars](https://img.shields.io/github/stars/truera/trulens?style=social&color=white)](https://github.com/truera/trulens/stargazers)  
  Evaluation and observability framework for analyzing LLM/RAG applications using feedback functions.

- **[LangWatch](https://github.com/langwatch/langwatch)** [![GitHub_Stars](https://img.shields.io/github/stars/langwatch/langwatch?style=social&color=white)](https://github.com/langwatch/langwatch/stargazers)  
  Complete LLM observability, guardrails, security monitoring, and quality evaluation platform.

- **[OpenLIT](https://github.com/openlit/openlit)** [![GitHub_Stars](https://img.shields.io/github/stars/openlit/openlit?style=social&color=white)](https://github.com/openlit/openlit/stargazers)  
  Open-source (Apache 2.0), OpenTelemetry-native platform for LLM and agent tracing, evaluations, prompt management, and GPU/cost tracking.

- **[UpTrain](https://github.com/uptrain-ai/uptrain)** [![GitHub_Stars](https://img.shields.io/github/stars/uptrain-ai/uptrain?style=social&color=white)](https://github.com/uptrain-ai/uptrain/stargazers)  
  Open-source evaluation and observability toolkit for monitoring LLM application performance and hallucination rates.

---

## 🛠️ Key Architectural Patterns

- 🔬 **All-in-One Workbench**: Choose **Langfuse** or **Arize Phoenix** for comprehensive tracing, prompt management, and evaluation primitives.
- 🛡️ **CI/CD Quality & Security Gates**: Pair **Promptfoo** or **DeepEval** with your continuous integration pipelines for regression and security testing.
- ⚡ **Lightweight Proxy & Caching**: Deploy **Helicone** or **Portkey AI Gateway** for immediate latency improvements, fallback routing, and cost control without changing code logic.
- 🤖 **Agentic Multi-Step Workflows**: Integrate **AgentOps** for visualizing multi-agent sessions, tool calls, and execution graphs.
- 📊 **Self-Built OpenTelemetry Pipeline**: Instrument with **OpenLLMetry** or **OpenLIT** → stream traces via OTel Collector → visualize in Grafana, Jaeger, or ClickHouse.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-LLM-Observability-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-LLM-Observability-Platform&type=date&legend=top-left)

---

## 🤝 How to Contribute

1. 🍴 Fork the repository.
2. 🌿 Create a new feature branch (`git checkout -b add-awesome-tool`).
3. ✏️ Add/edit entries in `README.md` following the established format (include links, pricing/stars, and clear descriptions).
4. 📬 Submit a Pull Request with a short explanation of why the tool should be included.

⭐ **Star the repo** if you find this curated list valuable for your AI engineering workflows!

---

## 📜 License & Disclaimer

- **License**: MIT Licensed — free for personal and commercial reference.
- **Data Privacy & Compliance**: LLM observability systems process prompts, completions, and sensitive metadata. Ensure appropriate data masking, encryption, and regulatory compliance (GDPR, HIPAA, SOC 2) are enforced in your deployments.
- **Disclaimer**: This is a community-curated list and does not constitute formal security or architecture endorsement. Evaluation scores and automated judges are decision-support tools.

