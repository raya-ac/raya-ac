<!--
  raya-ac/raya-ac
  if you're reading this, you know what's up
-->

<h1 align="center">security researcher. tool builder.</h1>

<p align="center">
  <a href="https://raya.li"><img src="https://img.shields.io/badge/site-raya.li-0a0a0a?style=flat-square" alt="site"></a>
  <a href="https://melee.garden"><img src="https://img.shields.io/badge/melee.garden-live-00c853?style=flat-square" alt="melee.garden"></a>
  <a href="https://status.raya.li"><img src="https://img.shields.io/badge/status-99.97%25-00c853?style=flat-square" alt="status"></a>
</p>

<p align="center">
  i build tools. mostly security research and gpu tooling right now, with competitive gaming infra on the side.
</p>

---

<h2>what i'm building</h2>

| project | what it does | stack |
|---------|--------------|-------|
| [AshForge](https://raya.li) | offensive security toolkit with Metal GPU acceleration. hash cracking, fuzzing, cors/jwt/port scanning, subdomain enum. 60 swift files + 9 metal shaders. | swift, metal, swiftui |
| [SecProbe](https://raya.li) | local macOS security scanner. runs 11 probe modules inside a real app sandbox, tags every finding with its actual sandbox status. | swift, app sandbox, tcc |
| [melee.garden](https://melee.garden) | competitive smash bros. melee platform. rankings, match history, community tooling. | live |
| [ModForge](https://raya.li) | generates and builds minecraft mods with ai assistance. cross-platform, mac first. | swift, electron, java |
| [intellidash](https://github.com/raya-ac/intellidash) | 200+ live data feeds, local ai analyst, flight tracker, 26 tools in one native app. | python, swiftui |
| [neuro-memory](https://github.com/raya-ac/neuro-memory) | structured cognitive memory for ai agents. 4 layers. | python, sqlite, neo4j |
| [epstein-archive](https://github.com/raya-ac/epstein-archive) | 100k+ documents, full-text indexed and searchable. | elasticsearch |
| [adelaide-metro-tracking](https://github.com/raya-ac/adelaide-metro-tracking) | live GTFS transit tracker for adelaide. | python, fastapi |

---

<h2>stack</h2>

```
languages      swift  python  javascript  c++  metal  go  bash
security       ashforge  secprobe  burp  nuclei  custom tooling
apple          swiftui  appkit  app sandbox  metal gpu  xcode
infra          docker  nginx  cloudflare  bare metal
ai             claude api  local models  cognitive memory systems
```

---

<h2>security research</h2>

```
26 reports across apple srdp, h1, bugcrowd, and direct disclosure
programs: apple, netflix, coinbase, stripe, monzo, twilio, grab, atlassian
focus: cors, sandbox escape, api authz, client-side
tools built this cycle: ashforge, secprobe, bountytoolkit (13 modules)
```

---

<h2>now</h2>

- apple srdp reports in review, stripe and monzo drafts ready to file
- ashforge v1 shipped last week — gpu hash cracking + full gui + cli
- melee.garden is live
- modforge mac at ~70%, windows started

---

<p align="center">
  <a href="https://raya.li">site</a> –
  <a href="https://melee.garden">melee.garden</a> –
  <a href="https://status.raya.li">status</a>
</p>

<p align="center">
  <sub>ask me about macos internals, sandbox escapes, or metal gpu compute</sub>
</p>
