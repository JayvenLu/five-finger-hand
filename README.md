# Five-Finger Dexterous Hand

Plain static GitHub Pages site for the five-finger dexterous hand build.

Live page: https://jayvenlu.github.io/five-finger-hand/

## Open-source CAD

The editable hardware design sources are available in [`assets/CAD`](assets/CAD):

| Model | STEP source |
| --- | --- |
| Fingertip mold | [`mold.STEP`](assets/CAD/mold.STEP) |
| Thumb component | [`thumb.STEP`](assets/CAD/thumb.STEP) |

Use the STEP files for manufacturing and modification.

The CAD sources under `assets/CAD/` are licensed under the [CERN Open Hardware Licence Version 2 - Strongly Reciprocal](assets/CAD/LICENSE.txt). Modified designs conveyed to others must remain available under the reciprocal terms of that license. The website code, photographs, and other media outside `assets/CAD/` are not covered by this CAD license.

Suggested citation:

> Xiaofan Lu, Yuankai Lin, and Tian Xu, "Five-Finger Dexterous Hand CAD," GitHub repository, 2026. https://github.com/JayvenLu/five-finger-hand

See [`assets/CAD/README.md`](assets/CAD/README.md) for credits, license scope, and the canonical source location.

## Local preview

```powershell
python -m http.server 4183 --bind 127.0.0.1
```
