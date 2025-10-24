# Lane Detection using OpenCV (Python)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg?style=for-the-badge&logo=oColor=ffdd54)
![OpenCV](https://img.shields.io/badge/OpenCV-Image%20Processing-red.svg?style=for-the-badge&logo=oColor=ffdd54)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-Lane%20Detection-purple.svg?style=for-the-badge&logo=oColor=ffdd54)
![License MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge&logo=oColor=ffdd54)

A beginner-friendly **lane detection system** built using **OpenCV** and **NumPy**. It processes road video footage from a vehicle’s front-facing camera to detect and highlight lane boundaries in real-time.

---

## ✨ Highlights

- Real-time lane detection using classical computer vision techniques.
- Canny edge detection and Hough Line Transform.
- Region of interest masking to focus on road lanes.
- Averaging of lane lines for smoother visualization.
- Easy to extend with calibration, perspective transform, or deep learning.

---

## ⚙️ Tech Stack

- **Python 3.9+**
- **OpenCV** for image and video processing
- **NumPy** for numerical operations

---

## 🎥 Input & Output

### Input
- `test1.mp4`: A video showing a vehicle's front-facing view on the road.
- `chessboard.png`: (Optional) Used for camera calibration.

### Output
- A video stream with detected lane lines overlaid in red.
- Optionally, save the processed video to `output/result.mp4`.

---

## 🧠 How It Works

1. **Read video frame-by-frame**
2. **Apply Canny edge detection**
3. **Mask region of interest (ROI)**
4. **Detect lines using Hough Transform**
5. **Average and draw lane lines**
6. **Overlay results on original frame**

---
