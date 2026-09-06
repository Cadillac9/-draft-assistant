Draft Assistant v10

Upload to GitHub Pages root:
- index.html
- service-worker.js

Changes:
- Attempts live Sleeper DST season projection pulls using DST/DEF endpoints.
- Matches DST by NFL team abbreviation.
- K and DST no longer use fake duplicate overall ranks; they show K1/K2... and DST1/DST2...
- Keeps live Sleeper team/injury/status data.
- Adds current FantasyPros fallback season projections for top K/DST when Sleeper is missing them.
- Joshua Karty correctly falls back to 0 projection because he is currently a free agent.
- v10 label added in Best Available.
