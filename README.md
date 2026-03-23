# Ozor Skills

Agent skills for [Ozor.ai](https://www.ozor.ai) — the AI video generator for product launches and marketing.

These skills extend Claude Code, Codex CLI, and other AI coding assistants with expert knowledge for creating high-quality videos with Ozor. They follow the open [SKILL.md](https://agentskills.io) standard.

## Skills

### 🎬 ozor-video-best-practices

Expert guide for writing effective Ozor prompts. Includes prompt formulas for every common video type (product launch, explainer, social ad, feature announcement, investor update, tutorial), scene structure principles, format selection, editing workflow, and common mistakes to avoid.

**Triggers on:** "make a video", "Ozor prompt", "launch video", "explainer video", "video best practices", and more.

### 📄 ozor-doc-to-video

Converts any document (PDF, PowerPoint, blog post, README, changelog, URL) into a structured, copy-pasteable Ozor prompt. Reads the document, identifies the best video type, structures scenes, and outputs a complete prompt ready to drop into Ozor.ai.

**Triggers on:** "turn this doc into a video", "video from this PDF", "video from my pitch deck", "convert this to a video", and more.

## Installation

### Claude Code (via plugin marketplace)

```bash
# Add this repo as a marketplace source
/plugin marketplace add ozor-ai/ozor-skills

# Install individual skills
/plugin install ozor-video-best-practices@ozor-skills
/plugin install ozor-doc-to-video@ozor-skills
```

### Claude Code (manual)

```bash
# Clone and copy to your skills directory
git clone https://github.com/ozor-ai/ozor-skills.git
cp -r ozor-skills/skills/ozor-video-best-practices ~/.claude/skills/
cp -r ozor-skills/skills/ozor-doc-to-video ~/.claude/skills/
```

### npx (one-liner)

```bash
npx skills add ozor-ai/ozor-skills
```

### Other agents (Codex CLI, Cursor, Gemini CLI)

Copy the skill folders into your agent's skills directory. The SKILL.md format is universal across all agents that support the standard.

## How It Works

These are **Encoded Preference** skills — they don't call APIs or execute code. They teach your AI assistant the best practices, prompt formulas, and workflows for creating great Ozor videos. When triggered, the assistant produces structured, copy-pasteable Ozor prompts instead of giving vague advice.

## About Ozor

[Ozor.ai](https://www.ozor.ai) turns any text prompt or document into a professional, launch-ready video in seconds. It supports PDFs, PowerPoints, images, Google Docs, and URLs. Videos are rendered as animated React components at 30 FPS and export to MP4 at up to 4K.

- 🌐 [ozor.ai](https://www.ozor.ai)
- 📖 [Docs](https://www.ozor.ai/docs)
- 💰 [Pricing](https://www.ozor.ai/pricing)

## License

MIT
