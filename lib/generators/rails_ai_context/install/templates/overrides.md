# Repo-specific AI / Copilot guidance

Edit this file with **your team's** rules. It is merged into compact
`.github/copilot-instructions.md` and `AGENTS.md` under **Repo-specific guidance**
when you run `rails ai:context`.

Examples of what to add:

- **Large or sensitive tables** — name tables that must never be full-scanned in requests;
  required indexes; patterns for batch jobs vs interactive UI.
- **Authorization** — org/tenant scoping, PII fields, audit requirements.
- **Performance** — caching layers, read replicas, known hot endpoints.
- **Testing** — minimum spec types for certain changes (e.g. request spec for API changes).

Remove this comment block once you have real content, or keep a short checklist.
