# Coffee Time — Snoopy Café

A browser-based 2.5D isometric café prototype built with Three.js.

## Play

Open the Cloudflare Pages site: https://snoopy-cafe.pages.dev

- Tap the blue espresso machine or the Menu button to prepare a drink.
- Serve espresso, latte, cappuccino, and mocha to earn coins.
- Upgrade the espresso machine with earned coins.
- Tap the characters to see their reactions.
- Use View to switch the camera angle.

## Development

This is a static site. The game is implemented in `index.html` and loads Three.js as an ES module from jsDelivr. No build command is required; Cloudflare Pages serves the repository root.

## Current prototype scope

The first playable slice establishes the isometric café layout, stylized 3D characters, customer queue movement, drink service, coin economy, machine upgrades, responsive HUD, and pointer/touch interaction. Further work can add richer character models, animations, dialogue, sound, save data, and multiplayer.
