# CVR 525 Residential Data Input Form
Mobile web app for eXp Realty - Central Virginia Regional MLS

## Market Pullback Alerts Dashboard
`dashboard.html` — a standalone buy-the-dip watchlist with editable support levels and
browser alerts that fire when a price hits its level.

- Live (delayed, best-effort) quotes from a free public source, with manual price entry as fallback.
- Per-ticker buy zones / key levels (e.g. PLTR < $107, NVDA L5 $180, MSTR L5 $250 / L4 $222,
  MU < $1,000, TSLA breakout above $420, BTC $60K magnet, SpaceX $150/$135, etc.).
- "Enable alerts" requests browser notifications; on-screen toast + sound also fire when a level is hit.
- "Auto" toggles 60-second background refresh. Edits and price targets are saved per device.

Open it directly or visit the GitHub Pages URL for this repo at `/dashboard.html`.
Educational tool, not financial advice.
