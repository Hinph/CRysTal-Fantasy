# Third-party notices

This table reflects the components named by Console Mode 1.1.2's built-in
license screen and the CRysTal Fantasy Test Release payload.

| Component | Treatment | License file |
|---|---|---|
| Console Mode original Retro Remake code | Modified upstream work; retain all notices | `Apache-2.0.txt` |
| Console Mode files derived from simplermenu_plus | Covered files and modifications remain MPL | `MPL-2.0.txt` |
| SDL 1.2.15, SDL_image 1.2.12, SDL_ttf 2.0.11 | Statically linked in Console Mode | `LGPL-2.1-only.txt` |
| SDL_gfx 2.0.26 | Statically linked | `Zlib.txt` |
| FreeType 2.10.4 | Used under FreeType License | `FreeType-FTL.txt` |
| libpng 1.6.40 | Statically linked | `Libpng-2.0.txt` |
| zlib 1.2.11 | Statically linked | `Zlib.txt` |
| stb_image / stb_image_write | Dual option stated upstream | `MIT.txt`, `Unlicense.txt` |
| miniz | MIT | `MIT.txt` |
| minimp3 | CC0-1.0 | `CC0-1.0.txt` |
| Boost 1.83 | Boost Software License 1.0 | `Boost-1.0.txt` |
| Go standard library in Go-built CRysTal helper executables | BSD-style Go license | `Go-BSD-3-Clause.txt` |
| PromptFont | SIL Open Font License 1.1 | `OFL-1.1.txt` |
| Noto Sans CJK JP, when packaged | SIL Open Font License 1.1 | `OFL-1.1.txt` |
| DejaVu Sans / Bitstream Vera / Arev glyphs | Font-specific notices | `DejaVu-Bitstream-Arev.txt` |
| console-logos compilation | MIT; console names/logos remain trademarks | `MIT.txt` |
| ES-DE | Not bundled; include only if code/resources are copied | `ES-DE-MIT-conditional.txt` |

The exact component list embedded in the official Console Mode 1.1.2 binary is
preserved in `ConsoleMode-1.1.2-built-in-notices.txt`.

## Items requiring upstream confirmation

* **Akrobat font:** Console Mode's binary identifies Akrobat/Fontfabric but does
  not state a standard open-source license. Preserve the embedded upstream
  notices, do not distribute the font separately, and ask Retro Remake to
  confirm the redistribution basis.
* **No-Intro/Redump-derived data:** preserve upstream attribution and verify the
  terms for any database material actually redistributed.
* **Static LGPL compliance:** provide the corresponding library source and the
  relinkable material/build instructions required for the exact executable, or
  obtain Retro Remake's canonical compliance bundle and written confirmation
  that redistributors may use it.
