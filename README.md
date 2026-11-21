# Ether Cymatic Studio

A single-file cymatics synthesizer and visualizer: sound, sacred geometry, sand and water. It's one `index.html` with no build step, written in vanilla JavaScript using Canvas, WebGL, the Web Audio API and the Web MIDI API.

## Run it

Open `index.html` in Chrome or Edge. For microphone input, serve the folder from localhost or HTTPS:

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

Web MIDI needs Chrome or Edge; Safari doesn't support it.

## Modes

1. **Chladni Plate:** liquid sand gathers on the nodal lines of square or circular (Bessel) plate eigenmodes, with hidden magnets under the plate.
2. **Magnetic Resonance:** a water dish driven by hidden floating magnets. Notes and audio strike the magnets, and only the water shows it.
3. **Sacred 3D Solids:** Metatron's Cube, a 3D Flower of Life and the five Platonic solids, with shaded faces, circles on lines and translucent bubbles.
4. **Hybrid Resonance:** the geometry lattice layered over live Chladni sand.

## Features

- **Synth:** sine, triangle or low-passed saw; a 20–1000 Hz fundamental with solfeggio presets; intervals (octave, fifth, fourth, overtones).
- **Audio in:** MP3/WAV playback with seek, mic or line-in analysis (never sent to the speakers), and band meters (RMS, bass, mid, treble) plus dominant pitch.
- **MIDI:** device list, notes with velocity and pitch bend, MIDI Learn for any control (saved in the browser).
- **Keys:** the computer keyboard, number pad or on-screen piano plays notes.
- **3D view:** tilt, turn or flip the plate and dish. Sand and water rise and fall as a real height map, and you can view from below.
- **Look panels:** per-mode scale, speed, density, colour wheels, gloss, glow, trails and magnetic strength.
- **Color Grade:** Resolve-style Lift, Gamma, Gain and Offset wheels, contrast and pivot, saturation, temperature and tint, hue, vignette and grain (GPU).
- **Capture:** PNG screenshots and video recording with sound (MP4 or WebM).
- **Floating control panel:** dock it left, right, top or bottom, or float and resize it.

## Shortcuts

| Key | Action |
|---|---|
| `1`–`4` | Switch mode |
| `Space` | Synth on/off |
| `` ` `` | On-screen keys on/off |
| `R` / `Shift+R` | Re-scatter / Record |
| `P` | Screenshot |
| `L` / `Esc` | MIDI Learn on/off |
| `H` | Readout panel (mobile) |
