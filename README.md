# Tiny Motion Capture & Playback

A minimal, dependency-free JavaScript tool for capturing and replaying pointer-based motion (mouse, touch, or pen). Designed for creative coding, animation prototyping, UI testing, or just fun gesture experiments.  

Try Here: [nyseer1.github.io/Record-Motion/](https://nyseer1.github.io/Record-Motion/)

## Features

- **Universal input:** Records mouse, touch, or pen via the Pointer Events API
- **Live recording:** Real-time capture of pointer movement
- **Playback:** Replays motion frame-by-frame
- **Save:** Exports raw motion data to a JSON file
- **Load:** Drag-and-drop a saved file to replay it
- **Responsive:** Runs on desktop and mobile
- **Lightweight:** Pure HTML/CSS/JS, no dependencies

## How to Use

1. **Draw:** Press and hold on the canvas to begin recording.
2. **Release:** Stop recording and start playback automatically.
3. **Save:** Click “Save Motion” to download a `.json` file.
4. **Load:** Drop a saved file onto the drop zone to replay it.

## File Format

Recorded motions are stored as an array of `{ x, y }` objects:

```json
[
  { "x": 150, "y": 300 },
  { "x": 152, "y": 302 },
  ...
]
```

## Live demo:
[nyseer1.github.io/Record-Motion/](https://nyseer1.github.io/Record-Motion/)

## Resources

These are the key Web APIs used in this project, which you might find helpful:

- [Pointer Events – MDN](https://developer.mozilla.org/en-US/docs/Web/API/Pointer_events)
- [requestAnimationFrame – MDN](https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame)
- [FileReader – MDN](https://developer.mozilla.org/en-US/docs/Web/API/FileReader)
- [Blob – MDN](https://developer.mozilla.org/en-US/docs/Web/API/Blob)
- [Drag and Drop API – MDN](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API)