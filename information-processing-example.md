[![Section 3](https://img.shields.io/badge/SECTION%203-Information%20Workflow-0B2545?style=flat-square)](../README.md) ![Tasks](https://img.shields.io/badge/Tasks-Synthesizing%20%7C%20Extracting-1F8A4C?style=flat-square)

# 🔵 Information Processing Example — Business Consultant

## Which Information Task(s) This Demonstrates, and Why

This example demonstrates two of the five information tasks: **synthesizing** (Part 1 — turning a scattered call recap into one coherent, decision-ready brief) and **extracting** (Part 2 — pulling structured action items out of the same unstructured notes). I chose these two because they are the tasks I rely on most as a consultant: a partner needs the synthesized bottom line to make a call, while the team needs the extracted table to know exactly who owes what, by when. Both use the same real, messy input below and show every step of the transformation.

## Part 1 — Raw Notes → Decision-Ready Brief

### Raw Input (unedited meeting notes)

> "Called with client Thursday. They're generally happy with progress but raised the pricing question again — need an answer by early next week or it holds up the workshop. Also flagged that the data-cleanup workstream is trending about 12% over the approved budget, not totally sure who on our side owns tracking that. Client also asked if we could move the final workshop a few days later to fit their board schedule."

### Attempt 1 — Generic Prompt (Weak)

**Prompt:** *"Summarize this."*

**Output:** "The client called on Thursday. They are happy with progress overall. They mentioned pricing, a possible budget issue, and a scheduling request for the workshop."

**Why it's weak:** flat, chronological retelling; no bottom line; reads like the raw notes, just shorter; a partner reading this still doesn't know what to *do*.

### Attempt 2 — Structured C.A.R.E. Prompt (Improved)

```
Context: You are helping prepare a status brief for the engagement partner
based on this call with the client (notes above).

Audience: Partner. They need decisions, risks, and timing — not a retelling.

Request: Provide a 3-5 bullet executive summary with a clear bottom line,
followed by risks and next steps.

Expectations: Keep it concise and action-oriented. Preserve dates, names,
and decisions exactly. Do not invent details — mark anything unclear as
[Not Specified].
```

**AI Output → Human-Reviewed Final Brief:**

> **Bottom line:** Client is satisfied with progress, but the pricing decision is now the critical path for keeping the workshop on schedule.
> - **Decision needed:** Client must confirm pricing by early next week, or the final workshop is delayed.
> - **Risk:** Data-cleanup workstream is trending ~12% over the approved budget — owner on our side is [Not Specified]; needs to be assigned.
> - **Client request:** Move the final workshop a few days later to fit their board schedule — exact new date [Not Specified], needs follow-up.
> - **Next step:** Confirm pricing with client's finance contact; assign a budget-tracking owner internally by Friday.

### Verification Pass

Before sharing the brief, I traced three claims back to the raw notes: the pricing deadline ("early next week"), the budget risk ("~12% over budget"), and the workshop reschedule request — all three matched the source, and nothing was added that wasn't actually said. The 12% figure specifically is treated as high-risk (it's a number that will shape how the partner reacts), so it also goes through the full Verification Checklist in **Section 5**, since it's a claim from this section being reused elsewhere in the portfolio.

## Part 2 — Extraction Table (Action Items)

Using the same call notes, here is the structured action-item extraction. Where the notes don't name an owner or a firm date, this is marked explicitly rather than guessed.

| Action Item | Owner | Deadline | Priority | Status |
|---|---|---|---|---|
| Confirm pricing with client's finance contact | [Consultant Name] | Early next week | High | Not Started |
| Assign owner to track data-cleanup budget | UNASSIGNED | TBD | Medium | Flagged, needs owner |
| Confirm new workshop date with client | UNASSIGNED | TBD | Medium | Not Started |

**Golden rule applied:** if the source doesn't name an owner, a deadline, or a decision, the table says so — it never guesses.

---
⬅ [Back: Writing Workflow](../02-writing-workflow/professional-writing-example.md) &nbsp;|&nbsp; 🏠 [README](../README.md) &nbsp;|&nbsp; ➡ [Next: Planning Workflow](../04-planning-workflow/planning-example.md)
