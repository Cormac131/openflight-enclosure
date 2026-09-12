# OpenFlight enclosure — HarjotDhanota — 2026-09

This directory contains a draft OpenFlight enclosure designed around a Raspberry Pi 5, Roadom 7-inch touchscreen, Geekworm X1209 UPS HAT, and Geekworm X12-A1 battery carrier, with dedicated mounts for the camera and sensor/radar modules listed below.

The files are grouped so builders can download only the printable enclosure parts, while enclosure designers can reuse the separate electronics reference models in their own layouts.

## Directory layout

```text
enclosure/
  assembly/          Complete assembled STEP for inspection
  editable/          Editable Fusion 360 source archive
  printable/step/    Individual editable printable parts
  printable/stl/     Individual high-resolution print meshes

reference-models/
  electronics/       Display, Raspberry Pi, X1209, and X12-A1
  sensors/           BME280, LIS3DH, camera, and sound detector
  radars/            OPS243 and IWR6843LEVM
  connectors/        Panel-mount Ethernet and DC references
  hardware/          Inserts, screws, washers, and kickstand hardware
```

## Printable parts

- Housing back
- Housing front
- Combined IWR/OPS radar brace
- X12-A1 cradle brace
- X12-A1 battery door
- Kickstand
- Left kickstand peg
- Right kickstand peg

Every printable is supplied as both STEP and STL. Electronics and hardware reference models are STEP-only and are **not intended to be printed**.

## Main fitted components

- Raspberry Pi 5
- Geekworm X1209 UPS HAT
- Geekworm X12-A1 four-cell battery carrier
- Roadom 7-inch 1024 × 600 touchscreen
- OmniPreSense OPS243 radar
- Texas Instruments IWR6843LEVM radar
- InnoMaker CAM-MIPIOV9281-V2 camera, 32 × 32 mm / 28 mm hole spacing
- BME280 environmental sensor
- LIS3DH accelerometer
- 43.7 × 23.3 mm sound-detector reference board

## Notes

- The complete assembly STEP reflects the intended shown/hidden component state in the Fusion source.
- The screen reference includes a white rounded Pi-footprint outline on its rear to indicate Raspberry Pi orientation.
- Reference geometry is intended for mechanical layout and clearance checks. Verify critical dimensions against the physical hardware and current vendor drawings before manufacturing.
- This contribution is submitted as a draft for structural and mechanical review.

