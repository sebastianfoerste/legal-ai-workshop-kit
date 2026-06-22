# Legal AI Workshop Kit

The deliverables for running a legal-AI rollout with a law firm or in-house team —
agendas, discovery tools, objection handling, and feedback templates. Everything here is
ready to use in a real engagement; the framing is generic and contains no client data.

> **What workflow does this improve?** Onboarding and enablement — getting partners, associates, and in-house counsel actually using legal AI after the contract is signed.
> **Who is the user?** A Legal Engineer, CSM, or Innovation lead running the rollout.
> **Where does human review happen?** Every agenda and template keeps the rule explicit: AI produces a first pass, a named lawyer signs off before reliance.
> **What is blocked until approval?** Nothing ships to a client or a court on AI output alone. The kit teaches the review gate, it does not remove it.
> **What would I tell Product?** The product-feedback template turns what you observe in sessions into structured requirements for Engineering.

## Problem

Adoption does not fail at procurement. It fails in the first ninety days, when a workshop
never gets booked, a skeptical partner is never answered, and the friction associates hit
never reaches Product. This kit is the operating system for that ninety days: what to run,
in what order, with whom, and what to do with what you learn.

## Who runs this

A Legal Engineer or CSM owning the rollout. The kit assumes you are not the lawyer of
record and not the engineer — you are the person who makes the tool stick.

## What's inside

| Document | Use it when |
| --- | --- |
| [60-minute workshop agenda](sessions/60-min-workshop-agenda.md) | You have a practice group for an hour and want them using the tool by the end. |
| [30-minute partner briefing](sessions/30-min-partner-briefing.md) | You have a partner's calendar for half an hour and need a go/no-go decision. |
| [90-minute associate hands-on](sessions/90-min-associate-hands-on.md) | You want associates to build real fluency on synthetic documents. |
| [Adoption questionnaire](discovery/adoption-questionnaire.md) | You are scoping an account and need to score its readiness. |
| [Workflow discovery template](discovery/workflow-discovery-template.md) | You are mapping a real workflow to a candidate AI use case. |
| [Use-case prioritization matrix](discovery/use-case-prioritization-matrix.md) | You have a list of candidate use cases and need to pick what to pilot first. |
| [Skeptical-partner objections](enablement/skeptical-partner-objections.md) | A partner is pushing back and you need an evidence-based answer, fast. |
| [Follow-up email templates](enablement/follow-up-email-templates.md) | A session just ended, or usage dipped, and you need to send the right note. |
| [Product-feedback template](enablement/product-feedback-template.md) | You watched a user hit friction and want to turn it into a product requirement. |
| [Customer workflow](docs/customer-workflow.md) | You need the standard context on the typical customer workflow. |
| [Product-feedback notes](docs/product-feedback-notes.md) | You need the standard repository file for worked product feedback examples. |
| [Reviewer guide](docs/reviewer-guide.md) | You need the standard guidance for reviewing these artifacts. |

Also includes an [example intake](examples/synthetic-input.json) with its [prioritization result](examples/sample-output.md).

## How to use it in a rollout

1. Scope the account with the adoption questionnaire and a few workflow-discovery sessions.
2. Rank candidate use cases with the prioritization matrix; pick one to pilot.
3. Run the partner briefing for the go decision, then the workshop for the group, then the associate hands-on for fluency.
4. Capture friction with the product-feedback template; send the right follow-up.
5. Re-baseline and expand.

## Data statement

All examples are generic or synthetic. No real client, firm, matter, or personal data
appears anywhere in this repo. Merge fields in the email templates use `{{double_brace}}`
placeholders you replace per engagement.

## Check

`make check` verifies every required document exists and that none is left half-written.
It is the only automated gate in this repo.
