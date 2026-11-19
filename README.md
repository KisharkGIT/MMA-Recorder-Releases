# MMA Recorder

Turn your **Mega Man Arena** replays (`.rpy`) into videos. Drop a replay in, click **Render**, and get an MP4 with
the match's sound effects and music, without opening the game, OBS, or anything else. Then trim, slice and speed up
clips in the built-in editor and export MP4, MOV or GIF.

## Download

**[Download the latest version](../../releases/latest)** and run `MMA-Recorder-Setup-<version>.exe`.

- Windows 10 or 11, 64-bit.
- Installs just for you (no admin needed), with a Start menu and desktop shortcut.
- Windows may say "Windows protected your PC / unknown publisher" the first time, because the installer isn't
  code-signed. Click **More info**, then **Run anyway**.

## What you need

- **A Mega Man Arena build with render mode.** Render mode is coming to the game in an upcoming alpha. Older builds
  can't render.
- **Replays from that same version.** Replays only play back on the exact game version they were recorded on, so
  record new matches with the build you point MMA Recorder at.

## How to use it

1. Open MMA Recorder, click **Settings**, and pick your `MegaManArena.exe` (a build with render mode). The badge at
   the top turns green.
2. Drop replays onto the window, or click **Browse**. Your replays are in
   `%LOCALAPPDATA%\MegaManArena\MMA Replays`.
3. Click **Render** for the whole match, or **Last 15s** for a quick clip of the ending.
4. Videos are saved to `Videos\MMA Recorder`. Click **Edit** on a finished render, or open **My videos**, to edit it.

**Render speed** (in Settings):

| Option | Speed | Sound |
|---|---|---|
| Exact | real time (a 2 minute match takes about 2 minutes) | yes, exact |
| Fast | as fast as your PC can go (about twice as fast) | yes |
| Fastest | as fast as your PC can go | no |

The game runs hidden and muted in the background while it renders; you can keep using your PC.

## The editor

- **Trim** by dragging a clip's edges, **slice** with `S`, **drag** clips anywhere (empty space plays black and silent).
- **Right-click** a clip for copy, cut, paste, duplicate, clip speed, properties and delete.
- **Clip speed** in the Properties panel (0.1x to 8x).
- Separate **sound effects** and **music** volume and mute.
- Export **MP4**, **MOV** or **GIF** (GIFs work best under 20 seconds).

Shortcuts: `Space` play/pause, `S` slice, `Del` delete, `Ctrl+C` / `Ctrl+X` / `Ctrl+V`, `Ctrl+Z` / `Ctrl+Y`,
arrow keys step a frame, `Ctrl+Left` / `Ctrl+Right` jump to a clip's start/end.

## Opening replays by double-clicking

The installer lets `.rpy` files open in MMA Recorder. If they still open in another program, right-click a replay,
choose **Open with > Choose another app > MMA Recorder**, and tick **Always**.

---

MMA Recorder is a fan-made tool for Mega Man Arena. Mega Man and all related content belong to Capcom.
