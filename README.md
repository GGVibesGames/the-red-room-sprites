# The Red Room: character sprites (LPC, CC-BY-SA)

The character sprite sheets of **The Red Room**, a horror game by **GG Vibes Games** after the story by H. G. Wells (1896).
Game page: https://gg-vibes-games.itch.io/the-red-room

The protagonist, the old man and the old woman are made of **Liberated Pixel Cup (LPC)** parts, put together with the
[Universal LPC Spritesheet Character Generator](https://github.com/LiberatedPixelCup/Universal-LPC-Spritesheet-Character-Generator)
and edited for the game. Some of those parts are licensed CC-BY-SA only, so the sheets as edited for the game are shared here
under the same licence.

This repository holds **only the sprite sheets**, exactly as the game uses them. The game's code and its other assets are not here
and are not covered by this licence.

## Files

All sheets use 64 x 64 px frames, rows facing up, left, down, right. The walk sheets have 9 columns (column 0 standing,
1-8 walking); the idle and sitting sheets have 4 columns: at rest, breathing in (upper body 1 px higher), blinking, both.

| File | What it is |
|---|---|
| `sprites/lpc_protagonist_walk.png` | Protagonist, walk (4 rows). |
| `sprites/lpc_protagonist_candle.png` | Protagonist holding a candle (12 rows): rows 0-3 arms still, rows 4-7 one hand cupped round the flame, rows 8-11 the hand on its way up. The arms in rows 4-11 were drawn for the game. |
| `sprites/lpc_protagonist_candle_front.png` | The layer drawn over the candle for the sheet above (same 12 rows): the hand cupping the flame and the fist on the candle's dish. |
| `sprites/lpc_old_man_walk.png` | The old man with the cane, walk (4 rows). |
| `sprites/lpc_old_woman_walk.png` | The old woman, walk (4 rows). |
| `sprites/lpc_old_woman_shawl.png` | The old woman with her white cap recoloured into a dark wool shawl (4 rows). |
| `sprites/*_idle.png` | Standing still, for each sheet above with the same name (same rows): breathing and blinking, made from that sheet's standing frame and the LPC "closed eyes" face. |
| `sprites/lpc_protagonist_sit.png` | Protagonist sitting on a chair (4 rows), from the LPC sit parts; his coat is the LPC Cardigan recoloured like the frock coat, over the Longsleeve 2 Buttoned shirt. |
| `sprites/old_woman_rocking.png` | 40 x 52 px: the old woman (from the shawl sheet) sitting in a side-view rocking chair. |
| `sprites/old_woman_rocking_look.png` | The same, her head turned to the viewer. |

The candle itself and the rocking chair's colours come from CC0 packs by Riclmbr (https://riclmbr.itch.io).

## Licence

The sprite sheets are licensed under **Creative Commons Attribution-ShareAlike 3.0 (CC-BY-SA 3.0)**:
https://creativecommons.org/licenses/by-sa/3.0/ (full text in [LICENSE](LICENSE)).
As CC-BY-SA 3.0 allows, you may also use them under CC-BY-SA 4.0: https://creativecommons.org/licenses/by-sa/4.0/

If you use them:
- credit the original LPC artists listed in [CREDITS.md](CREDITS.md), and GG Vibes Games for the edits;
- link to this licence;
- share your own changes to the sheets under the same licence.

Suggested credit line:

> Character sprites based on Liberated Pixel Cup (LPC) art by the artists listed at https://github.com/GGVibesGames/the-red-room-sprites/blob/main/CREDITS.md, edited by GG Vibes Games. CC-BY-SA 3.0.
