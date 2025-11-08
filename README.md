# MCP & A2A (ADK/Agent Engine)

This repository contains my reproductions of three Google codelabs focused on **Model Context Protocol (MCP)** and **Agent-to-Agent (A2A)** communication using the **Agent Development Kit (ADK)** and **Agent Engine**.

> Each codelab lives in its own folder with its **own README**, runnable code, and a **video walkthrough** placeholder.

---

## 📁 Repository Structure

```
mcp-a2a-codelabs/
├─ codelab-1-multi-agents-adk-a2a/          # Create multi-agent system with ADK, deploy to Agent Engine, start A2A
│  ├─ README.md
│  └─ ... (code & assets)
├─ codelab-2-currency-agent-mcp-a2a/        # Getting started with ADK, MCP, and A2A (Currency Agent)
│  ├─ README.md
│  └─ ... (code & assets)
├─ codelab-3-a2a-purchasing-concierge/      # Intro to A2A with Action Engine (Purchasing Concierge)
│  ├─ README.md
│  └─ ... (code & assets)
└─ README.md                                # (this file)
```

---

## 🎯 Assignment Goals

* Practice **MCP** (tooling/resources exposure to models) and **A2A** (agent-to-agent protocols).
* Use **ADK** to build & run agents locally and **deploy to Agent Engine** where required.
* Produce runnable artifacts + **video walkthroughs** for each codelab.

---

## 🔗 Codelabs (Source)

* **Codelab 1:** Create multi agent system with ADK, deploy in Agent Engine, get started with A2A
  [https://codelabs.developers.google.com/codelabs/create-multi-agents-adk-a2a#0](https://codelabs.developers.google.com/codelabs/create-multi-agents-adk-a2a#0)

* **Codelab 2:** Getting started with ADK, MCP and A2A (Currency Agent)
  [https://codelabs.developers.google.com/codelabs/currency-agent#0](https://codelabs.developers.google.com/codelabs/currency-agent#0)

* **Codelab 3:** Getting started with A2A Action Engine (Purchasing Concierge)
  [https://codelabs.developers.google.com/intro-a2a-purchasing-concierge#0](https://codelabs.developers.google.com/intro-a2a-purchasing-concierge#0)

> Exact instructions, environment variables, and commands are documented inside each codelab’s sub-README.

---

## 🧰 Prerequisites (High-Level)

* Recent **Python** and/or **Node.js** toolchains (as required by each codelab).
* Access to **Agent Engine** (if deployment is part of the exercise).
* Any API keys or project configuration mentioned in the codelabs.
* Recommended: virtual environments (`venv` / `conda`) or npm/yarn workspaces per codelab.

> See each folder’s README for precise versions, env vars, and run scripts.

---

## 🚀 How to Run (Quick Start)

```bash
# 1) Clone this repo
git clone <your-repo-url> mcp-a2a-codelabs
cd mcp-a2a-codelabs

# 2) Choose a codelab
cd codelab-1-multi-agents-adk-a2a    # or codelab-2-... / codelab-3-...

# 3) Follow the local README for environment setup & run commands
#    (e.g., create venv, install deps, set env vars, start agents/services)
```

---

## 🎥 Video Walkthroughs (Placeholders)

* (**Codelab 1 Video:** )[https://youtu.be/KMCOmMYH7mw]
* (**Codelab 2 Video:** )[#]
* (**Codelab 3 Video:** *)[#]

Each subfolder README includes a short agenda of what the video demonstrates and the exact commands used during the recording.

---

## ✅ Deliverables Checklist

* [ ] `codelab-1-multi-agents-adk-a2a/`

  * [ ] Code compiles/runs locally
  * [ ] Agent Engine deploy (if applicable)
  * [ ] README with steps, env vars, sample outputs
  * [ ] **Video link added**
* [ ] `codelab-2-currency-agent-mcp-a2a/`

  * [ ] Code compiles/runs locally
  * [ ] MCP/A2A flows validated
  * [ ] README with steps, env vars, sample outputs
  * [ ] **Video link added**
* [ ] `codelab-3-a2a-purchasing-concierge/`

  * [ ] Code compiles/runs locally
  * [ ] A2A action engine interactions validated
  * [ ] README with steps, env vars, sample outputs
  * [ ] **Video link added**

---

## 🧪 Verification & Evidence

Each sub-README includes:

* **Setup & Run** instructions (copy-pasteable).
* **Configuration** (env vars, keys, project IDs).
* **Screenshots / Logs** of successful runs and A2A interactions.
* **Troubleshooting** notes for common errors.

---

## 📄 License

Choose a license appropriate for your coursework or organization. Example:

```
MIT License — see LICENSE file for details.
```

---

## 🙌 Acknowledgments

* Google Codelabs & documentation for ADK, MCP, A2A, and Agent Engine.
* Course staff for assignment design and evaluation criteria.

---

> **Tip:** Keep your subfolder READMEs **self-contained**—someone should be able to run each codelab end-to-end by following only that file.
