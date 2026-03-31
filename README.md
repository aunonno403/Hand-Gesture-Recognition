# Hand Gesture Recognition (TensorFlow + OpenCV + MediaPipe)

This project performs real-time hand gesture recognition from webcam input using MediaPipe hand landmarks and a pre-trained TensorFlow model.

## Project Structure

- `TechVidvan-hand_gesture_detection.py`: Main script for webcam capture, hand landmark extraction, and gesture prediction.
- `gesture.names`: Gesture label names used for displaying predictions.
- `mp_hand_gesture/`: Saved model directory used for inference.
- `data.pickle`: Dataset artifact used during project work.

## Environment Used

- Python: `3.10.11`
- TensorFlow: `2.15.1`
- Keras: `2.15.0`
- MediaPipe: `0.10.21`
- OpenCV (`cv2`): `4.11.0`
- NumPy: `1.26.4`

## Installation

1. Create and activate a virtual environment.

```powershell
py -3.10 -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies.

```powershell
python -m pip install --upgrade pip
pip install tensorflow==2.15.1 keras==2.15.0 mediapipe==0.10.21 opencv-python==4.11.0.86 numpy==1.26.4
```

## Run

```powershell
python TechVidvan-hand_gesture_detection.py
```

Press `q` in the output window to quit.

## Notes

- This code expects a webcam to be available.
- The model is loaded from the `mp_hand_gesture` folder.
- The script displays predicted gesture labels in real time.

## Acknowledgement

This project is based on the TechVidvan tutorial:

https://techvidvan.com/tutorials/hand-gesture-recognition-tensorflow-opencv/
