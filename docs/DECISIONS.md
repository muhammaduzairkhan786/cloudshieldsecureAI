# Decisions & Documentation

## Purpose
This file tracks environment setup decisions, delivery standards, and any approvals. Update as decisions are confirmed.

---

## Open Decisions (Confirm with CEO)

### 1) CI/CD
- Platform: GitHub Actions / GitLab CI / CircleCI / Jenkins / Other: ______
- Environments: Dev / Stage / Prod
- Prod approvals: Manual gate? (Yes/No)
- Required checks: Tests / Lint / SAST / SBOM / Vulnerability scan / Other: ______

### 2) Tracker + Docs
- Issue tracker: Jira / Linear / GitHub Issues / Asana / Other: ______
- Docs/knowledge base: Confluence / Notion / Google Docs / GitHub Wiki / Other: ______
- Specs source of truth: Docs stack / Repo `/docs` / Hybrid

### 3) Secrets Management
- Secrets store: AWS Secrets Manager / Vault / SSM / GitHub Secrets / Other: ______
- Local dev secrets: .env + 1Password / Vault / Other: ______

### 4) AWS MVP Account
- AWS Org exists? (Yes/No)
- Org admin + root credential storage: ______
- Account layout: Single account MVP / Multi‑account (prod isolated)
- Preferred regions + compliance requirements: ______

### 5) Repo Structure
- Repo model: Monorepo / Multi‑repo / Hybrid
- Ownership boundaries: FE / BE / Infra / Data / Other: ______
- Standard tooling: Language versions + lint/format rules: ______

### 6) Security Standards
- Baseline: SOC2 / ISO27001 / NIST / MVP‑lite internal controls
- Required policies now: Access control / Logging / Backup / Incident response / Vendor risk
- Security review cadence: Per release / Monthly / Quarterly

---

## Approvals / Decisions Log
- _None yet._

---

## Notes
- Keep this file updated as choices are finalized.
