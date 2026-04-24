# linkedin-solopreneur-skill

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Built for Claude Code](https://img.shields.io/badge/Built%20for-Claude%20Code-blueviolet)](https://claude.ai)
[![LinkedIn](https://img.shields.io/badge/Platform-LinkedIn-blue)](https://linkedin.com)
[![Framework](https://img.shields.io/badge/Framework-Justin%20Welsh-orange)](https://justinwelsh.me)

> A Claude agent skill that turns you into a LinkedIn content machine — for any niche, any profession, any industry.
> Powered by **Justin Welsh's Niche of One** philosophy and 21 proven LinkedIn growth frameworks.

No more staring at a blank screen. No more generic posts nobody reads. Tell Claude your niche. Use a command. Get scroll-stopping LinkedIn content built on the exact system that took Justin Welsh to $1.7M/year at 94% margin.

---

## What it does

Once installed, Claude acts as your personal **LinkedIn Brand Strategist**. It knows Justin Welsh's complete system — 21 frameworks, 5 post templates, full newsletter formula, outreach scripts, and profile architecture — and applies all of it to YOUR specific niche and audience.

You set your context once. Then just talk naturally or use a command. Claude does the rest.

| Command | Output |
|---|---|
| `/post [topic]` | Full LinkedIn post — trailer, body, CTC, visual suggestion |
| `/comment [paste post]` | A spiky, strategic comment that stands out |
| `/outreach [person + goal]` | Connection request + first DM + follow-up DM |
| `/profile [section]` | Headline, About, Featured, or Banner copy |
| `/ideate` | 10 post headline ideas tagged by style, top 3 highlighted |
| `/newsletter [topic]` | Full newsletter draft + subject lines + repurpose hooks |

---

## Frameworks covered

All 21 Justin Welsh frameworks are built into this skill and applied to your specific niche automatically.

| Framework | What it does |
|---|---|
| **Niche of One** | Defines your unique positioning so you compete with no one |
| **Origin Mindset** | Builds a business model that protects autonomy above revenue |
| **Lifestyle First** | Optimizes for profit margin, not follower count |
| **Bleeding Neck Problem** | Anchors every post and offer to your audience's most urgent pain |
| **Service Before Product** | Sequences offers correctly — service first, product second |
| **Moneyball Consistency** | One post per day, one platform mastered first |
| **Creator Funnel** | Discovery (LinkedIn) -> Trust (Newsletter) -> Monetize (Offers) |
| **Profile Architecture** | Turns your profile into a sales page, not a resume |
| **Post Anatomy** | MEAT first, hook second — the structure every post follows |
| **PAIPS Formula** | Pain, Agitate, Intrigue, Positive Future, Solution — for story posts |
| **Content Matrix** | Crosses your themes with 7 content styles every week |
| **Play the Hits** | Tracks top posts and repurposes them systematically |
| **Newsletter Hub-and-Spoke** | One newsletter issue = 10-20 pieces of content |
| **Newsletter Formula** | 8-step, 75-minute writing system |
| **7:50 AM Strategy** | Strategic commenting on large accounts in adjacent niches |
| **De-Platforming** | Moves LinkedIn followers to your owned email list |
| **Productization Ladder** | $100 audits -> $2,500 productized service -> $3K+ retainer |
| **FITI** | Feedback -> Iteration -> Testimonials -> Increase prices |
| **Trust Tripwire** | First digital product at $50-$150 that creates repeat buyers |
| **ESAD Framework** | Eliminate, Simplify, Automate, Delegate — protect your time |
| **Strategic Networking** | Connection requests, DMs, and launch activation done right |

---

## Install

### Option A — Global install (recommended)

Works in every Claude Code session on your machine, in any folder, forever.

```bash
npx skills add ahsanishaq721/linkedin-solopreneur-skill -g
```

### Option B — Project install

Only active in the current project folder.

```bash
npx skills add ahsanishaq721/linkedin-solopreneur-skill
```

### Requirements
- Node.js v18 or higher
- Claude Code: `npm install -g @anthropic-ai/claude-code`

---

## First-time setup

The skill works for any niche. Before it writes anything, it needs to know yours.

**Step 1** — Open Claude Code:
```bash
claude
```

**Step 2** — Set your context once:
```
My context: [your niche] / [your target audience] / [your main offer]
```

Examples:
```
My context: Executive coach / mid-level managers / 1:1 coaching packages
My context: Shopify developer / e-commerce founders / done-for-you store builds
My context: Copywriter / SaaS startups / landing page copy on retainer
My context: Financial advisor / young professionals / flat-fee wealth planning
My context: HR consultant / SMB owners / fractional HR services
```

**Step 3** — Claude confirms your context. From this point, every command uses your niche automatically.

To update later:
```
Update my context: [new niche] / [new audience] / [new offer]
```

---

## How to use

After setting context, just talk naturally or use any command. No slash required — Claude activates the right framework automatically based on what you ask.

### Example prompts

```
Write me a LinkedIn post about the biggest mistake new consultants make with pricing
```

```
Give me 10 post ideas for this week
```

```
Write a comment on this post: [paste the post]
```

```
Rewrite my LinkedIn headline — I'm a UX designer helping fintech startups
```

```
Write a cold DM to a VP of Marketing at a SaaS company — I want to offer a content audit
```

```
Write a newsletter about why most solopreneurs undercharge
```

```
I want to launch a $97 product next month — write my pre-launch LinkedIn content for this week
```

Claude applies the right Justin Welsh framework to every output. Posts follow MEAT-first + PAIPS. Comments follow the 7:50 AM strategy rules. Outreach follows the value-first, zero-pitch protocol. Profile copy follows the sales page architecture.

---

## For claude.ai users (web or mobile)

1. Go to **[claude.ai](https://claude.ai)**
2. Click **Projects** -> **New Project** -> name it `LinkedIn Brand`
3. Click **Add content** -> **Upload files**
4. Download and upload `SKILL.md`:
   ```
   https://raw.githubusercontent.com/ahsanishaq721/linkedin-solopreneur-skill/main/SKILL.md
   ```
5. Every chat inside that project now has this skill active

---

## Sources

This skill is built on Justin Welsh's publicly documented LinkedIn system — his newsletter, course content, and interviews. All 21 frameworks are sourced from his published work.

| Source | Content |
|---|---|
| [The Content OS](https://www.justinwelsh.me/the-content-os) | Content Matrix, Post Anatomy, Newsletter Hub-and-Spoke |
| [The LinkedIn OS](https://www.justinwelsh.me/the-linkedin-os) | Profile Architecture, Creator Funnel, Strategic Networking |
| [Saturday Solopreneur Newsletter](https://newsletter.justinwelsh.me) | Productization Ladder, FITI, Trust Tripwire, Revenue Model |
| [Justin Welsh on LinkedIn](https://www.linkedin.com/in/justinwelsh) | PAIPS Formula, 7:50 AM Strategy, Moneyball Consistency |
| [Justin Welsh interviews & podcasts](https://www.justinwelsh.me) | Origin Mindset, Lifestyle First, ESAD Framework, De-Platforming |

---

## Repo structure

```
linkedin-solopreneur-skill/
├── SKILL.md                    # Main skill — 21 frameworks, 6 commands, quality gates
├── LICENSE                     # MIT License
├── README.md                   # This file
└── references/
    ├── frameworks.md           # All 21 frameworks in full detail with examples
    └── templates.md            # Post, outreach, newsletter, and profile templates
```

---

## Contributing

Found a Justin Welsh framework that isn't covered, or a better way to express an existing one? Open an issue or submit a PR.

When contributing, every addition must:
- Be based on Justin Welsh's publicly documented system — not paraphrased advice from other creators
- Include the framework name exactly as Justin Welsh uses it
- Apply universally to any niche — no niche-specific hardcoding
- Be tested with at least 3 different niche contexts before submitting

---

## License

MIT © [Ahsan Ishaq](https://github.com/ahsanishaq721)

## Built by

**Ahsan Ishaq**
