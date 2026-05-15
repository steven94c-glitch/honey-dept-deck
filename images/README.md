# Image folders

Each folder maps to a specific spot in the deck. Drop in JPGs/PNGs with the filename shown below and they'll appear immediately on next page load. If a slot is empty, a black-and-white placeholder shows automatically — no broken image icons.

## Strips & film references

| Folder | Where it shows up | Slots | Aspect |
|---|---|---|---|
| `intro-strip/` | The horizontal scrolling marquee right after the "Hello." page | 8 (`01–08`) | wide, ~16:10 |
| `film-02-eat-it-anywhere/` | The 2×2 reference grid on the **Film 01 — Eat It Anywhere** page | 4 (`01–04`) | 16:10 |
| `film-04-goes-with-everything/` | The 2×2 reference grid on the **Film 02 — Goes With Everything** page | 4 (`01–04`) | 16:10 |
| `closing-strip/` | The horizontal scrolling marquee just before the "Thank You." page | 8 (`01–08`) | wide, ~16:10 |

> Note: folder names for the film grids carry the legacy numbering (`film-02-…`, `film-04-…`). They still hold the reference imagery for what is now Film 01 and Film 02 in the live deck.

## The Cast — character portraits

Each character has its own page in the Cast chapter. One portrait per folder, named `portrait.jpg`. Aspect 4:5 (slightly portrait, like a character study).

| Folder | Character |
|---|---|
| `character-01-army-general/` | General Maurice "Mo" Greaves |
| `character-02-dog-walker/` | Coriander Wexler-Pike |
| `character-03-bee-keeper/` | Linwood Earhardt |
| `character-04-body-builder/` | Roman "Rome" Garafalo |
| `character-05-bicyclist/` | Henrik "Ren" Bjeldevskij |
| `character-06-bingo-regular/` | Margery "Marge" Bellanca |
| `character-07-cops/` | Officers Frank Tedesco & "Pencil" Pencillo |
| `character-08-hair-dresser/` | Stephanie "Steph" Ciardullo |
| `character-09-break-up/` | Devon Marquardt |
| `character-10-painter/` | Wesley "Wez" Cottingham |
| `character-11-monk/` | Brother Pemwa Tsering |
| `character-12-boxer/` | "Sweet" Sammy Quintero |
| `character-13-window-cleaner/` | Vasili "Vass" Romanenko |
| `character-14-broken-down-car/` | Lance & Bernadette Hoag |

## Notes

- Filenames must be exact. Strips/refs: `01.jpg` … `08.jpg` (two-digit zero-padded). Characters: `portrait.jpg`.
- All images get auto-converted to black & white via CSS, so don't worry about prepping them grayscale yourself.
- Source images at least 1200px wide for crispness on retina.
- If you use `.png` instead of `.jpg`, update the filename in `index.html` for that slot.
