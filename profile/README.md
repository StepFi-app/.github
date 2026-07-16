<div align="center">

<img src="https://github.com/StepFi-app/.github/raw/main/profile/StepFi.png" alt="StepFi Banner" />

# StepFi

### Step into your future. Credit without banks. Progress without limits. 🌍

**Open-source decentralized BNPL protocol on Stellar — built for learners, interns, and early-career developers in emerging markets.**

[![Stellar](https://img.shields.io/badge/Powered%20by-Stellar-7D00FF?style=flat-square&logo=stellar&logoColor=white)](https://stellar.org)
[![Open Source](https://img.shields.io/badge/Open%20Source-Yes-22C55E?style=flat-square)](https://github.com/StepFi-app)
[![Contributors Welcome](https://img.shields.io/badge/Contributors-Welcome-2563EB?style=flat-square)](https://github.com/StepFi-app/StepFi-API/issues)
[![License](https://img.shields.io/badge/License-MIT-F59E0B?style=flat-square)](./LICENSE)

</div>

---

## The Problem

Students and interns across Africa and beyond can't afford upfront costs for laptops, courses, and dev tools. Traditional banks won't lend to them without credit history. They're locked out before they even start.

## The Solution

StepFi lets learners finance what they need and repay in small installments — powered by Soroban smart contracts on Stellar. No banks. No passwords. Just your wallet.

---

## How It Works

| | |
|---|---|
| 🔐 **Wallet Auth** | Sign in with your Stellar wallet — no passwords, no email |
| 💻 **Finance Tools** | Laptops, courses, bootcamps, dev subscriptions |
| 📦 **Pay Small Small** | Weekly or monthly installments settled on-chain |
| ⭐ **Build Reputation** | Every on-time payment improves your on-chain credit score |
| 💧 **Community Pool** | Sponsors and contributors fund the learner lending pool |
| 🤝 **Mentor Vouching** | Mentors vouch for learners to unlock higher credit limits |

---

## 🔗 Live Deployments

| Resource | Link |
|---|---|
| Landing Page | https://stepfi.vercel.app |
| API | https://stepfi-api.onrender.com/api/v1 |
| Swagger | https://stepfi-api.onrender.com/api/v1/docs |
| Documentation | https://docs.page/StepFi-app/StepFi-Docs |
| StepFi-Web | https://stepfi-web.netlify.app |
| Demo | https://stepfi.vercel.app/demo |
| Playground | https://stepfi.vercel.app/playground |
| Creditline Contract | https://stellar.expert/explorer/testnet/contract/CAQDHYG3TALPNXG466SZUMJEPOI7VYV732LPFF3GHE4ASPBCNMIQBS3X |
| Reputation Contract | https://stellar.expert/explorer/testnet/contract/CC3BO57ZRJGA63QJBIBSOMI25Z3X2I5CYTARYRAUXUAILX6L3OWBL5SB |
| Liquidity Pool | https://stellar.expert/explorer/testnet/contract/CACKE7ML2BTOAGQTAAW5NEARHCFX4PXXKGEO6GMU6NHFBVYQFZRJS2BT |
| Vendor Registry | https://stellar.expert/explorer/testnet/contract/CCZ6T6NYCDNI26VGTPXKKWQDR7JCIZZ24LCEG4MMYHZJAG6BPWIVAU2L |
| Parameters | https://stellar.expert/explorer/testnet/contract/CCAE72SKYX55C5L56DBEFIMFVXRUIJY6JYLBREHEWRFNOW7AX5NBIJ5B |

## Repositories

| Repo | Stack | Description |
|---|---|---|
| [StepFi-API](https://github.com/StepFi-app/StepFi-API) | NestJS · Fastify · TypeScript | Off-chain orchestration — auth, loans, reputation, background jobs |
| [StepFi-Contracts](https://github.com/StepFi-app/StepFi-Contracts) | Rust · Soroban SDK | On-chain smart contracts — credit line, reputation, liquidity pool, vendor registry |
| [StepFi-App](https://github.com/StepFi-app/StepFi-App) | React Native · Expo · TypeScript | Mobile application — learner and sponsor interfaces |
| [StepFi-Web](https://github.com/StepFi-app/StepFi-Web) | Vite · React · TypeScript | Web app for sponsors, vendors, and mentors |
| [StepFi-Docs](https://github.com/StepFi-app/StepFi-Docs) | docs.page | Protocol documentation and developer guides |

---

## Tech Stack

```
Backend    →  NestJS + Fastify + TypeScript + Supabase + Redis + BullMQ
Contracts  →  Rust + Soroban SDK on Stellar
Mobile     →  React Native + Expo + WalletConnect v2
Auth       →  Stellar wallet signature → JWT (no passwords)
```

---
## Documentation

The StepFi protocol documentation covers smart contract
functions, API endpoints, authentication flows, reputation
tiers, contributing guides, and the full system architecture.
Built for developers who want to understand or contribute to the protocol. [View Docs]( https://docs.page/StepFi-app/StepFi-Docs)

## Contributing

We welcome contributors of all levels — whether you're a Soroban dev, a NestJS engineer, a React Native builder, or just getting started in open source. There's a place for you in StepFi.

**Where to start:**
- 📋 Browse [open issues](https://github.com/StepFi-app/StepFi-API/issues) — look for `good first issue`
- 📖 Read the [Contributing Guide](https://github.com/StepFi-app/StepFi-API/blob/main/CONTRIBUTING.md)
- 🗺 Check the [Roadmap](https://github.com/StepFi-app/StepFi-API/blob/main/ROADMAP.md)

**Areas open for contribution:**
- 🔧 Backend — NestJS modules, BullMQ jobs, Supabase migrations
- 🦀 Smart Contracts — Rust + Soroban development
- 📱 Mobile — React Native + Expo screens and components
- 🧪 Testing — Unit, integration, and E2E tests
- 📝 Documentation — Guides, API docs, tutorials

---

<div align="center">

**Built for the Stellar ecosystem. Built for learners. Built in the open.**

*Africa · Emerging Markets · Open Source*

</div>