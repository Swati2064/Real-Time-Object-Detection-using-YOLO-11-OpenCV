# 🚀 Real-Time Object Detection using YOLO 11 & OpenCV

A Computer Vision project that performs real-time object detection using **YOLO 11**, **OpenCV**, and **Python**.

The application detects multiple objects from images, videos, or webcam streams and displays bounding boxes, class labels, and confidence scores.

---

## 📌 Features

- Real-time object detection
- Image detection
- Video detection
- Webcam detection
- Bounding boxes with confidence score
- Supports multiple object classes
- Fast inference using YOLO 11 Nano

---

## 🛠️ Tech Stack

- Python
- OpenCV
- Ultralytics YOLO 11
- NumPy

---

## 📂 Project Structure

```
YOLO_Object_Detection/
│
├── img/
│   └── sample images
│
├── video/
│   └── sample videos
│
├── utils/
│   └── coco.txt
│
├── 2.yolov8_basics.py
├── 3.yolov8_n_opencv.py
├── yolo_check.py
├── yolo11n.pt
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/YOLO_Object_Detection.git
```

Move into the project

```bash
cd YOLO_Object_Detection
```

Install dependencies

```bash
pip install ultralytics opencv-python numpy
```

---

## ▶️ Run the Project

### Check YOLO Installation

```bash
python yolo_check.py
```

### Detect Objects in an Image

```bash
python 2.yolov8_basics.py
```

### Detect Objects in Video/Webcam

```bash
python 3.yolov8_n_opencv.py
```

---

## 🧠 How It Works

1. Load the pretrained **YOLO 11 Nano** model.
2. Read frames from an image, video, or webcam.
3. Perform object detection using YOLO.
4. Extract bounding boxes, class IDs, and confidence scores.
5. Draw bounding boxes and labels on each frame.
6. Display the results in real time.

---

## 📊 Model

- YOLO 11 Nano (`yolo11n.pt`)
- YOLO 8 Nano
- COCO Dataset (80 object classes)

---

## 📸 Sample Output

The model detects multiple objects and displays:

- Bounding Boxes
- Object Labels
- Confidence Scores

Example:

✔ Person  
✔ Car  
✔ Dog  
✔ Bicycle  
✔ Bus

---

## 📚 Concepts Covered

- Object Detection
- Computer Vision
- Deep Learning
- Bounding Boxes
- Confidence Scores
- OpenCV Video Processing
- YOLO Inference

---

## 🚀 Future Improvements

- Custom dataset training
- Object tracking (ByteTrack)
- Vehicle counting
- Speed estimation
- Face detection
- License plate detection
- Streamlit web interface
- Flask/FastAPI deployment

---

## 👨‍💻 Author

**Swati Jadhav**

