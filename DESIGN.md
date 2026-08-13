---
name: BATCOMPUTER
description: An Arkham-inspired evidence network for a private 90-day mission.
colors:
  canvas: "#020405"
  paper: "#060b0e"
  surface: "#0a1115"
  surface-strong: "#102129"
  ink: "#edf8ff"
  muted: "#89a6b8"
  faint: "#526d7e"
  line: "#173036"
  line-strong: "#367985"
  steel-blue: "#78ddeb"
  steel-blue-soft: "#0a2930"
  action-ink: "#041016"
  success-green: "#68b99b"
  success-green-soft: "#0c251f"
  telemetry-blue: "#abdfff"
  telemetry-blue-soft: "#102735"
  hair-neutral: "#8e9da7"
  danger-red: "#d36d71"
typography:
  display:
    fontFamily: "Momentum Sans, sans-serif"
    fontSize: "clamp(38px, 5.3vw, 72px)"
    fontWeight: 760
    lineHeight: 0.82
    letterSpacing: "-0.055em"
  headline:
    fontFamily: "Momentum Sans, sans-serif"
    fontSize: "17px"
    fontWeight: 720
    lineHeight: 1.2
    letterSpacing: "0.095em"
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
    backgroundColor: "{colors.steel-blue}"
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

# Design System: BATCOMPUTER

## Overview

**Creative North Star: "The Forensic Mission Network"**

BATCOMPUTER is a private operating surface for one person’s fixed 90-day transformation challenge, which began August 7. It is not a configurable productivity platform or a gallery of dashboard cards. The interface protects the existing goals, scoring weights, history, and evidence while letting the user record today’s weighted commitments directly.

The visual world is an original tactical evidence network inspired by the density, precision, and cinematic focus of Arkham-era Batcomputer interfaces: true-black scan fields, cold blue phosphor signals, compact mono instrumentation, asymmetric command rails, selection brackets, and an original winged command emblem. It should feel like a coherent forensic operating system, not a conventional dashboard wearing superhero decoration. Momentum Sans carries mission language while Momentum Mono identifies system state and measured data.

The first operational viewport is a continuous command deck, not a card gallery. Persistent top and left command rails establish mission status and direct access; the mission queue owns the wide dossier channel; and a connected instrument rail carries weekly score, career output, publishing output, and contextual evidence. The trajectory chart becomes a scan field, weekly comparison becomes a variance console, and Alfred analysis reads like a case file: what worked, what weakened, the next correction, and the follow-up condition. A Cmd/Ctrl+K console offers direct analytical and logging commands without adding navigation clutter.

**Key Characteristics:**

- Personal-only, private, and specific to the August 7 challenge.
- Direct execution: today’s weighted commitments appear before supporting analytics.
- A single deep-neutral dark theme with no theme switch or off-white surface.
- Graphite-blue rules, connective rails, and section-specific instrument framing instead of repeated cards.
- Cold steel blue for action, focus, and telemetry; green for completion; red only for negative deviation or error.
- Expressive Momentum Sans, operational Momentum Mono, and rare Georgia reflection.
- An original steel-blue winged command mark identifies BATCOMPUTER at product-chrome and app-icon scale; no third-party Batman artwork is embedded.
- One dismissible four-second secure-terminal diagnostic runs once per browser session and respects reduced-motion settings.
- Daily records can be intentionally closed; missing, open, and closed days remain distinct in the evidence model.
- Every heatmap cell opens a compact mission record without adding a navigation layer.
- The mission chart gives the overall trajectory highest contrast, keeps supporting systems secondary, and annotates the target band, mission milestones, and planned recovery without adding extra chart modes.
- No planning ceremony, timers, or productivity theater between the user and daily logging.

## Colors

The palette is deliberately narrow: four neutral black and gunmetal surfaces carry the product, cold steel blue carries action and analysis, and restrained status colors retain stable meanings.

### Primary

- **Phosphor Blue** (`#78ddeb`): The unmistakable interactive accent. Use it for primary controls, active challenge progress, selected system state, and explicit course corrections—not for ambient decoration.

### Secondary

- **Success Green** (`#68b99b`): Checked commitments, positive deltas, saved state, and completed controls.
- **Telemetry Blue** (`#abdfff`): Supporting chart lines, XP, comparative analysis, and live system labels. Its reduced contrast keeps the primary trajectory dominant.

### Tertiary

- **Danger Red** (`#d36d71`): Negative deltas, course deviation, and blocking errors only.

### Neutral

- **Canvas** (`#020405`): The application ground.
- **Command Paper** (`#060b0e`): Primary panels and contained chapters.
- **Inset Surface** (`#0a1115`): Controls, chart fields, and row hover.
- **Strong Inset Surface** (`#102129`): Progress tracks, stronger control hover, and deeper subdivisions.
- **Primary Ink** (`#edf8ff`): Mission language, headings, and primary values.
- **Muted Ink** (`#89a6b8`) and **Faint Ink** (`#526d7e`): Supporting explanation and low-emphasis operational metadata.
- **Gunmetal Rule** (`#173036`) and **Strong Gunmetal Rule** (`#367985`): One-pixel structure and interactive boundaries.

### Named Rules

**The Single-Night Rule.** BATCOMPUTER has one deep-dark theme. Do not add off-white surfaces, a light mode, or a theme switch.

**The Signal Rarity Rule.** Steel blue appears where the user can act, where the system is active, or where it recommends a correction; its scarcity makes the next move obvious.

**The One Signal, One Meaning Rule.** Bright steel blue means action, focus, or correction; pale blue means supporting telemetry; green means complete or positive; red means deviation or error. Never trade those meanings for decoration.

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

The application uses a centered fluid container capped at 1520px with a persistent left command rail and horizontal gutters that scale from 24px to 92px. A 12px dashboard gap and one-pixel rules create the instrument rhythm. The first viewport moves from the command mast and challenge status directly into today’s weighted commitments beside the connected live-instrument rail. Analytical proof follows; it never displaces daily execution. The rail indexes nine operational sectors and exposes the keyboard command console.

At 1080px the command rail disappears, wider dashboard chapters collapse to one column, and the mission queue remains ahead of supporting KPI evidence. At 760px content gutters reduce to 14px, task groups stack, the heatmap changes from 30 to 15 columns, and body metrics become two columns. At 480px the header stacks, the private label hides, task controls expand to the available width, signal and dossier metrics become one column, and wide charts retain an analytical canvas inside horizontal overflow.

**The Story Survives Reflow Rule.** Responsive layout may change columns and density, but it preserves challenge status → weighted execution → evidence → reflection.

## Elevation & Depth

BATCOMPUTER is flat by default and uses no ambient panel shadow. Depth comes from the four neutral surface levels, one-pixel gunmetal rules, inset scan fields, clipped command modules, and occasional one-pixel inner strokes. Restrained phosphor bloom is reserved for live signal traces and the original mark. The heatmap inspection ring and field-focus halo are functional exceptions. Data entry animation is brief and removed under reduced-motion preferences.

### Shadow Vocabulary

- **Selected Control** (`inset 0 0 0 1px var(--line)`): Identifies a selected chart range without lifting it.
- **Heatmap Inspection** (`0 0 0 2px var(--surface), 0 0 0 3px var(--accent)`): Isolates one hovered consistency cell.
- **Field Focus Halo** (`0 0 0 3px color-mix(in srgb, var(--blue) 18%, transparent)`): Reinforces text-entry focus.

### Named Rules

**The Flat-by-Default Rule.** Tonal separation and rules establish hierarchy; never add ambient shadows, glass, or blur to manufacture importance. Signal glow belongs only to active phosphor traces and focus evidence.

## Shapes

Primary panels, inputs, checks, and compact controls use a disciplined 1–2px radius. Major command surfaces clip one top-right corner, with an occasional bottom-left cut on standalone modules. Progress tracks, heatmap cells, chart keys, and telemetry tags are rectilinear. Circular geometry is reserved for status dots and milestone markers. Dashed strokes remain reserved for editable or not-yet-provided evidence.

The BATCOMPUTER mark is an original symmetrical winged command glyph drawn from an outlined chevron, central spine, and angular signal wings in phosphor blue. Preserve its wide silhouette, transparent ground, generous clear space, and hard points; never replace it with a copied game, film, or comic emblem or add an oval or decorative gradient.

**The Tactical Geometry Rule.** Use clipped corners only on primary command surfaces and keep inner controls rectilinear. Repeating cut corners at every nested level creates visual noise.

## Components

### Buttons

- **Shape:** Primary actions are 42–44px tall; compact controls are 32px tall; both use a 2px radius.
- **Primary:** Cold Steel Blue with dark Action Ink and compact uppercase Momentum Mono. Use it for consequential actions and explicit course corrections.
- **Hover / Focus:** Neutral controls move one tonal step stronger on hover. All keyboard-focusable controls receive a 2px steel-blue outline with 3px offset. Disabled controls retain their labels, reduce opacity, and remove the active cursor.
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
- **Focus:** Steel-blue outline for general keyboard focus; text entry uses the same border and restrained halo.
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
