<p align="center">
  <img src="./assets/profile-header.svg" alt="Sumeet Basfore — building the tools I wish existed" width="100%" />
</p>

<p align="center">
  <strong>Developer tools for working with AI coding agents.</strong><br/>
  <sub>Local-first · inspectable · built in public</sub>
</p>

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="" />
</p>

I build developer tools, experiment with AI coding workflows, and occasionally disappear down a completely unrelated rabbit hole.

The question I keep coming back to:

<p align="center">
  <img src="./assets/typing.svg" alt="what happens after the AI writes the code?" />
</p>

Who checks it, understands it, and decides it's ready? I'm interested in software that makes those answers clearer, especially when it runs locally and stays under your control.

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="" />
</p>

## Start here

| If you want to… | Go to |
| :-- | :-- |
| 🔭 See what I'm building | [Selected work](#selected-work) |
| 🔍 Look at the code | The repo link under each project |
| 🧪 Browse smaller experiments | [On the workbench](#on-the-workbench) |
| 📬 Get in touch | [Around the web](#around-the-web) |

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="" />
</p>

## Selected work

### [01 — sraww](https://github.com/Sumeet-basfore/sraww) &nbsp;/&nbsp; draw, then ask why

A local, single-user Excalidraw-style whiteboard. Drawings are plain `.excalidraw` files on your disk. It adds an AI assistant that uses your existing Claude Pro or ChatGPT Plus subscriptions through their command-line tools, plus architecture maps that show how a project's folders depend on each other. The app holds no API keys and no accounts.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Excalidraw](https://img.shields.io/badge/Excalidraw-6965DB?style=flat-square) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

· [Explore the repo →](https://github.com/Sumeet-basfore/sraww)

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="" />
</p>

### [02 — Traject](https://github.com/Sumeet-basfore/traject) &nbsp;/&nbsp; debug the agent, not just the code

A deterministic, local-first postmortem tool for coding-agent sessions. It connects agent transcripts, Git workspace state, and test output to show where progress went sideways. It uses no LLM to analyze the LLM, and no network calls.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![CLI](https://img.shields.io/badge/CLI-555555?style=flat-square) ![Agent observability](https://img.shields.io/badge/Agent%20observability-7DD3C0?style=flat-square)

· [Explore the repo →](https://github.com/Sumeet-basfore/traject)

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="" />
</p>

### [03 — Relay](https://github.com/Sumeet-basfore/relay) &nbsp;/&nbsp; less trust by default

A local-first, zero-trust MCP security gateway and credential broker for AI agents. Tool calls are checked against [Cedar](https://www.cedarpolicy.com/) policies before they run (default deny), credentials are leased per action instead of sitting in the agent's environment, and every allowed or denied action produces a signed, verifiable receipt. Built around a simple rule: permission should be specific, not assumed.

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-555555?style=flat-square) ![Security](https://img.shields.io/badge/Security-2E7D32?style=flat-square) ![Cedar](https://img.shields.io/badge/Cedar-555555?style=flat-square)

· [Explore the repo →](https://github.com/Sumeet-basfore/relay)

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="" />
</p>

### [04 — Ilvuno](https://github.com/Sumeet-basfore/ilvuno-code) &nbsp;/&nbsp; multiple agents, one place to review

An **in-progress** workspace for orchestrating coding agents, examining their changes, and integrating independently produced work. The ambition is a more manageable, verifiable multi-agent workflow.

The project is in the planning stage. The repository currently holds planning and architecture documents, and the code is still being added.

![Agentic engineering](https://img.shields.io/badge/Agentic%20engineering-555555?style=flat-square) ![In planning](https://img.shields.io/badge/In%20planning-E8B86D?style=flat-square)

· [Explore the repo →](https://github.com/Sumeet-basfore/ilvuno-code)

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="" />
</p>

## On the workbench

Smaller projects and experiments, still evolving.

| Project | Stack | What I'm exploring |
| :-- | :-- | :-- |
| [Forge](https://github.com/Sumeet-basfore/forge) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | A local-first CLI for solo engineering workflows: reusable skills, rules, and project templates for agent-assisted work. |
| [Dylani](https://github.com/Sumeet-basfore/Dylani) | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | A local-first AI studio for prompt-to-UI prototyping, with editable design tokens and React source export. |
| [Sonicity](https://github.com/Sumeet-basfore/Sonicity) | ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) | Audio and transcription experiments. |

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="" />
</p>

## Tech I work with

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-555555?style=flat-square) ![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square) ![Codex CLI](https://img.shields.io/badge/Codex%20CLI-555555?style=flat-square) ![Cedar](https://img.shields.io/badge/Cedar-555555?style=flat-square) ![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square) ![Cargo](https://img.shields.io/badge/Cargo-000000?style=flat-square&logo=rust&logoColor=white)

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="" />
</p>

## A few things I believe

- **Show the evidence.** A green demo isn't the same as verified behavior.
- **Keep the user in control.** Local-first isn't always possible, but it's worth asking why not.
- **Ship the experiment.** Then find out what was wrong with the idea.

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="" />
</p>

## Around the web

<p align="center">
  <a href="https://sumeet-portfolio-sandy.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/sumeet-basfore-405037399/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sumeetbasfore210@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<sub>Most of this work is evolving in public. Some repositories are early experiments, not finished products.</sub>
