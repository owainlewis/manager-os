---
name: status-update
description: Write a short status update for one project. Use when someone asks where a project is, or for each project's weekly update.
---

# Status update

## When to use
When someone asks where a project is, or once a week for each project I own.

## Reads
- The project's Linear issues: done, in progress, blocked, and their due dates
- The project's Slack channel since my last update
- My last status update for the project
- Goals in Notion, for the date and why the project matters

## Steps
1. Status first, in one line: On track, At risk or Off track, and the date we're working to. If the date moved, say from what to what.
2. Done since the last update: up to three items, each linked.
3. Next: the next two or three things, each with an owner and a date.
4. Risks: what could move the date, what it's waiting on, and who.
5. Asks: what I need from the reader. Leave this out if there's nothing.

## Output
A draft under 150 words, in this format:

```
[Project]: [On track | At risk | Off track], working to [date]
Done: ...
Next: ...
Risks: ...
Asks: ...
```

## Rules
- The reader should get the status from the first line.
- At risk means the date could move. Off track means it will move unless something changes. Say which, and why.
- Bad news goes in, plainly worded. Never round At risk up to On track.
- Every item links to its issue or message.
- Never post it. I send every update myself.
