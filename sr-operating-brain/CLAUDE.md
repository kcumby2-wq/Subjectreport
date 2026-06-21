# SubjectReport — Identity & Business Context

This file is auto-loaded every session. It is the agent's standing context on who SubjectReport is, what it sells, and how it operates. Everything else in this repo (goals, workflows, skills) executes against this context.

## What SubjectReport Is

SubjectReport is a film-graded athlete evaluation and recruiting platform. The core claim: every evaluation is analyst-graded (not AI-scored), clip-linked, and formatted the way college coaching staffs already read prospects. The product is a real document coaches know how to use — not a highlight reel, not exposure, not a promise.

Legal entity: programs are operated by Trail of Joy Player Management Group, LLC.

Operator: Kyron Cumby.

## The Brand Line

> "The athlete is not the product. They are the subject."

This is the organizing idea behind every product, every piece of content, and every customer interaction. SubjectReport sells verified evaluation and visibility — never exposure, never hype, never a promise about offers or rankings.

## Who It's For

Primary customer: the parent, as decision-maker, of a high-school (or younger) athlete pursuing college recruitment across any sport — football is the flagship sport shown in marketing, but the platform is sport-agnostic. The athlete is the subject of the work; the parent is who books the call and buys the package.

Secondary audience: event admins, combine operators, camp directors, and HS recruiting staff who use Staff Tools (admin-side, not athlete-facing).

## Products & Pricing

| Product | Price | Type | What's included |
|---|---|---|---|
| Player Transcript | $249 | One-time, 48hr turnaround | Player transcript (downloadable), recruiting tape, written player summary, graded evaluation |
| Recruiting Program | $1,500 | One-time, 6 weeks | Weekly recruiting education, personalized recruiting blueprint, advanced film breakdown, target school list + outreach templates, live group Q&A |
| Full Athlete Package | $5,000 | One-time | Everything in the 6-week program + player transcript, private coaches database, 1:1 college placement specialist, NIL & financial literacy readiness, media & marketing strategist, full coaches directory access |
| Prospect Membership | $99/month | Recurring, cancel anytime | Direct access to the coaches database (D1, FCS, D2, D3, JUCO, NAIA, post-grad) |
| Team/circuit group pricing | Custom | Custom | Built per roster and event structure for 7v7 circuits, HS programs, combine operators |

The Player Transcript is the front door: it's the cheapest entry point and the thing every other product upsells from (see Goal 1 and Goal 5 in `goals/goals.md`).

## How the Product Actually Works (the 5-phase loop)

1. **Submit film** — Hudl, DVSports, or QwikCut.
2. **Advanced film breakdown** — every play graded on assignment, technique, effort, execution by trained analysts inside Optimum Grading (the same platform 350+ coaching staffs use), via Prospect Edge.
3. **Recruiting education** — weekly curriculum on what recruiters want, what to send, when to send it.
4. **Recruiting blueprint** — personalized target list, outreach templates, timeline by class year.
5. **Launch & place** — player transcript delivered, outreach campaign, placement specialist support.

The 48-hour SLA on transcript delivery is a hard operational commitment, not a marketing line — see `workflows/daily.md` Step 2.

## Proof Points (use these exact numbers, don't invent new ones)

- **350+** coaching staffs use the same grading platform behind SubjectReport's evaluations
- **48h** from film submitted to recruit-ready transcript
- **1:1** dedicated college placement specialist for Full Athlete clients
- **100%** of evaluations are film-backed — every grade links to the exact play

## Platforms & Systems Referenced

- **Optimum Grading** — the underlying grading platform (optimumgrading.com)
- **Prospect Edge** — the evaluation tool built on Optimum Grading (prospectedge.optimumgrading.com)
- **Staff Tools** — admin-side intake/CSV tooling for event operators (not athlete-facing)
- **Xpand** — referenced platform link for Kyron Cumby's library/content

## Business Model Logic

- The transcript is the wedge product. It proves the platform is real (verified, film-backed, fast) and creates a warm, emotional moment to upsell from.
- Subject Media (the cross-sell) targets families right after transcript delivery, while they're engaged — see the "For Subject Media Cross-Sell Copy" section of `skills/srvoice/SKILL.md`.
- Prospect Membership ($99/mo) is the recurring revenue floor — it monetizes the coaches database independent of any one-time package purchase.
- The 6-week program and Full Athlete Package are the high-touch, high-ticket tiers; education (NIL, recruiting calendar, outreach, levels of play) is what justifies the jump in price and builds trust that the cheaper tiers alone can't.
- Booking a call is a deliberate filter, not friction — SubjectReport positions itself as declining to oversell families into the wrong package.

## Where This Plugs Into the Rest of the Repo

- `goals/goals.md` — the 6 active business goals this agent's daily work should move
- `workflows/daily.md`, `weekly.md`, `monthly.md` — the operating cadence
- `skills/srvoice/SKILL.md` — exact tone, banned words, and visual identity reference for anything customer-facing
- `skills/evaluation-processing/SKILL.md` — how a raw transcript becomes a family-facing summary
- `feedback/feedback-log.md` — Kyron's standing corrections; always read first, every session
