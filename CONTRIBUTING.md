# Contributing

Thanks for wanting to make this list more surprising (and more correct).

## The one hard rule

**No source, no fact.** Every fact needs at least one link to a source a skeptical reader would accept.

Good sources, roughly in order of preference:

1. **Primary sources**: the paper (arXiv, journal, conference), the company's own blog or system card, the court ruling, the official dataset or report.
2. **Reputable reporting**: established news outlets (Reuters, AP, BBC, CBC, The Guardian, NYT, etc.) or specialist outlets (MIT Technology Review, Nature news, ABA Journal).

Not accepted on their own: social media threads quoting other threads, AI-generated summaries, content farms, or "everyone knows this".

## What makes a good fact

- **Surprising.** A curious non-expert should go "wait, really?"
- **True, precisely.** Keep the numbers exactly as the source states them. If it's an estimate, say "estimated". If it depends on time, include the date.
- **Durable.** Avoid "the newest model can..." claims that go stale in weeks. Anchor to a date or a specific named model instead.
- **Short.** A punchy one-line hook (written as the heading), then 2–3 plain-English sentences. Put any longer backstory in a `<details>` block.

## Format

```markdown
### N. Punchy one-line hook.
Two or three sentences explaining what happened, with the key number and date.

📎 Source: [Who, "Title" (Date)](https://link)
```

## How to suggest a fact

- **Easiest:** open an issue using the **New fact** template. Paste the hook, the explanation and the source link.
- **Pull request:** fork the repo, add your fact to the right category in `README.md`, renumber if needed, update the counts in the table of contents and the badge, and open a PR.

## Corrections

Found a broken link, a revised number, or something that's just wrong? Please open an issue or PR with the correct source. Corrections are the most valuable contribution of all.
