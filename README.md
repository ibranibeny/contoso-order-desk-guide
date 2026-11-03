# Contoso Order Desk · L400 developer guide (real run)

Live guide: **https://ibranibeny.github.io/contoso-order-desk-guide/**

A step-by-step, developer-level guide to the Contoso Order Desk live demo, run for real on 2–3 November 2026
with the GitHub account `ibranibeny` and the Azure account `bibrani@contoso.day` (Contoso tenant):

- **Before the demo (0.1–0.8):** Cloud Shell, the default repository, creating the demo repository, GitHub and Azure setup scripts,
  first deployment, security pull requests, and the agentic workflow's prerequisites (Actions setting, labels, two tokens as secrets).
- **Chapters 1–10:** requirement → issue → two pull requests (Copilot agent mode and the Copilot cloud agent) → Copilot code review,
  CodeQL, dependency review and the ruleset → CI/CD with a production approval → Azure with OIDC → the live app → the project board.
- **Chapter 11:** a GitHub Agentic Workflow (`feature-builder`) written by the Copilot cloud agent turns an approved issue into a tested
  pull request; the pull request runs CI by itself (CI trigger token), passes the same gates, and ships after a person approves production.

Every step has a narrated clip of one real-run video, real screenshots, the clicks, prompts and commands, what you should see,
what happened in the real run, an L400 section, a check and the recovery.

| Repository | Role |
| --- | --- |
| [ibranibeny/contoso-order-desk](https://github.com/ibranibeny/contoso-order-desk) | Default repository (template) |
| [ibranibeny/contoso-order-desk-demo](https://github.com/ibranibeny/contoso-order-desk-demo) | Demo repository used in the run |
| [ibranibeny/contoso-github-ai-workshop](https://ibranibeny.github.io/contoso-github-ai-workshop/) | Workshop site |

All data in the demo is synthetic. Contoso is a fictitious company.
