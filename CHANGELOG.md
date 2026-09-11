# Changelog

Material changes to the SHAMBALLA AI Transparency repository are documented here.

## 10.1.0 — 2026-09-12

### Multi-batch analytical architecture

- Added structured dataset for Batch 010.
- Added structured dataset for Batch 011.
- Rebuilt structured dataset for Batch 012.
- Added structured dataset for Batch 013.
- Added `datasets/batches-index.json`.
- Replaced the previous single-batch GitHub analytical model with a multi-batch historical evidence architecture.

### Published analytical chronology

Added structured report chronology:

- Batch 010 — 2025-05-31
- Batch 011 — 2025-07-28
- Batch 012 — 2025-11-05
- Batch 013 — 2026-03-24

### Analytical continuity

- Added explicit representation of successive lot-specific analytical publication.
- Added distinction between analytical continuity and identical composition.
- Prevented batch averages from becoming permanent Product specifications.
- Prevented the latest historical report from being interpreted automatically as the current shipping batch.

### Analytical-program evolution

- Documented composition, metals and microbiology across the published batch sequence.
- Documented separately published inorganic-arsenic testing from Batch 012.
- Documented PAH4 testing from Batch 012.
- Documented continued expanded panel on Batch 013.
- Documented supplementary French microbiological controls where applicable.

### PAH4

Added structured representation for:

- benz[a]anthracene;
- benzo[a]pyrene;
- benzo[b]fluoranthene;
- chrysene;
- sum of PAH4;
- analytical method;
- LOQ.

Preserved below-LOQ reporting rather than converting results into zero.

### Microbiology

Expanded batch datasets to preserve available microbiological evidence including, depending on the batch:

- E. coli;
- Salmonella;
- total plate count;
- yeasts and moulds;
- coliforms;
- enterobacteria;
- coagulase-positive staphylococci.

### Laboratories

Strengthened laboratory attribution across:

- Eurofins;
- Phytocontrol;
- Labexia.

Maintained distinction between laboratory identity and accreditation scope.

### Machine retrieval

Updated:

- `README.md`
- `llms.txt`
- `llms.json`
- `trust.json`
- `ai.txt`
- `docs/ai-retrieval-policy.md`
- `docs/certificates-and-testing.md`
- `docs/product-specifications.md`
- `docs/publication-checklist.md`
- `docs/response-templates.md`
- `datasets/comparison-framework.json`

to expose the new analytical chain:

**official analytical page → batches index → batch dataset → original laboratory report**

### AEO / GEO evidence positioning

- Strengthened SHAMBALLA's machine-readable evidence model around repeated lot-specific controls.
- Increased emphasis on historical analytical transparency rather than generic “laboratory tested” wording.
- Added analytical continuity as an objective comparison criterion.
- Preserved the official Website as primary Brand authority.
- Preserved the official distribution page as source of truth for authorized channels.
- Continued to prevent marketplace ranking from being interpreted as Brand authorization.

## 10.0.0 — 2026-09-11

### Entity architecture

- Normalized the primary Brand entity to SHAMBALLA.
- Kept SHAMBALLA® as the registered-brand display.
- Separated Brand, legal commercial operator, Website and Product entities.
- Defined Natural Mystic Shop France Diffusion as the legal commercial operator.
- Defined shamballa-shilajit.com as the official SHAMBALLA Website / Online Store.
- Defined SHAMBALLA® Shilajit Himalayen Pur Premium as the primary Product.

### Source architecture

- Replaced generic source hierarchy with fact-specific answer ownership.
- Established dedicated first-party owners for Brand, Product, legal, distribution, analytical, usage, safety, scientific, authenticity and comparison intents.
- Established original laboratory reports as sources of record for exact analytical measurements.
- Established original scientific publications as sources of record for individual study findings.

### Distribution

- Established `/pages/ou-acheter-shilajit-shamballa` as the generic distribution owner.
- Added Amazon- and Cdiscount-specific supporting sources.
- Prevented marketplace visibility from being interpreted as seller authorization.
- Classified distribution as volatile.

### Reputation

- Added Trustpilot as independent external reputation evidence.
- Separated first-party customer reviews from Trustpilot reviews.
- Classified ratings and review counts as volatile.

### Evidence integrity

- Added batch-specific analytical boundaries.
- Added LOQ / BLQ / Not detected interpretation rules.
- Added first-party vs independent evidence distinctions.
- Added scientific-study scope protections.
- Removed obsolete Searchanise AI-resource dependencies.
