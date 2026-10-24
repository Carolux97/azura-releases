# Gears3-Azura releases

Downloads of the **Azura Launcher**, the launcher of [Gears3-Azura](https://github.com/Carolux97/Gears3-Azura):
an unofficial native port of Gears of War 3 (Xbox 360) to macOS on Apple Silicon and to Linux.

This repository only holds the releases. The source code, the issues and the documentation are in
[Carolux97/Gears3-Azura](https://github.com/Carolux97/Gears3-Azura).

**No game data is included.** You need your own copy of Gears of War 3 for Xbox 360, as a folder
or a disc image (`.iso`). The launcher builds the game for your computer from your own files.

## Download

Get the latest version from [Releases](https://github.com/Carolux97/gears3-azura-releases/releases/latest):

| System | File |
| --- | --- |
| macOS 13 or later, Apple Silicon (M1 or newer) | `Azura-Launcher_<version>_aarch64.dmg` |
| Linux x86-64 (glibc 2.35 or newer, as Ubuntu 22.04) | `Azura-Launcher_<version>_amd64.AppImage` |

Each release lists what it changes. A version may be published for one system first and get the
other one later.

## Install

**macOS.** Open the `.dmg` and drag Azura Launcher to Applications. The launcher is not signed with
an Apple Developer ID, so macOS blocks it the first time: open System Settings, Privacy & Security,
and choose Open Anyway next to the message about Azura Launcher.

**Linux.** Make the AppImage executable (`chmod +x Azura-Launcher_*_amd64.AppImage`) and run it.

Then, in the launcher, choose your copy of the game. The first time you press Play it builds the
game for your computer, which takes a few minutes and installs a C++ compiler if your system has
none.

## Updates

The launcher checks this repository for new versions and updates itself; each new launcher also
updates the game. The updates are signed, and the launcher only installs ones signed by the
project.

## License

The launcher and the project's own code are under the
[PolyForm Strict License 1.0.0](https://github.com/Carolux97/Gears3-Azura/blob/main/LICENSE):
you may use them for noncommercial purposes, but not change them or share them. The third-party
software they include keeps its own license (see the
[third-party notices](https://github.com/Carolux97/Gears3-Azura/blob/main/THIRD_PARTY_NOTICES.md)).

Gears of War is a trademark of Microsoft. This project is not affiliated with or endorsed by
Microsoft, Epic Games or The Coalition.
