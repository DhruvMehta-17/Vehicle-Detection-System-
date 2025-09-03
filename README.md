# Vehicle-Detection-System-

This is a **group project** focused on detecting vehicles in videos using classical image processing techniques and OpenCV in Python. The main objective is to extract frames from a video, detect vehicles in each frame, and generate a new video with detection results.

---

## 🧠 Project Objective

The goal of this project is to implement a basic yet efficient pipeline for **vehicle detection from video footage**. The system processes each frame, detects vehicles using traditional computer vision techniques, draws bounding boxes around the detected vehicles, and compiles the output frames into a new annotated video.

This is particularly useful in real-world applications like:
- Traffic surveillance systems
- Vehicle counting for tolls or smart cities
- Road safety monitoring

---

## ⚙️ Tech Stack

- **Language:** Python
- **Libraries:** OpenCV, NumPy
- **Model:** Haar Cascade Classifier (for object detection)
- **Tools:** Jupyter Notebook, Git

---

## 🛠️ Project Workflow

1. **Video Loading:** Load input video using OpenCV.
2. **Frame Extraction:** Read each frame one by one.
3. **Vehicle Detection:** Use Haar Cascade Classifier to detect vehicles in each frame.
4. **Draw Bounding Boxes:** Mark each detected vehicle with a rectangle.
5. **Video Compilation:** Save the annotated frames into a new output video.

---

## 📁 File Structure

```bash
├── Image_processing_notebook.ipynb   # Jupyter Notebook with code
├── input_video.mp4                   # Sample input video
├── output_video.avi                  # Output with vehicle detection
├── haarcascade_car.xml               # Pre-trained Haar Cascade model
└── README.md                         # Project documentation


---

▶️ How to Run

1. Clone the repository:

git clone https://github.com/your-username/vehicle-detection-project.git
cd vehicle-detection-project

2. Install dependencies:

pip install opencv-python numpy

3. Run the Jupyter Notebook:

jupyter notebook Image_processing_notebook.ipynb

4. The output video will be saved as output_video.avi after processing.

---

📌 Key Highlights

Simple and effective use of traditional computer vision methods.

Real-time application for detecting moving vehicles.

Can be extended using deep learning models like YOLO, SSD, or Faster R-CNN for better accuracy.
