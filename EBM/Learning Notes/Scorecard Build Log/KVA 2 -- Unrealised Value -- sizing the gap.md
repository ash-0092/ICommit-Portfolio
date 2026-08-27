### The question Unrealised Value answers

How much **more** value could we capture if the product met all the needs of all potential customers. It is the size of the gap between where we are and the ceiling.

**Why it matters most pre-launch:** Current Value is empty by definition before release. UV is the KVA that answers *"is this worth building at all?"* — and it is measurable today, without a product.

---

### Argument 1 — Assumption tests are not measures

I proposed three measures. Two of them (*fathers feel the pain most*, *sign-off reads as trust not friction*) were assumptions A1 and A2 from `biggest-untested-assumptions.md`.

| | Assumption test | Measure |
|---|---|---|
| Shape | Pass/fail threshold | A value that moves |
| Runs | Once, as a gate | Repeatedly, on a cadence |
| Answers | "Should we proceed?" | "How are we doing?" |
| Home | Assumptions file | Scorecard |

Once an assumption test passes, its row freezes forever. **A scorecard row that can never move again is dead weight.**

Same principle as NSM file vs scorecard: two artifacts, two jobs, one home per item.

**Result:** A1 and A2 stay in the assumptions file. They were never scorecard rows.

---

### Argument 2 — My third measure survived, reworded

My original: *"≥50% of fathers experience commitment tracking as painful."*

That one was a genuine UV measure — prevalence of the problem in the target population. It was kept, with one change: **from a feeling to an event.**

- Before: *"experience it as painful"* → a self-reported opinion
- After: *"reported a forgotten or chased commitment in the last 30 days"* → an event they can recall

Same instrument, same population. This is the interview principle (past behaviour beats stated opinion) applied to a survey.

**Methods note:** I had written "100 interviews and surveys". These are different instruments doing different jobs — interviews (n≈10) give depth and mechanism; surveys (n≈100) give prevalence. 100 interviews is not feasible for one person, and a survey cannot explain *why*. Keep them separate.

---

### Argument 3 — Is sizing really Unrealised Value?

I pushed back that bottom-up market sizing felt like market research, not UV.

**It is half the definition.** UV = *"value that could be realised if the product met all the needs of all potential customers."* Decompose it: "all potential customers" is the sizing term; "met all their needs" is the gap term. The EBM Guide's own example UV measures include market share and potential-customer count.

**But the objection was sound** — raw addressable population barely moves, and I had just argued that static rows are dead weight.

**Result:** converted from a static number to a ratio — `% of addressable population currently served`. Pre-launch it is 0%; post-launch it becomes a live trend. The sizing work supplies the denominator.

---

## What each measure means

**1. % of interviewed fathers who already maintain a deliberate workaround**

A workaround someone keeps by hand — a spreadsheet, a recurring alarm, a pinned chat — is *behavioural* evidence of unserved need. They have already decided the pain exceeds the cost of building a fix themselves.

Stated pain is an opinion. A maintained workaround is a fact.

**2. % of surveyed fathers reporting a forgotten or chased commitment in the last 30 days**

How widespread the problem is across the target population.

**Read it against measure 1.** If 70% report the problem but only 10% maintain a workaround, the pain is real but tolerable — that is an *adoption* problem, not a *demand* problem. One number alone cannot tell you which situation you are in. The gap between them is the finding.

**3. % of addressable population currently served**

```
addressable population  = everyone who could plausibly be a customer   (denominator)
currently served        = how many we actually have                    (numerator)
% served                = numerator / denominator
```

**Unrealised Value is the remainder.** Serve 3%, and 97% of the capturable value is still sitting there. This is UV in its most literal form.

**Why it belongs on a scorecard rather than in a market-research doc — it changes the decision.** Read against Current Value:

| | Low % served | High % served |
|---|---|---|
| **Strong Current Value** | Room to grow, product works → **invest in growth** | Near the ceiling → **harvest, or find a new segment** |
| **Weak Current Value** | Wrong product, or too early → **keep learning, don't scale** | Own a market that wants little → **rethink** |

Without this measure, a rising Current Value always looks like success. With it, you can tell *"growing into a large opportunity"* apart from *"efficiently saturating a small one."* Those need opposite decisions.

**Worked example (all figures illustrative — replace with cited sources):**

```
Households in Greater Cairo with >=1 school-age child        2,000,000   [CAPMAS]
x  % shared-responsibility (both parents coordinating)             60%   [CAPMAS / survey]
x  % smartphone-using                                              85%   [national ICT stats]
-------------------------------------------------------------------------
=  Addressable households                                    ~1,020,000
```

| | Served | % of addressable | UV headroom |
|---|---|---|---|
| Launch | 500 | 0.05% | 99.95% |
| Month 12 | 10,000 | ~1% | ~99% |
| Year 3 | 100,000 | ~10% | ~90% |

**What fell out of doing this arithmetic once:** the Vision Board target of *10,000 active users within 12 months* is roughly **1% of addressable**. That is either the right ambition for a first year, or an under-aim — but it is now a known quantity rather than a number picked because it sounded big.

**Two cautions:**

- **The denominator is a choice, not a fact.** *Fathers in Greater Cairo* / *parents across Egypt* / *families across MENA* produce wildly different shares for the same product. State the definition on the scorecard.
- **It is the easiest UV measure to game** — shrink the denominator and the share looks excellent. Which is exactly why the definition goes in writing next to the number, and does not change quietly. Same discipline as locking a threshold before taking a baseline.

---

### Final result

| Measure | Why we chose it | Source | Baseline | Target | Trend |
|---|---|---|---|---|---|
| % of interviewed fathers who already maintain a deliberate workaround | Behavioural proof of unserved need — they have already paid a cost to solve it themselves | discovery interviews (n≈10) | not yet run | — | — |
| % of surveyed fathers reporting a forgotten or chased commitment in the last 30 days | Prevalence across the population. Read against row 1 to tell a demand problem from an adoption problem | survey (n≈100) | not yet run | — | — |
| % of addressable population currently served *(denominator: Greater Cairo households with school-age children, shared-responsibility, smartphone-using)* | The literal headroom. The only UV measure that keeps moving after launch, and the one that turns a rising Current Value into a decision | national statistics + product analytics | 0% — sizing not yet done | — | — |

**Note the empty Target column.** UV measures are largely descriptive — you are sizing an opportunity, not steering toward a number. Do not invent targets to fill cells.
