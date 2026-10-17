# Usage Guide — ping-zapper

## Main Window

The dashboard shows live status and the primary action. *(Screenshot:
`assets/screenshots/main.png`)*

## Core Workflow

1. Launch ping-zapper
2. Configure options in the Settings tab
3. Use the main action (or global hotkey)
4. Status icon turns green when active

## Global Hotkeys (defaults, editable)

| Hotkey | Action |
|---|---|
| `Ctrl + Alt + X` | Toggle ping-zapper on/off |
| `Ctrl + Alt + S` | Open settings |
| `Shift + F9` | Panic key — restore defaults instantly |

## Profiles

Create per-scenario profiles in the Profiles tab, save to
`%APPDATA%\ping-zapper\profiles\`, share as files. Community presets live in
[`data/profiles/`](../data/profiles/).

## CLI Mode

```powershell
ping-zapper.exe --help        # all commands
ping-zapper.exe --version
```

All GUI actions are available as CLI flags for scripting and automation.
