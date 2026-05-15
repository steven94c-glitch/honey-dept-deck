# Image folders

Each folder maps to a specific spot in the deck. Drop in JPGs/PNGs named `01.jpg`, `02.jpg`, etc. and they'll appear immediately on next page load. If a slot is empty, a black-and-white placeholder shows automatically — no broken image icons.

## Strips & film references

| Folder | Where it shows up | Slots | Aspect |
|---|---|---|---|
| `intro-strip/` | The horizontal scrolling marquee right after the "Hello." page | 8 (`01–08`) | wide, ~16:10 |
| `film-01-demographics/` | The 2×2 reference grid on the **Film 01 — Demographics** page | 4 (`01–04`) | 16:10 |
| `film-02-eat-it-anywhere/` | The 2×2 reference grid on the **Film 02 — Eat It Anywhere** page | 4 (`01–04`) | 16:10 |
| `film-03-note-from-our-founder/` | The 2×2 reference grid on the **Film 03 — A Note From Our Founder** page | 4 (`01–04`) | 16:10 |
| `film-04-goes-with-everything/` | The 2×2 reference grid on the **Film 04 — Goes With Everything** page | 4 (`01–04`) | 16:10 |
| `closing-strip/` | The horizontal scrolling marquee just before the "Thank You." page | 8 (`01–08`) | wide, ~16:10 |

## The Cast — character portraits

Each character has its own page in the Cast interlude. One portrait per folder, named `portrait.jpg`. Aspect 4:5 (slightly portrait, like a character study).

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
