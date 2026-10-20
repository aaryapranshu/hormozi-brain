# Set up Hormozi Brain in Claude (3 minutes)

You'll make a Claude **Project**: a workspace where Claude always has the brain loaded. Every chat inside it answers like a Hormozi-style advisor.

## What you need
- A Claude account at [claude.ai](https://claude.ai). Projects have the most room on a paid plan (Pro, Max or Team), but try yours.

## Steps (paste-the-link version)
1. **Create the project.** Go to [claude.ai/projects](https://claude.ai/projects) → **Create project**. Name it `Hormozi Brain`.
2. **Paste one instruction line.** In the project, open **Instructions** and paste:
   `You are Hormozi Brain. Follow 00-instructions.md in project knowledge exactly, and read 01-how-to-advise.md at the start of every chat.`
3. **Add the brain from GitHub.** In **Project knowledge**, click **+** → **GitHub** → paste `https://github.com/aaryapranshu/hormozi-brain` → tick the **brain** folder → **Add files**. The first time, GitHub asks you to sign in. It's free.
4. **Start a chat inside the project** and type `/start`. It introduces itself and asks five questions about your business.

**Updates:** when we add frameworks, open the repo in your project knowledge and click **Sync now**.

**No GitHub?** Download the zip from https://hormozibrain.vercel.app/unlock, unzip it, and in step 3 upload the files from the `hormozi-brain` folder instead.

## Get the most out of it
- **Give it numbers.** "I'm at $30k/month, 4 clients, 20% close rate" gets you a real answer. "How do I grow?" gets you questions back.
- **Use the commands.** Type `/help` to see them all. The best ones to start with:
  - `/stage`: what stage you're in and the one thing to fix
  - `/offer`: build a Grand Slam Offer
  - `/teardown`: paste your offer or sales page and get it roasted
  - `/script`: a full sales call script for your offer
  - `/money-model`: design your upsells, downsells and continuity
  - `/roast`: a brutally honest review of your whole business
- **Paste real material.** Your sales page, your offer doc, an objection you got today. It works best on the real thing.

## Troubleshooting
- **It answers generically or ignores the frameworks.** Check you're chatting *inside* the project, not in a normal chat. Then check that the instructions saved.
- **It says it can't find a file.** Re-upload the files from step 3.
- **Upload limit hit.** Upload `01`, `02`, `04`, `05`, `08` and `09` first (the core), then the rest.

---
*Unofficial. Not affiliated with or endorsed by Alex Hormozi or Acquisition.com. Built by Fulcrum Labs.*
