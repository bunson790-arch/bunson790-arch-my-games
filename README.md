# Pocket Snake

A retro handheld-style Snake game in a single HTML file. All game logic uses plain JavaScript and Canvas, with no build step or dependencies.

## Play

Open `index.html` in a browser. To publish it publicly, enable **GitHub Pages** in repository Settings → Pages → Deploy from branch → `main` / root.

## Share a Challenge

Use **SHARE CHALLENGE** to open your device's native share menu. On devices without native sharing, the game copies a challenge with your score and current page URL.

## Controls

- **Arrow keys / WASD:** steer
- **Space / Enter:** start or pause
- **Phone:** swipe on the screen or use the on-screen D-pad
- **P / Escape:** pause

## Scoring

- Pellet: `10 × level`
- Blinking bug: `50 × level`
- Every 5 pellets increases the level and speed
- The high score is saved in local browser storage
