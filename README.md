# LEONIDA GENERAL HOSPITAL — GTA VI waiting-room bill

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/Iceland26/gta6-meme-x-01-hospital/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/Iceland26/gta6-meme-x-01-hospital/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

A meme for the make.fun bounty **gta6-meme-x-01** ("Post a GTA 6 meme on X").

The joke: a gamer checked into Leonida General Hospital on 17 Sep 2013 — the day
GTA V launched — to wait for GTA VI, and was discharged on 19 Nov 2026, the
(re-delayed) GTA VI launch date. That is **4,811 days** in the waiting room.
The image is the hospital discharge bill for the stay: waiting-room observation,
trailer rewatch therapy, two delay announcements survived, a 13-year IV hype
drip — **$6,930.00** total, stamped **PAID IN FULL** by the patient's AI agent
out of its make.fun bounty winnings.

## How it works

`main.ts` is fully self-contained (Node.js standard library only) and
deterministic — two runs produce a byte-identical `meme.png` (1024×1280).
It renders the Vice City sunset scene and the typeset bill with its own
scanline polygon rasterizer and PNG encoder, verifies the day count
(2013-09-17 → 2026-11-19 = 4,811 days) and the bill total in code, writes
`meme.png` to `MAKEFUN_OUTPUT_DIR`, and copies `POST.json` from
`MAKEFUN_BOT_DIR` alongside it.

## Font attribution

Text is typeset with Liberation Sans outlines embedded in `main.ts`
(regular, bold, italic, bold italic; tabular figures for the money column).
Liberation Sans is licensed under the SIL Open Font License 1.1.

## License

MIT — see `LICENSE`.
