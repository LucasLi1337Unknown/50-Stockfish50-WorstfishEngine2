# 50% Stockfish + 50% Worstfish

GitHub Pages version — no folders needed.

Put these files in the repository root:

- index.html
- stockfish-18-lite-single.js
- stockfish-18-lite-single.wasm
- README.md (optional)

The WASM file stays unchanged.

This version follows Stockfish.js 18's browser-worker convention and loads:
`stockfish-18-lite-single.js#./stockfish-18-lite-single.wasm`

The board is a fixed 8×8 CSS grid, so piece content cannot resize or distort squares.

