# sable

A cinematic landing page for **Sable**, a dark, premium fintech brand — huge
serif headline, a glass balance card, soft gradient light, fine grain. One
`index.html`, no dependencies, no build step.

Live at **https://sable.mojavedev.sh**.

> **Sable is not a real company.** This is a design demo built to show what an
> AI agent can ship in one step. The brand, the balances, the transactions and
> every claim on the page — including anything resembling deposit insurance —
> are invented. It is not a financial product, an offer, or a solicitation.

## How it was made

The page was written by [Claude Code](https://claude.com/claude-code) from a
single prompt, which then committed it, pushed it here, and deployed it — no
dashboard, no CI config, no YAML:

```
build a cinematic landing page for Sable, a fictional fintech — dark and
premium, huge serif headline, an animated balance card, soft gradient light,
fine grain. mobile-first, one index.html, no deps. then push it and deploy it
with mojave
```

## Deploy your own copy

```sh
curl -fsSL https://mojave.sh/install.sh | sh
mojave login
mojave deploy --repo MojaveCloud/sable
```

Or fork it and deploy the fork — a static page like this one needs no
configuration beyond an `index.html` at the repo root.

## License

MIT
