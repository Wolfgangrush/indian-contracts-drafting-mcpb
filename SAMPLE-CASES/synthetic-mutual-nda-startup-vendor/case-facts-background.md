# Case Facts Background — Mutual NDA between [Startup-A] and [Vendor-B]

This fixture is **transactional**, not litigation. The connector drafts a contract from instructions; the Reader stage reads the instructions + party particulars + transaction context to produce a draft agreement.

All party names, CIN, addresses, monetary figures, and ancillary dates are fictional placeholders.

## Parties

- **Party A — Discloser-cum-Recipient ("[Startup-A]"):** [Startup-A] Private Limited, CIN [Startup-CIN-Placeholder], Bengaluru-based SaaS startup operating a platform for [SaaS-Use-Case-Placeholder].
- **Party B — Discloser-cum-Recipient ("[Vendor-B]"):** [Vendor-B] Private Limited, CIN [Vendor-CIN-Placeholder], Mumbai-based payment-processing vendor with RBI [Vendor-Settlement-Placeholder] licences.

## Commercial context

- The parties have had introductory discussions on 22 May 2026 about a potential integration of [Vendor-B]'s payment rails into [Startup-A]'s SaaS workflow.
- Information to be exchanged is sensitive — product architecture, API specifications, customer lists, financial projections, code samples, settlement SLAs, RBI compliance posture.
- A mutual NDA is required before substantive technical and commercial discussions commence.

## Drafting parameters

- **Type:** Mutual (bilateral) NDA — both parties are disclosers and recipients.
- **Term:** Operational period 2 years from Effective Date; confidentiality survives 5 years.
- **Purpose:** Limited to evaluating the prospective commercial partnership.
- **Carve-outs:** Standard (public domain, independently developed, lawfully received from third party, required by law).
- **Non-solicit:** 12 months mutual on employees.
- **DPDP:** Section 8 safeguards on incidentally-shared personal data.
- **Injunctive relief:** Available, in addition to damages.
- **Return / destruction:** 30 days post-termination + written certification.
- **Governing law:** Indian law.
- **DR:** Institutional arbitration (3-arbitrator panel) at [Arbitral-Seat-Placeholder], in English.
- **Stamp duty:** Karnataka (party preparing the draft bears it).

## Case type

`nda`

## How to use this fixture

1. Point `read_case_folder(path)` at this directory.
2. Reader extracts the drafting instructions from `01-drafting-instructions-mutual-nda.docx` and the commercial context from `02-prior-discussion-note-2026-05-25.docx` plus this `case-facts-background.md`.
3. Call `get_case_type_format("nda")` for the NDA drafting template.
4. The Format stage maps drafting parameters into the NDA template placeholders.
5. The Drafter authors the full mutual NDA with all clauses (Definitions, Confidentiality Obligations, Permitted Use, Carve-outs, Term, Survival, Non-Solicit, DPDP, Injunctive Relief, Return / Destruction, Stamp, Governing Law, Dispute Resolution, Counterparts, Notices).
6. The Verifier checks that every clause requested in the instructions has been incorporated and that no extraneous obligations have been smuggled in.
7. The Refiner polishes language and harmonises defined terms.
8. The Overseer reads with opposing-counsel lens — identifies the weak limbs (e.g. broad "residual knowledge" clauses, overly-narrow injunctive-relief language) and surfaces them to the drafter.
9. Output: `final-draft.docx` — a ship-ready mutual NDA with execution block.

## Carve-outs flagged for human-counsel review

(i) Disclaimer of partnership / JV / fiduciary relationship — recommended to include.
(ii) Residual-knowledge clause — risk-laden; client to decide.
(iii) Feedback / improvement IP — recommended vesting in discloser with free licence-back.
(iv) Trade-secret indefinite-protection carve-out — recommended.
