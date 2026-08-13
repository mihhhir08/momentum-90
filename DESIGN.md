---
name: Momentum
description: A grounded tactical command interface that turns a fixed 90-day challenge into direct daily execution, evidence, and course correction.
colors:
  canvas: "#020609"
  paper: "#071017"
  surface: "#0b1720"
  surface-strong: "#10232e"
  ink: "#dcecf4"
  muted: "#8299a7"
  faint: "#536b79"
  line: "#17313e"
  line-strong: "#285063"
  action-amber: "#f0b35a"
  action-amber-soft: "#241b0c"
  action-ink: "#020609"
  success-green: "#63d6a0"
  success-green-soft: "#0a281d"
  telemetry-blue: "#55c7ff"
  telemetry-blue-soft: "#082130"
  body-blue: "#4e8dff"
  danger-red: "#ff6e62"
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
  tactical: "2px"
  heat-cell: "1px"
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
    backgroundColor: "{colors.action-amber}"
    textColor: "{colors.action-ink}"
    typography: "{typography.body}"
    rounded: "{rounded.tactical}"
    padding: "0 16px"
    height: "42px"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.muted}"
    typography: "{typography.label}"
    rounded: "{rounded.tactical}"
    padding: "0 10px"
    height: "32px"
  panel:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.tactical}"
    padding: "20px 22px"
---

# Design System: Momentum

## Overview

**Creative North Star: "The Cave Tactical Mainframe"**

Momentum is a private operating surface for one person’s fixed 90-day transformation challenge, which began August 7. It is not a configurable productivity platform or a gallery of dashboard cards. The interface protects the existing goals, scoring weights, history, and evidence while letting the user record today’s weighted commitments directly.

The visual world is a grounded, cinematic command system: near-black tactical surfaces, cold-blue telemetry, restrained amber controls, compact mono instrumentation, and clipped corners borrowed from serious industrial hardware. It evokes the focus of a Batcomputer without licensed character art, comic-book ornament, noisy sci-fi chrome, or decorative glow. Momentum Sans carries mission language while Momentum Mono identifies system state and measured data.

**Key Characteristics:**

- Personal-only, private, and specific to the August 7 challenge.
- Direct execution: today’s weighted commitments appear before supporting analytics.
- A single deep-neutral dark theme with no theme switch or off-white surface.
- Graphite-blue rules and tonal layers instead of floating-card depth.
- Amber for action, cyan for telemetry, green for completion, and red only for negative deviation or error.
- Expressive Momentum Sans, operational Momentum Mono, and rare Georgia reflection.
- A compact amber rise mark identifies Momentum at product-chrome and app-icon scale.
- No planning ceremony, timers, or productivity theater between the user and daily logging.

## Colors

The palette is deliberately narrow: four near-black neutrals carry the product, amber carries action, and telemetry colors retain stable meanings.

### Primary

- **Action Amber** (`#f0b35a`): The interactive accent. Use it for primary controls, active challenge progress, and explicit course corrections—not for ambient decoration.

### Secondary

- **Success Green** (`#63d6a0`): Checked commitments, positive deltas, saved state, and completed controls.
- **Telemetry Blue** (`#55c7ff`): Charts, XP, comparative analysis, and live system labels.

### Tertiary

- **Danger Red** (`#ff6e62`): Negative deltas, course deviation, and blocking errors only.

### Neutral

- **Canvas** (`#020609`): The application ground.
- **Command Paper** (`#071017`): Primary panels and contained chapters.
- **Inset Surface** (`#0b1720`): Controls, chart fields, and row hover.
- **Strong Inset Surface** (`#10232e`): Progress tracks, stronger control hover, and deeper subdivisions.
- **Primary Ink** (`#dcecf4`): Mission language, headings, and primary values.
- **Muted Ink** (`#8299a7`) and **Faint Ink** (`#536b79`): Supporting explanation and low-emphasis operational metadata.
- **Telemetry Rule** (`#17313e`) and **Strong Telemetry Rule** (`#285063`): One-pixel structure and interactive boundaries.

### Named Rules

**The Single-Night Rule.** Momentum has one deep-dark theme. Do not add off-white surfaces, a light mode, or a theme switch.

**The Action Rarity Rule.** Amber appears where the user can act or where the system recommends a correction; its scarcity makes the next move obvious.

**The One Signal, One Meaning Rule.** Amber means action or correction, cyan means telemetry, green means complete or positive, and red means deviation or error; never trade those meanings for decoration.

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

Primary panels, inputs, checks, and compact controls use a disciplined 1–2px radius. Major command surfaces clip one top-right corner, with an occasional bottom-left cut on standalone modules. Progress tracks, heatmap cells, chart keys, and telemetry tags are rectilinear. Circular geometry is reserved for status dots and milestone markers. Dashed strokes remain reserved for editable or not-yet-provided evidence.

The Momentum mark is one uninterrupted rising amber path with a narrow pale acceleration cut. Preserve its silhouette, transparent ground, generous clear space, and forward-right orientation; never add a licensed emblem, shadow, glow, text, or decorative gradient.

**The Tactical Geometry Rule.** Use clipped corners only on primary command surfaces and keep inner controls rectilinear. Repeating cut corners at every nested level creates visual noise.

## Components

### Buttons

- **Shape:** Primary actions are 42–44px tall; compact controls are 32px tall; both use a 2px radius.
- **Primary:** Action Amber with dark Action Ink and compact uppercase Momentum Mono. Use it for consequential actions and explicit course corrections.
- **Hover / Focus:** Neutral controls move one tonal step stronger on hover. All keyboard-focusable controls receive a 2px amber outline with 3px offset. Disabled controls retain their labels, reduce opacity, and remove the active cursor.
- **Secondary:** Restore, reopen, and footer actions are text-led and quiet.

### Chips

- **Style:** Compact rectilinear metadata with telemetry borders, muted 9–10px mono text, and 0 by 8–10px internal spacing.
- **State:** Selected analytical ranges and status chips retain explicit text; color never replaces the label.

### Cards / Containers

- **Corner Style:** Primary panels and controls use 1–2px radii. Standalone command surfaces may clip a 10–14px corner.
- **Background:** Paper for ledger chapters, Surface for operational footers and hover, Strong Surface for tracks and deeper subdivisions.
- **Shadow Strategy:** Flat; see Elevation & Depth.
- **Border:** One-pixel graphite boundaries and dividers. Repeated metrics share one container rather than floating independently.
- **Internal Padding:** Usually 20–22px and 12–16px for dense mobile content.

### Inputs / Fields

- **Style:** Measured targets use 44px steppers with 44px controls, right-aligned tabular inputs, and explicit units.
- **Focus:** Amber outline for general keyboard focus; text entry may use a blue border and restrained blue halo.
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
