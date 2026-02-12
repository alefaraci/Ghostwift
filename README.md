<h1>
<p align="center">
  <img src="https://raw.githubusercontent.com/alefaraci/Ghostwift/refs/heads/main/assets/images/Ghostwift%20Icon.png" alt="Logo" width="128">
  <br>Ghostwift
</h1>
  <p align="center">
    A lightweight macOS utility that opens your current Finder folder path directly in the <a href="https://github.com/ghostty-org/ghostty">Ghostty</a>.
    <br />
    <a href="#about">About</a>
    ·
    <a href="https://github.com/alefaraci/Ghostwift/releases/download/v1.0/Ghostwift.dmg">Download</a>
    ·
    <a href="#installation">Installation</a>
    ·
    <a href="#usage">Usage</a>
  </p>
</p>

<div align="center">
  
  <a href="https://github.com/alefaraci/Ghostwift/releases/tag/v1.0">![version](https://img.shields.io/badge/latest%20version-v1.0-brightgreen)</a>
  <a href="https://developer.apple.com/swift/">![language](https://img.shields.io/badge/language-Swift-orange)</a>
  <a href="https://github.com/alefaraci/Ghostwift/releases/download/v1.0/Ghostwift.dmg">![dmg](https://img.shields.io/badge/dmg-Ghostwift.dmg-yellow)</a>
  <a href="https://github.com/alefaraci/Ghostwift/blob/main/LICENSE">![license](https://img.shields.io/badge/license-MIT%20license-brightgreen.svg)</a>
</div>

## About
`Ghostwift` is a native [`Swift`](https://www.swift.org)/[`AppKit`](https://developer.apple.com/documentation/appkit) app that runs as a background agent (`LSUIElement`) — no dock icon, no menu bar, no UI. When launched, it queries the frontmost Finder window for its directory and opens that path in `Ghostty`. The first time you run `Ghostwift`, macOS will ask you to grant it **automation permission** to control Finder.

> [!IMPORTANT]
> `Ghostwift` requires the [`Ghostty` terminal](https://ghostty.org) to be installed on your Mac.

<img title="Ghostwift" alt="Ghostwift" src="./assets/images/Finder.png">

## Installation

1. Download [`Ghostwift.dmg`](https://github.com/alefaraci/Ghostwift/releases/download/v1.0/Ghostwift.dmg) file;
2. Move `Ghostwift.app` to `/Applications` folder;
3. Go to the `/Applications` folder. While holding the `cmd` key, drag `Ghostwift.app` to the Finder toolbar.

![Install Demo](./assets/gif/Install.gif "Install Demo")

## Usage

1. Navigate to a folder path you want to open with `Ghostty`;
2. Click on the `Ghostwift` toolbar icon.

The Finder folder path will open in `Ghostty` terminal.

Here's a quick demo:

![Application GIF](./assets/gif/Launcher.gif "Application Demo")

> [!IMPORTANT]
> If you see a message that the app cannot be opened because it is from an unidentified developer, follow these steps:
>
> 1. Open `System Preferences` > `Security & Privacy Settings`;
> 2. Look towards the bottom of the window for a message saying: *"Ghostwift was blocked from use because it is not from an identified developer."*;
> 3. Click `Open Anyway` (you may need to enter your admin password);
> 4. Click on the `Ghostwift` icon again in Finder;
> 5. A confirmation dialog will appear — click `Open` to confirm.

## Credit

App icon inspired by the [`Ghostty Logomark`](https://ghostty.org/brand). "Ghostty" and the Ghostty logo are trademarks of Mitchell Hashimoto. `Ghostwift` is not affiliated with or endorsed by Mitchell Hashimoto or the Ghostty project.

## Author

Alessio Faraci, [afaraci.com](https://afaraci.com).

## License

Licensed under the [MIT license](https://github.com/alefaraci/Ghostwift/blob/main/LICENSE).
