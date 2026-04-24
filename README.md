<!--
  raya-ac/raya-ac
-->

<h1 align="center">raya</h1>

<p align="center">
  security research, agent memory, native Mac apps, and tools that usually start as "this should exist"
</p>

<p align="center">
  <a href="https://raya.li"><img src="https://img.shields.io/badge/site-raya.li-0a0a0a?style=flat-square" alt="site"></a>
  <a href="https://memorylayer.run"><img src="https://img.shields.io/badge/memorylayer.run-live-ffffff?style=flat-square&labelColor=111111&color=ffffff" alt="memorylayer"></a>
  <a href="https://engram-memory.dev"><img src="https://img.shields.io/badge/engram-memory.dev-7c4dff?style=flat-square" alt="engram"></a>
  <a href="https://secpulse.tech"><img src="https://img.shields.io/badge/secpulse.tech-live-00c853?style=flat-square" alt="secpulse"></a>
  <a href="https://github.com/raya-ac/kiln"><img src="https://img.shields.io/badge/kiln-mac%20agent%20app-2563eb?style=flat-square" alt="kiln"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/focus-security%20research-111111?style=flat-square" alt="security research">
  <img src="https://img.shields.io/badge/focus-agent%20memory-111111?style=flat-square" alt="agent memory">
  <img src="https://img.shields.io/badge/focus-native%20macOS-111111?style=flat-square" alt="native macOS">
  <img src="https://img.shields.io/badge/focus-security%20tools-111111?style=flat-square" alt="security tools">
</p>

<p align="center">
  I build security tools, memory infrastructure for agents, and Mac software.
  A lot of it comes from getting annoyed at existing tooling and deciding to make the version I wanted.
</p>

---

## Now

<table>
  <tr>
    <td valign="top" width="50%">

### Shipping

- [Memorylayer](https://memorylayer.run) - hosted Engram workspaces, GitHub login, API keys, ingestion, usage tracking, and a small MCP-style bridge.
- [Engram](https://github.com/raya-ac/engram) - persistent memory for agents, with retrieval, graph context, MCP tools, and PyPI releases.
- [Kiln](https://github.com/raya-ac/kiln) - a native macOS front-end for agent CLIs, now with Claude and Codex support.
- [SecPulse](https://secpulse.tech) - responsible disclosure and secret triage tooling. SecPulse and Keyleak are the same line of work now.

    </td>
    <td valign="top" width="50%">

### Security Research

- Apple Security Research reports accepted.
- Apple work tagged for Spring 2026.
- 26 reports across Apple SRDP, HackerOne, Bugcrowd, and direct disclosure.
- Usual rabbit holes: CORS, authz, sandboxing, client-side bugs, exposed secrets, and weird platform behavior.

    </td>
  </tr>
</table>

---

## Projects

| project | what it is | status |
|---------|------------|--------|
| [Memorylayer](https://github.com/raya-ac/engram-cloud) | Hosted service layer for Engram: workspaces, API keys, ingestion, usage logs, starter skills, and a dashboard. | live at [memorylayer.run](https://memorylayer.run) |
| [Engram](https://github.com/raya-ac/engram) | Memory system for agents. Hybrid retrieval, MCP tooling, graph context, docs, and benchmarks. | active |
| [Kiln](https://github.com/raya-ac/kiln) | Native macOS app for agent CLIs like Claude Code and Codex. Local files, chat, approvals, sessions, model controls, and release tooling. | active |
| [SecPulse](https://github.com/raya-ac/secpulse) | Responsible disclosure platform and secret triage stack. This is where Keyleak work lands now. | live |
| [Warden](https://github.com/raya-ac/warden) | Remote control stack over Tailscale, with agent, CLI, web UI, and Mac app pieces. | active |
| [payphone-territory](https://github.com/raya-ac/payphone-territory) | Messaging and communications infrastructure. Twilio-shaped, but getting broader. | active |
| [sigint](https://github.com/raya-ac/sigint) | Monitoring and situational-awareness tooling, plus a few jokes that probably went too far. | active |
| [eero-mac](https://github.com/raya-ac/eero-mac) | Native macOS app for managing eero WiFi networks. | active |
| [ember-cpu](https://github.com/raya-ac/ember-cpu) | 32-bit CPU from scratch with assembler, C compiler, JIT, and DOOM. | systems project |

---

## What I Work With

```text
languages      swift  python  javascript  c++  metal  go  bash
apple          swiftui  appkit  app sandbox  xpc  metal  xcode
security       burp  nuclei  custom scanners  disclosure workflows
agents         mcp  retrieval  embeddings  memory systems  local models
infra          postgres  docker  cloudflare  tailscale  vps  nginx/caddy
```

---

## Security Work

```text
accepted Apple Security Research reports
Spring 2026-tagged Apple reports
26 total reports across Apple SRDP, HackerOne, Bugcrowd, and direct disclosure
targets include Apple, Netflix, Coinbase, Stripe, Monzo, Twilio, Grab, and Atlassian
tools built along the way: SecPulse, Keyleak, ashforge, secprobe, bountytoolkit
```

---

## Working Style

- I like native apps when they make sense. Web wrappers usually annoy me.
- I care about tools feeling fast, direct, and a little overbuilt in the right places.
- Security research keeps pulling me into infrastructure. Agent work keeps pulling me back into memory and retrieval.
- I prefer shipping something real, then sanding down the rough edges in public.

---

## Current Focus

- Making Memorylayer feel like a real hosted memory service for agents.
- Keeping Engram useful locally and hosted, without turning it into a fake SaaS abstraction.
- Turning Kiln into the Mac app I want for Claude, Codex, and whatever agent CLI comes next.
- Building SecPulse into a cleaner disclosure workflow with useful security tooling around it.
- Continuing Apple security research as accepted reports move through seasonal tagging.

---

<p align="center">
  <a href="https://raya.li">site</a> ·
  <a href="https://memorylayer.run">memorylayer</a> ·
  <a href="https://engram-memory.dev">engram</a> ·
  <a href="https://secpulse.tech">secpulse</a> ·
  <a href="https://github.com/raya-ac/kiln">kiln</a>
</p>

<p align="center">
  <sub>Ask me about macOS internals, sandboxing, agent memory, or why I keep starting infrastructure projects at 2am.</sub>
</p>
