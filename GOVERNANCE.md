# AFRION Sahara Governance

This document defines how AFRION Sahara is governed and how decisions are made.

## 1) Core principle (locked)
**AFRION retains final authority** over:
- roadmap
- merges to `main`
- official releases
- branding (AFRION, Sahara)
- contribution and safety policies

## 2) Roles
### Project Owner (AFRION)
- Ultimate decision-maker on scope, roadmap, and releases.
- Can approve or reject any PR.
- Appoints maintainers.

### Maintainers (TBD)
- Review PRs and Issues.
- Enforce repo standards and scope boundaries.
- Can be removed/added by AFRION.

**TBD:** maintainer selection approach.
Recommended options:
1) AFRION appoints maintainers based on consistent high-quality contributions.
2) Maintainership by nomination + AFRION approval.
3) Time-bound maintainer terms (e.g., 3 months), renewable by AFRION.

### Contributors
- Anyone submitting Issues, PRs, docs, or discussions.
- Must sign the CLA before code is accepted.

## 3) Decision-making
- **Day-to-day:** Maintainers decide, with AFRION override.
- **Major decisions:** AFRION decides after community input.
Major decisions include:
- scope changes
- benchmark definitions
- licensing changes
- release policies
- brand policy changes

## 4) Repository controls (planned)
- PR-only workflow (no direct pushes to `main`)
- Branch protection on `main`:
  - required reviews
  - required CI checks
- `CODEOWNERS` file for critical directories (**TBD**)
- Security policy and private vulnerability reporting (see SECURITY.md)

## 5) Releases and “official Sahara”
- “Official Sahara” releases/checkpoints/builds are AFRION-controlled.
- Public contributions may inform official releases, but AFRION decides what becomes canonical.

## 6) Open-core boundary (locked mindset)
Public repo: benchmarks, tooling, docs, safe demos.
Private assets (not in repo): proprietary datasets, weights, production infra, secrets, sensitive components.

## 7) Dispute resolution
- Maintainers attempt resolution via discussion.
- AFRION makes the final call when needed.
