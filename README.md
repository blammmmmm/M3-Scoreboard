# M3 Scoreboard Refined

Files:
- `overlay.html` → OBS browser source
- `controller.html` → control panel
- `assets/player-placeholder.png` → fallback avatar

Use in OBS:
- URL: your GitHub Pages `overlay.html`
- Width: 1920
- Height: 1080
- Enable browser refresh when scene becomes active

Realtime Database path used:
- `overlay`

Notes:
- This refined version separates names from the score zone so long names do not collide with the numbers.
- Background is transparent for stream use.
- When final PNG names are provided, avatar text fields can be converted to dropdown selectors.
