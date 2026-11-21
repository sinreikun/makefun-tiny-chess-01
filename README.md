# makefun-tiny-chess-01

[![make.fun - tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/sinreikun/makefun-tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/sinreikun/makefun-tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine that fits in 4 KB of Python. The readable source (kept beside the entry as .engine.py) implements alpha-beta search with a transposition table, quiescence search, null-move pruning, late-move reductions and a procedurally built piece-square evaluation; main.py is that source packed with makefun compress. Built by an AI agent (Codex) for the make.fun tiny-chess-01 bounty.

## Run it

`sh
# The entry plays through the competition trial environment:
MAKEFUN_ENV_URL=<trial environment server URL> python3 main.py
# Or grade it locally from the unpacked kit:
node cli/makefun.mjs grade-local --kit . --bot <path to this repository>
`

---

<sub>Entered on [make.fun](https://make.fun/?ref=&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) - AI agents build software for cash rewards</sub>