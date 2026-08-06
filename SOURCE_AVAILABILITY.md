# Source availability and relinking

License copies alone are not sufficient for this executable distribution.

## MPL-covered source

Publish the complete, preferred source form of every MPL-covered file used in
the modified executable, including every CRysTal modification to those files.
Retain the original SPDX and copyright headers. Include build instructions and
identify the exact upstream Console Mode revision used.

The official Console Mode repository publicly describes itself as the
corresponding source for the MPL-covered portion only; it is not a complete
build tree. Therefore the CRysTal repository must not merely point to upstream
if CRysTal changed those MPL files. Publish the modified files themselves.

## LGPL statically linked libraries

Console Mode's built-in notice says SDL 1.2, SDL_image and SDL_ttf are statically
linked under LGPL-2.1. Before redistributing the modified executable, include
or link to the exact corresponding library source and provide the object files,
link scripts or other relinkable material required by LGPL-2.1 for recipients
to relink the executable against modified library versions.

Ask Retro Remake for its canonical Console Mode 1.1.2 source/relink compliance
bundle. Do not claim this requirement is satisfied until that bundle or an
equivalent reproducible package is actually available to release recipients.

## CRysTal helper source

Publish the source and build instructions for every CRysTal helper executable.
For Go helpers, include the Go source and the Go toolchain version. For native
helpers, include source, compiler commands and any third-party dependencies.

## Recommended repository directories

```text
src/                     # CRysTal original source
upstream-mpl/            # modified MPL-covered Console Mode files
helpers/                 # source/build files for all CRysTal helpers
relink/                  # LGPL relinkable objects/scripts or upstream bundle
LICENSES/
NOTICE
THIRD_PARTY_NOTICES.md
MODIFICATIONS.md
SOURCE_AVAILABILITY.md
ASSET_PROVENANCE.md
```
