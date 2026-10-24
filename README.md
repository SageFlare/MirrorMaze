# MirrorMaze

![MirrorMaze](images/MirrorMaze.png)

Version 1.0.0. Built with [ArgonSDK](https://github.com/Chiv2-Community/ArgonSDK) (Unreal Engine 4.25). Requires [MirrorKit](https://github.com/SageFlare/MirrorKit) 1.0.0 or later.

## Installation

MirrorMaze needs both PAKs:

- `MirrorMaze.pak` (this map)
- `MirrorKit.pak` (the mirrors; see the [MirrorKit releases](https://github.com/SageFlare/MirrorKit/releases))

Copy both into `Chivalry 2/TBL/Content/Paks/` and launch through the [Unchained Launcher](https://github.com/Chiv2-Community/UnchainedLauncher). 

## Mirror quality

The map uses MirrorKit's settings for mirror-heavy maps (the same as its `High` preset). You can change them for your own game with a launch option, for example `-MirrorQuality=Low` or `-MirrorQuality=Ultra`, and server hosts can set values for everyone, or an optional cap, in the map options. See [Mirror quality in the MirrorKit README](https://github.com/SageFlare/MirrorKit#mirror-quality).

## Partner mirrors

Twenty pairs of facing mirrors across the corridors are partnered: with partners on, each shows the other correctly, so the reflection inside the reflection continues the corridor like a tunnel. They are **off by default** (they cost extra). Turn them on for your own game with `-MirrorPartners=1`, or as a server host for everyone with `?MirrorPartners=1` in the map options. The `Omega` quality preset (`-MirrorQuality=Omega`) also turns them on. Comparison screenshots: [MirrorKit quality options](https://github.com/SageFlare/MirrorKit/blob/main/docs/QUALITY.md).

## License

Copyright (C) 2026 SageFlare. Original MirrorMaze work is licensed under the GNU General Public License v3.0 (GPL-3.0-only): you may use, change and share it, and anything you publish that is built on it must be released under the same license, with its source. See `LICENSE` and `THIRD_PARTY_NOTICES.md`.

Releases up to 0.3.0 were published under the MIT License and stay under it.
