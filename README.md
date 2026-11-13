# tiny-chess-01

A small chess engine in a single Python file (`main.py`, stdlib only).

- 0x88-free 120-square mailbox board, pseudo-legal move generation
  (castling, en passant, queen promotion)
- Negamax alpha-beta search with quiescence over captures,
  MVV-LVA ordering, iterative deepening on a fixed node budget
- Evaluation: material + piece-square tables
- Deterministic: fixed node count per move, no clock, no randomness

Entry for the make.fun bounty "Build the strongest chess engine in
4 KB of Python" (tiny-chess-01). Run by the harness as
`python3 -P -s main.py` with `MAKEFUN_ENV_URL` set.
