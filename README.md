<!--
  raya-ac/raya-ac
-->

<h1 align="center">raya</h1>

<p align="center">
  security research, native Mac software, agent memory, local infra, and games that keep turning into systems projects
</p>

<p align="center">
  <a href="https://raya.li"><img src="https://img.shields.io/badge/site-raya.li-0a0a0a?style=flat-square" alt="site"></a>
  <a href="https://junkstep.com"><img src="https://img.shields.io/badge/junkstep-current%20active%20game-ff4d8d?style=flat-square&labelColor=111111" alt="junkstep"></a>
  <a href="https://github.com/raya-ac/kiln"><img src="https://img.shields.io/badge/kiln-native%20mac%20agents-2563eb?style=flat-square&labelColor=111111" alt="kiln"></a>
  <a href="https://github.com/raya-ac/Layerline"><img src="https://img.shields.io/badge/layerline-zig%20origin%20server-f7a41d?style=flat-square&labelColor=111111" alt="layerline"></a>
  <a href="https://github.com/raya-ac/mythic"><img src="https://img.shields.io/badge/mythic-cognition%20runtime-9f7aea?style=flat-square&labelColor=111111" alt="mythic"></a>
  <a href="https://engram-memory.dev"><img src="https://img.shields.io/badge/engram-memory%20for%20agents-7c4dff?style=flat-square&labelColor=111111" alt="engram"></a>
  <a href="https://verge.raya.ac"><img src="https://img.shields.io/badge/verge-evidence%20rooms-6d5dfc?style=flat-square&labelColor=111111" alt="verge"></a>
</p>

<p align="center">
  i build tools because the version i want usually does not exist yet.
  the work moves around: macOS internals, agent memory, security research, origin servers, DNS plumbing, and sometimes a rhythm game that accidentally grows a backend.
</p>

---

## now

**most active right now:** [Layerline](https://github.com/raya-ac/Layerline) — Zig origin server. HTTP/2 stable, HTTP/3 work in tree, request tracing, structured logs. the edge stack i keep tightening.

| public work | what it is right now |
|-------------|----------------------|
| [Layerline](https://github.com/raya-ac/Layerline) | Zig origin server with virtual hosts, PHP/FastCGI, reverse proxying, TLS, admin controls, HTTP/2, and HTTP/3 work in tree. this is the part of the edge stack i want to own myself. |
| [engram](https://github.com/raya-ac/engram) | memory system for agents. hybrid retrieval (HNSW + BM25 + graph + cross-encoder + MLP reranker), MCP tools, PyPI releases. 98.1% recall@5 on LongMemEval — current SOTA. |
| [mythic](https://github.com/raya-ac/mythic) | persistent cognition runtime above Engram: memory activation, cognitive cycles, reflection records, event streams, checkpoints, plugins, and resumable session state. |
| [kiln](https://github.com/raya-ac/kiln) | native macOS app for agent CLIs like Claude Code and Codex. SwiftUI, Swift 6, Apple Silicon + Intel, sessions, approvals, local files, model controls. |
| [dns-proxy](https://github.com/raya-ac/dns-proxy) | DNS-based web proxy — route specific domains through alternative exit nodes. bypass geo-restrictions and ISP-level blocks without touching normal traffic. Docker-deployed. |
| [engram-cloud](https://github.com/raya-ac/engram-cloud) | hosted layer around Engram: workspaces, API keys, ingestion, usage tracking, dashboard surfaces, and bridge work. |
| [verge.raya.ac](https://github.com/raya-ac/verge.raya.ac) | public evidence/chamber work. source registers, claim threads, receipts, maps, and audit trails instead of screenshots floating around with no spine. |

---

## active, but not all public

| work | shape |
|------|-------|
| [Junkstep](https://junkstep.com) / [downloads](https://download.junkstep.com) | C++20/raylib rhythm battle game. early alpha, Apple Silicon builds, signed downloads, bot battle, replays, hold notes, junk pressure, online backend, website accounts, rankings, chat. still getting built in real time. |
| Valhalla | platform backend — auth, invites, crypto payments, HWID licensing. software distribution and licensing infrastructure. |
| CS2 | external assistance platform. built on top of Valhalla's licensing stack. |
| Aurora / SRDPKit | local-first macOS security and infosec workbench. Apple baseline diffs, IOKit/SRDP research, safe tool registry, SwiftUI wrapper, Discord RPC, SecPulse/breach tooling, and a hard rule that risky probes stay gated. |
| Dawnline OS | Arch-based agent/workstation OS scaffold. archiso, rootfs targets, package groups, containerized builder flow, and Asahi/aarch64 planning. |
| SecPulse / Keyleak | responsible disclosure, leaked-secret triage, source handling, and operator workflows. some of it is public-facing, some of it stays private until it should not. |
| Warden | remote control stack over Tailscale with agent, CLI, web UI, and native Mac pieces. |
| Apple security research | accepted reports, seasonal tagging/review, local baselines, and tooling for making the reports repeatable instead of just clever. |

---

## older but still mine

| project | notes |
|---------|-------|
| [ember-cpu](https://github.com/raya-ac/ember-cpu) | 32-bit CPU from scratch with assembler, C compiler, JIT, and DOOM. |
| [eero-mac](https://github.com/raya-ac/eero-mac) | native macOS app for managing eero WiFi networks. |
| [intellidash](https://github.com/raya-ac/intellidash) | global intelligence dashboard with live feeds, a local analyst, flight tracking, and native macOS pieces. |
| [epstein-archive](https://github.com/raya-ac/epstein-archive) | large-scale document archive with full-text search. 100k+ documents indexed. |
| [adelaide-metro-tracking](https://github.com/raya-ac/adelaide-metro-tracking) | real-time public transport tracking for Adelaide. |
| [neuro-memory](https://github.com/raya-ac/neuro-memory) | older cognitive memory system. a predecessor to the Engram/Mythic line. |
| [Proton](https://github.com/raya-ac/Proton) / [wine](https://github.com/raya-ac/wine) | macOS ARM64 port spike around Proton/Wine. not a magic compatibility layer, just real port work and notes. |

---

## current public snapshot

```text
public repositories        27
public non-fork repos      21
public source (approx)     ~255k lines
recent public work         Layerline, engram, kiln, dns-proxy, engram-cloud, verge.raya.ac
current most active        Layerline (HTTP/3), Junkstep (alpha)
private/local active work  Valhalla, CS2, Aurora/SRDPKit, Dawnline OS, SecPulse, Warden
```

The line count is a practical estimate from GitHub Linguist byte totals across public non-fork repos, not a vanity metric. Lockfiles, vendored dependencies, generated bundles, binaries, and minified assets are excluded by Linguist. Private/local projects are not rolled into that public number.

---

## what i work with

```text
languages      swift  python  zig  c++  typescript  javascript  go  rust  bash
apple          swiftui  appkit  xpc  app sandbox  tcc  iokit  metal  xcode
agents         mcp  embeddings  retrieval  memory systems  event streams  local models
security       burp  nuclei  custom scanners  source registers  disclosure workflows
infra          postgres  docker  cloudflare  tailscale  layerline  nginx/caddy  dns
payments       crypto  hwid licensing  invite systems  key management
games          raylib  realtime input  chart importers  replays  multiplayer backends
```

---

## security work

```text
accepted Apple Security Research reports
Apple SRDP work under review/tagging
reports across Apple, HackerOne, Bugcrowd, and direct disclosure
usual holes: CORS, authz, sandboxing, exposed secrets, client-side trust, platform weirdness
tools built along the way: Aurora/SRDPKit, SecPulse, Keyleak, ashforge, secprobe, bountytoolkit
```

I care less about making this sound impressive than making it checkable. The boring parts matter: source boundaries, exact repro steps, local baselines, saved artifacts, and knowing when not to run the dangerous thing.

---

## working style

- native apps when they make sense. web when it earns it.
- tools should be fast, direct, and slightly overbuilt in the places that save time later.
- i would rather ship the rough real thing than polish a fake demo.
- security research keeps turning into infrastructure. agent work keeps turning back into memory.
- if a system cannot be resumed by another session, it probably is not done yet.

---

## current focus

- pushing Layerline from "works" toward "i trust it in front of real sites" — HTTP/3, tracing, hardening.
- keeping Engram useful locally while Engram-Cloud and Mythic grow around it.
- making Kiln the Mac app i actually want for agent CLIs.
- finishing Junkstep's early-alpha loop without letting the game feel like backend plumbing.
- building Valhalla into a real distribution and licensing platform.
- turning Aurora/SRDPKit into a real local security workbench, not just a pile of scripts.
- keeping Apple security research grounded in baselines, repeatable probes, and clean reports.

---

<p align="center">
  <a href="https://raya.li">site</a> ·
  <a href="https://junkstep.com">junkstep</a> ·
  <a href="https://github.com/raya-ac/kiln">kiln</a> ·
  <a href="https://github.com/raya-ac/Layerline">layerline</a> ·
  <a href="https://github.com/raya-ac/mythic">mythic</a> ·
  <a href="https://engram-memory.dev">engram</a> ·
  <a href="https://verge.raya.ac">verge</a>
</p>

<p align="center">
  <sub>ask me about macOS internals, sandboxing, agent memory, origin servers, DNS plumbing, or why a rhythm game needs this much backend.</sub>
</p>
