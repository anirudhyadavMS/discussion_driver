# Predefined Discussion Questions

This file contains a curated set of discussion questions designed for leadership discussions. These questions can be loaded into the Discussion Driver tool to facilitate structured conversations.

---

## 1. What are our goals?

**POV Mode:** Visual

**Our POV:**
(visual)

---

## 2. What is our success metric?

**POV Mode:** Visual

**Our POV:**
(visual)

---

## 3. how is chatgpt doing it?

**POV Mode:** Visual

**Our POV:**
(visual)

End User Experience
Admin Experience

---

## 4. What end-user value are we targeting?

**POV Mode:** Visual

**Our POV:**
(visual)

• Personal AI Assistant for Work — Quick individual setup with immediate payoff.
• Team Pilot, Bottom-Up Adoption — Small group uses user-sync to prove the case for AI.
• Integrating Personal & Private Data — Bringing in data that admins can't centrally index.

---

## 5. What is the MVP?

**Our POV:**

Starting point:
- What are the targeted surfaces?
- What are the targeted connectors?
- What will be the phases of MVP?

### Subquestions

#### 5.1 What are the targeted surfaces?

**POV Mode:** Visual

**Our POV:**
(visual)

There are two virality angles that we have explored
• Virality via discovery — Drive growth with improved discovery via user-led distribution (remove Admin intervention)
• Virality via sharing — Drive growth by enabling key people/team leads create Agents shared across the team.

BizChat / Researcher / Agents (with Maker exp) / Search
Why? — BizChat has the highest MAU, hence highest discovery surface. OpenAI also prioritized Mainline.

#### 5.2 What are the targeted connectors?

**POV Mode:** Visual

**Our POV:**
(visual)

Principles of connector selection
• Notion of private data
• Tough ACLs which are brittle at tenant level
• High relevance to my workspace / project (my items, my tickets)
• Files and tickets domain (has a proven quality tenant connector)
• High usage (popular source)
• Fast go to market (tenant-sync connector already exists)
• No / Less overlap with MCP

Targeted connectors:
Jira / Confluence / Google Drive / ADO Work Items / Box / Dropbox

#### 5.3 What will be the phases of MVP?

**POV Mode:** Visual

**Our POV:**
(visual)

• Crawl — Deliver an MVP and prove value with limited connectors and surfaces (Mainline only)
• Walk — Expand to next top connectors and enable Maker + Self-Agents experiences
• Run — Enable sharing of Agents & connections. Build workflows to push Admins to enable tenant-sync for heavily used user-sync connectors.

---

## 6. What Data Do We Ingest per Connector? Do we ingest everything the user can see, or do we apply additional heuristics to keep the corpus tight?

**POV Mode:** Visual

**Our POV:**
(visual)

TBD
Examples:
1. Google Drive
• My Drive files
• Files/folders shared with me
• What about org-wide shared drives?

---

## 7. Shared vs Private indexing? How do we avoid N copies of broadly shared objects? How do we reason about aggregate cost when scaled to many users?

**POV Mode:** Visual

**Our POV:**
(visual)

TBD

---

## 8. How do we maintain response quality when both tenant-sync and user-sync co-exist? + MCP too

**POV Mode:** Visual

**Our POV:**
(visual)

• Mainline — Fan out to all connections irrespective.
• Agents — TBD
• Search — Can we de-dup results based on item id?

---

## 9. How will an Admin manage these connectors?

**POV Mode:** Visual

**Our POV:**
(visual)

• Admin must be able to control enablement of a user-level sync connector to employees.
• Admin must be able to selectively enable a user-level connector to — 1) All employees 2) Specific employees (Entra groups)
• Admin must be able to restrict crawling of user-level connectors to certain base domain(s).

---

## 10. How will an Admin observe these connectors' usage?

**POV Mode:** Visual

**Our POV:**
(visual)

• Admin must be able to check the number & list of users who are using the connection
• Admin must be able to check the number & list of Agents operating on a connection

---

## 11. What is the user's connector configuration experience like?

**POV Mode:** Visual

**Our POV:**
(visual)

PM prototype: M365 Copilot

---

## 12. What is the user's mainline usage experience like?

**POV Mode:** Visual

**Our POV:**
(visual)

---

## 13. What will be the release criteria?

**POV Mode:** Visual

**Our POV:**
(visual)

Evals: A slice of the tenant-sync evals which must perform at parity with tenant-sync connectors.

---

## Usage

These questions can be imported into the Discussion Driver tool by:
1. Opening the Discussion Driver Dashboard HTML file in your browser
2. Clicking the "Load prefilled questions" button (loads built-in questions), OR
3. Using the "Import JSON" feature with the `predefined-questions.json` file (loads from file)

The JSON file follows the application's state structure:
```json
{
  "meta": {
    "title": "Leadership Discussion",
    "createdAt": "2026-01-09T00:00:00.000Z",
    "updatedAt": "2026-01-09T00:00:00.000Z"
  },
  "mode": "start",
  "selectedRef": null,
  "questions": [ ... ]
}
```

## Notes

- Questions marked with "POV Mode: Visual" have associated visual diagrams in the tool
- Subquestions provide detailed breakdown for complex topics
- POV (Point of View) sections provide starting points for discussion
- The JSON file can be imported directly using the "Import JSON" button in the tool
