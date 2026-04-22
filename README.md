<!--
  raya-ac/raya-ac
-->

<h1 align="center">building security tools, native Mac software, and agent infrastructure</h1>

<p align="center">
  <a href="https://raya.li"><img src="https://img.shields.io/badge/site-raya.li-0a0a0a?style=flat-square" alt="site"></a>
  <a href="https://engram-memory.dev"><img src="https://img.shields.io/badge/engram-memory.dev-7c4dff?style=flat-square" alt="engram"></a>
  <a href="https://secpulse.tech"><img src="https://img.shields.io/badge/secpulse.tech-live-00c853?style=flat-square" alt="secpulse"></a>
  <a href="https://github.com/raya-ac/kiln"><img src="https://img.shields.io/badge/kiln-agent%20cli%20app-2563eb?style=flat-square" alt="kiln"></a>
</p>

<p align="center">
  Security research, agent memory systems, and Mac apps are the center of gravity.
  Most of my recent work lives somewhere between those three.
</p>

---

## Current Focus

| project | what I'm doing with it |
|---------|------------------------|
| [engram](https://github.com/raya-ac/engram) | Memory system for AI agents. Hybrid retrieval, MCP tooling, docs, and benchmarks. Currently at `98.1%` R@5 on LongMemEval. |
| [kiln](https://github.com/raya-ac/kiln) | Native macOS app for agent CLIs like Claude Code and Codex. I’m actively pushing on provider support, UX, and release tooling. |
| [SecPulse](https://github.com/raya-ac/secpulse) | Responsible disclosure platform for leaked secrets. This is also where the `keyleak` checking and triage work lands. |
| [warden](https://github.com/raya-ac/warden) | End-to-end remote control stack over Tailscale, with agent, CLI, web UI, and native Mac app pieces. |
| [payphone-territory](https://github.com/raya-ac/payphone-territory) | Messaging and comms infrastructure. Very Twilio-shaped at the moment. |
| [eero-mac](https://github.com/raya-ac/eero-mac) | Native macOS app for managing eero networks. |

## Other Ongoing Projects

| project | note |
|---------|------|
| [ember-cpu](https://github.com/raya-ac/ember-cpu) | 32-bit CPU project with assembler, C compiler, JIT, and DOOM. |
| [intellidash](https://github.com/raya-ac/intellidash) | Native dashboard with a lot of live feeds and local AI analysis. |
| [sigint](https://github.com/raya-ac/sigint) | Monitoring and situational-awareness tooling. |

---

## Stack

```text
languages      swift  python  javascript  c++  metal  go  bash
security       ashforge  secprobe  secpulse  burp  nuclei  custom tooling
apple          swiftui  appkit  app sandbox  metal gpu  xcode
ai/ml          embeddings  hnswlib  retrieval  mcp  local models
infra          docker  nginx  cloudflare  tailscale  bare metal
```

---

## Working Style

- I like native software more than web wrappers.
- I build tools I want to use myself, then keep pushing until they stop being annoying.
- A lot of my work starts in security or infra and ends up drifting into agent systems.

---

## Security Research

```text
26 reports across apple srdp, h1, bugcrowd, and direct disclosure
targets include apple, netflix, coinbase, stripe, monzo, twilio, grab, and atlassian
usual focus: cors, sandbox escape, authz failures, client-side issues
tools built along the way: ashforge, secprobe, secpulse, bountytoolkit
```

---

## Right Now

- shipping Engram
- pushing Kiln toward better multi-provider support
- shaping SecPulse into something more useful and less vague
- building Warden and Payphone Territory in parallel
- still doing Apple SRDP work
- still choosing native Mac apps whenever I can get away with it

---

<p align="center">
  <a href="https://raya.li">site</a> ·
  <a href="https://engram-memory.dev">engram</a> ·
  <a href="https://secpulse.tech">secpulse</a> ·
  <a href="https://github.com/raya-ac/kiln">kiln</a>
</p>

<p align="center">
  <sub>Ask me about macOS internals, sandbox escapes, Metal compute, or memory systems for agents.</sub>
</p>
