# Egret FX

Every Egret effect in one download: the VST3 plugins and standalone apps,
for Windows, macOS and Linux, with one Windows installer.

**[Download the Egret FX Bundle](https://github.com/vox4vulpes/EgretFX/releases/latest)**

| Effect | In your browser | On its own |
|---|---|---|
| **Egret EQ** — 翡翠 · Parametric Equalizer: 48 bands, analog-matched curves, stereo/mid/side, analyzer | [open](https://vox4vulpes.github.io/EgretFX-EQ/) | [repository](https://github.com/vox4vulpes/EgretFX-EQ) |

Each effect lives in its own repository (included here as a git submodule)
with its web version, VST3 source and releases; this repository only builds
them together. Clone with `git clone --recursive`, or run
`git submodule update --init` after cloning.

## Install

**Windows:** run `1Bundle-Egret-FX-Setup-<version>.exe`. The plugins go to
`C:\Program Files\Common Files\VST3\Egret`, shared with the single-effect
installers, so having both never shows a plugin twice.

**Manual install:** copy the `.vst3` folders/files from the zip into your
plugin folder (Windows `C:\Program Files\Common Files\VST3`, macOS
`~/Library/Audio/Plug-Ins/VST3`, Linux `~/.vst3`) and rescan in your DAW.

## Releases

What changed is in [CHANGELOG.md](CHANGELOG.md). Pushing a version tag builds
every submodule with a `vst/` folder on all three platforms and publishes the
zips and the installer.

## License

[GNU AGPLv3](LICENSE). Copyright (c) 2026 vox4vulpes
