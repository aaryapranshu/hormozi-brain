# Hormozi Brain

**A business advisor that thinks like Alex Hormozi. In Claude or ChatGPT. Free.**

Give it your numbers. It finds the one thing holding you back, picks the right framework, and tells you what to do this week.

No code. No install. Paste this repo's link into Claude and it's saved.

> Unofficial. Not affiliated with or endorsed by Alex Hormozi or Acquisition.com. Built by [Fulcrum Labs](https://hormozibrain.vercel.app/#fulcrumos).

---

## Why this one is different

Most "Hormozi GPTs" are a PDF dump and a one-line prompt. They quote things he never said and give the same generic advice ChatGPT already gives.

This one was engineered:

- **Built from his public work.** The $100M books, the $100M Playbooks, the free Acquisition.com Scaling Course, and 63 of his most-watched and most recent YouTube videos (600,000+ words of transcript). We read all of it.
- **Distilled into 128 framework cards** written in plain words. Each card says *when to use it*, *how to run it*, *the numbers*, the *mistakes he calls out*, and *what to ask you first*. Small enough that Claude holds the whole brain in its head at once, so nothing gets missed.
- **Thinks before it talks.** It diagnoses your stage and your constraint first (market → offer → price → leads → sales → retention → team). It won't polish your ad copy when your offer is the problem.
- **Doesn't make things up.** 70 verified quotes, each with its source. ~40 stories, each tagged *verified*, *self-told* or *unverified*. Where his own sources disagree (they do: price-raise cadence, LTV:CAC targets, close-rate thresholds), it tells you.
- **Talks like him.** Verdict first. The math. Steps. One action. No fluff.

---

## Use it in 60 seconds

**Easiest: [https://hormozibrain.vercel.app](https://hormozibrain.vercel.app)**. Click through and pick a setup.

| Where | How | Lasts |
|---|---|---|
| **Claude Project** (recommended) | New project → paste one instruction line → **Project knowledge → + → GitHub** → paste this repo's URL → tick `brain` → **Add files**. Works on every plan, including Free. Full steps: **[SETUP-CLAUDE.md](SETUP-CLAUDE.md)** | Permanent. Click **Sync now** to get updates |
| **Any chat** (Claude or ChatGPT) | Paste: `Load the Hormozi Brain from https://hormozibrain.vercel.app/claude.md. Read it, follow it, then run /start.` Needs web access on | That chat |
| **Claude Code / Codex / Cursor** | `git clone https://github.com/aaryapranshu/hormozi-brain` and open it. `CLAUDE.md` / `AGENTS.md` wire it up | Permanent |

---

## Commands

Type these in the chat (the slash is optional):

| Command | What you get |
|---|---|
| `/start` | A 5-question intake, then your diagnosis |
| `/stage` | Which of the 10 scaling stages you're in, your one constraint, and what not to do |
| `/offer` | A Grand Slam Offer: deliverables, bonuses, guarantee, scarcity, name, price |
| `/teardown` | Paste an offer, page, ad or email and get it scored, with leaks ranked and a rewrite |
| `/price` | What to charge, the math, and how to raise prices without losing clients |
| `/money-model` | Your attraction → upsell → downsell → continuity stack, against your CAC |
| `/leads` | A 30-day lead plan using the Core Four and the Rule of 100 |
| `/outreach` | Cold and warm scripts plus a follow-up sequence |
| `/hooks` | 10 hooks across hook types, with the top 3 picked |
| `/ad` | 3 ad scripts (hook → retain → reward) plus a testing plan |
| `/script` | A full CLOSER sales call script for your offer |
| `/objection` | What the objection really means, and the exact words to say |
| `/churn` | Churn math, the likely cause and the levers, in order |
| `/hire` | Who to hire next, how to hire them and how to train them |
| `/roast` | A brutally honest scorecard of your whole business |

## Try these first

```
/stage: I run a design agency. $35k/month, 9 clients, 3 people including me.
Referrals only. Close rate ~60%. I want $100k/month.
```
```
/teardown: [paste your sales page]
```
```
A prospect just told me "it's too expensive." My offer is $4,000 for a 90-day program.
What do I say?
```

---

## What's inside

```
brain/
  00-instructions.md            ← the system prompt (paste this into the Project/GPT)
  01-how-to-advise.md           ← consult protocol, question router, command playbooks
  02-offers-and-pricing.md      ← Value Equation, Grand Slam Offer, guarantees, pricing, price raises
  03-money-models.md            ← attraction, upsell, downsell, continuity, CAC, 30-day cash
  04-leads-and-nurture.md       ← Core Four, Lead Getters, lead magnets, Rule of 100, follow-up
  05-sales-and-closing.md       ← CLOSER, every objection close, proof, script builder
  06-content-hooks-ads-brand.md ← Hook-Retain-Reward, hooks, ads, branding
  07-retention-and-ltv.md       ← churn, onboarding, activation, referrals, ascension
  08-scaling-stages-and-ops.md  ← the 10 stages, the one constraint, hiring, delegation
  09-voice-and-thinking-patterns.md ← how he thinks and talks, plus 70 sourced quotes
  10-story-bank.md              ← verified stories, plus facts it won't state
  11-go-deeper.md               ← his official free courses and books
```

## Make it yours

The brain gets sharper when it knows your business. In Claude, add a file to the Project called `my-business.md` with your offer, prices, numbers, ICP and common objections. It will apply every framework to *your* data.

---

## Want this running inside your business?

This is one advisor, trained on one person's frameworks.

**Fulcrum Labs** builds AI operating systems for founders: a full council of advisors trained on *your* calls, *your* numbers and *your* playbook, plus agents that do the follow-ups, the outreach and the admin.

No new platform. No migration. **[Talk to us →](https://hormozibrain.vercel.app/#fulcrumos)**

---

## Credits & disclaimer

All frameworks belong to Alex Hormozi and Acquisition.com. This kit is an independent, unofficial study aid. It contains summaries and short quotes for commentary and education, not his books, playbooks or courses. Get those free at [acquisition.com](https://www.acquisition.com) (links in `brain/11-go-deeper.md`). If you want his official AI, it's [ACQ AI](https://ai.acquisition.com).

"$100M" is a mark of its owner, used here only to refer to the books by name. Nothing here is legal, tax or financial advice.
