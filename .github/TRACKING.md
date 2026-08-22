# How work is tracked in this repository

This repository follows the organisation's canonical tracking structure.

**Canonical governance:** [`engineering-playbook` → `docs/governance/kartheon-tracking-structure.md`](https://github.com/is-hux/engineering-playbook/blob/main/docs/governance/kartheon-tracking-structure.md)

That document is authoritative for tracker structure across the organisation. This repository's own
conventions — build, test, layout, review — remain this repository's law.

## What that means here

- **Every open issue is on the organisation project and carries exactly one `Owner`.** Ownership is
  a field, not a sentence.
- **Issues are filed through the forms** in `.github/ISSUE_TEMPLATE/` — an issue needs an owner, a
  next action in one imperative sentence, evidence, and a source.
- **A blocker is a claim, not a state.** File it with the blocker form; a reviewer who is not you
  decides. Filing does not block anything by itself.
- **The base labels** — `operator-hold`, `blocker-claimed`, `retirement-sweep`, `bug`,
  `enhancement`, `documentation` — exist in every repository. This repository may add more; it may
  not lack these.
- **Cite by permalink, not by path.** A path is ambiguous where two files share content.

*This file is a pointer. If it disagrees with the canonical document, the canonical document wins.*
