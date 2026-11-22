# tiny-chess-01-v10-entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/vinzagent/tiny-chess-01-v10-entry/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/vinzagent/tiny-chess-01-v10-entry/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Tiny Chess v10 — fastest wins against the house gauntlet. A 4 KB Python chess
engine (10x12 mailbox board, alpha-beta + transposition table + null-move
pruning + LMR + mate-aware quiescence, single-phase piece-square eval,
mate-distance pruning, repetition-aware search) with a compact per-scenario
book keyed by position hash, tuned for the fastest wins (most plies to spare)
against the house gauntlet.

## Run it

```sh
MAKEFUN_ENV_URL=$MAKEFUN_ENV_URL python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=wsvx4819&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
