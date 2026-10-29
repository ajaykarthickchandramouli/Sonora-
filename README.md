# Sonora - A Real-Time Audio Visualizer

**See the sound, feel the flow**

## WHAT IS SONORA?
Sonora is an audio visualizer which graphically visualizes an audio file uploaded by the user.
There are bars of different heights, which determine their colour, to depict the audio being played. It has a liquid flow effect which makes it look polished and like a flowing river.

## FEATURES

1. Real-Time audio Visualization
2. Animated frequency bars with smoothening
3. Peak indicators above the bars
4. A glow in the background which reacts to bass frequencies
5. The spectrum has a colour gradience throughout
6. Audio Playback Tools
7. Local file selection
8. A playback progress indicator

## TECHNOLOGIES USED

HTML: HTML was used for basic page structuring and web implementations.
CSS: CSS was used to style the page and make it look attractive
JS: JS(JavaScript) was used to calculate the bar heights, smoothing, peak indicators, colour gradient etc.

## HOW TO USE SONORA?

**[LIVE DEMO](https://ajaykarthickchandramouli.github.io/Sonora-/)**

Use the above link to access the web page and follow the instructions for watching your audio!

1. Click "Choose Audio File" button.
2. Windows Explorer, or whatever file manager your OS has, will open as a dialog box where you have to select an audio file.
3. Click the play button(which looks like the triangle on the YouTube logo) to start the audio file.
4. You can see the visualization in an instant!
5. Use the speaker-like symbol to control the sound of the audio.

## HOW IT WORKS?
1. JS responds to "change" event of the event-listener function.
2. It loads the selected file into the audio player.
3. Uses Web Audio API to obtain frequency data.
4. Uses Canvas API to draw the calculated output.

## AI DECLARATION:

This project was developed by a human(a 14 year-old boy) with the help of some AI(ChatGPT). Only a very _few_ lines of code, only two or three of the toughest, was directly written by AI. Instead, it was only used for guidance and debugging.

## PROJECT INFORMATION:
1. Name of the creator: C. Ajay Karthick
2. Name of the project: Sonora
3. Type of project: Software
4. Web Site Link: https://ajaykarthickchandramouli.github.io/Sonora-/
5. Status: Completed and Shipped... Pending review.
