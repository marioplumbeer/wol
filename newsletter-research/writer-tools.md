# Article Writer Tools — Research Notes

Survey of tools that help write, edit, optimize, and publish articles/blog posts/newsletters — to inform the toolkit for the new newsletter.

## 1. Drafting (AI writing assistants)

| Tool | Best for | Notes |
|---|---|---|
| **Claude** | Long-form prose, holding an argument across 1,000+ words | Better rhythm, less hedging than GPT-4o; follows multi-part style instructions more reliably; Projects can store a style guide + past posts for consistency; large context window good for feeding multiple source articles at once. |
| **ChatGPT** | Versatility, speed, brainstorming breadth | Strong across many formats (tutorials, listicles, opinion, landing copy) in one interface; faster iteration and more angle variations per prompt; often cited as better for SEO-templated blog output. |
| **Writesonic / Koala Writer** | SEO-first blog generation | Generate full posts from a title/outline with built-in optimization; Koala pulls real-time Google data; budget-friendly ($9–16/mo range). |
| **StoryChief / Copy.ai** | Teams / multi-format content ops | Bundle drafting + SEO + collaboration + publishing (StoryChief), or drafting + social/promo repurposing (Copy.ai). |

**Takeaway:** pair one primary drafting model (Claude for the actual essay) with a cheaper/faster tool only if repurposing into social or SEO-templated formats.

## 2. Editing & line-level polish

| Tool | Strength | Price |
|---|---|---|
| **Grammarly** | Fastest for everyday grammar/spelling, tone detection, broad app integration (500k+ apps) | Free tier; Pro ~$12/mo annually |
| **Hemingway Editor** | Readability scoring (Flesch-Kincaid grade level), flags passive voice & dense sentences visually | Free web version; $19.99 one-time desktop |
| **ProWritingAid** | Deepest style reports — pacing, overused words, sentence-variation scores; strongest for long manuscripts | Paid, subscription |

**Common power-user workflow:** draft → Grammarly (fix grammar) → Hemingway (tighten readability, cut passive voice) → optional ProWritingAid pass for a periodic deep style audit.

## 3. SEO / content optimization (if organic search matters)

| Tool | Approach | Best for |
|---|---|---|
| **Surfer SEO** | Real-time Content Score vs. SERP analysis, keyword clustering, AI writing assist bundled in | All-around, real-time on-page optimization |
| **Clearscope** | Simple A++–F topic-coverage grade vs. top-ranking pages | Non-SEO-specialist writers who want a clean, low-friction grader |
| **Frase** | Content briefs + AI-visibility tracking | Lower-cost alternative with strong brief generation |
| **MarketMuse** | Site-wide topical authority mapping, content-gap analysis | Enterprise/strategic — not per-article, more for planning a whole content inventory |

Relevant only if the newsletter is trying to rank in Google, not just via email/subscriber discovery.

## 4. Research & outlining

| Tool | Role |
|---|---|
| **Perplexity** | Real-time web research with citations — verifying facts, building background on a topic before drafting |
| **NotebookLM** | Research grounded in *your own* uploaded source documents/notes rather than the open web |
| **Notion AI** | Turns raw bullet-point research into a structured outline; doubles as the notes/organization hub |
| **Readwise Reader** | Solves source/highlight collection sprawl — read widely, save highlights, resurface them later |

Suggested pipeline: Perplexity (external research) → Readwise (save/curate highlights) → Notion (organize + outline) → Claude (draft).

## 5. Publishing platforms

| Platform | Model | Best for |
|---|---|---|
| **Substack** | Revenue share (10% of paid subs), hosted | Easiest start, built-in discovery network (500k+ publications), best when just starting out |
| **Beehiiv** | Flat SaaS fee, you keep 100% of subscription revenue | Growth-focused: referral program, cross-promotion network, paid-acquisition "boosts", best deliverability infrastructure; ~3x Ghost's growth rate, ~47% higher revenue than Substack per some reports |
| **Ghost** | Self-hosted or Ghost(Pro), full CMS | Best for SEO/organic-search growth (posts rank well on Google) and long-term data/revenue ownership; used by Scarlet Ink (per the [newsletter-research README](README.md)) |

**Framing that recurred across sources:** start on Substack for discovery, move to Beehiiv if optimizing for growth mechanics, move to Ghost if optimizing for owned SEO traffic and full control.

## 6. Cross-cutting takeaway

For a new solo-authored newsletter, the minimal effective stack looks like:
**Perplexity/Readwise (research) → Notion (outline) → Claude (draft) → Hemingway + Grammarly (polish) → Substack or Ghost (publish)**, adding an SEO tool (Clearscope/Surfer) only once organic search becomes a real growth channel rather than email/discovery.

---
*Research doc — will keep updating as we test specific tools.*
