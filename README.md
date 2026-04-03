# Chillodoro Pomodoro Timer

A lightweight Pomodoro timer built with vanilla HTML, CSS, and JavaScript.

## Overview

Chillodoro is a focused study/work timer based on the Pomodoro method. It provides a 25-minute countdown, a circular visual timer UI, and a bell sound when the session ends.

## Features

- 25:00 countdown timer
- Start button to begin a session
- Circular progress-style visual timer layout
- Bell notification when time reaches 00:00
- Clean, minimal interface

## Tech Stack

- HTML
- CSS
- JavaScript

## Project Structure

```text
pomodoro-app/
	index.html      # app markup
	style.css       # app styles
	app.js          # timer logic
	README.md
```

## Getting Started

1. Clone or download this project.
2. Open the `pomodoro-app` folder.
3. Run the app by opening `index.html` in your browser.

You can also use a local development server (for example, VS Code Live Server) if preferred.

## Sound Setup

The app expects a bell sound file at:

```text
./sounds/bell.wav
```

To enable notification audio:

1. Create a `sounds` folder in the project root.
2. Add your sound file as `bell.wav`.

Example structure:

```text
pomodoro-app/
	sounds/
		bell.wav
```

## Customization

- Change the initial session time by editing the minute value in `index.html`.
- Replace the bell sound by swapping `sounds/bell.wav` with another `.wav` file.
- Add a wallpaper by setting `background-image` in `style.css`.

## Future Improvements

- Add pause and reset controls
- Add break sessions (short and long)
- Let users choose custom durations
- Save preferences with local storage
- Improve accessibility and keyboard support

## License

This project is open for learning and personal use.
