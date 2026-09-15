[![Section 4](https://img.shields.io/badge/SECTION%204-Planning%20Workflow-1F8A4C?style=flat-square)](../README.md) ![Chain](https://img.shields.io/badge/Chain-Goal%20→%20Mechanisms%20→%20Phases%20→%20Tasks-0B2545?style=flat-square)

# 🟢 Planning Workflow Example — Business Consultant

This example applies the **Planning Chain** (Goal → Mechanisms → Phases → Tasks, then Dependencies → Owners → Deadlines → Risks) to a real goal from a business-consulting role. Together with Section 3, this is one of the two saved workflows I kept from the Day 2 end-of-day AI Productivity Workflow Pack — this one filed under "planning," the other under "information processing."

## Weak vs. Structured Planning Prompt

**Weak prompt:** *"Create a project plan."*
Too vague — lacks context, direction, and structure, which leads to a generic, incomplete plan.

**Structured prompt (C.A.R.E.):**
```
Context: Our firm wants to launch a new fixed-fee "Financial Health Diagnostic"
service for SME clients within 6 weeks, using a 3-person team and no
dedicated additional budget.

Action: Build a phased plan that breaks this goal into mechanisms, phases,
and tasks.

Role: Act as an experienced program manager.

Expected Output: Phases with tasks underneath each; one owner, deadline,
and dependency per task.
```
This is stronger because it's specific, gives real constraints (team size, budget, timeframe), and tells the model exactly what structure to return.

## Goal

Launch a fixed-fee **Financial Health Diagnostic** service for SME clients, ready to sell, within **6 weeks** — using a 3-person team and no dedicated additional budget.

## Mechanisms

The key approaches that will get us there:
- Package our existing diagnostic frameworks into a standardized, fixed-fee offer.
- Reuse and adapt past client deliverables as templates instead of building from scratch.
- Run one pilot engagement internally (a "friendly client") before general launch.

## Phases & Tasks

**Phase 1 — Design the Offer (Weeks 1–2)**
| Task | Owner | Deadline | Dependency |
|---|---|---|---|
| Define scope, pricing, and deliverables | Partner lead | End of Week 1 | None |
| Draft the diagnostic framework and client questionnaire | Senior consultant | End of Week 2 | Scope defined |

**Phase 2 — Build the Materials (Weeks 3–4)**
| Task | Owner | Deadline | Dependency |
|---|---|---|---|
| Build client-facing deck and proposal template | Consultant | End of Week 3 | Framework drafted |
| Build internal delivery playbook and report template | Senior consultant | End of Week 4 | Framework drafted |

**Phase 3 — Pilot & Launch (Weeks 5–6)**
| Task | Owner | Deadline | Dependency |
|---|---|---|---|
| Run pilot diagnostic with one friendly client | Partner lead | End of Week 5 | Materials complete |
| Incorporate pilot feedback and finalize materials | Senior consultant | Mid Week 6 | Pilot complete |
| Officially launch the offer to the client base | Partner lead | End of Week 6 | Feedback incorporated |

## Making It Executable (Dependencies, Owners, Deadlines, Risks)

- **Dependencies:** Materials cannot be finalized until the pilot is complete; the pilot cannot start until Phase 2 materials are built.
- **Owners:** Every task above has a named owner — none are left as "the team."
- **Deadlines:** Each task has a firm date within the 6-week window, not just a phase-level target.
- **Risks:**
  - *Risk:* The pilot client cancels or delays — *Mitigation:* identify a backup pilot client in Week 1.
  - *Risk:* No dedicated budget means the team is stretched across billable work — *Mitigation:* cap non-billable planning time at 20% per person per week.

This stays a short, usable plan tied to a real business goal — not a long, abstract roadmap.

---
⬅ [Back: Information Workflow](../03-information-workflow/information-processing-example.md) &nbsp;|&nbsp; 🏠 [README](../README.md) &nbsp;|&nbsp; ➡ [Next: Verification](../05-verification/verification-checklist.md)
