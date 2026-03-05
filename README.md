# SEO-AEO-GEO-Assistant
Modern SEO optimization suite for AI agents. Optimize content for traditional search rankings, voice assistants, and AI citations in ChatGPT, Perplexity, Google AI Overviews, Claude, and Gemini.

**Built for in-house SEO teams** who need practical, data-driven workflows.

---

## What This Does

- Analyze content gaps from Google Search Console / Ahrefs / Semrush data
- Generate featured snippet content (paragraph, list, table, HowTo formats)
- Optimize for AI citations (ChatGPT, Perplexity, AI Overviews)
- Run technical SEO audits (crawlability, Core Web Vitals, schema markup)
- Create topic clusters and content strategies
- Test AI visibility across multiple platforms
- Generate llms.txt files for AI crawler optimization

---

## Repository Structure

```
SEO-AEO-GEO-Assistant/
├── SKILL.md                          # Entry point & orchestrator
├── skills/                           # Specialist modules
│   ├── seo-os.SKILL.md              # Core principles + routing
│   ├── serp-gap-analysis.SKILL.md   # SERP & content gap analysis
│   ├── aeo-snippet-writer.SKILL.md  # Featured snippets + AEO
│   ├── geo-visibility.SKILL.md      # GEO optimization + AI visibility
│   └── technical-seo-audit.SKILL.md # Technical SEO diagnostics
├── templates/                        # Ready-to-use templates
│   ├── technical-seo-audit.md       # Audit framework
│   └── aeo-brief.md                 # Content brief template
├── docs/                             # Reference guides
│   ├── geo-optimization-guide.md    # Complete GEO strategy
│   └── skill-usage.md               # End-to-end workflow
└── tools/                            # Helper scripts
    └── gsc_ahrefs_clean.py          # Clean GSC/Ahrefs/Semrush exports
```

---

## Installation

### Method 1: Via skills.sh (Recommended)

```bash
npx skills add kxwu222/SEO-AEO-GEO-Assistant
```

Verify installation:
```bash
npx skills list
```

Compatible with Claude Code, Cursor, Windsurf, and other skills.sh-enabled agents.

---

### Method 2: Manual Installation

**Step 1: Clone the repository**
```bash
git clone https://github.com/kxwu222/SEO-AEO-GEO-Assistant.git
cd SEO-AEO-GEO-Assistant
```

**Step 2: Install in your AI agent**

<details>
<summary>ChatGPT (Custom GPT)</summary>

1. Go to https://chat.openai.com/gpts/editor
2. Click "Create a GPT"
3. Paste `SKILL.md` contents into Instructions
4. Upload `.md` files from `skills/`, `templates/`, and `docs/` to Knowledge
5. Name it "SEO-AEO-GEO Assistant" and save
</details>

<details>
<summary>Claude</summary>

1. Create new Project in Claude.ai
2. Upload `SKILL.md` and files from `skills/`, `templates/`, `docs/`
3. Add to Custom Instructions:
   ```
   You are an expert SEO strategist with access to the SEO-AEO-GEO-Assistant 
   skill package. Follow workflows in SKILL.md. Use data-first methodology—
   never invent metrics.
   ```
4. Save the project
</details>

<details>
<summary>Gemini (Gem)</summary>

1. Go to https://gemini.google.com/gems → New Gem
2. Paste `SKILL.md` contents into Instructions
3. Upload key files: `skills/seo-os.SKILL.md`, `docs/geo-optimization-guide.md`
4. Name "SEO-AEO-GEO Assistant" and save
</details>

---

## Quick Start

### For Beginners

1. Load `SKILL.md` in your AI agent
2. Ask: *"What can you help me with using the SEO-AEO-GEO skills?"*
3. Try a simple task: *"Create a featured snippet for 'What is content marketing?'"*

### For SEO Professionals

**Complete workflow:**

```bash
# 1. Clean your search data
python tools/gsc_ahrefs_clean.py gsc_export.csv > data_summary.md

# 2. Analyze with your agent
"Using the SEO-AEO-GEO skills, analyze this GSC data [paste data_summary.md]. 
Prioritize opportunities using striking distance and high impression rules."
```

**Common use cases:**

| Task | Prompt | Skill Used |
|------|--------|------------|
| Analyze content gaps | "Analyze this GSC export and prioritize opportunities" | `serp-gap-analysis.SKILL.md` |
| Create featured snippet | "Write a featured snippet for [query]" | `aeo-snippet-writer.SKILL.md` |
| Optimize for AI citations | "Make this content citable by ChatGPT and Perplexity" | `geo-visibility.SKILL.md` |
| Run technical audit | "Audit this site for indexability issues" | `technical-seo-audit.SKILL.md` |
| Create topic cluster | "Build a topic cluster around [topic]" | `seo-os.SKILL.md` |
| Generate llms.txt | "Create llms.txt for my site" | `geo-visibility.SKILL.md` |

---

## Python Data Cleaner

**Prerequisites:**
- Python 3.8 or higher
- No additional packages required (standard library only)

**Usage:**

```bash
# View help
python tools/gsc_ahrefs_clean.py --help

# Basic usage
python tools/gsc_ahrefs_clean.py your_export.csv

# Save to markdown file
python tools/gsc_ahrefs_clean.py your_export.csv > summary.md
```

**Output includes:**
- Dataset summary (total rows, unique queries, unique pages)
- Performance by page (clicks, impressions, average position)
- Striking distance queries (positions 6-20)

**Supported exports:** Google Search Console, Ahrefs, Semrush

---

## Documentation

| File | Purpose |
|------|---------|
| **SKILL.md** | Entry point and orchestrator |
| **docs/skill-usage.md** | Complete workflow guide |
| **docs/geo-optimization-guide.md** | Deep-dive GEO strategy (29KB) |
| **templates/aeo-brief.md** | Content planning template |
| **templates/technical-seo-audit.md** | Technical audit framework |

---

## Compatible AI Agents

**Tested:**
- Cursor
- Claude Code
- ChatGPT (Custom GPT)
- Claude Projects
- Gemini Gems

Works with any agent supporting custom instructions and file attachments.

---

## Who This Is For

**Ideal for:**
- In-house SEO teams managing multiple projects
- Content strategists planning topic clusters
- Technical SEOs running audits
- Marketing teams exploring AI search visibility
- Agencies needing repeatable workflows

**Requires:** Intermediate SEO knowledge (keywords, rankings, backlinks, technical SEO basics)

---

## Updating

**Via skills.sh:**
```bash
npx skills update
```

**Manual installation:**
```bash
cd SEO-AEO-GEO-Assistant
git pull origin main
```

Re-upload updated files to your agent if needed.

---

## Troubleshooting

**Python script errors:**
- Ensure Python 3.8+ is installed: `python --version`
- Script uses standard library only, no pip installs needed
- For encoding errors, export CSV as UTF-8

**Skill not triggering:**
- Verify `SKILL.md` is loaded correctly
- Explicitly mention skills: "Using the SEO-AEO-GEO skills..."
- Check agent's context window limits

**Installation issues:**
- For `npx skills add` failures, try manual installation
- Some agents have file size limits—prioritize core files
- Check that repository is public and accessible

[Open an issue](https://github.com/kxwu222/SEO-AEO-GEO-Assistant/issues) for additional support.

---

## Contributing

Contributions welcome. To contribute:

1. Fork the repository
2. Create a branch: `git checkout -b feature/your-improvement`
3. Make changes and test with an AI agent
4. Submit pull request with clear description

---

## License

MIT License. Free to use, modify, and distribute for commercial and personal projects.

See [LICENSE](LICENSE) for details.

---

## FAQ

**Do I need coding skills?**  
No. Main skills are plain Markdown. Python script is optional for data cleaning.

**Will this work with existing SEO tools?**  
Yes. Complements existing tools—export data from GSC/Ahrefs/Semrush and analyze with the agent.

**Can I use this for client work?**  
Yes. MIT license allows commercial use.

**How often is this updated?**  
Quarterly for major updates, as-needed for bug fixes.

---

## Changelog

### v2.0 (March 2025)
- Modular skill architecture
- Complete GEO optimization coverage
- Technical SEO audit framework
- Data cleaner Python script
- Comprehensive documentation
- Industry-agnostic design

### v1.0 (February 2025)
- Initial release
- SEO + AEO coverage
- Basic snippet templates

---
