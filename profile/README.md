# GNS Foundation

**Building the identity layer the internet never had.**

The Geospatial Naming System (GNS) is a decentralized identity protocol where **Identity = Public Key** and humanity is proven through physical movement — not biometrics, not corporations, not CAPTCHAs.

We call it **Proof-of-Trajectory**: cryptographically-signed location breadcrumbs collected through smartphone movement create unfakeable behavioral patterns that only real humans produce.

*"You are not your iris. You are your journey through the world."*

---

### What We're Building

🔑 **[TRIP Protocol](https://github.com/GNS-Foundation/trip-protocol)** — IETF Internet-Draft for Trajectory-based Identity Proof. Defines how devices collect, sign, and verify location trajectories. Currently at revision -02, under review by the RATS (Remote ATtestation procedureS) working group.

🦅 **[ULissy](https://github.com/GNS-Foundation/ulissy)** — A domain-specific programming language for moving machines. Treats identity, location, time, cryptography, and energy as first-class language primitives. 26,000 lines, working compiler, 74/74 protocol tests passing. [Try it in your browser →](https://gns-foundation.github.io/ulissy/playground/)

📱 **[GNS Browser](https://github.com/GNS-Foundation/gns-mobile)** — Mobile app (Flutter) with encrypted messaging, handle-based payments, DIX microblogging, and spatial identity discovery.

---

### How It Works

```
You move through the world with your phone
        ↓
Breadcrumbs are collected (H3 cells, not raw GPS — privacy preserved)
        ↓
Breadcrumbs are signed with your Ed25519 key and chained
        ↓
100+ breadcrumbs = 1 Epoch (submitted to the network)
        ↓
Epochs accumulate → Trust score rises → You earn your @handle
        ↓
Your identity IS your public key. No passwords. No corporations.
```

---

### Key Links

| | |
|---|---|
| **IETF Datatracker** | [draft-ayerbe-trip-protocol](https://datatracker.ietf.org/doc/draft-ayerbe-trip-protocol/) |
| **ULissy Playground** | [gns-foundation.github.io/ulissy/playground](https://gns-foundation.github.io/ulissy/playground/) |
| **Language Whitepaper** | [ULissy Whitepaper v0.1](https://github.com/GNS-Foundation/ulissy/blob/main/docs/whitepaper/WHITEPAPER.md) |
| **Formal Grammar** | [EBNF Specification (93 rules)](https://github.com/GNS-Foundation/ulissy/blob/main/docs/GRAMMAR.md) |
| **Patent** | Provisional #63/948,788 — Proof-of-Trajectory |
| **Contact** | camilo@ulissy.com |

---

### Architecture

| Layer | Protocol | What It Does |
|-------|----------|-------------|
| **Identity** | GNS | @handle naming, Ed25519 keys, facet addressing |
| **Proof** | TRIP | Trajectory collection, epoch bundling, trust scoring |
| **Language** | ULissy | Domain-specific compiler for spatial-identity programs |
| **Payments** | IDUP | Handle-based payments on Stellar (USDC/EURC) |
| **Discovery** | TrIP Search | Spatial-identity search ranked by cryptographic trust |

---

### The Philosophy

**HUMANS PREVAIL.** No iris scans. No corporate gatekeepers. No specialized hardware. Any smartphone. Any person. Anywhere.

The internet has DNS for documents. GNS is DNS for humans — where your name is earned through living, not purchased from a registrar.

---

*Rome, Italy · [ulissy.com](https://ulissy.com) · MIT / Apache 2.0 / BSL 1.1*
