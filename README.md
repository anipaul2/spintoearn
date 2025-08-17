# Spin to Earn - Farcaster Miniapp

Cross-chain wheel game with real token rewards:
- Spin on **Arbitrum** network with $SE and $0xanik tokens
- 8-segment wheel with different reward amounts
- Automatic claiming on **Base** network
- 2x bonus multiplier segment
- Leaderboard tracking total spins

## Quick start

1. Put your images:
   - `public/arbitrum.png`
   - `public/base.png`

2. Verify contract JSONs:
   - `public/arbitrumGame.json` (address + ABI)
   - `public/baseClaim.json` (address + ABI)

3. Serve locally:
   - Use any static server, e.g.:
     ```bash
     npx http-server -p 5173 .
     ```
   - Open `http://localhost:5173`

4. Deploy:
   - **Vercel** or **GitHub Pages** (static hosting)

## Notes
- Uses wagmi + Farcaster Miniapp connector (esm.sh) — no Node build needed.
- Toast popups are modern, glassmorphism style.
- Change reward images/branding in `index.html` as you like.
