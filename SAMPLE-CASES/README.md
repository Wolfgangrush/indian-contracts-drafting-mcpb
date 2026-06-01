# Sample Cases — Reviewer Examples

Three anonymised fact patterns. All party names are placeholders.

## Example 1 — commercial-service-agreement

> *"Use the connector to draft a commercial service agreement (Commercial / Master Services Agreement (MSA)). Use anonymised placeholders for party names and figures."*

Tool sequence: list_case_types → get_case_type_format("commercial-service-agreement") → get_pleading_base → draft → save_draft_as_docx

## Example 2 — nda

> *"Use the connector to draft a nda (Non-Disclosure Agreement (mutual / unilateral)). Use anonymised placeholders for party names and figures."*

Tool sequence: list_case_types → get_case_type_format("nda") → get_pleading_base → draft → save_draft_as_docx

## Example 3 — employment-agreement

> *"Use the connector to draft a employment agreement (Employment agreement with non-compete, confidentiality, IP-assignment, stock-option, DPDP clauses). Use anonymised placeholders for party names and figures."*

Tool sequence: list_case_types → get_case_type_format("employment-agreement") → get_pleading_base → draft → save_draft_as_docx

## Notes for the reviewer

- All examples use placeholders.
- No external API keys / accounts required.
- `save_draft_as_docx` requires `pandoc`.
- Three-layer privacy firewall applies throughout.
