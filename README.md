# linkedin-solopreneur-skill

> A Claude skill for building your LinkedIn personal brand as an n8n / AI Automation expert.
> Powered by Justin Welsh's **Niche of One** philosophy.

---

## Install in 1 command

```bash
npx skills add ahsanishaq721/linkedin-solopreneur-skill
```

That's it. Claude now knows this skill.

---

## What this skill does

Once installed, Claude acts as your **Personal Brand & AI Agency Strategist**. It writes LinkedIn posts, strategic comments, outreach DMs, newsletter issues, and profile copy — all through the lens of Justin Welsh's 21 proven frameworks, filtered for an n8n / AI Automation audience.

---

## Requirements

- **Node.js** v18 or higher
- `npx` (comes with Node.js automatically)
- **Claude Code** installed (`npm install -g @anthropic-ai/claude-code`)

---

## Install Options

### Option 1 — Global install (works in every Claude Code session, everywhere)

```bash
npx skills add ahsanishaq721/linkedin-solopreneur-skill -g
```

Use `-g` to install globally to `~/.claude/skills/`. After this, the skill is active in **any** Claude Code session on your machine without needing to install it again per project.

### Option 2 — Project install (only in the current folder)

```bash
npx skills add ahsanishaq721/linkedin-solopreneur-skill
```

Installs to `.claude/skills/` inside your current project folder. Only active when you run Claude Code from that directory.

---

## How to use after installing

Open any terminal and start Claude Code:

```bash
claude
```

Then type any of the commands below directly in the chat:

| Command | What it does |
|---|---|
| `/post n8n workflow automation` | Writes a full LinkedIn post — trailer, meat, CTC, visual suggestion |
| `/ideate` | Generates 10 post headline ideas, tags each with style, picks top 3 |
| `/comment [paste a post here]` | Writes a spiky, specific comment that gets noticed |
| `/outreach [person name + goal]` | Writes a connection request or DM — value-first, zero pitch |
| `/profile headline` | Rewrites your LinkedIn headline using the Who-How-Result formula |
| `/profile about` | Writes your About section using PAIPS formula |
| `/newsletter [topic]` | Full newsletter draft + 3 subject lines + 5 repurpose hooks |

---

## For claude.ai (web / mobile)

The CLI installs the skill for **Claude Code** (terminal). If you want to use this skill on **claude.ai in any chat**, follow these steps:

1. Go to [claude.ai](https://claude.ai)
2. Click **Projects** in the left sidebar
3. Create a new Project — name it `LinkedIn Brand` or anything you like
4. Inside the project, click **Add content** or **Project files**
5. Download `SKILL.md` from this repo:
   ```
   https://raw.githubusercontent.com/ahsanishaq721/linkedin-solopreneur-skill/main/SKILL.md
   ```
6. Upload that file to the project
7. Every chat inside that project now has this skill active — no need to explain anything to Claude, just use the commands

---

## Uninstall

```bash
# Remove from current project
npx skills remove linkedin-solopreneur-skill

# Remove from global install
npx skills remove linkedin-solopreneur-skill -g
```

---

## Update to latest version

```bash
npx skills update linkedin-solopreneur-skill
```

---

## What's inside this repo

```
linkedin-solopreneur-skill/
├── SKILL.md                    # Main skill file — the brain
└── references/
    ├── frameworks.md           # All 21 Justin Welsh strategy frameworks
    └── templates.md            # Post, outreach, newsletter & profile templates
```

When you install this skill, Claude gets access to all three files. It loads `frameworks.md` and `templates.md` automatically when the task needs them.

---

## Built by

**Ahsan Ishaq** — [ahsomatic.com](https://ahsomatic.com)
