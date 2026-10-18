# Alexander Saravia

**Principal AI Architect · Technical Lead · AI Audit & Governance Lead** · Quito, Ecuador

I design AI systems end to end (data and models, agent orchestration, security, observability, cost) and govern them against ISO/IEC 42001 and Ecuador's LOPDP. Production work is under employer confidentiality; the public repositories are reference implementations on public data. Career narrative: [LinkedIn](https://www.linkedin.com/in/asaravia).

Lifelong learner. I like building, breaking and explaining things, so you'll find labs, notebooks and learning paths here more than polished products.

> **Working maxim:** I lead hybrid engineering teams, human specialists and virtual agent teams, driven by specifications, explicit invariants and automated quality gates (spec-driven design).

---

## Results in production

| System | Outcome |
|---|---|
| Generative AI agent for branch staff, deployed across 200 branches | Answer retrieval from ~20 min to ≤ 8 s; 5,000+ active users, 200,000+ questions, 80% satisfaction. Designed and run end to end: infrastructure, assurance, monitoring, cost. FELABAN Digital Innovation Award 2026, AI category, first place in Latin America. |
| Fraud detection for a 4M-user digital channel | Variational autoencoders for anomaly detection on highly imbalanced transactions; cyclic features (time of day, weekday) re-encoded by change of coordinates; behavioral rules engine that cut transaction delays. |
| Edge AI on single-board computers with 3D vision | Real-time deep learning inference at the edge; internationally published patent. |

Technical lead of a 10-person cross-functional team (DevOps, QA, senior engineers, cloud, solution, data and security architects) across the full lifecycle: feasibility, business case, budget readiness and delivery to operations.

---

## How I architect

- **Governance and security by design, from day one.** OWASP Top 10 for LLM and agentic applications, risk matrices, least privilege.
- **Human oversight and traceability** in every agent, aligned with ISO/IEC 42001 and LOPDP.
- **Observability and cost as requirements**, not afterthoughts.
- **From MVP to production load**: sizing, sandboxes, and protocols (MCP, A2A) before scale.
- **Specifications first**: invariants and quality gates written down so human and virtual teams build the same thing.

---

## Technical depth

**Deep learning and representation learning**
- Variational autoencoders and anomaly detection on imbalanced tabular and temporal data
- Siamese CNNs and metric learning for similarity ([`img-similarity`](https://github.com/basaravia/img-similarity))
- Vision-language models and document layout understanding ([`document-parsing-dl-mllm`](https://github.com/basaravia/document-parsing-dl-mllm))

**Agentic systems**
- Multi-agent orchestration with LangGraph; tool use over MCP ([`langchain-mcp-duckduckgo`](https://github.com/basaravia/langchain-mcp-duckduckgo))
- Conversational agents with RAG and audio ([`agente_sp2sp`](https://github.com/basaravia/agente_sp2sp))
- Local and private model serving for sensitive workloads

**Security and governance**
- Hands-on OWASP Top 10 for LLM Applications (2025) and for Agentic Applications (2026) ([`taller-ia-cibersecurity`](https://github.com/basaravia/taller-ia-cibersecurity))
- ISO/IEC 42001 and NIST AI RMF applied across projects: human oversight, traceability, risk matrices

**Data and platform**
- PySpark at scale, Python, SQL, Docker, Kubernetes, PyTorch

---

## Selected repositories

| Repository | What it demonstrates |
|---|---|
| [`taller-ia-cibersecurity`](https://github.com/basaravia/taller-ia-cibersecurity) | Hands-on lab for OWASP LLM and Agentic risks: 20 scenario branches with checklists, a LangGraph agent CLI, a multi-agent mesh sandbox and two OWASP notebooks |
| [`langchain-mcp-duckduckgo`](https://github.com/basaravia/langchain-mcp-duckduckgo) | Agent with a remote MCP server and a local model |
| [`agente_sp2sp`](https://github.com/basaravia/agente_sp2sp) | Spanish conversational agent with RAG, LLM and audio processing |
| [`document-parsing-dl-mllm`](https://github.com/basaravia/document-parsing-dl-mllm) | Content extraction and layout identification with deep learning and multimodal models |
| [`advanced-ai-path`](https://github.com/basaravia/advanced-ai-path) | Structured path from fundamentals to scalable AI architectures |

---

## Research, patent and community

- International patent, Edge AI inference with 3D vision (Universidad Indoamérica)
- MSc Data Science, PUCE. MSc studies in Computational Intelligence, COPPE/UFRJ (coursework completed)
- Teaching and community: Saturdays.AI, tinyML Foundation, IEEE CIS and RAS

---

<details>
<summary>Resumen en español</summary>

Arquitecto principal de IA, líder técnico y líder de auditoría y gobierno de IA. Diseño sistemas de IA de punta a punta (datos, modelos, orquestación de agentes, seguridad, observabilidad y costos) y los gobierno con ISO/IEC 42001 y la LOPDP. Lidero equipos híbridos de especialistas humanos y agentes virtuales, guiados por especificaciones. Resultados en producción: agente de IA generativa en 200 agencias (de ~20 min a ≤ 8 s, +5.000 usuarios, 80 % de satisfacción; Premio FELABAN 2026, primer lugar en Latinoamérica) y detección de fraude para un canal de 4 millones de usuarios. El trabajo de producción está bajo confidencialidad; los repositorios públicos son implementaciones de referencia con datos públicos.

</details>
