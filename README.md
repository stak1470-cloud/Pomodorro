# Focus Café ☕

A Pomodoro timer and alarm clock with a cozy coffee shop aesthetic. Built as a single HTML file — no build step, no dependencies.

## Features

### 🍅 Pomodoro Timer
- Focus (25 min), Short Break (5 min), and Long Break (15 min) modes
- Animated ring progress indicator
- Play / Pause / Reset / Skip controls
- Session label input
- Dot tracker for 4-session cycles
- Stats: sessions completed, total focus time, breaks taken

### ⏰ Alarm Clock
- Live 12-hour clock with AM/PM display
- Scroll pickers for hour and minute
- AM/PM toggle
- Quick preset times (6 AM through 5 PM)
- Custom alarm naming
- Active alarm list with countdown display
- Snooze (5 min) and Stop controls
- Web Audio API beeps — no external files needed

## Usage

Just open `index.html` in any modern browser. No server required.

```bash
open index.html
# or
npx serve .
```

## Aesthetic

Built around a warm café color palette:
- Deep mocha headers and primary buttons
- Espresso and latte text tones
- Caramel progress ring accents
- Cream / foam card surfaces
- SVG plant strip illustration

## Tech

- Vanilla HTML, CSS, JavaScript
- Web Audio API for alarm beeps
- Zero dependencies
- Single file
