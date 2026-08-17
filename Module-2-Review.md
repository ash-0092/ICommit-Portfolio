# Module 2 Review — ICommit
### Reviewed against Module 2 (Vision & Product Strategy) and Pichler's own checklists · [date]

---

## Scorecard

| Artifact | Score | One-line verdict |
|---|---|---|
| Elevator pitch | 3/5 | Great differentiator, no target group |
| Product Vision Board | 3/5 | Solid Needs and Product; Target Group and Business Goals fail their checklists |
| GO Product Roadmap | 3.5/5 | Best artifact of the four. Fix the Date row and trim the metrics |
| Product Goal | 3/5 | Well-structured, but sitting at vision altitude — duplicates a rung |
| **Consistency across all four** | **2/5** | **Four documents, three different target groups. Fix this first.** |

**Overall: you did the work properly. The gaps are alignment and specificity, not effort.**

---

## The three things that matter most

### 1. Your target group changes in every document ⚠️ *fix first*

| Document | Says the customer is |
|---|---|
| Elevator pitch | "Any person with access to the internet" |
| Vision Board | Fathers, Mothers, Students, Teenagers, Work colleagues |
| Lean Canvas | 5 segments; early adopters = fathers |
| Product Goal | "Every father (employed or unemployed)" |

Pichler's Target Group checklist requires **Cohesive** — members share similar attributes. Teenagers and work colleagues share nothing with fathers in lifestyle, disposable income, or willingness to pay. And "any person with internet access" excludes nobody, which is the definition of a failed target group.

**You already made the decision** — your Lean Canvas and Product Goal both say fathers. The other two documents just haven't caught up.

**Fix (30 min):** pick fathers, add attributes, propagate to all four documents.

> **Target group:** Fathers aged 30–45 with school-age children, in dual-responsibility households, who already use a smartphone daily and currently juggle family commitments via WhatsApp, memory, and verbal promises.
>
> *Secondary (later):* mothers in the same households. *Not now:* students, teenagers, workplace teams.

---

### 2. Your ladder has a duplicated rung

Module 2's ladder: **Vision → Strategy → Product Goal → Sprint Goal → Backlog Item.**

What you actually have:

```
Vision (README)        "everyone ... never see commitments out of hand"
Vision Board vision    "Making fulfilling commitments easy with shared understanding"
Product Goal.md        "Every father can track and manage commitments collaboratively"   ← still vision altitude
Roadmap 1.0 goal       "User can create, track and manage commitments ..."               ← this is your real Product Goal
```

Your Product Goal is unbounded and can never be verifiably reached — that's a vision, not a goal. Meanwhile your roadmap 1.0 goal is at the right altitude but phrased as a capability.

**Fix (20 min):** promote the 1.0 roadmap goal into `Product Goal.md`, sharpened into an outcome:

> **Product Goal:** A father and one other person can agree, track and complete a shared commitment end-to-end — so that within a week of signing up, a new user has fulfilled at least one commitment that someone else agreed to.

Then `Product Goal.md`'s current content becomes your **vision**, and the README vision is retired (you currently have two).

---

### 3. Everything on the board is an untested hypothesis

Pichler's **Overall Criteria → Validated** says the Target Group, Needs, Product and Business Goal sections should contain no major unvalidated hypotheses. Right now every box does — and nothing in the folder names them.

That's completely fine at this stage, but Module 2 Exercise 2.1 asks you to *write them down*. They become your Module 4 discovery backlog.

**Fix (15 min):** add to the bottom of your vision board notes:

> **Biggest untested assumptions:**
> 1. Fathers experience commitment-tracking as painful enough to adopt a new app (vs. WhatsApp + memory).
> 2. The two-party sign-off is felt as *trust-building*, not as *bureaucratic friction between family members*. ← riskiest
> 3. Someone will pay for this; family/group packages are the primary revenue driver.

Assumption 2 is the one that kills the product if it's wrong. Test it first in Module 4.

---

## Per-document notes

### Vision-Elevator_Pitch.md

**Right:** all six slots filled; the "Unlike / our product" clause is genuinely differentiated and defensible — shared agreement between two parties is a real wedge, and it's the strongest single sentence in the whole set.

**Fix:**
- Target group (see above)
- "Cloud based application" is an implementation detail, not a category people shop in
- "Makes fulfilling commitments easier" — no outcome. What changes?
- Your real competitor is missing: **the status quo** — WhatsApp, verbal promises, memory. Calendars aren't what people use for this
- Typos: *engagin* → engaging; *it's* → its

**Suggested rewrite:**

> **For** fathers juggling family, work and school commitments
> **who** currently rely on memory, WhatsApp and verbal promises — and end up chasing or being chased,
> **the** ICommit app **is a** shared commitment tracker
> **that** makes sure commitments between two people actually get done, with no chasing and no ambiguity about who agreed to what.
> **Unlike** calendars, to-do lists and task managers — or the WhatsApp thread most families use today —
> **our product** requires both people to explicitly agree to a commitment and its sub-commitments before it starts, so accountability is shared rather than assumed.

---

### Product-Vision-Board-with-Checklist.pdf

**Right:**
- **Needs** — well done. Outcome-based, prioritised, and you correctly put the differentiated need (shared understanding) at the top rather than the generic one
- **Product** — 3 coarse-grained features, under the limit of five, differentiator listed first ✓
- Needs-first sequencing followed ✓

**Fix:**

| Box | Checklist criterion failed | What to do |
|---|---|---|
| Vision | **Ambitious** — "making X easy" isn't a big, audacious goal for 5–10 years | Raise the ceiling: *"A world where a promise between two people is never forgotten, and nobody has to chase."* |
| Vision | typo: *fulfulling* | — |
| Target Group | **Cohesive, Specific** | See fix #1 |
| Needs | **Specific** (detailed enough to validate) | "Commitments are less to get out of hand" — how would you validate that? Add the missing emotional need: *not having to nag or chase* — your own README example (school papers) is exactly this, and it's your strongest need |
| Product | **Type** not stated | Say it: "mobile app (iOS + Android) with a web companion" |
| Business Goals | **Specific** — "state rough targets if possible" | Currently zero numbers. Add them: *"1. £X MRR / N paying subscribers within 12 months. 2. 30% of revenue from family packages by month 9."* |
| Business Goals | Wording | "Create a new revenue source" implies an existing company with other products. If ICommit is standalone, say what the business outcome actually is |

---

### GO-Product-Roadmap-with-Checklist.pdf

**Your best artifact.** Metrics are quantified, features are coarse-grained, and your git history shows you already revised the goal to be more outcome-based — good instinct.

**Fix:**

- **DATE row holds durations, not dates.** "3 months" then "2 months" — is 2.0 two months after 1.0, or two months total? The checklist wants "Q1" or "1st February." Use **Q1 2027 / Q2 2027**, or **Month 3 / Month 5**.
- **Goals are capability statements, not outcomes.** "User can easily create, track and manage commitments" describes what the product does. Rewrite as what changes:
  - *1.0:* "A new user completes their first shared commitment with someone else within 7 days of signup."
  - *2.0:* "Families run their recurring shared responsibilities in ICommit instead of WhatsApp."
- **"Events" appears in the 2.0 goal from nowhere** — it's not in your vision board, lean canvas or product goal. Either define it or drop it.
- **Trim the metrics.** 2.0 has nine. Checklist wants precise; practically, pick **one primary + 2–3 supporting**, everything else is a guardrail.
- **Cut the vanity metric:** *"100% of new users login to the application"* is true by definition — it measures nothing.
- **Your most important metric is missing.** Your Product Goal says *80% of users actively fulfilling commitments weekly* — that's your North Star, and it doesn't appear on the roadmap at all. Put it on 1.0 as the primary metric.
- **Move bug counts off the roadmap.** "Not more than 3 critical bugs/day" is a quality guardrail — it belongs in your Definition of Done (Module 5), not as a goal metric. (Also: 3 critical bugs a day is very high for a new product.)
- **Make metrics time-bound consistently** — some say "after 1 month of release", most don't.
- *"100% of active users still active"* is untestable as worded — you mean retention. Say: "80% of month-1 actives are still active in month 3."
- Pricing items ("First 3 commitments free", "Individual subscription") are business-model decisions sitting in the Features row. Fine to keep, but flag them as your **riskiest untested assumption** — you have no evidence anyone will pay.

⚠️ **Technical issue worth fixing:** the PDF's saved field values and its visible rendering disagree. Opened normally it shows *"At least 10% invites people"* and *"Subscription (monthly/yearly)"*, while the stored values say *5%* and *"Subscription - Individual"*. Anyone reviewing your portfolio may see stale text. **Re-save or flatten the PDF**, then re-check.

Leaving columns 3 and 4 empty is correct — don't plan further than you can see. Just add a one-line note saying that's deliberate, so it doesn't read as unfinished.

---

### Product Goal.md

**Right:**
- First document with a specific target group ✓
- Has success measures, a "why now", and an explicit NOT-doing section — most people skip that last one entirely. Genuinely good.
- Timeframe correctly labelled as not a commitment ✓
- One Product Goal, not three ✓ (Scrum Guide: fulfil or abandon one before taking the next)

**Fix:**
- **Altitude** — see fix #2. This is a vision.
- **Numbers conflict with your roadmap.** Here: *"at least 50% of subscriptions are family packages."* Roadmap 2.0: *"at least 30% upgrade to Group."* Pick one.
- **Timeframe conflict.** You say 3 months, matching release 1.0 — but both of your success measures depend on *group/family* features, which are in release 2.0. The goal spans both releases.
- **Define "actively fulfilling."** 80% weekly is aggressive and currently unmeasurable. Make it concrete: *"marks at least one commitment as Done per week."* Then decide if 80% is realistic (it's very high — 30–40% would be a strong result).
- **Add a scope exclusion.** "We're not telling people how to commit" is a good *product principle*, but it's not a scope boundary. Add one: *"Not in this goal: workplace/team workflows, calendar sync, recurring commitments, enterprise accounts."*
- Typos: *collabortive*, *needs* → need

---

## Still missing from Module 2

| Exercise | Status |
|---|---|
| 2.1 Vision Board + assumptions | Board ✓ · assumptions ✗ |
| 2.2 Reverse-engineer 3 real strategies | ✗ — do this, it's the "product sense" interview muscle |
| 2.3 Product Goal rewriting | Partially |
| 2.4 GO roadmap | ✓ |
| 2.5 Impact map | ✗ |
| 2.6 Ladder test (10 items) | ✗ — you don't have a backlog yet; do it in Module 5 |

---

## Do these next, in this order (~90 minutes total)

1. **[30 min]** Fix the target group to "fathers + attributes" in all four documents.
2. **[20 min]** Move the roadmap 1.0 goal up into `Product Goal.md` as an outcome; demote the current Product Goal text to vision; retire the duplicate README vision.
3. **[15 min]** Write your three biggest assumptions at the bottom of the vision board notes. Mark the riskiest.
4. **[10 min]** Put a number on your Business Goals. Any number. You can be wrong; you can't be silent.
5. **[10 min]** Trim roadmap metrics to one primary + 3 supporting per release; add the fulfilment metric to 1.0; move bug counts out.
6. **[5 min]** Re-save the roadmap PDF so the visible text matches the stored values.

Then you're ready for Module 3 — and your EBM scorecard will be much easier to build, because you'll finally have numbers to attach.
