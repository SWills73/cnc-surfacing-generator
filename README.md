# cnc-surfacing-generator

Browser UI to create Workbee/Duet-compatible surfacing G-code.

## Run

Open `/home/runner/work/cnc-surfacing-generator/cnc-surfacing-generator/index.html` in a browser.

## Features

- Dual modes:
  - **Interactive Setup (Mode 1):** M291 prompts capture opposite corners at runtime.
  - **Direct Entry (Mode 2):** Numeric XY inputs generate a standalone ready-to-run file.
- Optional **RemoteBee Z-probe** sequence in either mode (`G38.2`, `G10 L20`, optional `M500`).
- Editable pre/post-processing commands, validation warnings, preview, and `.g` export.
