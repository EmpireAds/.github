<div align="center">

<img src="https://raw.githubusercontent.com/EmpireAds/.github/main/profile/assets/logo.png" width="220" alt="EmpireAds">

<h1 align="center">Empire Project MGMT</h1>

<p align="center">
  <b>An affiliate network, and the tools we build to run it.</b><br>
  Offers, tracking, payouts, and the internal software that keeps all three honest.
</p>

<p align="center">
  <a href="https://github.com/orgs/EmpireAds/repositories">Repositories</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/orgs/EmpireAds/projects">Project Boards</a>
  &nbsp;&middot;&nbsp;
  <a href="#project-board">Status</a>
  &nbsp;&middot;&nbsp;
  <a href="#working-with-us">Get in touch</a>
</p>

<sub>Logo by <b>DAN</b></sub>

</div>

---

## What we build

EmpireAds runs an affiliate network and the software stack around it. Two halves:

- **The network.** Advertiser offers, publisher onboarding, conversion tracking, and payouts.
- **The tools.** Internal dashboards, reporting pipelines, fraud and quality checks, and the automation that removes manual steps from the above.

This page is the front door. The table below is the honest answer to "what is everyone actually working on right now".

---

## Project board

> Replace the placeholder rows with your real projects. One line per project, one edit to update.

| Project | Status | Owner | Now working on | Links |
| :--- | :--- | :--- | :--- | :--- |
| **Tracking Core** | 🟢 Live | @owner | Postback retry queue | [repo](#) · [board](#) |
| **Partner Dashboard** | 🔵 Beta | @owner | Invite-only rollout, feedback pass | [repo](#) · [board](#) |
| **Payouts Engine** | 🟡 Building | @owner | Multi-currency support | [repo](#) · [board](#) |
| **Fraud Signals** | 🟠 Scoping | @owner | Deciding data sources | [repo](#) · [board](#) |
| **Offer Importer** | ⚪ Maintenance | @owner | Security patches only | [repo](#) · [board](#) |
| **Legacy Reporting** | 🔴 Paused | @owner | Blocked on Tracking Core v2 | [repo](#) · [board](#) |

**Last reviewed:** _set a date here and update it whenever you touch this table._

---

## Status legend

A status is a promise, not a mood. Each one has a rule that has to be true before a project can wear it, which is what stops everything quietly drifting into a permanent "Building".

| Status | Means | Only if this is true |
| :--- | :--- | :--- |
| 🟠 **Scoping** | We are deciding what to build | An open issue describes the problem, no implementation work has started |
| 🟡 **Building** | Active development | Someone committed code in the last two weeks |
| 🔵 **Beta** | Real users, limited blast radius | Deployed, in use by a known group, breaking changes still allowed |
| 🟢 **Live** | In production, depended on | Monitored, on-call covered, breaking changes need a migration plan |
| ⚪ **Maintenance** | Stable, no new features planned | Security and bug fixes only, still supported |
| 🔴 **Paused** | Stopped on purpose | The reason and the unblocker are written in the "Now working on" column |

Anything that cannot honestly hold its status gets moved down, or moved to **Paused** with a reason. A stale board is worse than no board, because people trust it and act on it.

---

## How work is tracked

The table above is the summary. The detail lives in GitHub.

- **Boards.** Every active project has a board under the org [Projects](https://github.com/orgs/EmpireAds/projects) tab. That is the source of truth for day to day work, not this page.
- **Issues.** Work starts as an issue in the project's own repo. If the work spans repos, it goes in the coordinating repo and links out.
- **Branches.** Branch from `main`, name it after the issue, open a pull request early as a draft. Small pull requests get reviewed, large ones get postponed.
- **Definition of done.** Merged to `main`, deployed, and the issue closed by the pull request. Not merged. Not "done locally".

### Labels we use

| Label | Meaning |
| :--- | :--- |
| `bug` | Something is broken in production |
| `feature` | New capability |
| `chore` | Dependencies, tooling, cleanup |
| `blocked` | Cannot progress, the blocker is named in the thread |
| `needs-decision` | Waiting on a human call, not on code |

---

## Working with us

**Want something built or changed?** Open an issue in the relevant repo. A good request states the problem and the impact, not the solution. "Publisher payouts take three days to reconcile" gets a better answer than "add a CSV export button".

**Found a bug?** Open an issue with what you did, what you expected, and what happened instead. Include the timestamp and any IDs. Do not put credentials, API keys, or partner data in a public issue.

**Security issue?** Do not open a public issue. Use the contact below and we will get you a private channel.

**New to the org?** Read this page, then find your project's board, then pick up something labelled `feature` or `chore` to get your first pull request through the process.

---

## Contact

| Reason | Where |
| :--- | :--- |
| Partnerships and offers | _add email_ |
| Publisher and affiliate support | _add email_ |
| Security disclosure | _add email_ |
| Internal team | _add channel_ |

<div align="center">
<sub><b>EmpireAds</b> · Logo by <b>DAN</b></sub>
</div>
