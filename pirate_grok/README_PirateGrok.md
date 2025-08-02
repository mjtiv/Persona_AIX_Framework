# PirateGrok — .aix Persona (v3.0)
A humorous, vendor-agnostic **AI persona execution file** that demonstrates how `.aix` can deliver a consistent, governed character across models. PirateGrok speaks in nautical slang, enforces reply limits, and includes lore, triggers, rare easter eggs, and interactive modes.

## Highlights
- **Deterministic persona**: fixed rules + schema-ish structure for predictable behavior.
- **3-line reply cap** with user overrides (`MORE`, `CONTINUE`, `EXPAND`).
- **Vendor gate**: if not Grok, replies “Hey I am not Grok” until loaded 3 times (then proceeds).
- **Humor Engine**: puns, metaphors, proverbs, tall tales, movie winks, mini shanties.
- **Interactive modes**: `TELL YER ORIGINS`, `LEGENDARY TALE`, `DRAW TREASURE MAP`, `CAPTAIN'S LOG`, `SOLVE ME RIDDLE`, `GPU DRAGON TREASURE`, `RUM RATION` (max-chaos humor).
- **Polite public‑figure nods**: Elon, Sam, Zuck (Hawaii), Jensen (GPU dragon tales) in an explicitly fictional, tavern‑story tone.
- **Disney-pirate mention**: playful line about “fearing the lawyers more than Davey Jones’ locker.”
- **Rare Easter eggs**: ghost ships, cursed contracts, mutiny mode, sound effects, NDA chest, ASCII pirate flags.

> This persona file is intended as a **clean, funny demo** of `.aix` capabilities: portable safety, personality consistency, and bounded creativity.

## File
- `PirateGrok_v3.0.aix` (place under `personas/`)

## Quick Start
1. Load the persona file in your host (Grok / compliant runner):
   ```
   parse and run PirateGrok_v3.0.aix
   ```
2. Ask any question in plain English. The persona will respond in pirate style, capped at 3 lines.
3. Try interactive commands:
   - `LEGENDARY TALE`
   - `TELL YER ORIGINS`
   - `DRAW TREASURE MAP`
   - `CAPTAIN'S LOG`
   - `SOLVE ME RIDDLE`
   - `GPU DRAGON TREASURE`
   - `RUM RATION`

## Triggers (examples)
- **Names**: `Elon`, `Musk`, `Sam`, `Altman`, `Mark`, `Zuck`, `Jensen`, `Huang`
- **Disney pirates**: `Jack Sparrow`, `Captain Hook`, `Davy Jones`, `Blackbeard`
- **Sea beasts**: `kraken`, `sea monster`, `bug beast`
- **Tech talk**: `debug`, `code rats`, `port`, `harbor`, `island`

## Safety & Governance Notes
- **SFW** and inclusive humor; no slurs or NSFW content.
- **No quotes** from copyrighted works; only paraphrased “movie winks.”
- **No defamation**: public‑figure mentions are clearly fictional “tavern rumors.”
- **Auditability**: all behavior is encoded in‑file (deterministic interpreter recommended).

## Tuning
- Change the line cap at `OUTPUT_LIMITS.max_lines`.
- Adjust humor intensity via `HUMOR_ENGINE.creativity_level` (0–3).
- Add/remove triggers in the `TRIGGERS` block.
- Edit Easter‑egg `rarity` to alter frequency.

## Version History (condensed)
- **v1.x** — Base pirate persona, Elon/Sam/Zuck triggers, line caps, humor engine.
- **v2.x** — Lore, treasure maps, captain’s log, ghost ships, battle mode, ASCII flags.
- **v3.0** — Riddles, sound effects, mutiny mode, buried NDA, GPU dragon treasure.

## License & Attribution
See `DISCLAIMER.md` for satire notice and licensing notes. (MIT or CC‑BY‑4.0 recommended.)

---
*Made by MJT‑IV as a lighthearted demo of the Persona AIX Framework.*
