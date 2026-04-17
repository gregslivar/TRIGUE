# TRIGUE
TRIGUE is a two-device Max for Live system that turns monophonic audio input (voice, instrument) into controllable MIDI for performance and sound design.
============================================================================================================================================
<img width="708" height="423" alt="Screenshot_Trigue" src="https://github.com/user-attachments/assets/5e5785ed-ce19-4c70-ba83-adbe1e831cb0" />

The Send device (Audio Effect) analyzes incoming audio in real time, tracks pitch and amplitude, converts them to MIDI note/velocity data, and routes the result through selectable internal buses (1–5). Its interface provides quick visual feedback (waveform, meter, Hz/pitch, note name, velocity) plus direct control of dry audio monitoring level.

The Receive device (MIDI Effect) listens to the matching bus and outputs musical MIDI. It includes three operation modes: Note (monophonic note output), CC (amplitude-to-CC output), and Both (notes + CC simultaneously). Users can select CC number (1–127), choose tracking presets (Standard / Stable / Fast / Slow) to balance stability vs latency, use a momentary Sustain control, and trigger Stop (panic) to instantly clear held notes.

Together, Send + Receive provide a practical Audio-to-MIDI workflow with flexible routing and live-friendly controls.
-----------------------------------------
Quick Setup in Ableton Live
1) Add the Send device (Audio Effect)
Create or choose an Audio Track (mic, vocal, instrument, or audio clip source).
Drag the TRIGUE Send device to that track (as an Audio Effect).
In the Send device, choose a bus in Send (1–5).
2) Add the Receive device (MIDI Effect)
Create or choose a MIDI Track.
Add your target instrument after the MIDI effect (for example Operator, Wavetable, VSTI, etc.).
Drag the TRIGUE Receive device before the instrument (as a MIDI Effect).
In the Receive device, choose the same bus in Receive (1–5) used in Send.
3) Choose operation mode in Receive
Note: outputs notes only.
CC: outputs CC only.
Both: outputs notes + CC.
If using CC Mode or Both, choose the desired CC number (1–127).

------------------------
## License
This project is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
© 2026 Gregory Silva — commercial use not permitted.
