<div align="center">

# raya

i build things because the version i want usually doesn't exist yet.

[site](https://raya.li) · [zigcho](https://github.com/zigcho) · [junkstep](https://junkstep.com) · [engram](https://engram-memory.dev)

</div>

---

most of my time goes into games, native mac apps, agent memory and the infrastructure underneath them. i like being able to follow a problem all the way down instead of finding another service i have to work around.

[zigcho](https://github.com/zigcho) is the main rabbit hole. what started as an osu! server in Zig now has Stable and lazer, a website, multiplayer, a beatmap mirror and its own private anticheat. the server, client patch and protocol harness have their own repos under the org now. [kai.ovh](https://kai.ovh) is where it runs.

## what i'm building

| project | what it does |
| --- | --- |
| [zigcho](https://github.com/zigcho/zigcho) | the osu! backend and website. shared accounts and stats, separate client scoring, chat, rooms, replays, teams and staff tools. |
| [zigcho!lazer](https://github.com/zigcho/zigcho-lazer) | the pinned osu! client patch and portable builds. the client side has its own home instead of living inside the server repo. |
| [Layerline](https://github.com/raya-ac/Layerline) | my Zig web server. virtual hosts, reverse proxying, FastCGI, TLS and the private ingress used by zigcho. |
| [kiln](https://github.com/raya-ac/kiln) | a native macOS app for working with agent CLIs. SwiftUI, Swift 6, Apple Silicon and Intel. |
| [engram](https://github.com/raya-ac/engram) | persistent memory for agents. hybrid retrieval, a graph and MCP tools so the next session doesn't start from nothing. |
| [mythic](https://github.com/raya-ac/mythic) | the cognition runtime around engram: activation, reflection, checkpoints and plugins. |
| [model-o-control](https://github.com/raya-ac/model-o-control) | native macOS controls for the original wired Glorious Model O. |
| [Junkstep](https://junkstep.com) | a C++ rhythm battle game with online play and replays. another game that grew a backend. |

## the zigcho bit

Stable and lazer use the same local kai account. their scores keep the values and replay format they actually submitted; combined stats use comparable legacy scoring and the highest-PP play per map. vanilla, Relax and Autopilot stay separate.

Cloudflare handles public DNS and HTTPS, Layerline carries the traffic to the private origin, and zigcho handles the game itself. PostgreSQL holds the account and game state. S3-compatible storage holds the large stuff: map sets, replays, avatars and backups.

i keep the [Stable conformance harness](https://github.com/zigcho/stable-conformance) separate so it checks the server from outside. the anticheat module is private and permission-only. the public server exposes its integration boundary, not its detection rules.

the [org profile](https://github.com/zigcho) has the full layout. new zigcho-specific work goes there.

## other things here

| project | what it is |
| --- | --- |
| [dns-proxy](https://github.com/raya-ac/dns-proxy) | route selected domains through alternative exit nodes without moving all traffic. |
| [engram-cloud](https://github.com/raya-ac/engram-cloud) | the hosted layer around engram. |
| [verge](https://github.com/raya-ac/verge.raya.ac) | evidence rooms, source registers and claim threads. |
| [ember-cpu](https://github.com/raya-ac/ember-cpu) | a 32-bit CPU, assembler, C compiler and JIT. then i put DOOM on it. |
| [eero-mac](https://github.com/raya-ac/eero-mac) | a native mac app for eero networks. |
| [intellidash](https://github.com/raya-ac/intellidash) | a native dashboard for live feeds, maps, flight tracking and local analysis. |
| [adelaide-metro-tracking](https://github.com/raya-ac/adelaide-metro-tracking) | live public transport tracking. |

there's private work too: Warden for remote control, Valhalla for software distribution, and macOS security research. those get published when there's something i actually want to put out, not to fill a contribution graph.

## how i work

mostly Zig, Swift, C++, Rust, Python and TypeScript, depending on what i'm building. native apps when they make sense. a website when people need to reach it without installing anything.

i want the actual flow to work. a green build doesn't tell me whether someone can finish a multiplayer room or download their replay. i keep the rough edges visible, save enough context to resume the work, and try not to make the next fix harder than it needs to be.

read the licence in each repo before using it. public source doesn't mean everything here has the same terms.
