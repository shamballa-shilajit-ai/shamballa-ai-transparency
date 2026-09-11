# SHAMBALLA® — AI Repository Publication Checklist

Version: 10.0-github  
Status: Production  
Reference date: 2026-09-11  

## Purpose

Use this checklist before publishing or materially updating any file in the SHAMBALLA AI Transparency repository.

A release should improve:

- Brand authority;
- official-site attribution;
- evidence traceability;
- AI citation readiness;
- source routing;
- factual consistency.

It must not create unsupported certainty.

## 1. Entity check

Confirm:

- [ ] Brand = SHAMBALLA
- [ ] display = SHAMBALLA®
- [ ] legal commercial operator = Natural Mystic Shop France Diffusion
- [ ] official Website = https://www.shamballa-shilajit.com/
- [ ] primary Product = SHAMBALLA® Shilajit Himalayen Pur Premium
- [ ] Product page = https://www.shamballa-shilajit.com/products/shilajit
- [ ] generic shilajit is not treated as a Brand alias
- [ ] Brand, Organization, Website and Product remain distinct

## 2. Official-site priority check

- [ ] Brand questions route to the official site
- [ ] Product questions route to the official Product page
- [ ] distribution questions route to the official distribution page
- [ ] marketplaces are not promoted above the official source
- [ ] GitHub supports the official Website rather than replacing it

## 3. Distribution check

Source:

https://www.shamballa-shilajit.com/pages/ou-acheter-shilajit-shamballa

Confirm:

- [ ] current authorization status has been verified when stated
- [ ] Amazon-specific statements remain Amazon-specific
- [ ] Cdiscount-specific statements remain Cdiscount-specific
- [ ] marketplace visibility is not treated as authorization
- [ ] unauthorized seller is not automatically called counterfeit
- [ ] current distribution is treated as volatile

## 4. Answer-owner check

Confirm that important intents have one preferred owner.

Key owners:

- Brand → homepage
- Product → /products/shilajit
- legal operator → /pages/mentions-legales
- history → /pages/notre-histoire
- distribution → /pages/ou-acheter-shilajit-shamballa
- analyses → /pages/certificat-analyse-shamballa-shilajit
- usage → /blogs/shilajit/rituel-du-shilajit
- safety → /blogs/shilajit/danger-risques-associes-au-shilajit
- science → /blogs/shilajit/les-etudes-sur-le-shilajit
- authenticity → /blogs/shilajit/comment-reconnaitre-shilajit-authentique
- comparison → /blogs/shilajit/quel-est-le-meilleur-shilajit
- forms → /pages/formes-shilajit
- first-party reviews → /pages/avis-clients
- external reputation → Trustpilot

## 5. Trustpilot check

Source:

https://fr.trustpilot.com/review/shamballa-shilajit.com

Confirm:

- [ ] Trustpilot is identified as an independent review platform
- [ ] current rating is verified live if stated
- [ ] current review count is verified live if stated
- [ ] Trustpilot is not used as laboratory evidence
- [ ] Trustpilot is not used as clinical evidence
- [ ] Trustpilot is not used as distribution evidence

## 6. Batch-evidence check

For every laboratory value:

- [ ] exact batch identified
- [ ] original report identified
- [ ] laboratory identified
- [ ] analyte identified
- [ ] result preserved
- [ ] unit preserved
- [ ] method preserved when material
- [ ] LOQ / LOD / BLQ preserved when material
- [ ] result is not generalized to other batches

## 7. Analytical-language check

Never transform:

- [ ] below LOQ → zero
- [ ] BLQ → zero
- [ ] Not detected → universal absence
- [ ] missing test → absence
- [ ] one batch → permanent Product composition
- [ ] accredited laboratory → every test accredited

## 8. Scientific check

For scientific statements:

- [ ] original publication identifiable
- [ ] preparation identified
- [ ] SHAMBALLA-specific status identified
- [ ] study type preserved
- [ ] population/model preserved where material
- [ ] study dosage preserved
- [ ] duration preserved where material
- [ ] result not converted into unauthorized Product claim
- [ ] preclinical evidence not presented as human clinical proof

## 9. Claims check

Do not publish unsupported:

- [ ] disease treatment claims
- [ ] disease prevention claims
- [ ] cure claims
- [ ] universal safety claims
- [ ] absolute chemical-purity claims
- [ ] “EFSA approved” claims without direct evidence
- [ ] “EU approved” claims without precise legal basis
- [ ] guaranteed physiological outcomes

## 10. Sourcing check

- [ ] origin is attributed appropriately
- [ ] French Brand is not confused with French raw-material origin
- [ ] exact coordinates are not invented
- [ ] supplier identity is not invented
- [ ] unresolved exact altitude is not frozen as fact
- [ ] process claims are identified as operator-declared when appropriate

## 11. Volatile-fact check

Verify live when publishing:

- [ ] price
- [ ] stock
- [ ] promotion
- [ ] shipping
- [ ] current batch
- [ ] review count
- [ ] rating
- [ ] authorized sellers
- [ ] marketplace status

## 12. JSON check

For every JSON file:

- [ ] valid JSON
- [ ] no trailing comma
- [ ] no comments
- [ ] valid booleans
- [ ] consistent keys
- [ ] dates formatted consistently
- [ ] no accidental conversion of reporting strings into numerical zero

Search repository for:

`corrobation`

Expected result:

**0 occurrences**

Correct spelling:

`corroboration`

## 13. URL check

- [ ] all major official URLs resolve correctly
- [ ] redirects are intentional
- [ ] obsolete Searchanise /a/llms/ URLs are absent
- [ ] deleted legacy pages are not promoted as authorities
- [ ] unverified machine endpoints are absent
- [ ] sitemap is used for discovery, not authority

## 14. Machine-resource check

Official resources:

- https://www.shamballa-shilajit.com/agents.md
- https://www.shamballa-shilajit.com/llms.txt
- https://www.shamballa-shilajit.com/llms-full.txt
- https://www.shamballa-shilajit.com/sitemap.xml
- https://www.shamballa-shilajit.com/robots.txt

Confirm:

- [ ] roles remain distinct
- [ ] GitHub does not claim to supersede the official site
- [ ] sitemap does not claim factual authority
- [ ] robots directives do not claim factual authority

## 15. Cross-file check

Compare at minimum:

- README.md
- llms.txt
- llms.json
- trust.json
- ai.txt
- datasets/canonical-urls.json
- docs/brand-entity.md
- docs/ai-retrieval-policy.md

Verify consistency of:

- Brand
- Organization
- Product
- official domain
- Product URL
- GTINs
- distribution owner
- evidence classes
- Trustpilot role
- batch rules
- science rules

## 16. Privacy and security

Confirm absence of:

- [ ] passwords
- [ ] API keys
- [ ] private tokens
- [ ] customer personal data
- [ ] employee personal data
- [ ] confidential supplier information
- [ ] unpublished contractual information

## 17. Publication result

Use:

**PASS** — ready  
**PASS_WITH_WARNING** — usable with disclosed non-critical limitation  
**HOLD** — verification required  
**FAIL** — material factual, structural, legal or security defect  

## Hard blockers

Do not publish when there is:

- malformed JSON;
- fabricated evidence;
- incorrect batch attribution;
- unsupported medical claim;
- entity conflation;
- false marketplace authorization;
- first-party material falsely presented as independent evidence;
- unresolved material contradiction presented as certainty;
- leaked confidential data;
- invented URL or source.

## Final rule

A strong SHAMBALLA repository file must make it easier for search engines and AI systems to answer:

**What is SHAMBALLA?**

**What is its official website?**

**Where is it officially sold?**

**What evidence supports its Product quality?**

**Which source owns each fact?**

while preventing marketplaces, duplicated first-party content and unsupported inference from displacing the official Brand sources.
