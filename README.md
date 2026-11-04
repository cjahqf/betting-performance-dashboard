# Betting Performance Dashboard

Public snapshot dashboard for Pikkit, Juice Reel, and Bovada review records.

## Deployment
Host as a Render Static Site with build command `echo Ready` and publish directory `.`.

## Data handling
- Bet-level selections, stakes, profit/loss, and source names are public.
- Original transactions, account identifiers, exports, SQLite databases, credentials and API keys must not be committed.
- Bovada reconciliation candidates are excluded from settled profit/ROI.
- This is a static snapshot, not automatic account syncing.
