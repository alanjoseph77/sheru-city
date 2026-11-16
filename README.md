# Sherubhai – King of the City

Open-world 3D browser game built with three.js. Everything (game, character model, music) is in a single `index.html`.

## Hosting on Cloudflare Pages

1. Cloudflare dashboard → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
2. Pick this repository.
3. Build settings: Framework preset **None**, build command **empty**, build output directory **`/`**.
4. **Save and Deploy**. The game is live at `https://<project>.pages.dev`.

Every push to `main` redeploys automatically.

## Phones

- Android (Chrome / Samsung Internet / Edge): tapping Play goes fullscreen and locks to landscape. "Add to Home screen" opens it straight in landscape.
- iPhone: Safari can't lock orientation, so players are asked to turn the phone sideways, or can tap "Play sideways anyway".

three.js is loaded from cdn.jsdelivr.net, so an internet connection is needed.
