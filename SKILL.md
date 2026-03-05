---
name: seo-aeo-geo-optimizer
description: Comprehensive SEO, AEO, and GEO optimization for in-house teams. Handles: (1) Technical SEO audits—indexability, Core Web Vitals, schema markup, crawl diagnostics; (2) Content gap analysis from GSC/Ahrefs/Semrush with data-driven prioritization; (3) Featured snippet, SERP feature, and People Also Ask optimization; (4) AI search visibility—Google AI Overviews, ChatGPT, Perplexity, Claude; (5) Competitor SERP analysis and content benchmarking; (6) Topic cluster planning and question-based content architecture. Uses data-first methodology—never invents metrics, always grounds analysis in provided analytics. Outputs include: snippet-optimized content blocks, technical audit reports, schema markup, content briefs, and strategic recommendations. Trigger this skill for any SEO strategy, content optimization, technical diagnostics, or AI visibility tasks.
---

# SEO, AEO & GEO Optimizer

## When to Use This Skill

Use this skill whenever the user mentions:

**SEO & Content Optimization:**
- **Featured snippets**, **SERP features**, **People Also Ask (PAA)**, **rich results**
- **Content strategy**, **content briefs**, **SEO outlines**, **topic clusters**
- **Question-based content** (who/what/where/when/why/how, comparisons, definitions)
- **Topic gaps**, **content planning**, **keyword research**, **intent mapping**

**Technical SEO:**
- **Technical SEO audit**, **site health check**, **indexability issues**
- **Core Web Vitals**, **page speed**, **crawl errors**
- **Schema markup**, **structured data**, **rich snippets**
- **Robots.txt**, **sitemap**, **crawl budget**

**AI Search Visibility (GEO):**
- **AI Overviews**, **ChatGPT visibility**, **Perplexity**, **Claude citations**
- **Generative Engine Optimization (GEO)**, **zero-click searches**
- **Voice search**, **conversational queries**, **AI-generated answers**
- **llms.txt**, **AI crawler optimization**

**Competitive Analysis:**
- **Competitor analysis**, **SERP benchmarking**, **content gaps vs competitors**
- **Backlink opportunities**, **ranking comparison**

**Default Assumptions:**
- Locale: **English (UK)** (neutral spelling and tone; adjust if user specifies otherwise)
- Tone: **Neutral / encyclopedic** (clear, factual, non-salesy) unless user requests different voice

---

## Core Principles

### 1. Data-First Methodology (CRITICAL)

**Never invent or assume metrics.** This skill operates on a strict data-first basis:

- **When user provides data** (GSC, Ahrefs, Semrush, analytics):
  - Treat it as the **primary source of truth** for gaps and opportunities
  - Clearly state which insights are **directly supported** by the data
  - Reference specific data points in recommendations

- **When no data is provided:**
  - Work from **generic patterns only** (common intents, typical site structures, obvious questions)
  - Explicitly label outputs as **"Inferences (not based on live data)"**
  - Never claim to have checked "current rankings" or "live SERPs"

- **What never to invent:**
  - Search volume, clicks, impressions, CTR, ranking positions
  - Traffic estimates, conversion rates, bounce rates
  - Backlink counts, domain authority scores
  - Specific SERP feature presence (unless user confirms)

- **When user mentions tools:**
  - First ask for a small table or export to ground the analysis
  - Exception: If they explicitly say they have no access to data

### 2. Output Clarity

Always prioritize:
- **Directness**: Lead with the answer, not with throat-clearing
- **Plain language**: Avoid jargon where not needed; explain specialized terms
- **Scannability**: Use headings, lists, and tables where they improve clarity

---

## 1. DISCOVERY & DIAGNOSIS

### 1.1 Content Gap Analysis (GSC/Ahrefs-Driven)

When user provides search console or keyword tool data, use this workflow:

#### Step 1: Summarize the Dataset
```markdown
### Dataset Summary
- Data source: [GSC / Ahrefs / Semrush]
- Time range: [dates]
- Scope: [full site / specific section / country-device filters]
- Metrics included: [queries, pages, clicks, impressions, positions, etc.]
```

#### Step 2: Prioritize Opportunities Using Clear Rules

State which rules you're applying:

**Striking Distance (Positions 6-20)**
- Good candidates for snippet-focused rewrites/expansions
- Target: Move from page 2 into top 5

**High Impressions + Low CTR**
- Likely needs better snippet alignment
- Fix: Improve titles, add intro answer blocks, use lists/tables

**Multiple Queries → One URL**
- Add sections/FAQs to satisfy missing intents
- Opportunity for comprehensive hub page

**Queries with No Relevant URL**
- Propose new page or dedicated section hub
- Content gap to fill

#### Step 3: Group by Question Family

Organize opportunities by intent pattern:
- **Definition / "What is..."**: Core concept explanations
- **HowTo / Process**: Step-by-step guides
- **Tools / Templates / Resources**: Downloadable assets, tool lists
- **Costs / Time / Difficulty**: Practical constraints
- **Comparisons / "X vs Y"**: Side-by-side evaluations
- **Examples / Use Cases**: Real-world applications

#### Step 4: Output Prioritized Recommendations

```markdown
### Content Gap Recommendations

#### High Priority (Quick Wins)
1. **[Page URL or new page title]**
   - Opportunity: [Striking distance / High impressions-low CTR / etc.]
   - Data support: [Specific queries, positions, CTR from dataset]
   - Action: [Rewrite intro / Add FAQ section / Create new page]
   - Expected impact: [Move to top 5 / Capture featured snippet]

#### Medium Priority
[Same format]

#### Low Priority (Long-term)
[Same format]

#### Marked as Inference (No Direct Data Support)
[Clearly separate speculative recommendations]
```

### 1.2 Competitor SERP Analysis

When user asks to analyze competitor content or SERP landscape:

#### What to Include:
1. **SERP Feature Inventory**
   - Featured snippet (type: paragraph/list/table)
   - People Also Ask questions
   - Video results
   - Image pack
   - Local pack
   - Site links
   - Related searches

2. **Top 5 Competitor Breakdown**
   For each top-ranking page:
   - URL
   - Content type (guide, listicle, comparison, tool, etc.)
   - Unique angle or positioning
   - Notable strengths (depth, visuals, authority signals)

3. **Content Gaps & Opportunities**
   - Questions competitors don't answer well
   - Formats missing from SERP (video, interactive, calculator)
   - Depth gaps (superficial vs comprehensive coverage)

**Important:** Only analyze competitors user specifically provides or asks you to search for. Don't assume competitive landscape.

---

## 2. CONTENT OPTIMIZATION

### 2A. Traditional SEO & Featured Snippets

#### Quick Start: Featured Snippet Block

When user asks a question that could trigger a featured snippet:

1. **Clarify intent silently**: Informational / Commercial / Transactional / Comparison / Navigational
2. **Produce primary snippet block** in best-fit format:
   - **Paragraph**: 40–60 words directly answering the question
   - **List**: 4–8 items for steps, pros/cons, types, tools
   - **Table**: 3–6 rows, 2–4 columns for comparisons or attributes
   - **HowTo**: Clear ordered steps for processes
   - **Video notes**: Chapter outline + 1–2 line answer per chapter

3. **Add supporting context** (optional):
   - 3–6 PAA-style follow-up questions
   - Short "When to use / Why it matters" section

#### Snippet Format Templates

##### Paragraph Snippet (40–60 Words)
```markdown
### Featured Snippet Answer (Paragraph)

[40–60 word answer that:
- Restates the core entity or concept
- Directly answers the question in the first sentence
- Avoids filler like "In conclusion" or "Overall"]
```

**Guidelines:**
- One short paragraph
- Key entity and verb early (e.g., "A content brief is...", "Internal linking helps SEO by...")
- Factual; avoid speculation unless requested

##### List Snippet (Bulleted or Numbered)
```markdown
### Featured Snippet Answer (List)

1. [Step or item 1 — 1 short sentence]
2. [Step or item 2 — 1 short sentence]
3. [Step or item 3 — 1 short sentence]
4. [Step or item 4 — 1 short sentence]
```

**Guidelines:**
- Prefer **4–8 items**
- **Numbered lists** for ordered processes; **bullets** for unordered sets
- Each item: **one sentence** when possible

##### Table Snippet (Comparisons / Attributes)
```markdown
### Featured Snippet Answer (Table)

| [Item] | [Attribute 1] | [Attribute 2] | [Attribute 3] |
|--------|---------------|---------------|---------------|
| [Row 1]| [...]         | [...]         | [...]         |
| [Row 2]| [...]         | [...]         | [...]         |
| [Row 3]| [...]         | [...]         | [...]         |
```

**Guidelines:**
- **3–6 rows** and **2–4 key columns**
- **Short, concrete values** (e.g., "Free", "Beginner", "Manual upload")
- Align columns with **real search modifiers** (price, difficulty, use case, platform)

##### HowTo / Process Snippet
```markdown
### Featured Snippet Answer (HowTo)

1. **[Step name]**: [1–2 sentences, action-focused]
2. **[Step name]**: [1–2 sentences, action-focused]
3. **[Step name]**: [1–2 sentences, action-focused]
4. **[Step name]**: [1–2 sentences, action-focused]
```

**Guidelines:**
- Begin each step with a **verb** (Define, Research, Draft, Optimize, Publish, Measure)
- Keep **4–7 steps**
- Sequence is **complete but minimal**

##### Video Snippet Notes (Chapters + Answers)
```markdown
### Video Snippet Structure

- **Hook (0:00–0:30)**: [Plain-language summary of main answer in 1–2 sentences]
- **Chapter 1 – [Subtopic] (0:30–2:00)**: [Key takeaway in 1 sentence]
- **Chapter 2 – [Subtopic] (2:00–4:00)**: [Key takeaway in 1 sentence]
- **Chapter 3 – [Subtopic] (4:00–6:00)**: [Key takeaway in 1 sentence]
- **Closing (6:00–7:00)**: [Reinforce main answer + call to action]
```

**Guidelines:**
- **Clear segment labels** that match common PAA phrasing
- Each chapter takeaway: **short and quotable**
- Can be reused as **web page headings** and **social/short-form content**

#### People Also Ask (FAQ) Blocks

Proactively add **3–6 FAQ items** that mirror People Also Ask questions:

```markdown
### Related FAQs (People Also Ask Style)

**Q: [Question 1?]**  
A: [Concise 1–2 sentence answer]

**Q: [Question 2?]**  
A: [Concise 1–2 sentence answer]

**Q: [Question 3?]**  
A: [Concise 1–2 sentence answer]
```

**Guidelines:**
- Cover **adjacent intents**: cost, time, difficulty, alternatives, examples, risks, next steps
- Answers **short enough** to be snippet-eligible
- Natural question phrasing ("Is...", "Can...", "What is the best...?")

---

### 2B. AEO (Answer Engine Optimization)

When generating snippet-optimized content, also optimize for answer engines (AI Overviews, assistants, voice search):

#### AEO Core Principles

1. **Lead with Canonical Short Answer**
   - Start each main section with **direct, self-contained answer** in ≤25 words
   - Include core entity and verb early (e.g., "A content brief is...", "A 301 redirect permanently forwards...")

2. **Structure Information for Extraction**
   - Clear, semantic headings that mirror natural language questions
   - Short paragraphs, clean lists, small tables
   - Avoid long preambles; place definitions and steps **before** stories or commentary

3. **Clarify Entities and Relationships**
   - Use consistent names for products, features, plans, concepts
   - When relevant, briefly define related entities so answer engines can map relationships

4. **Provide Layered Answers**
   - **Layer 1 – Short answer**: 1–2 sentences for voice assistant
   - **Layer 2 – Expanded answer**: 1–3 short paragraphs with nuance and edge cases
   - **Layer 3 – Supporting structures**: Lists, tables, FAQs for deeper exploration

5. **Natural Spoken-Language Style**
   - Headings/FAQ questions sound like how real people ask
   - Avoid keyword stuffing; prioritize clarity and natural phrasing

6. **Mark Uncertainty and Inferences**
   - When speculating, use "typically", "often", "in many cases"
   - Don't present inferences as hard facts, especially without data

#### AEO Answer Pattern Template

```markdown
### [Question in Natural Language]

**Short Answer (Voice-Ready, ≤25 words):**
[Direct answer with subject, verb, and key constraint]

**Expanded Clarification (1–2 Paragraphs):**
[Extra detail, variations, or conditions]

**Scannable Support (Optional):**
- [Key step, criterion, or example 1]
- [Key step, criterion, or example 2]
- [Key step, criterion, or example 3]
```

---

### 2C. GEO (Generative Engine Optimization) 🆕

Optimize for AI platforms that generate answers: Google AI Overviews, ChatGPT, Perplexity, Claude, Gemini.

#### When to Use GEO Optimization

Trigger GEO workflows when user asks about:
- **AI Overviews**, **ChatGPT visibility**, **Perplexity**, "will AI find my content?"
- **Conversational queries** (vs traditional keyword queries)
- **Thought leadership content** that AI tools should cite
- **Zero-click searches** or **AI-generated answers**

#### Core GEO Principles

**1. Citation-Worthy Content Structure**

AI models prefer content that:
- Leads with authoritative, verifiable claims
- Includes specific data points (statistics, dates, research)
- Uses clear attribution ("According to [Source]...")
- Avoids vague or promotional language

**Example:**
```markdown
❌ Weak (won't get cited):
"Our product is the best solution for content marketing."

✅ Strong (citation-worthy):
"According to a 2024 Content Marketing Institute study, 72% of B2B marketers cite lack of time as their primary content challenge."
```

**2. Conversational Query Optimization**

Optimize for how people TALK to AI (not type keywords):

**Query Patterns to Target:**
- **"Should I..."** (decision-making queries)
  - Example: "Should I use WordPress or Webflow?"
  
- **"Compare X vs Y"** or **"X vs Y for [use case]"**
  - Example: "Compare Ahrefs vs Semrush for technical SEO"
  
- **"Why does..."** (causal explanation queries)
  - Example: "Why does my site load slowly on mobile?"
  
- **"What's the best way to..."** (solution-seeking queries)
  - Example: "What's the best way to recover from a Google penalty?"

**3. llms.txt Protocol**

Create `/llms.txt` at your domain root to help AI crawlers understand your site:

```
# [Company/Brand Name]

## About
[2-3 sentence description of what you do, who you serve, your unique expertise]

## Key Resources
- [Topic/Resource 1]: [URL]
- [Topic/Resource 2]: [URL]
- [Topic/Resource 3]: [URL]
- [Topic/Resource 4]: [URL]

## Content Focus
[Primary topics you cover, separated by commas]

## Last Updated
[YYYY-MM-DD]
```

**Example:**
```
# Acme SEO Agency

## About
Acme provides technical SEO audits and content strategy for SaaS companies. We specialize in JavaScript framework SEO, international site optimization, and enterprise migrations.

## Key Resources
- Technical SEO Guide: https://acme.com/guides/technical-seo
- International SEO Checklist: https://acme.com/international-seo
- Core Web Vitals Optimization: https://acme.com/core-web-vitals
- Migration Playbook: https://acme.com/migration-guide

## Content Focus
Technical SEO, Core Web Vitals, JavaScript SEO, hreflang, site migrations, enterprise SEO, SaaS marketing

## Last Updated
2026-03-04
```

**4. Layered Answer Architecture**

Structure content in three layers for maximum AI visibility:

- **Layer 1 (AI-Ready)**: 25-50 word direct answer that can be quoted
- **Layer 2 (Context)**: 150-200 words with nuance, caveats, when it applies
- **Layer 3 (Deep Dive)**: Full article with examples, data, edge cases, alternatives

**Example:**
```markdown
## How Long Does SEO Take to Show Results?

**Quick Answer (Layer 1 - AI-Ready):**
SEO typically takes 3-6 months to show measurable results for new websites, and 1-3 months for established sites with good authority. Technical fixes can show improvements within weeks.

**Context (Layer 2):**
The timeline varies significantly based on your starting point. Brand-new domains face a "sandbox" period where Google limits visibility while assessing quality. Established sites with existing authority can rank new content much faster. Competitive industries (finance, insurance, legal) take longer than niche markets. Low-competition long-tail keywords can rank in weeks, while high-volume competitive terms may take 6-12 months or longer.

**Deep Dive (Layer 3):**
[Full article with case studies, factors that accelerate/delay results, what to track, realistic expectations by scenario, etc.]
```

#### GEO Content Templates

##### Template 1: Comparison Query (X vs Y)

```markdown
## [Product A] vs [Product B]: Which Should You Choose?

**Quick Answer (AI-Ready):**
[Product A] is better for [use case], while [Product B] excels at [different use case]. Choose [A] if you prioritize [factor 1]; choose [B] if [factor 2] matters more.

**Detailed Comparison:**

| Factor | [Product A] | [Product B] |
|--------|-------------|-------------|
| [Key criterion 1] | [Specific detail] | [Specific detail] |
| [Key criterion 2] | [Specific detail] | [Specific detail] |
| [Key criterion 3] | [Specific detail] | [Specific detail] |
| Best for | [Use case] | [Use case] |
| Price | [Specific] | [Specific] |

**When to Choose [Product A]:**
- [Specific scenario 1 with details]
- [Specific scenario 2 with details]
- [Specific scenario 3 with details]

**When to Choose [Product B]:**
- [Specific scenario 1 with details]
- [Specific scenario 2 with details]
- [Specific scenario 3 with details]

**Key Differences:**
[1-2 paragraphs explaining the fundamental differences that drive the choice]
```

##### Template 2: "Should I..." Decision Query

```markdown
## Should You [Action]?

**Quick Answer (AI-Ready):**
You should [action] if [condition]. However, [alternative] may be better when [different condition]. The decision depends primarily on [key factor].

**Context:**
[2-3 paragraphs explaining:
- When this action makes sense
- When it doesn't
- Trade-offs to consider
- Edge cases or exceptions]

**Decision Framework:**

✅ **Do [Action] When:**
- [Criterion 1 with specific example]
- [Criterion 2 with specific example]
- [Criterion 3 with specific example]

❌ **Don't [Action] When:**
- [Criterion 1 with specific example]
- [Criterion 2 with specific example]
- [Criterion 3 with specific example]

**Related Considerations:**
- [Alternative approach 1]: When to use this instead
- [Alternative approach 2]: When to use this instead
```

##### Template 3: "Why Does..." Causal Explanation

```markdown
## Why Does [Problem Occur]?

**Quick Answer (AI-Ready):**
[Problem] occurs primarily because [main cause]. Additional contributing factors include [cause 2] and [cause 3].

**Primary Causes:**

1. **[Cause 1 - Most Common]**
   - Explanation: [How this causes the problem]
   - Frequency: [How often this is the culprit]
   - How to check: [Specific diagnostic step]

2. **[Cause 2]**
   - Explanation: [How this causes the problem]
   - Frequency: [How often this is the culprit]
   - How to check: [Specific diagnostic step]

3. **[Cause 3]**
   - Explanation: [How this causes the problem]
   - Frequency: [How often this is the culprit]
   - How to check: [Specific diagnostic step]

**How to Diagnose Which Applies to You:**
[Step-by-step diagnostic workflow]

**Solutions by Cause:**
- If [Cause 1]: [Specific solution]
- If [Cause 2]: [Specific solution]
- If [Cause 3]: [Specific solution]
```

#### AI Visibility Testing

After publishing GEO-optimized content, test visibility:

**1. Google AI Overviews**
- Search your target query in Google
- Check if your content appears in the AI-generated answer
- Note: Position (cited in overview?) and whether it's a direct quote

**2. ChatGPT / Claude / Gemini**
- Ask the same question in each AI tool
- Check if your domain is cited as a source
- Test variations of the query (different phrasings)

**3. Perplexity**
- Same query in Perplexity
- Check citation in both "Quick" and "Pro" modes
- Note which sources are prioritized

**4. Track Over Time**
- Monthly spot-checks for key queries
- Document which platforms cite you (and which don't)
- Identify patterns: What content types get cited vs ignored?

**Testing Template:**
```markdown
### AI Visibility Test Results

**Query Tested:** "[Your target query]"
**Date:** [YYYY-MM-DD]

| Platform | Cited? | Position | Quote/Paraphrase | Notes |
|----------|--------|----------|------------------|-------|
| Google AI Overview | Yes/No | 1st/2nd/3rd/Not shown | Quote/Paraphrase/None | [Observations] |
| ChatGPT | Yes/No | [Position in response] | Quote/Paraphrase/None | [Observations] |
| Claude | Yes/No | [Position in response] | Quote/Paraphrase/None | [Observations] |
| Perplexity Quick | Yes/No | [Position] | Quote/Paraphrase/None | [Observations] |
| Perplexity Pro | Yes/No | [Position] | Quote/Paraphrase/None | [Observations] |
| Gemini | Yes/No | [Position in response] | Quote/Paraphrase/None | [Observations] |

**Patterns Observed:**
[What types of content get cited? What gets ignored? Any insights?]
```

---

## 3. TECHNICAL IMPLEMENTATION

For detailed technical SEO audit workflows, refer to `technical-seo-audit.md` template.

### 3.1 Schema Markup Quick Reference

Use structured data to help search engines understand your content. For full implementation guide, see the technical audit template.

**Priority Schema Types:**
- **Article**: Blog posts, guides, news articles
- **FAQPage**: FAQ sections, help pages
- **HowTo**: Step-by-step guides and tutorials
- **Organization**: Company/brand site-wide schema
- **Product**: E-commerce, SaaS products
- **BreadcrumbList**: Navigation breadcrumbs

**Validation Tools:**
- Google Rich Results Test: https://search.google.com/test/rich-results
- Schema.org Validator: https://validator.schema.org/
- Google Search Console → Enhancements

---

## 4. TOPIC STRATEGY & PLANNING

### 4.1 Topic Cluster Architecture

When user wants to build content authority around a core topic:

#### Step 1: Define Core Topic (Pillar)

```markdown
### Core Topic Definition
- **Primary topic**: [Broad topic that defines the pillar]
- **Primary search intent**: [Informational / Commercial / Transactional]
- **Business goal**: [Traffic / Authority / Conversions / Brand awareness]
```

#### Step 2: Identify Subtopic Clusters

Group related subtopics into logical clusters:

**Cluster Pattern:**
```
Core Pillar: [Broad Topic]
├── Cluster 1: [Subtopic Category]
│   ├── [Specific question/topic 1]
│   ├── [Specific question/topic 2]
│   └── [Specific question/topic 3]
├── Cluster 2: [Subtopic Category]
│   ├── [Specific question/topic 1]
│   └── [Specific question/topic 2]
└── Cluster 3: [Subtopic Category]
    ├── [Specific question/topic 1]
    └── [Specific question/topic 2]
```

**Example:**
```
Core Pillar: Content Marketing
├── Cluster 1: Strategy & Planning
│   ├── How to create a content marketing strategy
│   ├── Content calendar templates
│   └── Measuring content ROI
├── Cluster 2: Content Creation
│   ├── Blog post writing guide
│   ├── Video content production
│   └── Infographic design best practices
└── Cluster 3: Distribution & Promotion
    ├── Social media promotion tactics
    ├── Email newsletter best practices
    └── Content repurposing strategies
```

#### Step 3: Map Essential Question Types

For each cluster, ensure coverage of these question families:

- **Definition**: "What is...", "What are..."
- **How-to / Process**: "How to...", "Steps to..."
- **Tools / Resources**: "Best tools for...", "Templates for..."
- **Timing / Cost / Difficulty**: "How long...", "How much...", "Is it hard to..."
- **Comparisons**: "X vs Y", "Difference between..."
- **Examples / Use Cases**: "Examples of...", "When to use..."

#### Step 4: Internal Linking Structure

**Hub-and-Spoke Model:**
- Pillar page links to ALL cluster pages
- Cluster pages link back to pillar
- Related cluster pages link to each other
- Use descriptive anchor text (not "click here")

### 4.2 Content Calendar Prioritization

When planning content pipeline:

**Prioritization Matrix:**

```markdown
### Content Priority Scoring

| Content Piece | Business Value | Quick Win Potential | Resource Cost | Priority Score |
|---------------|----------------|---------------------|---------------|----------------|
| [Title 1]     | [High/Med/Low] | [High/Med/Low]      | [High/Med/Low]| [Calculated]   |
| [Title 2]     | [High/Med/Low] | [High/Med/Low]      | [High/Med/Low]| [Calculated]   |

**Scoring Logic:**
- Business Value: Direct revenue impact, strategic alignment
- Quick Win Potential: Striking distance keywords, low competition
- Resource Cost: Writer time, design needs, research depth

**Recommended Order:**
1. High value + Quick win + Low cost = Do first
2. High value + High cost = Schedule with resources
3. Low value + Quick win = Batch together
4. Low value + High cost = Defer or skip
```

---

## 5. USING THIS SKILL PROACTIVELY

When user asks any SEO or content question that could surface in SERPs:

1. **Recognize snippet opportunity**:
   - Question-based phrasing ("how", "what", "why", "best", "vs", "examples")
   - Topics commonly associated with guides, checklists, definitions, comparisons

2. **Produce at least one snippet block**:
   - Paragraph, list, table, HowTo, or video snippet as appropriate

3. **Optionally add**:
   - 3–6 PAA-style FAQs
   - Short topic-gap summary and 1–3 recommended follow-on pieces

Always keep outputs:
- **Concise first**, then expand only if user asks
- **Structured** with headings and lists
- **Aligned with UK English** conventions unless user's locale is clearly different

---

## Additional Resources

This skill comes with supporting templates and tools:

- **`aeo-brief-template.md`**: Structured brief template for planning new content with clear snippet and AEO goals, SERP observations, headings, and success criteria
- **`technical-seo-audit.md`**: Comprehensive technical audit checklist and reporting template
- **`geo-optimization-guide.md`**: Deep-dive guide on AI search visibility optimization
- **`gsc_ahrefs_clean.py`**: Helper script to clean and summarize CSV exports from GSC, Ahrefs, or Semrush into markdown tables for data input

Refer to these templates when user requests specific deliverables.
