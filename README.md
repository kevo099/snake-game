# snake-game

> Classic Snake — a single-file HTML5 Canvas browser game.

Eat the food, grow longer, don't hit the walls or yourself. No build step, no dependencies —
the entire game lives in [`index.html`](index.html).

## Play

Open a terminal in this repository. Opening the file directly needs only a browser;
the optional local server also needs Python 3.

```bash
# just open it
xdg-open index.html        # (or double-click the file)

# …or serve it
python3 -m http.server 8000 --bind 127.0.0.1   # then visit http://localhost:8000
```

## Controls

| Key | Action |
| --- | --- |
| Arrow keys / WASD | Move; also start, restart or resume a game |
| Space | Start, pause, resume or restart |
| Swipe on the canvas | Turn on a touch screen |
| Tap the canvas | Start, restart or resume |

Press Space to begin. Eating food increases the score and the snake's length;
hitting a wall or the snake ends the run and shows a restart prompt. Stop the
optional server with Ctrl+C when finished.

## Tech

Plain HTML + CSS + JavaScript on a `<canvas>`. That's it.

## License

MIT — see [LICENSE](LICENSE).
