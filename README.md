# MPC Program Builder

A browser-based Akai MPC program builder for loading, editing, chopping and exporting audio samples as MPC-compatible program packages.

## Features

- Four banks of 16 playable pads
- Audio import, drag and drop and microphone recording
- Waveform chopping and pad assignment
- Pad layers and sound-design controls
- Keyboard performance shortcuts
- XPM and legacy PGM generation
- WAV normalization and ZIP package export
- Optional Google Drive import and export

## Deployment

This repository contains a recovered production build rather than the original React source code. It can be deployed as a static site.

Deploy the repository root with no build command. The output directory is `/`.

For Google Drive authentication, add the deployed domain to:

1. Firebase Authentication authorized domains.
2. Google Cloud OAuth authorized JavaScript origins and redirect URIs.

The core audio tools and local exports do not require Google authentication.

## Structure

- `index.html`: application entry point
- `assets/index-BpMscep1.js`: compiled application bundle
- `icon.svg`: fallback application icon

## Important

Because the original component source and build configuration were not included, future development should ideally continue from the original source repository. Editing the compiled bundle directly is possible but difficult to maintain.
