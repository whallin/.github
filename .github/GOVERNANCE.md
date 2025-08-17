# Governance

This document describes governance for my repositories: who’s responsible for decisions, how I handle larger changes, where to report issues (including security), legal/licensing expectations, and the schedule for governance reviews.

## Roles & responsibilities

- **Core maintainers** — sets direction, handles escalations, and makes final decisions when consensus cannot be reached.
- **Project maintainers** — manages daily project work, reviews and merges contributions per project policies, and escalates governance issues when necessary.
- **Community moderator** — helps keep interactions civil and routes conduct or governance reports to the right place.

> [!TIP]
> If you're unsure who owns a decision, consult the repository `README` and `CODEOWNERS`; if it's still unclear, ask a core maintainer.

## Decision making

1. **Consensus** — I prefer to reach agreement through open discussion (issues, discussions, or RFCs) when possible.
2. **RFCs** — substantial changes to governance, APIs, release policy, or licensing belong in an RFC that explains the problem, potential approaches, trade-offs, and a recommended approach.
3. **Escalation** — if consensus isn't possible within a reasonable timeframe, I will decide; the decision will be recorded and communicated (linked PR/issue/RFC).

## Reporting: what, how, and where

### 📍 Where to report

- [GitHub Issues](https://github.com/whallin/.github/issues/new/choose) — for reproducible bugs or repository-specific governance/process questions.
- [GitHub Discussions](https://github.com/orgs/whallin/discussions) — for broader governance conversations and initial proposals not yet ready for RFCs.
- Email — for private or sensitive matters that shouldn't be public: [william@hallin.media](mailto:william@hallin.media)

### 📝 What to include

- A brief summary of the issue or request.
- Helpful context (repository, links to PRs/issues, relevant dates, and affected versions).
- Any proposed fixes or desired outcomes.

### 🔁 How reports are handled

- I will acknowledge reports within 3 business days.
- Confidential email reports will be handled by me and any relevant stakeholders.
- Where feasible, I will record outcomes and next steps publicly (issue/PR/RFC) for transparency.

## Security and incident reporting

Security issues should be reported only via the [SECURITY.md](SECURITY.md) process. Do not publish exploit details. Security reports routed through the SECURITY process will be triaged by me and any security contacts under coordinated disclosure.

## Legal, licensing & contributor agreements

- Public repositories should include a license file. If a CLA is required, follow the repository's stated process and direct legal questions to [william@hallin.media](mailto:william@hallin.media).
- Respect third-party license obligations and disclose restrictive dependencies when proposing major architecture changes.

## Access control & protected branches

- Main branches are protected. Merges require at least one maintainer approval and passing CI checks unless I approve an exception.
- Access to private repos or elevated permissions is granted on a need-to-work basis and I review access periodically.

## Privacy & compliance

I follow privacy-by-design principles and relevant data protection regulations (e.g., GDPR/CCPA) where applicable. Repositories that collect or process personal data must document data flows and controls and consult legal when needed.

## Changes to this document

Changes to this document should be proposed via RFC or a tracked PR. Major updates should be announced and linked from the accepting PR.

---

_If you're unsure where to report something or what details to include, email [william@hallin.media](mailto:william@hallin.media) and I'll help you._
