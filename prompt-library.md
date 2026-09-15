[![Section 1](https://img.shields.io/badge/SECTION%201-Prompt%20Library-0B2545?style=flat-square)](../README.md) ![Framework](https://img.shields.io/badge/Frameworks-C.A.R.E.%20%7C%20R.C.T.O.-1F8A4C?style=flat-square)

# 🔵 Prompt Library — Business Consultant

This library collects the reusable, structured prompts I rely on as a **Business Consultant**. Every prompt is built with either the **C.A.R.E.** framework (Context, Action, Role, Expected Output) or the **R.C.T.O.** framework (Role, Context, Task, Output Format), depending on which one fits the situation best.

| Prompt Name | Source Lab / Exercise | Workplace Task | Framework | Prompt | Expected Output |
|---|---|---|---|---|---|
| Client Timeline-Shift Update | Day 1 — "The Vague Prompt Rescue" hands-on lab | Notifying a client that a deliverable date has moved | C.A.R.E. | **Context:** Our 6-person consulting team is midway through a client engagement. The final deliverable is due soon, but we need to shift the delivery date by two weeks. **Action:** Write an email to the client explaining the timeline change and the new date. Ask them to confirm the new date works on their end. **Role:** Act as a calm, direct engagement manager who communicates with empathy and professionalism. **Expected Output:** 150 words, 3 paragraphs, professional tone, no jargon, ends with one clear next step. | See "Example Output 1" below. |
| Engagement Kickoff Brief | Day 1 — R.C.T.O. live demo + practice | Framing a new client engagement in the right professional voice from the start | R.C.T.O. | **Role:** You are an experienced management consultant leading a new client engagement. **Context:** You are kicking off a 6-week diagnostic engagement for a mid-size client, working with a 4-person client-side team. **Task:** Write a kickoff brief that sets expectations for the engagement, introduces the team, and outlines what the client should expect in week one. **Output Format:** One page, headed sections (Purpose, Team, Week 1 Expectations, How We'll Communicate). | — |
| Weekly Client Status Email | Day 1 — Few-Shot Prompting practice exercise | Recurring weekly update that must match a consistent house format | C.A.R.E. (Few-Shot) | **Context:** You send a weekly status email to the client every Friday. **Action:** Write this week's status email following the example format below exactly. **Role:** Act as the engagement lead. **Expected Output:** Match this structure — Subject: [Short, clear subject] / Hi [Client Name], / [Key update in 1–2 sentences] / [Progress this week] / [What's next] / Thanks, [Your name]. | — |
| Decision-Ready Executive Brief | Day 2 — "Messy Notes → Decision-Ready Brief" lab | Turning messy client meeting notes into a brief a partner can act on | C.A.R.E. | **Context:** You are helping prepare a status brief for the engagement partner from this week's client meeting notes (pasted below). **Action:** Provide a 3–5 bullet executive summary that leads with the bottom line, then risks, then next steps. **Role:** Act as a senior consultant preparing materials for a partner review. **Expected Output:** Keep it concise and action-oriented. Preserve all dates, names, and decisions exactly as given. Do not invent details — mark anything unclear as [Not Specified]. | See "Example Output 2" below. |
| Action-Item Extraction Table | Day 2 — Extraction & Action Items exercise | Converting call notes into an assignable action-item table | C.A.R.E. | **Context:** These are raw notes from a client status call. **Action:** Extract every action item, decision, deadline, risk, and open question mentioned. **Role:** Act as a detail-oriented engagement coordinator. **Expected Output:** A table with columns Action Item, Owner, Deadline, Priority, Status. If the owner or deadline is not stated, write "UNASSIGNED" or "TBD" — never guess. | — |
| Phased Engagement Plan | Day 2 — Planning & Work Organization (Weak vs. Structured Planning Prompt practice) | Structuring a new advisory offer into an executable plan | C.A.R.E. | **Context:** Our firm wants to launch a new fixed-fee "Financial Health Diagnostic" service for SME clients within 6 weeks, with a 3-person team and no dedicated budget. **Action:** Build a phased plan that breaks this goal into mechanisms, phases, and specific tasks, and note dependencies, owners, deadlines, and risks for each task. **Role:** Act as an experienced program manager. **Expected Output:** Phases with tasks underneath each, and one owner/deadline/dependency per task. | — |

*This library also reflects the collecting habit built through the Day 1 end-of-day Prompt Starter Kit deliverable — these six prompts are the ones I kept and refined afterward.*

## Example Output 1 — Client Timeline-Shift Update

> Subject: Engagement Timeline Update — 2-Week Extension
>
> Hi [Client Name],
>
> After reviewing our progress and current findings, we've determined that we need to shift our final deliverable date by two weeks. This additional time will help us deliver a stronger, more rigorous set of recommendations.
>
> Our new delivery date will be Friday, [date]. This change only affects the final report; all interim check-ins remain on schedule.
>
> Please let me know by [date] if this shift creates any conflicts on your end. Thank you for your flexibility — we're using this time to make the final deliverable even stronger.
>
> Best,
> [Consultant Name]

## Example Output 2 — Decision-Ready Executive Brief

> **Bottom line:** The engagement is on track, but the client's pricing decision is now the critical path — it needs a decision by Thursday or the final workshop slips a week.
> - **Decision needed:** Client must confirm pricing tier by Thursday to keep the workshop on schedule.
> - **Risk:** Contractor budget on the data-cleanup workstream may be over — owner not yet confirmed [Not Specified].
> - **Next step:** Follow up with the client's finance lead today; assign a contractor-budget owner by end of week.

---
⬅ [Back to README](../README.md) &nbsp;|&nbsp; ➡ [Next: Before/After Example](before-after-example.md)
