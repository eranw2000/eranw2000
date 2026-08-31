## Hi, I'm Eran 👋

**AI & Data Solutions Architect.** I turn business problems into AI and data systems that run in production, handling the whole path myself: domain research, architecture, development, and live operation.

Since 2024 I have designed, built, and now operate production systems for clients in finance, legal, education, insurance, and consumer health, including:

- A multi-agent financial advisory platform (live public web product)
- A predictive learning-analytics platform, with risk scoring statistically validated against real outcomes
- A B2B account-intelligence pipeline: scraping, enrichment, deduplication, LLM-adjudicated scoring
- A voice + text knowledge-agent framework, deployed as four branded customer instances
- RAG-based legal risk assessment with a secured in-tenant architecture, where no document leaves the client's cloud

Most of that work lives in private repos. What you see here is the **AI-native development infrastructure I build and use daily**: Claude Code workflows for shipping to production, review agents, security and privacy guardrails, multi-phase skill frameworks, and the tooling around them. If you want to know how I work, these repos are the honest sample.

### The public repos

- **[multi-phase-skills-framework](https://github.com/eranw2000/multi-phase-skills-framework)** takes work from a rough idea to tested code through named phases, each leaving a handoff artifact for the next. Includes the plan gate that drives every weak spot in an approved plan to fixed or explicitly accepted before any code is written.
- **[claude-release-workflow](https://github.com/eranw2000/claude-release-workflow)** is the path to production: checkpoint a branch as a PR, run the three-reviewer round, release, then smoke test the live service. Ships a hook that blocks a direct push to main.
- **[claude-review-agents](https://github.com/eranw2000/claude-review-agents)** reviews a diff before it ships. Four agents covering code quality, deploy safety, whether the PR's tests actually pass, and prose that reads as machine-written.
- **[secure-dev-guardrails](https://github.com/eranw2000/secure-dev-guardrails)** handles security and privacy for AI-assisted development: threat modeling, dependency and secret review, plus hooks that block a commit carrying credentials or personal data.
- **[claude-maintenance-skills](https://github.com/eranw2000/claude-maintenance-skills)** keeps project knowledge healthy over time. What state a project is in when you return to it, and how to stop its context file from bloating.
- **[claude-commands](https://github.com/eranw2000/claude-commands)** holds the session commands and a status line that shows context use while you work.
- **[drawio-diagram-skill](https://github.com/eranw2000/drawio-diagram-skill)** produces diagrams as draw.io files, then validates and renders them, so the image is looked at before the diagram is called done.
- **[google-slides-skill](https://github.com/eranw2000/google-slides-skill)** rebuilds a Google Slides deck against branding you point it at: one design system, card layouts instead of paragraph dumps, real tables, and a render of every slide it touches before it says the deck is ready.

- **[plain-english-skills](https://github.com/eranw2000/plain-english-skills)** makes Claude write for a reader instead of for the session it has been sitting in: restate the last report in plain English, name the next step with the command to start it, or rewrite a document into Simplified Technical English with a checker that exits non-zero on violations.

Before consulting: founder and CEO of InfoGin (acquired by Wix), with products used by more than 100M people; head of product groups at Wix; wrote 15 patents, six granted by the USPTO, in contextual data analysis and adaptive systems (2006-2014), the same class of problems I now solve with modern AI.

### Core technologies

Python · Anthropic Claude · OpenAI GPT · Google Gemini (incl. real-time voice) · LangChain / LangGraph · RAG · Neo4j · Django · FastAPI · Docker · Playwright · Render / AWS / Azure

### Contact

[eranwyler.com](https://www.eranwyler.com) · [LinkedIn](https://www.linkedin.com/in/eranwyler/) · eran@wyler.ai
