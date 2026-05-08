# Image folders

Each folder maps to a specific spot in the deck. Drop in JPGs/PNGs named `01.jpg`, `02.jpg`, etc. and they'll appear immediately on next page load. If a slot is empty, a black-and-white placeholder shows automatically — no broken image icons.

| Folder | Where it shows up | Slots | Aspect |
|---|---|---|---|
| `intro-strip/` | The horizontal scrolling marquee right after the "Hello." page | 8 (`01–08`) | wide, ~16:10 |
| `film-01-demographics/` | The 2×2 reference grid on the **Film 01 — Demographics** page | 4 (`01–04`) | 16:10 |
| `film-02-eat-it-anywhere/` | The 2×2 reference grid on the **Film 02 — Eat It Anywhere** page | 4 (`01–04`) | 16:10 |
| `film-03-note-from-our-founder/` | The 2×2 reference grid on the **Film 03 — A Note From Our Founder** page | 4 (`01–04`) | 16:10 |
| `film-04-goes-with-everything/` | The 2×2 reference grid on the **Film 04 — Goes With Everything** page | 4 (`01–04`) | 16:10 |
| `closing-strip/` | The horizontal scrolling marquee just before the "Thank You." page | 8 (`01–08`) | wide, ~16:10 |

## Notes

- Filenames must be exact: `01.jpg`, `02.jpg`, … `08.jpg`. Two-digit zero-padded.
- All images get auto-converted to black & white via CSS so don't worry about prepping them grayscale yourself.
- Strips display each image at ~28vw × 32vh. Reference grids display each at ~45% page width × 16:10 aspect. Source images at least 1200px wide for crispness.
- If you use `.png` instead of `.jpg`, update the filenames in `index.html` (search for the folder name to find the references).
