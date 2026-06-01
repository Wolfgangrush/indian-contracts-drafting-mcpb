# Wolfgang Rush — Indian Contracts & Personal-Estate Drafting

**MCPB Desktop Extension** for Indian advocates using Claude Desktop App. Local-execution. Zero data collection.

> *Also available as a Claude Code Plugin:* *[github.com/Wolfgangrush/indian-contracts-drafting](https://github.com/Wolfgangrush/indian-contracts-drafting)*

## What this connector does

MSAs, NDAs, employment, lease, sale, GPA/SPA, shareholders agreement, will, loan, arbitration clauses. Indian Contract Act + DPDP + Stamp + Registration + Arbitration Act 2021 amended.

## Case types

- `commercial-service-agreement` — Commercial / Master Services Agreement (MSA)
- `nda` — Non-Disclosure Agreement (mutual / unilateral)
- `employment-agreement` — Employment agreement with non-compete, confidentiality, IP-assignment, stock-option, DPDP clauses
- `lease-deed` — Lease deed under Section 105 TPA + Registration Act
- `sale-deed` — Sale deed under Section 54 TPA + Stamp Act + Registration Act
- `gpa-spa` — General / Special Power of Attorney
- `shareholders-agreement` — Shareholders Agreement (Indian companies)
- `will` — Will under the Indian Succession Act 1925
- `loan-agreement` — Loan agreement (secured / unsecured)
- `arbitration-clause` — Section 7 Arbitration Agreement / arbitration clause for commercial contracts

## Install

1. Claude Desktop App → **Settings → Extensions → Install Extension**
2. Select `wolfgang-indian-contracts-drafting.mcpb`
3. Enable

## System requirements

Claude Desktop App ≥ 0.10.0 · Python ≥ 3.10 · `pandoc` for .docx · `pdftotext` for PDF case-files (optional)

## Privacy

Zero data collection. Three-layer privacy firewall. Canonical policy: **<https://wolfgangrush.github.io/privacy/>**


## ⚠️ AI verification disclaimer · 🔒 Pseudonymisation procedure

> **⚠️ AI can make mistakes — please verify the information before filing.**
> Every draft produced by this connector is a STARTING POINT. The Verifier
> agent runs an anti-hallucination firewall and the Overseer agent runs an
> opposing-counsel review, but neither replaces an advocate's independent
> verification of statutory references, citation accuracy, factual fidelity,
> and Registry-formatting compliance with the user's High Court / forum.
> The advocate filing the pleading remains responsible for the contents.
>
> **🔒 Protected by pseudonymisation procedure.** The Reader agent applies a
> domain-specific privacy firewall as the first step of the pipeline — party
> names, addresses, identifying numbers (FIR / CR / Crime / Suit / Diary /
> SLP / lower-court case numbers), PAN / Aadhaar references, financial
> figures, witness names, and statutory-notice references are substituted
> with structural placeholders BEFORE any downstream agent sees the facts.
> The Drafter, Verifier, Refiner, and Overseer agents process placeholders
> only. Real values are re-substituted at the final docx render step on the
> user's local machine. No real identifying data leaves the case folder.

## License

MIT.

## Publisher

**Rushikesh R. Mahajan**, Advocate, Bombay HC Nagpur, publishing as **Wolfgang Rush**. advrushikeshravindramahajan@gmail.com

## Source

<https://github.com/Wolfgangrush/indian-contracts-drafting-mcpb>

## Sample cases

See `SAMPLE-CASES/`.
