# 🧠 Facial Recognition App (Python + OpenCV)

This is a simple real-time facial recognition app built with Python, OpenCV, and the `face_recognition` library. The app uses your webcam to detect and recognize faces based on known images provided in a folder.

## 📦 Features

- Real-time face detection and recognition
- Logs recognized faces with timestamps in `logs.csv`
- Easily add known faces by dropping images into the `known_faces/` folder

---

## 🚀 Setup Instructions

### 1. Clone or Download the Project

Download and unzip this repository or clone it using Git:

```bash
git clone <your-repo-url>
```

Or download directly:
[📥 facial_recognition_app.zip](sandbox:/mnt/data/facial_recognition_app.zip)

### 2. Install Dependencies

Make sure Python 3.6+ is installed. Then install the required libraries:

```bash
pip install face_recognition opencv-python numpy
```

### 3. Add Known Faces

Place `.jpg` or `.png` images of people you want the app to recognize into the `known_faces/` folder.

> 📛 The image filename (e.g., `john_doe.jpg`) will be used as the person's name.

---

## ▶️ How to Run

In your terminal, navigate to the project folder and run:

```bash
python main.py
```

Your webcam will open and start detecting faces. When a face is recognized, it will:

- Display the person's name on screen
- Log the recognition in `logs.csv` with a timestamp

To stop the app, press the **`q`** key.

---

## 📁 Project Structure

```
facial_recognition_app/
├── known_faces/        # Place known face images here
│   └── john_doe.jpg
├── logs.csv            # Automatically updated with name + timestamp
├── main.py             # Main application script
└── README.md           # This file
```

---

## 📝 Logs

All recognized faces are logged in the `logs.csv` file:

```
Timestamp,Name
2025-06-13 14:32:05,John_Doe
```

---

## ✅ Requirements

- Python 3.6+
- `opencv-python`
- `face_recognition`
- `numpy`

---

## 📌 Notes

- Make sure lighting is good for better recognition.
- For accurate results, use clear front-facing face images.
- This project uses basic face recognition with no database or authentication—suitable for learning and demos.

---

## 📧 License & Contact

This project is for educational purposes.  
Feel free to modify and enhance it for your own needs.

Maintained by: **Ntsika Ngilane**