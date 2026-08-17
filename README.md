# ICommit — Product Ownership Portfolio

A hands-on product ownership project by **Ashraf Hesham** — engineering background, PSPO I.
This repository holds the strategy artifacts for ICommit, built as practice for the Product Owner accountability.

---

## Vision

> A world where a promise between two people is never forgotten, and nobody has to chase.

## Positioning

> **For** fathers juggling family, work and school commitments
> **who** currently rely on memory, WhatsApp and verbal promises — and end up chasing or being chased,
> **the** ICommit app **is a** shared commitment tracker
> **that** makes sure commitments between two people actually get done, with no chasing and no ambiguity about who agreed to what.
> **Unlike** to-do lists and task managers — or the WhatsApp thread most families use today,
> **our product** requires both people to explicitly agree to a commitment and its sub-commitments before it starts, so accountability is shared rather than assumed.

## Current Product Goal

> A father and one other person can agree, track and complete a shared commitment end-to-end — so that within a week of signing up, a new user has fulfilled at least one commitment that someone else agreed to.

---

## Artifacts

| Artifact | What it shows |
|---|---|
| [Product Vision Board](Product-Vision-Board-with-Checklist.pdf) | Vision, target group, needs, product and business goals — with Pichler's checklist |
| [Positioning statement](Positioning%20statement.md) | Who this is for, and what it beats |
| [Product Goal](Product%20Goal.md) | The current goal, its success measures, and what's explicitly out of scope |
| [GO Product Roadmap](GO-Product-Roadmap-with-Checklist.pdf) | Outcome-based roadmap for releases 1.0 and 2.0 — with Pichler's checklist |
| [Lean Canvas](lean-canvas.pdf) | Business model view: problem, solution, revenue, channels |
| [Biggest untested assumptions](biggest-untested-assumptions.md) | What could be wrong, ranked, with the test for each |
| [Module 2 review](Module-2-Review.md) | Self-assessment of these artifacts against the checklists |

> **Status:** the strategy is drafted but **not yet validated**. The assumptions listed above are the discovery backlog — customer interviews come next.

---

## What ICommit is

A SaaS product that helps people manage and track their day-to-day commitments in a way both sides can trust.

A user can add a commitment for themselves, ask someone else to commit to something, or be assigned a commitment by someone in their contacts.

Each commitment has:

- Due date
- Signed statement of agreement between the accountable person and the requesting person
- Requesting person
- Accountable person
- Pre-commitments / dependencies — each dependency is a commitment itself
- State (Not started / In progress / Done)
- Remind before (how many days)
- Priority (High / Medium / Low)

### Example of usage

- My wife asks me to visit the school and provide the papers required so our daughter is accepted into Year 1.
- My wife adds the commitment and assigns it to me.
- I review the commitment and realise we need to prepare the papers first.
- I add pre-commitments for preparing the papers and split them between me and my wife.
- We both sign off on each commitment, so we both know we agree on it — a commitment can't be marked `In progress` until both of us agree.
- The main commitment can't be marked `In progress` until we both agree and its pre-commitments are `Done`.
- The person assigned to a commitment is reminded before it is due, according to the lead time set by whoever created it.
