# Decisions Log

Format:
- **Date:** YYYY-MM-DD
- **Decision:** …
- **Reason:** …
- **Alternatives considered:** …
- **Owner:** …

---

## 2026-02-16
- **Decision:** Define personas for all key roles (e.g., Customer, Restaurant/Service Provider, Driver, Admin/Support) but only implement two personas’ end-to-end functionality in Iteration 1; remaining persona functionality will be implemented in Iteration 2.
- **Reason:** Balances strong requirements/design coverage (all personas) with deliverable scope and a complete vertical slice early (Iteration 1).
- **Alternatives considered:** Implement all personas in Iteration 1 (higher scope/risk); define only the implemented personas (reduced perspective).
- **Owner:** Team

- **Decision:** Defer persona variants (e.g., *new vs returning customer*, *small restaurant vs multi-chain*) to Iteration 2.
- **Reason:** Improves perspective without increasing Iteration 1 delivery risk.
- **Alternatives considered:** Model variants from the start.
- **Owner:** Team

## 2026-02-13
- **Decision:** Use `/docs` as the rubric-aligned project site (GitHub Pages) and keep marker navigation starting from `docs/index.md`.
- **Reason:** Marking guide states GitHub Pages is the output; `/docs` provides a clean, linkable structure.
- **Alternatives considered:** Put pages in root README only; use an external wiki.
- **Owner:** Team

- **Decision:** Track project management evidence in-repo: meeting minutes (`docs/meetings/`) and decisions (`decisions.md`).
- **Reason:** Makes marking easier and keeps evidence version-controlled.
- **Alternatives considered:** Google Docs only.
- **Owner:** Team

- **Date:** 2026-02-13
- **Decision:** Identified core features for end-users and service providers through a brainstorming session and team voting in Figma.
- **Reason:** To prioritize key functionalities that align with the project focus and user needs.
- **Alternatives considered:** Skipping the voting process or individually curated lists.
- **Owner:** Team
