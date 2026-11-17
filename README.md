# Vidgi — free, easy video editor for Windows

Arabic / English · No account · No watermark · Works offline · Updates itself from GitHub Releases

**ڤيجي** — برنامج مونتاج مجاني وسهل لويندوز، عربي وإنگليزي، بدون علامة مائية، ويشتغل بدون إنترنت.

**[⬇ Download Vidgi for Windows](https://github.com/senesikakashi-design/vidgi/releases/latest)**

## Install

1. Download **Vidgi-Setup-x.y.z.exe** from [Releases](https://github.com/senesikakashi-design/vidgi/releases/latest) and run it.
2. Windows may show "Windows protected your PC" (the app isn't code-signed). Click **More info → Run anyway**.
3. Choose the install folder, finish, and open Vidgi from the desktop shortcut.

Projects are saved automatically in **Documents\Vidgi Projects**. Voiceovers go in **Documents\Vidgi Projects\Recordings**.

## Make a video in one minute

1. On the home screen pick a size: **9:16** (TikTok / Reels / Shorts), **16:9** (YouTube), **1:1**, **4:5** …
2. Drag your videos, photos and music anywhere into the window (or click **Import**).
3. Drag clips to the timeline — or hover a file and click **+**.
4. Cut with **S** (split at the playhead), delete with **Del**, drag edges to trim.
5. Add text (**T**), stickers, filters, effects and transitions from the left bar.
6. Click **Export** → choose 720p / 1080p / 2K / 4K → done. No watermark.

## What's in version 1

| Area | Features |
| --- | --- |
| Timeline | magnetic main track, overlay / text / audio tracks, drag, trim, split, duplicate, copy/paste, snapping, zoom, undo/redo, lock / hide / mute tracks |
| Edit | position, scale, rotation, flip, crop, opacity, blend modes, fit / fill, **keyframes** (position, scale, rotation, opacity, volume) |
| Speed | 0.1x – 10x, freeze frame |
| Look | 15 filters with intensity, 9 colour adjustments, 12 video effects, chroma key (green / blue screen) with eyedropper |
| Motion | 15 transitions, 12 in/out animations, 7 loop animations |
| Text | Arabic & English fonts (Cairo, Tajawal, Lalezar, Amiri, Inter, Bebas Neue…), 14 styles, outline, shadow, background box, gradient, typewriter |
| Audio | volume up to 500%, fades, **noise reduction**, **voice enhancer**, **voice changer** (deep, chipmunk, robot, monster, echo, hall, radio, telephone), voiceover recording, extract audio, waveforms |
| Canvas | 7 aspect ratios, blurred or colour background |
| Export | MP4 H.264 up to 4K, 24–60 fps, 3 quality levels, MP3 audio-only |
| Smart tools (1.5) | **auto captions** Arabic/English word-by-word (offline Whisper), **remove pauses**, **even out volume**, **match voice tone**, **match colours**, **lower music when talking** |
| Formats | MP4, MOV, MKV, AVI, WEBM, iPhone HEVC (auto-optimized), JPG, PNG, GIF, WEBP, MP3, WAV, M4A, AAC, OGG, FLAC… |

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| Space | Play / pause |
| S or Ctrl+B | Split |
| Del | Delete clip |
| Ctrl+Z / Ctrl+Shift+Z | Undo / redo |
| Ctrl+D | Duplicate |
| Ctrl+C / Ctrl+V | Copy / paste clip |
| ← → | One frame (Shift = one second) |
| Alt + ← → | Nudge selected clip |
| + / − or Ctrl+wheel | Zoom timeline |
| T | Add text |
| F | Full-screen preview |
| Ctrl+I | Import |
| Ctrl+S / Ctrl+E | Save / Export |
| Alt+wheel over preview | Resize selected item |

In the preview you can drag items directly: drag to move, corner dots to resize, top dot to rotate. Double-click text to type.

## Smart tools

Open the **Smart** tab on the left. Captions download a speech model once (Fast ~80 MB, Accurate ~250 MB, Best ~1 GB) into `%APPDATA%\Vidgi\models`; after that everything works offline. Select a clip first for *Match voice tone* / *Match colours* - it becomes the reference.

## Updates

Vidgi checks this repository's latest release a few seconds after it opens, downloads a newer version in the background and asks you to restart. You can also check from Settings → Updates.

## Coming next

YouTube → Reels auto-reframe with face tracking, beat sync, AI studio (talking photo, story → images → animated clips), text-to-speech voiceover, AI background removal without a green screen. Then motion tracking, reverse, templates.

