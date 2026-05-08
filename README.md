<!--
  raya-ac/raya-ac
-->

<h1 align="center">raya</h1>

<p align="center">
  security research, agent memory, origin servers, evidence rooms, native Mac apps, and tools that usually start as "this should exist"
</p>

<p align="center">
  <a href="https://raya.li"><img src="https://img.shields.io/badge/site-raya.li-0a0a0a?style=flat-square" alt="site"></a>
  <a href="https://layerline.dev"><img src="https://img.shields.io/badge/layerline.dev-origin%20server-f7a41d?style=flat-square&labelColor=111111" alt="layerline"></a>
  <a href="https://verge.report"><img src="https://img.shields.io/badge/verge.report-evidence%20workspace-6d5dfc?style=flat-square&labelColor=111111" alt="verge report"></a>
  <a href="https://memorylayer.run"><img src="https://img.shields.io/badge/memorylayer.run-live-ffffff?style=flat-square&labelColor=111111&color=ffffff" alt="memorylayer"></a>
  <a href="https://engram-memory.dev"><img src="https://img.shields.io/badge/engram-memory.dev-7c4dff?style=flat-square" alt="engram"></a>
  <a href="https://secpulse.tech"><img src="https://img.shields.io/badge/secpulse.tech-live-00c853?style=flat-square" alt="secpulse"></a>
  <a href="https://github.com/raya-ac/kiln"><img src="https://img.shields.io/badge/kiln-mac%20agent%20app-2563eb?style=flat-square" alt="kiln"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/focus-security%20research-111111?style=flat-square" alt="security research">
  <img src="https://img.shields.io/badge/focus-agent%20memory-111111?style=flat-square" alt="agent memory">
  <img src="https://img.shields.io/badge/focus-native%20macOS-111111?style=flat-square" alt="native macOS">
  <img src="https://img.shields.io/badge/focus-origin%20servers-111111?style=flat-square" alt="origin servers">
  <img src="https://img.shields.io/badge/focus-source%20bound%20research-111111?style=flat-square" alt="source-bound research">
</p>

<p align="center">
  I build security tools, memory infrastructure for agents, origin-server software, and Mac apps.
  A lot of it comes from getting annoyed at existing tooling and deciding to make the version I wanted.
</p>

---

## Now

<table>
  <tr>
    <td valign="top" width="50%">

### Shipping

- [Layerline](https://github.com/raya-ac/Layerline) - a Zig origin web server with static serving, PHP/FastCGI, reverse proxying, TLS, HTTP/2, admin controls, and in-tree HTTP/3 work. It serves [layerline.dev](https://layerline.dev).
- [Verge Report](https://verge.report) - source-bound evidence workspace with subdomain surfaces for documents, courts, releases, intake, privacy, media handling, claims, networks, timelines, sources, and review.
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
- Source-bound public research surfaces are becoming their own lane now: more receipts, fewer vibes.

    </td>
  </tr>
</table>

---

## Projects

| project | what it is | status |
|---------|------------|--------|
| [Layerline](https://github.com/raya-ac/Layerline) | Zig origin web server for static sites, PHP/FastCGI, reverse proxying, TLS, admin controls, HTTP/2, and in-tree HTTP/3 work. | serves [layerline.dev](https://layerline.dev) |
| [Verge Report](https://verge.report) | Evidence workspace and dossier site with canonical subdomains for document families, court records, releases, source intake, review lanes, claims, networks, timelines, and public data contracts. | live |
| [Verge](https://github.com/raya-ac/verge.raya.ac) | Shared chamber and public evidence workspace. The Port Pirie surface is a source-bound network index with claim threads, receipts, source registers, map context, and an audit trail. | live at [verge.raya.ac](https://verge.raya.ac) |
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

## GitHub Snapshot

```text
visible repos counted  45
owned non-fork repos   39
source lines           773,425  non-fork
source lines           8,629,270 including forks
largest own repo       raya-monitor
large forks            wine, Proton
```

The fork-inclusive number is mostly upstream Wine and Proton. The non-fork number is the one I would use when talking about my own projects.

---

## What I Work With

```text
languages      python  html/css  typescript  javascript  swift  go  zig  rust  bash
apple          swiftui  appkit  app sandbox  xpc  metal  xcode
security       burp  nuclei  custom scanners  disclosure workflows  source registers
agents         mcp  retrieval  embeddings  memory systems  local models
infra          postgres  docker  cloudflare  tailscale  vps  layerline  nginx/caddy
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
- Evidence work keeps teaching me that the boring part matters: source boundaries, repeatable builds, and public data that can be checked.
- I prefer shipping something real, then sanding down the rough edges in public.

---

## Current Focus

- Making Layerline good enough to keep replacing the boring parts of my edge stack.
- Expanding Verge Report without letting it become a pile of screenshots and claims nobody can audit.
- Making Memorylayer feel like a real hosted memory service for agents.
- Keeping Engram useful locally and hosted, without turning it into a fake SaaS abstraction.
- Turning Kiln into the Mac app I want for Claude, Codex, and whatever agent CLI comes next.
- Building SecPulse into a cleaner disclosure workflow with useful security tooling around it.
- Continuing Apple security research as accepted reports move through seasonal tagging.

---

<p align="center">
  <a href="https://raya.li">site</a> ·
  <a href="https://layerline.dev">layerline</a> ·
  <a href="https://verge.report">verge report</a> ·
  <a href="https://memorylayer.run">memorylayer</a> ·
  <a href="https://engram-memory.dev">engram</a> ·
  <a href="https://secpulse.tech">secpulse</a> ·
  <a href="https://github.com/raya-ac/kiln">kiln</a>
</p>

<p align="center">
  <sub>Ask me about macOS internals, sandboxing, agent memory, or why I keep starting infrastructure projects at 2am.</sub>
</p>
