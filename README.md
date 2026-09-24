# Awesome-AI-Agent-Monitoring

## Top AI Agent Monitoring Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Agent Tracing, Tool-Call Spans, Multi-Agent Sessions, Cost & Latency Tracking, Eval Loops & Production Agent Health*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Monitoring**. These systems capture full agent trajectories—LLM calls, tool use, memory, and multi-agent handoffs—so teams can debug failures, measure success rates, control cost, and improve agent reliability in production.



**Examples** include Langfuse, AgentOps, Arize Phoenix, Helicone, Keywords AI, Braintrust, HoneyHive, OpenLIT, Comet Opik, and Humanloop (the category leaders).



**Open-source emphasis**: Agent monitoring inherits a strong open stack from LLM observability. **Langfuse**, **Arize Phoenix**, **OpenLLMetry**, **Helicone**, **Opik**, and related projects support agent-level spans and sessions. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Langfuse (Cloud)](https://langfuse.com/)**  

  LLM and agent engineering platform—traces, sessions, prompt management, and evals with strong support for multi-step agent workflows (open-source core available).



- **[AgentOps](https://www.agentops.ai/)**  

  Observability built specifically for AI agents—session replay, tool-call tracking, cost attribution, and agent performance analytics.



- **[Arize Phoenix / Arize AX](https://arize.com/)**  

  Open Phoenix plus enterprise Arize for tracing, evaluation, and monitoring of agents and LLM applications.



- **[Helicone, Keywords AI, OpenLIT](https://www.helicone.ai/)**  

  Proxy and instrumentation-oriented platforms for logging LLM/agent requests, latency, and cost with minimal code changes.



- **[Braintrust, HoneyHive, Humanloop](https://www.braintrust.dev/)**  

  Evaluation-first and human-feedback platforms that monitor agent quality, run experiments, and close the loop from production to improvement.



- **[Comet Opik](https://www.comet.com/site/products/opik/)**  

  LLM/agent evaluation and observability toolkit with tracing and experiment workflows (open-source edition available).



- **[Other commercial agent monitoring platforms](https://langfuse.com/)**  

  Additional solutions for agent analytics, guardrail monitoring, and production reliability.



## Open-Source GitHub Projects



- **[Langfuse](https://github.com/langfuse/langfuse)**  

  Leading open-source (MIT) platform for LLM and agent tracing—sessions, nested observations, prompt versioning, and evals; ideal self-hosted agent monitor.



- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  

  Open-source tracing and evaluation focused on LLM and agent runs—notebook-friendly and production-capable with OpenTelemetry support.



- **[OpenLLMetry (Traceloop)](https://github.com/traceloop/openllmetry)**  

  OpenTelemetry instrumentation for GenAI and agents—standard spans for LLM providers, tools, and vector DBs that export to any OTel backend.



- **[Helicone](https://github.com/Helicone/helicone)**  

  Open-source proxy logging for LLM and agent traffic—request/response capture, cost, and latency with simple gateway integration.



- **[Opik (Comet)](https://github.com/comet-ml/opik)**  

  Open evaluation and observability library for LLM/agent traces, datasets, and experiments.



- **[AgentOps open SDK patterns](https://github.com/search?q=agentops+OR+agent+tracing+open+source)**  

  Community and vendor SDKs that record agent sessions, tool calls, and outcomes for replay and analytics.



- **[OpenLIT & LiteLLM proxy observability](https://github.com/openlit/openlit)**  

  Open instrumentation and gateway layers that emit traces and metrics for multi-model agent stacks.



- **[Evidently & custom agent metrics](https://github.com/evidentlyai/evidently)**  

  Open monitoring framework adaptable to agent success rates, step counts, and quality scores over time.



### Additional Strong Open-Source Options



- **Full agent platform**: Langfuse for end-to-end traces, sessions, and evals.

- **OTel-native**: OpenLLMetry + existing APM (Jaeger, Grafana, Datadog) for vendor-neutral pipelines.

- **Proxy path**: Helicone/OpenLIT for quick visibility without deep SDK work.

- **Eval loop**: Opik and Phoenix for experiment tracking tied to production traces.

- **Composable stacks**: Agent framework (LangGraph/CrewAI) + Langfuse/OpenLLMetry + dashboards.

- Commercial platforms still lead in polished agent replay UX and multi-team governance.



**Frameworks for building custom systems**:  

**Langfuse** and **Phoenix** are the strongest open agent monitoring products.  

**OpenLLMetry** and **Helicone** provide instrumentation and proxy options.  

Commercial platforms (AgentOps, Braintrust, HoneyHive, Keywords AI, Humanloop, etc.) add specialized agent analytics and eval workflows.  

Most teams instrument agents with open SDKs and optionally send data to commercial backends for scale. Fully open stacks are production-ready with self-hosted Langfuse or OTel collectors.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Agent traces often contain tools outputs, user data, and credentials in prompts. Sanitize sensitive fields, encrypt storage, and restrict access. Autonomous agents need monitoring plus guardrails—observability alone does not prevent harmful actions.

- Open-source tools offer control and data residency but require operational ownership. Commercial platforms shift that burden to the vendor. Align monitoring with your security and compliance requirements.



---



**Made for agent builders, AI platform teams, and anyone running multi-step agents in production.**  

Let's expand open agent monitoring while recognizing the specialized analytics and scale that leading commercial platforms deliver.
