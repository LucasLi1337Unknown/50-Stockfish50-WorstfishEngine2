# 50% Stockfish + 50% Worstfish

Static GitHub Pages version.

## Files

Keep these three files together in the repository root:

- `index.html`
- `stockfish-18-lite-single.js`
- `stockfish-18-lite-single.wasm`

The `.wasm` file does not need to be modified.

## GitHub Pages

In GitHub:

Settings → Pages → Deploy from a branch → `main` → `/ (root)`

## Engine behavior

On every engine turn:

- Stockfish mode picks MultiPV #1, the best move.
- Worstfish mode picks the lowest-ranked move returned by Stockfish.
- The default probability is 50% / 50%.

## Board layout

The board is deliberately implemented as a fixed 8×8 CSS grid with fixed equal rows and columns.
Pieces cannot resize or distort board squares.
