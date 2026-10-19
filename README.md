# Dragify

Drag any image, PDF, video or song on your Mac and a ring of formats pops up. Drop the file on a format and a converted copy appears right next to the original.

Dragify is in private beta. Thanks for testing it!

## Install

1. Open **[Releases](../../releases)** and download the latest `.dmg` for your Mac:
   - **arm64** for Apple Silicon (Apple menu → About This Mac says **Apple M…**)
   - **x64** for Intel (it says **Intel**)
2. Open the `.dmg` and drag **Dragify** into **Applications**.
3. Open Dragify. macOS will say it can't verify the app, because it isn't signed with an Apple Developer account yet. Click **Done**, then go to **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to Dragify.
4. A ring icon appears in your menu bar. Drag any file to try it.

If macOS says the app is "damaged", open Terminal and run `xattr -cr /Applications/Dragify.app`, then open it again.

## Get notified about new versions

On this page, click **Watch → Custom → Releases → Apply**. GitHub will email you whenever a new version is out.

## Using it

These are for the latest version. v1.0.0 handles images and PDFs only.

| Drag a… | Convert to |
|---|---|
| Image (JPG, PNG, WEBP, GIF, TIFF, AVIF, HEIC, SVG) | PNG, JPG, WEBP, GIF, TIFF, AVIF, PDF |
| PDF | PNG, JPG, WEBP (one image per page) |
| Video (MP4, MOV, M4V, MKV, WEBM, AVI) | MP4, MOV, WEBM, MKV, GIF, MP3, WAV |
| Audio (MP3, WAV, M4A, AAC, FLAC, OGG, AIFF) | MP3, WAV, M4A, FLAC, OGG, AIFF |

- Drop in the middle of the ring to cancel. Click the middle while it's converting to stop.
- **⌃⌥D** turns Dragify on or off. You can change the shortcut in Settings.
- Menu bar icon → **Settings…** for quality (Best / Balanced / Small), keeping or trashing the original, and opening at login.

## Found a bug or have an idea?

Open an **[Issue](../../issues)**, or message Kunal, and say what you dragged, what you dropped it on, and what happened.
