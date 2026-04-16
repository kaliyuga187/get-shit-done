# Get Shit Done (GSD) — Monetization Strategy

## Product Overview
npm CLI tool (v1.28.0) for AI meta-prompting and context engineering. 57 commands that help AI assistants reliably build complete features by managing context windows, breaking work into atomic tasks, and orchestrating sub-agents. Supports Claude Code, OpenCode, Gemini, Codex, Copilot, Cursor, and more.

## Target Market
- **Primary**: Developers using AI coding assistants globally
- **Secondary**: Engineering teams, dev agencies, AI tool builders
- **Distribution**: Already published on npm as `get-shit-done-cc`, with Japanese and Chinese translations

## Revenue Streams

### 1. Freemium CLI + Pro Tier

| Tier | Price | Includes |
|------|-------|----------|
| **Free** | $0 | Core 30 commands, basic context management |
| **Pro** | US$19/mo or US$149/yr | All 57 commands, priority processing, advanced orchestration, team workstreams |
| **Team** | US$49/mo per seat | Shared workstreams, admin dashboard, usage analytics, SSO |

**Implementation**: GitHub Sponsors tiers linked to license key validation in CLI
**Revenue Target**: US$3,000/mo by Month 12

### 2. Ebook: "Context Engineering for AI Coding Assistants"
- **Price**: US$39
- **Platform**: Gumroad
- **Content**: The methodology behind GSD — meta-prompting, spec-driven development, context window management, wave-based parallel execution
- **Revenue Target**: US$800/mo

### 3. Course: "Context Engineering Masterclass"
- **Price**: US$79
- **Platform**: Gumroad + Teachable
- **Duration**: 6-8 hours
- **Content**: Deep dive into GSD's architecture, hands-on workshops building features with context engineering
- **Revenue Target**: US$1,500/mo

### 4. Consulting: AI-Assisted Development
- **Rate**: A$250/hr or US$150/hr
- **Service**: Help teams adopt AI coding workflows with GSD
- **Target**: Engineering teams at mid-size companies
- **Revenue Target**: US$2,000/mo (retainer clients)

### 5. Affiliate Revenue
- Cloud hosting affiliates (Vercel, Railway, Supabase referral programs)
- AI API affiliates (if available)
- **Revenue Target**: US$300-800/mo

## Go-Live Checklist

### Week 1-2
- [ ] Set up GitHub Sponsors with Pro/Team tiers
- [ ] Implement license key validation in CLI
- [ ] Create landing page / docs site for GSD Pro
- [ ] Write announcement blog post

### Week 3-4
- [ ] Launch Pro tier
- [ ] Post on Hacker News, r/programming, Dev.to, X/Twitter
- [ ] Begin writing Context Engineering ebook
- [ ] Create demo videos showing GSD workflow

### Month 2-3
- [ ] Publish ebook on Gumroad
- [ ] Begin recording Masterclass course
- [ ] Launch consulting page on personal website
- [ ] Reach out to AI tool YouTubers for reviews

## Key Implementation Files
- `package.json` — npm package at v1.28.0
- `src/commands/` — 57 command files
- `CHANGELOG.md` — 1847-line change history
- `README.md` — Primary documentation (also translated to JP/CN)
