# Retro Bowl College Career Mode

This project includes the compiled Retro Bowl College browser game and a high-school career integrated into its native GameMaker UI. Start a new Player career to create a character, choose Hampshire High or Lavticit High, select QB or RB, and choose a starting rating from 1 to 3 stars. Play a six-game high-school season using the regular on-field gameplay, custom school identities and uniforms, and a Player-specific season screen. After the season, choose between two college offers; the selected offer determines the reduced college-entry rating and initial college attributes. The Coach path remains unchanged.

The career flow uses the game's native UI and in-canvas message system; no browser overlay or separate career storage is used. Player mode skips the introductory tutorial and displays high-school opponents and schedule details instead of the college league during the season. In an RB career, offensive plays hand the ball to the selected player so the normal arrow-key running controls work.

Have Fun!

## Launch

Extract the ZIP, open a terminal in the extracted folder, and run:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/` in your browser. Opening `index.html` directly may leave the game blank because the game loads its assets over HTTP.

## Testing the Player career

Start a new save, choose Player, create your player, choose a high school, position, and starting rating, then play six native field matches. The post-season screen presents college offers and the college-entry rating.
