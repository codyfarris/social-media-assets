# Idea 1 — Seasonal switch (week of Oct 26) — READY-TO-POST PACKS

Status: **Cody posts only after his OK.** Nothing queued. Silent video so Cody adds the TikTok sound in-app.
Aligned with Hook Lab draft `/workspace/askmyelf/pipeline/next-week-hooks-oct27.md` (#1).
Expires ~Nov 1 (jaylynn Halloween→Christmas itch audio).

## Files
| File | Role | Duration | Audio |
|---|---|---|---|
| `idea1_seasonal_v046.mp4` | **PRIMARY** (twins / living room) | 7.5s | none (0 streams) |
| `idea1_seasonal_v038.mp4` | **ALT** (bus stop → Leo runs home) | 7.2s | none (0 streams) |

1080×1920, yuv420p, +faststart. Hard cuts only. No swish/whoosh. No baked music.

## Sound (add in TikTok app)
- **Primary:** `original sound - jaylynn` (Halloween-but-Christmas-itch; music id `7694666776516365087` if useful; ~18.9M)
- **Alt if needed:** `Ramalama (Bang Bang)` — Róisín Murphy

## Caption (Hook Lab #1 — use exactly)
**Caption hook line:** Still Halloween at my house. Not at theirs.

**Full caption:**
Still Halloween at my house. Not at theirs. 🎃➡️🎄 Who else's kids are already asking when our Christmas elf comes back? 👇 askmyelf.com/tiktok

## On-screen text
- Baked-in Drive captions stay as-is (not covered, not blurred).
- **v046 (PRIMARY):** short seasonal meme in the clear mid/lower safe-zone gap so it does not sit on the baked top band (`WHAT WILL OUR ELF SAY FIRST?` / `NOBODY GUESSED THAT.`):
  - `Me: it's still Halloween 🎃`
  - `My kids: Christmas elf?? 🎄`
  - From frame 0; Anton + Noto Color Emoji; inside TikTok safe zone (x 60–918, y 288–1344).
- **v038 (ALT):** full three-line meme stack in the top safe zone (source top band is clear from 3.5s; baked captions stay at the bottom):
  - `Me: it's still Halloween 🎃`
  - `My kids: when does our`
  - `Christmas elf talk again?? 🎄`
  - From frame 0.

## Cuts used (source timestamps)
**v046** `/workspace/askmyelf/drive-videos/raw/v046.mp4`
1. `0.00–3.00` twins whispering
2. hard cut → `4.00–6.50` speech-bubble guesses (still kids; before app UI ~7.0)
3. hard cut → `17.50–19.50` reaction laugh + punch-in zoom (before end-card ~19.7)

**v038** `/workspace/askmyelf/drive-videos/raw/v038.mp4`
1. `3.50–6.10` bus-stop kids (after Ava top band clears; bottom caption stays)
2. hard cut → `6.35–8.75` Leo runs home (skips white flash at 6.2)
3. hard cut → `8.50–10.70` mom / “CAN OUR ELF TALK TOO?!” + punch-in (before app CTA ~10.8)

## Post notes for Cody
- Post natively in TikTok (Buffer can’t attach the sound).
- Prefer evening slot if clearing this week; seasonal window closes ~Nov 1.
- Kid names in the Drive clips (Leo, etc.) are fine as-is.
- Copy rule: “our/Christmas elf” only — never “the elf” / “Elf on the Shelf” in *our* words (baked Drive wording left alone).
- QC sheets + OCR: `qc/`. Build scripts: `build/`.

## QC checklist
- [x] 7–9s (7.5 / 7.2)
- [x] 0 audio streams
- [x] Text from frame 0, safe-zone asserted in `build/textpng.py`
- [x] OCR matches intended meme lines (`qc/ocr_beats.txt`)
- [x] freezedetect clean (no freeze >0.3s)
- [x] No swish/whoosh assets; no shared music
