<div align="center">

<!-- ═══════════════════════════════ HEADER ═══════════════════════════════ -->
<svg width="760" height="170" viewBox="0 0 760 170" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Ghassan Gaidi">
  <defs>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#DC2626"/>
      <stop offset="50%" stop-color="#f0f0f0"/>
      <stop offset="100%" stop-color="#DC2626"/>
    </linearGradient>
    <linearGradient id="ruleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#DC2626" stop-opacity="0"/>
      <stop offset="50%" stop-color="#DC2626" stop-opacity="1"/>
      <stop offset="100%" stop-color="#DC2626" stop-opacity="0"/>
    </linearGradient>
  </defs>

  <text x="380" y="72" text-anchor="middle" font-family="Georgia, 'Times New Roman', serif" font-size="56" font-weight="bold" letter-spacing="6" fill="url(#nameGrad)">GHASSAN GAIDI</text>

  <line x1="120" y1="94" x2="640" y2="94" stroke="url(#ruleGrad)" stroke-width="1.5"/>

  <text x="380" y="124" text-anchor="middle" font-family="'Courier New', monospace" font-size="16" fill="#9ca3af">backend &amp; security engineer</text>
  <text x="380" y="150" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" fill="#6b7280">Rust <tspan fill="#DC2626">·</tspan> Python <tspan fill="#DC2626">·</tspan> TypeScript</text>
</svg>

<p>
  <a href="https://ghassan.dev"><img src="https://img.shields.io/badge/ghassan.dev-DC2626?style=flat-square&logo=googlechrome&logoColor=white" alt="ghassan.dev"></a>
  <a href="mailto:gg2574@proton.me"><img src="https://img.shields.io/badge/email-gg2574%40proton.me-6b7280?style=flat-square&logo=protonmail&logoColor=white" alt="email"></a>
  <img src="https://img.shields.io/badge/location-Bizerte%2C_Tunisia-6b7280?style=flat-square" alt="Bizerte, Tunisia">
  <img src="https://img.shields.io/badge/status-%E2%9A%A1%20open%20to%20remote%20roles-00ff41?style=flat-square" alt="Open to remote roles">
</p>

</div>

---

### About

Final-year ICT student (graduating June 2027) who builds and ships **backend and security software** — in Rust, Python and TypeScript. I care about systems that are correct by construction and verifiable by CI: encrypted protocols with formal models, APIs with real auth and rate limits, and products that actually get deployed. **Multiple verified high-severity vulnerability reports on HackerOne.** Published SDKs for an AI-agent memory API to **npm** and **PyPI**.

---

> ⚡ **Open to remote junior software engineering roles** (backend / security / systems) — available June 2027, open to relocation.


## Featured Work

<table>
<tr>
<td width="33%" valign="top">

### <a href="https://github.com/ghassan-gaidi/Null">Null</a>
<sub>Rust · Cryptography</sub>

**Post-quantum, metadata-resistant terminal messenger.** End-to-end encrypted, serverless, RAM-only — zero forensic residue.

- Hybrid **post-quantum handshake**, formally modeled in **Tamarin** and verified in CI
- **124 automated tests** + fuzzing, known-answer vectors, reproducible builds
- Ongoing PQ rekeying in a triple ratchet · deniable by default
- Multi-transport (Tor / I2P) · `clippy -D warnings` clean

[![CI](https://github.com/ghassan-gaidi/Null/actions/workflows/ci.yml/badge.svg)](https://github.com/ghassan-gaidi/Null/actions)
[![tests](https://img.shields.io/badge/tests-124%20green-00ff41?style=flat-square)](https://github.com/ghassan-gaidi/Null)
[![license](https://img.shields.io/badge/license-MIT%20%7C%20Apache--2.0-blue?style=flat-square)](https://github.com/ghassan-gaidi/Null)

</td>
<td width="33%" valign="top">

### <a href="https://github.com/ghassan-gaidi/crypto-empire">Crypto Empire</a>
<sub>Python · Flask · Live</sub>

**Autonomous crypto-intelligence platform** — live dashboard + Telegram bot, end-to-end monetized.

- Dashboard: top-20 markets, multi-chain gas, whale tracker, portfolios, yields
- **50+ Telegram commands** via `@Crypt0Emp1reBot`, webhook + polling modes
- **30+ REST endpoints**, token-bucket rate limiting, premium tiers via **Polar.sh**
- 4 GitHub Actions crons keep data fresh; hardened auth + secret-scan CI

[![live](https://img.shields.io/badge/live-crypto--empire--ten.vercel.app-000?style=flat-square)](https://crypto-empire-ten.vercel.app)
[![bot](https://img.shields.io/badge/bot-%40Crypt0Emp1reBot-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/Crypt0Emp1reBot)
[![API](https://img.shields.io/badge/API-30%2B%20endpoints-DC2626?style=flat-square)](https://crypto-empire-ten.vercel.app/docs)

</td>
<td width="33%" valign="top">

### <a href="https://github.com/ghassan-gaidi/drops.codes">drops.codes</a>
<sub>TypeScript · Next.js 16 · Live</sub>

**File-sharing platform** — upload, share, track. A WeTransfer alternative with teeth.

- No-signup uploads to **500 MB**: password protection, expiry, QR codes
- **12+ in-browser viewers** — PDF, code, EPUB, spreadsheets, ZIP, torrents
- **Build & Host**: write HTML/CSS/JS in the browser, publish instantly
- Team workspaces + analytics; subscriptions via **Dodo Payments**

[![live](https://img.shields.io/badge/live-dropscodes.vercel.app-000?style=flat-square)](https://dropscodes.vercel.app)
[![Next.js](https://img.shields.io/badge/Next.js-16-000?style=flat-square&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![Supabase](https://img.shields.io/badge/Supabase-Postgres-3ECF8E?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com)

</td>
</tr>
</table>

---

## Security Research

Multiple vulnerability reports submitted on **HackerOne**, verified at **high severity** — API security, auth logic, and applied cryptography. Details are restricted by program disclosure terms.

---

## Skills

<table>
<tr>
<td width="50%" valign="top">

**Languages**
`Rust` `Python` `TypeScript` `JavaScript` `SQL`

**Backend & web**
`REST API design` `Flask` `Next.js` `Supabase` `SQLite` `webhooks` `usage-based billing`

</td>
<td width="50%" valign="top">

**Security**
`vulnerability research` `API security` `applied cryptography` `formal modeling (Tamarin)` `fuzz testing`

**Tools**
`Git` `GitHub Actions (CI)` `Linux` `npm` `PyPI`

</td>
</tr>
</table>

---

## Education & Languages

**Bachelor's Degree (Licence) in Information and Communication Technology** — expected June 2027
Université de Carthage, Faculté des Sciences de Bizerte

**Arabic** (fluent) · **French** (conversational) · **English** (IELTS C1)

---

<div align="center">

### GitHub activity

![Stats](https://github-readme-stats.vercel.app/api?username=ghassan-gaidi&show_icons=true&theme=dark&hide_border=true&count_private=true&include_all_commits=true&bg_color=00000000&text_color=9ca3af&title_color=ffffff&icon_color=DC2626)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ghassan-gaidi&theme=dark&hide_border=true&count_private=true&layout=compact&bg_color=00000000&text_color=9ca3af&title_color=ffffff)

</div>

---

<div align="center">

`$ whoami`

**ghassan.dev** · [github.com/ghassan-gaidi](https://github.com/ghassan-gaidi) · [linkedin.com/in/ghassan-gaidi](https://linkedin.com/in/ghassan-gaidi-4637b3319) · [gg2574@proton.me](mailto:gg2574@proton.me)

<sub>PGP: A060 94AB E482 FB77 C67F F0F2 1266 E7E4 3803 2BD1</sub>

</div>
