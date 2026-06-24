# face recogniasation

# Face Detection using OpenCV

## 📌 Project Description
This project uses OpenCV's Haar Cascade Classifier to detect human faces in real-time using a webcam.

The program captures video from the computer's camera, converts each frame to grayscale, detects faces, and draws a blue rectangle around each detected face.

---

## 🚀 Features
- Real-time face detection
- Uses webcam as input
- Draws bounding boxes around detected faces
- Press `q` to exit the application

---

## 🛠 Requirements
- Python 3.x
- OpenCV

Install OpenCV using:

```bash
pip install opencv-python
```

---

## 📂 Files Used
- `face_detection.py` → Main Python script
- `haarcascade_frontalface_default.xml` → Pre-trained face detection model provided by OpenCV

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone <your-repository-link>
```

2. Navigate to the project folder:

```bash
cd <project-folder>
```

3. Run the program:

```bash
python face_detection.py
```

---

## ⌨ Controls

| Key | Action |
|-----|--------|
| q | Quit the application |

---

## 🧠 How It Works

1. Open the webcam using `cv2.VideoCapture(0)`.
2. Capture frames continuously.
3. Convert each frame to grayscale.
4. Detect faces using Haar Cascade.
5. Draw rectangles around detected faces.
6. Display the video feed.

---

## 📸 Output

When a face is detected, a blue rectangle appears around it in the webcam window.

Example:

```
+----------------------+
|      [ FACE ]        |
|   ┌────────────┐     |
|   │            │     |
|   │   Person   │     |
|   │            │     |
|   └────────────┘     |
+----------------------+
```

---

## 📚 Technologies Used
- Python
- OpenCV
- Haar Cascade Classifier

---

## 👨‍💻 Author
Uday Pratap Yadav