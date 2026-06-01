# Managing Team Execution

> **Service Delivery · File 3.**
> *Client Onboarding* (File 1) got the client live; *Business Processes* (File 2) gave you the SOPs/skills the work runs on. This file is about **running the delivery engine day-to-day** — the project-management system that organises the work, the team structure (brand pods) that does it, and the operating rhythm (stand-ups, EOD reports) that keeps it moving.
>
> **AI-native note:** the same translation as the rest of Service Delivery — every role here is "a person or an agent," every recurring ritual (stand-up, EOD report, PM-board update) is an agent-executable routine, and the PM board is the shared state an agent reads from and writes to. Where a pod is described as people, an AI-native agency reads it as an **agent swarm with human leads at the gates.**

The core idea: **delivery doesn't fail because the work is hard — it fails because it's disorganised.** Missed deadlines, scope creep, budget overruns, burnout, and unhappy clients are all symptoms of *not managing execution*, not of bad talent. A project-management system, a clear team structure, and a daily rhythm are what convert a signed client into delivered results, repeatably.

---

## 1. Why a project-management system exists

A PM system is the backbone of delivery. What it gives you:

- **📚 Clarity on workload + priority** — the team has a roadmap: what to execute, in what order, day to day.
- **👥 Resource management** — you know who's working on what and when, so nothing falls through the cracks and no one burns out.
- **⚠️ Risk mitigation** — you can foresee missed deadlines, budget overruns, and capacity gaps *before* they become problems (hire, re-prioritise, or spot missing work early).
- **🗣️ Client communication** — regular updates, progress reports, and timelines are easy to pull, which makes managing client expectations far easier.

### What happens without one
- **⛔️ Missed deadlines** → a client asking for a refund, or worse.
- **⬆️ Scope creep** → "just one more thing" until a single client eats unprofitable amounts of time.
- **💸 Budget overruns** → tasks run long, costs escalate, margin erodes.
- **😴 Team burnout** → no visibility of each person's load → overload → stress, demotivation, falling quality.
- **👎 Client dissatisfaction** → miscommunication + missed deadlines + off-spec output → churn and reputational damage.

> The five failure modes map one-to-one onto the four benefits: the system exists specifically to prevent scope creep, overrun, burnout, missed deadlines, and dissatisfaction. **Scope creep is the one to watch hardest** — it's where the offer (*High-Converting Offers*) and the signed scope (*Service Agreement*) meet daily reality, and where margin quietly dies.

---

## 2. The delivery board — one workspace per client

Each client gets a **delivery board** (the example is built in Asana) — a single workspace that holds everything about that client and every task to be done. Tasks are grouped into sections:

| Section | What lives here |
|---|---|
| **Client Resources** | The reference layer: client details (from the onboarding form), service agreement (services, monthly fee, date signed, term end), client meetings (with minutes + actions), client folders (Dropbox/Drive), pitch deck, onboarding deck, brand guidelines |
| **Client To-Dos** | What you're waiting on *from the client*: complete onboarding form, deliver brand guidelines, approve next month's ad creatives, share podcast footage, etc. |
| **Agency To-Dos** | What *your team* owes: the onboarding steps (team KO, client KO email, KO deck, follow-up, folders, Slack, add to financial forecast) plus the actual delivery work (web set-up, LP wireframes, ad creatives scripted, cart optimisation, etc.) |

Each task carries the standard fields: **assignee, start/due dates, tags, notes, parent task, and dependencies (blocked by / blocking).**

> **Why this structure works:** it separates *reference* (Client Resources) from *action* (the two To-Do lists), and within action it separates **client-owed** from **agency-owed** — so at a glance you can see whether a stall is your fault or theirs. The dependencies field encodes the *order* of work (e.g. "content brainstorming" is blocked by "KO deck created"), turning the board into the live version of the documented process from File 2.

> **AI-native angle:** the delivery board is the **shared state / source of truth an agent operates on.** An agent reads Client Resources for context (agreement scope, brand guidelines, demographics), works the Agency To-Dos in dependency order, fires reminders against Client To-Dos, and writes meeting minutes/actions back into the Client Meetings section. The board is to delivery what Pipedrive was to acquisition — the canonical object the whole system reads and writes.

---

## 3. The team structure — Brand Pods

Delivery is organised into **pods**: cross-functional teams that own one or more brands within a category (e.g. clothing brands "Thrst" and "Flossy" share a pod). The pod is the unit that delivers; shared specialists support across pods.

### The core pod
| Role | Owns | Cadence |
|---|---|---|
| **Brand Lead (Pod Owner)** | The P&L, growth roadmap, prioritisation, overall account management | Daily internal; weekly strategy |
| **Media Buyer** | Meta/Google/TikTok/Snap ads; scaling and creative testing | Daily |
| **Creative Strategist** | Ad angles, hooks, briefs; creative-performance analysis | Weekly |
| **Email/SMS Strategist** | Campaigns, automated flows, retention, LTV | Weekly |
| **CRO / Funnel Marketer** | Landing pages, AOV, conversion rates | Weekly |
| **Product Lead** | Manufacturing interface, product development | Weekly |

### Shared specialists (support multiple pods)
**Commercial Lead** (high-level strategy across all pods) · **Senior Media Buyer** (manages the pod media buyers) · **Creative Director** (quality + positioning of ads/brand) · **Data & Analytics** (dashboards, CAC/LTV, data integrity) · **Shopify Dev Team** (technical updates across all sites) · **Supply Chain / Inventory** (3PL + logistics across the portfolio) · **Project Manager (PMO)** (runs all work through the centralised delivery system).

> **The design logic:** put the *frequently-needed, brand-specific* roles inside the pod (so each brand has dedicated daily attention) and pool the *expensive, high-leverage, occasionally-needed* roles as shared specialists (so you're not paying for a Creative Director or a Shopify team per brand). The Brand Lead owning the P&L is the key accountability — one person owns whether the brand makes money.

---

## 4. Scaling the structure — shared → dedicated

The pod system is built to scale with brand complexity/revenue:

- **The breaking point:** keep adding brands to a pod until the system *"breaks"* — that strain is the signal to spin up a new pod or add resource. (You scale *reactively to a clear signal*, not speculatively.)
- **Dedicated pods:** large "Power Brands" (e.g. Shreddy, Neutonic) graduate out of shared pods into their own **dedicated pod.**
- **Self-sufficiency:** once a brand is big enough, its *own revenue* pays for its dedicated team — the brand funds its own pod.
- **Peak periods:** dedicated pods are essential in "breaking point" seasons like Black Friday, when every brand needs 100% focus and shared resource can't stretch.

> **The principle:** start shared (cheap, efficient), graduate to dedicated when revenue justifies it and complexity demands it. The "breaking point" is a deliberate management signal, not a failure — it tells you exactly when to invest in more structure.

> **AI-native angle:** the pod model maps cleanly onto an **agent-swarm-with-human-leads** design. The recurring, well-SOP'd functions (media buying ops, email flows, CRO tests, reporting) become agents; the **Brand Lead, Creative Director, and Commercial Lead remain human gates** owning P&L, taste/positioning, and strategy — i.e. exactly the judgement-and-accountability roles that §9 of *Business Processes* says shouldn't be fully automated. "Scale until it breaks, then add a pod" becomes "scale until quality/latency degrades, then add agents or a dedicated agent cluster" — and an AI-native agency hits the breaking point far later, because agents absorb the high-frequency load that used to force a new human pod.

---

## 5. The operating rhythm — daily team execution

Two daily rituals keep the pod synchronised, bookending each working day:

### Daily Stand-up (morning, ~9:30am)
A short team meeting with a fixed agenda:
- **Team Focus** — each person confirms their focus for the day.
- **Other Priorities** — flag work not yet mentioned that needs doing; re-prioritise if needed (*client work going out the door comes first*).
- **Approvals Pending** — flag anything the team is waiting on.
- **Blockers** — surface and resolve.

### End-of-Day Report (~5:30pm, via Slack)
Quick bullet points posted in Slack before anyone signs off:
- **What's done.**
- **What's not.**
- **Why not.**

> **The bookend logic:** the stand-up *sets* the day (focus, priorities, unblock) and the EOD *closes* it (done / not done / why). Together they create a daily accountability loop — nothing drifts for more than a day without being surfaced. Note the priority rule baked into the stand-up: **client work going out the door comes first.** This is the same daily/weekly/monthly cadence seen in *Paid Ads* and the *Client KO* comms model — here it's the *internal team* version.

> **AI-native angle:** stand-up and EOD are the most directly automatable rituals in delivery. An agent (or the PM agent) can assemble the stand-up agenda from the board each morning (today's due tasks, pending approvals, dependency-blocked items) and emit the EOD report each evening straight from task-completion state (what moved to done, what's still open, blockers logged) — exactly the *done / not done / why not* structure, and the same shape as the acquisition-team EOD report in *Outbound — Hot Outreach*. The board makes both reports a query, not a meeting.

---

## Synthesis — how Managing Team Execution fits Service Delivery

This file is the **delivery operating system** that sits between onboarding and the work itself:

1. **A PM system** exists to give clarity, manage resource, mitigate risk, and ease client comms — and to prevent the five failure modes (missed deadlines, scope creep, overrun, burnout, dissatisfaction).
2. **The delivery board** (one per client) is the single source of truth — Client Resources (reference) + Client To-Dos + Agency To-Dos, with assignees, due dates, and dependencies that encode the documented process.
3. **Brand pods** are the team unit: brand-specific roles inside the pod (daily attention, Brand Lead owns P&L), expensive high-leverage roles pooled as shared specialists.
4. **Scaling** runs shared → dedicated, triggered by the "breaking point" and funded by the brand's own revenue once it's big enough.
5. **The daily rhythm** (stand-up sets the day, EOD closes it) creates a same-day accountability loop, with "client work out the door first" as the priority rule.

**The single biggest idea:** execution is a *management* problem, not a talent problem. Talented people with no system miss deadlines, creep scope, burn out, and lose clients; the same people on a clear board, in a well-structured pod, running a daily set-and-close rhythm deliver consistently. For an **AI-native agency**, the board is the shared state, the pods become agent swarms with humans holding the P&L/taste/strategy gates, and the daily rituals become automatic reports generated from board state — so "managing team execution" largely becomes *designing the system and minding the gates* while the routine execution and reporting run themselves.

---

### Cross-references
- **The documented processes** the board's tasks execute → *Business Processes* (the web-dev process, content brief, SOPs/skills).
- **Onboarding steps** that appear as the first Agency To-Dos (team KO, client KO email/deck/follow-up, folders, Slack) → *Client Onboarding.*
- **Scope** the PM system protects against creep → *High-Converting Offers* (custom offer/deliverables) + *Sales Leads & Pipeline Management → §7 (service agreement).*
- **The daily/weekly/monthly cadence** the rhythm mirrors → *Paid Ads → §4* and *Client Onboarding → §6 (comms cadence).*
- **The EOD report structure** (done / not done / why) echoes the acquisition EOD → *Outbound Leads — Hot Outreach.*
- **The comms rules** governing the Slack EOD + client channels → *Business Processes → §4 (Communications Handbook).*
- **Approvals / permission gates** the human pod leads hold → *Business Processes → §9 (SOPs as Agent Skills).*

*(Frameworks adapted from the Genflow / Agency Insiders "Project Management Overview," the "Client Delivery" Asana board template, the "Brand Pod Structure & Scaling" document, and the "Managing Team Execution" board. Pod roles/brands shown are illustrative examples.)*
