# linkedin-solopreneur-skill

> A Claude skill that turns you into a LinkedIn content machine — for any niche, any profession, any industry.
> Powered by **Justin Welsh's Niche of One** philosophy and 21 proven LinkedIn frameworks.

Works for: consultants, coaches, developers, designers, marketers, founders, lawyers, doctors, recruiters, freelancers, AI agency owners, solopreneurs, and anyone building a personal brand on LinkedIn.

---

## What this skill does

Once installed, Claude acts as your personal **LinkedIn Brand Strategist**. It knows Justin Welsh's complete system — 21 frameworks, 5 post templates, full newsletter formula, outreach scripts, and profile formulas — and applies all of it to YOUR specific niche and audience.

You just type a command. Claude does the rest.

| Command | Output |
|---|---|
| `/post [topic]` | Full LinkedIn post — trailer, body, CTC, visual suggestion |
| `/comment [paste post]` | A spiky, strategic comment that stands out |
| `/outreach [person + goal]` | Connection request + DM + follow-up DM |
| `/profile [section]` | Headline, About, Featured, or Banner copy |
| `/ideate` | 10 post headline ideas tagged by style, top 3 highlighted |
| `/newsletter [topic]` | Full newsletter draft + subject lines + repurpose hooks |

---

## Requirements

Before installing, make sure you have:

1. **Node.js v18 or higher**
   Check your version: `node --version`
   Download if needed: https://nodejs.org

2. **Claude Code** (the CLI tool from Anthropic)
   Install it: `npm install -g @anthropic-ai/claude-code`
   Verify: `claude --version`

---

## Install the skill

### Option A — Global install (recommended)

Installs the skill once. Works in **every Claude Code session** on your machine, in any folder, forever.

```bash
npx skills add ahsanishaq721/linkedin-solopreneur-skill -g
```

After this, open any terminal, type `claude`, and the skill is ready.

### Option B — Project install

Installs the skill only inside your current project folder.

```bash
cd your-project-folder
npx skills add ahsanishaq721/linkedin-solopreneur-skill
```

Only active when you run `claude` from that folder.

---

## First-time setup (required, one time only)

The skill works for any niche, so it needs to know yours before it can write anything specific.

**Step 1:** Open Claude Code in your terminal:
```bash
claude
```

**Step 2:** Set your context by typing this (fill in your details):
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

**Step 3:** Claude will confirm your context and ask if anything needs adjusting.

That's it. From this point, every command you run uses your niche, audience, and offer automatically. You never need to explain yourself again.

To update your context later, just type:
```
Update my context: [new niche] / [new audience] / [new offer]
```

---

## How to use the commands

Once your context is set, use any of these commands in your Claude Code chat:

### `/post [topic]`
Write a complete LinkedIn post on any topic.

```
/post the biggest mistake new consultants make with pricing
/post why most people misunderstand personal branding
/post a story about when I lost my best client and what I learned
/post 5 things I wish I knew before going freelance
```

Claude will output:
- The TRAILER (<=210 chars, the part above "...more")
- The MEAT (full post body)
- CTC or CTA (comment driver or action prompt)
- Visual format suggestion
- Content Matrix tag (Theme x Style)

---

### `/comment [paste the post]`
Write a strategic LinkedIn comment that gets noticed.

```
/comment [paste the full text of a LinkedIn post here]
```

Claude will write a 2-4 sentence spiky, specific comment — never hollow, never "Great post!" It will add value, extend the argument, or respectfully challenge it. Zero self-promotion.

---

### `/outreach [person name + your goal]`
Write connection request, first DM, and follow-up DM for any person.

```
/outreach [Name], [their role] at [company] — [your goal]
/outreach a career coach with 50K followers — exploring a potential collab
/outreach the founder of a startup I admire — no specific goal, just want to connect
```

Claude delivers three messages:
- Connection request (300 characters max)
- First DM (value-first, no pitch)
- Follow-up DM (new insight, zero pressure)

---

### `/profile [section]`
Rewrite any section of your LinkedIn profile.

```
/profile headline
/profile about
/profile featured
/profile banner
```

Claude applies Justin Welsh's profile architecture formula to your specific niche and context.

---

### `/ideate`
Generate 10 LinkedIn post headline ideas right now.

```
/ideate
```

Claude crosses your niche themes with 7 different content styles (Teaching, Observation, Contrarian, Prediction, Teardown, Listicle, Comparison). Tags each idea. Picks the top 3 with reasoning.

---

### `/newsletter [topic]`
Write a complete newsletter issue ready to send.

```
/newsletter why most [your audience] struggle with [core problem]
/newsletter my 3-step process for [the result you deliver]
/newsletter the truth about [industry myth or misconception]
```

Claude delivers:
- 3 subject line options (ready to A/B test)
- Full newsletter body (Problem -> Why common solutions fail -> Your solution -> Action step)
- 5 repurpose hooks for LinkedIn posts
- Friday pre-CTA post
- Sunday post-CTA post

---

## For claude.ai users (web or mobile)

The CLI installs the skill for **Claude Code** (terminal use). If you want to use this skill on **claude.ai in any chat session**, follow these steps:

1. Go to **[claude.ai](https://claude.ai)**
2. Click **Projects** in the left sidebar
3. Click **New Project** — name it something like `LinkedIn Brand`
4. Inside the project, click **Add content** or **Project files**
5. Download the skill file:
   ```
   https://raw.githubusercontent.com/ahsanishaq721/linkedin-solopreneur-skill/main/SKILL.md
   ```
6. Upload that file to the project
7. Every chat you start **inside that project** now has this skill active

You only need to do this once. All future chats in that project will have the skill automatically, and you can use all the same commands (`/post`, `/ideate`, etc.) directly in the claude.ai chat window.

---

## Manage the skill

### Check what skills are installed
```bash
npx skills list
npx skills ls -g   # global only
```

### Update to the latest version
```bash
npx skills update linkedin-solopreneur-skill
```

### Uninstall
```bash
# Project install
npx skills remove linkedin-solopreneur-skill

# Global install
npx skills remove linkedin-solopreneur-skill -g
```

---

## What's inside this repo

```
linkedin-solopreneur-skill/
├── SKILL.md                    # Main skill file — all identity, frameworks, and commands
└── references/
    ├── frameworks.md           # All 21 Justin Welsh strategy frameworks in full detail
    └── templates.md            # All post, outreach, newsletter, and profile templates
```

When you install the skill, Claude gets all three files. It loads `frameworks.md` when you ask about strategy and `templates.md` when executing content commands.
