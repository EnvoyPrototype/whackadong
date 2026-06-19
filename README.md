# 🍆 Whack-a-D\*ck

A comedic, single-file browser take on Whack-a-Mole. Cartoon dudes pop up from
holes — whack them with the mallet cursor before they duck back down.

## Play

Open **`whack.html`** in any modern browser (Chrome, Firefox, Edge, Safari).
No install, no server, no dependencies — it's one self-contained HTML file.

- **Laptop:** move the mouse to aim the mallet, click to whack.
- **Tablet:** tap to whack. The mallet follows your finger.

## Features

- 3×3 grid of holes; figures rise with a springy bounce.
- Custom SVG mallet cursor that swings on click/tap.
- Generous hit detection — clicking anywhere over a raised figure's cell counts.
- Goofy looping chiptune background music + a satisfying "thwack" on every hit
  (all generated live via the Web Audio API — no audio files).
- Difficulty ramps every 10 seconds.
- 60-second rounds, a score rating, and an end-of-round dance party 🎉
- Mute button (🔊/🔇) in the HUD.

## Tech

Vanilla HTML/CSS/JS. Scales to any screen via `vmin` units. Web Audio API for
all sound. No build step.
