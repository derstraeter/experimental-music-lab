EXPERIMENTAL MUSIC LAB - USER GUIDE
====================================

Created: experimental-music-lab.html
A brutalist experimental music making website with real-time audio-reactive visualization.

CORE FEATURES:
-------------

1. SYNTHESIZERS (8 types):
   - SINE: Pure sine wave
   - SQUARE: Square wave (harsh, retro)
   - SAW: Sawtooth wave (bright, aggressive)
   - TRIANGLE: Triangle wave (mellow)
   - NOISE: White noise generator
   - FM: Frequency modulation synthesis
   - AM: Amplitude modulation synthesis
   - SAMPLE: Play loaded audio samples

2. SYNTHESIS CONTROLS:
   - FREQUENCY: 20-2000 Hz (pitch control)
   - DETUNE: -100 to +100 cents (microtuning)
   - ATTACK: 0.001-2 seconds (sound fade-in)
   - RELEASE: 0.01-5 seconds (sound fade-out)
   - FILTER FREQ: 20-20000 Hz (lowpass filter cutoff)
   - RESONANCE: 0.1-30 (filter resonance/Q)

3. STEP SEQUENCER:
   - 16-step grid at the bottom
   - Click any step to toggle it on/off (yellow = active)
   - SEQ PLAY: Start sequence playback
   - STOP: Stop playback
   - CLEAR: Clear all active steps
   - BPM: 40-300 (tempo control)
   - Red border shows current playing step

4. SAMPLER:
   - LOAD SAMPLE: Import your own audio files
   - Samples appear in the list below
   - Click a sample to select it
   - Switch to SAMPLE synth to play it
   - Pitch follows FREQUENCY control

5. VISUALIZATIONS (7 modes):
   - WAVEFORM: Classic oscilloscope view
   - SPECTRUM: Frequency spectrum bars
   - PARTICLES: Audio-reactive particle system
   - RADIAL: Rotating radial frequency display
   - GRID: Grid of cells responding to frequency
   - FLOW: Perlin noise flow field driven by audio
   - GLITCH: Glitch effect triggered by audio amplitude

6. YOUTUBE INTEGRATION:
   - Paste any YouTube URL
   - Click LOAD VIDEO
   - Toggle SHOW/HIDE to overlay video
   - Visualization renders on top at 30% opacity
   - Make music to your favorite videos

WORKFLOW:
---------

IMMEDIATE PLAYBACK:
1. Select a synth type (SINE, SQUARE, etc.)
2. Click ► PLAY to trigger a sound
3. Adjust FREQUENCY, FILTER, ATTACK, RELEASE
4. Try different synths and parameters

SEQUENCED PATTERNS:
1. Select your synth
2. Click steps in the sequencer grid
3. Adjust BPM
4. Click ► SEQ PLAY
5. Pattern loops automatically

SAMPLE PLAYBACK:
1. Click LOAD SAMPLE
2. Select an audio file (.wav, .mp3, etc.)
3. Sample appears in list
4. Click sample name to select it
5. Click ► PLAY to trigger

VISUAL EXPLORATION:
1. Make sound with any method above
2. Switch between visualization modes
3. Each mode responds differently to audio
4. Combine with YouTube for multimedia

BRUTALIST DESIGN FEATURES:
--------------------------
- Black & white high-contrast interface
- Monospace typography (Courier New)
- 4px white borders separating sections
- Yellow (#ff0) accent color for active states
- No gradients, no decorative elements
- Functional, tool-first layout
- Hover effects: shadow displacement
- Grid-based composition

TECHNICAL DETAILS:
-----------------
- Built with Web Audio API (synthesis & analysis)
- p5.js for real-time visualization
- Single self-contained HTML file
- Works offline once loaded
- No build step required
- Responsive canvas sizing

KEYBOARD SHORTCUTS:
------------------
(None implemented - use mouse/touch)

BROWSER COMPATIBILITY:
---------------------
- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support (may require user interaction to start audio)

TIPS:
-----
- Start with low FILTER FREQ and high RESONANCE for classic synth sounds
- Use short ATTACK + RELEASE for percussive sounds
- Combine FM/AM synths with filter modulation for complex timbres
- NOISE + low FILTER FREQ = bass drum
- SQUARE + high RESONANCE = acid bass
- Load vocal samples and pitch them with FREQUENCY
- Use GLITCH visualization with heavy audio for intense effects
- YouTube overlay works best with music videos or abstract content

EXPERIMENTAL TECHNIQUES:
-----------------------
1. Create rhythmic patterns in sequencer
2. Load multiple samples
3. Switch samples mid-sequence for variation
4. Use extreme RESONANCE values (20-30) for self-oscillation
5. Rapidly switch between synth types while sequencer plays
6. Layer YouTube video under visualization
7. Use FLOW or PARTICLES viz with slow, evolving sounds

NEXT STEPS / EXTENSIONS:
-----------------------
- Add keyboard shortcuts (e.g., QWERTY keys trigger notes)
- MIDI controller support
- Record output to WAV
- Save/load patterns
- Multiple tracks in sequencer
- Effects (reverb, delay, distortion)
- LFO modulation
- More synthesis types (wavetable, granular, physical modeling)
- Preset system
- Fullscreen mode

Enjoy experimenting!
