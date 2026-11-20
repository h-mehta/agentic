<div align="center">

# 🤖 Agentic AI Projects

**A collection of proof-of-concept AI agents: small, self-contained experiments in building LLM systems that reason, use tools, and take action.**

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![LLM Agents](https://img.shields.io/badge/Focus-LLM%20Agents-6E56CF)
![Status](https://img.shields.io/badge/Status-Experimental-yellow)

</div>

---

## 📖 About

This repository is the **parent folder for my agentic AI proofs of concept (POCs)**. Each subfolder is a standalone project with its own notebook or code and its own README. Each one explores how an AI agent can handle a real-world workflow on its own, for example:

- 🔍 **Investigating** a problem by calling tools and reading the results
- 🧠 **Reasoning** about what it finds to reach a diagnosis
- ⚡ **Acting** by fixing the issue itself or handing it to a human

These projects are kept small on purpose. They show the core pattern clearly and are not production systems.

---

## 🗂️ Projects

| Project | Description | Key Concepts |
|---------|-------------|--------------|
| 🚨 [**Data Pipeline Incident Agent**](Data_pipeline_incident_agent/) | An AI "first responder" for broken data pipelines. It checks health and logs, reruns jobs that failed for temporary reasons, and escalates real problems (schema mismatches, upstream outages) to an engineer. | Tool calling, agent loop, triage logic, DataOps |

*More POCs coming soon.*

---

## 🧱 Repository Structure

```
agentic/
├── README.md                          # You are here
└── Data_pipeline_incident_agent/      # POC: data pipeline incident responder
    ├── Data_Pipeline_Incident_Agent_POC.ipynb
    └── ReadMe.md
```

Each new POC gets its **own folder** at the root, with a README explaining what it does and how to run it.

---

## 🚀 Getting Started

1. Pick a project from the table above.
2. Open its folder and read its README for setup steps (API keys, dependencies, etc.).
3. Most POCs are Jupyter notebooks that run directly in **Google Colab**.

---

<div align="center">

Exploring what AI agents can do, one POC at a time ⚙️

</div>
