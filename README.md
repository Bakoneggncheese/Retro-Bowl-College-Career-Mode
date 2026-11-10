# Retro Bowl College Career Mode

This project includes the compiled Retro Bowl College browser game and a high-school season integrated into its native GameMaker UI. On a new Player career, use the native player setup screen to enter your name and choose your appearance, then play six high-school games. Each game has three drives; choose pass or run on every play, convert first downs, score touchdowns, and earn a recruiting grade. At the end, choose between two college offers to begin your native QB career at that school. The Coach path and existing saves remain in the original game.

The season runs through the game's in-canvas message system; no browser overlay or separate career storage is used. Choose **Existing Saves** before starting the season to return to the game's save screen without modifying a save.

Have Fun!

## Launch

Extract the ZIP, open a terminal in the extracted folder, and run:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/` in your browser. Opening `index.html` directly may leave the game blank because the game loads its assets over HTTP.

## Testing the career prelude

Start a new save, choose Player, create your player, then press Continue to begin the high-school season. Existing saves bypass the first-run season.
