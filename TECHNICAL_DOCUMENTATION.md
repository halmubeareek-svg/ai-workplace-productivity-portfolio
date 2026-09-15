[![Docs](https://img.shields.io/badge/DOCS-Technical%20Documentation-0B2545?style=flat-square)](../README.md)

# Technical Documentation

This document describes how this repository is organized, the conventions used across all files, and exactly which training lab or exercise each portfolio artifact is built from.

## 1. Repository Structure

```
ai-workplace-productivity-portfolio/
│
├── README.md                          # Entry point: overview, scenario, navigation
├── CHANGELOG.md                       # Versioned history of this repository
├── .gitignore                         # OS/editor files excluded from version control
│
├── docs/
│   ├── TECHNICAL_DOCUMENTATION.md     # This file
│   └── VERSION_CONTROL.md             # Git workflow & commit conventions
│
├── 01-prompt-engineering/
│   ├── prompt-library.md              # Section 1a — 6 reusable C.A.R.E./R.C.T.O. prompts
│   └── before-after-example.md        # Section 1b — weak vs. improved prompt
│
├── 02-writing-workflow/
│   └── professional-writing-example.md   # Section 2 — 4-Step Drafting Workflow
│
├── 03-information-workflow/
│   └── information-processing-example.md # Section 3 — notes → decision-ready brief
│
├── 04-planning-workflow/
│   └── planning-example.md            # Section 4 — Planning Chain (Goal→Tasks)
│
├── 05-verification/
│   └── verification-checklist.md      # Section 5 — verification protocol, applied
│
├── 06-responsible-ai/
│   └── responsible-use-checklist.md   # Section 6 — six concepts + Green/Amber/Red
│
└── 07-integration-plan/
    └── personal-integration-plan.md   # Section 7 — future AI usage plan
```

This mirrors the folder structure required by the L0-FGP Final Course Project Guide exactly (numbered `01`–`07` folders, one Markdown artifact per section).

## 2. File & Naming Conventions

- All content is plain **Markdown (`.md`)** — no build step, no dependencies, renders natively on GitHub.
- Folder names are zero-padded and numbered (`01-`…`07-`) so they sort in reading order in any file browser.
- File names are lowercase, hyphen-separated, and describe the artifact, not the section number (e.g. `planning-example.md`, not `section4.md`) — this keeps links stable even if a section were renumbered.
- Every section file starts with a badge banner identifying its section number and topic, and ends with a **navigation footer** (`⬅ Back | 🏠 README | ➡ Next`) linking to the previous file, the README, and the next file — so the repository can be read start-to-finish without leaving GitHub's file viewer.

## 3. Design System

A consistent 3-color palette (matching the L0-FGP course branding) is used across every badge, table, and classification marker in this repository:

| Color | Hex | Meaning |
|---|---|---|
| 🔵 Navy | `#0B2545` | Structure, frameworks, primary headings |
| 🟢 Green | `#1F8A4C` | Workflows in motion / "safe to share" |
| 🟡 Gold | `#E8A33D` | Verification and caution / "needs review" |

Badges are generated via [shields.io](https://shields.io) using this exact palette. Where GitHub natively renders a color (hex codes inside backticks, e.g. `` `#1F8A4C` ``), it is used for the Green/Amber/Red classification in Section 6 so the swatch is a real rendered color, not just an emoji.

## 4. Lab-to-Portfolio Traceability Matrix

Every artifact in this repository is reused and adapted from a specific L0-FGP lab or exercise, per the Final Course Project Guide's mapping table. This is the same mapping, applied to the Business Consultant scenario:

| Day | Lab / Exercise | Skill Practiced | Portfolio Artifact |
|---|---|---|---|
| 1 | "The Vague Prompt Rescue" lab | C.A.R.E. structuring | [`01-prompt-engineering/prompt-library.md`](../01-prompt-engineering/prompt-library.md) (Prompt 1) & [`before-after-example.md`](../01-prompt-engineering/before-after-example.md) |
| 1 | R.C.T.O. live demo + practice | Leading with role | [`prompt-library.md`](../01-prompt-engineering/prompt-library.md) (Prompt 2) |
| 1 | Few-Shot Prompting exercise | Examples for recurring formats | [`prompt-library.md`](../01-prompt-engineering/prompt-library.md) (Prompt 3) |
| 1 | Executive Writing (4-Step Workflow) | Draft → Verify → Refine → Sign-off | [`02-writing-workflow/professional-writing-example.md`](../02-writing-workflow/professional-writing-example.md) |
| 1 | Prompt Starter Kit (EOD deliverable) | Collecting reusable prompts | [`prompt-library.md`](../01-prompt-engineering/prompt-library.md) (full table) |
| 2 | "Messy Notes → Decision-Ready Brief" lab | Summarizing / synthesizing | [`03-information-workflow/information-processing-example.md`](../03-information-workflow/information-processing-example.md) (Part 1) |
| 2 | Extraction & Action Items exercise | Notes → action-item table | [`information-processing-example.md`](../03-information-workflow/information-processing-example.md) (Part 2) |
| 2 | Weak vs. Structured Planning Prompt | Goal → Mechanisms → Phases → Tasks | [`04-planning-workflow/planning-example.md`](../04-planning-workflow/planning-example.md) |
| 2 | AI Productivity Workflow Pack (EOD deliverable) | Saved workflows by task type | Sections 3 & 4 (linked to each other) |
| 3 | "One Decision, Six Questions" activity | Six Responsible-AI concepts | [`06-responsible-ai/responsible-use-checklist.md`](../06-responsible-ai/responsible-use-checklist.md) |
| 3 | "Classify These 9 Items" activity | Green/Amber/Red classification | [`responsible-use-checklist.md`](../06-responsible-ai/responsible-use-checklist.md) |
| 3 | Verification Protocol / Scenario Lab | Identify → Criteria → Test → Confirm | [`05-verification/verification-checklist.md`](../05-verification/verification-checklist.md) |
| 3 | "Building Your Integration Plan" work time | Future AI use planning | [`07-integration-plan/personal-integration-plan.md`](../07-integration-plan/personal-integration-plan.md) |

## 5. Cross-Section Data Traceability

To demonstrate genuine applied verification rather than isolated examples, one figure is deliberately traced across three sections:

`~12% budget overrun estimate` → introduced in raw notes (**Section 3**) → run through the full verification checklist (**Section 5**) → classified for sharing sensitivity (**Section 6**).

## 6. Dependencies

None. This is a documentation-only repository — no build tools, package managers, or runtime are required to view or use it.

---
⬅ [Back to README](../README.md) &nbsp;|&nbsp; ➡ [Next: Version Control](VERSION_CONTROL.md)
