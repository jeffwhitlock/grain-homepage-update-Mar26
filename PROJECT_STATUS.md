# Project Status

## Intent
- Reposition grain.com from "AI Notetaker" to "Meeting capture for AI agents" — aligned with Q1 2026 strategy shift toward AI-forward, conversation-driven professionals.
- Success = homepage and key pages reflect the new ICP (consultants, founders, advisors) and lead with the capture → enrich → deliver-to-AI value chain.

## Context

### What is Grain?
Grain (grain.com) is an AI meeting notetaker SaaS product at ~$3.7M ARR. It records meetings on Zoom, Google Meet, and Teams, generates AI-powered transcripts and notes, and integrates with CRMs, Slack, Zapier, etc. The company is small (~15 people), cash-flow positive, and historically positioned for sales teams. The website is built on Webflow.

### Why this project exists
Grain is executing a major strategic pivot. The old positioning targeted sales managers with features like coaching scorecards, CRM sync, and deal tracking. The new strategy (documented in `project_context/20260314_Grain Strategy_Q1 2026_Master.md`) shifts focus to **AI-forward, conversation-driven professionals** — consultants, founders, advisors, and small agencies — whose meetings ARE their work product. The core thesis: recording and AI notes are commoditized; the real value is enriched transcripts flowing into AI tools (Claude, ChatGPT, Cursor) so agents can do real work with meeting context.

### The strategic value chain
The new positioning follows a three-step pipeline: **Capture → Enrich → Deliver to AI**
1. **Capture**: Desktop-based local recording (no bots required), works across all platforms
2. **Enrich**: Transcripts with speaker identity, company context, relationship history, reference links — not just raw text
3. **Deliver to AI**: One-click "Open in Claude/ChatGPT," MCP server, enriched Markdown downloads, API access

### New ICP (Ideal Customer Profile)
The "AI-forward, conversation-driven professional" — someone whose primary work product flows from meetings. Unified by:
- Ongoing relationships where context compounds across meetings (not one-off calls)
- Action items and deliverables originate in conversations
- Need context organized by project/relationship, not a flat timeline
- Increasingly feeding meeting context into AI tools to do real work

Shows up as: independent consultants, coaches, advisors, founders, some CSMs/AEs/PMs, some VCs.

### Key product features being built (relevant to copy)
- **Enriched AI Transcript format** — Markdown with speaker IDs, timestamps, company context, relationship links
- **"Open in Claude/ChatGPT"** — deep links to open transcripts directly in AI tools
- **MCP Server** — connects Grain data to Claude, Cursor, and MCP-compatible tools
- **Desktop local capture** — bot-free recording on Mac (shipping), Windows (coming soon)
- **Projects** (future, not yet shipped) — auto-organizing meeting spaces by client/project with accumulated context, replacing playlists

### What has been deprecated or is being de-emphasized
- Sales coaching scorecards
- Sales-manager-specific features
- "Conversation Intelligence" positioning
- CRM sync as a leading feature (still present, just not the headline)

## File guide

### Root
- **`PROJECT_STATUS.md`** — This file. Working memory for the project.
- **`Updated Website Copy_Draft.md`** — The main deliverable. Complete draft of updated homepage copy with: hero section, value prop blocks, 4 feature deep-dive sections, nav/footer/FAQ changes, tone guidance, customer interview insights, and implementation priority. **This is where all the work lives.**

### `project_context/` — Source materials

- **`20260314_Grain Strategy_Q1 2026_Master.md`** — The master strategy document. Covers where Grain is, the new ICP, what's being built, sequencing, growth loops, and kill criteria. **Read this first for full strategic context.**
- **`Current Website Copy_3.17.26.txt`** — Text dump of the current grain.com homepage as of March 2026.
- **`Strategy Discussion_3.17.26.txt`** — Transcript of a team strategy discussion (3/16/26). Key insight from Mike (Speaker 3): the homepage should position Grain as "meeting capture for agents" immediately — "nobody wants freaking notes anymore, everybody wants to be feeding into their agents." Also surfaced tension around Projects being "context-aware" vs. "context-owning" (team prefers lightweight, auto-generated, no data entry).

### `project_context/Interview Call Transcripts/` — 7 customer research calls
All conducted by Jeff Whitlock (CEO) in Feb–Mar 2026 with target ICP users:

| File | Who | Role | Key insight |
|------|-----|------|-------------|
| `Call with Ariane Bischoff_2:26:26.txt` | Ariane Bischoff | Architectural firm founder (Germany) | Wants "rolling protocol" — accumulated meeting minutes across meetings, not one-off notes. 4hrs/week spent on manual meeting protocols. |
| `Call with Continuity Consulting_3:2:26.txt` | Rich Daly, Matt Chamberlain, Kathryn Howard | Healthcare tech consulting (15 staff, ~24 clients) | Load every transcript into ChatGPT projects per client for longitudinal context. Want auto-flow of transcripts into GPT projects. Cross-meeting action item tracking. |
| `Call with Emma Holliday_2:24:26.txt` | Emma Holliday | AI trainer + association director (Australia) | Wants meeting content auto-turned into blog posts, social content. Biggest pain: no time to follow up after back-to-back meetings. |
| `Call with Jill Freeman_2:20:26.txt` | Jill Freeman | Employer culture consultant (~6 clients) | Wants Grain to be a proactive AI assistant — prep her before meetings with last week's context, stack notes week-over-week. Creates branded PDF meeting notes for clients. No CRM (uses Notion chart). |
| `Call with Sonia_2:27:26.txt` | Sonia Germain | Luxury hotel interior design (Toronto, ~4 multi-year clients) | Biggest pain: volume of information across channels. Wants meetings organized by client/phase. No CRM. Needs Windows desktop capture and translation. |
| `Huddle with Adrian_3:5:26.txt` | Adrian (internal power user) | Uses MCP + Claude daily | Wants projects with auto-rules (by domain/email), decision logs that regenerate per update, markdown export as separate files per meeting (not one giant file). "Video knowledge base / transcript-based knowledge base." |
| `Yocheved from Intentional Marketing_3:19:26.txt` | Yocheved | Digital agency owner (NJ, ~25 people) | Feeds every transcript into SmartSuite → triggers AI agent pipelines → auto-generates client deliverables. Loves Grain's clean/minimal UI. Wants better API access and Relay integration. |

### `project_context/Strategy Discussions/` — Additional internal strategy transcripts
Supporting context for the strategic direction. Less critical than the master strategy doc but useful for nuance.

## Decisions made so far

1. **H1 approved by Jeff:** "The AI notetaker built for agents"
2. **H2 approved by Jeff:** "Capture every meeting. Enrich your transcripts with context. Deliver them to Claude, ChatGPT, or any AI tool so your agents can do the meeting work."
3. **Hero section tracks three evolutionary stages:** Old (sales-focused) → Current (transitional, live now) → Proposed (agent-forward)
4. **Value prop Block 2 was rewritten** based on interview insights — changed from "Enriched transcripts, not just raw text" to "Context that builds across meetings — not one-off notes" because longitudinal context was the #1 unmet need across all interviews.
5. **Integration hierarchy:** AI tools (Tier 1) > Communication/workflow (Tier 2) > CRM (Tier 3, present but not leading)
6. **"Grain for Sales" nav item:** recommended to remove or deprioritize — not yet decided by Jeff.
7. **Social proof:** Replace rotating "sales / customer success / product / teams" with static "professionals" or rotate ICP roles.

## Recent work
- Read and synthesized three core context docs: strategy strawman, strategy discussion transcript, current website copy.
- Drafted complete updated homepage copy in `Updated Website Copy_Draft.md`.
- Jeff reviewed and approved H1/H2. Provided feedback that H1 must explain what Grain is + deliver value (not just a clever tagline).
- Read all 7 customer interview transcripts. Added "Customer Interview Insights" section to draft with 8 patterns and copy implications.
- Searched Grain for additional interview calls Jeff conducted in 2026. Identified Jeff<>Courtney (3/13) but confirmed it was a product feedback call, not an ICP interview.
- Updated value prop blocks based on interview insights (Block 2 rewrite, Block 3 and 4 refinements).

## In-progress
- Jeff reviewing the updated draft with interview insights incorporated.
- No sections have been implemented in Webflow yet — this is still in the copy/strategy phase.

## Next up
- Get Jeff's sign-off on remaining sections (feature deep-dives, FAQ, footer).
- Decide on implementation approach (Webflow MCP tool available, or manual implementation by a designer/developer).
- Iterate on specific sections based on feedback.
- Consider secondary pages: pricing copy, use case pages for new ICP personas.

## Risks / questions
- Should "Grain for Sales" be fully removed from nav or just deprioritized? (Retention risk for existing sales customers.)
- How aggressive to be on removing sales/CRM language from homepage vs. keeping it secondary?
- Are there existing designs or mockups for the refresh, or is this copy-first?
- Does the team want to keep the 97% retention stat or update it?
- Projects feature is not yet shipped — how much should the homepage promise "context that compounds across meetings" if the product doesn't fully deliver it yet?

## Parking lot
- Pricing page copy updates.
- New use case pages (Consultants & Advisors, Founders, AI-Powered Workflows).
- SEO keyword shift from "Conversation Intelligence" to "AI Meeting Agent" terms.
- FAQ answer copy (questions identified, answers not yet drafted).
