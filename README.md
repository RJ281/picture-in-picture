# Picture-in-Picture Demo

A minimal demo that lets you share your screen and open the video in Picture-in-Picture (PiP) mode.

## Features
- Uses `navigator.mediaDevices.getDisplayMedia()` to capture a screen/window/tab.
- Uses `HTMLVideoElement.requestPictureInPicture()` to enter PiP mode.

## Files
- [index.html](index.html) — page markup and UI.
- [script.js](script.js) — main JavaScript that requests the media stream and PiP.
- [style.css](style.css) — basic styles for the demo.

## Usage
1. Open `index.html` in a modern browser (preferably Chrome, Edge, or Safari).
2. Click the button to select a screen/window/tab to share.
3. After the video starts, click the button to open Picture-in-Picture.

Notes: The browser will show a prompt to allow screen capture; choose the screen/window/tab you want to share.

## Browser Support
- `getDisplayMedia()` is supported in modern Chromium-based browsers and recent versions of Firefox and Safari.
- `requestPictureInPicture()` works in Chromium-based browsers and Safari (behavior may vary).

## Development
- No build step required — this is a static demo. Just open `index.html`.
- If testing locally, some browsers may require serving files over `http(s)` for full feature support.

## License
This project is provided as-is for learning and demonstration purposes.
