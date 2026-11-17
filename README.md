# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/hertzhzzz/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/hertzhzzz/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4KB Python chess engine. 0x88 board, alpha-beta search with iterative deepening to a fixed node budget, quiescence search on captures, and a procedural evaluation (material, centrality, pawn advance, bishop pair, endgame king). It plays the make.fun gauntlet through the env and never reads a clock, so every replay plays the same moves.

## Run it

```sh
python3 main.py
```

The engine reads MAKEFUN_ENV_URL and plays every game the env serves.

---

<sub>Entered on [make.fun](https://make.fun/?ref=trpdktbz&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
