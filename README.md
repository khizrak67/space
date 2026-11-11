# Earth Jukebox

An interactive Earth imagery sonification prototype inspired by the 2026 NASA Space Apps Earth Information Jukebox challenge.

## Features

- Four illustrative Earth scenes and real-time Web Audio synthesis.
- Image uploads processed locally in the browser.
- Tempo, sound intensity, instrument, volume, and playback controls.
- Responsive interface, keyboard controls, and scene descriptions.

The included scenes are illustrative, not live NASA observations. Audio is an artistic interpretation of image pixels, not a scientific measurement.

## Run locally

No dependencies or build step are needed.

```sh
python3 -m http.server 8000
```

Open http://localhost:8000 and press play to enable audio.

## Deploy on Vercel

1. Import this GitHub repository into Vercel.
2. Use framework preset **Other** and leave the root directory at the repository root.
3. Leave the build command empty and set the output directory to `.`.
4. Deploy. No environment variables or Supabase connection are required.

## Files

- `index.html`: layout, styles, and explanatory content.
- `app.js`: visualization, pixel analysis, audio synthesis, and controls.
- `vercel.json`: static hosting configuration.
