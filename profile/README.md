<div align="center">

<img src="https://raw.githubusercontent.com/Skybox-Code-Repository-Knowledge-Graph/.github/main/profile/assets/skybox-wordmark.svg" alt="skybox — code repository knowledge graph" width="520"/>

<br/>

**Know what breaks before you change it.**

<br/>

![One binary](https://img.shields.io/badge/one_binary-runs_on_your_machine-38bdf8)
![Platforms](https://img.shields.io/badge/macOS_·_Windows_·_Linux-supported-6366f1)
![Languages](https://img.shields.io/badge/languages-14-a855f7)

</div>

---

## What is skybox?

skybox reads your repositories and builds a knowledge graph of them: every function, class and route, and how they call each other. Your AI coding agent then asks the graph instead of grepping and guessing:

> **Where is it? How does it work? What breaks if I change it?**

```mermaid
flowchart LR
    R([your repositories]) --> G[("knowledge graph")]
    G --> Q["query: find it"]
    G --> C["context: understand it"]
    G --> I["impact: see what breaks"]
    Q & C & I --> A([your AI agent])

    style R fill:#38bdf8,color:#fff,stroke:none
    style G fill:#6366f1,color:#fff,stroke:none
    style A fill:#22c55e,color:#fff,stroke:none
```

## Try it

```bash
npm install -g @skylence-ai/skybox
skybox setup      # connects skybox to your coding agent
skybox index .    # index the current repository
```

**TL;DR**: one binary on your own machine. It indexes your code into a graph, and your agent uses it to find, understand and safely change that code, across one repository or many.

<br/>

<div align="center">

Built by **[Skylence](https://skylence.be)**

</div>
