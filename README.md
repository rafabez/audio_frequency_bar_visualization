# Audio Frequency Bar Visualization

**Audio Frequency Bar Visualization** is a dynamic web-based audio visualizer that creates mesmerizing bar graphics that react to real-time audio frequencies. Built using HTML5 Canvas and Web Audio API, this project brings your music to life with smooth and responsive animations.

## Features
- **Real-time bar graphics** visualizing audio frequencies dynamically.
- Fully responsive design, adapting to any screen size.
- Simple and intuitive: click to start the audio and visualization.
- Neon-inspired aesthetic with retro terminal-style visuals.
- Customizable: Easily replace the default audio file with your own.

## Demo
[Live Demo](https://rafabeznos.com.br/fx/sound/soundviz/audio_frequency_bar_viz.html)

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/rafabez/audio_frequency_bar_visualization.git
   cd audio_frequency_bar_visualization
   ```
2. Add the audio file `Odoia.mp3` to the root directory (already included in the repository).
3. Open the `index.html` file in any modern browser.
4. Click anywhere on the screen to start the visualization.

## Adding Custom MP3 Files
You can replace the default `Odoia.mp3` file with your own custom MP3:
1. Place your desired MP3 file in the root directory of the project.
2. Rename your MP3 file to `Odoia.mp3` (or update the `src` attribute in the `<audio>` tag in the `index.html` file).
   ```html
   <audio id="audio" src="your-audio-file.mp3" preload="auto" style="display: none;"></audio>
   ```
3. Reload the `index.html` file in your browser, and the visualization will now respond to your custom audio.

## Audio Attribution
The song **Odoia.mp3** used in this project is by **Deva Garin** and is available on [SoundCloud](https://soundcloud.com/) under the **Creative Commons License**.

## How It Works
- The **Web Audio API** processes and analyzes the audio frequencies in real-time.
- The frequency data is visualized as animated bar graphics, with each bar height representing the intensity of specific frequencies.
- **HTML5 Canvas** is used for rendering the visualization smoothly and efficiently.

## Technologies
- **HTML5 Canvas**
- **CSS3**
- **JavaScript**
- **Web Audio API**

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for improvements, bug fixes, or new features.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy the beats and the visuals! 🎶📊