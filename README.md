# Awesome-LLM-Observability-Platform

## Top LLM Observability Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on LLM Tracing, Prompt Management, Evaluations, Cost Tracking, Agent Observability & Production Monitoring*

**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **LLM Observability**. These tools help teams trace LLM and agent calls, manage prompts, run evaluations, monitor cost and latency, detect quality regressions, and debug AI applications in production.

**Examples** include Langfuse, Helicone, LangSmith, Phoenix by Arize, Weights & Biases Weave, HoneyHive, WhyLabs, Fiddler AI, PromptLayer, Patronus AI, Galileo AI, Keywords AI, and OpenLIT (the category leaders).

**Open-source emphasis**: LLM observability has an unusually strong open-source ecosystem. **Langfuse**, **Arize Phoenix**, **OpenLIT**, **Helicone**, and related projects offer production-grade tracing, evals, and self-hosting. This section is heavily expanded with these tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits / Trial |
| :--- | :--- | :--- | :--- |
| **[LangSmith](https://www.langchain.com/langsmith)** | Native LLM & agent tracing, evaluation framework, prompt playground, and debugging suite for LangChain/LangGraph and general AI apps. | **$39 / seat / month** (Plus Plan; includes 10,000 base traces/month, $0.005/extra trace) | **Free Forever**: 1 seat, 5,000 base traces/month, 14-day data retention, 100 eval cell runs/month |
| **[Weights & Biases Weave](https://wandb.ai/site/weave)** | LLM and agent tracing, dataset management, prompt versioning, and evaluation tracking integrated with the W&B MLOps platform. | **$60 / user / month** (Pro Plan; includes 100 GB storage and 1.5 GB/month Weave data ingestion) | **Free Forever**: 1 user seat, 5 GB storage, 1 GB/month Weave trace ingestion |
| **[Galileo AI](https://www.galileo.ai/)** | End-to-end LLM observability, agent analytics, prompt evaluation, hallucination detection, and real-time guardrails. | **$100 / month** (Pro Plan, billed yearly; includes 50,000 traces/month, standard RBAC) | **Free Forever**: 5,000 traces/month, unlimited user seats, unlimited custom evaluators |
| **[PromptLayer](https://www.promptlayer.com/)** | Prompt management, visual LLM request logging, prompt version control, collaboration playground, and automated evals. | **$49 / month** (Pro Plan; includes unlimited playgrounds/workspaces, 150MB max dataset size) | **Free Forever**: 5 users, 2,500 requests/month, 1 workspace, 250 eval cell runs/month, 10MB dataset limit |
| **[Keywords AI (Respan)](https://www.respan.ai/)** | LLM gateway and observability platform offering real-time logging, user analytics, prompt management, and model cost optimization. | **$39 / month** (Pro Tier) / **$199 / month** (Team Tier, billed yearly; +$8 per 100k extra logs) | **Free Forever**: 10,000 traces/month (100k logs), 1,000 scores, 5 datasets, 2 evaluators, 5 prompts |
| **[HoneyHive](https://www.honeyhive.ai/)** | LLM observability, production monitoring, user feedback tracking, automated evaluations, and CI/CD prompt versioning. | **$0.003 / event** (Usage-based Developer overage) / **$500 / month** (Team/Enterprise starting tier) | **Free Forever**: 10,000 events/month, 1,000 RPM, up to 5 user seats, 30-day data retention |
| **[Fiddler AI](https://www.fiddler.ai/)** | Enterprise LLM observability, real-time guardrails (PII, toxicity, hallucination detection), and predictive model performance monitoring. | **$0.002 / trace** (Developer Plan; includes unified AI observability and RBAC) | **Free Plan**: Real-time guardrails (<80ms latency); or **30-Day Free Trial** on AWS Marketplace (up to 5 models) |
| **[Patronus AI](https://www.patronus.ai/)** | Automated evaluation platform specialized in LLM testing, automated scoring, enterprise guardrails, and hallucination detection. | **$0.005 / evaluation** (Self-serve pay-as-you-go rate); Custom enterprise quotes | **$5 Free Platform Credits** upon signup (~500–1,000 evaluations) + free 45-min evaluation strategy session |
| **[WhyLabs](https://whylabs.ai/)** | AI observability and guardrail platform with real-time drift, quality monitoring, and security tracking powered by LangKit and whylogs. | **$0 / month** (Open-source Apache 2.0 self-hosted platform; legacy SaaS starter was $125/mo) | **Free Forever**: Unlimited self-hosted traces & models under Apache 2.0 (hosted starter was 2 models, 10M profiles/mo) |



## Open-Source GitHub Projects

- **[Langfuse](https://github.com/langfuse/langfuse)**  

  Leading open-source LLM engineering platform (MIT) — tracing, prompt management, evaluations, datasets, metrics, and playground. Fully self-hostable; also offers a managed cloud. Widely adopted and production-ready.



- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  

  Open-source AI observability and evaluation platform from Arize — OpenTelemetry-native tracing, LLM-as-judge evals, datasets, and troubleshooting. Self-host free; managed option via Arize AX.



- **[OpenLIT](https://github.com/openlit/openlit)**  

  Open-source (Apache 2.0), OpenTelemetry-native platform for LLM and agent tracing, evaluations, prompt management, cost tracking, and self-hosting.



- **[Helicone](https://github.com/Helicone/helicone)**  

  Open-source LLM observability via proxy or SDK — simple drop-in logging, cost tracking, caching, and analytics. Self-hostable with a generous free/cloud tier.



- **[OpenLLMetry](https://github.com/traceloop/openllmetry)**  

  OpenTelemetry-native instrumentation for LLM applications, enabling traces to flow into any OTEL-compatible backend.



- **[Comet Opik](https://github.com/comet-ml/opik)**  

  Open-source tracing and evaluation toolkit that can run standalone or inside the Comet platform.



- **[DeepEval](https://github.com/confident-ai/deepeval)**  

  Open-source LLM evaluation framework with pytest-style testing, useful for CI regression checks on prompts and outputs.



- **[AgentOps and related agent observability projects](https://github.com/)**  

  Community tools focused on tracing multi-agent workflows, tool calls, and session-level analytics.



- **[LangWatch and similar open platforms](https://github.com/)**  

  Additional open-source or open-core LLM monitoring and evaluation projects.



- **[Custom OpenTelemetry + Grafana / Jaeger stacks](https://github.com/)**  

  Self-built observability pipelines that instrument LLM calls with OTEL and visualize in existing open monitoring tools.



### Additional Strong Open-Source Options

- Starting with **Langfuse** for the most complete open-source LLM engineering workbench (traces + prompts + evals).

- Choosing **Arize Phoenix** when you want strong OpenTelemetry-native tracing and ML-grade evaluation primitives.

- Using **OpenLIT** or **Helicone** for lightweight, standards-based instrumentation and cost visibility.

- Exporting traces via OpenTelemetry so you can keep data in your own Grafana, Jaeger, or ClickHouse stack.

- Combining open tracing with open evaluation libraries (DeepEval, etc.) for CI/CD quality gates.

- Accepting that some advanced enterprise features (SSO, advanced RBAC, managed scale, specialized guardrails) still favor commercial hosted platforms.



**Frameworks for building custom systems**: Instrument with OpenTelemetry or a native SDK (Langfuse / Phoenix / OpenLIT) → store traces in your own backend → run evals on datasets → manage prompts versioned in git or the platform → alert on cost, latency, and quality drift. This stack is fully open and production-proven. Commercial platforms (LangSmith, W&B Weave, HoneyHive, Patronus, Galileo, etc.) remain strong when you want tight framework integration, managed scale, or specialized evaluation workflows without operating the infrastructure.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- LLM observability systems capture prompts, completions, and sometimes user data. Treat this data as sensitive: apply access controls, retention policies, and compliance requirements (GDPR, etc.). Self-hosted open-source deployments require proper security hardening, backups, and monitoring of the observability stack itself. Evaluation scores and automated judges are decision-support tools, not absolute truth. This list is not security, compliance, or production-architecture advice.



---

**Made for AI engineers, MLOps teams, and builders who need to see what their LLMs and agents are actually doing.**

Let's keep observability open, standards-based, and under your control.
