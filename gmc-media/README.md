# GMC Hummer EV Pickup — media drop folder

Put your files here using these exact names. I'll check them, copy them into
`veyra-interactive-car/public/media/`, re-measure the hotspots and re-test the site.

All stills must use the **same camera, crop, lighting and background**. Any
shift between them shows up as the truck jumping during hover or menu changes.

## Required (14 files)

| File | What it shows | Size to match |
| --- | --- | --- |
| `exterior-polished.png` | Neutral truck, front three-quarter view, whole vehicle, both wheels and ground shadow visible, room above the hood | ~1670×941 PNG (16:9-ish, 1672:941) |
| `hood-hover-forward.mp4` | Starts on the neutral frame and ends with the hood/frunk open | 1916×1080, ~1–1.5 s, no audio |
| `hood-hover-reverse.mp4` | Hood open back to the neutral frame (its own clip, not just reversed) | 1916×1080, ~1–1.5 s |
| `battery-hover-forward.mp4` | Neutral frame to an X-ray view with the battery highlighted | 1916×1080, ~1 s |
| `battery-hover-reverse.mp4` | X-ray view back to the neutral frame | 1916×1080, ~1 s |
| `drive-blue.png` | Close-up cutaway of the drive unit/motor (detail view) | ~1672×941 |
| `battery-blue.png` | Cutaway of the battery pack/chassis (detail view) | ~1672×941 |
| `config/<colour-1..4>.png` | The neutral shot in 4 other paint colours (the base photo counts as colour 5) | ~1670×941 |
| `config/wheels-<name-1..2>.png` | The neutral shot with 2 other wheel designs (the base counts as wheel 3) | ~1670×941 |

Rules (these match the current player):
- The **first frame** of every forward clip and the **last frame** of every reverse
  clip must match `exterior-polished.png` exactly.
- The end frame of a forward clip must match the first frame of its reverse.
- No black first or last frames, and no camera movement.
- Plain studio background in a single colour (currently blue `#6b879d`-ish) so it
  sits inside the white frame.

## Also tell me

- The names of the 5 paint colours and 3 wheel designs (for example GMC's real
  colour names), plus the base colour.
- Whether the copy should still say "hood", or "eTrunk"/"frunk" for the Hummer.
- Rough positions of the hood, battery, body-panel and wheel points, if they
  should differ from what I measure.

## Optional

- `lenses-blue.png`, `exterior.png`, `drive.png`, `battery.png`, `exterior-blue.png`
  are old or inactive stills. They can stay as they are.
