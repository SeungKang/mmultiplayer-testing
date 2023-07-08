# Mirror's Edge Multiplayer Mod

## Setup

1. Download the latest launcher from <a href="https://github.com/Toyro98/mmultiplayer/releases">here</a>.
2. Run the launcher either before Mirror's Edge or when Mirror's Edge is running.
3. Press `Insert` to view the in-game menu where you can adjust settings as you please.

## Features

- Full multiplayer client with custom names, rooms, and characters
- General purpose engine and world menus
- Trainer
    - Save/load state
    - God mode
    - Fly mode
    - KG tool
    - Beamer tool
    - Strang tool
- Dolly camera
    - Supports player recordings
    
## Addons

- Tag (Work In Progress)

## How to create a release
1. Go to GitHub releases
2. Create a new release
3. Create new tag with version #
4. Wait for CI to finish

## Building from source
To build dll and Launcher:
- `./build.sh` - Requires DirectX June 2010, MSBuild, Visual Studio 2019 and Git Bash.

To build the installer:
- `VERSION=X.X.X ./package.sh` - Expects a version to be provided by setting an environment variable. Saves and builds artifacts to `build/`. Requires Inno Setup and Git Bash.
