# Hi, I'm David 👋

**Engineering leader · Enterprise AI/ML platforms · Banking & Financial Services**
London, UK

I've spent 25+ years building technology for large financial institutions. For the last several years I've led the engineering behind enterprise data, machine learning and GenAI platforms at a tier-1 bank. I run a global engineering organisation of 100+ engineers, and I still write code: Python, RAG pipelines, agent workflows and infrastructure as code.

## Currently working towards

🎯 **Claude Certified Architect – Foundations**

> Validates that you can scope and design Claude-based solutions: selecting the right model and deployment platform, framing agentic versus single-shot architectures, and accounting for evaluation, cost, and responsible deployment from day one.

I'm learning by building. The projects below are my practice ground for those skills, and I'm doing the work in public.

## The hands-on path

- **Agentic patterns.** A cookbook of agent architectures (tool use, routing, multi-step orchestration, guardrails) that I run and compare in an interactive app, so I can see when each pattern earns its complexity.
- **MCP from both sides.** A chat client and servers built on the Anthropic API, exposing tools, resources and prompts. This includes a server wrapping a public economic-data API, and an authenticated service with several clients.
- **A grounded RAG and MCP service on real documents.**
  - Ingests public regulatory filings, parses them into structured facts with no LLM involved, and serves exact-lookup tools next to retrieval for open-ended questions.
  - Answers carry citations, and the system says "not found" rather than guessing.
  - A graph database handles relationship questions.
  - An agent client shows, for every answer, which tools ran, which data store served them, and whether an LLM or plain code produced each step.
- **Claude Code engineering workflow.** Working through Anthropic's Claude Code courses with exercise repos covering context management, project memory files, subagents, skills, hooks, MCP integration and code review. I apply the same practices to my own projects.
- **A study workbench.** A small app I built to structure and track my preparation.
- **End-to-end delivery.** A cross-platform mobile app built from idea to device with Claude Code, to practise the full cycle: plan, build, test, ship.

## What I work on professionally

- **Agentic AI and LLM pipelines.** Multi-agent orchestration (LangGraph), retrieval-augmented generation on AWS Bedrock, and document-intelligence workflows that turn large volumes of unstructured material into structured, reviewable output in a regulated setting.
- **Models as a service.** A central platform that delivers quantitative, statistical and ML models to business teams through consistent interfaces, with versioning, lineage and controlled releases.
- **Model governance and monitoring.** Monitoring frameworks on Databricks for performance and drift, aligned to SR 11-7 style governance and regulatory expectations.
- **Platform engineering.** Kubernetes on AWS, Terraform, GitLab CI/CD, and SRE practice (ELK stack, APM) so models and AI workloads ship repeatably and safely.
- **Data platforms.** Spark and Databricks, Airflow orchestration, federated SQL query, and data catalogues.

## What I care about

- **Grounded AI:** answers that come from retrieved evidence, with citations and a clear "not found" instead of a confident guess.
- **LLMs only where they add value,** with plain deterministic code, SQL and graph queries everywhere else.
- **Evaluation before scale:** test sets, measurable quality, and audit trails for anything that influences a decision.
- **Safe by default:** secrets never committed, test data free of personal information, and failures shown rather than hidden behind defaults.
- **Cloud portability:** small interfaces around storage, models and embeddings, so a home prototype and a production AWS build differ by configuration, not by rewrite.

## Toolbox

![AWS](https://img.shields.io/badge/AWS-Bedrock%20%C2%B7%20EKS%20%C2%B7%20S3%20%C2%B7%20Glue-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-agents-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-embeddings%20%C2%B7%20vector%20search-6A1B9A?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-servers%20%26%20clients-000000?style=flat-square)
![Claude API](https://img.shields.io/badge/Claude%20API-tool%20use-D97757?style=flat-square)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Elastic](https://img.shields.io/badge/ELK%20%C2%B7%20APM-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)

## Certifications

- AWS Certified Solutions Architect, Associate
- AWS Certified Machine Learning, Specialty
- Certificate in Quantitative Finance (CQF)
- Enterprise Model Risk Management (PRMIA)
- Building AI Agents with MongoDB
- 🎯 In progress: Claude Certified Architect – Foundations

## Get in touch

[LinkedIn](https://www.linkedin.com/in/djeyam/)

<sub>Views and projects here are my own.</sub>
