---
name: Momentum
description: A mission-control ledger for executing and proving a focused 90-day transformation.
colors:
  canvas: "var(--canvas)"
  paper: "var(--paper)"
  surface: "var(--surface)"
  surface-strong: "var(--surface-strong)"
  ink: "var(--ink)"
  muted: "var(--muted)"
  faint: "var(--faint)"
  line: "var(--line)"
  line-strong: "var(--line-strong)"
  live-coral: "var(--accent)"
  live-coral-soft: "var(--accent-soft)"
  accent-ink: "var(--accent-ink)"
  signal-ink: "var(--signal-ink)"
  progress-green: "var(--green)"
  progress-green-soft: "var(--green-soft)"
  data-blue: "var(--blue)"
  data-blue-soft: "var(--blue-soft)"
  caution-amber: "var(--amber)"
typography:
  display:
    fontFamily: "Momentum Sans, sans-serif"
    fontSize: "clamp(30px, 4vw, 48px)"
    fontWeight: 720
    lineHeight: 1.03
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Momentum Sans, sans-serif"
    fontSize: "18px"
    fontWeight: 690
    lineHeight: 1.2
    letterSpacing: "-0.025em"
  title:
    fontFamily: "Momentum Sans, sans-serif"
    fontSize: "15px"
    fontWeight: 650
    lineHeight: 1.25
  body:
    fontFamily: "Momentum Sans, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Momentum Sans, sans-serif"
    fontSize: "11px"
    fontWeight: 650
    lineHeight: 1.35
    letterSpacing: "0.04em"
  numeric:
    fontFamily: "Momentum Sans, sans-serif"
    fontSize: "38px"
    fontWeight: 720
    lineHeight: 1
    letterSpacing: "-0.04em"
    fontFeature: "tnum"
rounded:
  heat-cell: "3px"
  check: "6px"
  control: "8px"
  field: "10px"
  inset: "12px"
  summary: "14px"
  panel: "16px"
  pill: "999px"
spacing:
  hairline-gap: "6px"
  control-gap: "8px"
  compact: "10px"
  inset-sm: "12px"
  grid: "16px"
  section: "20px"
  panel: "22px"
  shell-top: "34px"
components:
  button-primary:
    backgroundColor: "{colors.live-coral}"
    textColor: "{colors.accent-ink}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 12px"
    height: "36px"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.live-coral}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 9px"
    height: "34px"
  panel:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
    padding: "20px 22px"
  field:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "0 12px"
    height: "44px"
  chip:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.muted}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "4px 7px"
---

# Design System: Momentum

## Overview

**Creative North Star: "The Mission Ledger"**

Momentum is a live execution ledger, not a gallery of interchangeable cards. It should feel like a disciplined mission-control surface: dark by default, equally resolved on paper white, compact enough for repeated daily use, and calm enough that incomplete work remains legible without becoming punitive. Graphite rules establish order; coral identifies the live commitment; blue and green report data and completion.

The interface tells one continuous story: mission status, today’s weighted work, KPI proof, daily trend, weekly comparison, consistency, body evidence, and milestones. Panels are chapters in that ledger rather than self-promoting objects. Controls remain small and operational, while large tabular numerals and the opening statement carry visual authority.

**Key Characteristics:**

- Operational, direct, and evidence-led.
- Dark midnight and paper-white canvases with the same semantic hierarchy.
- Graphite borders and tonal fields instead of decorative depth.
- Coral for live work, green for completion, blue for analytical comparison, and amber for caution or secondary goal data.
- Compact controls, dense ledger rows, and tabular numerals.
- Responsive reflow that preserves the mission-first reading order.

## Colors

The palette is semantic and restrained: near-neutral operational surfaces carry most of the screen, while coral, green, blue, and amber each communicate one distinct kind of information. The frontmatter points directly at the live CSS custom properties; the light values are defined on `:root` and the default dark substitutions on `[data-theme="dark"]`.

### Primary

- **Live Coral:** Marks today’s active mission, primary actions, featured score data, progress, and error or down-state signals. It is warmer and brighter in dark mode so it retains urgency against midnight surfaces.

### Secondary

- **Progress Green:** Confirms completed commitments, positive deltas, saved state, and secured outcomes.
- **Data Blue:** Carries comparative and career data, XP progress, and analytical focus treatment.

### Tertiary

- **Caution Amber:** Marks secondary goal-series data and transient saving or caution states without competing with coral.

### Neutral

- **Canvas / Paper / Surface / Surface Strong:** Form a four-step tonal stack from application ground to inset ledger field.
- **Ink / Muted / Faint:** Separate primary reading, supporting evidence, and low-emphasis metadata.
- **Line / Line Strong:** Draw the graphite rules that organize the ledger and strengthen interactive boundaries.
- **Accent Ink / Signal Ink:** Preserve readable foregrounds on coral and green fills in both themes.

### Named Rules

**The One Signal, One Meaning Rule.** Coral means live or urgent, green means complete or positive, blue means comparative data, and amber means caution or secondary data; never swap those meanings for decoration.

**The Theme Parity Rule.** Dark is the default, but every semantic role must remain equally legible and intentional on paper white; never treat light mode as a simple inversion.

## Typography

**Display Font:** Momentum Sans (with `sans-serif` fallback)  
**Body Font:** Momentum Sans (with `sans-serif` fallback)  
**Label/Mono Font:** Momentum Sans with tabular-number features for quantitative values

**Character:** One variable sans family keeps the system direct and operational. Authority comes from weight, scale, tight display tracking, and fixed-width numerals rather than from decorative type pairing.

### Hierarchy

- **Display** (720, fluid 30–48px, 1.03): The opening mission statement only; balanced over a maximum width of 720px.
- **Headline** (690, 18px, 1.2): Panel chapter titles; reduces to 16px below 760px.
- **Title** (650, 15px, 1.25): Brand and focused inset-card headings.
- **Body** (400, 12px, 1.5): Explanations and operational guidance; important long copy stays near 65–80 characters.
- **Label** (650, 11px, 0.04em when categorizing): Controls, metadata, tags, axes, and compact instructions. Uppercase is reserved for true status labels such as the challenge name.
- **Numeric** (720, usually 38px, 1): KPI and comparison values. All scores, counts, dates, percentages, and measurements use tabular numerals.

### Named Rules

**The Ledger Numeral Rule.** Quantitative values always use tabular figures so updates do not disturb alignment or scan rhythm.

**The One Display Moment Rule.** Reserve the large, tightly tracked display style for the page mission; downstream hierarchy is compact and workmanlike.

## Layout

The application sits in a centered fluid container capped at 1380px, with 34px top spacing and horizontal gutters that scale from 22px to 56px. A 16px grid gap and 1px graphite dividers create the main rhythm. The header pairs the mission statement with a 340px challenge summary; the dashboard then reads as a single evidence ledger: today’s commitments first, KPI strip and trend proof next, followed by weekly, consistency, body, photo, and milestone chapters.

At desktop widths, the dashboard uses two equal columns, while full-width analytical and execution chapters span both. Today’s ledger uses two columns for the live distribution mission and score-by-goal summary, then two-column task groups below. At 1080px the dashboard and daily summary collapse to one column; comparison cards become a two-by-two grid. At 760px gutters reduce to 14px, task groups and insight rows stack, the heatmap halves from 30 to 15 columns, and body metrics become two columns. At 480px the header stacks, comparisons become single-column, controls expand to available width, and check rows place their metadata on a second line. Wide charts keep a 720px analytical canvas inside horizontal overflow instead of crushing labels.

**The Story Survives Reflow Rule.** Responsive layout may change columns, density, and scrolling behavior, but it never changes the order from mission status to execution to proof.

## Elevation & Depth

The system is flat by default and uses no ambient card shadows. Depth comes from tonal layering, graphite rules, inset surfaces, and occasional 1px inner strokes. The only outward multi-ring shadow belongs to hovered heatmap cells as a precise inspection affordance; field focus uses a restrained blue halo. Trend animation and saving-state pulse communicate change without simulating physical elevation.

### Shadow Vocabulary

- **Selected Control** (`inset 0 0 0 1px var(--line)`): Identifies the active chart range without lifting it off the segmented control.
- **Heatmap Inspection** (`0 0 0 2px var(--surface), 0 0 0 3px var(--accent)`): Isolates one hovered consistency cell.
- **Field Focus Halo** (`0 0 0 3px color-mix(in srgb, var(--blue) 18%, transparent)`): Reinforces keyboard and text-entry focus around authentication fields.

### Named Rules

**The Flat-by-Default Rule.** Surfaces are separated by tone and 1px rules; never add ambient shadows to make routine panels feel important.

## Shapes

Shapes are compact, softly engineered, and subordinate to the ledger. Panels use gently rounded 13–16px corners, inset mission blocks use 12px, fields and steppers use 9–10px, action controls use 7–8px, and checks use 6px. Pills and progress tracks are fully rounded; heatmap cells retain a tighter 3px radius; score rings and milestone markers are circular. Borders are crisp 1px graphite rules, with dashed strokes reserved for editable or not-yet-provided evidence.

**The Nested Radius Rule.** Corners become smaller as components move inward: panel, inset field, control, then check or cell. Do not repeat the same large radius at every nesting level.

## Components

### Buttons

- **Shape:** Compact rounded controls (7–9px) with 34–44px heights according to task importance.
- **Primary:** Live Coral with Accent Ink; labels are 11px and weight 700. Primary actions appear only at a real decision or recording point.
- **Hover / Focus:** Hover shifts neutral controls toward the coral-soft field; keyboard focus receives a 2px coral outline with 3px offset. Disabled controls lower opacity and lose the active cursor.
- **Ghost / Tertiary:** Transparent with coral text; a thin coral-mixed rule is added when the action needs a bounded target.

### Chips

- **Style:** Small pill-shaped metadata with transparent or Surface fill, graphite border, muted 11px text, and 4px by 7px internal spacing.
- **State:** Selected segmented controls move to Paper with Ink text and an inset graphite stroke. Chips label status and scoring; they do not behave as decorative badges.

### Cards / Containers

- **Corner Style:** Gently curved outer panels (16px; 13px on the narrowest viewport) and smaller inset surfaces (12–14px).
- **Background:** Paper for chapters; Surface and Surface Strong for contained analysis and supporting rows.
- **Shadow Strategy:** Flat; see Elevation & Depth.
- **Border:** One-pixel Line boundaries and internal rules. KPI cards share one outer container and divider network instead of floating independently.
- **Internal Padding:** Usually 20–22px; compact mobile sections reduce to 12–18px.

### Inputs / Fields

- **Style:** 44px fields with a strong graphite stroke and 9–10px radius. Numeric fields integrate directly into steppers and use right-aligned tabular values.
- **Focus:** Coral outline for general keyboard focus; blue border and subtle blue halo for text entry; inline weight editing uses a coral dashed underline.
- **Error / Disabled:** Errors reuse the semantic coral role with explicit text; disabled stepper buttons use reduced opacity and no pointer cue.

### Navigation

- **Style:** Navigation is intentionally minimal: brand, theme toggle, anchored chapter IDs, and footer data actions. The theme toggle is a 30px outlined pill with an inline 14px icon, explicit text, hover contrast, and `aria-pressed` state. Mobile preserves labels rather than collapsing to ambiguous icon-only controls.

### Daily Execution Ledger

This is the signature component. A full-width panel combines a score ring, coral-soft mission inset, weighted goal progress, two-column checklist, and measured-target steppers. Hover indicates actionable rows, completed checks turn green with a visible check icon, upcoming work is coral-soft with a dashed mark, and planned recovery is green-soft with explicit explanatory copy. Status must never rely on fill color alone.

### Analytical Evidence

Trend charts, weekly comparisons, the 90-day heatmap, body metrics, and milestones each use one visual grammar. Charts include legends and accessible names, comparisons pair arrows with color, heatmap cells carry titles and an aggregate label, and milestone state combines line progress with numbered or checked circular markers. Entry animation uses 500–650ms emphasized easing and is removed under reduced-motion preferences.

## Do's and Don'ts

### Do:

- **Do** lead every screen with current mission status and the next recordable work.
- **Do** preserve the semantic color contract across light and dark themes.
- **Do** use graphite rules, shared containers, and tonal insets to expose hierarchy.
- **Do** use tabular numerals for every changing quantity and pair data color with labels, arrows, icons, or text.
- **Do** retain visible keyboard focus, semantic progress values, accessible chart names, touch-friendly controls, and reduced-motion behavior.
- **Do** keep interaction copy direct, specific, and confidence-preserving.

### Don't:

- **Don't** turn the ledger into a gallery of floating, equally weighted cards.
- **Don't** add decorative gradients, glowing borders, ambient shadows, glass effects, or effects without information value.
- **Don't** use coral, green, blue, or amber as arbitrary decoration or as the only carrier of meaning.
- **Don't** shrink labels below the established 11px floor or compress charts until their axes become unreadable.
- **Don't** reorder analytics ahead of today’s weighted execution on smaller screens.
- **Don't** introduce oversized controls, playful badges, or nested rounded containers that dilute the mission-control character.
