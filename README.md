# pawnstorm

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/jrdrwn/pawnstorm/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/jrdrwn/pawnstorm/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An original chess engine in 4 KB of Python: 0x88 board, negamax with alpha-beta, iterative deepening on a fixed node budget, quiescence, transposition table, null-move pruning, late-move reductions, killer and history ordering, and a material + piece-square eval. No clock, no randomness — the same position always gets the same move, so replays match move for move.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

It plays every game through the env at `MAKEFUN_ENV_URL` and exits when all games are over.

---

<sub>Entered on [make.fun](https://make.fun/?ref=7s88r2m0&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
