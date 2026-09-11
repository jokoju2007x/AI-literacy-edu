# 생각한칸 (Saenggak-han-kan) — AI literacy for 8th graders

An AI literacy program for middle schoolers at community childcare centers in Seoul,
and the practice tool used to teach it.

**Live:** https://jokoju2007x.github.io/AI-literacy-edu/
**Tool:** https://jokoju2007x.github.io/AI-literacy-edu/lab/

---

## What this is

Low-income middle schoolers use AI less capably than their higher-income peers — not
because they can't reach a chat box, but because nobody has shown them what to ask it
for. Every childcare center we contacted said the same thing: there is almost no AI
literacy education, and one-off sessions run by outside organizations don't stick.

So this is a repeating curriculum plus a tool students keep open while they use it.

## The tool — `lab/`

`ai_literacy_lab` is a single HTML file. No install, no login, no account, no backend.
It runs on whatever laptop the center already has.

Three parts:

- **Goal checklist** — the student picks what they're trying to get from the AI before typing.
- **Prompt coach** — reads the prompt and shows what's missing before it's sent.
- **Level-up track** — visible progress, which is what keeps a 14-year-old in the seat.

Built with Claude.

> **What broke in the room:** `[fill in the real failure you saw]`
> **The fix:** `[fill in what you changed]`

That failure became session 2 of the curriculum.

## The curriculum — 170 minutes, three sessions

| Session | Content |
|---|---|
| 1 · How AI works | Enough mental model that sessions 2 and 3 make sense |
| 2 · Where AI fails | Hands-on: break it on purpose, then catch it being confidently wrong |
| 3 · Build something | Every student ships a small game or web page they can show someone |

One laptop per student, plus a printed workbook.

**Pilot:** Bijeontree Community Childcare Center, Seongbuk-gu, Seoul — October 2026

## Team

Shinhan Scholarship Foundation Impact Lab, Team 2 (5 people).
`[Your name]` — tool development and partner outreach.

## License

MIT
