# UltraPay Docs

My learning log and notes for **UltraPay**, UltraShip TMS's bill payments module. No code lives here. It exists so I can see what I learned each day and so the notes are easy to find later.

## How I use this repo

- **30 minutes a day** on UltraPay. One entry per day in [LOG.md](./LOG.md), newest on top.
- If a day produces something worth keeping (a guide, a diagram, a Q&A), it goes in [notes/](./notes) and the log entry links to it.
- Open questions stay in the log until someone answers them. Then I write the answer next to the question.

## Layout

```
README.md      this file: purpose and topic tracker
LOG.md         daily entries, newest first
notes/         longer write-ups that a log entry links to
```

Rules to keep it small: one log file, no per-day files, no code, no screenshots of tenant data, and no secrets, bank numbers or customer names.

## Topic tracker

Source: the UltraPay Bill Payments user manual (version 30 Oct 2026). Tick a topic when I can explain it without looking.

| # | Topic | Manual | Done |
| --- | --- | --- | --- |
| 1 | The big picture: flow, four rules, glossary | §1 | [ ] |
| 2 | Before you can pay: checklist, permissions, settings | §2 to §4 | [ ] |
| 3 | Who gets paid: payee rules, payee bank accounts | §5, §6 | [ ] |
| 4 | Paying bills: quote, pay, pre-flight, methods, dates, fees | §7, §8 | [ ] |
| 5 | After paying: statuses, cancel/refresh/retry, accounting, returns | §10, §13 to §15 | [ ] |
| 6 | Watching payments: Payments page, details, jobs, webhooks | §11, §12, §16 | [ ] |
| 7 | Problem codes, use cases, edge cases, errors | §9, §17 to §19 | [ ] |
| 8 | API reference and security rules | §20, §21 | [ ] |

## Phases

The repo description mentions phases. Add each phase here as it starts, with a one-line goal and the date.

| Phase | Goal | Started |
| --- | --- | --- |
| 1 | Read the manual and understand the whole flow | 2026-11-02 |
