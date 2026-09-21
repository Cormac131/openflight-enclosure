# Printing

Minimum print bed: **220 × 190 mm**. See the [project README](../README.md#printer) for example printers.

## Files

Print only the **`v1/`** STLs from your [variant list](choosing-a-variant.md). Do not print from `experimental/` or `eol/` unless you intend to. Do not use a screen bezel that does not match the panel.

CAD source for checking orientation: [`../step/Open-Flight-Monitor-3.step`](../step/Open-Flight-Monitor-3.step)

## Suggested starting point

Fill in after a known-good print. These are placeholders, not validated profiles.

| Setting | Suggestion | Notes |
| --- | --- | --- |
| Material | PETG or ABS/ASA | TODO: confirm preferred filament |
| Layer height | 0.2 mm | |
| Nozzle | 0.4 mm | |
| Walls | 3–4 | |
| Infill | 15–20% | |
| Supports | Tree where noted below | Shell, camera, and no-fill radar |
| Bed | **220 × 190 mm** minimum | |

## Orientation

**Camera and screen:** cosmetic face on the build plate.

**Radar (current no-fill):** on its back. **Tree supports required.** (No-fill means no cover in front of the radars, not a slicer infill setting.)

**Shell:** flat on its back (rear of the enclosure on the bed). Needs supports; **tree supports recommended**.

![Radar no-fill — on its back](drawings/print-radar-nofill.png)

Current radar (no-fill): on its back. **Tree supports required.** The filled front is EOL (`radar/eol/`).

![Screen — face to the plate](drawings/print-screen.png)

Screen: face to the plate.

![Camera — face to the plate](drawings/print-camera.png)

Camera strip: face to the plate. **Tree supports required.** The sound-detector retainer is a separate 2.5 mm plate — print it **flat**, no supports.

![Shell — on its back](drawings/print-shell.png)

Shell: printed on its back. **Supports required; tree recommended.**

## Per-part exceptions

- **Radar** — print on its back; tree supports. No cover in front of the radars (RF). See [radar](parts/radar.md).
- **Sound-detector retainer** — print flat. See [camera](parts/camera.md).
- **Insert bosses** — pause is not required; press inserts after printing.

## Fit

If holes are tight, note slicer XY compensation or drill sizes on the relevant part page rather than scaling the whole model.

If you like the design, [buy me a coffee](https://buymeacoffee.com/cormacmcgrath).
