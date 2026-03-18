# PAOLA

A biosignal drawing interpreter.

Draw on the canvas with your mouse or trackpad, then press SPACE. AI analyzes the visual qualities of your gesture — speed, rhythm, pressure, curvature, spatial distribution — as a proxy for your body's current state. Your strokes transform and reactive particles emerge, each behavior shaped by the detected signal pattern.

The way you move your hand reveals something about your nervous system. PAOLA reads that trace.

## How to use

1. Open the app
2. Draw freely with your mouse or trackpad
3. Press **SPACE** to interpret your gesture
4. Watch your drawing come alive — strokes dissolve and particles emerge
5. Press **C** to clear and start over
6. Draw again — each gesture gets its own interpretation

## How it determines your signal

When you press SPACE, a screenshot of your canvas is sent to Google's Gemini API. The AI reads the visual trace of your gesture and classifies it into one of five body signal patterns based on what it sees:

- **Rest** (violet) — slow, heavy, expansive marks suggest deep stillness. Strokes drift upward slowly.
- **Drift** (teal) — flowing, looping, meditative lines suggest the edge of consciousness. Strokes morph and undulate.
- **Calm** (green) — balanced, rhythmic, evenly spaced movements suggest relaxed awareness. Strokes sway gently.
- **Focus** (orange) — sharp, quick, angular marks suggest concentrated attention. Strokes scatter and jitter.
- **Surge** (red-pink) — rapid, dense, explosive energy suggests peak intensity. Strokes burst outward from center.

Tight angular scribbles will likely trigger Focus. Slow flowing curves will likely trigger Drift. Fast chaotic marks will likely trigger Surge. The AI interprets the gestural quality, not the content of what you drew.

## Built with

- p5.js
- Google Gemini API

---

Jess Adriana Rivera, 2026
