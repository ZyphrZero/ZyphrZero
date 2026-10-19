<div align="center">

# Hi, I'm ZyphrZero <img src="./img/cat.gif" alt="Waving cat" width="45" />

**Test Development Engineer · Developer Tools · AI Agents & Harnesses**

China · UTC+8 · 中文 / English

[Selected work](#selected-work) · [Agent research](#ai-agents--harnesses) · [LINUX DO](https://linux.do/u/cassianvale/summary)

</div>

I build tools that make development and everyday computing more reliable: test automation, native desktop apps, terminals, and AI workflows. My work spans Python testing frameworks, Rust tooling, and applications built with TypeScript, C#, and Go.

AI agents and **agent harnesses** have been a long-running interest of mine. I keep studying how they work, experimenting with their internals, and integrating them into tools I use. My testing background shapes the questions I ask: what context does an agent need, how should its tools behave, and how do we verify that a task is actually complete?

## AI agents & harnesses

I'm especially interested in the engineering around the model:

- **Execution & orchestration** — agent loops, tool calls, approvals, cancellation, and coordination across tasks.
- **Context & continuity** — connecting editors and terminals to agents, managing context budgets, and carrying useful state through sessions, memory, and reusable skills.
- **Reliability & feedback** — event traces, session replay, failure recovery, and tests that make agent behavior easier to inspect and improve.

I explore these through hands-on integrations, source-code study, and private experiments with agent runtimes. [Termy](https://github.com/ZyphrZero/Termy) is one public example: it brings AI coding CLIs into Obsidian and connects them to the active note, editor selection, and workspace.

## Selected work

| Project | What it does | Built with |
| --- | --- | --- |
| [**Termy**](https://github.com/ZyphrZero/Termy) | An Obsidian terminal with AI CLI integrations, editor context handoff, split panes, and reusable workflows. | TypeScript · Rust · xterm.js |
| [**dvup**](https://github.com/ZyphrZero/dvup) | A cross-platform toolchain updater with a TUI, lock-aware updates, and PATH conflict diagnostics. | Rust |
| [**omdrop-windows**](https://github.com/ZyphrZero/omdrop-windows) | AirDrop between Windows and Apple devices through an ESP32 USB bridge, with a native desktop app, CLI, and firmware. | Rust · GPUI · ESP32 |
| [**LingYaoKeys**](https://github.com/ZyphrZero/LingYaoKeys) | A Windows keyboard automation tool with configurable hotkeys and a native desktop interface. | C# · .NET · WPF |
| [**Smart Workflow**](https://github.com/ZyphrZero/obsidian-smart-workflow) | AI-assisted note naming, voice input, translation, and writing inside Obsidian. | TypeScript |
| [**playwright-python**](https://github.com/ZyphrZero/playwright-python) | Web UI test automation with reusable test workflows and reports. | Python · Playwright · pytest · Allure |

I also extend existing open-source projects. My [**kiro.rs**](https://github.com/ZyphrZero/kiro.rs) work builds on [hank9999/kiro.rs](https://github.com/hank9999/kiro.rs) and explores API compatibility, tool-call handling, failover, and request tracing. [**pytest-api-auto**](https://github.com/ZyphrZero/pytest-api-auto) is my adaptation of [pytest-auto-api2](https://gitee.com/yu_xiao_qi/pytest-auto-api2) for API testing.

## Tools I work with

- **Languages:** Rust · Python · TypeScript / JavaScript · C# · Go
- **Testing:** pytest · Playwright · Selenium · Allure
- **Applications:** React · Tauri · WPF · FastAPI
- **Delivery:** GitHub Actions · Docker

## Around the community

You can find me on **[LINUX DO as Cassianvale / 长秋](https://linux.do/u/cassianvale/summary)**, where I share practical notes and discuss AI coding tools, automation, deployment, and desktop development.

A few things I've shared there, in Chinese:

- [Remote AI coding with HAPI + Cloudflare Tunnel](https://linux.do/t/topic/2288037) — deployment notes and lessons from using the setup.
- [An English AGENTS.md contribution](https://linux.do/t/topic/940740/64) — instructions for agent collaboration, analysis, and review.
- [Automating Tieba check-ins with GitHub Actions](https://linux.do/t/topic/263044) — a community project adaptation and the improvements behind it.

Always happy to compare notes on agent harnesses, test tooling, and useful developer tools.

<details>
<summary><strong>GitHub activity</strong></summary>

<br />

<p align="center">
  <img
    height="165"
    src="https://github-readme-stats-eight-psi-43.vercel.app/api?username=ZyphrZero&amp;show_icons=true&amp;locale=en&amp;line_height=21&amp;theme=tokyonight&amp;cache_seconds=86400&amp;v=1"
    alt="ZyphrZero's GitHub activity statistics"
  />
  <img
    height="165"
    src="https://github-readme-stats-eight-psi-43.vercel.app/api/top-langs?username=ZyphrZero&amp;locale=en&amp;layout=compact&amp;theme=tokyonight&amp;langs_count=8&amp;cache_seconds=259200&amp;v=1"
    alt="Languages used across ZyphrZero's GitHub repositories"
  />
</p>

</details>
