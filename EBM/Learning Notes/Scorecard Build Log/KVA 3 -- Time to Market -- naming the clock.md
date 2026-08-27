### The question Time to Market answers

How quickly can we deliver new capability, service or product? It is the speed of the **learning loop**, not the speed of typing.

**Why it matters more than it sounds.** T2M is the denominator of everything else. If it takes six months to test an idea, you get two learnings a year — and no amount of clever prioritisation compensates for that. A team with strong Current Value and weak T2M is coasting on a position it can no longer renew.

---

### The core lesson — a time measure is meaningless until you name two events

I proposed "lead time" and "feedback loop time" and could not operationalise them. The reason is that neither is a measure yet.

**"Lead time" tells you nothing. "Lead time *from what to what*" is a measure.**

Every time measure needs three things: a **clock-start event**, a **clock-stop event**, and a **unit**. That is the entire skill here; everything else follows from it.

| Measure | Clock starts | Clock stops |
|---|---|---|
| **Cycle time** | Work is started | Work is finished |
| **Lead time** | Request enters the system | Delivered to the user |
| **Time to learn** | We admit we don't know X | We have evidence about X *and* recorded a decision |
| **Release frequency** | — | Count of releases per period |

**Lead time includes queue time; cycle time does not.** That is why lead time is the customer-facing one — it is what someone actually experiences from asking to receiving. Cycle time only measures the part where you were working, which conveniently hides how long the request sat in a backlog.

---

### The realisation that unlocked this KVA

**Pre-launch, lead time and feedback-loop time are the same clock.**

Nothing ships to users, so "delivery" *is* "learning". They only separate into two distinct measures after launch.

So there aren't two measurable things right now — there is one measurable thing and one declared placeholder. That is honest, and it is the same treatment given to *conversion to paid* under Current Value.

---

### The subtle bit — the clock stops at the decision, not at the data

Time to learn could reasonably stop when the evidence arrives. It shouldn't.

**Evidence sitting unread has not closed a loop.** Teams routinely gather findings and then take weeks to act on them, and a measure that stops at "data collected" hides that delay completely — which is exactly the delay worth seeing.

So: clock stops when the write-up exists **and** a decision is recorded — *proceed / adapt / kill*.

---

## What each measure means

**1. Time to learn — days from an assumption being logged to a decision being recorded**

Pre-launch, learning speed *is* delivery speed. This is the loop everything else depends on.

The figure already existed, unlabelled, in `biggest-untested-assumptions.md`: *"10 story-based interviews + a clickable Figma flow. ~2 weeks."* Defining its start and stop events is what turned it from a plan into a measure.

- **Starts:** the assumption is logged with a testable form
- **Stops:** write-up exists and a decision is recorded

**2. Time to first user contact — days from "we need to know X" to the first conversation with a real user about it**

This isolates the largest delay inside measure 1. If time-to-learn is six weeks and five of them were spent getting to the first conversation, that tells you precisely where the system is slow.

**This row is uncomfortable, and that is the point.** The loop currently has an unbounded first leg — the tests are designed and not run. A scorecard that does not show that is flattering rather than informing. Empty cells are information.

**3. Lead time — idea accepted → live for users**

The post-launch version of the same question. Declared now so the row exists before there is data to put in it.

---

### On custom measures

"Time to first user contact" is not one of the EBM Guide's example measures. That is fine.

The Guide gives **examples** of Key Value Measures, not a fixed list. What matters is that a measure answers the KVA's question and is defined precisely enough to be checkable. **A custom measure that fits the context beats a textbook one that doesn't apply.**

---

### The misuse to avoid

T2M measures are the easiest of the four to turn into a team-productivity stick. That is the classic EBM misuse.

The scorecard exists for **investment decisions**, not performance management. Pick measures that describe the *system's* speed, not how fast individuals work. "Our time to learn is six weeks" is a statement about a system with a bottleneck. "The team is slow" is a statement that will get you worse data next quarter.

---

### Final result

| Measure | Why we chose it | Source | Baseline | Target | Trend |
|---|---|---|---|---|---|
| **Time to learn** — days from an assumption being logged to a decision being recorded | Pre-launch, learning speed *is* delivery speed. This is the loop everything else depends on | assumption test log | ~14 days (planned, not yet run) | <=14 days | — |
| **Time to first user contact** — days from "we need to know X" to the first conversation with a real user about it | Isolates the biggest delay inside the loop above. Currently unbounded — no interviews run yet | discovery log | not yet — no interviews run | <=7 days | — |
| **Lead time** — idea accepted → live for users | The post-launch version of the same question. Declared now so the row exists before there is data | delivery tooling | not measurable pre-launch | — | — |
