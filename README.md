<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Abhishek Sharma: AI engineer — evaluation harnesses, LLM pipelines, SWE-bench, SWE-Smith, ARC-AGI">
</p>

Software engineer based in Noida, working in Gurugram, India. I build **evaluation harnesses and LLM pipelines** — turning real repository changes into benchmark tasks, scoring model outputs, and shipping tools that work without a paid API.

I like work where the hard part is judgment: deciding what a correct answer looks like, writing tests that prove it, and making sure the whole thing runs the same way in CI as it does locally.

---

### What I work on

<p align="center"><img src="./assets/pipeline.svg" width="100%" alt="Pipeline: a real repo change becomes a task with tests, a model attempts it, and the harness scores it"></p>

- **AI coding tasks.** I turn real repository changes into SWE-bench / SWE-Smith-style tasks: a clear problem statement, a reference fix, and tests that fail before the fix and pass after it.
- **Reasoning benchmarks.** I've worked on ARC-AGI abstract-reasoning tasks alongside the coding benchmarks.
- **Evaluation harnesses.** I've built harnesses that run and score tasks against models automatically, using pytest, Docker and GitHub Actions.

### Open source

- **[WooCommerce](https://github.com/woocommerce/woocommerce)**: pull requests and issue reports. [See my PRs →](https://github.com/woocommerce/woocommerce/pulls?q=author%3Aabhiishek-sharma)

### A day at the desk

<p align="center"><img src="./assets/chibi.svg" width="100%" alt="Chibi Abhishek debugging with chai and a rubber duck: the test fails, then it passes and he celebrates"></p>

### Things I've built

| Project | What it is | Stack |
|---|---|---|
| **[QueryForge](https://github.com/abhiishek-sharma/QueryForge)** | Upload a CSV or SQLite file, ask a question in plain English, get SQL and results. Local model only — no API key. 16/16 eval cases correct on `qwen2.5-coder:7b` (filter, aggregation, join, ambiguous, unanswerable). Five-layer read-only SQLite enforcement, each layer covered by its own test. | Python, FastAPI, React, Ollama, sqlparse |
| **[Automation Auditor](https://github.com/abhiishek-sharma/automation-auditor)** | CLI that detects automation jobs that exit 0 but produce the wrong outcome — wrong file, duplicate inserts, partial batch, stale output, swallowed exception. 10/10 synthetic scenarios correct, 0 false alerts. Verdict is always deterministic; LLM adds an optional plain-English explanation. | Python, Ollama (optional) |
| **[Aspiron Systems](https://aspironsystems.com)** | Production website for an SAP training and consulting company (~3,200 monthly visitors). Built end to end, shipping ongoing features and fixes. | Next.js, React, TypeScript, Tailwind CSS |

### Tools I use

<p align="center"><img src="./assets/stack.svg" width="100%" alt="Tools: Python, TypeScript, JavaScript, SQL, pytest, Docker, GitHub Actions, Next.js, React, FastAPI, Tailwind CSS, Ollama, SWE-bench, SWE-Smith, ARC-AGI"></p>

### Elsewhere

- Runner-up, **Smart India Hackathon 2023** (national level)
- B.Tech. in Computer Science, Galgotias University

### Contribution snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/abhiishek-sharma/abhiishek-sharma/output/github-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/abhiishek-sharma/abhiishek-sharma/output/github-snake.svg" width="100%" alt="A snake eating my GitHub contribution graph">
</picture>

<p align="center"><img src="./assets/footer.svg" width="100%" alt="Open to full-time AI/ML and LLM engineering roles, and flexible AI coding-task work"></p>

<p align="center"><a href="https://www.linkedin.com/in/abhisheksharma04/">LinkedIn</a> · Abhisheksharmaa1404@gmail.com</p>
