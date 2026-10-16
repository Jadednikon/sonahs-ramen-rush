# Sonah's Ramen Rush

A phone-first browser game. Sonah catches falling ramen toppings, earns robot parts, upgrades and codes Noodle-Bot, then competes in the Robot Rumble.

## Play

Open `index.html` in any browser, or publish it with GitHub Pages:

1. Push these files to a GitHub repository.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute the game is live at `https://<your-username>.github.io/<repo-name>/`.

## Files

- `index.html`: the whole game (vanilla JS, no build step)
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Tuning

All gameplay numbers (fall speeds, drop rates, upgrade costs, rival difficulty, missions) live in the `CONFIG` object near the top of the `<script>` in `index.html`. Sprites live in the `SPR` object right below it.

Progress saves in the browser's localStorage, per device.
