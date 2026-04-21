# Scriptboard

Scriptboard is a focused desktop app for turning a screenplay written in Fountain into a structured visual planning workflow: sequences, scenes, beats, shots, storyboard, and animatic export.[web:430][web:458]

It is designed for writers, directors, and visual storytellers who want to move from script text to shot planning without leaving a compact desktop environment.[web:430][web:461]

## What Scriptboard does

Scriptboard helps you move from a plain-text Fountain script to a visual production plan.[web:430]

With Scriptboard, you can:

- open and structure screenplay files written in Fountain.[web:430][web:456]
- organize the project into sequences, acts, and scenes based on the script structure.[web:430]
- break scenes into beats and order shots inside those beats as visual storytelling units.[web:458]
- build a storyboard from planned shots and scene structure.[web:458]
- shape timing, order, and transitions into an animatic preview.[web:458][web:461]
- export storyboard and animatic outputs for review and production handoff.[web:459][web:461]

## Workflow

A typical Scriptboard workflow looks like this:

1. Write or import a screenplay in Fountain format.[web:430][web:456]
2. Parse the script into sequences, acts, and scenes for planning.[web:430]
3. Refine scenes into beats and arrange shots inside each beat.[web:458]
4. Review the visual flow as a storyboard.[web:458]
5. Build an animatic by timing storyboard panels and transitions.[web:458][web:461]
6. Export materials for review, planning, or downstream production.[web:459][web:461]

## Core features

- **Fountain-based scripting** — start from plain-text screenplay files using the Fountain syntax.[web:430][web:456]
- **Scene planning** — structure scripts into sequences, acts, and scenes for navigation and production planning.[web:430]
- **Beat and shot organization** — break scenes into dramatic beats and arrange shots inside them to clarify intent and coverage.[web:458]
- **Storyboard workflow** — turn planned shots into a visual board for review and iteration.[web:458]
- **Animatic building** — preview pacing by sequencing storyboard images over time, with timing and transitions.[web:458][web:461]
- **Export for review** — prepare storyboard and animatic outputs for collaboration and delivery.[web:459][web:461]

## Download

Get the latest public build here:

[Open latest release](../../releases/latest)

Typical files in each release:

- Windows installer (`.msi` or `.exe`)
- macOS installer (`.dmg`)
- Checksums (`SHA256SUMS.txt`)

## Example scripts

Want to try Scriptboard immediately?

Open the [`examples/`](./examples) folder and download one of the sample `.fountain` files. You can open them in Scriptboard right away to explore script structure, scene planning, and early storyboard workflows.[web:430]

Included examples:

- [`starter-scene.fountain`](./examples/starter-scene.fountain) — the smallest possible screenplay example
- [`short-film-sample.fountain`](./examples/short-film-sample.fountain) — a short atmospheric sample with multiple scenes
- [`beat-sheet-example.fountain`](./examples/beat-sheet-example.fountain) — a lightweight planning-oriented example

## Install

1. Open the latest release.
2. Download the installer for your platform.
3. Optionally verify the file with `SHA256SUMS.txt`.
4. Install and launch Scriptboard.
5. Open one of the sample Fountain files from `examples/`.

## Feedback

Have an idea, feature request, or bug report?

[Open a new issue](../../issues/new)

[Browse existing issues](../../issues)

If you are reporting a problem, please include:

- your platform (`macOS` or `Windows`)
- the Scriptboard version
- a short description of what happened
- steps to reproduce the issue, if possible

## Suggested assets

Place these files in `assets/`:

- `icon-512.png` — square app icon
- `screenshot-editor.png` — main writing/editor view
- `screenshot-board.png` — board or storyboard view
- `social-preview.png` — optional banner image for sharing

Recommended image sizes:

- `icon-512.png`: 512×512
- `screenshot-editor.png`: around 1600×1000
- `screenshot-board.png`: around 1600×1000
- `social-preview.png`: 1280×640

## About this repository

This repository is used only for public binary distribution, screenshots, example scripts, and release notes.

The source code is maintained separately in a private repository.
