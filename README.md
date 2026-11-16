A deterministic alpha-beta chess engine in Python for make.fun tiny-chess-01.

Run main.py with MAKEFUN_ENV_URL set: POST /game for FEN and legal moves, then POST /move with game ID and a UCI move; repeat until done.

main.py is the whole engine, packed into at most 4,096 bytes. engine.py is the readable source. Run python3 test_perft.py, python3 test_search.py, and python3 test_packed.py to check it.
