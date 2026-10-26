# Idea 3 — Save-bait compilation (week of Oct 26) — READY-TO-POST PACK

Status: **Cody posts only after his OK.** Nothing queued. Silent video so Cody adds the TikTok sound in-app.
Aligned with review brief idea 3 in `/workspace/askmyelf/performance-reviews/2026-10-26.md`. Save CTA kept (not comment-bait).

## Files
| File | Role | Duration | Audio |
|---|---|---|---|
| `idea3_savebait.mp4` | 5 zero-mess Christmas elf nights | 17.0s | none (0 streams) |

1080×1920, yuv420p, +faststart. Hard jump cuts only. No zooms. No swish/whoosh. No baked music. Live-action only (app UI / Elf Missions / pricing outro skipped).

## Sound (add in TikTok app — do NOT bake in)
- **Primary:** `Holly Jolly Christmas` — Michael Bublé
- **Alt:** `Rockin' Around The Christmas Tree` — Brenda Lee
- **Fallback:** a Commercial Music Library holiday track if the business account blocks those

## Caption (review — save CTA; use exactly)
Save this for December. 5 nights where your elf does the work, not you. Which one first? 3 free chats at askmyelf.com/tiktok

Hook / on-cover idea (not baked): `5 zero-mess Christmas elf nights for tired parents 💡 Bookmark this`

## On-screen text
- Baked-in Drive captions stay as-is (not covered, not blurred) — including any baked “the elf”.
- **Our overlays** (Poppins Bold numbered pills; TikTok safe zone x 60–918, y 288–1344):
  - Pastel rounded pills bottom-center (`center_y=1260`, bottom ≤1322): `1/5` mint → `2/5` peach → `3/5` lavender → `4/5` sky → `5/5` butter
  - Text from frame 0 on every segment
  - Pills sit above baked bottom captions (those land ~y 1450+)

## Cuts used (source timestamps)
1. **v013** `/workspace/askmyelf/drive-videos/raw/v013.mp4` — `0.20–3.60` printable letter / name (dining table)
2. **v311** `/workspace/askmyelf/drive-videos/raw/v311.mp4` — `2.20–5.60` Elf Task: tidy playroom (cleaning motion)
3. **v302** `/workspace/askmyelf/drive-videos/raw/v302.mp4` — `0.40–3.80` Daily Note: heard you made your bed (bedroom)
4. **v035** `/workspace/askmyelf/drive-videos/raw/v035.mp4` — `0.30–3.70` 7 PM family chat (living room)
5. **v301** `/workspace/askmyelf/drive-videos/raw/v301.mp4` — `0.80–4.20` bedtime secret (night bedroom)

Each segment 3.4s → **17.0s** total. Different room every cut.

## Motion
- On-beat hard jump cuts only.
- No zoompan / punch-in / freeze-frames.
- No swish/whoosh assets.

## Post notes for Cody
- Post natively in TikTok (Buffer can’t attach the sound).
- Prefer evening slot (7:30–8:30 PM CT) if clearing this week.
- Kid names in Drive clips are fine as-is.
- Copy rule: “your/our elf” only in *our* words — never “the elf” / “Elf on the Shelf” (baked Drive wording left alone). Feature names: Elf Tasks, Daily Notes.
- QC sheets + OCR: `qc/`. Build: `build/build_idea3.py`, `build/textpng_idea3.py` (reuses safe-zone patterns from `textpng.py`).

## QC checklist
- [x] 15–20s (17.0s)
- [x] 0 audio streams
- [x] Text (pills) from frame 0 on each segment; safe-zone asserted in `textpng_idea3.py`
- [x] OCR: baked bands readable; pill crop reads `4/5` (tesseract flaky on small pastels — visual sheet confirms 1/5…5/5)
- [x] freezedetect clean (no freeze >0.3s)
- [x] No app UI / pricing outro; no swish; no shared baked music; no zooms
