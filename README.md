# Sixty-K Mark III — tiny-chess-01 round 3

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Avapage/makefun-tiny-chess-01-r3/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Avapage/makefun-tiny-chess-01-r3/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A byte-economical chess engine for the make.fun [tiny-chess-01](https://make.fun/bounty/tiny-chess-01) bounty:
0x88 board, negamax alpha-beta with PVS, a packed transposition table,
null-move pruning, LMR, check extensions and capture quiescence, plus a
tapered evaluation whose piece-square tables decode from symmetry-packed
strings with material baked in. It searches a fixed 110,000-node budget per
move — no clocks — so every position always gets the same move.

Bounty: https://make.fun/bounty/tiny-chess-01
