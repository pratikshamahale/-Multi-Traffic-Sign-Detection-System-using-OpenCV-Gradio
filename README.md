# -Multi-Traffic-Sign-Detection-System-using-OpenCV-Gradio

# 🚦 Multi Traffic Sign Detection System using OpenCV & Gradio

This project is a computer vision–based Traffic Sign Detection System that identifies common traffic signs and signals using color segmentation and shape detection techniques. The system provides a simple and interactive web interface using Gradio.

---

## 🔍 Features

- Detects **Traffic Signals**
  - 🔴 Red Signal – Stop
  - 🟡 Yellow Signal – Ready
  - 🟢 Green Signal – Go
- Detects **Road Signs**
  - 🛑 Stop Sign
  - ⛔ No Entry Sign
  - 🚫 Speed Limit Sign
  - 🚸 Pedestrian Crossing
- Uses **HSV color space** for accurate color detection
- Uses **Contour & Shape Detection** for identifying sign geometry
- Interactive **Gradio Web Interface**
- Lightweight and fast (No Machine Learning required)

---

## 🧠 Technologies Used

- Python
- OpenCV
- NumPy
- Gradio
- Computer Vision (HSV, Edge Detection, Contours)

---

## ⚙️ How It Works

1. The uploaded image is converted to HSV and Grayscale formats.
2. Color masks are created for red, yellow, green, and blue.
3. Pixel counts determine dominant colors.
4. Contours and polygon approximation identify shapes.
5. Traffic signs are classified using **color + shape logic**.
6. The detected traffic sign is displayed on the web interface.

---

## 📷 Input

- Upload any image containing traffic signs or traffic signals.

---

## 📤 Output

- Displays the detected traffic sign or signal as text.

---

## 🚀 Installation & Run

```bash
pip install opencv-python numpy gradio

📌 Applications

Intelligent Transportation Systems (ITS)

Driver Assistance Systems

Traffic Monitoring

Educational Computer Vision Projects

🔮 Future Enhancements

Display bounding boxes around detected signs

Improve accuracy using morphological operations

Add confidence score

Integrate Deep Learning (CNN) for advanced detection

Real-time video detection

👩‍💻 Author

Pratiksha Chavan
Engineering Student | Python & Computer Vision Enthusiast

⭐ Acknowledgment

This project is developed for learning and academic purposes using OpenCV and Gradio.


---

If you want, I can:
- ✨ Make this **more attractive for recruiters**
- 📄 Add **project screenshots section**
- 🌐 Prepare **Hugging Face deployment README**
- 🧠 Simplify language for **college submission**

Just say the word 😄
::contentReference[oaicite:0]{index=0}
