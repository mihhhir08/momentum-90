---
name: Momentum
description: A personal mission ledger that turns a fixed 90-day challenge into direct daily execution and honest evidence.
colors:
  canvas: "#080d13"
  paper: "#101720"
  surface: "#151e28"
  surface-strong: "#1b2732"
  ink: "#f2f6fa"
  muted: "#a5afba"
  faint: "#7f8b97"
  line: "#26323e"
  line-strong: "#3b4a59"
  action-coral: "#ff7657"
  spark-coral: "#ff5d35"
  action-coral-soft: "#2a1c19"
  action-ink: "#0b1016"
  success-green: "#48c991"
  success-green-soft: "#13271f"
  data-blue: "#69a8ff"
  data-blue-soft: "#14243a"
  caution-amber: "#e2ad57"
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
  operational:
    fontFamily: "Momentum Mono, monospace"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.35
    letterSpacing: "0.04em"
    fontFeature: "tnum"
  editorial:
    fontFamily: "Georgia, serif"
    fontSize: "11px"
    fontWeight: 400
    lineHeight: 1.5
rounded:
  heat-cell: "3px"
  check: "6px"
  compact-control: "7px"
  control: "8px"
  action: "9px"
  field: "10px"
  inset: "12px"
  summary: "14px"
  kpi-ledger: "15px"
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
    backgroundColor: "{colors.action-coral}"
    textColor: "{colors.action-ink}"
    typography: "{typography.body}"
    rounded: "{rounded.action}"
    padding: "0 16px"
    height: "42px"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    typography: "{typography.label}"
    rounded: "{rounded.compact-control}"
    padding: "0 10px"
    height: "32px"
  panel:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
    padding: "20px 22px"
---

# Design System: Momentum

## Overview

**Creative North Star: "The Personal Mission Ledger"**

Momentum is a private operating surface for one person’s fixed 90-day transformation challenge, which began August 7. It is not a configurable productivity platform or a gallery of dashboard cards. The interface protects the existing goals, scoring weights, history, and evidence while letting the user record today’s weighted commitments directly.

The visual world is a single deep-neutral dark ledger. Graphite rules and four near-black surface levels create order; coral identifies action; blue reports analytical comparison; green confirms completion. Momentum Sans gives mission language authority, Momentum Mono makes quantitative state precise, and Georgia is reserved for rare reflective editorial notes.

**Key Characteristics:**

- Personal-only, private, and specific to the August 7 challenge.
- Direct execution: today’s weighted commitments appear before supporting analytics.
- A single deep-neutral dark theme with no theme switch or off-white surface.
- Graphite rules and tonal layers instead of floating-card depth.
- Coral for action, blue for data, green for completion, and amber for caution.
- Expressive Momentum Sans, operational Momentum Mono, and rare Georgia reflection.
- A continuous coral rise mark identifies Momentum at product-chrome and app-icon scale.
- No planning ceremony, timers, or productivity theater between the user and daily logging.

## Colors

The palette is deliberately narrow: four deep neutrals carry the product, one coral carries action, and data colors retain stable meanings.

### Primary

- **Action Coral** (`#ff7657`): The interactive accent. Use it for primary controls, live links, required attention, progress, and blocking errors—not for ambient decoration.

### Secondary

- **Spark Coral** (`#ff5d35`): The default MiniLine data-series stroke. It reports the featured sparkline and is not an interactive state.
- **Success Green** (`#48c991`): Checked commitments, positive deltas, saved state, and completed controls.
- **Data Blue** (`#69a8ff`): XP, comparative analysis, and quantitative labels.

### Tertiary

- **Caution Amber** (`#e2ad57`): Secondary goal-series data and saving or caution states.

### Neutral

- **Canvas** (`#080d13`): The application ground.
- **Ledger Paper** (`#101720`): Primary panels and contained chapters.
- **Inset Surface** (`#151e28`): Controls, chart fields, and row hover.
- **Strong Inset Surface** (`#1b2732`): Progress tracks, stronger control hover, and deeper subdivisions.
- **Primary Ink** (`#f2f6fa`): Mission language, headings, and primary values.
- **Muted Ink** (`#a5afba`) and **Faint Ink** (`#7f8b97`): Supporting explanation and low-emphasis operational metadata.
- **Graphite Rule** (`#26323e`) and **Strong Graphite Rule** (`#3b4a59`): One-pixel structure and interactive boundaries.

### Named Rules

**The Single-Night Rule.** Momentum has one deep-dark theme. Do not add off-white surfaces, a light mode, or a theme switch.

**The Action Rarity Rule.** Coral appears where the user can act or must attend; its scarcity is what makes the next move obvious.

**The One Signal, One Meaning Rule.** Action Coral means interaction or intervention, Spark Coral means the default MiniLine series, blue means analysis, green means complete or positive, and amber means caution; never trade those meanings for decoration.

## Typography

**Display Font:** Momentum Sans (self-hosted variable face; `sans-serif` fallback)

**Body Font:** Momentum Sans (self-hosted variable face; `sans-serif` fallback)

**Label/Mono Font:** Momentum Mono (self-hosted variable face; `monospace` fallback)

**Editorial Font:** Georgia (`serif` fallback), used sparingly

**Character:** The type system separates intention from operation. Momentum Sans is expressive and tightly tracked at mission scale, Momentum Mono makes quantitative state and private metadata exact, and Georgia introduces a quiet human register only for reflective or interpretive notes.

### Hierarchy

- **Page Display** (720, fluid 30–48px, 1.03): The two-part opening mission statement; its second line softens to 0.78em and weight 420.
- **Panel Headline** (690, 18px, 1.2): Ledger chapter titles; standard panel titles reduce to 16px below 760px.
- **Body** (400, 12px, 1.5): Explanations and rationale, generally constrained to 58–76 characters.
- **Label** (650, 11px, 1.35): Controls, tags, axes, and compact instructions.
- **Operational Mono** (400–700, 10–17px): Private-workspace metadata and quantitative values; numerals use tabular figures.
- **Editorial Accent** (400, 11px, 1.5): Rare reflective notes or interpretive markers; never navigation, controls, or bulk body copy.

### Named Rules

**The Three Voices Rule.** Sans sets intent, mono records operation, and Georgia marks reflection; never use the three faces interchangeably.

**The Ledger Numeral Rule.** Durations, scores, counts, dates, percentages, and measurements use tabular figures so updates do not disturb alignment.

## Layout

The application uses a centered fluid container capped at 1380px with 34px top spacing and horizontal gutters that scale from 22px to 56px. A 16px dashboard gap and one-pixel rules create the ledger rhythm. The first viewport moves from private brand and challenge status directly into today’s weighted commitments. KPI and analytical proof follow; they never displace daily execution.

At 1080px the wider dashboard chapters collapse to one column and weekly comparisons become two-by-two. At 760px content gutters reduce to 14px, task groups stack, the heatmap changes from 30 to 15 columns, and body metrics become two columns. At 480px the header stacks, the private label hides, task controls expand to the available width, and wide charts retain a 720px analytical canvas inside horizontal overflow.

**The Story Survives Reflow Rule.** Responsive layout may change columns and density, but it preserves challenge status → weighted execution → evidence → reflection.

## Elevation & Depth

Momentum is flat by default and uses no ambient panel shadow. Depth comes from the four neutral surface levels, one-pixel graphite rules, inset fields, and occasional one-pixel inner strokes. The heatmap inspection ring and field-focus halo are functional exceptions, not decorative elevation. Data entry animation is brief and removed under reduced-motion preferences.

### Shadow Vocabulary

- **Selected Control** (`inset 0 0 0 1px var(--line)`): Identifies a selected chart range without lifting it.
- **Heatmap Inspection** (`0 0 0 2px var(--surface), 0 0 0 3px var(--accent)`): Isolates one hovered consistency cell.
- **Field Focus Halo** (`0 0 0 3px color-mix(in srgb, var(--blue) 18%, transparent)`): Reinforces text-entry focus.

### Named Rules

**The Flat-by-Default Rule.** Tonal separation and rules establish hierarchy; never add ambient shadows, glow, glass, or blur to manufacture importance.

## Shapes

The radius ramp is compact and nested: heatmap cells use 3px; checks 6px; compact controls 7px; action buttons and sign-in fields 9px; steppers 10px; inset evidence 12px; challenge status 14px; the shared KPI ledger 15px; and primary panels 16px, reducing to 13px on the narrowest viewport. Pills and progress tracks are fully rounded. Score rings and milestone markers are circular. Dashed strokes are reserved for editable or not-yet-provided evidence.

The Momentum mark is one uninterrupted rising coral path with a narrow pale acceleration cut. Preserve its silhouette, transparent ground, generous clear space, and forward-right orientation; never place it inside a decorative tile or add shadow, glow, text, or a gradient.

**The Nested Radius Rule.** Radius decreases as components move inward: panel, inset, control, then check or cell. Do not repeat large rounded rectangles at every level.

## Components

### Buttons

- **Shape:** Primary actions are 42–44px tall with a 9px radius; compact controls are 32px tall with 7–8px radii.
- **Primary:** Action Coral with dark Action Ink, 12px Momentum Sans, weight 750, and 16px horizontal padding. Use it for consequential actions and direct logging controls.
- **Hover / Focus:** Neutral controls move one tonal step stronger on hover. All keyboard-focusable controls receive a 2px coral outline with 3px offset. Disabled commit and decrement states retain their labels, reduce opacity, and remove the active cursor.
- **Secondary:** Restore, reopen, and footer actions are text-led and quiet.

### Chips

- **Style:** Compact 7px rounded metadata with graphite borders, muted 11px text, and 0 by 8–10px internal spacing.
- **State:** Selected analytical ranges and status chips retain explicit text; color never replaces the label.

### Cards / Containers

- **Corner Style:** Primary panels use 16px; the shared KPI ledger uses 15px; challenge status uses 14px; inner evidence uses 12px or less.
- **Background:** Paper for ledger chapters, Surface for operational footers and hover, Strong Surface for tracks and deeper subdivisions.
- **Shadow Strategy:** Flat; see Elevation & Depth.
- **Border:** One-pixel graphite boundaries and dividers. Repeated metrics share one container rather than floating independently.
- **Internal Padding:** Usually 20–22px and 12–16px for dense mobile content.

### Inputs / Fields

- **Style:** Measured targets use 44px steppers with 44px controls, right-aligned tabular inputs, and explicit units.
- **Focus:** Coral outline for general keyboard focus; text entry may use a blue border and restrained blue halo.
- **Error / Disabled:** Invalid or unavailable actions name the problem where applicable. Disabled decrement controls use reduced opacity.

### Navigation

- **Style:** Navigation is intentionally minimal: private brand, anchored chapters, and footer data actions. There is no theme control.

### Analytical Evidence

Trend charts, weekly comparisons, the 90-day heatmap, body metrics, and milestones keep the existing August 7 data and weighted scoring legible. Charts have legends and accessible names, comparisons pair arrows with color, progress controls expose semantic values, and status combines labels, icons, or position with color. Entry animation uses 500–650ms emphasized easing and collapses under reduced motion.

## Do's and Don'ts

### Do:

- **Do** preserve the August 7 challenge start, existing history, goals, scoring weights, and analytical evidence.
- **Do** place today’s weighted commitments before analytics and keep their controls directly usable.
- **Do** use the three type voices deliberately and tabular mono for operational time.
- **Do** retain semantic progress values, accessible chart names, visible keyboard focus, touch-friendly controls, and reduced-motion behavior.
- **Do** keep incomplete work clear, specific, and confidence-preserving.

### Don't:

- **Don't** add a theme switch, light theme, off-white surface, or warm paper metaphor.
- **Don't** insert planning ceremony, countdowns, pomodoros, or extra approval steps between the user and daily logging.
- **Don't** add decorative gradients, glowing borders, ambient shadows, glass effects, arbitrary color, or effects without information value.
- **Don't** use Georgia for controls or bulk copy, mono for expressive mission language, or Sans where exact operational state needs mono.
- **Don't** rely on color alone, shrink labels below the established 11px floor, or compress charts until axes become unreadable.
- **Don't** invent public-user affordances, claims, testimonials, or scoring behavior beyond this personal challenge.
