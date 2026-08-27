# EBM Scorecard — ICommit

**Status:** pre-launch · **Last reviewed:** [date] · **Review cadence:** quarterly

> **What this is for.** The investment conversation — *should we keep funding this product, and in what?* It is not a weekly steering dashboard, and it is not a measure of team performance. Steering measures live in [North Star Metric (NSM)](North%20Star%20Metric%20%28NSM%29.md); goals for the cycle live in [OKRs](OKRs.md).
>
> **Every target below is a pre-launch hypothesis.** Recalibrate once baselines exist. Empty cells are deliberate — a declared gap is a scope decision; an omitted row is an oversight.

Structured per **The Evidence-Based Management Guide** (Scrum.org, May 2024). *Market value* KVAs — Unrealised and Current Value — reflect customer outcomes. *Organisational capability* KVAs — Time to Market and Ability to Innovate — reflect our ability to deliver them.

---

## Current Value (CV)
*Measures that quantify the value the product delivers today.*

| Measure | Why we chose it | Source | Baseline | Target | Trend |
|---|---|---|---|---|---|
| **Promise Keepers** — monthly active users who fulfil a shared commitment in ≥2 of the last 4 weeks | The North Star. The single number that says whether users get real, repeated value | product analytics | TBC at launch | TBC after baseline | — |
| % of fulfilled commitments that were two-party agreed | Tells us the differentiator is actually being *used*. If most fulfilled commitments are solo, we deliver value but the positioning quietly stops being true | product analytics | TBC at launch | ≥80% | — |
| % of shared commitments fulfilled on or before due date | Maps straight to the vision — *"nobody has to chase."* A commitment kept three weeks late was still kept, but someone chased | product analytics | TBC at launch | ≥70% | — |
| **Conversion to paid** | CV covers value to customers *and* to the organisation. Declared rather than omitted so the gap is a decision, not an oversight | billing | not measurable pre-launch | ≥8% of signups within 30 days | — |

---

## Unrealised Value (UV)
*Measures that quantify the potential future value if we met the needs of all potential customers.*

| Measure | Why we chose it | Source | Baseline | Target | Trend |
|---|---|---|---|---|---|
| % of interviewed fathers who already maintain a deliberate workaround | Behavioural proof of unserved need — they have already paid a cost to solve this themselves. Stated pain is an opinion; a maintained spreadsheet is a fact | discovery interviews (n≈10) | not yet run | — | — |
| % of surveyed fathers reporting a forgotten or chased family commitment in the last 30 days | Prevalence across the population. Read against the row above: problem widespread but few workarounds = an *adoption* problem, not a *demand* problem | survey (n≈100) | not yet run | — | — |
| % of addressable population currently served | The literal headroom — UV is the remainder. The only UV measure that keeps moving after launch, and the one that turns a rising Current Value into a decision | national statistics + product analytics | 0% — sizing not yet done | — | — |

> **Denominator definition (fixed — do not change quietly):** households in Greater Cairo with at least one school-age child × shared-responsibility households × smartphone-using. Changing this scope changes the share without changing the product, so any revision must be stated and re-baselined.

> Targets are intentionally blank. UV measures are descriptive — we are sizing an opportunity, not steering toward a number.

---

## Time to Market (T2M)
*Measures that quantify how quickly we can deliver new capability.*

| Measure | Why we chose it | Source | Baseline | Target | Trend |
|---|---|---|---|---|---|
| **Time to learn** — days from an assumption being logged to a decision being recorded | Pre-launch, learning speed *is* delivery speed. This is the loop everything else depends on. The clock stops at the **decision**, not the data — evidence sitting unread has not closed a loop | assumption test log | ~14 days (planned, not yet run) | ≤14 days | — |
| **Time to first user contact** — days from *"we need to know X"* to the first conversation with a real user about it | Isolates the largest delay inside the loop above. Currently unbounded — the tests are designed and not run | discovery log | not yet — no interviews run | ≤7 days | — |
| **Lead time** — idea accepted → live for users | The post-launch version of the same question. Declared now so the row exists before there is data | delivery tooling | not measurable pre-launch | — | — |

---

## Ability to Innovate (A2I)
*Measures that quantify our effectiveness at delivering new capabilities that might better meet customer needs.*

| Measure | Why we chose it | Source | Baseline | Target | Trend |
|---|---|---|---|---|---|
| **Employee Engagement** — degree to which employees are aligned with and bought into the goals | A team not bought into what it is building cannot innovate on it. Distinct from Employee Satisfaction (CV), which measures feeling rather than alignment | team survey | not measurable — no team yet | — | — |
| **Innovation Rate** — % of effort on new capability ÷ total product effort | The headline A2I measure, and the one that makes technical debt legible to a business audience | delivery data | not measurable pre-launch | — | — |
| **On-Product Index** — time on the product ÷ total available team time | Exposes how much paid capacity actually reaches the product rather than the organisation around it | time / work tracking | not measurable pre-launch | — | — |
| **Technical Debt Ratio** — remediation effort ÷ development effort | Structural quality is the leading indicator of future slowdown | static analysis (e.g. SonarQube) | no codebase yet | <5% | — |

---

## Interpretation

**Weakest area: Unrealised Value.** Not because the number is bad — because there is no number, and pre-launch it is the KVA that decides whether this product is worth building at all. Current Value is empty *by definition* before release; the Guide says so directly. UV is empty *by omission*.

**A2I is entirely undeclared**, and that is honest: no team, no codebase, no capacity to divide. It becomes measurable the moment development starts, and the choices being made now — Definition of Done, quality standards, architecture — will determine what those numbers read in year two.

**T2M has the one live signal, and it is unflattering.** Time to first user contact is currently unbounded. The tests are designed, ranked by risk, and not run.

### Action

**Run the five discovery interviews.** One action populates two KVAs at once — UV rows 1 and 2, and it starts the T2M clock. Nothing else on this scorecard can move until it happens.

---

## Related

| Artifact | Job |
|---|---|
| [North Star Metric (NSM)](North%20Star%20Metric%20%28NSM%29.md) | Weekly steering — the NSM with its input metrics and counter-metrics |
| [OKRs](OKRs.md) | Goals for the current cycle |
| [Product Goal](../Product%20Goal.md) | The near-term outcome and its success measures |
| [Biggest untested assumptions](../biggest-untested-assumptions.md) | What could be wrong, ranked, with the test for each |
| [Learning Notes](Learning%20Notes) | Why each measure on this page was chosen, and what was rejected |

**Source:** The Evidence-Based Management Guide, Scrum.org, May 2024.
