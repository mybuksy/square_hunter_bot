**Welcome to Square Hunter Bot**

I search Binance Square for you based on your custom rules.

Use this input format in ONE line:

`(time_window_hours) (repeat_interval_hours) (topN) (what to search)`

**Parameters:**
- `time_window_hours` – how far back to search: `1`, `6`, `12`, `24` (hours)
- `repeat_interval_hours` – how often to repeat:
  - `0` or `-` = run once only
  - `1`, `4`, `6`, `12`, `24` = repeat every X hours
- `topN` – how many results to return: `3`, `5`, `10`, `20`
- `what to search` – free text query (news, contests, airdrops, etc.)

**Examples:**
1. One-time search, last 12 hours, TOP 10 most popular news:
`(12) (0) (10) (most popular news)`

2. Auto search every 4 hours, last 24 hours, TOP 5 trading contests:
`(24) (4) (5) (trading contests skill no followers requirement)`

3. One-time search, last 6 hours, TOP 3 free airdrops:
`(6) (0) (3) (free airdrops no KYC)`

**Commands:**
- `/start` – show this help
- `/new` – clear previous settings and enter a NEW search line from scratch
- `/unsub` – stop all active auto searches (subscriptions)

When you send `/new`, I will forget your previous search configuration and expect a new line in the same format.
