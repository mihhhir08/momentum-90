# BATCOMPUTER v2 — Build Plan

Day 20 restart. Sector-switched terminal, two voices, survivable gaps.

## Why v2

v1 was abandoned after a 6-day life gap. Diagnosis: the system had no
concept of returning. Grey cells, zeroed streaks, wrecked averages — opening
it meant facing evidence of failure, so it stopped being opened.

v2 fixes the return path first, the shell second, the voice third.

## Mechanics

**Floor / score split.**
- Floor (binary, decides if the day counts): 10,000 steps · post across
  socials · scalp massage.
- Score (0-100, weighted, unchanged): how good the day was.
- Everything else is bonus, never obligation.

**Gaps are survivable.**
- Missing days become OFF-GRID, not failed.
- Streaks split: current run + longest run. A break can't destroy the best.
- Charts show a visible break, not a zero.
- Return Protocol: boot announces the gap once, Alfred addresses it once,
  then never again.

## Voices

- **ORACLE** — system chrome. Cold, operational, tactical. All interface text.
- **ALFRED** — one daily line via OpenRouter. Personal, dry, unimpressed.
  Cached daily in Supabase. Writes into the case file overnight.

## Shell

Fixed viewport, sector switching, no page scroll. Nine sectors on the rail
swap the viewport instead of jumping to an anchor. Drawn connections between
nodes. Continuous life: sweeps, decode-in, resolving values. Layered depth
under a fixed scan overlay.

## Boot

The boot IS the briefing. Floor status, gap announcement, Alfred's line.
Earns its seconds instead of taxing them.

## Removed

Progress photos (UI + storage bucket). Waist metric. RFM estimate.

## Sound

Web Audio synthesis — CRT hum, relay clicks, servo sweep. No media files.
Muteable.

## Delivery

- Nightly Vercel cron -> Resend nudge (free tier, test sender).
- Read-only share route `/dossier/[token]` from a snapshot table.
  Body metrics stripped. No write path.

## Invariants

Scoring logic preserved byte-for-byte. 20 days of history and every past
score stay identical. Supabase schema changes stay additive.
