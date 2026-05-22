# OPC Growth

OPC Growth is a content repository for one-person companies, solo founders, and independent builders who want to use AI to grow a personal brand, find real users, and build practical monetization paths.

The writing is designed for execution, not inspiration.

It focuses on the questions that matter when you are building alone:

- Who should I talk to first?
- What audience is actually willing to pay?
- How do I turn AI from a productivity toy into a growth system?
- How do I create content that compounds into trust, demand, and revenue?
- What is the lowest-cost path from attention to real money?

## Positioning

This repo is built around **OPC**, short for **One-Person Company**.

An OPC is not just a freelancer, creator, or indie hacker. It is a business model where one person uses software, AI tools, content, systems, and focused distribution to create leverage without building a traditional team.

The content strategy is written from the perspective of a creator-strategist who specializes in:

- AI-assisted solo business growth
- Personal brand strategy
- Audience research and signal extraction
- Low-cost cold start systems
- Practical monetization paths
- Content that converts into trust and demand

## Writing Style

The style is inspired by the execution-first, first-person writing often seen in Dan Koe's work:

- Direct and practical
- First-person perspective when useful
- Strong point of view
- Clear mental models
- Short paragraphs
- No vague motivation
- No generic AI tool lists
- Every article should point toward a concrete action, offer, audience, or revenue path

The goal is not to sound clever. The goal is to help an independent builder move.

## Target Readers

This repository is for:

- One-person company builders
- Solo founders
- Indie hackers
- Consultants turning expertise into products
- Creators building a personal brand around expertise
- Builders using AI to reduce cost, increase output, and validate faster

The reader usually has limited time, limited budget, and no team. They need content that helps them decide what to do next.

## Core Themes

The articles focus on five recurring themes:

1. **Audience Signals**

   How to identify who has real pain, payment intent, urgency, and the language of demand.

2. **AI Leverage**

   How to use AI for audience research, content production, workflow design, offer testing, and decision support.

3. **Personal Brand Growth**

   How solo founders can turn their thinking, experiments, and proof into a distribution asset.

4. **Cold Start**

   How to find first users, run interviews, validate demand, and create early traction without ads.

5. **Monetization**

   How to move from content and conversations to templates, consulting, small products, subscriptions, or productized services.

## Articles

Current English articles:

- [How an OPC Can Use AI to Earn the First ¥100,000](articles/how-an-opc-can-use-ai-to-earn-the-first-100k.md)
- [Why Most OPCs Fail on Audience Judgment, Not Product](articles/why-most-opcs-fail-on-audience-judgment.md)
- [OPC Cold Start: How AI Helps You Find Your First Real Users](articles/opc-cold-start-how-ai-helps-you-find-your-first-real-users.md)

## Repository Structure

```text
articles/
  Published or publish-ready Markdown articles.

prompts/
  Prompt templates for topic selection, outlines, and article generation.

src/
  Local helper scripts for AI text and image generation.

scripts/
  Utility scripts for media and publishing workflows.

docs/
  Internal workflow notes and automation documentation.
```

## Content Principles

Every article should pass these checks:

- It speaks to a real OPC problem, not a broad entrepreneurship topic.
- It helps the reader make a decision or take an action.
- It connects AI to leverage, growth, or revenue instead of novelty.
- It uses concrete scenarios instead of abstract personas.
- It treats audience signal as more important than traffic.
- It avoids empty motivation and focuses on execution.

## Suggested GitHub Usage

Use `articles/` as the public article library.

Each article should be one Markdown file with:

- A clear H1 title
- Short paragraphs
- Scannable H2 sections
- No Notion metadata
- No image generation prompts
- No internal pipeline JSON

If this later becomes a website, the clean migration path is to move article files into a static-site content folder such as:

```text
content/posts/
```

Then add frontmatter for title, date, description, tags, and canonical URL.

## About the Pipeline

This repository also contains internal tooling for a Notion-based content workflow. The public-facing output is the Markdown article library in `articles/`.

The intended flow is:

```text
Notion research and planning
-> outline generation
-> article drafting
-> cleanup and translation
-> GitHub-ready Markdown
```

The pipeline exists to support consistent publishing, but the core asset is the thinking: practical, signal-driven content for OPC growth.
