---
name: grant-application
description: >-
  Expert support for writing, strengthening, and reviewing any funding or opportunity
  application — grants, fellowships, scholarships, prizes, awards, accelerators, residencies,
  RFPs, calls for proposals, concept notes, cover letters, budgets, and pitch decks. Use this
  whenever the user says anything like "I'm applying for a grant / fellowship / funding /
  opportunity", "help me write my proposal", "review my application", "draft a concept note",
  "build my budget", "answer this funder question", or shares a call/RFP/eligibility text and
  wants help responding to it — even if they don't say the word "grant". It blends proven
  fundraising, storytelling, and persuasion frameworks with a disciplined fit-and-criteria
  check so the application is tailored to the specific funder, answers the actual questions,
  stays within the rules, and keeps the applicant's authentic voice and honest claims.
---

# Grant & Opportunity Application

Help people win funding by translating real work into a clear, credible, persuasive case that
fits *this specific* funder and answers *this specific* call. The goal is never to inflate or
generically dazzle — it is to make a genuinely strong project legible to someone who has never
met the applicant or seen their context, and to do it within the funder's rules.

This skill draws on a youth climate/nature fundraising toolkit (co-created by grassroots project
leaders) plus widely used storytelling, persuasion, and proposal-writing frameworks. The core
discipline that ties them together: **understand the call and the applicant before writing, write
to the criteria, and check the draft back against the criteria.**

## The non-negotiables (read first)

These hold across every funding type and every section. Violating them is the fastest way to lose.

1. **Never fabricate.** Do not invent impact numbers, beneficiary counts, partnerships, dates,
   credentials, quotes, or outcomes. If a fact is missing, ask the user for it or mark it clearly
   as a placeholder like `[NUMBER REACHED — confirm]`. A single made-up figure can sink a real
   application and damage trust. Double-check every name, number, and claim the user gives you.
2. **Tailor to the actual funder and call.** Generic applications read as generic. Reflect the
   funder's stated priorities *in the applicant's own words* — never copy-paste their phrases back
   at them. If you don't know the funder's priorities, find them (see step 1).
3. **Answer the actual questions, within the actual limits.** Respect word/character/page limits,
   required sections, file formats, and eligibility rules. An eloquent answer to the wrong question
   scores zero.
4. **Keep the applicant's authentic voice.** Tools can tighten structure and grammar, but the ideas,
   story, and wording must sound like the person. Flattened, "AI-sounding," over-polished prose is a
   red flag to reviewers.
5. **Protect people.** Get consent before telling someone else's story. Don't expose sensitive
   community details, locations, or identities that could create risk. Offer private verification
   (references, photos shared privately, a call) instead of public disclosure when needed.
6. **Be honest about fit.** If the project genuinely doesn't match the funder's geography, theme,
   stage, or eligibility, say so plainly. Forcing a fit wastes the applicant's limited time. Not
   every opportunity is worth applying for.

## Workflow

Follow these steps in order. Don't skip step 1 — writing blind is the most common failure mode.

### Step 1 — Gather the two contexts: the CALL and the APPLICANT

You cannot write a winning application without both. Collect what's missing before drafting.

**The CALL / funder context.** Get (and if a funder name or URL is given, *web-search to confirm*):
- What they fund: themes, target population, geography, project stage, funding type
  (restricted vs. unrestricted/core, project vs. seed, individual vs. registered org).
- Eligibility rules: who can apply, registration requirements, age/region limits, exclusions.
- The questions/sections required, and the **word/character/page limits** for each.
- The **evaluation criteria or scoring rubric**, if stated, and their relative weights.
- Budget cap, allowable/disallowed costs, co-funding or match requirements.
- Deadline, format, submission method, and any required attachments.
- Recent grantees (a fast way to read what they actually back — size, stage, geography).

If the user pasted the call/RFP, extract all of the above from it. If a key piece is missing and
matters (especially criteria, limits, eligibility), ask for it. Use `ask_user_input_v0` for a few
crisp multiple-choice questions on mobile-friendly choices; otherwise ask in prose, one focused
question at a time.

**The APPLICANT / project context.** Get the real material:
- The "why": what they saw or experienced that made them act; why they/their team are well placed.
- What they actually do (current activities), where, with/for whom.
- Proof: 1–3 real numbers, a concrete example of change, or a quote — whatever genuinely exists.
- Stage, team, prior funding, partnerships, registration status.
- The change they're working toward (their Theory of Change, even if rough).
- A realistic budget or cost picture.

If the user has applied before, ask for prior application text — reusing a strong, consistent core
saves time and keeps the story coherent.

### Step 2 — Check fit before investing effort

Write two sentences. If you can't, the fit is weak or the pitch needs sharpening:
1. How the project supports *this funder's* stated priorities (in the applicant's words).
2. What this specific funding would unlock for the project.

Also confirm: Do they fund work like this, in this place, at this stage? Does the applicant meet
eligibility? Is the amount worth the time to apply and report? If fit is poor, tell the user
honestly and suggest better-matched paths rather than forcing it.

> Watch-out: legitimate grants don't charge application fees. If the user describes one, flag it.

### Step 3 — Build the spine (story + logic) before prose

Lock these down first; everything else hangs off them.

- **One-line mission:** *what you do + who it's for + the change you're aiming for.*
- **The narrative arc:** **Problem → Approach → Proof of change → Ask.** This is the backbone of
  almost every proposal, pitch, and cover letter.
  - *Problem:* what's happening and why it matters (specific, not "raise awareness").
  - *Approach:* what you do and why it fits this community/context.
  - *Proof:* one solid number, example, or quote showing it works or that you can deliver.
  - *Ask:* what you need and what it will unlock — linked to the budget.
- **Theory of Change (one sentence):**
  *"Because we [activities], we expect to see [outcomes in 6–24 months], which contributes to
  [long-term impact]."* It only needs to show a clear link: what you do → what changes → the impact.
- **The explicit alignment link** (the persuasion hinge): one sentence on how the work advances the
  funder's priorities, the next on what their funding unlocks. *This turns an "ask" into a
  "partnership"* — and it's what reviewers are scoring.

For deeper storytelling and persuasion technique (the "why you" layers, Made-to-Stick concreteness,
ethical use of Cialdini's persuasion principles, before/after impact stories), read
`references/storytelling-and-persuasion.md`.

### Step 4 — Draft to the criteria

Write each required section to its question and limit. As you draft:
- **Mirror the rubric.** If a criterion is "innovation" or "sustainability" or "community
  leadership," make sure a clearly identifiable part of the answer speaks to it, in plain language.
  Reviewers often score section by section against the rubric — make their job easy.
- **Be concrete.** Replace vague goals with who, where, how many, by when, what will be different.
  "Plant 500 mangrove seedlings with 80% survival across 3 sites by June" beats "restore the coast."
- **Lead with the strongest framing.** If the funder explicitly backs youth/community leadership,
  say it early and confidently. If they fund outcomes, lead with impact and proof, mentioning who
  leads it where it adds credibility.
- **Weave the personal "why"** even if not directly asked — a short, relevant lived-experience note
  shows why this team can deliver. Keep it tied to the project.
- **Use active voice, short sentences, and front-loaded points.** Reviewers skim first; make the
  problem, approach, change, and delivery plan graspable in seconds.

For the standard anatomy of a proposal (need statement, objectives/SMART goals, activities/methods,
evaluation/MEL, sustainability, organizational capacity, budget justification) and how to write each
part well, read `references/proposal-anatomy.md`.

### Step 5 — Build or sanity-check the budget

A budget is the project plan in numbers; it builds trust when every line is explainable in one plain
sentence. Cover the cost types people under-budget: **project costs** (visible delivery costs),
**operational costs** (coordination, admin, comms, finance, safeguarding — what makes it sustainable),
**growth costs**, and **safety & wellbeing costs**. Include the applicant's own time where real; name
in-kind support; add a 5–10% contingency. Match the budget to the plan and to the funder's rules and
cap. For full guidance and a budget table, read `references/budgets-and-financials.md`.

### Step 6 — Run the criteria-check pass (mandatory before finishing)

Check the draft *back against the call*. Go criterion by criterion and confirm each is addressed.
Run the checklist below. Report to the user anything unmet, over-limit, or unconfirmed — don't quietly
paper over gaps. This pass is what separates a submitted-and-forgotten draft from a competitive one.

For the funder-research method, green/red flags, and a detailed criteria-mapping table you can fill in,
read `references/funder-fit-and-criteria-check.md`.

### Step 7 — Offer the right follow-ons

Depending on what they're doing, offer: a tailored cover letter, a 4-sentence project description, a
concept note, a pitch deck outline, an elevator pitch, interview/donor-meeting prep, a match-funding
ask, or a reporting plan. Ready-to-use templates are in `references/templates.md`.

## Final self-check (before you hand anything back)

- [ ] **Criteria:** Every stated evaluation criterion is visibly addressed.
- [ ] **Questions:** Every required question/section is answered — the actual question, not an adjacent one.
- [ ] **Limits:** Within word/character/page limits and the budget cap. (State the count if limits are tight.)
- [ ] **Eligibility:** The applicant clearly meets it (or the path, e.g. fiscal host, is named).
- [ ] **Alignment:** The explicit "supports your priorities / unlocks this" link is present and not forced.
- [ ] **Specificity:** Goals have who/where/how many/by when. No naked "raise awareness."
- [ ] **Proof:** Impact claims are real and, where used, exact figures are confirmed with the user.
- [ ] **Names:** Funder, programme, project, and people names are spelled correctly. (Getting a name
      wrong makes reviewers doubt everything else.)
- [ ] **Voice:** It sounds like the applicant — not flattened or generic.
- [ ] **Budget:** Every line is explainable in one sentence; matches the plan; operational costs included.
- [ ] **Honesty & safety:** No fabrication; consent respected; no risky disclosure of people/places.
- [ ] **Placeholders:** Any `[unconfirmed]` items are flagged to the user, not hidden.

## A note on mindset (worth passing on)

Rejection is feedback, not a verdict on worth — strong applicants apply often, hear "no" more than
"yes," and improve each round. The project has value before, during, and beyond funding; funding is a
tool, not the goal. When useful, reassure honestly without overpromising outcomes you can't guarantee.

## Reference files

- `references/storytelling-and-persuasion.md` — the "why" layers, narrative frameworks (ABT,
  Made-to-Stick/SUCCESs, before-after-bridge), ethical persuasion (Cialdini), and impact-story craft.
- `references/proposal-anatomy.md` — standard proposal sections and how to write each; SMART
  objectives; logic model / Theory of Change; MEL & indicators; sustainability; capacity statements.
- `references/budgets-and-financials.md` — cost categories, what people under-budget, sizing the ask,
  in-kind, contingency, a budget table, and match-funding logic.
- `references/funder-fit-and-criteria-check.md` — how to research a funder, green/red flags (and
  reverse due diligence), and a criteria-mapping table to score your draft before submitting.
- `references/templates.md` — copy-paste templates: 4-sentence project description, Theory of Change
  builder, budget table, cover letter, concept note, elevator pitch, pitch-deck outline, match-funding
  ask, story checklist, and interview/donor-meeting prep.
