# Idea 2 — Midnight-panic POV series (week of Oct 26) — READY-TO-POST PACKS

Status: **Cody posts only after his OK.** Nothing queued. Silent video so Cody adds the TikTok sound in-app.
Aligned with Hook Lab draft `/workspace/askmyelf/pipeline/next-week-hooks-oct27.md` (#2–#4) and review brief idea 2.

## Files
| File | Role | Duration | Audio |
|---|---|---|---|
| `idea2_midnight_v040.mp4` | Flour / 11:58 PM | 10.0s | none (0 streams) |
| `idea2_midnight_v304.mp4` | Towel / 12:03 AM | 10.27s | none (0 streams) |
| `idea2_midnight_v313.mp4` | Laundry / 11:40 PM | 10.27s | none (0 streams) |

1080×1920, yuv420p, +faststart. Hard cuts only. No swish/whoosh. No baked music. Live-action only (app UI / Elf Missions / pricing outro skipped).

## Sound (add in TikTok app — same family for the series; do NOT bake in)
- **Primary:** `I've got a plan` (SocialBee Oct 21 trend)
- **Alt:** `RealestK Toxic` — RealestK
- **Alt:** `Trumpets` — Jason Derulo

## Captions (Hook Lab — use exactly)

### v040
**Caption hook:** 11:58 PM. Flour everywhere. I went to bed.
**Full:** 11:58 PM. Flour everywhere. I went to bed. 😴 What's your latest-ever elf save? 👇 askmyelf.com/tiktok

### v304
**Caption hook:** 12:03 AM. Towel on. Crafting? Nope.
**Full:** 12:03 AM. Towel on. Crafting? Nope. Tonight your elf can talk and you can sleep. What time do you usually remember? ⏰ askmyelf.com/tiktok

### v313
**Caption hook:** 11:40 PM. Laundry done. Then I remembered.
**Full:** 11:40 PM. Laundry done. Then I remembered. Not this year. What's the last chore before you crash? 🧺 askmyelf.com/tiktok

## On-screen text
- Baked-in Drive captions stay as-is (not covered, not blurred) — including any baked “the elf”.
- **Our overlays** (Anton + Rubik Mono One; TikTok safe zone x 60–918, y 288–1344):
  - Big **red digital-clock** timestamp from frame 0 (placed mid safe-zone under the baked top band).
  - Typewriter-ish punchline phrases at ~0.55s then ~1.25s.
  - v040: `11:58 PM` → `Flour everywhere.` → `I went to bed.`
  - v304: `12:03 AM` → `Towel on.` → `Crafting? Nope.`
  - v313: `11:40 PM` → `Laundry done.` → `Then I remembered.`

## Cuts used (source timestamps)
**v040** `/workspace/askmyelf/drive-videos/raw/v040.mp4` (29.0s source)
1. `0.00–3.40` panic flour mess + slow push-in
2. hard cut → `3.40–7.10` exhausted close + continue push (before family inset / app UI ~7.5)
3. SNAP → `22.00–24.90` bed calm, slight ease-out to wide (before endcard ~25.0)

**v304** `/workspace/askmyelf/drive-videos/raw/v304.mp4` (25.5s source)
1. `0.00–2.90` towel panic + slow push-in
2. hard cut → `2.90–6.70` “not crafting” beat + push (before app UI ~7.0)
3. SNAP → `18.25–21.80` live return / “KID: THRILLED…” (before endcard ~22.0)

**v313** `/workspace/askmyelf/drive-videos/raw/v313.mp4` (25.5s source)
1. `0.00–2.90` laundry folded + slow push-in
2. hard cut → `2.90–6.70` “Not this year” + push (before app UI ~7.0)
3. SNAP → `18.25–21.80` live return / “LAUNDRY: DONE…” (before endcard ~22.0)

## Motion
- Panic halves: slow push-in (~1.0→1.22 via zoompan).
- Calm half: snap cut + slight ease-out (1.08→1.0) to a wider still — not a freeze-frame.
- No swish/whoosh assets.

## Post notes for Cody
- Post natively in TikTok (Buffer can’t attach the sound).
- Prefer evening slot (7:30–8:30 PM CT) if clearing this week.
- Kid names in Drive clips are fine as-is.
- Copy rule: “our/your/Christmas elf” only in *our* words — never “the elf” / “Elf on the Shelf” (baked Drive wording left alone).
- QC sheets + OCR: `qc/`. Build: `build/build_idea2.py`, `build/textpng_idea2.py` (reuses safe-zone patterns from `textpng.py`).

## QC checklist
- [x] 10–12s (10.0 / 10.27 / 10.27)
- [x] 0 audio streams
- [x] Text from frame 0; punch phrases ~0.55s / ~1.25s; safe-zone asserted in `textpng_idea2.py`
- [x] OCR sees clock + punchlines (`qc/ocr_idea2.txt`); baked top bands still readable
- [x] freezedetect clean (no freeze >0.3s)
- [x] No app UI / pricing outro; no swish; no shared baked music
