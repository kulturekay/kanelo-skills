# Client Onboarding

> **Service Delivery · File 1.**
> The Client Acquisition section ended at **"Signed"** — a deal closed and a service agreement executed (*Sales Leads & Pipeline Management → §7*). This section, **Service Delivery**, is what happens next: turning a signed contract into a delivering, happy, retained client. It opens with **onboarding** — the bridge between "they paid" and "the work begins."
>
> **AI-native note:** this whole sequence was designed to run on a human team (outreach exec → account manager → service team), but **every step is executable by an AI agent or an AI-native agency.** Emails are templated, the form is structured data, the kick-off decks and meeting agendas are fixed frameworks, and the admin set-up is API-driven (Slack, Dropbox, Asana, Trello, ad accounts). Throughout, read each human role as "**a person or an agent**," and note the explicit AI-agent translations at each stage.

The core idea: **onboarding is where trust is either cemented or lost.** The client has just spent money on a promise; a tight, professional, well-orchestrated onboarding makes them feel safe and confident from day one — *"when everyone knows what they're doing, the client can feel it."* A sloppy one creates doubt before any work has even started.

---

## 1. The onboarding sequence — the whole flow

Onboarding is a fixed, ordered pipeline of nine steps. Each one has an owner and a clear output:

```
 1. Team Briefing Email   → internal: announce the new signing
 2. Client Onboarding Email → external: welcome + propose KO meeting + first invoice
 3. Client Onboarding Form → external: collect all data, assets & access
 4. Internal KO Meeting    → internal: align the team before facing the client
 5. Client KO Meeting      → external: the deck-led welcome call
 6. Client Internal Set-up → internal: Slack, folders, PM tools, ad accounts
 7. Client Follow-up       → external: recap email, next steps, invites
 8. Execution Begins 🚀    → the work starts
```

Two threads run in parallel: **internal steps** (1, 4, 6) get *your side* ready; **external steps** (2, 3, 5, 7) manage *the client's* experience and pull what you need from them. The sequence alternates between them deliberately so you're never client-facing without being internally prepared first.

---

## 2. Step 1 — Team Briefing Email (internal)

The moment a deal is signed, the closer broadcasts it to the team so the people who'll deliver know it's coming. It's a structured handoff from acquisition to delivery.

**Contents:**
- **New client:** name · social links · website · location.
- **Partnership overview:** service (with specifics — e.g. Facebook/Instagram/TikTok Ads) · signing date · agreed fee · term · client email · agreement attached for reference.
- **Next steps:** who sends the Client Onboarding Email · who builds the kick-off deck.

> *Worked example:* "New Signing: XY Cosmetics" — Paid Ads Management (FB/IG/TikTok), signed July 25th, £3,000/month, 6-month minimum then rolling monthly, agreement attached, @Sarah to send onboarding email + build deck.

**AI-agent translation:** on the Pipedrive card hitting "Signed," an agent auto-generates this briefing from the deal record (all fields already live on the card and in the agreement), posts it to the team channel, and assigns the next two tasks (onboarding email, deck) to owners.

---

## 3. Step 2 — Client Onboarding Email (external)

The first contact *after* signing. Warm, reassuring, and action-oriented — it welcomes them, restates the outcome you promised, and proposes the kick-off meeting.

**Structure:**
- **Welcome** + restate the result you promised to deliver.
- "Now we have the signed agreement, I'd love to set up a **kick-off meeting**."
- **What the KO meeting will cover:** clarity on services · team introductions · communication systems · planning + reporting · initial [content/ads/ecomm] strategy · deliverables needed from you · timelines for going live.
- Position the meeting as *their* chance to ask anything before work starts.
- **Propose 3 date/time options** → confirm → send calendar invite.
- **First invoice / deposit:** settle by [date]; *the team begins all services only once paid, post-onboarding meeting.*
- Warm sign-off.

> **The payment gate:** services don't begin until the first invoice is settled. Onboarding can proceed (meeting, form) but execution waits on payment — a clean, non-confrontational way to enforce it.

**AI-agent translation:** agent drafts from the template (merge client name + promised result + service), proposes times from the real calendar, attaches the invoice, and on payment-confirmation webhook flips the deal to "execution-ready."

---

## 4. Step 3 — Client Onboarding Form (external)

The data-collection engine. One structured form gathers **everything you need to deliver** so you're never chasing the client mid-project. Four blocks:

1. **Client details:** full name, address, email, timezone, phone, DOB, copy of passport (link), bank details (only if *you* pay *them*), proof of address.
2. **Company details:** company name, brand name, brand assets (link), website URL, social links.
3. **Set-up information** (service-specific — the example is Paid Ads): domain provider & login, website platform (Shopify/Webflow/Kajabi), Google Analytics tag ID, Google Ad account, YouTube accounts, FB Business Manager ID, FB Pixel ID, Instagram (linked to FB?), lookalike audience data, existing raw video content (link).
4. **Access to grant:** admin-level access to named team-member emails; plus a **resources block** — Looms/links showing the client *how* to grant FB Business Manager / Google Ads / Analytics access if they don't have accounts set up.
5. **Strategic questions:** describe your customer base (demographics, interests, income, problems); what they want from the partnership (with target metrics); the key problems to solve.

> **Two jobs in one doc:** it collects *operational* access (so you can actually do the work) *and* the *strategic* inputs (so the work is aimed correctly). The "resources/Loom" column is the self-service unblocker — it stops access-granting from becoming a week of back-and-forth.

> **Security note (important for an AI-native agency):** this form requests passwords, bank details, and passport copies. An AI agent must **never store, transmit, or enter these credentials itself** — collection of sensitive identity/financial data and account access should be handled through secure client-completed forms and proper permission-based access (admin invites by email), not by an agent handling raw passwords. Treat the form as client-completed; the agent orchestrates and reminds, but a human/secure system holds the secrets.

**AI-agent translation:** agent issues the form, auto-reminds until complete, validates that required fields/links are present, files responses to the client folder, and flags any missing access before the internal KO so it's resolved early.

---

## 5. Step 4 — Internal Kick-off Meeting (internal)

Before you face the client, the delivery team aligns. **Don't leave it all to you (the founder).**

**Why hold it:**
- **Alignment** on the client's objectives and *why they joined you*.
- **Alignment on agreed services** — what's in and out of scope (so the team can escalate out-of-scope requests).
- **Clear responsibilities** — each person's role, no overlap.
- **Set timelines** — deadlines, and capacity troubleshooting.
- **Prevent issues** — spot risks early (capacity, resources, miscommunication).
- **Foster collaboration + accountability** — the team feels like a team and owns their part from day one.
- **Ensures smooth onboarding** — a tight ship the client can *feel*.

**What to cover (checklist):** client overview (industry, background, stakeholders) · relationship specifics (how signed, rapport, personality) · client goals & success metrics & timeframe · scope of work (walk the agreement) · **SLAs** (reporting frequency, meeting cadence, comms style) · roles & responsibilities · project timeline & milestones · key challenges/risks · next steps (assign all post-meeting actions: PM set-up, client + competitor research, strategy, build the Client KO deck).

> The internal KO is also where the **Client KO deck** gets briefed and assigned — the two meetings are linked: internal alignment produces the external presentation.

**AI-agent translation:** an agent prepares the internal KO brief automatically — pulling the agreement scope, deal history/personality notes from the CRM, and proposed roles — and drafts the first-cut project plan, timeline, and risk list for the team (or agent swarm) to confirm.

---

## 6. Step 5 — Client Kick-off Meeting (external)

The deck-led welcome call — the client's first real experience of the team. **12-slide deck**, agenda-driven:

| Slide | Purpose |
|---|---|
| **Cover** | Client name · "Kick-off Meeting" · date |
| **Agenda** | Team intros · clarity on services · comms systems · initial strategy · deliverables needed · timelines · next steps |
| **Your core team** | Photos + names + titles — "familiar faces you'll communicate with" |
| **Our services** | Overview of what you've agreed to provide |
| **Your role** | The client's obligations in the partnership |
| **Communication systems** | Slack (daily informal, briefs, approvals) vs Email (formal comms, decisions) |
| **Comms: what + how** | The daily / weekly / monthly cadence (see below) |
| **Strategy** | Initial strategy across the service — audience/creative/content pillars/web optimisation + *why* |
| **Your deliverables** | What you need *from them* to start (brand guidelines, copy, content, FAQs, etc.) |
| **Timelines** | Week-by-week steps/milestones |
| **Next steps** | Concrete actions + dates (Slack set-up, form deadline, ad accounts live, social takeover date) |
| **Closing** | Repeat cover |

### The communication cadence (a reusable SLA model)
| Cadence | What it covers | How |
|---|---|---|
| **Daily** | Comms responses, delivery management, operational management, fire-fighting | Ad hoc, via Slack |
| **Weekly** | Status updates, plan for the week, next commercial action, operational list, top-line performance | Weekly video call / email |
| **Monthly** | Last month's performance assessment, goals/priorities, performance deep-dive (revenue, ROAS, growth, engagement), next-3-months strategy | Monthly meeting |

> This daily/weekly/monthly model is the same rhythm as the ad-optimisation cadence in *Paid Ads* — operational firefighting daily, iteration weekly, strategy monthly. It doubles as the client's **SLA**: it sets expectations for exactly how and how often you'll communicate.

**AI-agent translation:** an agent assembles the deck from the template using the agreement + form + strategy inputs, and can run or co-run the call; for an AI-native agency the "core team" slide honestly represents the agent(s) and any humans, and the cadence above becomes the agent's literal operating schedule (daily Slack presence, weekly report, monthly deep-dive).

---

## 7. Step 6 — Admin / Internal Set-up (internal)

With the client aligned, stand up the operational infrastructure:

- **Comms:** create the client Slack channel; send the invite.
- **Files:** set up client folders internally (Dropbox).
- **Project management:** Asana / Trello boards for the work.
- **Ad accounts / platforms:** configure access granted via the onboarding form (FB Business Manager, Google Ads, Analytics, etc.).
- **Cadence:** add the weekly call to the calendar; send the invite.

**AI-agent translation:** this is the most directly automatable stage — an agent provisions the Slack channel, creates the folder structure and PM boards from a template, accepts the granted ad-account access, and schedules the recurring calls, all from the data captured in the form. (Account *creation* and password-based login remain client-side / human-authorised; the agent operates via proper delegated admin access.)

---

## 8. Step 7 — Client Follow-up (external)

Right after the Client KO meeting, send a recap that converts the meeting into tracked actions. **Contents:** attach the KO deck + onboarding form · note any decisions made in the meeting · two bulleted lists — **Client actions + deadlines** and **Agency actions + deadlines.**

**Example structure:**
- *What's needed from you:* complete onboarding form by [date]; share content assets (Dropbox); share brand guidelines; grant FB Business Manager access.
- *Agency next steps:* set up Slack + invite; set up weekly call + invite; script first creatives; create LP wireframe; deliver first week of content for review by EOW.

> Same discipline as the EOD/pipeline reporting earlier in the knowledge base: **named actions, named owners, dated deadlines.** Nothing is left ambiguous, so the client knows exactly what to do and sees you already moving on yours.

**AI-agent translation:** agent generates the recap from the meeting (transcript/notes → decisions + action items), assigns and date-stamps each action, fires reminders, and tracks completion to a board.

---

## 9. Step 8 — Execution Begins 🚀

Once the form is complete, access is granted, payment is settled, and set-up is done — **the work starts.** Onboarding's job was to reach this point with the client confident, the team aligned, the access in hand, and the first deliverables already scheduled. Execution then runs on the cadence established in the KO deck (daily Slack / weekly call / monthly deep-dive).

---

## Synthesis — how onboarding fits Service Delivery

Onboarding is the **handoff hinge** between selling and delivering:

1. **Acquisition handed over a signed client** (*Sales Leads & Pipeline Management*). The Team Briefing Email is the literal baton-pass from the closer to the delivery team.
2. **The external track** (onboarding email → form → KO meeting → follow-up) manages the client's experience and extracts everything you need from them, gated on the first payment.
3. **The internal track** (team briefing → internal KO → admin set-up) gets your side aligned and operational *before* and *around* each client-facing moment.
4. **It ends at Execution**, running on the daily/weekly/monthly cadence that the KO deck established as the client's SLA.

**The single biggest idea:** onboarding is a *trust-manufacturing system*, not paperwork. Every step is engineered so the client feels a tight, professional operation from the moment they pay — aligned team, clear comms, defined deliverables, dated next steps. For an **AI-native agency** this is the ideal first delivery surface to automate end-to-end: it's template-driven, data-structured, and API-executable — an agent can run the entire sequence (briefing, emails, form chasing, deck assembly, Slack/PM/calendar set-up, follow-up tracking), escalating only sensitive-credential handling and genuine judgement calls to a human.

---

### Cross-references
- **"Signed" + the service agreement** that triggers onboarding → *Sales Leads & Pipeline Management → §7.*
- **The acquisition→delivery handoff & Account Manager role** → *Sales Leads & Pipeline Management → §4 (Onboard phase).*
- **Daily/weekly/monthly cadence** mirrors the ad operating rhythm → *Paid Ads, Email Marketing & Automation → §4.*
- **Named-action / named-owner / dated-deadline** discipline → *Outbound Leads — Hot Outreach* (EOD reporting) and *Sales Leads & Pipeline Management.*
- **Strategic inputs collected in the form** feed the initial strategy, which builds on the **IACP / customer profile** → *Niche & Target Market → Part A.*
- **Next in Service Delivery:** execution, reporting, retention (the following files in this section).

*(Frameworks adapted from the Genflow / Agency Insiders onboarding whiteboards, "Team Briefing Email," "Onboarding Email," "Internal Kick-off Meeting," "Client Onboarding Form," "Client KO Meeting Deck," and "Client KO Call Follow-up Actions.")*
