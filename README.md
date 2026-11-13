# FakeChat

FakeChat is a local-first creative utility for building fictional conversations and exporting them as screenshots or vertical screen-recording-style videos.

## Studios
- **Video Studio:** progressive message reveal, vertical 9:18 canvas recording, natural scroll progression, optional background audio, and browser-supported MP4/WebM export.
- **Screenshot Studio:** visible-screen or long-conversation PNG/JPG export.
- **Conversation editor:** WhatsApp-inspired, Instagram DM, SMS and iMessage visual presets; sent/received text and voice-message bubbles.

## Run locally
Open `index.html` in a modern browser, or serve the folder with any static web server. Install as a PWA when served over HTTPS or localhost.

## Privacy
Conversation content and saved project data stay in the browser. Local project save uses `localStorage`; no account or backend is required.

## Browser notes
Video export uses `MediaRecorder` and canvas capture. MP4 is selected only when the current browser reports support; otherwise FakeChat exports WebM. Audio recording depends on browser media capabilities.

## Design direction
Digital Brutalism: high-contrast ink and acid-lime palette, heavy display typography, hard borders, mono labels and a functional grid.

## Manifest
The project includes `manifest.txt` (Design & Development Quality Constitution, Version 4.3).