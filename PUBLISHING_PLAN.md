# Publishing Ozor Skills to SkillsMP — Step by Step

## What You Have

```
ozor-skills/
├── README.md              ← Repo landing page with install instructions
├── package.json           ← Enables npx install + SkillsMP discovery
├── LICENSE                ← MIT license
└── skills/
    ├── ozor-video-best-practices/
    │   └── SKILL.md       ← Best practices & prompt formulas
    └── ozor-doc-to-video/
        └── SKILL.md       ← Document-to-video converter
```

## Step 1 — Create the GitHub Repo

Option A: From the GitHub website
1. Go to https://github.com/new
2. Repo name: `ozor-skills`
3. Owner: `ozor-ai` (or your personal account)
4. Set to **Public**
5. Don't initialize with README (you already have one)
6. Click "Create repository"

Option B: From the terminal
```bash
gh repo create ozor-ai/ozor-skills --public --description "Agent skills for Ozor.ai — AI video generation"
```

## Step 2 — Push the Files

```bash
cd ozor-skills
git init
git add .
git commit -m "feat: initial ozor skills — video best practices & doc-to-video"
git branch -M main
git remote add origin https://github.com/ozor-ai/ozor-skills.git
git push -u origin main
```

## Step 3 — Add GitHub Topics (CRITICAL for SkillsMP discovery)

1. Go to your repo page on GitHub
2. Click the ⚙️ gear icon next to "About" (top right of repo)
3. In the "Topics" field, add these tags:
   - `agent-skills`
   - `claude-code`
   - `claude-skills`
   - `skill-md`
   - `skillsmp`
   - `ai-video`
   - `ozor`
   - `codex-cli`
4. Click "Save changes"

## Step 4 — Get 2+ Stars

SkillsMP filters out repos with fewer than 2 stars. Options:
- Star it yourself (that's 1)
- Ask Marcelo to star it (that's 2)
- Share on X/Twitter or the Claude community for organic stars

## Step 5 — Wait for SkillsMP Scraper

SkillsMP syncs regularly from GitHub. Once your repo is:
- ✅ Public
- ✅ Has the right topics (especially `skillsmp`, `agent-skills`, `skill-md`)
- ✅ Has 2+ stars
- ✅ Contains valid SKILL.md files

...it will be automatically indexed and appear on https://skillsmp.com

## Step 6 (Optional) — Accelerate Discovery

- Share the repo URL on X/Twitter with hashtags #ClaudeCode #AgentSkills
- Post on Reddit r/ClaudeAI or r/ChatGPTCoding
- Post in the Vercel community (Ozor is built on Next.js/Vercel — good angle)
- Add a link to the skills from ozor.ai/docs

## Step 7 (Optional) — Enable Plugin Marketplace Install

Once the repo exists, any Claude Code user can run:
```
/plugin marketplace add ozor-ai/ozor-skills
```
And then install individual skills. No extra configuration needed on your end — the `skills/` directory structure + `SKILL.md` files are all Claude Code needs.

## How Users Will Install

After publishing, users have three install paths:

### Claude Code Plugin (recommended)
```
/plugin marketplace add ozor-ai/ozor-skills
/plugin install ozor-video-best-practices@ozor-skills
```

### npx One-Liner
```bash
npx skills add ozor-ai/ozor-skills
```

### Manual Copy
```bash
git clone https://github.com/ozor-ai/ozor-skills.git
cp -r ozor-skills/skills/ozor-video-best-practices ~/.claude/skills/
```

## Verification Checklist

After pushing, confirm:
- [ ] Repo is public at github.com/ozor-ai/ozor-skills
- [ ] README renders correctly with install instructions
- [ ] Both SKILL.md files have valid YAML frontmatter (name + description)
- [ ] Topics are set (agent-skills, claude-skills, skillsmp, skill-md)
- [ ] Repo has 2+ stars
- [ ] After a few days, check https://skillsmp.com and search for "ozor"

## Next Skills to Add

When ready, you can add more skills to the same repo:
```
skills/
├── ozor-video-best-practices/
├── ozor-doc-to-video/
├── ozor-changelog-to-video/     ← future
├── ozor-landing-page-to-video/  ← future
├── ozor-social-batch/           ← future
└── ozor-prompt-optimizer/       ← future
```

Just add the new folder with a SKILL.md, commit, push. SkillsMP picks up changes automatically.
