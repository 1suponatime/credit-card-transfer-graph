# Credit Card Transfer & Redemption Value Toolkit

Interactive visualizations for US credit card points programs — transfer partners and redemption value analysis.

## Pages

### 1. [Transfer Partners Graph](index.html)
Interactive Three.js bipartite graph showing credit card → airline transfer relationships.
- 6 card programs: Chase UR, Amex MR, Citi TYP, Capital One, Bilt, Marriott Bonvoy
- 27 airlines grouped by alliance (Star Alliance, oneworld, SkyTeam, Independent)
- Animated particle flow, hover highlighting, alliance filtering
- Pan/zoom & click-to-lock

### 2. [Redemption Value Analysis](redemption-value.html)
Chart.js dashboard comparing points redemption value (cents per point / CPP).
- Min/Max/Average CPP for flights & hotels
- Portal vs transfer partner value comparison
- Per-card detail breakdowns
- Airline miles value table with transfer sources

## Data Sources
- [US Credit Card Guide — Wings of the Points](https://uscreditcardguide.com/wings-of-the-points/) (2026.3)
- [The Points Guy](https://thepointsguy.com) valuations
- [NerdWallet](https://nerdwallet.com) & [FrequentMiler](https://frequentmiler.com) analysis

## Tech Stack
- Vanilla HTML/CSS/JS (no build step)
- [Three.js](https://threejs.org/) for the transfer graph
- [Chart.js](https://www.chartjs.org/) for redemption charts
- [Inter](https://fonts.google.com/specimen/Inter) font via Google Fonts

## License
Private repository — personal use only.
