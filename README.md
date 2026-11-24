# CART3R Chess Analyzer

Responsive static chess analysis website for **post-game review only**.

## Features
- Import PGN by pasting text or selecting a .pgn file
- Interactive legal chessboard and move navigation
- Stockfish WASM engine with up to three candidate moves
- Position evaluation and approximate blunder/mistake/inaccuracy review
- Responsive layout for iPad and mobile browsers

## Fair-play boundary
Use this site only to review completed games or practice positions. It does not connect to Chess.com or read live games. Do not use engine assistance during live or rated games.

## GitHub Pages deployment
1. Open repository Settings → Pages.
2. Under Build and deployment, choose Deploy from a branch.
3. Select branch main and folder /(root), then Save.
4. Wait for the published URL shown by GitHub Pages.

## Notes
The page loads chess.js 0.10.3 from cdnjs and Stockfish 16 from jsDelivr. Internet access is required. Stockfish is GPL-3.0; retain its license and attribution when redistributing. Engine review is approximate and is not an official Chess.com accuracy score.
