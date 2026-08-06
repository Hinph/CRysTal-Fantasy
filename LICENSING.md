# Licensing layout

This repository is **multi-license**. A single license file cannot accurately
cover every file.

## CRysTal Fantasy original code

The root `LICENSE` applies Apache-2.0 to original CRysTal Fantasy code owned by
Hinph, unless an individual file says otherwise. Add this header to
new original source files:

```text
Copyright 2026 Hinph
SPDX-License-Identifier: Apache-2.0
```

## Console Mode / simplermenu_plus files

Any file derived from an MPL-covered Console Mode or simplermenu_plus file must
stay under MPL-2.0. Preserve the upstream header and add a truthful modification
notice, for example:

```text
// SPDX-License-Identifier: MPL-2.0
// Copyright 2026 Retro Remake
// Derived from simplermenu_plus (rg35xx-cfw), MPL-2.0.
// Modified for CRysTal Fantasy in 2026 by Hinph.
```

Do not replace or remove the upstream copyright line.

## Third-party code and assets

`THIRD_PARTY_NOTICES.md` maps each component to the exact license text in
`LICENSES/`. A license file does not grant rights to an asset of unknown origin.
Uncleared assets must be replaced or separately licensed before release.

## ES-DE

CRysTal Fantasy currently interoperates with ES-DE but does not bundle ES-DE.
Merely reading ES-DE-generated metadata does not require copying ES-DE's MIT
license into the release. `LICENSES/ES-DE-MIT-conditional.txt` is provided only
for use if ES-DE code or resources are actually copied into this repository or
release.
