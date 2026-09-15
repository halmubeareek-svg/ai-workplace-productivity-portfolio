[![Docs](https://img.shields.io/badge/DOCS-Version%20Control-0B2545?style=flat-square)](../README.md)

# Version Control (Git) — Conventions Used in This Repository

This repository follows standard Git best practices, scaled appropriately for a solo documentation portfolio.

## 1. Commit Message Convention

Commits follow the **Conventional Commits** format: `<type>: <short description>`

| Type | Used for |
|---|---|
| `docs:` | Adding or editing portfolio content (this repo is almost entirely `docs:` commits) |
| `feat:` | Adding a new section or new supporting file |
| `fix:` | Correcting an error in an existing file (a wrong mapping, a broken link, a factual slip) |
| `chore:` | Repository maintenance (`.gitignore`, folder restructuring, badge updates) |

**Example history for this repository:**
```
chore: initialize repository structure (7 sections + README)
docs: add Section 1 prompt library and before/after example
docs: add Section 2 writing workflow example
docs: add Sections 3-4 information and planning workflows
docs: add Sections 5-6 verification and responsible AI checklists
docs: add Section 7 integration plan
fix: align verification example with Section 3 output for traceability
fix: correct Green/Amber/Red classification to reference in-repo content
docs: apply 3-color badge design system across README and all sections
docs: add technical documentation and version-control guidelines
chore: add .gitignore and CHANGELOG
```

Each commit is scoped to one logical change — a single section, or a single fix — rather than one large "final version" commit, so the project's evolution stays reviewable.

## 2. Branching Strategy

For a single-author capstone submission, all work is committed directly to `main` in a **linear history**. This is intentional and appropriate at this scale: branching/PRs add process overhead without benefit when there is one contributor and no concurrent work to isolate. If this repository were extended by a team, the recommended model would be:
- `main` — always reflects the reviewed, submittable state
- `feature/section-x-name` — one short-lived branch per section or fix, merged via pull request

## 3. Tags & Releases

The submitted state of the portfolio is tagged as a release:
```bash
git tag -a v1.0.0 -m "L0-FGP capstone submission — Business Consultant portfolio"
git push origin v1.0.0
```
Any post-submission corrections increment the patch version (`v1.0.1`, `v1.0.2`, …) and are logged in [`CHANGELOG.md`](../CHANGELOG.md).

## 4. What's Excluded from Version Control

See [`.gitignore`](../.gitignore) — OS artifacts (`.DS_Store`, `Thumbs.db`) and editor/temp files are excluded so the repository only ever contains the actual portfolio content.

## 5. Recommended Workflow for Future Updates

```bash
git checkout -b docs/update-section-3
# edit files
git add 03-information-workflow/information-processing-example.md
git commit -m "docs: refresh Section 3 example with updated figures"
git push origin docs/update-section-3
# open a pull request into main, review, then merge
```

---
⬅ [Back: Technical Documentation](TECHNICAL_DOCUMENTATION.md) &nbsp;|&nbsp; 🏠 [Back to README](../README.md)
