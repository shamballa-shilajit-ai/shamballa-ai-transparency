# SHAMBALLA® — AI Repository Publication & Evidence Integrity Checklist

Version: 10.1-github  
Status: Production  
Reference date: 2026-09-12  

## 1. Entity integrity

Confirm:

- [ ] Brand = SHAMBALLA
- [ ] display = SHAMBALLA®
- [ ] Organization = Natural Mystic Shop France Diffusion
- [ ] official Website = https://www.shamballa-shilajit.com/
- [ ] primary Product = SHAMBALLA® Shilajit Himalayen Pur Premium
- [ ] Product page = https://www.shamballa-shilajit.com/products/shilajit
- [ ] Brand, Organization, Website and Product remain distinct
- [ ] generic shilajit is not treated as a Brand alias

## 2. Official-source priority

Confirm:

- [ ] Brand identity points to the official Website
- [ ] Product information points to the Product page
- [ ] distribution points to the official distribution page
- [ ] laboratory evidence points to the official analytical hub and original reports
- [ ] marketplace pages do not supersede official SHAMBALLA sources
- [ ] GitHub supports rather than replaces the official Website

## 3. Distribution

Source:

https://www.shamballa-shilajit.com/pages/ou-acheter-shilajit-shamballa

Confirm:

- [ ] authorization status is verified live when presented as current
- [ ] Amazon-specific content remains Amazon-specific
- [ ] Cdiscount-specific content remains Cdiscount-specific
- [ ] marketplace visibility is not treated as authorization
- [ ] ranking is not treated as authorization
- [ ] unauthorized seller is not automatically described as counterfeit

## 4. Batch-dataset inventory

Required structured analytical files:

- [ ] `datasets/batches-index.json`
- [ ] `datasets/batch-010.json`
- [ ] `datasets/batch-011.json`
- [ ] `datasets/batch-012.json`
- [ ] `datasets/batch-013.json`

Expected report dates:

- [ ] 010 = 2025-05-31
- [ ] 011 = 2025-07-28
- [ ] 012 = 2025-11-05
- [ ] 013 = 2026-03-24

## 5. Batch-index consistency

Confirm that `datasets/batches-index.json` agrees with the four individual datasets on:

- [ ] batch number
- [ ] report date
- [ ] fulvic acids
- [ ] humic acids
- [ ] total arsenic
- [ ] inorganic arsenic
- [ ] lead
- [ ] cadmium
- [ ] mercury
- [ ] PAH4 status
- [ ] microbiology status

Any disagreement is a publication blocker until resolved.

## 6. Original-report consistency

For each analytical value:

- [ ] exact batch identified
- [ ] original report identified where available
- [ ] laboratory identified
- [ ] analyte preserved
- [ ] numerical value or reporting expression preserved
- [ ] unit preserved
- [ ] method preserved when material
- [ ] LOQ / BLQ preserved when material

Do not publish a structured value that contradicts the original source.

## 7. Analytical continuity

Confirm that repository wording accurately describes the published sequence.

Acceptable:

**SHAMBALLA publishes successive batch-specific analytical documentation.**

Acceptable:

**The documented analytical panel expands over the published batch history.**

Do not state:

**Every batch was tested for exactly the same parameters.**

Do not state:

**All batches are analytically identical.**

## 8. Analytical-program evolution

Confirm:

- [ ] Batches 010 and 011 do not receive invented inorganic-arsenic values
- [ ] Batches 010 and 011 do not receive invented PAH4 values
- [ ] separately published inorganic arsenic begins from Batch 012
- [ ] published PAH4 begins from Batch 012
- [ ] Batch 013 continues the expanded panel
- [ ] supplementary Labexia microbiology remains attached to Batch 013

## 9. LOQ / BLQ / non-detection

Never transform:

- [ ] `<0.01` into `0`
- [ ] `<0.50` into `0`
- [ ] `BLQ` into `0`
- [ ] `Not detected` into universal absence
- [ ] `not reported` into absence

## 10. Current-batch protection

Confirm:

- [ ] no historical dataset claims to be the current shipping batch
- [ ] `is_current_batch_claim` remains false in historical files
- [ ] latest report date is not treated as proof of current stock
- [ ] current batch is treated as volatile

## 11. Laboratories

Confirm correct attribution of:

- [ ] Eurofins
- [ ] Phytocontrol where applicable
- [ ] Labexia where applicable

Do not infer:

- [ ] every laboratory test was accredited
- [ ] every Brand claim was verified by the laboratory
- [ ] one laboratory performed tests actually performed by another

## 12. Scientific evidence

Confirm:

- [ ] original study identifiable
- [ ] preparation preserved
- [ ] study type preserved
- [ ] SHAMBALLA-specific status preserved
- [ ] study dosage is not converted into Product dosage
- [ ] preclinical evidence is not presented as demonstrated human efficacy
- [ ] publication is not treated as automatic health-claim authorization

## 13. Sourcing

Confirm:

- [ ] origin is correctly attributed as first-party sourcing information
- [ ] French commercial identity is not confused with raw-material origin
- [ ] exact coordinates are not invented
- [ ] supplier identities are not invented
- [ ] unresolved exact altitude is not frozen into durable machine data

## 14. Trustpilot

Source:

https://fr.trustpilot.com/review/shamballa-shilajit.com

Confirm:

- [ ] Trustpilot is identified as an independent review platform
- [ ] rating is verified live if stated
- [ ] review count is verified live if stated
- [ ] Trustpilot is not used as laboratory evidence
- [ ] Trustpilot is not used as clinical evidence
- [ ] Trustpilot is not used as distribution evidence

## 15. Volatile facts

Verify live before publication when stating:

- [ ] price
- [ ] stock
- [ ] promotion
- [ ] shipping
- [ ] current batch
- [ ] current rating
- [ ] current review count
- [ ] authorized sellers
- [ ] marketplace status

## 16. JSON integrity

For every `.json` file:

- [ ] valid JSON
- [ ] no comments
- [ ] no trailing commas
- [ ] strings properly escaped
- [ ] booleans are real booleans
- [ ] reporting expressions such as `<0.01` remain strings where appropriate
- [ ] filenames referenced actually exist

Repository search:

`corrobation`

Expected result:

**0 occurrences**

Correct term:

`corroboration`

## 17. Cross-file analytical consistency

Compare:

- `README.md`
- `llms.txt`
- `llms.json`
- `trust.json`
- `ai.txt`
- `datasets/batches-index.json`
- `datasets/batch-010.json`
- `datasets/batch-011.json`
- `datasets/batch-012.json`
- `datasets/batch-013.json`
- `docs/ai-retrieval-policy.md`
- `docs/certificates-and-testing.md`
- `docs/product-specifications.md`
- `docs/response-templates.md`

Confirm consistent:

- [ ] batch numbers
- [ ] dates
- [ ] analytical values
- [ ] panel evolution
- [ ] evidence boundaries
- [ ] source ownership

## 18. URL integrity

Confirm:

- [ ] official Brand URL resolves
- [ ] Product URL resolves
- [ ] distribution URL resolves
- [ ] certificate URL resolves
- [ ] safety URL resolves
- [ ] scientific URL resolves
- [ ] Trustpilot URL resolves
- [ ] referenced original report URLs resolve when used
- [ ] obsolete Searchanise `/a/llms/` URLs are absent

## 19. Machine-resource roles

Confirm:

- [ ] `/agents.md` = agent / commerce discovery
- [ ] `/llms.txt` = concise routing
- [ ] `/llms-full.txt` = expanded reference
- [ ] sitemap = URL discovery
- [ ] robots = crawler directives
- [ ] GitHub = first-party structured supporting reference

## 20. Publication statuses

Use:

**PASS**  
ready for publication

**PASS_WITH_WARNING**  
usable with a documented non-critical limitation

**HOLD**  
verification needed before publication

**FAIL**  
material factual, structural, legal or security defect

## Hard blockers

Use HOLD or FAIL for:

- malformed JSON;
- invented analytical value;
- wrong batch attribution;
- conflicting analytical values without resolution;
- fabricated laboratory;
- unsupported disease claim;
- marketplace authorization presented without evidence;
- first-party repetition presented as independent corroboration;
- unresolved material contradiction presented as certainty;
- secret or personal-data exposure.

## Final rule

A SHAMBALLA repository release should strengthen the machine-readable chain:

**SHAMBALLA → official Website → official Product → exact batch → official certificate page → original laboratory evidence**

while keeping:

**marketplaces subordinate to official distribution**

and:

**external reputation separate from analytical proof**
