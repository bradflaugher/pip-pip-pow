# Pip Pip Pow!

Endless domino logic puzzles for your phone or desktop. **Play: https://bradflaugher.github.io/pip-pip-pow/**

Drop every domino on the board so each colored zone's rule comes true. Inspired by domino-and-region logic puzzles; every level here is generated in your browser.

## Features

- **Unlimited levels** in four difficulties (Easy, Medium, Hard, Expert). Level numbers are deterministic, so "Hard 37" is the same puzzle for everyone.
- **Daily puzzle** with a streak counter; browse back through earlier days.
- **Every puzzle has exactly one solution** — a built-in solver checks each one.
- Zone rules: exact sum, less than, greater than, all equal, all different, plus **ODD / EVEN** zones.
- Hints, undo, timer, star ratings, best times, share links, sounds, haptics, light and dark themes.
- Progress is saved on your device. No accounts, no tracking, no build step.

## Controls

Drag a domino to place it. Tap it to rotate. Drag it off the board to return it to the tray.

## Development

It's a single static file. Open `index.html`, or serve the folder:

```sh
python3 -m http.server
```

MIT licensed.
