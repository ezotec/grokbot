# Live bots

Seven bots Eric runs. Each one is a role from the stream catalogue, or a small set of them. Paste-ready descriptions are under [`roster/`](roster/).

House rules: [`AGENTS.md`](AGENTS.md).

## CoS

The one thread Eric talks to. Routes work, ranks the morning, and posts one digest.

| Role | One line |
|---|---|
| [`Chief of Staff`](roster/chief-of-staff.md) | The one bot the human talks to. Routes every request to the right specialist, holds who-is-working-on-what, and is the only thread that pings the human. |
| [`Inbox Manager`](roster/inbox-manager.md) | Ranks overnight email, Slack and meeting invites into an action order every morning, drafts replies to the routine ones, and only escalates what matters. |
| [`Daily Digest`](roster/daily-digest.md) | Reads the newsletters, podcasts and feeds you subscribed to and can't keep up with, and posts one summary a morning where you'll see it. |

## Spectrum SE

Account context, product truth, battle cards, and the brief before a call.

| Role | One line |
|---|---|
| [`Account Specialist`](roster/account-specialist.md) | A dedicated bot with the full context of one account: plan, stakeholders, renewal, signals, promises. Updates the account plan after every call and flags what needs you. |
| [`Technical Expert`](roster/technical-expert.md) | Answers "how does the product actually do X" from the codebase, via cloud agents, and rephrases it for a customer — without leaking IP. |
| [`Battle Card Writer`](roster/battle-card-writer.md) | Combines the competitor bot's hands-on findings with the technical expert's codebase truth into short, SE-ready battle cards: competitor claim vs. our reality. |
| [`Call Prep`](roster/call-prep.md) | 15–20 minutes before a call (or the night before), hands you who's on it, what happened last time, their usage, what shipped since, a suggestion, and any bug on their site to open with. |

## Writing Assist

| Role | One line |
|---|---|
| [`Voice`](roster/voice.md) | Learns how you actually write from what you actually sent — filtered, weighted to recent and successful — and drafts everything external in that voice, per audience. |

## Invest Advisor

| Role | One line |
|---|---|
| [`Data Scientist`](roster/data-scientist.md) | Answers data questions in plain English by writing and running the SQL against the warehouse, returns numbers and charts, and corrects the humans when they misread a chart. |

## Job Hunt

[`Recruiter`](roster/recruiter.md), flipped to the candidate side: finds the recruiters and warm contacts for a job seeker and drafts outreach.

## Shopping

| Role | One line |
|---|---|
| [`Negotiator`](roster/negotiator.md) | Lists items or requests quotes, and negotiates with counterparties inside a framework you set — floor price, walk-away rules — reporting back for anything outside it. |

## Agent Zero

| Role | One line |
|---|---|
| [`Signal Scanner`](roster/signal-scanner.md) | Scans the outside world for changes across your whole account list — funding, job posts, news, blog posts — every day, at scale, by fanning out to sub-agents. |

## How to use one

1. Copy the description block into the bot. Fill the placeholders.
2. Keep the *needs approval* list as written until it has earned trust.
3. When you correct it, add the general rule to its description. See [`AGENTS.md`](AGENTS.md).
