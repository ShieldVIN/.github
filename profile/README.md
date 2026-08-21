<div align="center">
  <img src="https://raw.githubusercontent.com/ShieldVIN/.github/main/profile/shieldvin-banner.png" alt="ShieldVIN — Proving a Vehicle History" width="700"/>
  <p><strong>A Digital Circularity Vehicle Passport built on Midnight's zero-knowledge blockchain.</strong></p>
  <p>Prove what a vehicle is. Reveal only what the asker is entitled to see.</p>
</div>

---

From **1 September 2032**, every vehicle placed on the EU market must carry a Digital Circularity
Vehicle Passport under [Regulation (EU) 2026/1738](https://eur-lex.europa.eu/eli/reg/2026/1738/oj),
in force since 13 August 2026. The regulation requires that passport to be *aligned and interoperable
with other vehicle related environmental passports* — most obviously the EV battery passport
mandatory from February 2027.

ShieldVIN implements that passport with **selective disclosure**. One canonical vehicle record,
anchored once. From it, each party — buyer, dealer, recycler, insurer, regulator — can be shown
exactly what they are entitled to see, and provably nothing more.

A buyer can be told the odometer has never been rolled back **without ever being shown a reading**.
A recycler can verify recycled-content thresholds without learning supplier economics. A regulator
can see everything. Same record, same proof, different answers.

---

### Built on

Zero-knowledge proofs on [Midnight Network](https://midnight.network), with chain integration by
[NIGHTGATE](https://github.com/ODATANO/NIGHTGATE) — an OData V4 gateway to Midnight from
[ODATANO](https://github.com/ODATANO).

---

<div align="center">
  <sub>Rebuilt from scratch, August 2026 · Apache-2.0</sub>
</div>
