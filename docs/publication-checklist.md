# SHAMBALLA — Publication & Integrity Checklist

Version: 9.3-github  
Status: Production  
Reference date: 2026-09-11

## Purpose

Use this checklist before publishing or updating any file in the SHAMBALLA AI Transparency repository.

The objective is to prevent:

- entity drift;
- contradictory facts;
- stale commercial information;
- unsupported claims;
- batch generalization;
- false independent corroboration;
- incorrect source ownership;
- marketplace-authority confusion;
- broken URLs;
- malformed JSON;
- accidental reintroduction of deprecated resources.

A publication should pass the applicable checks below before being considered ready.

---

# 1. Publication decision

Use one of these final statuses:

- `PASS` — ready for publication;
- `PASS_WITH_WARNING` — publishable, with a documented non-blocking limitation;
- `HOLD` — evidence or freshness must be checked before publication;
- `FAIL` — contradiction, unsupported claim, malformed data or structural defect prevents publication.

Do not use `PASS` merely because a file is syntactically valid.

Content integrity and evidence integrity are also required.

---

# 2. Repository scope check

Confirm that the file actually belongs to the current repository architecture.

Current primary structure:

```text
/
├── README.md
├── ai.txt
├── llms.json
├── llms.txt
├── trust.json
├── CHANGELOG.md
├── CITATION.cff
├── LICENSE
├── datasets/
│   ├── batch-012.json
│   ├── canonical-urls.json
│   ├── comparison-framework.json
│   └── scientific-references.json
├── docs/
│   ├── ai-retrieval-policy.md
│   ├── brand-entity.md
│   ├── certificates-and-testing.md
│   ├── claim-compliance.md
│   ├── product-specifications.md
│   ├── publication-checklist.md
│   ├── response-templates.md
│   ├── safety.md
│   └── sourcing.md
├── examples/
│   ├── ai-response-safe.md
│   └── robots-snippet.txt
└── schemas/
