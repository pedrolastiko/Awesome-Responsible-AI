# Contributing to Awesome Responsible AI

Thank you for helping improve this Responsible AI knowledge base.

## Ways to contribute

- Add or update framework entries.
- Submit tools, templates, and interactive artifacts.
- Report outdated legislation and enforcement references.
- Improve structure, references, and cross-linking.

## Before you start

1. Open an issue describing your change (recommended for medium/large changes).
2. Verify the topic does not already exist in the repository.
3. Use primary sources whenever possible (official institutions, standards bodies, regulators).

## How to add a new framework

All framework entries must follow [`frameworks/TEMPLATE.md`](./frameworks/TEMPLATE.md).

### Required location

Place the new file in one of these folders:

- `frameworks/international/`
- `frameworks/national/`
- `frameworks/sectorial/`
- `frameworks/industry/`
- `frameworks/academic/`

### Required markdown template

Copy and complete this structure:

```md
# <Framework name>

- **Issuing body:**
- **Publication date / last update:**
- **Geographic scope:**
- **Legal status:** Enacted / Proposed / Guidance / Voluntary

## Summary (max 150 words)

<summary>

## RAI pillars covered

- [ ] Transparency
- [ ] Fairness
- [ ] Accountability
- [ ] Privacy
- [ ] Safety and reliability
- [ ] Security
- [ ] Inclusiveness
- [ ] Sustainability
- [ ] Governance

## Key requirements or principles

- ...

## Official link

- ...

## Related frameworks

- ...

## Notes / Quebec-Canada relevance

<optional implementation note>
```

## How to submit a new tool or artifact

1. Choose the proper directory under [`tools/`](./tools/):
   - `tools/html-artifacts/` for interactive HTML resources.
   - `tools/assessment/` for scoring or maturity methods.
   - `tools/checklists/` for operational checklists.
   - `tools/templates/` for reusable documents.
2. Add a `README.md` in the target folder if one does not exist, and register the entry.
3. For each tool, include:
   - Purpose
   - Intended audience
   - Inputs/outputs
   - Maintenance status
   - Link to source or official documentation

## How to report outdated legislation

If you detect outdated legal content:

1. Open an issue titled: `legislation-update: <jurisdiction/topic>`.
2. Include:
   - Current repository link
   - What changed (new law, amendment, repeal, enforcement action)
   - Official source URL
   - Effective date or consultation timeline
3. If possible, submit a PR moving the content between:
   - `legislation/proposed/` → `legislation/enacted/`
   - `legislation/guidelines/` → `legislation/enforcement/` (when enforceable actions appear)

## Branch naming conventions

Use lowercase and hyphens:

- `docs/<short-topic>`
- `framework/<issuer-or-standard>`
- `legislation/<jurisdiction-topic>`
- `tool/<tool-name>`
- `fix/<what-is-fixed>`

Examples:

- `framework/nist-ai-rmf-update`
- `legislation/eu-ai-act-enforcement`
- `tool/model-card-template`

## Pull request review process

1. **Automated checks**: markdown links/formatting should pass.
2. **Maintainer triage**: verifies scope and folder placement.
3. **Content review**: checks source quality, neutrality, and duplication.
4. **Structure review**: validates cross-links and table of contents updates.
5. **Merge**: squash merge with a clear changelog entry.

PR checklist:

- [ ] Correct folder and naming convention
- [ ] Template fields completed (if framework)
- [ ] Sources are official and accessible
- [ ] Internal links work
- [ ] README tables of contents updated where relevant

## Code of Conduct

By participating, you agree to follow the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).
