# User Sync Connectors - Predefined Questions

This document contains all the predefined questions used in the Discussion Driver tool.

## Motivations

### M1: OpenAI parity
Match competitive expectations / feature completeness.

### M2: AU w. enhanced discovery / virality
Drive active usage via better discovery, sharing, and distribution.

### M3: Better response quality
Improve grounding, personalization, and relevance via synced user context.

---

## Value Pillars

### Pillar 1: Personal AI Assistant for Work
**Quick individual setup – immediate payoff.**

A Slack power user connects Copilot to GDrive and Slack in just a few clicks—no IT help needed. By lunchtime, Copilot is synced and ready. She can instantly ask:

"Summarize latest of Project Atlas and update the Atlas Status sheet in GDrive."

"Find the budget sheet I created and send the summary to Rohan."

### Pillar 2: Team Pilot, Bottom-Up Adoption
**Small group uses user-sync to prove the case for AI.**

Finance team pilots AI with user-synced apps. They connect Google Drive and Slack to Copilot, enabling natural language queries like:

"What were last quarter's key findings?"

"What issues came up during the audit?"

POC proves productivity gains without security risks. Their success becomes a proof point that convinces IT to roll out connectors org-wide—showing how bottom-up adoption drives innovation.

### Pillar 3: Integrating Personal & Private Data
**Bringing in data that admins can't centrally index.**

User-level connectors enable Copilot to access data that admins can't centrally index, such as an executive's private calendar or 1:1 chats. With user authentication, assistants can securely connect calendars and email so Copilot can answer questions like:

"When is the next board meeting?"

"Summarize today's CEO emails."

Unlike tenant connectors, this approach keeps data confidential and delivers personalized insights that broad integrations can't provide.

---

## Crawl-Walk-Run Phases

### Crawl: Prove value with a focused MVP

**POV:** Ship the smallest safe slice that proves user value.

**Scope:**
- Deliver an MVP with limited, high-signal connectors
- Mainline surfaces only (primary Copilot/chat experience)
- Core flows: connect → consent → use → revoke

**Non-goals:**
- Sharing agents/connections
- Cross-user workflows
- Tenant-wide enablement

**Success signals:**
- Meaningful usage lift in target cohort
- Clear response-quality or time-saved proof points
- Low support + low security incidents

### Walk: Expand coverage + enable richer experiences

**POV:** Turn the MVP into repeatable adoption by widening the funnel and unlocking compound use-cases.

**Scope:**
- Expand to next top connectors
- Enable Maker experiences (build/customize)
- Enable Self-Agents (multi-step, multi-connector)
- Better onboarding, error recovery, observability

**Success signals:**
- Multi-connector scenarios become common
- Retention / weekly active usage increases
- Admin sentiment improves (fewer exceptions, clearer controls)

### Run: Scale, share, and institutionalize

**POV:** Move from individual value → organizational leverage.

**Scope:**
- Enable sharing of Agents & connections (clear permission model)
- Build workflows that nudge admins toward tenant-sync for heavily used user-sync connectors
- Converge user-sync + tenant-sync into a cohesive admin model

**Success signals:**
- Admin-led rollout / defaults
- Ecosystem effects (shared agents)
- Durable platform adoption (lower churn, higher stickiness)

---

## Discussion Questions

### Q1: Motivation for user sync connectors
**Why now**

**Description:** Critique the motivations and rank them by priority. Capture critique ideas as cards.

**POV:**
- Motivation is **virality + growth**, not "parity".
- User-sync should unlock **discovery + sharing loops** while staying user-led (minimal admin gating).

**LT feedback asks:**
- What is the #1 business metric we should anchor on?
- Any red lines on security / privacy?

---

### Q2: How is ChatGPT doing it?
**Reference**

**Description:** Review two views (Admin Flow vs End User Flow). Add questions/feedback and vote with 👍/👎.

**POV:**
- Treat it as **admin policy + user connection**: admins enable the capability, users consent & connect accounts.
- Default to **user-led distribution** (remove admin intervention where possible).

**LT feedback asks:**
- Where do we draw the line between user-led vs admin-led?
- What approval points are non-negotiable?

---

### Q3: Value framing for user sync connectors
**Narrative**

**Description:** Use a 3-pillar framing. Click into a pillar to review scenarios and reserve image space.

**POV:**
- Frame value in 3 pillars:
  1) Personal AI assistant for work
  2) Team pilot → bottom-up adoption
  3) Integrating personal & private data

**LT feedback asks:**
- Which pillar should we lead with for MVP?

**Discussion topics:**
- What is the buyer story vs user story?
- What metrics prove value?
- What is the strongest pillar for MVP?

**Starter:**
Draft 1–2 sentences for the value prop and list measurable outcomes.

---

### Q4: MVP phasing: Crawl – Walk – Run
**Phasing**

**Description:** Crawl / Walk / Run — agree the rollout phasing and what "done" means per phase.

**POV (Crawl–Walk–Run):**
- **Crawl:** MVP on limited connectors + mainline surfaces to prove value safely.
- **Walk:** Expand connectors + enable Maker + Self-Agents.
- **Run:** Enable sharing of Agents & connections; workflows that push admins toward tenant-sync for heavily used user-sync connectors.

**LT feedback asks:**
- Are phases sequenced correctly?
- What's the minimum proof for moving Crawl → Walk?

**Discussion topics:**
- Crawl: MVP scope (limited connectors + mainline surfaces)
- Walk: Next connectors + Maker + Self-Agents
- Run: Share agents & connections + workflows → tenant-sync
- Success metrics per phase

**Starter:**
Crawl – Deliver an MVP and prove value with limited connectors and surfaces (Mainline only)

Walk – Expand to next top connectors and enable Maker + Self-Agents experiences

Run – Enable sharing of Agents & connections. Build workflows to push Admins to enable tenant-sync for heavily used user-sync connectors.

---

### Q4a: Which surfaces should we target?
**Surfaces**

**Description:** Two target surfaces — Mainline/Researcher and Agents — each with a virality thesis.

**POV (2 surfaces):**
- **Mainline/Researcher:** *Virality via discovery* — drive growth with improved discovery via user-led distribution (remove Admin intervention).
- **Agents:** *Virality via sharing* — enable key people/team leads to create Agents shared across the team.

**LT feedback asks:**
- Which surface should lead in the narrative?
- Any concerns about sharing model?

**Discussion topics:**
- Admin console
- End-user settings / profile
- In-product onboarding
- Copilot chat / composer

**Starter:**
List candidate surfaces and what users do there.

For each surface: trigger → action → feedback → recovery (errors/permissions).

---

### Q4b: Which connectors are we targeting?
**Targets**

**Description:** Prioritize connectors by impact and feasibility.

**POV:**
- Start with **Tier-1 connectors** that maximize immediate daily value and virality loops (discovery/sharing).
- Keep MVP narrow; expand only after strong signal.

**LT feedback asks:**
- Which 2–3 connectors must be in Crawl?

**Discussion topics:**
- Top 3 by customer demand
- Top 3 by technical feasibility
- Enterprise-critical sources
- Long-tail / future

**Starter:**
Create a short list:
- Tier 1 (MVP)
- Tier 2 (next)
- Tier 3 (later)

Add why: demand, coverage, complexity, risk.

---

### Q4c: What is the data ingest model?
**Data**

**Description:** What data is synced, how, and with what guarantees?

**POV:**
- Keep ingest minimal + safe: identity mapping + entitlements first; then deltas; strong audit/observability.
- Prefer **delta / event-driven** where possible; define clear SLAs.

**LT feedback asks:**
- What latency / SLA is acceptable for MVP?

**Discussion topics:**
- Identity + org mapping
- Groups / roles / entitlements
- Delta vs full sync
- Latency + SLAs

**Starter:**
Define:
- Entities (users, groups, roles…)
- Mapping keys
- Sync mode (full/delta/event-driven)
- Storage + retention
- Auditing + observability

---

### Q4d: MVP phases
**Phases**

**Description:** A phased plan to reduce risk and ship sooner.

**POV:**
- Use phased rollout with entry/exit criteria: threat model → limited beta → GA for Tier-1 → scale + ecosystem.
- Distinguish hardening vs new features.

**LT feedback asks:**
- What is the right cohort for beta? Any must-have launch partners?

**Discussion topics:**
- Phase 0: Design + threat model
- Phase 1: Limited beta
- Phase 2: GA for Tier-1 connectors
- Phase 3: Scale + ecosystem

**Starter:**
Draft phases with: entry criteria, exit criteria, and customer cohort.

Also call out what is "hardening work" vs "new features".

---

### Q5: Unifying connectors for Admin + end-user
**Unify**

**Description:** One mental model and one system for many connector types.

**POV:**
- One connector mental model: shared primitives (auth, scopes, policy), consistent lifecycle (install→configure→monitor), clear delegation (admin enables, user connects).

**LT feedback asks:**
- What do we need to make admins comfortable while keeping it user-led?

**Discussion topics:**
- Shared primitives (auth, scopes, policies)
- Connector lifecycle (install→configure→monitor)
- Delegation model (admin enables, user connects)
- Consistency across types

**Starter:**
Propose a unified model:
- Primitives (connector, account, policy, workspace, permission)
- Admin actions vs user actions
- Audit logs + health

Then list edge cases (multi-tenant, offboarding, revocation).
