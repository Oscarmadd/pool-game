# Pool

A browser 8-ball pool game (UK blackball rules by default), built with HTML, JavaScript and Three.js.

Play it at **https://oscarmadd.github.io/pool-game/**

## How it's put together

Everything is in `index.html`. It has four separate parts: physics, the rules engine (`RULESETS`), rendering and input.

## Making changes

Edit `index.html` and push to `main`. GitHub Pages redeploys automatically, usually within a minute or two.

## Game modes

Pick these from the **Rules** menu:

- **UK Blackball**: the default.
- **Blackball + power-ups**: the same rules, but every visit the player at the table gets an attack power-up and the other player gets a defence one. Each has to be used before the shot is struck (press **Use** on the card, or Q). It works online and on one screen, where E is for the player who isn't at the table. The power-ups are in `POWERUPS` in `index.html`.
- **Free play**: no rules, just practice.

Online play (peer to peer, through PeerJS) is under the **Online** button.
