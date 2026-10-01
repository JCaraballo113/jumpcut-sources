# Jumpcut source code for its open-source components

Jumpcut, by John Caraballo, includes programs licensed under the GNU General Public License, version 2 or later: FFmpeg (ffmpeg and ffprobe), built with x264 and x265, plus libvpx and Opus (BSD-3-Clause), and Remotion's renderer, which contains its own FFmpeg build.

Each [release](https://github.com/JCaraballo113/jumpcut-sources/releases) here matches a Jumpcut version and platform. It carries the complete corresponding source for these programs:

- the unchanged source tarball of each component, as published by its authors, with `SHA256SUMS`;
- the scripts used to build them;
- the exact configure line (`CONFIGURE.txt`).

Each release stays available for at least three years after that version was last distributed.

- **Remotion's FFmpeg:** its source and build scripts are published by Remotion at <https://github.com/remotion-dev/rust-ffmpeg-splitter>.
- **Chromium's LGPL components** (in Electron and in the video renderer): available from their upstream tags, and listed in `THIRD_PARTY_NOTICES.txt` in the app.

## Requests and licence questions

[Open an issue](https://github.com/JCaraballo113/jumpcut-sources/issues). For three years after a version was last distributed, anyone who received it may also ask here for the source on a physical medium. It costs no more than the cost of physically sending it.
