# 🚦 Multi Traffic Sign Detection System using OpenCV & Gradio

## 📌 Project Overview
The Traffic Sign & Traffic Light Detection System is a computer vision–based project that detects common road traffic signs and traffic signals and identifies their category or current state (Red, Yellow, or Green).  
This project demonstrates the application of image processing techniques used in intelligent transportation systems and driver assistance systems.

---
## 🎯 Objectives
- Detect traffic signs from image input
- Identify traffic light state (Red / Yellow / Green)
- Recognize road signs such as Stop, No Entry, Speed Limit, and Pedestrian Crossing
- Apply practical computer vision concepts
- Understand rule-based traffic sign recognition


## 🛠️ Technologies Used
- Python
- OpenCV
- NumPy
- Gradio
- Computer Vision & Image Processing

---

## 📂 Project Structure
Traffic-Sign-Detection/
│
├── app.py # Main Python application
├── README.md # Project documentation
├── requirements.txt # Required libraries
├── screenshots/ # Project screenshots
│ ├── input.png
│ ├── red_signal.png
│ ├── yellow_signal.png
│ └── green_signal.png
└── sample_images/ # Test images


---

## ⚙️ Working Methodology
1. Load the input image using Gradio interface
2. Convert the image to HSV and Grayscale color spaces
3. Apply color thresholding for Red, Yellow, Green, and Blue
4. Perform edge detection and contour extraction
5. Identify traffic signs using shape and color analysis
6. Classify the detected traffic sign or signal
7. Display the detection result to the user

---

## ▶️ How to Run the Project

### Clone the repository

git clone https://github.com/your-username/traffic-sign-detection.git


Navigate to the project directory
cd traffic-sign-detection

Install dependencies
pip install opencv-python numpy gradio

Run the application
python app.py


Open the Gradio link displayed in the terminal.

## 📸 Screenshots
🔹 Input Image
<img width="1920" height="1020" alt="Screenshot 2026-01-29 175515" src="https://github.com/user-attachments/assets/47ec886f-801f-4834-b11c-b3ff3021dde5" />
<img width="1920" height="1020" alt="Screenshot 2026-01-29 175530" src="https://github.com/user-attachments/assets/7c1efd72-c544-4043-a0d5-a78051ff78ca" />
<img width="1920" height="1020" alt="Screenshot 2026-01-29 175542" src="https://github.com/user-attachments/assets/82a51e3f-3e44-4a6d-b292-2fe88a3c330c" />



* 🔹 Red Signal Detection
<img width="1920" height="1020" alt="Screenshot 2026-01-29 180628" src="https://github.com/user-attachments/assets/2dda0f83-7d28-419f-9a6f-62ebf99d34fb" />


* 🔹 Yellow Signal Detection
<img width="1920" height="1020" alt="Screenshot 2026-01-29 181759" src="https://github.com/user-attachments/assets/53a9086e-7cbb-44d9-9acf-78326a220ba2" />


* 🔹 Green Signal Detection
<img width="1920" height="1020" alt="Screenshot 2026-01-29 175610" src="https://github.com/user-attachments/assets/be9e47cc-804b-4d47-b4ad-5d31afc17554" />


## 📊 Output

* Traffic sign detected from the uploaded image

* Traffic light color correctly identified

* Detection result displayed via web interface


## 🚀 Applications

* Intelligent Transportation Systems (ITS)

* Autonomous Vehicles

* Smart Traffic Management

* Advanced Driver Assistance Systems (ADAS)

* Road Safety Automation


## 🌱 Future Enhancements

* Real-time detection using live camera feed

* Deep learning–based detection using CNN or YOLO

* Improved accuracy in complex environments

* Detection of multiple traffic signs simultaneously


## 👩‍💻 Author

* Name: Pratiksha Chavan
* Domain: Python & Computer Vision
* Skills: Python, OpenCV, NumPy, Data Analytics, Image Processing


## 📜 License

* This project is developed for educational purposes and is free to use with proper credit.
