🔥 Real-Time Fire Detection (YOLOv8 + Streamlit)

This project uses a YOLOv8 model to detect fire in real time through your system’s webcam. It runs on Streamlit, gives live visual feedback, and highlights fire regions in each frame. You also get a simple progress bar that shifts instantly when fire is detected, making it easy to monitor activity.

⭐ What this app does

Opens your webcam and processes the video feed frame by frame

Uses a trained YOLO model (best.pt) to locate fire

Draws bounding boxes around detected fire

Shows a clean progress indicator for detection status

Lets you start and stop detection with one click

Runs entirely on your local machine

🧠 How it works

The Streamlit frontend loads the YOLO model once and handles live video streaming with OpenCV. Each frame is sent to the model and the annotated output is displayed back in the browser. If class 0 appears in the prediction results, the app marks it as fire and updates the UI instantly.
