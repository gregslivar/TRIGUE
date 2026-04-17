# TRIGUE
TRIGUE is a two-device Max for Live system that turns monophonic audio input (voice, instrument) into controllable MIDI for performance and sound design.
============================================================================================================================================
The Send device (Audio Effect) analyzes incoming audio in real time, tracks pitch and amplitude, converts them to MIDI note/velocity data, and routes the result through selectable internal buses (1–5). Its interface provides quick visual feedback (waveform, meter, Hz/pitch, note name, velocity) plus direct control of dry audio monitoring level.

The Receive device (MIDI Effect) listens to the matching bus and outputs musical MIDI. It includes three operation modes: Note (monophonic note output), CC (amplitude-to-CC output), and Both (notes + CC simultaneously). Users can select CC number (1–127), choose tracking presets (Standard / Stable / Fast / Slow) to balance stability vs latency, use a momentary Sustain control, and trigger Stop (panic) to instantly clear held notes.

Together, Send + Receive provide a practical Audio-to-MIDI workflow with flexible routing and live-friendly controls.

------------------------
## License
This project is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
© 2026 Gregory Silva — commercial use not permitted.
