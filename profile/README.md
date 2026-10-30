<h1 align="center">Nirry</h1>

<p align="center"><em>Local-first platforms for AI and security work.</em></p>

<p align="center">
  <a href="https://nirry.net"><strong>nirry.net</strong></a>
  &nbsp;·&nbsp;
  <a href="mailto:info@nirry.net">info@nirry.net</a>
</p>

---

I build systems that run entirely on one machine — dependency-light, auditable,
and tuned to do real work on ordinary hardware. This org is where I open-source
the small, self-contained tools that fall out of that work, and write down what I
learned building each one.

Think of it as a **learning journal that happens to be useful software**: every
repo carries a *Learning notes* section — what I set out to learn, and what
actually surprised me.

### 🔧 Tools

| Project | What it does |
| --- | --- |
| **[vramlease](https://github.com/nirry-dev/vramlease)** | Cooperative GPU memory leasing — let several local jobs share one GPU by VRAM *budget*, with crash-safe leases (a lease lives as long as its TCP connection) and priority + preemption. Pure stdlib. |
| **[llm-council](https://github.com/nirry-dev/llm-council)** | Multi-model consensus for local models: propose → **blind** peer review → chair synthesis, over any OpenAI-compatible endpoint (llama.cpp, Ollama, LM Studio…). Pure stdlib. |
| **[vulntriage](https://github.com/nirry-dev/vulntriage)** | Triage dependency CVEs by *real-world exploitability* — correlate OSV findings with CISA KEV + FIRST EPSS and rank by what to fix first, not raw CVSS. Pure stdlib. |

*More tools land here as I build them.*

### 🧭 What I work on

- **Local AI** — serving open-weight models on consumer GPUs, GPU scheduling, interpretability tooling.
- **Applied security** — safety-by-construction tooling for authorized testing.
- **Dependency-minimal systems** — standard-library-first and buildless, so tools stay small, legible, and easy to audit.

### 📫 Elsewhere

- **Portfolio** — [nirry.net](https://nirry.net)
- **Email** — [info@nirry.net](mailto:info@nirry.net)
