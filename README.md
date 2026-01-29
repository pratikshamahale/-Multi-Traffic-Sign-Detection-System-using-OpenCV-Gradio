# 🚦 Multi Traffic Sign Detection System using OpenCV & Gradio

This project is a computer vision–based Traffic Sign Detection System that identifies common traffic signs and signals using color segmentation and shape detection techniques. The system provides a simple and interactive web interface using Gradio.

---

## 📸 Project Screenshots

### Upload Image Interface
<img width="1920" height="1020" alt="Screenshot 2026-01-29 175515" src="https://github.com/user-attachments/assets/63240e5d-7e0e-47ce-b314-4998107b6cde" />
<img width="1920" height="1020" alt="Screenshot 2026-01-29 175530" src="https://github.com/user-attachments/assets/c8593d42-1a65-495b-a0cb-425e77c4e0c5" />
<img width="1920" height="1020" alt="Screenshot 2026-01-29 175542" src="https://github.com/user-attachments/assets/c894c677-afe2-4003-b467-8b373e902a0a" />




### Detection Result
<img width="1920" height="1020" alt="Screenshot 2026-01-29 175610" src="https://github.com/user-attachments/assets/f12d6555-3546-42cd-a983-7a2c823b14cd" />
<img width="1920" height="1020" alt="Screenshot 2026-01-29 180628" src="https://github.com/user-attachments/assets/bbfcd695-6e23-44f1-ab4c-f2bf5d7456c7" />





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

⭐ Acknowledgment

This project is developed for learning and academic purposes using OpenCV and Gradio.


