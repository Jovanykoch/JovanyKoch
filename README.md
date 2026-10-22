<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=160&section=header&text=Jovany%20Koch&fontSize=40&animation=fadeIn&fontAlignY=35" width="100%" alt="Jovany Koch" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2F81F7&center=true&vCenter=true&width=600&lines=Student+%7C+Self-hosted+network+tooling;Building+Surge+%2F+mihomo+rule+sets+for+China+routing;Daily-built+rules+for+Surge%2C+Clash%2C+Quantumult+X%2C+sing-box" alt="Typing SVG" />

<br />

<img src="https://komarev.com/ghpvc/?username=Jovanykoch&style=flat-square&color=blue" alt="Profile views" />
<a href="https://github.com/Jovanykoch?tab=followers"><img src="https://img.shields.io/github/followers/Jovanykoch?style=flat-square&label=Followers" alt="Followers" /></a>

</div>

## About

- 🎓 Student at Joliet Junior College
- 🎯 Focusing on self-hosted **Surge / mihomo** rule sets for China routing
- 🛠️ I build and maintain my own network tooling supply chain — rule data is rebuilt daily by CI from upstream sources, cleaned, converted, and republished in the formats each client actually consumes. Nothing depends on anyone else's rule service.

## Featured project

### [Jovanykoch/rules](https://github.com/Jovanykoch/rules)

<a href="https://github.com/Jovanykoch/rules"><img src="https://img.shields.io/github/stars/Jovanykoch/rules?style=flat-square" alt="rules stars" /></a>
<img src="https://img.shields.io/badge/build-daily%2000%3A00%20UTC-blue?style=flat-square" alt="Daily build" />
<img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="MIT license" />

An automated rule-generation repository for proxy and network tools. It fetches upstream data (v2fly `domain-list-community`, GFWList, hagezi, Loyalsoldier, felixonmars), parses and cleans it, and publishes unified outputs for **Surge, Clash, Quantumult X, sing-box, and V2Ray GeoSite** on the `rel` branch.

| Tag | What it is |
| --- | --- |
| `china` | Mainland-China domains — v2fly `cn` merged with dnsmasq-china-list (~110k) |
| `ads` / `ads-mini` | Ad & tracker blocklists — hagezi Multi PRO (~230k) / PRO mini (~60k) |
| `apple` / `apple-lite` | Apple services — full set (~1.6k) / hand-maintained light set (33, built for Loon) |
| `douyin` | Douyin service domains, incl. snssdk / pstatp / byteimg |
| `ai` | Non-mainland-China AI services (OpenAI, Anthropic, Gemini, …) |
| `school` | School & education services (hand-maintained) |
| `gfw` / `reject` / `loc-cn` | GFWList proxy rules, block rules, China direct rules |

```text
# Surge example
DOMAIN-SET,https://github.com/Jovanykoch/rules/raw/rel/china.list,DIRECT
```

It also ships a self-built China-only GeoIP MMDB generator (`tools/mmdb/`, from Loyalsoldier `cn.txt`) — no third-party MMDB dependency.

**Consumer side:** [us-kg/surge](https://github.com/us-kg/surge) — a complete, ready-to-use Surge setup (profile, modules, rule index) maintained under my second account, wired directly to the daily builds above.

## Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,go,git,githubactions,cloudflare,linux" alt="Python, Go, Git, GitHub Actions, Cloudflare, Linux" />

</div>

## GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Jovanykoch&show_icons=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jovanykoch&layout=compact" alt="Top languages" />

<br />

<img src="https://streak-stats.demolab.com?user=Jovanykoch" alt="GitHub streak" />

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=100&section=footer" width="100%" alt="" />
