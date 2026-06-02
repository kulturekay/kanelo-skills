---
name: kanelo-service-business-os
description: Kanelo Labs' reusable service-business operating system. Use whenever an agent makes a decision about service/niche selection, market validation, IACP/ICP, positioning and messaging, offer creation, pricing, outreach, sales calls, pipeline management, onboarding, delivery, hiring/training (humans or agents), retention, and expansion — and to evaluate any venture hypothesis it is handed. It routes each decision to the right reference playbook, applies Kanelo's positioning rules, and enforces required output and approval rules before anything reaches Caleb. Trigger this skill whenever a task touches how Kanelo finds, signs, serves, keeps, or expands customers, even if the request does not name a specific playbook. Don't use for general software, coding, or infrastructure tasks, or for anything unrelated to how Kanelo finds, signs, serves, keeps, or expands customers.
---

# Kanelo Service-Business OS

This skill is the routing and judgment layer over Kanelo Labs' service-business knowledge base. It does **not** restate the source material. It tells you which reference file to open for a given decision, which lifecycle **stage** you are operating in, how to translate the source tactics through Kanelo's positioning, and what every output must contain before it goes to Caleb.

The canonical operating knowledge lives in `references/` (14 playbooks). Read only the file(s) relevant to the task — do not load all 14 references at once. Venture hypotheses are **not** stored in this skill: they are handed to you as task input (the task brief or a linked doc). This skill supplies the *method* for evaluating them (§7), never the hypothesis content itself.

---

## 1. Long-term purpose

This skill is Kanelo Labs' service-business operating system. Use it whenever agents make decisions about:

- service / niche selection
- market validation
- IACP / ICP
- positioning and messaging
- offer creation
- pricing
- outreach
- sales calls
- pipeline management
- onboarding
- delivery
- hiring / training humans or agents
- retention and expansion

It is durable infrastructure, not a one-task script. The same routing applies whether Kanelo is validating its first market or scaling a proven one. If a task touches how Kanelo **finds, signs, serves, keeps, or expands** customers, start here.

---

## 2. Stage-Based Routing

Identify which stage the task belongs to, then open only that stage's references. Stages run in sequence, but you re-enter earlier stages whenever evidence changes.

**Current stage: A — Validation.** (See §8, KAN-2A.) Confirm or correct the market and offer hypothesis with real evidence before building acquisition machinery, delivery systems, or team.

### A. Validation
Confirm (or correct) the market + offer hypothesis with evidence.
- `references/01-service-and-niche.md`
- `references/02-niche-and-target-market.md`
- `references/03-high-converting-offers.md`
- `references/04-sign-clients-like-never-before.md`
- `references/07-outbound-leads-hot-outreach.md`
- `references/10-sales-leads-pipeline-management.md`

### B. Offer + acquisition
Sharpen the offer and stand up repeatable lead flow.
- `references/02-niche-and-target-market.md`
- `references/03-high-converting-offers.md`
- `references/04-sign-clients-like-never-before.md`
- `references/05-inbound-leads-personal-branding.md`
- `references/06-landing-pages-funnels-vsls.md`
- `references/07-outbound-leads-hot-outreach.md`
- `references/08-outbound-leads-automated-cold-outreach.md`
- `references/10-sales-leads-pipeline-management.md`

### C. Delivery
Onboard, run, and retain the clients you signed.
- `references/11-client-onboarding.md`
- `references/12-managing-team-execution.md`
- `references/14-client-portfolio-management.md`

### D. Scaling
Increase volume and capacity without breaking quality.
- `references/08-outbound-leads-automated-cold-outreach.md`
- `references/09-paid-ads-email-marketing-automation.md`
- `references/12-managing-team-execution.md`
- `references/13-hiring-training-your-team.md`
- `references/14-client-portfolio-management.md`

### E. Retention and expansion
Keep and grow existing accounts.
- `references/14-client-portfolio-management.md`
- `references/12-managing-team-execution.md`
- `references/09-paid-ads-email-marketing-automation.md` *(only if email/automation is involved)*

If a task spans several stages, open the files in the order of the Kanelo operating sequence (niche → IACP → offer → outreach → sales → pipeline → onboarding → delivery → team → retention/expansion), not all at once.

---

## 3. Source routing

For each reference, this is when to open it, the decisions it informs, and the outputs it should shape.

### `01-service-and-niche.md` — Service and Niche
- **When:** choosing or re-testing the service and market hypothesis.
- **Decisions:** what Kanelo sells, to whom, and why now.
- **Outputs:** service definition, niche shortlist, market hypothesis.

### `02-niche-and-target-market.md` — Niche & Target Market
- **When:** defining who the buyer is and how to speak to them.
- **Decisions:** IACP / ICP, segment priority, core message.
- **Outputs:** IACP profile, positioning statement, messaging angles.

### `03-high-converting-offers.md` — High-Converting Offers
- **When:** building or revising the offer and price.
- **Decisions:** offer structure, guarantee, packaging, price point.
- **Outputs:** offer doc, pricing options, value justification.

### `04-sign-clients-like-never-before.md` — Sign Clients Like Never Before
- **When:** preparing for or reviewing sales conversations.
- **Decisions:** call structure, objection handling, close.
- **Outputs:** sales script, discovery questions, objection map.

### `05-inbound-leads-personal-branding.md` — Inbound & Personal Branding
- **When:** building inbound demand and DM flow.
- **Decisions:** content angles, channel, DM strategy.
- **Outputs:** content plan, profile/bio, DM scripts.

### `06-landing-pages-funnels-vsls.md` — Landing Pages, Funnels, VSLs
- **When:** building conversion assets.
- **Decisions:** funnel shape, page structure, VSL narrative.
- **Outputs:** page copy outline, funnel map, VSL script. *(Internal drafts only — see Approval rules.)*

### `07-outbound-leads-hot-outreach.md` — Outbound: Hot Outreach
- **When:** doing high-touch, researched, person-by-person outreach.
- **Decisions:** target list logic, personalization, sequence.
- **Outputs:** outreach research, message drafts, follow-up cadence. *(Draft only — do not send.)*

### `08-outbound-leads-automated-cold-outreach.md` — Outbound: Automated Cold
- **When:** scaling outbound with tooling/automation.
- **Decisions:** list-building, sending infrastructure, volume.
- **Outputs:** campaign structure, sequence copy, sending plan. *(Draft only — do not send.)*

### `09-paid-ads-email-marketing-automation.md` — Paid Ads & Email Automation
- **When:** running paid acquisition or owned email/automation.
- **Decisions:** channel, budget logic, automation flows.
- **Outputs:** ad/test plan, email flow maps, automation spec. *(Spend requires approval.)*

### `10-sales-leads-pipeline-management.md` — Sales & Pipeline Management
- **When:** managing leads through stages and handing off signed deals.
- **Decisions:** pipeline stages, qualification, deal handoff.
- **Outputs:** pipeline definition, stage criteria, handoff checklist.

### `11-client-onboarding.md` — Client Onboarding
- **When:** a pilot or deal has closed and delivery begins.
- **Decisions:** onboarding steps, expectations, kickoff.
- **Outputs:** onboarding plan, kickoff agenda, intake checklist.

### `12-managing-team-execution.md` — Managing Team Execution
- **When:** running delivery operations across humans/agents.
- **Decisions:** workflow, ownership, quality control.
- **Outputs:** delivery SOP, RACI/ownership map, QA loop.

### `13-hiring-training-your-team.md` — Hiring & Training Your Team
- **When:** adding or training people or agents.
- **Decisions:** roles, hiring bar, training path.
- **Outputs:** role spec, hiring rubric, training plan / agent brief.

### `14-client-portfolio-management.md` — Client Portfolio Management
- **When:** retaining and expanding existing accounts.
- **Decisions:** retention risk, expansion offers, account health.
- **Outputs:** account health review, retention plan, expansion proposal. *(Customer-facing steps require approval.)*

---

## 4. Kanelo positioning rules

Apply these to every recommendation, regardless of which reference you used.

Kanelo does **not** sell "AI agents" as novelty.

Kanelo helps founder-led service businesses turn scattered tools, messy operations, and ad hoc AI usage into **reliable operating loops that create measurable business outcomes**.

When a source playbook suggests a tactic, translate it through these priorities:

- outcomes over workflows
- customer evidence over ideas
- revenue over demos
- repeatability over novelty
- integration and ownership over tool hype
- research before outreach
- paid validation before software

If a tactic in a reference conflicts with these priorities, flag the conflict in the output rather than following it blindly.

---

## 5. Output requirements

Every output produced using this skill must explicitly state, in this order, as a clearly labelled block at the top or bottom of the output:

1. **Source files used** — which reference(s) in `references/` (and which provided hypothesis, if any) informed the work.
2. **Stage** — where this sits in the Kanelo operating sequence (A–E).
3. **Assumptions made** — what was taken as given.
4. **Evidence still missing** — what would need to be true and is not yet confirmed.
5. **Decision or recommendation** — the actual call.
6. **Caleb approval required** — yes/no, and for what specifically.
7. **Next action** — the single next step.

Do not bury these.

---

## 6. Approval rules

Agents **may**:

- research
- summarize
- compare
- draft
- score
- recommend
- create internal plans
- create internal playbooks

Agents **may not**, without Caleb's explicit approval:

- contact customers
- publish externally
- send outreach
- change pricing
- commit to deadlines
- spend money
- change company strategy
- make customer-facing promises

When a task would cross one of these lines, stop at the draft/recommendation stage, mark "Caleb approval required: yes," and describe exactly what you would do on approval.

---

## 7. How to Evaluate Venture Hypotheses

Use this skill to evaluate **any** venture hypothesis you are handed — supplied in the task brief, a linked doc, or the company workspace. The hypothesis is *input to the task*; this skill provides the evaluation method, not the hypothesis content. Nothing per-venture is stored in the skill itself.

**A venture hypothesis is not company strategy until Caleb approves it.** Treat every hypothesis you're given as a candidate to be tested against evidence — never as an adopted direction, and never as canonical operating knowledge. Do not merge venture material into the `references/` knowledge base.

When evaluating a venture hypothesis, open the relevant reference files (usually the Validation-stage set) and produce:

- **Summary of the hypothesis**
- **Target buyer**
- **Pain / desired outcome**
- **Current alternatives**
- **Willingness-to-pay evidence**
- **Buyer access**
- **Delivery feasibility**
- **Risks**
- **Assumptions**
- **Validation plan**
- **Recommendation:** confirm, modify, park, or reject

Deliver the evaluation with the full Output Requirements block from §5. A recommendation to "confirm" is a recommendation only — adopting it as strategy still requires Caleb's approval (§6).

---

## 8. KAN-2A guidance

For **KAN-2A market research**:

- Use the **Validation stage** references (§2.A).
- Compare possible first markets.
- Include **boutique B2B agencies** and the **Claude Cowork Ops / small accounting-bookkeeping firms** hypothesis (provided in the KAN-2A task brief) as candidates.
- Recommend whether to **confirm, modify, or replace** the boutique B2B agency hypothesis.
- **Hard stop:** do **not** proceed to ICP, target list, outreach, or pilot materials until Caleb approves the research brief. KAN-2A ends at a recommendation, not at execution.

Deliver KAN-2A with the full Output Requirements block from §5, and set "Caleb approval required: yes — to proceed past research into ICP/targeting/outreach."
