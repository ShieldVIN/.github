<div align="center">
  <img src="https://raw.githubusercontent.com/VINPassport/.github/main/profile/vinpassport-banner.png" alt="VINPassport, proving a vehicle identity" width="700"/>
  <p><strong>A Digital Circularity Vehicle Passport built on Midnight's zero-knowledge blockchain.</strong></p>
  <p>Prove what a vehicle is. Reveal only what the asker is entitled to see.</p>
  <p>
    <a href="https://passport.vin/"><b>Website (Live Demo)</b></a> ·
    <a href="https://passport.vin/deck/"><b>Slide deck</b></a>
  </p>
</div>

---

From **1 September 2032**, every vehicle placed on the EU market must carry a Digital Circularity
Vehicle Passport under [Regulation (EU) 2026/1738](https://eur-lex.europa.eu/eli/reg/2026/1738/oj),
in force since 13 August 2026. The regulation requires that passport to be *aligned and interoperable
with other vehicle related environmental passports*, most obviously the EV battery passport
mandatory from February 2027.

VINPassport implements that passport with **selective disclosure**. One canonical vehicle record
(identity, provenance, accident and service history, inspection record, type approval, environmental
declarations) anchored once. From it, each party (buyer, dealer, recycler, insurer, regulator)
can be shown exactly what they are entitled to see, and provably nothing more.

An EV's **battery** is a separate regime with its own passport. Ours carries a reference to it
rather than restating its claims: the regulation asks these passports to interoperate, not to
absorb one another.

A buyer can be told the vehicle was **never written off** and has **no reported accidents**, without
being shown the file. A recycler can verify recycled-content thresholds without learning supplier
economics. A dealer can prove the mileage has never been wound back without publishing a reading. A
regulator can see everything. Same record, same proof, different answers.

Every proof that holds leaves a **public record of the claim** (which vehicle, which field, which
bound) and never the value behind it. So a verdict can be checked by anyone, against the chain,
without anyone being handed the file.

---

### Repositories

| | |
|---|---|
| **[VINPassport](https://github.com/VINPassport/VINPassport)** | The passport: architecture, decisions, roadmap, and the build |

### Built on

Zero-knowledge proofs on [Midnight Network](https://midnight.network). The passport contract is
VINPassport's own work. The field panel and local transaction building use tooling from
[ODATANO](https://github.com/ODATANO), who also sponsored the contract deployment. Every
transaction is built, proven and signed on our side, so no private value ever leaves the process.
Fees for the live demo are paid from our own wallet.

---

<div align="center">
  <sub>Formerly ShieldVIN. Renamed August 2026 after a company-name collision · Rebuilt from scratch, August 2026 · Apache-2.0</sub>
</div>
