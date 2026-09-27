# ISO/IEC 42001-Governed Agentic Orchestration Architecture
> **An Architectural Reference Blueprint for Verifiable AI Governance in Public Health Systems**

This repository contains the Technical Specifications, Intellectual Property (IP) mapping, and Progressive Deliverables for an AI Agentic Flow Orchestration Architecture engineered specifically to generate native, unalterable compliance evidence for the **ISO/IEC 42001:2023 Standard (Artificial Intelligence Management System - AIMS)**.

---

## 🏛️ Architectural Framework Overview
This architecture transitions an un-governed environment (*As-Is*) prone to "Shadow Agents" into a structured, auditable ecosystem (*To-Be*) using a **Layered Abstraction Model** mapped directly to ISO 42001 Annex A controls.

![Arquitecture](arquitectura_ia_iso%2042001.png)

## 🗺️ Architectural Mapping to ISO/IEC 42001 Controls

Every software component in this repository acts as a functional machine and simultaneously outputs verifiable audit trails for specific clauses and controls:

| Layer / Component | Functional Responsibility | Target ISO/IEC 42001 Control / Clause |
| :--- | :--- | :--- |
| **Cross-Cutting Policy Layer** | Real-time token budget limits, PII masking, and prompt-injection filtering. | **Clause 7.1 (Resources)**, **Annex A.7 (Data for AI)**, **Annex A.9 (Use of AI)** |
| **Layer 1: Bounded Context** | Restricts information exposure via Minimum Context Packets (PC-nnn). | **Annex A.7 (Data for AI Systems)** — Provenance, data lineage, and corpus quality. |
| **Layer 2: Agent Reasoning** | Controls Multi-Agent interactions and runs execution tasks via Model Context Protocol (MCP). | **Annex A.6 (AI System Life Cycle)**, **Annex A.10 (Relationships with Third Parties)** |
| **Layer 3: Deterministic Verification** | Hardcoded evaluation ("When → Then") checking probabilistic outputs against logical constraints. Generates cryptographic logs. | **Clause 9.2 (Internal Audit)**, **Annex A.6 (Verification)** — Ultimate source of immutable proof. |
| **Layer 4: Operational Governance** | Enforces Human-in-the-Loop (HITL) and Human-in-Command bounds for high-risk operations. | **Annex A.3 (Internal Organization)**, **Annex A.9 (Human Oversight Framework)** |

---

## 📂 Repository Structure
* `/docs` - Detailed architectural diagrams (ArchiMate scripts) and design patterns.
* `/deliverables` - The 16 progressive artifacts forming the final IP & Dissemination Dossier.
* `/src` - Architectural interface components and Model Context Protocol (MCP) data contracts.

---

## 📈 Progressive Dossier Index (16 Artifacts)
Every academic session builds one technical or legal artifact based on this architecture. The progress is tracked sequentially below:

### Learning Unit 1: Legal Framework & Foundations
* [ ] **Session 01:** IP Asset Map (Doctoral Project Boundary Selection)
* [ ] **Session 02:** Protect-versus-Share Memo (Licensing Spectrum Analysis)
* [ ] **Session 03:** [Four Questions Technical Compliance Assessment](/deliverables/unit-1/session-03-four-questions.md)  `<- Current Milestone`
* [ ] **Session 04:** Patentability Pre-Assessment under Decision 486 (Andean Community Framework)


Your doctoral research on an ISO/IEC 42001-Governed Agentic Architecture is protected through a hybrid Intellectual Property (IP) strategy. 

Under Andean Community Decision 486 (INDECOPI) and Peruvian law, three distinct legal regimes apply simultaneously:
- Patent Law (Computer-Implemented Inventions): Protects the technical process and structural control loop. While raw software as such is excluded, your architecture qualifies because components like the Dependency Graph Validator and Cryptographic Log Repository produce a measured technical effect—specifically eliminating non-deterministic agent drift and securing data immutability.
- Copyright Law (Software & Literature): Automatically protects the literal expression of your project. This covers the source code of your Multi-Agent Orchestrator, your versioned MCP Interface contracts, your doctoral thesis text, and your ArchiMate implementation scripts.
- Trade Secret Law: Protects your internal heuristics, prompt topologies, and proprietary rule-sets within the "When → Then" Rules Engine. This is the ideal instrument for confidential operational knowledge that you choose not to disclose publicly in a patent application.

Additionally, due to its deployment in the healthcare sector, your architecture is legally bound by Data Protection Law (Ley 29733), which is technically enforced by your Automated Anonymization Pipeline before data crosses any runtime boundaries.To finalize your Learning Unit 1 portfolio, should we proceed to:
- Complete the Session 04 Patentability Pre-Assessment Brief focusing on how your technical effects beat the software patent exclusion.
- Draft the Protect-versus-Share Memo to decide which specific code components will be open-sourced on GitHub versus kept as trade secrets.

---
*Developed as part of the Doctoral Program in Deep Tech AI and Emerging Technologies.*
