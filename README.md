# Awesome World Law Agent

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> This repo is created and maintained by [**Sirui Han**](https://siruihan.com/).

An unparalleled, comprehensive, and continuously updated survey of the **World Law Agent** ecosystem. This repository consolidates and curates resources from leading collections, including foundational research, cutting-edge models, commercial platforms, and open-source tools, making it the definitive starting point for anyone building, researching, or investing in the intersection of AI and Law. This is the most comprehensive survey of its kind.

## Visual Overview

### Taxonomy of Legal AI

![Taxonomy of Legal AI](./images/taxonomy.png)

### Typical Law Agent Workflow

![Typical Law Agent Workflow](./images/agent_workflow.png)

### Legal Datasets & Benchmarks Landscape

![Legal Datasets & Benchmarks Landscape](./images/datasets_overview.png)

### Legal AI Evolution Timeline

![Legal AI Evolution Timeline](./images/timeline.png)

## Table of Contents

- [Surveys & Overviews](#surveys--overviews)
- [Foundational Research](#foundational-research)
- [Foundation Models](#foundation-models)
  - [Large Language Models (LLMs)](#large-language-models-llms)
  - [BERT-style & Embedding Models](#bert-style--embedding-models)
  - [Multilingual & Regional Models](#multilingual--regional-models)
- [Legal Search & Research](#legal-search--research)
  - [Legal Reasoning & Theory](#legal-reasoning--theory)
  - [Retrieval-Augmented Generation (RAG)](#retrieval-augmented-generation-rag)
  - [Knowledge Graphs & Ontologies](#knowledge-graphs--ontologies)
- [Litigation & Dispute Resolution](#litigation--dispute-resolution)
  - [Legal Judgment Prediction (LJP)](#legal-judgment-prediction-ljp)
  - [Courtroom Simulation & Argument Mining](#courtroom-simulation--argument-mining)
  - [Online Dispute Resolution (ODR)](#online-dispute-resolution-odr)
- [Compliance, Governance, & Regulation](#compliance-governance--regulation)
- [Advisory, Consultation & Transactions](#advisory-consultation--transactions)
  - [Contract Analysis & Drafting](#contract-analysis--drafting)
  - [Negotiation & Deal Simulation](#negotiation--deal-simulation)
- [Workflow Automation & E-Discovery](#workflow-automation--e-discovery)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Ethics, Fairness, and Bias](#ethics-fairness-and-bias)
- [Datasets & Corpora](#datasets--corpora)
  - [Pretraining Corpora](#pretraining-corpora)
  - [Task-Specific Datasets](#task-specific-datasets)
- [Tools, Platforms & Products](#tools-platforms--products)
  - [Full-Stack Legal Platforms](#full-stack-legal-platforms)
  - [Legal Research Platforms](#legal-research-platforms)
  - [Document Automation & Drafting](#document-automation--drafting)
  - [Contract Lifecycle Management (CLM)](#contract-lifecycle-management-clm)
  - [E-Discovery & Document Review](#e-discovery--document-review)
  - [Practice Management & Legal Ops](#practice-management--legal-ops)
  - [Intellectual Property & Patent Tech](#intellectual-property--patent-tech)
  - [MCP Servers for Legal](#mcp-servers-for-legal)
- [Agentic Infrastructure & OpenClaw](#agentic-infrastructure--openclaw)
  - [Core Frameworks](#core-frameworks)
  - [Legal Skills](#legal-skills)
  - [Legal MCP Servers](#legal-mcp-servers)
  - [Multi-Agent Frameworks](#multi-agent-frameworks)
  - [Protocols](#protocols)
- [Other Awesome Lists](#other-awesome-lists)
- [Citation](#citation)
- [Contributing](#contributing)
- [License](#license)

## Surveys & Overviews

- **Trustworthy Legal Reasoning: A Comprehensive Survey**, Preprints 2026. [[Paper](https://www.preprints.org/manuscript/202602.0870/v1)]
- **LLM Agents in Law: Taxonomy, Applications, and Challenges**, arXiv 2026. [[Paper](https://arxiv.org/abs/2601.06216)]
- **Large Language Models in Legal Systems: A Survey**, Nature Humanities and Social Sciences Communications 2025. [[Paper](https://www.nature.com/articles/s41599-025-05924-3)]
- **A Survey of Large Language Models for Legal Tasks: Progress, Prospects and Challenges**, [Computer Science Review](https://www.sciencedirect.com/journal/computer-science-review) 2026. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1574013726000158)]
- **AI Agents and the Law**, arXiv 2025. [[Paper](https://arxiv.org/html/2508.08544v1)]
- **The Rise and Potential of Large Language Model Based Agents: A Comprehensive Survey**. [[GitHub](https://github.com/WooooDyy/LLM-Agent-Paper-List)]
- **Natural Language Processing for the Legal Domain: A Survey of Tasks, Datasets, Models, and Challenges**, ACM Computing Surveys 2024. [[Paper](https://dl.acm.org/doi/abs/10.1145/3777009)]
- **Scenario, Role, and Persona: A Scoping Review of Design Strategies for Socially Intelligent AI Agents**, CHI EA 2025. [[Paper](https://dl.acm.org/doi/10.1145/3706599.3719762)]

## Foundational Research

- **GPT-4 Passes the Bar Exam**, Philosophical Transactions of the Royal Society A 2023. [[Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4389233)]
- **LEGAL-BERT: The Muppets Straight out of Law School**, EMNLP 2020. [[Paper](https://aclanthology.org/2020.findings-emnlp.261.pdf)]
- **LexGLUE: A Benchmark Dataset for Legal Language Understanding**, ACL 2022. [[Paper](https://aclanthology.org/2022.acl-long.297/)]
- **LegalBench: A Collaboratively Built Benchmark for Legal Reasoning**, 2023. [[Paper](https://arxiv.org/abs/2308.11462)]
- **Artificial Intelligence and Legal Analytics**, 2017. [[Book](https://www.cambridge.org/core/books/artificial-intelligence-and-legal-analytics/E7D705EEF392501A1DB180645917E7E0)]

## Foundation Models

### Large Language Models (LLMs)

- **SaulLM-7B/54B/141B**: A Pioneering Large Language Model for Law. [[Paper](https://arxiv.org/abs/2403.03883)]
- **ChatLaw**: A Multi-Agent Collaborative Legal Large Language Model. [[Paper](https://arxiv.org/abs/2306.16092)] [[Code](https://github.com/PKU-YuanGroup/ChatLaw)]
- **LawGPT**: A Chinese Legal Knowledge-Enhanced Large Language Model. [[Paper](https://arxiv.org/abs/2406.04614)]
- **Lawyer GPT: A Legal Large Language Model with Enhanced Domain Knowledge.** [RAIIE '24](https://dl.acm.org/doi/proceedings/10.1145/3689299) [[Paper](https://dl.acm.org/doi/abs/10.1145/3689299.3689319)]
- **Lawma-8B/70B**: Fine-tuned Llama 3 for legal classification tasks. [[Paper](https://arxiv.org/html/2407.16615v1)]
- **DISC-LawLLM**: Chinese legal assistant from Fudan. [[GitHub](https://github.com/FudanDISC/DISC-LawLLM)]

### BERT-style & Embedding Models

- **LEGAL-BERT**: Pretrained on EU/US legislation + court cases. [[Paper](https://aclanthology.org/2020.findings-emnlp.261.pdf)]
- **Pile of Law BERT large model 2:** Trained on Pile of Law corpus. [[Code](https://huggingface.co/pile-of-law/legalbert-large-1.7M-2)]
- **voyage-law-2 Embedding Model:** State-of-the-art closed-source embedding model for legal text retrieval. [[repository](https://marketplace.microsoft.com/en-us/product/azure-applications/voyageaiinnovationsinc1718340344903.voyage-law-2?tab=overview)]
- **Kanon 2 Embedder**: #1 on MLEB benchmark; legal semantic search + RAG. [[Code](https://isaacus.com/blog/introducing-kanon-2-embedder)]
- **Lawformer**: Long-context legal document model. [[Paper](https://www.sciencedirect.com/science/article/pii/S2666651021000176)]

### Multilingual & Regional Models

- **InLegalBERT**: Trained on 5.4M Indian legal documents. [[Code](https://huggingface.co/law-ai/InLegalBERT)]
- **OpenGPT-X / Teuken-7B**: Covers all 24 official EU languages. [[Code](https://huggingface.co/openGPT-X/Teuken-7B-instruct-research-v0.4)]
- **EmuBERT**: RoBERTa-based model for Australian law. [[Code](https://huggingface.co/isaacus/emubert)]

## Legal Search & Research

### Legal Reasoning & Theory

- **LRAS: Advanced Legal Reasoning with Agentic Search**, arXiv 2026. [[Paper](https://arxiv.org/abs/2601.07296)]
- **L-MARS: Legal Multi-Agent Workflow with Orchestrated Reasoning and Agentic Search**, arXiv 2025. [[Paper](https://arxiv.org/abs/2509.00761)]
- **Legal&Delta;: Enhancing Legal Reasoning in LLMs via Reinforcement Learning**, arXiv 2025. [[Paper](https://arxiv.org/abs/2508.12281)]
- **Reimagining Legal Fact Verification with GenAI**, CHI 2026. [[Paper](https://arxiv.org/abs/2602.06305)]

### Retrieval-Augmented Generation (RAG)

- **LegalBench-RAG: A Benchmark for Retrieval-Augmented Generation in the Legal Domain**, arXiv 2024. [[Paper](https://arxiv.org/abs/2408.10343)]
- **AI-Powered Lawyering: AI Reasoning Models, RAG, and the Future of Legal Practice**, 2025. [[Paper](https://www.governance.ai/research-paper/ai-powered-lawyering-ai-reasoning-models-retrieval-augmented-generation-and-the-future-of-legal-practice)]

### Knowledge Graphs & Ontologies

- **Capturing Legal Reasoning Paths from Facts to Law in a Legal Knowledge Graph**, K-CAP '25 2025. [[Paper](https://arxiv.org/abs/2508.17340)]
- **EuroVoc**: EU's multilingual thesaurus. [[Website](https://op.europa.eu/en/web/eu-vocabularies/concept-scheme/-/resource?uri=http://publications.europa.eu/resource/authority/eurovoc)]
- **LKIF-Core**: Legal Knowledge Interchange Format. [[GitHub](https://github.com/RinkeHoekstra/lkif-core)]
- **SALI LMSS**: Structured ontology for legal matter types. [[GitHub](https://github.com/SALIstandards/LMSS)]
- **LegalDocML / Akoma Ntoso**: XML + ontology for legislative and judicial documents. [[Website](http://www.akomantoso.org/)]

## Litigation & Dispute Resolution

### Legal Judgment Prediction (LJP)

- **LegalReasoner: Step-wised Verification-Correction for Legal Judgment Reasoning**, ACL 2025. [[Paper](https://aclanthology.org/2025.acl-long.361/)]
- **GLARE: Agentic Reasoning for Legal Judgment Prediction**, arXiv 2025. [[Paper](https://arxiv.org/abs/2508.16383)]
- **AgentsBench: A Multi-Agent LLM Simulation Framework for Legal Judgment Prediction**, MDPI 2025. [[Paper](https://www.mdpi.com/2079-8954/13/8/641)]

### Courtroom Simulation & Argument Mining

- **Courtroom Simulator AI**. [[GitHub](https://github.com/E-Asrar-Haghighi/courtroom-simulator-ai)]
- **A Reflective Multi-Agent Approach for Legal Argument Generation**, arXiv 2025. [[Paper](https://arxiv.org/abs/2506.02992)]

### Online Dispute Resolution (ODR)

- **Kleros**: Decentralized, blockchain-based crowdsourced justice protocol. [[Website](https://kleros.io/)]

## Compliance, Governance, & Regulation

- **Law-Following AI: Designing AI Agents to Obey Human Laws**, Fordham Law Review. [[Paper](https://ir.lawnet.fordham.edu/cgi/viewcontent.cgi?article=6171&context=flr)]
- **Context Reasoner: Incentivizing Reasoning Capability for Contextualized Privacy and Safety Compliance via RL**, EMNLP 2025. [[Paper](https://aclanthology.org/2025.emnlp-main.44/)]

## Advisory, Consultation & Transactions

### Contract Analysis & Drafting

- **Develop AI Agent for Legal Document Drafting**. [[Website](https://www.cloudapper.ai/legal-document-drafting-agent/)]
- **Automated generation of smart contract code from legal contract specifications**, SoSyM 2025. [[Paper](https://link.springer.com/article/10.1007/s10270-024-01187-9)]

### Negotiation & Deal Simulation

- **NegotiationGym: A Platform for Developing and Evaluating Negotiation Agents**, 2025. [[Paper](https://arxiv.org/html/2510.04368v1)]

## Workflow Automation & E-Discovery

- **The key to autonomous legal workflows with agentic AI**, Thomson Reuters 2025. [[Blog](https://legal.thomsonreuters.com/blog/the-key-to-autonomous-legal-workflows-with-agentic-ai/)]
- **AI in E-Discovery**, American Bar Association 2026. [[Article](https://www.americanbar.org/groups/science_technology/resources/scitech-lawyer/2026-winter/ai-e-discovery/)]
- **FreeEed**: AI-enabled open-source e-discovery platform. [[GitHub](https://freeeed.org/)]

## Benchmarks & Evaluation

- **SafeLawBench**: Towards Safe Alignment of Large Language Models. [[Paper](https://aclanthology.org/2025.findings-acl.721/)]
- **LegalBench**: 162-task benchmark for English legal reasoning in LLMs. [[GitHub](https://github.com/HazyResearch/legalbench)]
- **LawBench**: 20-task Chinese legal benchmark. [[Paper](https://aclanthology.org/2024.emnlp-main.452.pdf)]
- **LexGLUE**: 7-task legal NLP benchmark. [[Paper](https://aclanthology.org/2022.acl-long.297/)]
- **LegalAgentBench**: Evaluating LLM Agents in Legal Domain. [[Paper](https://aclanthology.org/2025.acl-long.116/)]
- **PrivaCI-Bench**: Evaluating Privacy with Contextual Integrity and Legal Compliance. [[Paper](https://aclanthology.org/2025.acl-long.518/)]
- **MLEB (Massive Legal Embedding Benchmark)**: Comprehensive benchmark for legal text embedding models. [[GitHub](https://huggingface.co/blog/isaacus/introducing-mleb)]

## Ethics, Fairness, and Bias

- **Consumer Protection in AI–Governed Credit Markets**, UI JLTP 2026. [[Paper](https://uillinoisjltp.com/journal/consumer-protection-in-ai-governed-credit-markets-algorithmic-bias-and-the-right-to-explanation/)]
- **Simulated Justice: How AI Alignment Replaces Conflict with Coherence**, IHRLR 2026.
- **When AI Sounds Judicious: How AI Alignment Mimic Procedure While Evading Accountability**, UCLA JLT 2026.
- **PKU-SafeRLHF: Towards Multi-Level Safety Alignment for LLMs**, ACL 2025. [[Paper](https://aclanthology.org/2025.acl-long.1544.pdf)]

## Datasets & Corpora

### Pretraining Corpora

| Name | Size | Languages | Description |
|------|------|-----------|-------------|
| [MultiLegalPile](https://huggingface.co/datasets/joelniklaus/Multi_Legal_Pile) | 689 GB | 24 | From 17 jurisdictions |
| [Pile of Law](https://huggingface.co/datasets/pile-of-law/pile-of-law) | 256 GB | EN | US legal and administrative data |
| [LeXFiles](https://github.com/coastalcph/lexlms) | 19B tokens | EN | 6 English-speaking legal systems |
| [CourtListener](https://www.courtlistener.com/) | 9M+ opinions | EN | US court opinions |
| [Caselaw Access Project (CAP)](https://github.com/harvard-lil/capstone) | 6.9M cases | EN | US court decisions, 1600s-2020 |

### Task-Specific Datasets

- **Judgment Prediction**: [CAIL2018](https://github.com/china-ai-law-challenge/CAIL2018) (2.6M Chinese cases), [ECHR](https://huggingface.co/datasets/AUEB-NLP/ecthr_cases) (11K cases), [ILDC](https://aclanthology.org/2021.acl-long.313/) (34K Indian cases)
- **Case Retrieval**: [LeCaRD](https://huggingface.co/datasets/sentence-transformers/lecard-v2) (10.7K Chinese cases), [COLIEE](https://coliee.org/COLIEE2026/overview) (EN/JA)
- **Question Answering**: [JEC-QA](https://github.com/thunlp/jec-qa) (26K Chinese bar exam questions), [CaseHOLD](https://github.com/reglab/casehold) (53K US case law QA)
- **Summarization**: [BillSum](https://aclanthology.org/D19-5406/) (22K US bills), [Multi-LexSum](https://multilexsum.github.io/) (9.3K expert summaries)
- **Classification**: [CUAD](https://www.atticusprojectai.org/cuad/) (510 contracts), [LEDGAR](https://aclanthology.org/2020.lrec-1.155/) (60K provisions)

## Tools, Platforms & Products

### Full-Stack Legal Platforms

- **Harvey AI**: AI-Native full-stack legal AI with 30+ autonomous agentic workflows. [[Website](https://www.harvey.ai/)]
- **Thomson Reuters**: Owner of CoCounsel, Westlaw, Practical Law, and HighQ. [[Website](https://www.thomsonreuters.com.hk/en/products-services/legal-overview/cocounsel.html)]
- **LexisNexis**: Owner of Lexis+ AI, Protege, and Shepard's citations. [[Website](https://www.lexisnexis.com/en-us/products/lexis-plus-protege.page)]

### Legal Research Platforms

- **Vaquill AI**: Indian legal research platform with agentic workflows. [[Website](https://www.vaquill.ai/)]
- **Leya**: Agentic research and legal memo generation. [[Website](https://legora.com/)]
- **Paxton AI**: Jurisdiction-aware AI legal answers. [[Website](https://www.paxton.ai/)]
- **vLex / Vincent AI**: Global coverage with cross-jurisdictional AI comparison. [[Website](https://vlex.com/vincent-ai)]

### Document Automation & Drafting

- **Docassemble**: Open-source guided legal interviews and document assembly. [[Website](https://projects.suffolklitlab.org/legal-tech-class/docs/introduction-to-docassemble/)]
- **Spellbook**: AI contract drafting and review assistant in Microsoft Word. [[Website](https://www.spellbook.legal/)]
- **Clearbrief**: AI-powered factual verification and drafting assistance. [[Website](https://clearbrief.com/)]

### Contract Lifecycle Management (CLM)

- **Ironclad**: CLM with AI clause detection, redlining, and Jurist AI assistant. [[Website](https://ironcladapp.com/product/ai-based-contract-management)]
- **Icertis**: Enterprise CLM leader with Icertis Vera AI. [[Website](https://www.icertis.com/)]
- **Robin AI**: AI contract negotiation and review platform. [[Website](https://robinai.com/)]

### E-Discovery & Document Review

- **Relativity**: Industry leader with aiR for Review and aiR for Privilege. [[Website](https://www.relativity.com/data-solutions/air/privilege/)]
- **Everlaw**: Cloud-native with AI clustering and predictive coding. [[Website](https://www.everlaw.com/)]
- **Nuix**: High-performance processing with Cognitive AI (CogAI). [[Website](https://www.nuix.com/)]

### Practice Management & Legal Ops

- **Clio**: Leading cloud-based practice management suite featuring Clio Duo AI. [[Website](https://www.clio.com/features/legal-ai-software/)]
- **Filevine**: Legal operating system with AI-enhanced case lifecycle management. [[Website](https://www.filevine.com/)]
- **Darrow**: Litigation intelligence identifying meritorious lawsuits from public data. [[Website](https://www.darrow.ai/resources/legal-intelligence-assets)]

### Intellectual Property & Patent Tech

- **PatSnap**: Patent analytics and intelligence powered by AI. [[Website](https://www.patsnap.com/)]
- **Anaqua**: Comprehensive IP management system. [[Website](https://www.anaqua.com/)]

### MCP Servers for Legal

*See also: [Legal MCP Servers](#legal-mcp-servers) in the Agentic Infrastructure section.*

## Agentic Infrastructure & OpenClaw

This section covers the foundational infrastructure that powers legal agents, including core frameworks like OpenClaw, reusable skill libraries, and the protocols that enable agent-to-tool and agent-to-agent communication.

### Core Frameworks

| Name | Stars | Description |
|------|-------|-------------|
| [OpenClaw](https://github.com/openclaw/openclaw) | 312k | Personal AI assistant, multi-channel, skills-based. The de facto standard. |
| [gitclaw](https://github.com/SawyerHood/gitclaw) | - | OpenClaw on GitHub Actions (no server needed). |
| [webclaw](https://github.com/ibelick/webclaw) | - | Fast web client for OpenClaw. |
| [NanoClaw, ZeroClaw, etc.](https://www.aimagicx.com/blog/openclaw-alternatives-comparison-2026) | - | A growing ecosystem of OpenClaw alternatives and variants. |

### Legal Skills

Skills are reusable, portable instructions that encode legal expertise into AI workflows. They are a critical component for building specialized legal agents.

| Collection | Stars | Description |
|------------|-------|-------------|
| [awesome-legal-skills](https://github.com/lawvable/awesome-legal-skills) | 169 | Curated list of skills for commercial law, privacy, compliance, employment, and more. |
| [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | 37.1k | 5,400+ community skills, including a dedicated legal category. |

### Legal MCP Servers

Model Context Protocol (MCP) servers act as bridges, giving agents secure access to external tools, databases, and APIs.

| Server | Description |
|--------|-------------|
| [us-legal-mcp](https://github.com/JamesANZ/us-legal-mcp) | Comprehensive US legislation (Congress.gov, Federal Register, US Code, CourtListener). |
| [court-listener-mcp](https://github.com/Travis-Prall/court-listener-mcp) | Access to the full CourtListener legal database. |
| [Vaquill AI MCP](https://www.vaquill.com/) | Access to 20M+ Indian judgments. |
| [Obsidian RI MCP](https://obsidianri.com/blog/top-regulatory-intelligence-mcp-2026) | Real-time regulatory monitoring from official government sources. |
| [freema/openclaw-mcp](https://github.com/freema/openclaw-mcp) | Secure bridge between Claude.ai and a self-hosted OpenClaw assistant. |

### Multi-Agent Frameworks

### Protocols

## Other Awesome Lists

- [Awesome-LegalAI-Resources](https://github.com/CSHaitao/Awesome-LegalAI-Resources)
- [awesome-legaltech](https://github.com/Vaquill-AI/awesome-legaltech)
- [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)

## Citation

```bibtex
@misc{han2026awesomeworldlawagent,
  author = {Sirui Han},
  title = {Awesome World Law Agent: A Comprehensive Survey of AI in Law},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/siruihan2024/awesome-world-law-agent}}
}
```

## Contributing

Contributions are welcome! Please read the [contribution guidelines](how-to-PR.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
