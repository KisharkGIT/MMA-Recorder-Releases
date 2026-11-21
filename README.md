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
- From 0.5.0 on, the app updates itself: when a new version is out, a pop-up offers to download and install it
  (or use **Settings > Check for updates**). On 0.4.0 or older, download the new version here once.

## What you need

- **A Mega Man Arena build with render mode.** Render mode is coming to the game in an upcoming alpha. Older builds
  can't render.
- **Replays from that same version.** Replays only play back on the exact game version they were recorded on, so
  record new matches with the build you point MMA Recorder at.

## How to use it

1. Open MMA Recorder. **Settings** opens: drop your `MegaManArena.exe` (a build with render mode) on the box, or
   click **Browse**. The badge at the top turns green.
2. The **Replays** screen lists your replays from `%LOCALAPPDATA%\MegaManArena\MMA Replays`. You can also drop
   replays onto the window, or click **Browse**.
3. Click **Render** for the whole match, or **Last 15s** for a quick clip of the ending.
4. Videos are saved to `Videos\MMA Recorder`. Click **Edit** on a finished render, or open **My videos**, to edit it.

**Render speed** (in Settings):

| Option | Speed | Sound |
|---|---|---|
| Normal + Sound | real time (a 2 minute match takes about 2 minutes) | yes, exact |
| Quick + Sound (default) | as fast as your PC can go (about twice as fast) | yes |
| Fast + No Sound | as fast as your PC can go | no |

The game runs hidden and muted in the background while it renders; you can keep using your PC. Windows tells you
when your renders are done (you can turn that off in Settings).

## Finding replays

The **Replays** screen lists every replay in your MMA Replays folder (or any folder you pick with **Change**).
Search by player, character, stage or file name; filter by up to 4 characters, up to 4 players, stage or mode; sort
by date or length; and star your favorites. **Only Show Replays for this Version** hides replays your game can't
render (their version tag is red). Click **Render**, **Last 15s** or **Add to queue** right from the list.

**Batch renders:** click replays' pictures to select them, then **Render selected**. Tick **Auto-Edit Renders** to
have each one edited with your batch render profile (input display, format, thumbnail...) and exported automatically.

## Thumbnails

The **Thumbnails** screen sets the look of a VS-style thumbnail for 1v1, multiplayer and Boss Mode matches. Every
video gets its own, with its players' taunts in their colors. In Settings (Thumbnail tab) choose whether to save it
as a `.png` next to the video and/or bake it into the start of the video.

## Profiles

In the editor, **Profiles** saves your editor settings (input display, sound levels) and render options. Pick
**My editing profile** to open new videos with it, and a **Batch render profile** for Auto-Edit Renders.

## The editor

- **Trim** by dragging a clip's edges, **slice** with `S`, **drag** clips anywhere (empty space plays black and silent).
- **Right-click** a clip for copy, cut, paste, duplicate, clip speed, properties and delete.
- **Clip speed** in the Properties panel (0.1x to 8x).
- Separate **sound effects** and **music** volume and mute.
- Click **empty space** on the timeline and press `Del` to close the gap.
- Right-click a clip for **Auto-trim** (cuts the READY intro and the dead time after the match).
- Add the **thumbnail** at the start or anywhere on the timeline.
- Export **MP4**, **MOV** or **GIF** (GIFs work best under 20 seconds). When it's done, copy the video and paste it
  into Discord with `Ctrl+V`, or drag it out of the pop-up.

**Input display:** show each player's button presses in the video, fighting-game style: the direction, the buttons
and how many frames they were held, newest on top. Turn it on per player under **Input display** in the editor.
Pick a corner, or **Custom** to drag it anywhere on the picture. **Properties** sets its size (1x to 3x), the
background opacity and every button's color.

- J = Jump
- S = Shoot
- 1 = Special 1
- 2 = Special 2
- SL = Slide
- IT = Item
- SE = Select

Shortcuts: `Space` play/pause, `S` slice, `Del` delete, `Ctrl+C` / `Ctrl+X` / `Ctrl+V`, `Ctrl+Z` / `Ctrl+Y`,
arrow keys or `,` / `.` step a frame, `Ctrl+Left` / `Ctrl+Right` jump to a clip's start/end.

## Opening replays by double-clicking

The installer lets `.rpy` files open in MMA Recorder. If they still open in another program, right-click a replay,
choose **Open with > Choose another app > MMA Recorder**, and tick **Always**.

---

MMA Recorder is a fan-made tool for Mega Man Arena. Mega Man and all related content belong to Capcom.
