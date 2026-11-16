# Sherubhai – King of the City

**Play:** https://sheru-city.littlegarage.workers.dev/

Open-world 3D browser game built with three.js. Everything (game, character model, music) is in a single `index.html`.

## Hosting on Cloudflare

The site lives in `public/`; `wrangler.jsonc` tells Cloudflare to serve it as static assets.

**Workers (Connect to Git):** pick this repo, leave the build command empty, keep the deploy command `npx wrangler deploy`, and press **Deploy**. Live at `https://sheru-city.<your-subdomain>.workers.dev`.

**Pages (alternative):** Framework preset **None**, build command empty, build output directory **`public`**.

Every push to `main` redeploys automatically.

## PC controls

| Key | Action |
|---|---|
| W A S D / arrows | Move, drive |
| Shift | Walk (on foot), throttle up (jet) |
| Mouse drag / wheel | Look around / zoom |
| F or E | Get in / out of vehicles, use doors, beds, desks |
| Space | Jump (helicopter: climb) |
| G | Draw / holster gun |
| Left click | Fire (gun out) |
| Q / B / V | Wave / Dance / Call car |
| H | Horn |
| C | Helicopter: descend |
| Ctrl | Jet: throttle down |
| 1 / 2 / 3 | Auction: +10% / double / walk away |
| Esc | Skip the flight animation |
| K | Show / hide controls |

## Phones

- Android (Chrome / Samsung Internet / Edge): tapping Play goes fullscreen and locks to landscape. "Add to Home screen" opens it straight in landscape.
- iPhone: Safari can't lock orientation, so players are asked to turn the phone sideways, or can tap "Play sideways anyway".

three.js is loaded from cdn.jsdelivr.net, so an internet connection is needed.
