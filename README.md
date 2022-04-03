# Moog Claravox firmware mirror
This repository contains a copy of Moog's Claravox theremin firmware.

Claravox-\*.syx © Moog Music Inc.

## Upstream changelog
### 1.0.2
- Properly use MSB and LSB for interpreting RPN 0 Pitch Bend Sensitivity.
- Express instrument MIDI input and output channels as absolute numbers instead
  of normalized across the full 14-bit resolution of NRPN 1026 and 1027.
- Pitch Antenna Mod to Wavescan Freq parameter now properly clamps to 0.1Hz and 200Hz instead of rolling over.
- Fixed MIDI Pitch Mode now uses the full 0-16383 range of bend values and
  sends RPN 0 Pitch Bend Sensitivity before any note on event.

### 1.0.1
- Initial Release

![Claravox theremin](https://thumbs.static-thomann.de/thumb/padthumb600x600/pics/bdb/505911/15658910_800.jpg)

