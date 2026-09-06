Draft Assistant v10.1

Upload:
- index.html
- service-worker.js

Health/status fixes:
- DST can never display individual-player IR/PUP/Q/Out badges.
- Questionable/Doubtful/Out only display when Sleeper injury_status explicitly reports that designation.
- IR/PUP/NFI/Suspended may come from explicit injury_status or explicit roster status.
- Unknown Sleeper status values no longer become a Questionable badge.
- Old cached DST health statuses are cleared automatically.
- Rankings/projections from v10 are preserved.
