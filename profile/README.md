# ShieldVIN

**Cryptographic vehicle identity on Midnight Network's zero-knowledge proof blockchain.**

ShieldVIN embeds three tamper-resistant Secure Element chips into every new vehicle at manufacture — one in the engine, one in the chassis, one in the telematics module. All three must co-sign every identity proof. The vehicle's identity record is minted as a token on [Midnight Network](https://midnight.network) at the point of production.

The result: VIN cloning and chassis fraud become permanently impossible on enrolled vehicles. Every proof reveals exactly what each authority needs — and nothing more.

---

## The Problem

Over **$20 billion** is lost globally each year to vehicle theft and VIN fraud. VIN cloning — copying a plate from a legitimate vehicle onto a stolen one — is undetectable by current systems. Existing databases are reactive, rely on timely reporting, and are easily circumvented.

A VIN is a stamped metal plate. Anyone can replicate it. ShieldVIN makes the physical hardware the unforgeable identity.

---

## Why Midnight Network

Zero-knowledge proofs allow ShieldVIN to prove a claim is true without revealing the underlying data.

- Police receive: **stolen / not stolen**
- Insurers receive: **ownership count, service history, mileage**
- Dealers receive: **identity valid, transfer count**
- Buyers receive: **clean title confirmation**

Each party gets exactly what they need. Personal data never touches the blockchain.

---

## The Three Hardware Nodes

| Node | Location | Role |
|------|----------|------|
| **EN-1** Engine Node | ECU housing, engine bay | Independent Ed25519 keypair — key wipe on breach |
| **CN-2** Chassis Node | A-pillar / firewall | Independent Ed25519 keypair — alert on frame cut |
| **TN-3** Telematics Node | Telematics module | Independent Ed25519 keypair — witness data assembler |

Remove any one node — proof fails. Identity rejected.

---

## Proposal Documents

| Document | Description |
|----------|-------------|
| [Landing Page](https://shieldvin.github.io/proposal/) | Project overview and navigation |
| [One-Page Summary](https://shieldvin.github.io/proposal/shieldvin-summary.html) | Chips, proof flow, stakeholder access, revenue overview |
| [Interactive Demo](https://shieldvin.github.io/proposal/shieldvin-demo.html) | Live verification simulation — all roles and scenarios |
| [Full Whitepaper](https://shieldvin.github.io/proposal/whitepaper.html) | 15-section technical and business proposal |
| [Market Opportunity](https://shieldvin.github.io/proposal/market-opportunity.html) | OEM adoption scenarios with live revenue modelling |
| [Process Flow](https://shieldvin.github.io/proposal/process-flow.html) | 14-phase vehicle lifecycle — manufacture to decommission |
| [Glossary](https://shieldvin.github.io/proposal/glossary.html) | 50 terms across 8 categories |

---

## Industry Standards

ShieldVIN proposes four open standards for the automotive identity ecosystem:

| Standard | Name | Description |
|----------|------|-------------|
| **VSE-1** | Vehicle Secure Element Standard | Hardware specification for the three SE chips |
| **VIT-1** | Vehicle Identity Token Standard | On-chain data structure and proof schema |
| **VAP-1** | Verification API & Protocol Standard | API contract for all verification roles |
| **VGM-1** | Vehicle Governance Model | W3C-style consortium governance framework |

---

## Repositories

| Repo | Description |
|------|-------------|
| [proposal](https://github.com/ShieldVIN/proposal) | Concept proposal — whitepaper, specs, interactive demo, ZK contract |

*Platform repositories coming soon.*

---

Built on [Midnight Network](https://midnight.network) · Targeting the $20B/yr vehicle fraud problem
