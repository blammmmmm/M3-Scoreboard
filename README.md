# M3 Scoreboard Overlay

Files to upload to GitHub:
- `overlay.html` -> use this in OBS as a Browser Source
- `controller.html` -> use this to control names, colors, scores, objective, and winner animations
- `assets/player-placeholder.png` -> replace with your own PNGs or use URL paths

## Firebase rules
Use this while testing:

```json
{
  "rules": {
    "overlay": {
      ".read": true,
      ".write": true
    }
  }
}
```

## GitHub Pages
1. Upload all files to a repo.
2. Turn on GitHub Pages.
3. Open `controller.html` from the Pages URL.
4. Add `overlay.html` to OBS as a Browser Source.

## Avatar paths
You can either:
- type a full image URL into the controller, or
- upload PNGs into `assets/` and reference them like `assets/marlon.png`

## Notes
- The overlay listens to the `overlay` node in Firebase Realtime Database.
- Winner animation is triggered by the controller and includes the winner face.
- Animations can be toggled on and off in the controller.
