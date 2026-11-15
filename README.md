# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/h05meigames2/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/h05meigames2/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python, written from scratch for the
[make.fun](https://make.fun/bounty/tiny-chess-01) tiny-chess-01 bounty:
0x88 board, negamax with alpha-beta, iterative deepening, quiescence
search, transposition table, MVV-LVA + killer move ordering and
piece-square evaluation. Deterministic: a fixed node budget per move,
no clock, no randomness.

Run it with the trial env at `MAKEFUN_ENV_URL`:

    MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
