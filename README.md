# Audio Spectrum

A real-time system audio spectrum visualizer for the Cinnamon panel.

Audio Spectrum displays the audio currently playing on your system directly
in the Cinnamon panel, with multiple visualization styles and configurable
animation settings.

## Features

- Real-time system audio visualization
- 10 visualization styles:
  - Classic LED
  - 80s Car Stereo
  - Dot Matrix
  - Classic Spectrum
  - Fire
  - Neon Line
  - VU Meter
  - 1980s Digital
  - Oscilloscope
  - Classic Neon
- Adjustable number of EQ bars
- Adjustable sensitivity
- Configurable width, height and bar spacing
- Selectable 20, 25, 30 or 60 FPS
- Adjustable fall speed
- Optional peak hold
- Designed for the Cinnamon desktop panel

## Screenshots

### 80s Car Stereo

![80s Car Stereo](screenshots/80s-car-stereo.png)

### Classic LED

![Classic LED](screenshots/classic-led.png)

### 1980s Digital

![1980s Digital](screenshots/1980s-digital.png)

## Requirements

- Cinnamon desktop
- CAVA
- PulseAudio/PipeWire compatibility through CAVA's PulseAudio input

## Installation

### Easy Install

For the simplest installation, download the Easy Install package from the
Releases section.

Extract the ZIP file and run:

`Install Audio Spectrum.sh`

The installer checks for CAVA and can install it if necessary.

### Manual Installation

Copy the folder:

`audio-spectrum@crazyswede`

to:

`~/.local/share/cinnamon/applets/`

Then add **Audio Spectrum** to the Cinnamon panel through the Applets settings.

CAVA must be installed on the system.

## Configuration

Right-click the applet and open its settings to configure the visualization,
number of bars, sensitivity, dimensions, animation speed, fall speed and
peak hold.

![Audio Spectrum settings](screenshots/settings.png)

## License

Copyright (C) 2026 CrazySwede

Audio Spectrum is free software licensed under the
GNU General Public License version 3 (GPL-3.0).

See [LICENSE](LICENSE) for the full license text.
