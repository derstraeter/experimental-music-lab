# EXPERIMENTAL MUSIC LAB

A brutalist experimental music-making website with real-time audio-reactive visualization.

## 🎵 [LIVE DEMO](https://derstraeter.github.io/experimental-music-lab/)

![Experimental Music Lab Interface](https://img.shields.io/badge/status-experimental-yellow) ![License](https://img.shields.io/badge/license-MIT-blue)

## Overview

An experimental web-based music creation tool that combines synthesis, sequencing, sampling, and real-time visualization in a brutalist interface. Built with Web Audio API and p5.js.

## Features

### 🎹 8 Synthesizer Types
- **SINE** - Pure sine wave
- **SQUARE** - Square wave (harsh, retro)
- **SAW** - Sawtooth wave (bright, aggressive)
- **TRIANGLE** - Triangle wave (mellow)
- **NOISE** - White noise generator
- **FM** - Frequency modulation synthesis
- **AM** - Amplitude modulation synthesis
- **SAMPLE** - Play imported audio files

### 🎛️ Synthesis Controls
- **FREQUENCY**: 20-2000 Hz pitch control
- **DETUNE**: -100 to +100 cents microtuning
- **ATTACK**: 0.001-2 seconds fade-in
- **RELEASE**: 0.01-5 seconds fade-out
- **FILTER FREQ**: 20-20000 Hz lowpass cutoff
- **RESONANCE**: 0.1-30 filter Q

### 🎼 16-Step Sequencer
- Click steps to toggle patterns
- BPM control: 40-300
- Real-time playback
- Visual step indicator

### 🎨 7 Audio-Reactive Visualizations
- **WAVEFORM** - Oscilloscope view
- **SPECTRUM** - Frequency bars
- **PARTICLES** - Audio-driven particle system
- **RADIAL** - Rotating frequency display
- **GRID** - Audio-reactive cell grid
- **FLOW** - Perlin noise flow field
- **GLITCH** - Amplitude-triggered effects

### 📹 YouTube Integration
- Paste any YouTube URL
- Video plays underneath visualization
- Create music over your favorite videos
- Toggle show/hide overlay

### 💾 Sample Import
- Load your own audio files
- Pitch-shift samples with frequency control
- Play samples through any synth engine

## Design Philosophy

### Brutalist Approach
- **Stark black & white** interface with yellow accents
- **Courier New** monospace typography
- **4px white borders** creating aggressive grid separation
- **No gradients, no decoration** - pure function
- **Tool-first layout** optimized for making sound

This is an **Operate** surface - designed for active manipulation, not passive viewing. Controls and real-time feedback dominate.

## Quick Start

### Immediate Playback
1. Select a synth type (SINE is default)
2. Click **► PLAY**
3. Adjust parameters
4. Switch visualizations

### Pattern Sequencing
1. Click steps in the 16-step grid
2. Set BPM
3. Click **► SEQ PLAY**
4. Pattern loops automatically

### Sample Playback
1. Click **LOAD SAMPLE**
2. Select an audio file (.wav, .mp3, etc.)
3. Click sample name to select
4. Click **► PLAY** to trigger

## Technical Details

- **Audio Engine**: Web Audio API
- **Visualization**: p5.js
- **Single HTML file** - fully self-contained
- **No build step** required
- **Works offline** once loaded
- **Responsive** canvas sizing

## Browser Compatibility

- ✅ Chrome/Edge - Full support
- ✅ Firefox - Full support
- ✅ Safari - Full support (may require user interaction to start audio)

## Experimental Techniques

1. Create rhythmic patterns in sequencer
2. Load multiple samples and switch mid-sequence
3. Use extreme RESONANCE (20-30) for self-oscillation
4. Rapidly switch synth types while sequencer plays
5. Layer YouTube video under visualization
6. Combine FLOW or PARTICLES with slow, evolving sounds

## Tips

- Start with low **FILTER FREQ** and high **RESONANCE** for classic synth sounds
- Use short **ATTACK** + **RELEASE** for percussive sounds
- **NOISE** + low **FILTER FREQ** = bass drum
- **SQUARE** + high **RESONANCE** = acid bass
- Load vocal samples and pitch them with **FREQUENCY**

## Future Extensions

- Keyboard shortcuts (QWERTY triggers notes)
- MIDI controller support
- Record output to WAV
- Save/load patterns
- Multiple sequencer tracks
- Effects (reverb, delay, distortion)
- LFO modulation
- More synthesis types (wavetable, granular, physical modeling)
- Preset system
- Fullscreen mode

## License

MIT - Do whatever you want with it

## Credits

Built with:
- [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
- [p5.js](https://p5js.org/)

---

**Enjoy experimenting!** 🎵🎨
