# Printable parts

Each part has its own version folder so you can keep a release set and experiments side by side.

| Folder | Meaning |
| --- | --- |
| `v1/` | Current release — print these |
| `experimental/` | In-progress or test prints — do not use for a production unit unless you mean to |
| `eol/` | Withdrawn variants kept for archive only |

Mix versions only on purpose (for example a `v1` shell with an experimental radar).

```
stls/
  adapters/v1/     Pi adapters
  camera/v1/       Camera strip + sound-detector retainer
  feet/v1/         Solid and adjustable feet
  radar/v1/        Radar fronts
  screen/v1/       Display bezels
  shell/v1/        Rear shells (Ethernet, DC jack, power button)
  shell/eol/       Withdrawn USB-C rear shells — see shell/eol/README.md
```
