# +1 RUN!

A fast tap-to-run, launch-and-fly HTML5 game built for [CrazyGames](https://www.crazygames.com/).
Tap to build speed, run through gates, hit the ramp, then boost, dive, bounce and spin your way through 16 hand-made worlds and endless random ones past 100,000 m.

The whole game is one file: **`index.html`** (no build step, no dependencies). Open it in a browser to play.

## Play
| Action | Keyboard | Touch / mouse |
|---|---|---|
| Run (+1 speed per tap) | Space / any letter key | tap or click the screen |
| Jump (for high coins) | W / Up | JUMP button |
| Boost in the air | W / Up / Space | BOOST button or tap |
| Dive | S / Down (hold) | DIVE button (hold) |
| Spin in the air | A / D or Left / Right (hold) | spin buttons |
| Pause | P | pause button |

## Features
- Main menu, shop (upgrades, outfits, trails), skippable 5-slide tutorial, results screen
- Ribbon trails, free in-air rotation with flip bonus, bounce pads, boosts
- 16 hand-made worlds, then endless procedurally generated worlds from 100,000 m
- Procedural soundtrack that changes with game state, speed and world
- Guarded "Reset progress" (menu only: tick-box + 3 second hold)

## CrazyGames SDK v3
`init`, `loadingStart/Stop`, `gameplayStart/Stop`, `happytime`, midgame and rewarded ads (spinner while loading, audio muted only when an ad starts, no reward on error), `data` module for saves (localStorage fallback), `user` module (username/avatar, progress follows the account). The game also runs without the SDK for local testing.

To test ads locally without the SDK, open `index.html?devads` (simulated ads, local testing only).

## Upload to CrazyGames
Zip `index.html` on its own and upload that zip in the Developer Portal. Run the portal's QA tool before submitting.

## Credits and licenses
- Game code and art: this repository.
- Font: **Poppins** Bold and ExtraBold (Latin subset), embedded in `index.html`, under the SIL Open Font License 1.1. See `FONT-LICENSE-Poppins-OFL.txt`.
