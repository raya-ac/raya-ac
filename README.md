<!--
  raya-ac/raya-ac
-->

<h1 align="center">raya</h1>

<p align="center">
  building security tools, native Mac software, and agent infrastructure
</p>

<p align="center">
  <a href="https://raya.li"><img src="https://img.shields.io/badge/site-raya.li-0a0a0a?style=flat-square" alt="site"></a>
  <a href="https://engram-memory.dev"><img src="https://img.shields.io/badge/engram-memory.dev-7c4dff?style=flat-square" alt="engram"></a>
  <a href="https://secpulse.tech"><img src="https://img.shields.io/badge/secpulse.tech-live-00c853?style=flat-square" alt="secpulse"></a>
  <a href="https://github.com/raya-ac/kiln"><img src="https://img.shields.io/badge/kiln-agent%20cli%20app-2563eb?style=flat-square" alt="kiln"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/focus-security%20research-111111?style=flat-square" alt="security research">
  <img src="https://img.shields.io/badge/focus-native%20macOS-111111?style=flat-square" alt="native macOS">
  <img src="https://img.shields.io/badge/focus-agent%20memory-111111?style=flat-square" alt="agent memory">
  <img src="https://img.shields.io/badge/focus-infrastructure-111111?style=flat-square" alt="infrastructure">
</p>

<p align="center">
  Most of what I build sits somewhere between security research, agent systems, and Mac apps.
  I like tools that feel native, do real work, and don't need a paragraph of excuses.
</p>

---

## At a Glance

<table>
  <tr>
    <td valign="top" width="50%">

### Current Work

- shipping [Engram](https://github.com/raya-ac/engram), a memory system for AI agents
- pushing [Kiln](https://github.com/raya-ac/kiln) further into a real multi-provider Mac app
- shaping [SecPulse](https://github.com/raya-ac/secpulse) into a stronger disclosure platform
- building [Warden](https://github.com/raya-ac/warden) and [Payphone Territory](https://github.com/raya-ac/payphone-territory) in parallel
- still defaulting to native macOS apps whenever I can get away with it

    </td>
    <td valign="top" width="50%">

### Security Snapshot

- 26 reports across Apple SRDP, HackerOne, Bugcrowd, and direct disclosure
- multiple Apple Security Research reports accepted
- Spring 2026-tagged Apple work currently in the queue
- usual focus: CORS, sandbox escape, authz failures, and client-side bugs

    </td>
  </tr>
</table>

---

## Selected Projects

| project | what it is | stack |
|---------|------------|-------|
| [engram](https://github.com/raya-ac/engram) | Memory system for AI agents. Hybrid retrieval, MCP tooling, docs, and benchmarks. Currently at `98.1%` R@5 on LongMemEval. | python, sqlite, hnswlib, fastapi |
| [kiln](https://github.com/raya-ac/kiln) | Native macOS app for agent CLIs like Claude Code and Codex. Local editor, approvals, session management, remote control, and release tooling. | swift, swiftui, sparkle |
| [SecPulse](https://github.com/raya-ac/secpulse) | Responsible disclosure platform for leaked secrets. This is also where the `keyleak` checking and triage work lands. | python, web |
| [warden](https://github.com/raya-ac/warden) | End-to-end remote control stack over Tailscale, with agent, CLI, web UI, and native Mac app pieces. | swift, python, web |
| [payphone-territory](https://github.com/raya-ac/payphone-territory) | Messaging and communications infrastructure. Very Twilio-shaped right now. | python, twilio |
| [eero-mac](https://github.com/raya-ac/eero-mac) | Native macOS app for managing eero WiFi networks. | swift, swiftui |
| [ember-cpu](https://github.com/raya-ac/ember-cpu) | 32-bit CPU from scratch with assembler, C compiler, JIT, and DOOM. | systems, compilers |
| [intellidash](https://github.com/raya-ac/intellidash) | Native dashboard with live feeds, local AI analysis, and a lot of scope. | python, swiftui |
| [sigint](https://github.com/raya-ac/sigint) | Monitoring and situational-awareness tooling. | python, data |

---

## What I Work On

```text
languages      swift  python  javascript  c++  metal  go  bash
security       secpulse  ashforge  secprobe  burp  nuclei  custom tooling
apple          swiftui  appkit  app sandbox  metal gpu  xcode
ai/ml          embeddings  hnswlib  retrieval  mcp  local models
infra          docker  nginx  cloudflare  tailscale  bare metal
```

---

## Working Style

- I prefer native software over web wrappers.
- I build tools I want to use myself, then keep pushing until they stop being annoying.
- A lot of my work starts in security or infrastructure and drifts into agent systems.
- I like ambitious projects, but I still want them to feel usable on day one.

---

## Security Research

```text
26 reports across apple srdp, h1, bugcrowd, and direct disclosure
multiple Apple Security Research reports accepted
Spring 2026-tagged Apple work in progress
targets include apple, netflix, coinbase, stripe, monzo, twilio, grab, and atlassian
tools built along the way: ashforge, secprobe, secpulse, bountytoolkit
```

---

## Right Now

- Engram is shipped, documented, and live on PyPI
- Kiln just got Codex support and is turning into a serious desktop front-end for agent CLIs
- SecPulse is live, but still getting sharper
- Warden and Payphone Territory are both active
- Apple research work is moving through acceptance and seasonal tagging

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
