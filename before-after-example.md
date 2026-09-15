[![Section 1](https://img.shields.io/badge/SECTION%201-Before%2FAfter-0B2545?style=flat-square)](../README.md) ![Framework](https://img.shields.io/badge/Framework-C.A.R.E.-1F8A4C?style=flat-square)

# 🔵 Before/After Example — Business Consultant

This example shows the real impact of structuring a prompt with **C.A.R.E.** instead of leaving it vague, using a common consulting task: telling a client that a deliverable date has shifted.

## Before

**Weak prompt:**
```
Write an email about the deadline change.
```

**Initial Result (weak output):**
> Subject: Deadline Change
>
> Hi [Client],
>
> I wanted to let you know that the project deadline has changed. We will need to adjust our timeline accordingly. Please let me know if you have any questions.
>
> Best regards,
> [Consultant Name]

**Why it was weak:**
- No audience — doesn't name the client or engagement
- No context — doesn't say why the deadline shifted
- No new date, no impact, no next step
- Generic enough to apply to almost any situation

## After

**Improved prompt (C.A.R.E.):**
```
Context: Our 6-person consulting team is midway through a client engagement.
The final deliverable is due soon, but we need to shift the delivery date by two weeks.

Action: Write an email to the client explaining the timeline change and the new date.
Ask them to confirm the new date works on their end.

Role: Act as a calm, direct engagement manager who communicates with empathy
and professionalism.

Expected Output: 150 words, 3 paragraphs, professional tone, no jargon,
ends with one clear next step.
```

**Improved Result:**
> Subject: Engagement Timeline Update — 2-Week Extension
>
> Hi [Client Name],
>
> After reviewing our progress and current findings, we've determined that we need to shift our final deliverable date by two weeks. This additional time will help us deliver a stronger, more rigorous set of recommendations and reduce risk ahead of your final decision.
>
> Our new delivery date will be Friday, [date]. This change only affects the final report — all interim check-ins and working sessions remain on schedule.
>
> Please confirm by [date] whether this new date works on your end. Thank you for your flexibility — we're putting this time to good use.
>
> Best,
> [Consultant Name]

## What Improved?

- **Specific date and audience** — the client is named and a real date is set, instead of a vague "the deadline."
- **Clear reason and impact** — the client understands why the change happened and what it does (and doesn't) affect.
- **One explicit next action** — the client knows exactly what to confirm and by when.
- **Consistent, professional voice** — calm and solution-focused throughout, matching how an engagement manager should sound to a client.

---
⬅ [Back: Prompt Library](prompt-library.md) &nbsp;|&nbsp; 🏠 [README](../README.md) &nbsp;|&nbsp; ➡ [Next: Writing Workflow](../02-writing-workflow/professional-writing-example.md)
