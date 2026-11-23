# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/b7hdhi9x-beep/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/b7hdhi9x-beep/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An original chess engine in Python, packed into a 4,037-byte main.py: 0x88 board, negamax alpha-beta search with a transposition table, quiescence search, late move reductions and a piece-square evaluation, playing on a fixed node budget per move (never a clock), so every game is reproducible. It talks to the make.fun env over HTTP and calls no model.

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 -P -s main.py
```

---

Entered on [make.fun](https://make.fun/?ref=gj5ptqn1&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
