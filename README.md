
# ComfyUI Avatar Dance Node

This project combines audio-driven lip-syncing with beat-synchronized animations into a single cohesive node for ComfyUI.

## Features
1. **Lip-Sync Animations**: Uses Echo Mimic for phoneme-to-viseme mapping and animation.
2. **Beat-Synchronized Gestures**: Generates body and hand movements aligned with music beats.
3. **Outputs Frames**: Produces individual animation frames for combination into a video.

## Installation
1. Clone this repository.
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Place your input files in the `inputs/` folder:
   - An image (e.g., `image.jpg`).
   - An audio file (e.g., `audio.mp3`).

4. Run the script:
   ```
   python src/main.py
   ```

## Outputs
Animation frames are saved in the `outputs/` directory.

## License
MIT License
