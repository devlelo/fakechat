# FakeChat

FakeChat is a local-first creative tool for building fictional chat conversations and exporting them as screenshots or vertical videos.

## Product structure
- `/` — product presentation and entry page.
- `/video.html` — dedicated Video Studio.
- `/screenshot.html` — dedicated Screenshot Studio.

## Studios
- Video: progressive message reveal, vertical screen-style recording, adjustable pacing, optional background audio, and MP4/WebM depending on browser support.
- Screenshot: export a phone-screen image or a long conversation as PNG/JPG.
- Shared editor: WhatsApp, Instagram DM, SMS and iMessage visual styles; sent/received text and visual voice-message bubbles.

## UX direction
Digital Brutalism with a warm paper surface, ink-black structure, acid-lime actions, cobalt accents, strong typography and hard-edged geometry. The landing page is separate from both workspaces. Desktop editors keep the main workflow in a viewport-sized three-column workspace; mobile uses a fixed three-tab switcher for Conversation, Preview and Export.

## Run locally
Serve the repository with any static web server. PWA installation requires HTTPS or localhost.

## Privacy and browser limits
Conversation data is processed locally. Save/load uses localStorage. Video export uses MediaRecorder and canvas capture; MP4 is chosen only if supported, otherwise WebM. Voice-message bubbles are visual representations, not recorded voice clips. No backend or real messaging integration is included.

## Manifest
The project includes `manifest.txt` (Design & Development Quality Constitution, Version 4.3).