# Sonora — A Real-Time Audio Visualizer

**See the sound. Feel the flow.**

Sonora is a browser-based audio visualizer that transforms audio into a dynamic, animated spectrum. Built using HTML, CSS, JavaScript, the Canvas API, and the Web Audio API, it combines real-time audio analysis with a sleek, dark interface and a distinctive violet-to-blue-to-cyan colour palette.

## 🌐 Live Demo

**[Launch Sonora](https://ajaykarthickchandramouli.github.io/Sonora-/)**

Upload an audio file, press play, and watch your sound come to life through an animated frequency spectrum.

## ✨ Features

* **Real-Time Audio Visualization** — Frequency bars respond dynamically to the audio being played.
* **Smooth Animations** — Smoothed bar transitions create a fluid visual experience.
* **Peak Indicators** — Markers track the recent peak level reached by each frequency bar.
* **Bass-Reactive Background** — A glowing background responds to low-frequency audio energy.
* **Dynamic Colour Gradient** — A violet-to-blue-to-cyan palette gives the spectrum its distinctive appearance.
* **Audio Playback Controls** — Play, pause, seek through, and adjust the volume of audio using the built-in player.
* **Local Audio Upload** — Select an audio file from your device and visualize it in the browser.
* **Playback Progress Indicator** — Follow the current playback position through the visualization.

## 🛠️ Built With

| Technology    | Purpose                                   |
| ------------- | ----------------------------------------- |
| HTML5         | Page structure and audio controls         |
| CSS3          | Layout, styling, and visual design        |
| JavaScript    | Animation and audio-processing logic      |
| Canvas API    | Rendering the spectrum and visual effects |
| Web Audio API | Analysing audio frequencies in real time  |

## 🚀 Getting Started

### Use the Live Demo

1. Open the [Sonora web application](https://ajaykarthickchandramouli.github.io/Sonora-/).
2. Click **Choose Audio File**.
3. Select an audio file from your device.
4. Press play using the built-in audio controls.
5. Enjoy the real-time visualization!

### Run Locally

1. Clone or download this repository.
2. Ensure `index.html` and `Sonora Logo.png` are in the same directory.
3. Open `index.html` in a modern web browser.
4. Upload an audio file and start playback.

For the most reliable experience, use a local development server if your browser encounters restrictions when opening the HTML file directly.

## 🎧 How It Works

Sonora uses the Web Audio API to analyse audio playing through its built-in player.

The analyser produces frequency data that JavaScript processes continuously. These values determine the heights of the spectrum bars, while smoothing creates more fluid transitions.

The visualizer also tracks the recent peaks of individual bars and calculates low-frequency intensity to control the background glow. The Canvas API renders these elements continuously, creating an animated visualization that responds to the audio.

A progress indicator reflects the current playback position relative to the audio's duration.

## 📁 Project Structure

```text
Sonora-/
├── index.html       # Application structure, styles, and JavaScript
├── Sonora Logo.png  # Application logo and favicon
└── README.md        # Project documentation
```

## 🔮 Future Possibilities

Potential future improvements include:

* Additional visualization modes, such as waveform and circular spectrum views.
* Audio section looping and timestamp bookmarks.
* Screenshot and video export.
* Customization options for visualization behaviour.
* Support for additional audio sources.

These are ideas for future development, not features currently implemented.

## 👨‍💻 Project Information

**Project:** Sonora — A Real-Time Audio Visualizer
**Tagline:** See the sound. Feel the flow.
**Status:** Active development
**Live Demo:** [Open Sonora](https://ajaykarthickchandramouli.github.io/Sonora-/)

Sonora is a hands-on web development project exploring real-time audio analysis, interactive graphics, and browser-based media experiences.

---

*Turn sound into something you can see.*
