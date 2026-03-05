# SEO-AEO-GEO-Assistant Skill

Modern SEO isn’t just blue links any more. `SEO-AEO-GEO-Assistant` gives you a complete, workflow-driven system for **SEO**, **AEO (Answer Engine Optimization)**, and **GEO (Generative Engine Optimization)** so your content can win:

- Traditional rankings and featured snippets  
- Voice and assistant answers  
- Citations in AI systems like Google AI Overviews, ChatGPT, Perplexity, Claude, Gemini, and Copilot  

It’s designed for **in‑house teams** who want practical, copy‑pasteable workflows instead of theory.

---

## What’s Included

This repo contains five core files:

- **`SKILL.md`** – Main skill definition  
  Workflow-driven instructions for an AI assistant covering:
  - Content gap analysis from GSC/Ahrefs/Semrush
  - Featured snippets, SERP features, and People Also Ask
  - AEO answer patterns (voice‑ready, layered answers)
  - GEO for AI Overviews and chatbots (citation‑worthy content, llms.txt, AI visibility testing)
  - Technical SEO integration (schema, Core Web Vitals, indexability)
  - Topic clusters, content calendar prioritisation, competitor SERP analysis

- **`technical-seo-audit.md`** – Technical SEO audit template  
  A structured audit and reporting framework covering:
  - Crawlability & indexability (robots.txt, sitemaps, GSC Coverage)
  - Site architecture, depth, and internal linking
  - On‑page SEO (titles, meta descriptions, headings)
  - Core Web Vitals and page speed
  - Mobile usability, HTTPS/security, hreflang, crawl budget
  - Action plan tables with priorities and timelines

- **`geo-optimization-guide.md`** – GEO (Generative Engine Optimization) deep‑dive  
  A long‑form reference on how to get cited by AI systems:
  - What GEO is and why it matters in 2026
  - How AI search and answer engines retrieve, synthesise, and attribute content
  - Citation‑worthy content patterns (data‑backed, comparative, procedural, decision frameworks)
  - Conversational query optimisation patterns (“Should I…”, “X vs Y”, “How do I…”, “Why does…”)
  - llms.txt protocol with templates and examples
  - Platform‑specific strategies for Google AI Overviews, ChatGPT, Perplexity, Claude, Gemini
  - AI visibility testing workflows, metrics, and GEO scorecards

- **`aeo-brief-template.md`** – AEO + featured snippet content brief  
  A planning template for new content that should:
  - Target featured snippets and SERP features
  - Structure headings and FAQs for AEO
  - Capture SERP observations, data inputs, and success criteria
  - Map primary/secondary questions and multi‑format notes (web, video, social)

- **`gsc_ahrefs_clean.py`** – CSV cleaner & summariser for search data  
  A small Python script that:
  - Normalises GSC / Ahrefs / Semrush CSV exports
  - Aggregates performance by page
  - Highlights “striking distance” queries (positions ~6–20)
  - Prints clean **Markdown tables** you can paste straight into your AI workflow

---

## Who This Is For

- **In‑house SEO teams** who want repeatable, documented workflows  
- **Content strategists** planning topic clusters and briefs  
- **Technical SEOs** running audits and explaining priorities to stakeholders  
- **Teams experimenting with AI visibility** (GEO) and wanting a concrete playbook  

You don’t need to be an AI expert. The materials are written in plain, neutral English and assume familiarity with core SEO concepts.

---

## How To Use the Package

### 1. Wire It Into Your AI Assistant

Use `SKILL.md` as the “operating system” for your SEO assistant:

- Paste or load it as a skill/instruction file.  
- Call it whenever you:
  - Analyse GSC/Ahrefs/Semrush exports
  - Draft snippet‑optimised content or FAQs
  - Plan topic clusters and content calendars
  - Investigate technical SEO issues
  - Work on AI search / GEO visibility

The skill is written to be **data‑first**: when you provide real data, it treats that as the source of truth and clearly labels any inferences.

### 2. Run Technical Audits

Use `technical-seo-audit.md` as the backbone of your technical reviews:

- Duplicate the template per site or section.  
- Fill in data from GSC, crawlers, PageSpeed Insights, etc.  
- Summarise findings and action plan for stakeholders.  
- Reuse the same structure for quarterly health checks.

### 3. Optimise for AI & GEO

Use `geo-optimization-guide.md` to:

- Learn how AI tools choose which pages to cite.  
- Design citation‑worthy content structures (3C: **Credible, Clear, Current**).  
- Build and maintain your `/llms.txt` file.  
- Target conversational queries your audience actually asks.  
- Test and track AI visibility over time.

### 4. Brief New Content

Use `aeo-brief-template.md` with your writers or agencies:

- Capture intent, target questions, and SERP context.  
- Decide snippet and AEO formats up front (paragraph, list, table, HowTo).  
- Align headings with natural‑language queries.  
- Set measurable SEO/AEO success criteria.

### 5. Prep Your Data

Use `gsc_ahrefs_clean.py` before you ask the AI to analyse search data:

```bash
python gsc_ahrefs_clean.py your_export.csv > gsc_summary.md
```

Then paste `gsc_summary.md` into your AI session so you’re working from a clean, compact dataset instead of a noisy raw export.

---

## Installation & Requirements

- The Markdown files (`SKILL.md`, `technical-seo-audit.md`, `geo-optimization-guide.md`, `aeo-brief-template.md`) work in **any editor or AI environment**.
- The Python helper `gsc_ahrefs_clean.py` requires:
  - Python 3.8+  
  - Standard library only (no third‑party dependencies)

Recommended:

```bash
python gsc_ahrefs_clean.py --help
```

to see usage, then run it against a sample CSV from GSC/Ahrefs/Semrush.

---

## Versioning

- **Current version:** `2.0`  
- **Status:** Production‑ready for in‑house use  
- **Last updated:** `2026‑03‑04`  

If you adapt this for your own organisation (e.g. industry‑specific workflows, localisation), consider forking the repo and maintaining your own `VERSION` / change log.

---

## Contributing

If you’d like to:

- Suggest improvements to workflows  
- Add new templates (e.g. for specific verticals)  
- Report issues or ambiguities  

open an issue or pull request with a clear description and, where possible, concrete examples from your own use cases.

---

## License

This project is licensed under the **MIT License**. You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the terms of the MIT licence.

See the `LICENSE` file for full details (or add one if it’s not yet present).
