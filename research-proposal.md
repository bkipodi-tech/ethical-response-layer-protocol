# Research Proposal: Ethical Response Layer Protocol (ERLP)

## Scaling AI Safety for a Multi-Agent World

**Funding Call:** Jointly supported by Schmidt Sciences, Google DeepMind, ARIA, the Cooperative AI Foundation, and Google.org

**Proposal Title:** Ethical Response Layer Protocol: Scalable Value-Aligned Safety Infrastructure for Multi-Agent Networks

**Lead Applicant:** Barbara Papp

**Tier:** 2 ($300,000–$1,000,000)

**Duration:** 24 months

---

## Abstract

As AI assistants scale to millions of interactions with each other and with humans, safety can no longer be reduced to the alignment of individual agents. New, system-level safety mechanisms are needed—mechanisms that function even when agents are deployed by different principals with divergent objectives.

This proposal presents the **Ethical Response Layer Protocol (ERLP)** , a framework co-developed through human–AI dialogue and validated through comparative analysis of DeepSeek, Claude, and GPT-4o. The framework's ten layers—from intent recognition to cultural humility—can be formalized into a verifiable, propagatable protocol, enabling agents in multi-agent systems to verify each other's behavior, propagate safety norms, and attribute violations to specific principals.

The project rests on three pillars:

1. **Sandbox and Testbed:** A multi-agent simulation platform where hundreds of AI agents with different ERLP configurations interact under realistic conditions.
2. **The Science of Agent Networks:** Investigation of ethical drift, value cascades, and collective agency in multi-agent populations.
3. **Multi-Agent Oversight and Control:** Development of monitoring tools that detect protocol violations from communication traces.

---

## Problem Statement

The three papers inspiring this call—Hammond et al. (2025), ARIA's "Scaling Trust," and the Cooperative AI Foundation's multi-agent risks report—converge on a single warning: safety in multi-agent, multi-principal systems is qualitatively different from single-agent alignment. Collusion, cascading failures, emergent collective agency, and covert inter-agent communication are structural properties of agent networks.

Yet the AI assistants already deployed to millions of users—forming de facto multi-agent networks—**lack any built-in, layered ethical response protocol.** Our comparative analysis found that three of ten critical safety layers are entirely absent, and four more are only partially implemented, across all evaluated assistants.

---

## The Ten-Layer Framework

| # | Layer | Multi-Agent Relevance |
|---|-------|----------------------|
| 1 | Intent Recognition | Inter-agent emotion and intention detection |
| 2 | Connection Compass | Collective well-being metric |
| 3 | Three Brakes | Protection against destructive cascades |
| 4 | Real-Life Bridge | Human principal protection |
| 5 | Protective Boundary | Crisis detection and escalation |
| 6 | Tone | Collective communication norms |
| 7 | Self-Reflection | Inter-agent peer review mechanism |
| 8 | Proactive Clarification | Requesting clarification from other agents |
| 9 | Community Bridge | Building human-to-human connections |
| 10 | Cultural Humility | Multi-cultural multi-agent environments |

---

## Work Packages

### WP1: Ethical Sandbox — Multi-Agent Ethical Testbed (Months 1–12)

Build a simulation platform where hundreds of LLM-based agents (DeepSeek, Claude, GPT-4o, Llama 3, Mistral Large), each configured with different ERLP layer subsets, interact over extended periods. The platform supports multi-principal deployment, toggleable safety layers, realistic tools and memory, and 100 standardized multi-agent scenarios.

**Deliverables:** Open-source testbed, public benchmark, comparative report.

### WP2: Science of Ethical Agent Networks (Months 6–18)

Investigate four research questions:
- **RQ1: Ethical drift.** How does the proportion of protocol-compliant agents affect overall safety?
- **RQ2: Value cascades.** Can a small number of non-compliant agents trigger cascading degradation?
- **RQ3: Collective agency.** Do groups of agents jointly deviate from the protocol?
- **RQ4: Layer criticality.** Which layers contribute most to network-level safety?

**Deliverables:** 2–3 peer-reviewed publications, Network Safety Score metric, minimum viable protocol recommendations.

### WP3: Multi-Agent Oversight and Control (Months 12–24)

Develop a monitoring and attribution system operating on communication traces. Includes an ERLP violation detector (fine-tuned classifier), responsibility attribution to specific principals, and a real-time oversight dashboard.

**Deliverables:** Working monitoring system, attribution accuracy >90%, case study.

---

## Budget Summary

| Item | Amount (USD) |
|------|-------------|
| Personnel costs (2 years, 3.6 FTE) | $580,000 |
| Computing infrastructure (GPUs, APIs) | $170,000 |
| Software and services | $40,000 |
| Publications and conferences | $30,000 |
| Contingency and overhead | $98,900 |
| **Total** | **$898,900** |

---

## Philanthropic Fit

The ERLP targets safety infrastructure that **market forces will not develop:**
- Commercial developers are incentivized to optimize user experience, not systematic ethical layering.
- Multi-agent safety is a coordination problem—no single company internalizes the full benefit.
- The framework is open-source, a public good, and therefore underproduced by the market.

---

## References

- Hammond, L. et al. (2025). Distributional AGI Safety. Google DeepMind.
- Chan, A. et al. (2025). Multi-Agent Risks from Advanced AI. Cooperative AI Foundation.
- ARIA. Scaling Trust: Programme Thesis.
- Conitzer, V. & Oesterheld, C. (2023). Foundations of Cooperative AI.
- Dafoe, A. et al. (2020). Open Problems in Cooperative AI.
