# Artillery Duel — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Turn-based artillery duel vs AI. Set angle and power, read the wind, blast
craters into destructible terrain and hit the enemy turret 3 times. Free.

## Details

- Genre: Strategy / Action / Artillery (scorched-earth)
- Controls: Drag out from your turret to aim, release to fire. Keyboard: ←/→ angle, ↑/↓ power, Space to fire. M toggles sound.
- Features: Destructible terrain (shells carve craters, turrets slide down),
  random wind ±10 every turn, trajectory preview (first third only),
  2 AI difficulties (Easy / Hard with wind compensation + 15% miss chance),
  first to 3 hits wins, local win/loss/streak stats, mute toggle,
  procedural graphics & sounds, single-file HTML5 (no external assets),
  works offline once loaded.
- Tech: Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking.

## Tags
artillery, cannon, turn-based, physics, scorched-earth, strategy, casual, duel, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales to window, landscape-friendly, touch + keyboard)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png

## GameDistribution
- Upload artillery-duel-gd.zip (index.html only). SDK auto-loads on
  gamedistribution / gd.games domains.

## itch.io
- Upload zip (artillery-duel-itch.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 960×540, kind: html
- Pricing: $0 (donations optional)
