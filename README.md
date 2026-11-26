# Sushi Cut

A relaxing slicing toy. Cut the roll, feed it forward, and let the slices stack.

## Controls

| | Phone | Desktop |
|---|---|---|
| Lower the knife | Drag down | Scroll down (or ↓) |
| Raise the knife | Drag up | Scroll up (or ↑) |
| Feed the roll | Tap | Space (or click) |
| On-screen controls | Turn the knife knob, press feed | Same |

Bring the knife back up before feeding. The feed button glows red when the roll is ready. Cutting without feeding just moves the stack over and a new one starts.

## Host it on GitHub Pages

1. Create a new public repository, for example `sushi-cut`.
2. Upload `index.html` and the `assets` folder (and this README) to the root of the repository. On github.com you can drag them all onto **Add file → Upload files** in one go.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/sushi-cut/`.

## Embed it in Framer

Add an **Embed** component, choose **URL**, and paste the GitHub Pages address. The game fills whatever size you give the embed, so any shape works. Wide frames show more of the roll, tall frames centre the action.

Keyboard controls work after the visitor clicks into the embed once. Scroll and drag work right away.

## Files

- `index.html` is the whole game (code and layout).
- `assets/` holds the art: your 1280×960 Blender renders, cropped to just the frames the game uses (about 630 KB). Keep the folder name as `assets`, next to `index.html`.
