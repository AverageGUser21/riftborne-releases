# Riftborne

An anime-style 3D action RPG: clear ranked Rift Gates, fight multi-phase bosses, collect loot, unlock cinematic Ascendant Arts, and team up with a friend in 2-player online co-op.

**Latest version: 2.4.1** · [All downloads](https://github.com/AverageGUser21/riftborne-releases/releases/latest)

## Download

| Your computer | Download |
|---|---|
| **Windows 10 / 11** (recommended) | [Riftborne-Setup-2.4.1.exe](https://github.com/AverageGUser21/riftborne-releases/releases/latest/download/Riftborne-Setup-2.4.1.exe) |
| Windows, no install (portable) | [Riftborne-2.4.1-Windows.exe](https://github.com/AverageGUser21/riftborne-releases/releases/latest/download/Riftborne-2.4.1-Windows.exe) |
| **Mac with Apple Silicon** (M1, M2, M3, M4) | [Riftborne-2.4.1-mac-AppleSilicon.zip](https://github.com/AverageGUser21/riftborne-releases/releases/latest/download/Riftborne-2.4.1-mac-AppleSilicon.zip) |
| Mac with an Intel processor | [Riftborne-2.4.1-mac-Intel.zip](https://github.com/AverageGUser21/riftborne-releases/releases/latest/download/Riftborne-2.4.1-mac-Intel.zip) |

Not sure which Mac you have? Apple menu › About This Mac: "Chip: Apple M…" means Apple Silicon, "Processor: Intel" means Intel.

## Install

### Windows
1. Run **Riftborne-Setup-2.4.1.exe**. No administrator rights needed; it installs for your user and adds a desktop and Start-menu shortcut.
2. If Windows shows **"Windows protected your PC"**, click **More info** › **Run anyway**. (The game isn't signed with a paid code-signing certificate, so Windows doesn't recognise it yet.)

### Mac (macOS 12 Monterey or newer)
1. Double-click the zip. You get **Riftborne.app** and **Install Riftborne.command**.
2. Double-click **Install Riftborne.command**. It copies the game to Applications, makes macOS trust it and opens it.
   - If macOS says it can't verify the file: open **System Settings › Privacy & Security**, scroll down and click **Open Anyway**, then run it again. (Older macOS: right-click the file › Open.)
   - Prefer Terminal? Drag Riftborne.app into Applications and run:
     `xattr -cr /Applications/Riftborne.app && codesign --force --deep --sign - /Applications/Riftborne.app`

## Updates
The game checks for updates when it starts. When one is ready you'll see **Update to v…** on the title screen (also **Settings › Check for Updates**). Click it: the game downloads the update (usually a few MB), restarts and keeps your save.

## Playing together
Walk to **City Hall** in the Hunter Plaza (or Pause › Party Lobby). One player creates a lobby and shares the code (like `RIFT-7K2Q`), the other joins with it. Windows and Mac can play together over the internet, no port forwarding needed.

## Your save
- Windows: `%APPDATA%\Riftborne\riftborne-save.json`
- Mac: `~/Library/Application Support/Riftborne/riftborne-save.json`

Moving to another computer? In the game press **F9** › Save › Export, then Import on the new computer.
