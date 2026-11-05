---
name: meeting-follow-up
description: Turn a meeting transcript or AI summary into shareable meeting notes, decisions, actions and a follow-up draft.
---

# Meeting follow-up

## When to use
After any meeting with actions, or when I ask for meeting notes.

## Reads
- The meeting transcript in Zoom. If there's no transcript, the Zoom AI summary. If there's neither, ask me for my notes.
- Linear

## Steps
1. Find the meeting I named. If I didn't name one, use my most recent meeting and tell me which one you picked.
2. Pull the transcript. If there is none, pull the AI summary and say the notes come from a summary, not a transcript.
3. List every action agreed, with who agreed to it and by when. From a transcript, quote it with a timestamp. From a summary, link the summary.
4. Mark any action with no owner or no date as "not agreed".
5. Write the meeting notes in the format below, show them to me and wait.
6. For each action I approve, create a Linear task with the owner, the due date and a link to the transcript or summary.
7. For each "not agreed" action, draft a one-line message asking who owns it.

## Meeting notes format

```
# [Meeting name]: [date]
Attendees: [names] · Source: [Zoom link to transcript or summary]

## Summary
Three sentences at most: what we met about and where we landed.

## Decisions
- [Decision], made by [who]

## Action items
| Action | Owner | Due |
|---|---|---|
| [Action] | [Name] | [Date] |

## Not agreed yet
- [Action]: needs an owner or a date

## Open questions
- [Question], for [who]
```

When working from a transcript, add a Source column to the action items table with the timestamp and a short quote.

## Output
Meeting notes I can share with my team, Linear tasks with owners, and draft messages for the open actions.

## Rules
- Every action needs an owner and a due date. If either is missing, it goes under "Not agreed yet".
- Never invent a name, date or decision.
- Leave out anything I wouldn't say to the person's face.
- Show me the notes. Never send them or the messages.
- Don't copy the transcript or a summary into Notion. It stays in Zoom.
