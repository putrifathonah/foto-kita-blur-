# Peace Blur Camera

A desktop Python application that blurs the webcam feed by default and unblurs when a Peace Gesture (✌️) is detected.

## Requirements

- Python 3.12
- OpenCV
- MediaPipe
- NumPy

## Install

1. Create a virtual environment (recommended):

```powershell
python -m venv .venv
.\.venv\Scripts\activate
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

## Run

Use the included `run.bat` (Windows) or run directly:

```powershell
python main.py
```

## Controls

- `ESC`: Exit
- `L`: Toggle landmarks
- `B`: Toggle blur on/off
- `1`: Low blur
- `2`: Medium blur
- `3`: High blur
- `S`: Screenshot (saved to `outputs/`)
- `R`: Toggle recording (saved to `outputs/`)

## Notes

- If the webcam cannot be opened, confirm no other app is using it and that drivers are installed.
- MediaPipe may require specific platform wheels; if installation fails, consult MediaPipe installation docs.
