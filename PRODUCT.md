# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

The user is running a focused 90-day transformation challenge. They use the dashboard daily to execute high-priority commitments and weekly to review progress across audience growth, career, body recomposition, and hair health. The current product is deliberately personal; making it configurable for a wider audience is outside this version's scope.

## Product Purpose

Momentum turns a demanding multi-goal challenge into a clear daily operating system. Success means the user knows what to do today, records it quickly, sees honest weighted progress, and stays confident enough to continue without losing accountability.

## Positioning

Unlike a generic habit tracker where every checkbox counts equally, Momentum weights actions by their contribution to the user's actual goals and separates execution, trend analysis, weekly comparison, and recovery planning.

## Operating Context

The dashboard is checked throughout the day to update binary commitments and measured targets. Weekly use includes weight entry, week-over-week review, consistency analysis, progress photos, and milestone reflection. The user may switch devices and expects cloud-synced history to remain intact while the application evolves.

## Capabilities and Constraints

- A 90-day challenge with a configurable start date and days-remaining framing.
- Weighted scoring across Audience, Career, Body, and Hair.
- Daily X volume, LinkedIn and optional Instagram publishing, job applications until employment, career-growth work, clean food, protein, strength or planned recovery, steps, water, and scalp massage.
- Multi-series progress chart, weekly comparison, consistency heatmap, weekly review, body metrics, progress photos, milestones, backups, and end-of-challenge summary.
- Supabase passwordless email sign-in, cloud-synced logs, and private photo storage with local-storage fallback.
- Existing scoring rules, saved history, cloud schema, and data migration behavior must remain compatible through redesigns.
- A proposed daily focus plan uses a minimum three-hour capacity, lets the user adjust allocations, requires explicit approval, and records whether the plan fit the day.
- Focus mode removes surrounding analytics but does not include a timer.
- The interface must remain responsive, keyboard accessible, and legible in its single deep-dark theme.

## Brand Commitments

- Product name: Momentum.
- Voice: direct, accountable, specific, and confidence-preserving; never saccharine or needlessly punitive.
- Today's execution is the primary experience; analytics support action rather than displacing it.
- A deep, neutral dark canvas is the sole theme; off-white surfaces and a theme switch are intentionally excluded.
- Typography should distinguish mission, instruction, and operational data without becoming decorative or monotonous.
- The analytical restraint and legibility of DataFast are a binding quality reference.
- Avoid generic AI-generated interface tells: decorative gradients, glowing borders, nested-card clutter, arbitrary color, tiny text, and effects without information value.

## Evidence on Hand

- The working dashboard and its real interaction model are implemented in `app/page.tsx` and `app/globals.css`.
- Real user goals, targets, scoring weights, measurements, and workflow decisions are encoded in the application and confirmed in the project conversation.
- No testimonials, public usage metrics, or external performance claims are available and none should be invented.

## Product Principles

1. Execution before analysis.
2. Weight actions by goal impact, not checkbox count.
3. Make incomplete work clear without damaging confidence.
4. Preserve history and trust through every product change.
5. Use each visual device for one distinct analytical purpose.

## Accessibility & Inclusion

The dashboard must preserve readable type, sufficient contrast, visible keyboard focus, semantic controls, touch-friendly targets, reduced-motion support, and meaning that does not rely on color alone.
