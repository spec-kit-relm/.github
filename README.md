# spec-kit-relm/.github

Organization-wide defaults for every `spec-kit-relm` repository. GitHub applies these
automatically to any repository that does not define its own.

| Path | GitHub feature | Purpose |
|------|----------------|---------|
| `profile/README.md` | Organization profile | Landing page: what Relm is, repository map, feature flow, rule layers |
| `PULL_REQUEST_TEMPLATE.md` | Default PR template | Relm PR template (Feature ID, contracts, analyze/converge evidence) read by `sdd-gates / pr-check` |
| `ISSUE_TEMPLATE/` | Default issue forms | Bug (bugfix lane), Task (from `tasks.md`); new features are redirected to `product-specs` |
| `workflow-templates/relm-sdd-gates.yml` | Org workflow template | Shown under **Actions → New workflow** in every repo: calls the reusable SDD gates |
| `CONTRIBUTING.md`, `SECURITY.md` | Community health files | Lanes, gates, and data-handling rules |

## When to change what

- The **PR template** is a copy of `speckit-platform/templates/repo/.github/pull_request_template.md`.
  Change it there first (the `pr-check` gate parses it), then copy it here.
- Issue forms and the workflow template follow the handbook; change them with a `lane:chore` PR
  reviewed by the SDD Guild.
