# ASCII Art Video Player

Simple script to play a video in your terminal by converting frames to ASCII art using OpenCV.

## Requirements
- Python 3.8+
- opencv-python
- numpy

Install dependencies:

```powershell
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Usage

Run the script and follow prompts:

```powershell
python .\index.py
```

You will be asked for the video path, terminal width, and FPS (optional). If FPS is left blank or 0 the script will try to use the video's FPS and otherwise fall back to 30 FPS.

If `cv2` is missing the script will print the Python interpreter path and an install hint.

## Notes
- On Windows you may need `ffmpeg` installed if some video files won't open in OpenCV.
- For headless environments use `opencv-python-headless` instead of `opencv-python`.

License: MIT
