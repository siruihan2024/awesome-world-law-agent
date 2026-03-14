# Awesome World Law Agent

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> This repo is created and maintained by [**Sirui Han**](https://siruihan.com/).

An unparalleled, comprehensive, and continuously updated survey of the **World Law Agent** ecosystem. This repository consolidates and curates resources from leading collections, including foundational research, cutting-edge models, commercial platforms, and open-source tools, making it the definitive starting point for anyone building, researching, or investing in the intersection of AI and Law.

This is the most comprehensive survey of its kind, integrating and expanding upon other excellent resources like `Awesome-LegalAI-Resources`, `awesome-legaltech`, and `awesome-llm-apps`.

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
- [Other Awesome Lists](#other-awesome-lists)
- [Citation](#citation)
- [Contributing](#contributing)
- [License](#license)

## Surveys & Overviews

- **Trustworthy Legal Reasoning: A Comprehensive Survey**, Preprints 2026. [[Paper](https://www.preprints.org/manuscript/202602.0870/v1)]
- **LLM Agents in Law: Taxonomy, Applications, and Challenges**, arXiv 2026. [[Paper](https://arxiv.org/abs/2601.06216)]
- **Large Language Models in Legal Systems: A Survey**, Nature 2025. [[Paper](https://www.nature.com/articles/s41599-025-05924-3)]
- **A survey of large language models for legal tasks**, ScienceDirect 2026. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1574013726000158)]
- **AI Agents and the Law**, arXiv 2025. [[Paper](https://arxiv.org/html/2508.08544v1)]
- **The Rise and Potential of Large Language Model Based Agents: A Comprehensive Survey**. [[GitHub](https://github.com/WooooDyy/LLM-Agent-Paper-List)]
- **Natural language processing for the legal domain: A survey of tasks, datasets, models, and challenges**, ACM Computing Surveys 2024. [[Paper](https://dl.acm.org/doi/abs/10.1145/3777009)]
- **Scenario, Role, and Persona: A Scoping Review of Design Strategies for Socially Intelligent AI Agents**, CHI EA 2025. [[Paper](https://dl.acm.org/doi/10.1145/3711956.3712089)]

## Foundational Research

- **GPT-4 Passes the Bar Exam**, 2023. [[Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4389233)]
- **LEGAL-BERT: The Muppets straight out of Law School**, EMNLP 2020. [[Paper](https://aclanthology.org/2020.findings-emnlp.261.pdf)]
- **LexGLUE: A Benchmark Dataset for Legal Language Understanding**, ACL 2022. [[Paper](https://aclanthology.org/2022.acl-long.297/)]
- **LegalBench: A Collaboratively Built Benchmark for Legal Reasoning**, 2023. [[Paper](https://arxiv.org/abs/2308.11462)]
- **Artificial Intelligence and Legal Analytics**, 2017. [[Book](https://www.cambridge.org/core/books/artificial-intelligence-and-legal-analytics/963D4B7E63497576526A3141A338912E)]

## Foundation Models

### Large Language Models (LLMs)

- **SaulLM-7B/54B/141B**: A pioneering Large Language Model for Law. [[Paper](https://arxiv.org/abs/2403.03883)]
- **ChatLaw**: A Multi-Agent Collaborative Legal Large Language Model. [[Paper](https://arxiv.org/abs/2306.16092)] [[Code](https://github.com/PKU-YuanGroup/ChatLaw)]
- **LawGPT**: A Chinese Legal Knowledge-Enhanced Large Language Model. [[Paper](https://arxiv.org/abs/2406.04614)]
- **Lawyer GPT**: A Legal Large Language Model with Enhanced Domain Knowledge. [[Paper](https://dl.acm.org/doi/abs/10.1145/3689299.3689319)]
- **Lawma-8B/70B**: Fine-tuned Llama 3 for legal classification tasks.
- **DISC-LawLLM**: Chinese legal assistant from Fudan. [[GitHub](https://github.com/FudanDISC/DISC-LawLLM)]

### BERT-style & Embedding Models

- **LEGAL-BERT**: Pretrained on EU/US legislation + court cases. [[Paper](https://aclanthology.org/2020.findings-emnlp.261.pdf)]
- **CaseLawBERT**: Trained on Pile of Law corpus. [[Code](https://huggingface.co/pile-of-law/legalbert-large-1.7M-2)]
- **voyage-law-2**: State-of-the-art closed-source embedding model for legal text retrieval.
- **Kanon 2 Embedder**: #1 on MLEB benchmark; legal semantic search + RAG. [[Code](https://huggingface.co/isaacus/kanon-2)]
- **Lawformer**: Long-context legal document model.

### Multilingual & Regional Models

- **InLegalBERT**: Trained on 5.4M Indian legal documents.
- **Pasal.id**: RAG-powered access to 40,000+ Indonesian regulations.
- **NyayaSahayak**: AI legal assistant covering Indian Constitution.
- **OpenGPT-X / Teuken-7B**: Covers all 24 official EU languages.
- **EmuBERT**: RoBERTa-based model for Australian law.

## Legal Search & Research

### Legal Reasoning & Theory

- **LRAS: Advanced Legal Reasoning with Agentic Search**, arXiv 2026. [[Paper](https://arxiv.org/abs/2601.07296)]
- **L-MARS: Legal Multi-Agent Workflow with Orchestrated Reasoning and Agentic Search**, arXiv 2025. [[Paper](https://arxiv.org/abs/2509.00761)]
- **LegalΔ: Enhancing Legal Reasoning in LLMs via Reinforcement Learning**, arXiv 2025. [[Paper](https://arxiv.org/abs/2508.12281)]
- **Reimagining Legal Fact Verification with GenAI**, CHI 2026. [[Paper](https://dl.acm.org/doi/abs/10.1145/3613904.3642314)]

### Retrieval-Augmented Generation (RAG)

- **LegalBench-RAG: A Benchmark for Retrieval-Augmented Generation in the Legal Domain**, arXiv 2024. [[Paper](https://arxiv.org/abs/2408.10343)]
- **AI-Powered Lawyering: AI Reasoning Models, RAG, and the Future of Legal Practice**, 2025. [[Paper](https://www.governance.ai/research-paper/ai-powered-lawyering-ai-reasoning-models-retrieval-augmented-generation-and-the-future-of-legal-practice)]

### Knowledge Graphs & Ontologies

- **Capturing Legal Reasoning Paths from Facts to Law in a Legal Knowledge Graph**, ICAIL 2025. [[Paper](https://arxiv.org/abs/2508.17340)]
- **EuroVoc**: EU's multilingual thesaurus. [[Website](https://op.europa.eu/en/web/eu-vocabularies/concept-scheme/-/resource?uri=http://publications.europa.eu/resource/authority/eurovoc)]
- **LKIF-Core**: Legal Knowledge Interchange Format.
- **SALI LMSS**: Structured ontology for legal matter types.
- **LegalDocML / Akoma Ntoso**: XML + ontology for legislative and judicial documents.

## Litigation & Dispute Resolution

### Legal Judgment Prediction (LJP)

- **GLARE: Agentic Reasoning for Legal Judgment Prediction**, arXiv 2025. [[Paper](https://arxiv.org/abs/2508.16383)]
- **LegalReasoner: Step-wised Verification-Correction for Legal Judgment Reasoning**, ACL 2025. [[Paper](https://aclanthology.org/2025.acl-long.115/)]
- **AgentsBench: A Multi-Agent LLM Simulation Framework for Legal Judgment Prediction**, MDPI 2025. [[Paper](https://www.mdpi.com/2079-8954/13/8/641)]

### Courtroom Simulation & Argument Mining

- **Courtroom Simulator AI**. [[GitHub](https://github.com/E-Asrar-Haghighi/courtroom-simulator-ai)]
- **A Reflective Multi-Agent Approach for Legal Argument Generation**, arXiv 2025. [[Paper](https://arxiv.org/abs/2506.02992)]

### Online Dispute Resolution (ODR)

- **Kleros**: Decentralized, blockchain-based crowdsourced justice protocol. [[Website](https://kleros.io/)]
- **Modria**: Pioneer ODR platform (now owned by Tyler Technologies).

## Compliance, Governance, & Regulation

- **Law-Following AI: Designing AI Agents to Obey Human Laws**, Fordham Law Review. [[Paper](https://ir.lawnet.fordham.edu/cgi/viewcontent.cgi?article=6171&context=flr)]
- **Context Reasoner: Incentivizing Reasoning Capability for Contextualized Privacy and Safety Compliance via RL**, EMNLP 2025. [[Paper](https://aclanthology.org/2025.emnlp-main.1/)]
- **Drata**: GRC automation with continuous monitoring for SOC 2, ISO 27001, HIPAA, GDPR, EU AI Act.
- **Vanta**: Compliance automation with 375+ integrations and AI vendor risk assessment.

## Advisory, Consultation & Transactions

### Contract Analysis & Drafting

- **Develop AI Agent for Legal Document Drafting**. [[Website](https://www.cloudapper.ai/legal-document-drafting-agent/)]
- **Automated generation of smart contract code from legal contract specifications**, SoSyM 2025. [[Paper](https://link.springer.com/article/10.1007/s10270-024-01187-9)]

### Negotiation & Deal Simulation

- **NegotiationGym: A Platform for Developing and Evaluating Negotiation Agents**, 2025. [[Paper](https://arxiv.org/abs/2501.08636)]

## Workflow Automation & E-Discovery

- **The key to autonomous legal workflows with agentic AI**, Thomson Reuters 2025. [[Blog](https://legal.thomsonreuters.com/blog/the-key-to-autonomous-legal-workflows-with-agentic-ai/)]
- **AI in E-Discovery**, American Bar Association 2026. [[Article](https://www.americanbar.org/groups/science_technology/resources/scitech-lawyer/2026-winter/ai-e-discovery/)]
- **FreeEed**: AI-enabled open-source e-discovery platform.

## Benchmarks & Evaluation

- **LegalBench**: 162-task benchmark for English legal reasoning in LLMs. [[GitHub](https://github.com/HazyResearch/legalbench)]
- **LawBench**: 20-task Chinese legal benchmark. [[Paper](https://aclanthology.org/2024.emnlp-main.452.pdf)]
- **LexGLUE**: 7-task legal NLP benchmark. [[Paper](https://aclanthology.org/2022.acl-long.297/)]
- **LegalAgentBench**: Evaluating LLM Agents in Legal Domain. [[Paper](https://aclanthology.org/2025.acl-long.116/)]
- **SafeLawBench**: Towards Safe Alignment of Large Language Models. [[Paper](https://aclanthology.org/2025.acl-long.117/)]
- **PrivaCI-Bench**: Evaluating Privacy with Contextual Integrity and Legal Compliance. [[Paper](https://aclanthology.org/2025.acl-long.118/)]
- **MLEB (Massive Legal Embedding Benchmark)**: Comprehensive benchmark for legal text embedding models.

## Ethics, Fairness, and Bias

- **Consumer Protection in AI–Governed Credit Markets**, UI JLTP 2026. [[Paper](https://uillinoisjltp.com/journal/consumer-protection-in-ai-governed-credit-markets-algorithmic-bias-and-the-right-to-explanation/)]
- **Simulated Justice: How AI Alignment Replaces Conflict with Coherence**, IHRLR 2026. [[Paper](https://www.ihrlr.com/simulated-justice-how-ai-alignment-replaces-conflict-with-coherence/)]
- **When AI Sounds Judicious: How AI Alignment Mimic Procedure While Evading Accountability**, UCLA JLT 2026. [[Paper](https://uclajolt.com/when-ai-sounds-judicious-how-ai-alignment-mimic-procedure-while-evading-accountability/)]
- **PKU-SafeRLHF: Towards Multi-Level Safety Alignment for LLMs**, ACL 2025. [[Paper](https://aclanthology.org/2025.acl-long.119/)]

## Datasets & Corpora

### Pretraining Corpora

| Name | Size | Languages | Description |
|---|---|---|---|
| **MultiLegalPile** | 689 GB | 24 | From 17 jurisdictions |
| **Pile of Law** | 256 GB | EN | US legal and administrative data |
| **LeXFiles** | 19B tokens | EN | 6 English-speaking legal systems |
| **CourtListener** | 9M+ opinions | EN | US court opinions |
| **Caselaw Access Project (CAP)** | 6.9M cases | EN | US court decisions, 1600s-2020 |

### Task-Specific Datasets

- **Judgment Prediction**: CAIL2018 (2.6M Chinese cases), ECHR (11K cases), ILDC (34K Indian cases)
- **Case Retrieval**: LeCaRD (10.7K Chinese cases), COLIEE (EN/JA)
- **Question Answering**: JEC-QA (26K Chinese bar exam questions), CaseHOLD (53K US case law QA)
- **Summarization**: BillSum (22K US bills), Multi-LexSum (9.3K expert summaries)
- **Classification**: CUAD (510 contracts), LEDGAR (60K provisions)

## Tools, Platforms & Products

### Full-Stack Legal Platforms

- **Harvey AI**: AI-Native full-stack legal AI with 30+ autonomous agentic workflows.
- **Thomson Reuters**: Owner of CoCounsel, Westlaw, Practical Law, and HighQ.
- **LexisNexis**: Owner of Lexis+ AI, Protégé, and Shepard's citations.

### Legal Research Platforms

- **Vaquill AI**: Indian legal research platform with agentic workflows.
- **Leya**: Agentic research and legal memo generation.
- **Paxton AI**: Jurisdiction-aware AI legal answers.
- **vLex / Vincent AI**: Global coverage with cross-jurisdictional AI comparison.

### Document Automation & Drafting

- **Docassemble**: Open-source guided legal interviews and document assembly.
- **Spellbook**: AI contract drafting and review assistant in Microsoft Word.
- **Clearbrief**: AI-powered factual verification and drafting assistance.

### Contract Lifecycle Management (CLM)

- **Ironclad**: CLM with AI clause detection, redlining, and Jurist AI assistant.
- **Icertis**: Enterprise CLM leader with Icertis Vera AI.
- **Robin AI**: AI contract negotiation and review platform.

### E-Discovery & Document Review

- **Relativity**: Industry leader with aiR for Review and aiR for Privilege.
- **Everlaw**: Cloud-native with AI clustering and predictive coding.
- **Nuix**: High-performance processing with Cognitive AI (CogAI).

### Practice Management & Legal Ops

- **Clio**: Leading cloud-based practice management suite featuring Clio Duo AI.
- **Filevine**: Legal operating system with AI-enhanced case lifecycle management.
- **Darrow**: Litigation intelligence identifying meritorious lawsuits from public data.

### Intellectual Property & Patent Tech

- **PatSnap**: Patent analytics and intelligence powered by AI.
- **Anaqua**: Comprehensive IP management system.

### MCP Servers for Legal

- **Vaquill AI MCP**: Access to 20M+ Indian judgments.
- **CourtListener MCP**: Multiple community-built servers for US case law.
- **adeu**: Agentic DOCX Redlining Engine for Word Track Changes.

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
    howpublished = {\url{https://github.com/your-username/awesome-world-law-agent}}
}
```

## Contributing

Contributions are welcome! Please read the [contribution guidelines](how-to-PR.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
