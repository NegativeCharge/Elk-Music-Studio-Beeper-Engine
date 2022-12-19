# Acorn Electron Music Studio 1-bit Beeper Engine Player

## Music Studio

A classic ZX Spectrum beeper engine

This engine provides two melody channels, plus percussion that may take the place of individual melody notes on channel 2. Sustain settings are ignored, any percussion entered into the Drum column will cause no note to be sounded on channel 2 for the duration of the drum effect.

- Original version by Saša Pušica
- Atari 8-Bit GTIA/PIA port by XXL
- Acorn Electron port by Negative Charge (Dec 2022)

The track currently needs to be referenced in main.s.6502

Playback speed can be altered in the track file by updating music_speed.  0x7 works for an unexpanded Electron, and 0xf for an Electron with a turbo board enabled.

Release Notes:

- v0.1 - Initial BeebAsm port for the Acorn Electron
