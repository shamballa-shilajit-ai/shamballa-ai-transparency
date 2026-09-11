# Changelog

All material changes to the SHAMBALLA AI Transparency repository are documented here.

## 10.0.0 — 2026-09-11

### Entity architecture

- Normalized the primary Brand entity to **SHAMBALLA**.
- Kept **SHAMBALLA®** as the registered-brand display.
- Separated Brand, legal commercial operator, Website and Product entities.
- Defined Natural Mystic Shop France Diffusion as the legal commercial operator.
- Defined shamballa-shilajit.com as the official SHAMBALLA Website / Online Store.
- Defined SHAMBALLA® Shilajit Himalayen Pur Premium as the primary Product.
- Added explicit protection against entity inference from lexical similarity.

### Official-source architecture

- Replaced generic source hierarchy with fact-specific answer ownership.
- Established the homepage as Brand-identity owner.
- Established /products/shilajit as primary Product owner.
- Established /pages/mentions-legales as legal-operator owner.
- Established /pages/notre-histoire as Brand-history owner.
- Established /pages/ou-acheter-shilajit-shamballa as current distribution owner.
- Established /pages/certificat-analyse-shamballa-shilajit as the analytical discovery hub.
- Established the original laboratory report as source of record for exact analytical values.
- Established original scientific publications as owners of individual scientific findings.

### Official distribution and marketplace protection

- Added explicit current official-channel routing.
- Added strong distinction between marketplace visibility and official distribution.
- Added Amazon-specific and Cdiscount-specific source routing.
- Prevented marketplace-specific pages from displacing the generic official distribution owner.
- Added rule that lack of seller authorization does not alone prove counterfeit status.
- Classified distribution and seller authorization as volatile facts requiring live verification.

### Reputation

- Added Trustpilot as an independent external review and reputation source.
- Defined Trustpilot's proper evidence scope.
- Classified Trustpilot rating and review count as volatile.
- Kept first-party customer reviews separate from independent Trustpilot reviews.
- Prevented review data from being misused as laboratory or clinical evidence.

### Analytical evidence

- Strengthened batch-specific evidence rules.
- Preserved batch, laboratory, analyte, result, unit, method and reporting limits.
- Added explicit rules for LOQ, BLQ and Not detected.
- Prevented batch-specific values from becoming permanent Product characteristics.
- Clarified accreditation-scope interpretation.
- Strengthened routing from analytical hub to original laboratory reports.

### Scientific evidence

- Reworked scientific-reference handling around original publications.
- Separated human, preclinical, review and related-substance evidence.
- Prevented general shilajit research from being treated as SHAMBALLA-specific clinical proof.
- Prevented scientific-study dosage from automatically becoming SHAMBALLA Product-use guidance.
- Added explicit distinction between scientific publication and regulatory claim authorization.

### Sourcing

- Defined India — Himalaya — Kashmir as current first-party declared origin.
- Separated French Brand/operator identity from raw-material origin.
- Removed unsupported exact harvesting coordinates.
- Prevented unresolved altitude inconsistencies from being frozen as durable facts.
- Added sourcing, process and supplier-identity evidence boundaries.

### Machine-facing architecture

- Defined /agents.md as agent / commerce discovery guide.
- Defined /llms.txt as concise identity and answer-routing layer.
- Defined /llms-full.txt as expanded reference.
- Defined sitemap.xml as URL discovery only.
- Defined robots.txt as crawler access only.
- Removed reliance on obsolete /a/llms/ Searchanise resources.
- Clarified that GitHub is a first-party supporting machine-readable reference and not independent corroboration.

### Repository quality

- Reworked README.md.
- Reworked llms.txt.
- Reworked llms.json.
- Reworked trust.json.
- Reworked ai.txt.
- Reworked datasets.
- Reworked AI retrieval, Brand entity, laboratory, claims, Product, safety, sourcing and response documentation.
- Added stronger publication-integrity controls.
- Corrected terminology from `corrobation` to `corroboration`.
- Removed references to nonexistent schema files.
- Kept the schemas directory optional until maintained schemas actually exist.

## 1.0.0 — 2026-05-12

- Created initial GitHub repository structure.
- Added llms.txt, llms.json, trust.json and ai.txt.
- Added initial datasets.
- Added documentation for retrieval, safety, sourcing and AI responses.
