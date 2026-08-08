<!--
  raya-ac/raya-ac
-->

<h1 align="center">raya</h1>

<p align="center">
  i build things because the version i want usually doesn't exist yet.
</p>

<p align="center">
  <a href="https://raya.li"><img src="https://img.shields.io/badge/site-raya.li-0a0a0a?style=flat-square" alt="site"></a>
  <a href="https://junkstep.com"><img src="https://img.shields.io/badge/junkstep-rhythm%20battle-ff4d8d?style=flat-square&labelColor=111111" alt="junkstep"></a>
  <a href="https://github.com/raya-ac/kiln"><img src="https://img.shields.io/badge/kiln-native%20mac%20agents-2563eb?style=flat-square&labelColor=111111" alt="kiln"></a>
  <a href="https://github.com/raya-ac/Layerline"><img src="https://img.shields.io/badge/layerline-zig%20origin%20server-f7a41d?style=flat-square&labelColor=111111" alt="layerline"></a>
  <a href="https://github.com/raya-ac/mythic"><img src="https://img.shields.io/badge/mythic-cognition%20runtime-9f7aea?style=flat-square&labelColor=111111" alt="mythic"></a>
  <a href="https://engram-memory.dev"><img src="https://img.shields.io/badge/engram-memory%20for%20agents-7c4dff?style=flat-square&labelColor=111111" alt="engram"></a>
  <a href="https://verge.raya.ac"><img src="https://img.shields.io/badge/verge-evidence%20rooms-6d5dfc?style=flat-square&labelColor=111111" alt="verge"></a>
</p>

---

the work moves between macOS internals, agent memory, security research, origin servers, and games that keep turning into systems projects. i don't really separate these — they feed each other. the security work becomes infrastructure, the agent work keeps coming back to memory, and the games keep growing backends they don't need.

right now i'm pushing [Layerline](https://github.com/raya-ac/Layerline) toward something i'd trust in front of real sites, building [Junkstep](https://junkstep.com) — a rhythm battle game in early alpha — and growing [Valhalla](#valhalla) into a real distribution platform.

---

## what's public

| project | what it is |
|---------|-----------|
| [Layerline](https://github.com/raya-ac/Layerline) | zig origin server. vhosts, fastcgi, reverse proxy, TLS, HTTP/2 stable, HTTP/3 in tree. the edge stack i want to own end to end. |
| [engram](https://github.com/raya-ac/engram) | agent memory system. hybrid retrieval — HNSW, BM25, graph, cross-encoder, learned reranker. 98.1% R@5 on LongMemEval. |
| [mythic](https://github.com/raya-ac/mythic) | cognition runtime above engram. activation cycles, reflection, checkpoints, plugins. not another wrapper — the layer that makes memory feel alive. |
| [kiln](https://github.com/raya-ac/kiln) | native mac app for agent CLIs. the thing i wished existed, so i built it. swiftui, swift 6. |
| [dns-proxy](https://github.com/raya-ac/dns-proxy) | DNS-based web proxy. route specific domains through exit nodes, bypass geo blocks without touching everything else. docker-deployed. |
| [engram-cloud](https://github.com/raya-ac/engram-cloud) | hosted layer around engram. workspaces, api keys, ingestion. |
| [verge.raya.ac](https://github.com/raya-ac/verge.raya.ac) | evidence work. source registers, claim threads, receipts. structured accountability instead of screenshots. |

---

## Valhalla

a platform for licensing and distributing software. auth, invites, crypto payments, HWID binding, key management — the full stack for selling and gating a product without handing the whole thing to stripe and a licensing SaaS.

it started as a backend for one product and turned into something general. the architecture is clean enough now that i'm starting to trust it with real products, not just prototypes.

**running on it:** CS2 (external assistance platform). more coming.

not public yet. getting there.

---

## also active, less visible

| work | shape |
|------|-------|
| [Junkstep](https://junkstep.com) | C++20/raylib rhythm battle. alpha — signed apple silicon builds, online play, replays, bot battle. still getting sanded down. |
| Aurora / SRDPKit | local-first macos security workbench. baseline diffs, IOKit research, safe tool registry. risky probes stay gated. |
| Dawnline OS | arch-based os scaffold for agent workstations. archiso, rootfs, containerized builder. |
| SecPulse / Keyleak | disclosure tooling, leaked-secret triage, source handling. |
| Warden | remote control over tailscale. agent, CLI, web, native mac. |
| Apple security research | accepted reports, SRDP tagging, baselines. the boring parts are the point. |

---

## older work

| project | notes |
|---------|-------|
| [ember-cpu](https://github.com/raya-ac/ember-cpu) | 32-bit CPU from scratch. assembler, C compiler, JIT, and then i ported DOOM to it. |
| [eero-mac](https://github.com/raya-ac/eero-mac) | native mac app for eero networks. |
| [intellidash](https://github.com/raya-ac/intellidash) | intelligence dashboard. 200+ live feeds, local analyst, flight tracking. |
| [epstein-archive](https://github.com/raya-ac/epstein-archive) | document archive, full-text search. 100k+ docs indexed. |
| [adelaide-metro-tracking](https://github.com/raya-ac/adelaide-metro-tracking) | real-time transit tracking for adelaide. |
| [neuro-memory](https://github.com/raya-ac/neuro-memory) | older memory system. what came before engram. |
| [Proton](https://github.com/raya-ac/Proton) / [wine](https://github.com/raya-ac/wine) | ARM64 port spike. real port work, not a magic compatibility layer. |

---

## snapshot

```text
public repos     27 (21 non-fork)
public source    ~255k lines (linguist estimate, private work not counted)
most active      Layerline, Junkstep, kiln, engram
private active   Valhalla, CS2, Aurora/SRDPKit, Dawnline OS, SecPulse, Warden
```

i don't count lines as a vanity metric. linguist skips lockfiles, vendored deps, generated code, binaries. private work isn't in that number.

---

## how i work

native apps when they make sense. web when it earns it. tools should be fast, direct, and slightly overbuilt in the places that save time later. i'd rather ship something rough and real than polish a fake demo.

security research keeps turning into infrastructure. agent work keeps turning back to memory. if a system can't be resumed by another session, it probably isn't done yet.

---

## stack

```text
languages   swift  python  zig  c++  typescript  javascript  go  rust  bash
apple       swiftui  appkit  xpc  sandbox  tcc  iokit  metal
agents      mcp  embeddings  retrieval  memory systems  event streams  local models
security    burp  nuclei  custom scanners  source registers  disclosure
infra       postgres  docker  cloudflare  tailscale  layerline  nginx  dns
payments    crypto  hwid licensing  invites  key management
games       raylib  realtime input  chart importers  replays  multiplayer
```

---

## security

accepted apple security research reports. SRDP work under tagging. reports across apple, hackerone, bugcrowd, and direct disclosure. the usual holes — CORS, authz, sandboxing, exposed secrets, client-side trust, platform weirdness.

i care less about making this sound impressive than making it checkable. source boundaries, exact repro steps, local baselines, saved artifacts. knowing when not to run the dangerous thing.

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
  <sub>macOS internals, sandboxing, agent memory, origin servers, DNS — or why a rhythm game needs this much backend.</sub>
</p>
