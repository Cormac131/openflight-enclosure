# Shell and power

The rear body. Pick one board-specific file. Every current `v1` shell has the same rear I/O:

- **Ethernet** through the rear
- **Barrel DC jack** for power
- **Power button**

USB-C rear shells are **EOL** (USB-C spec compatibility) — see [`stls/shell/eol/`](../../stls/shell/eol/README.md).

![Pi and UPS mounted in the shell](../drawings/assy-01-boards.png)

## Board-specific shells

| Board | STL |
| --- | --- |
| x1209 (uses x12-a1 shell + adapter) | [`stls/shell/v1/Shell-x12-a1.stl`](../../stls/shell/v1/Shell-x12-a1.stl) |
| x1202 (UPS; also use this shell with no UPS) | [`stls/shell/v1/Shell-x1202.stl`](../../stls/shell/v1/Shell-x1202.stl) |
| x1206 | [`stls/shell/v1/Shell-x1206.stl`](../../stls/shell/v1/Shell-x1206.stl) |

**x12-a1 is not a standalone build.** Print `Shell-x12-a1` only with the [x1209 Pi adapter](adapters.md).

**x1202 is the UPS shell.** With the UPS board, print that shell only. With no UPS, still print an x1202 shell and add the [x1202 Pi adapter](adapters.md).

![Rear render](../../renders/rear.png)

## Hardware

See [Required hardware](../hardware.md).

| Qty | Item | Role |
| --- | --- | --- |
| 4 | M2.5 insert | UPS and Raspberry Pi |
| 2 or 4 per bay | M2.5 insert | Each of 3 Adafruit bays you populate |
| 10 | M3×8 / M3×10 / M3×12 | Mount screen and lower front to the shell |
| 4 | M3 insert | Adjustable feet only — none if using solid feet |

Same counts on every current shell.

## Print notes

Print **flat on its back** (rear of the enclosure on the bed). **Supports required; tree recommended.** Minimum bed **220 × 190 mm**.

![Shell print orientation](../drawings/print-shell.png)
