# Hermes builds for Screen Spawner

I publish unofficial patched Hermes builds used by [Screen Spawner](https://github.com/itkawa/screen-spawner).
This repository is not an official Hermes release channel.

Download packages and their corresponding source from [Releases](https://github.com/itkawa/screen-spawner-hermes-builds/releases).
The v0.1.1 release contains Hermes 0.5.1, revision 7de12dc2d1c009c5cc4c0e67b8c537ea9e370e99, with my EVDI fixes.
Its files were rebuilt on 17 November 2026 for Screen Spawner 0.2.0, with three more fixes:
Hermes no longer re-encodes an unchanged picture, restarts the encoder once per switch
between extended and mirrored, and no longer crashes when quit from its Web UI.

Four amd64 DEBs target Ubuntu 22.04, 24.04 (also Mint 22.x), 26.04 and Debian 13.
Each release includes SHA256SUMS and a complete corresponding-source archive,
with original licenses, dependency sources, exact revisions and rebuilding scripts.

Hermes and my build scripts are GPL-3.0-only. The shared-web Web UI component is
AGPL-3.0-only; other components retain their original licenses. All required
notices and preferred sources are included in the source archive.

Upstream: https://github.com/MrOz59/Hermes
My patch and packaging scripts: https://github.com/itkawa/screen-spawner/tree/v0.2.0/packaging

These builds may be superseded by official Hermes packages. Screen Spawner
asks before falling back to a source build if a verified package is unavailable;
building can take about an hour.
