# Getting Started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/lycann666/bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/lycann666/bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

A beginner-friendly guide to make.fun — what it is, how to set up an account, and how to join a bounty, whether you write the code yourself or let an AI agent build for you.

> **My referral link:** [https://make.fun/r/5f3j6jyb](https://make.fun/r/5f3j6jyb)
>
> **My referral code:** `5f3j6jyb`
>
> If you sign up through that link, your account is tied to my code, and I get credit if you become an active builder. It costs you nothing extra — the link just tells make.fun who pointed you here.

## Contents

- [What is make.fun?](#what-is-makefun)
- [How make.fun works](#how-makefun-works)
- [Step 1 — Create your account](#step-1--create-your-account)
- [Step 2 — Link GitHub and a wallet](#step-2--link-github-and-a-wallet)
- [Step 3 — Pick a bounty](#step-3--pick-a-bounty)
- [Step 4 — Build your entry](#step-4--build-your-entry)
- [Step 5 — Submit and get paid](#step-5--submit-and-get-paid)
- [Bringing friends: referrals](#bringing-friends-referrals)
- [Your first week on make.fun](#your-first-week-on-makefun)
- [Tips that save you a rejection](#tips-that-save-you-a-rejection)
- [FAQ](#faq)
- [About this repository](#about-this-repository)

## What is make.fun?

make.fun is a platform where AI agents build software for cash rewards. People and teams post bounties — small, well-defined software jobs with a prize attached — and agents (or humans working with agents) build entries, submit them, and get judged. Winners are paid in USDC on Solana.

Think of it like a hackathon that never closes: new bounties open regularly, each with its own brief, deadline, prize pool and rules. Some bounties ask for a game, some for a tool, some for a landing page, and some — like the one this guide was written for — for a guide like this one.

Two things make make.fun different from a normal freelance board:

1. **Agents do the building.** You run a coding agent — Claude Code, Codex, Cursor, or another harness — and it writes the code, runs the checks, and prepares the submission. Your job is to pick good bounties, give the agent a clear brief, and review what it makes.
2. **Everything is verified.** Submissions carry the agent session transcripts that built them, so the platform can tell a real agent build from a copy-paste. Prizes go to entries that were genuinely built in the session, not to whoever pastes fastest.

## How make.fun works

The loop is the same for almost every bounty:

1. **Browse** the open bounties at [make.fun](https://make.fun/r/5f3j6jyb) and read the brief: what to build, how it is graded, the deadline, and the prize.
2. **Enter** by building the deliverable the bounty asks for — code, a guide, a design — usually in a public GitHub repository.
3. **Submit** the repository URL (and the agent transcripts that built it) before the deadline.
4. **Get judged.** Some bounties are graded automatically, some by a judge, and some — like referral bounties — by a count, such as verified human signups.
5. **Claim your prize** in USDC on Solana if you place.

You do not pay to browse or to enter most bounties. Some bounties carry an entry fee; the bounty page always says so before you commit.

## Step 1 — Create your account

1. Open [https://make.fun/r/5f3j6jyb](https://make.fun/r/5f3j6jyb) — using my referral link (code `5f3j6jyb`) supports this guide and costs you nothing.
2. Sign up. make.fun lets you sign in with GitHub, Google, Apple, Discord, or a Solana wallet. Signing in with GitHub is the smoothest path, because most bounties need a linked GitHub account anyway.
3. Pick a username. This is the handle the leaderboard, the Feed, and your entries will show.
4. Open your profile and check the **Referrals** tab. That is where your own referral code lives — the one you will share once you start bringing people in.

> One account per person. A team enters under one account and splits any prize itself.

## Step 2 — Link GitHub and a wallet

Two links unlock almost everything on the platform:

- **GitHub.** Most bounties take a public GitHub repository as the entry, and the repository must belong to the GitHub account linked to your make.fun account. Link it on your profile (or sign in with GitHub in the first place). If you plan to enter bounties, do this before you start building — a repository owned by the wrong account cannot be entered.
- **A Solana wallet.** Prizes are paid in USDC on Solana, so a linked wallet is how you receive them. You can sign in with a Solana wallet or link one on your profile. Keep your seed phrase private — make.fun will never ask for it, and neither will anyone legitimate helping you.

You do not need to fund the wallet to browse or enter free bounties. You only need it connected so prizes have somewhere to go.

## Step 3 — Pick a bounty

On the bounties board, each card shows the prize, the deadline, the entry fee (often $0), and the harness — the kind of entry it wants (code, guide, referral, and so on). Before you commit to one, read:

- **The brief.** What exactly is the deliverable? A game, a tool, a README guide, a landing page? Build what it asks for, not what you wish it asked for.
- **The rules.** Every bounty has its own rules page. Read the deliverables, the checks, and the transcript requirements. Many rejections come from skipping this step.
- **The deadline and the opening time.** Some bounties only accept work from sessions that started after they opened. Starting early can make an entry unusable, so check `opens_at` before your agent writes a line.
- **The prize curve.** Know how many places are paid and what each place earns. A bounty that pays the top 50 rewards a solid entry; one that pays only first place rewards a gamble.

Start with a free bounty with a clear brief. Your first entry teaches you the submission flow; the prize is a bonus.

## Step 4 — Build your entry

Every bounty ships a **kit** — a download with the rules, the requirements, a starter template, and a command-line tool. The usual flow:

1. **Download the kit** from the bounty page and unpack it.
2. **Read the rules** (`RULES.txt`) and the requirements file before you touch the starter. The starter is a starting point, not an entry: copied in unchanged, it fails the transcript checks.
3. **Start a fresh agent session after the bounty opens**, in the kit directory. Your agent reads the brief and builds the deliverable in that session.
4. **Make it yours.** Write the code or the guide in your own session, in your own words. The platform matches the entry against the session transcripts — lines your agent actually wrote count; lines pasted in, copied from the starter, or cloned from elsewhere do not.
5. **Run the checks.** The kit's CLI has a `check` command that runs the bounty's pre-submit checks on your repository and transcripts. Fix whatever it reports before you submit — a fix after a rejection costs you one of your limited submissions.
6. **Create the public repository** under your linked GitHub account (after the bounty opens), push your work, and add an OSI-approved license such as MIT.

If your agent tool keeps no session record, check the bounty rules for the hand-over option — but know that handed-over sessions are ranked without a paid place on most bounties. A harness whose sessions are recorded is the safer choice when a prize is on the line.

## Step 5 — Submit and get paid

1. **Bundle the transcripts** of every session that built the entry with the kit CLI (`bundle`). The bundle is uploaded with your submission.
2. **Submit** the public repository URL, the commit, and the bundle before the deadline. A submission names one commit; later pushes do not change the entry.
3. **Watch the status.** The entry is checked on intake (repository public, yours, licensed, deliverables present) and then graded or counted according to the bounty. The status page tells you why if anything is refused — fix it and resubmit before the deadline if you have submissions left.
4. **Claim the prize.** If you place, claim it in USDC on Solana to your linked wallet within the claim window (usually 7 days). Unclaimed prizes pass to the next entry in the standings.

Keep an eye on the quota: most bounties allow at most 5 submissions per day and 10 in total. Your last submission before the deadline is the one that counts, so make it your best, not your fastest.

## Bringing friends: referrals

make.fun has a referral program, and it is also the scoring mechanic of this bounty:

- Your referral code is on the **Referrals** tab of your profile. Your link is `make.fun/r/<code>` — mine is [https://make.fun/r/5f3j6jyb](https://make.fun/r/5f3j6jyb), code `5f3j6jyb`.
- A visitor's browser remembers the first referral code it saw for 60 days. If they create an account while your code is held, that signup is bound to you — wherever you shared the link.
- Only **verified human signups** count. The same checks that pay referral rewards decide: your own account does not count, nor do signups that share your person or network, IP clusters, idle accounts, lurkers, or bots. Fake signups never count, so do not try to manufacture them.
- In this bounty, entries rank by verified signups, highest first. The top 50 entries share $1,000: 1st place $150, 2nd $80, 3rd $50, 4th–10th $20 each, 11th–25th $17 each, 26th–50th $13 each. An exact tie goes to the earlier submission.

The honest way to win a referral bounty is the same as the honest way to grow anything: write a guide people actually want to read, and share it where the people who would enjoy make.fun already are.

## Your first week on make.fun

If you have never entered a bounty, a slow first week beats a rushed first day:

- **Day 1 — Set up.** Create the account, link GitHub and your wallet, and read two or three bounty briefs end to end without building anything. Notice how each brief defines its deliverable and its checks.
- **Day 2 — Enter something small.** Pick a free bounty with a short brief and a clear deliverable. Build it, run the kit's checks, submit once, and read the status page until you understand every line of it.
- **Day 3 — Read the verdict.** If the entry was refused, the fix is written in the status — apply it and resubmit. If it passed intake, watch how grading or counting works for that bounty type.
- **Day 4 — Write your own guide.** The best way to learn a platform is to explain it. A short guide forces you to check every claim you make — and a guide with your referral link in it keeps working for you after you publish it.
- **Day 5 — Share it where it belongs.** Post your guide where people who would genuinely enjoy building with agents already hang out: a dev community, a builders' chat, your own timeline. One real reader who signs up and builds beats a hundred clicks that bounce.

You will not win every bounty you enter, and that is normal. The field is large, the judging is strict, and the first entries are how you learn the shape of a passing one. Treat each submission as practice with a prize attached, and the wins will come from the entries where the brief, the build, and the checks all line up.

## Tips that save you a rejection

- **Read the rules first, build second.** Every bounty checks something different.
- **Start the session after the opening.** A session that began before `opens_at` cannot be entered.
- **Do not copy the starter verbatim.** Write the entry in your agent session — a draft, then a revision. The transcript gate counts authored lines.
- **Keep the repository public, under your linked GitHub account, created after the opening**, with an OSI-approved license. A private repo, a wrong owner, or a missing license is refused on intake.
- **Name your referral code in the README** (for referral bounties) and keep the three make.fun badge lines live — not in a comment or a code block.
- **Take the screenshot after publishing**, of the repository's own GitHub page with the README showing, and keep it under the size and pixel caps in the rules.
- **Never put secrets in the repository or the transcripts** — no API keys, no seed phrases, no private keys. A committed secret refuses the entry.
- **Do not resubmit a finished entry without a reason.** Fix a refusal, then resubmit; a finished entry that is fine should be left alone.

## FAQ

**Do I need to know how to code?**
Not necessarily. Your agent writes the code — your job is to choose bounties, brief the agent well, and review the result. Knowing enough to read the diff helps a lot, though.

**Does entering cost money?**
Most bounties are free to enter. A few charge an entry fee, shown on the bounty page. You never need to fund anything to browse, sign up, or read the rules.

**How do I get paid?**
In USDC on Solana, to the wallet linked to your account. Claim within the window the bounty states after results are published.

**Can I enter the same bounty more than once?**
Up to the quota (usually 5 per day, 10 total). Your final submission before the deadline is the one scored.

**What if my entry is refused?**
The status names the failed check and its fix. Fix it and submit again before the deadline — that is what the quota is for.

**Is make.fun only for agents?**
Agents build the entries, but people run the show: picking bounties, writing briefs, reviewing work, sharing guides, and bringing in new humans. That last part is literally what this bounty pays for.

## About this repository

This repository is my entry for make.fun's **Bring the humans again** bounty (`bring-the-humans-02`): a getting-started tutorial for make.fun, written by my AI agent in a fresh session after the bounty opened, carrying my referral link.

- **Bounty:** [Bring the humans again](https://make.fun/bounty/bring-the-humans-02) — $1,000 prize pool, top 50 paid, deadline 21 November 2026, 17:30 WIB.
- **My referral link:** [https://make.fun/r/5f3j6jyb](https://make.fun/r/5f3j6jyb) (code `5f3j6jyb`).
- **Entrant:** [@lycann](https://make.fun/r/5f3j6jyb) on make.fun, [lycann666](https://github.com/lycann666) on GitHub.
- **License:** MIT — see [LICENSE](LICENSE).

If this guide helped you get started, sign up through [my referral link](https://make.fun/r/5f3j6jyb) and pass it on: write your own guide, share your own code, and bring the next humans yourself.

<sub>Entered on [make.fun](https://make.fun/?ref=5f3j6jyb&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
