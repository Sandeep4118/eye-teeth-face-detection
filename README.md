<img width="421" height="277" alt="image" src="https://github.com/user-attachments/assets/2b18ee4f-3220-45d8-bc8a-a3502a12782a" /># 👁️ Eye Teeth Face Detection using OpenCV

This project performs real-time detection of:

- 👤 Face Detection  
- 👀 Eye Detection  
- 😄 Smile / Teeth Detection  

using Haar Cascade classifiers in OpenCV.

---

## 🚀 Technologies Used

- Python
- OpenCV
- NumPy
- Haar Cascade Classifiers

---


---

## ▶️ How It Works

1. Loads Haar Cascade models.
2. Starts webcam.
3. Converts frames to grayscale.
4. Detects face.
5. Detects eyes inside face.
6. Detects smile (teeth visibility).
7. Draws rectangles and labels.
8. Press **q** to exit.

---

## 🛠️ Installation

Install required libraries:

```bash
pip install opencv-python numpy


## Run the project
python main.py


## Project Structure
eye-teeth-face-detection/
│
├── main.py
├── haarcascade_eye.xml
├── haarcascade_smile.xml
├── haarcascade_frontalface_default.xml
└── README.md
