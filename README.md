# 50% Stockfish + 50% Worstfish — v6

This version fixes the move system.

Repository root:
- index.html
- stockfish-18-lite-single.js
- stockfish-18-lite-single.wasm
- README.md (optional)

No folders required.

Changes in v6:
- Stockfish WASM loader kept exactly as the working v5 version.
- Chess legality is handled by chess.js instead of parsing Stockfish's `d` output.
- Click-to-move works.
- Drag-and-drop works.
- Legal moves only.
- Check/checkmate/draw handled by chess.js.
- Fixed 8×8 CSS grid: pieces cannot resize squares.
- Stockfish JS and WASM remain separate and the WASM does not need editing.
