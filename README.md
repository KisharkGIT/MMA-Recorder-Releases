# MMA Recorder

Turn **Mega Man Arena** replays (`.rpy`) into (`.mp4`) or (`.gif`)! Generate a thumbnail and then edit the footage with the built in editor!

## Download

**[Download the latest version](../../releases/latest)** and run `MMA-Recorder-Setup-<version>.exe`.

- Windows 10 or 11, 64-bit.
  
## What you need

- **A Mega Man Arena** version that corresponds to your replay file.

## How to use it

1. Drop your (`.rpy`) replay file into the application and press render!
2. You can mess with settings such as whether to generate thumbnails, how the thumbnails look, and what part of the video to render.
3. You can select **Render Speed**, video format, resolution, and more.

**Render speed**:

| Option | Speed | Sound |
|---|---|---|
| Normal + Sound | real time (1 to 1 frame by frame) | yes |
| Quick + Sound (default) | speeds up gameplay and audio, then processes back to normal | yes |
| Fast + No Sound | speeds up gameplay, up to 8x speed | no |

The application doesn't require Mega Man Arena to be open. Once you've linked your MegaManArena.exe file, it uses MMA as an engine to process the replay.

## Finding replays

The **Replays** list can be linked to your actual MMA replays file.
You can filter by player names that have shown up in replays (via online play), by stage, mode, and even character!

**Batch renders:** click replays' pictures to select them, then **Render selected**. Tick **Auto-Edit Renders** to
have each one edited with your batch render profile and exported automatically.
1. Using the built-in editor, you can create a profile to save the way you like your videos to be edited, and auto edit batches of renders all at once.

## Thumbnails

The thumbnails tab lets you create certain thumbnail defaults that automatically generate when you render replays.
- You can even set the thumbnail to be baked into the first few frames of the video so it shows up in video previews, such as Discord!

## Profiles

In the editor, use **profiles** to save your presets.

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

**Input display:** utilizes each player's inputs to display them alongside the frame they were pressed on. Below is the breakdown of what each input means.

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

The installer lets `.rpy` files open straight to MMA Recorder. 
- If this doesn't work, right click and **Open with > Choose another app > MMA Recorder**, and press **Always**.

------------------------------------

All related content belongs to Capcom, this is a fan project.
