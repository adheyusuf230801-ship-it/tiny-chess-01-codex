[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/adheyusuf230801-ship-it/tiny-chess-01-codex/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/adheyusuf230801-ship-it/tiny-chess-01-codex/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic alpha-beta chess engine in Python for make.fun tiny-chess-01.

Run main.py with MAKEFUN_ENV_URL set: POST /game for FEN and legal moves, then POST /move with game ID and a UCI move; repeat until done.

main.py is the whole engine, packed into at most 4,096 bytes. engine.py is the readable source. Run python3 test_perft.py, python3 test_search.py, and python3 test_packed.py to check it.
