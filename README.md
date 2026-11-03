# Manager OS

The starter kit for the AI Manager OS course. It gives your AI one place to work from: a set of instructions, a skill for each recurring part of a manager's job, and an example wiki to copy.

## What's in it

| Path | What it is |
|---|---|
| `CLAUDE.md` | The instructions your AI reads at the start of every conversation: where things live, which skill to use, and the rules |
| `.claude/skills/` | 11 skills, one per job: email triage, daily briefing, plan my week, weekly report, meeting prep, 1:1 prep, meeting follow-up, team page update, decision log, project audit, find the bottleneck |
| `example-wiki/` | The wiki for Alpha Corporation, a made-up company used in the course demos: Me, Goals, Team (7 people), Stakeholders, How we work, Decisions |

## How the pieces fit

- **This repo** holds how you work: the instructions and the skills.
- **A Claude project** is the one conversation where you talk to your AI. It reads this repo.
- **Notion** is your second brain: who you are, your goals, one page per person, your decisions.
- **Linear** (optional) is where you track work you delegate to the AI.

## Set up

1. Copy this repo to your own GitHub account (use it as a template, or fork it).
2. Create a Claude project and add your copy of this repo to it.
3. Connect Notion. Add Google Calendar, Gmail, Slack and Linear if you use them.
4. Import `example-wiki/` into Notion to see how it fits together, then replace it with your own pages, starting with Me and one team page.
5. Start the conversation: "Read CLAUDE.md and my Me page in Notion. Tell me what you know about me and what's missing."

## Make it yours

- Edit `CLAUDE.md` to match your tools and your rules.
- Change a skill when it gets something wrong, so the fix stays. Test it again in a fresh conversation.
- Add a skill when you catch yourself explaining the same job twice.

Using ChatGPT instead? The same files work: paste `CLAUDE.md` into your project instructions and upload the skills as files.

Everything in `example-wiki/` is fictional.
