# Get Shit Done — Monetization Strategy (DRAFT)

> Status: **draft**. Repo is a meta-prompting / context-engineering / spec-driven-development system for Claude Code, OpenCode, Gemini CLI, Codex, Copilot, Antigravity. Distributed via `npx get-shit-done-cc@latest` (npm). README displays $GSD token + Dexscreener badge — **a token already exists** for this project. MIT-licensed.

## What's monetizable

Three distinct revenue surfaces, given the existing context:

1. **npm-distributed OSS tool with paid upgrades** (Pro CLI tier).
2. **$GSD token / community-funded model** (already initiated per the README).
3. **Services / consulting on context engineering** (high-margin, low-scale).

## Revenue mechanics

### A. Pro CLI tier (primary, SaaS-shape)

Free OSS core (current state). Add a Pro tier with paid features:

| Tier | Price | Includes |
| --- | --- | --- |
| OSS | $0 | All current functionality, MIT |
| Pro | $19/mo | Cloud-synced specs, team workspaces, premium templates |
| Team | $49/user/mo | SSO, audit log, custom skill packs |

Auth via `npx get-shit-done-cc login`. License key gates Pro features without removing OSS access.

### B. $GSD token economics (existing — needs governance)

A token already exists. This adds regulatory + operator complexity:

- **Be honest in this doc**: a token that exists but has no utility wired into the product is a marketing asset (and a regulatory liability). Either tie it to product value (governance, fee discounts, retroactive airdrops for OSS contributors) or wind it down.
- If keeping: design a clear utility (e.g., $GSD holders get free Pro tier for staking 1k tokens; or $GSD pays for cloud-spec storage).
- If winding down: communicate clearly to holders. Don't ignore.
- **Don't market the token as an investment.** Securities exposure is real.

### C. Services / consulting (tertiary, high-margin)

- "Set up context engineering for your team" — $5k–$25k engagements.
- Workshops on spec-driven dev with Claude Code — $1k–$3k/seat group sessions.
- High margin but doesn't scale. Useful for funding the product work.

### D. Carbium swap-fee hook

**APPLICABLE** if $GSD is Solana-based (Dexscreener link suggests it is). Two surfaces:

- If users buy $GSD via the GSD website/UI, route swaps through Carbium with referral fee — captures fee on token purchases without raising prices.
- The openclaw `carbium-swap` skill is the canonical pattern. Wire it in if you stand up a "buy $GSD" UI.

## Sequencing

1. **Decide on the $GSD token's role first.** This is the biggest single decision; it shapes everything else.
2. **Ship the Pro tier** behind a license-key gate. Lowest-risk recurring revenue.
3. **Open consulting channel** quietly via Discord / Twitter — useful for funding while Pro tier ramps.
4. **Wire Carbium fee-capture** into any $GSD purchase UI (if token continues).

## Out of scope for this draft

- New token launches (don't pile on regulatory surface).
- VC fundraise (token + OSS tool is hard to raise on cleanly).
- Selling the OSS itself (MIT prohibits).

## Open questions for the operator

- Is $GSD active / what's its current utility? Critical first question.
- Is this repo upstream-of or a fork of `glittercowboy/get-shit-done`? (Affects branding/distribution rights.)
- npm download volume + Discord size? (Sets realistic Pro-tier revenue ceiling.)
