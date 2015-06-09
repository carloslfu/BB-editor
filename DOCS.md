# Documentation

## Architecture

### Code structure

- *core*: All core BB-editor GUI built with the BBlocks API.
- *languages*: Definitions for all built-in supported languages.
  - *javascript*: Definitions for JavaScript.
    - *blocks*: Definitions of native blocks using the BBlocks API.
    - *workspaces*: Definitions of workspaces using the BBlocks API.
    - *generators*: Code generators (blocklify project).
    - *importers*: Code importers (blocklify project).
    - *mapper.js*: Code mapper for code import/generate handling (blocklify project).
  - *otherlangs* ...
- *extensions*: Extensions for the editor (Based on Brackets extensions architecture).
  - *example*: Extension example.
    - *blocks*.
    - *workspaces*.
    - *init.js*: Extension initializer.
- *profiles*: User defined blocks, GUI elements and preferences.
  - *default*: Default profile.
- *msg*: Mesages in some languages for translation.
- *media*: All media resources (sounds, images, etc ...).
- *libs*:
  - *utils.js*: Utilities for BB-editor (compressed).
  - *thirdparty/BBlocks*: BBlocks sources (compressed).
