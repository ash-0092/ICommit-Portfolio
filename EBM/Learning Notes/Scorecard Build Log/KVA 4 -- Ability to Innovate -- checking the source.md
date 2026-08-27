### The question Ability to Innovate answers

*The effectiveness of an organization to deliver new capabilities that might better meet customer needs.*

The Guide frames it as two questions: **what prevents the organization from delivering new value?** and **what prevents customers from benefiting from that innovation?**

A2I degrades as low-value features, technical debt, defects and operational drag accumulate — each consuming budget and time that could have gone to new capability.

---

### The correction that matters most in this note

**Claude asserted that Employee Engagement was a Current Value measure and was wrong.** It was arguing from the **2020** EBM Guide. The current guide is **May 2024** — and it lists Employee Engagement as the **first row of the A2I table**:

> **Employee Engagement** — *A measure of the degree to which employees are aligned with and bought in to the organization's goals.*

**The lesson is not about EBM. It is about sourcing.** Frameworks get revised. Before arguing from a source, check which version you are holding. This applies to me in interviews as much as to Claude here — quoting a superseded guide confidently is worse than saying "I'd need to check."

**Both measures exist, and the distinction is deliberate:**

| | KVA | Measures |
|---|---|---|
| **Employee Satisfaction** | Current Value | How people *feel* — sentiment, energy, enthusiasm. Value the organisation realises today |
| **Employee Engagement** | Ability to Innovate | Whether people are *pointed at the same thing* — aligned with and bought into the goals |

A team can be satisfied and misaligned. Satisfaction is value now; alignment is capacity to build what comes next. The 2020 Guide already hinted at this in the A2I prose — it lists *"inability to hire and inspire talented, passionate team-members"* among the things that impede A2I. The 2024 revision made it measurable.

**My reasoning was sound:** a team that isn't bought into what it's building can't innovate on it, however satisfied it is.

---

### Argument — two of three formulas were wrong

**On-Product Index.** I wrote `time spent on product and value / total time working on product`. Numerator and denominator are nearly the same, so the ratio is ~1 by construction and the measure cannot fail.

The Guide defines it as *"the percentage of time teams spend working on product and value."* The denominator is **total available team time** — including meetings, org admin, context-switching, support rotations, other products. The point is to expose how much paid capacity actually reaches the product. A team at 45% is being consumed by the organisation around it, which is an innovation constraint unrelated to how hard anyone works.

**Technical Debt Ratio.** I wrote `cost of fixing defects / cost of rebuilding`.

Defects are not technical debt. A defect is broken behaviour; technical debt is structural quality that slows *future* work — the Guide calls it *"the extra development and testing work that arises when 'quick and dirty' solutions result in later remediation."*

```
TDR = remediation effort / development effort
```

My **<5% target was correct** — that is the standard "A" rating threshold in tools like SonarQube. Right benchmark, wrong numerator.

**Innovation Rate was missing**, and it is the headline A2I measure: *"the percentage of effort or cost spent on new product capabilities, divided by total product effort or cost."*

This is the measure that turns technical debt into a business number. *"60% of our capacity goes to keeping the lights on"* is a sentence a CFO acts on. Translating technical reality into business language is the single strongest thing an engineering background brings to product ownership.

---

### Decision — declare all four, measure none

Two options were on the table:

- **A** — declare Employee Engagement like the other three: source named, target blank, baseline "not measurable — no team yet"
- **B** — redefine it into something measurable today (are the people I'd need convinced?)

**Chose A.** It keeps the Guide's definition intact. B starts bending a defined KVM to fit my circumstances, which is the habit this whole exercise has been pushing against.

**A2I is therefore entirely empty pre-launch, and that is the honest state.** Four declared rows, no data, because there is no team, no codebase and no delivery capacity to divide. Empty cells are information: they say *"we have no capacity data because we have no capacity yet."*

A2I is the weakest KVA on this scorecard, and the interpretation line should say so.

---

### One idea rejected

Claude floated measuring *my own effort split* — time spent on new learning vs reworking existing artifacts — as a solo-practice analogue for innovation rate. I ignored it; on reflection Claude agreed it was wrong.

It stretches the KVA past what it means, and a scorecard is not the place for a personal-productivity observation. **A measure that needs an analogy to justify it usually belongs somewhere else.**

*(The underlying observation still stands as a personal note: several sessions went into refining strategy artifacts and none into running the interviews. That is worth knowing. It just isn't a scorecard row.)*

---

### Final result

| Measure | Why we chose it | Source | Baseline | Target | Trend |
|---|---|---|---|---|---|
| **Employee Engagement** — degree to which employees are aligned with and bought into the goals | A team that isn't bought into what it is building cannot innovate on it. Distinct from Employee Satisfaction (CV), which measures feeling rather than alignment | team survey | not measurable — no team yet | — | — |
| **Innovation Rate** — % of effort on new capability ÷ total product effort | The headline A2I measure, and the one that makes technical debt legible to a business audience | delivery data | not measurable pre-launch | — | — |
| **On-Product Index** — time on the product ÷ total available team time | Exposes how much paid capacity actually reaches the product rather than the organisation around it | time / work tracking | not measurable pre-launch | — | — |
| **Technical Debt Ratio** — remediation effort ÷ development effort | Structural quality is the leading indicator of future slowdown | static analysis (e.g. SonarQube) | no codebase yet | <5% | — |

**Source:** The Evidence-Based Management Guide, Scrum.org, May 2024 — Appendix: Example Key Value Measures.
