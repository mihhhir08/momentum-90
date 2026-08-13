---
name: Momentum
description: A grounded tactical command interface that turns a fixed 90-day challenge into direct daily execution, evidence, and course correction.
colors:
  canvas: "#050607"
  paper: "#0d1012"
  surface: "#13171a"
  surface-strong: "#1a2024"
  ink: "#f1f1e9"
  muted: "#9ca4a7"
  faint: "#697276"
  line: "#273036"
  line-strong: "#3c4a51"
  signal-yellow: "#ffd43b"
  signal-yellow-soft: "#2a250c"
  action-ink: "#090a08"
  success-green: "#70d49b"
  success-green-soft: "#10261a"
  telemetry-blue: "#8bb9d0"
  telemetry-blue-soft: "#13232b"
  hair-bronze: "#c7a96b"
  danger-red: "#ff776d"
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
    backgroundColor: "{colors.signal-yellow}"
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

The visual world is a grounded, cinematic command system: true-black tactical surfaces, sharp signal-yellow controls, desaturated steel-blue telemetry, compact mono instrumentation, and clipped corners borrowed from serious industrial hardware. It evokes the focus of a Batcomputer without licensed character art, comic-book ornament, noisy sci-fi chrome, or decorative glow. Momentum Sans carries mission language while Momentum Mono identifies system state and measured data.

**Key Characteristics:**

- Personal-only, private, and specific to the August 7 challenge.
- Direct execution: today’s weighted commitments appear before supporting analytics.
- A single deep-neutral dark theme with no theme switch or off-white surface.
- Graphite-blue rules and tonal layers instead of floating-card depth.
- Signal yellow for action and system focus, steel blue for telemetry, green for completion, and red only for negative deviation or error.
- Expressive Momentum Sans, operational Momentum Mono, and rare Georgia reflection.
- A compact signal-yellow rise mark identifies Momentum at product-chrome and app-icon scale.
- No planning ceremony, timers, or productivity theater between the user and daily logging.

## Colors

The palette is deliberately narrow: four neutral black and gunmetal surfaces carry the product, signal yellow carries action, and desaturated telemetry colors retain stable meanings.

### Primary

- **Signal Yellow** (`#ffd43b`): The unmistakable interactive accent. Use it for primary controls, active challenge progress, selected system state, and explicit course corrections—not for ambient decoration.

### Secondary

- **Success Green** (`#70d49b`): Checked commitments, positive deltas, saved state, and completed controls.
- **Telemetry Blue** (`#8bb9d0`): Charts, XP, comparative analysis, and live system labels. Its reduced chroma keeps signal yellow dominant.

### Tertiary

- **Danger Red** (`#ff776d`): Negative deltas, course deviation, and blocking errors only.

### Neutral

- **Canvas** (`#050607`): The application ground.
- **Command Paper** (`#0d1012`): Primary panels and contained chapters.
- **Inset Surface** (`#13171a`): Controls, chart fields, and row hover.
- **Strong Inset Surface** (`#1a2024`): Progress tracks, stronger control hover, and deeper subdivisions.
- **Primary Ink** (`#f1f1e9`): Mission language, headings, and primary values.
- **Muted Ink** (`#9ca4a7`) and **Faint Ink** (`#697276`): Supporting explanation and low-emphasis operational metadata.
- **Gunmetal Rule** (`#273036`) and **Strong Gunmetal Rule** (`#3c4a51`): One-pixel structure and interactive boundaries.

### Named Rules

**The Single-Night Rule.** Momentum has one deep-dark theme. Do not add off-white surfaces, a light mode, or a theme switch.

**The Signal Rarity Rule.** Yellow appears where the user can act, where the system is active, or where it recommends a correction; its scarcity makes the next move obvious.

**The One Signal, One Meaning Rule.** Yellow means action, focus, or correction; steel blue means telemetry; green means complete or positive; red means deviation or error. Never trade those meanings for decoration.

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

The Momentum mark is one uninterrupted rising signal-yellow path with a narrow pale acceleration cut. Preserve its silhouette, transparent ground, generous clear space, and forward-right orientation; never add a licensed emblem, shadow, glow, text, or decorative gradient.

**The Tactical Geometry Rule.** Use clipped corners only on primary command surfaces and keep inner controls rectilinear. Repeating cut corners at every nested level creates visual noise.

## Components

### Buttons

- **Shape:** Primary actions are 42–44px tall; compact controls are 32px tall; both use a 2px radius.
- **Primary:** Signal Yellow with dark Action Ink and compact uppercase Momentum Mono. Use it for consequential actions and explicit course corrections.
- **Hover / Focus:** Neutral controls move one tonal step stronger on hover. All keyboard-focusable controls receive a 2px signal-yellow outline with 3px offset. Disabled controls retain their labels, reduce opacity, and remove the active cursor.
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
- **Focus:** Signal-yellow outline for general keyboard focus; text entry may use a steel-blue border and restrained steel-blue halo.
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
