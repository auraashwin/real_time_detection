
# Real-Time Object Detection Web App

This is a real-time object detection web application using YOLOv8 and a webcam feed. The backend is built with Flask and Ultralytics' YOLOv8, and the frontend is a simple HTML page using JavaScript to send video frames for detection.

## Installation and Running

1. Clone the repository.
2. Navigate to the backend directory: `cd backend`
3. Install the dependencies: `pip install -r ../requirements.txt`
4. Download the YOLOv8n model: `from ultralytics import YOLO; YOLO('yolov8n')` or manually place `yolov8n.pt` in the backend folder.
5. Start the backend: `python detect_api.py`
6. Open `frontend/index.html` in your browser.
7. Allow camera access and click "Start Detection" to begin detecting objects in real time.
