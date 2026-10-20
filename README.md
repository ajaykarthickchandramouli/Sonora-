# Sonora — A Real-Time Audio Visualizer

**See the sound. Feel the flow.**

Sonora is a browser-based audio visualizer that transforms your audio into a dynamic, glowing spectrum. Built with HTML, CSS, JavaScript, the Canvas API, and the Web Audio API, it combines real-time audio analysis with a sleek, dark interface.

## ✨ Features

* **Real-Time Audio Visualization** — Watch frequency bars respond dynamically to the audio being played.
* **Smooth Animations** — Smoothed bar transitions create a fluid visual experience.
* **Peak Indicators** — Track the highest recent level reached by each frequency bar.
* **Bass-Reactive Background** — A glowing background responds to low-frequency audio energy.
* **Dynamic Colour Gradient** — A violet-to-blue-to-cyan palette gives the spectrum its distinctive appearance.
* **Audio Playback Controls** — Play, pause, seek through, and adjust the volume of your audio using the built-in player.
* **Local Audio Upload** — Select an audio file from your device and visualize it directly in your browser.
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

### Run Locally

1. Download or clone this repository.
2. Ensure `index.html` and `Sonora Logo.png` are in the same directory.
3. Open `index.html` in a modern web browser.
4. Select an audio file using **Choose Audio File**.
5. Press play and watch Sonora bring your audio to life!

For the most reliable experience, run the project through a local development server if your browser encounters any restrictions when opening the file directly.

## 🎧 How It Works

Sonora uses the Web Audio API to analyse the audio playing in its built-in player.

The analyser produces frequency data that JavaScript processes frame by frame. These values determine the heights of the spectrum bars, while smoothing creates more fluid transitions.

Sonora also tracks the recent peaks of individual bars and calculates a low-frequency intensity value to control the background glow. The Canvas API renders these elements continuously, creating a visualization that responds to the audio in real time.

## 📁 Project Structure

```text
sonora/
├── index.html       # Application structure, styles, and JavaScript
├── Sonora Logo.png  # Application logo and favicon image
└── README.md        # Project documentation
```

## 🌐 Live Demo

**Coming soon!** Sonora will be available through GitHub Pages once deployment is complete.

## 🔮 Future Possibilities

Potential future improvements include:

* Additional visualization modes.
* Audio section looping and bookmarks.
* Screenshot and video export.
* More customization options for the visualizer.

These are ideas for future development, not features currently implemented.

## 👨‍💻 Project Information

Sonora is a hands-on web development project exploring real-time audio analysis, interactive graphics, and browser-based media experiences.

**Project:** Sonora — A Real-Time Audio Visualizer
**Tagline:** See the sound. Feel the flow.
**Status:** Active development

---

*Turn sound into something you can see.*
