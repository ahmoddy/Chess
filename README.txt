CHESS - files to host on GitHub Pages (or any static host)

Upload ALL FOUR of these files to the SAME folder (for GitHub: the top level of your repository):
  index.html                        the game
  stockfish-19-lite-single.js       the Stockfish 19 Lite engine (loader)
  stockfish-19-lite-single.wasm     the Stockfish 19 Lite engine (WebAssembly)
  Copying.txt                       the GNU GPL v3 licence for Stockfish - keep it with the engine files

If the two stockfish files are missing, the game still works and uses its built-in engine.
The start menu says whether Stockfish loaded.

Sources: Stockfish.js by Nathan Rugg (npm package "stockfish" 19.0.1, GPL-3.0),
https://github.com/nmrugg/stockfish.js and https://github.com/official-stockfish/Stockfish
Opening names: https://github.com/lichess-org/chess-openings (CC0).
Online play outside the Claude link uses PeerJS (MIT), loaded from the jsDelivr CDN.
