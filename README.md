
# DRDO Internship — Deep Learning Fundamentals, Custom Object Detection & Tracking

This repository contains the work completed during my 6–8 week summer internship at the **Defence Research and Development Organisation (DRDO)**, AI Division, Hyderabad.  
The project covers deep learning fundamentals, neural network architectures, custom object detection using YOLOv7, and real-time object tracking with re-identification using DeepSORT.


## 🔹 Project Highlights
- Studied and implemented concepts of **Neural Networks, CNNs, Gradient Descent, and evaluation metrics**.
- Developed a **custom object detection model** using YOLOv7, trained on a self-annotated dataset.
- Implemented **real-time multi-object tracking** using the DeepSORT algorithm.
- Integrated **person re-identification** so individuals maintain the same ID even after leaving and re-entering the frame.
- Used **Google Colab** for training and experimentation.



## 📂 Project Structure
- **/src** — Python scripts for YOLOv7 training, detection, and tracking.
- **/notebooks** — Google Colab / Jupyter notebooks for experiments and demos.
- **/outputs** — Sample detection and tracking results (images/videos).
- **/datasets** — Dataset instructions (dataset not included for confidentiality).
- **requirements.txt** — Python dependencies.
- **Internship_Report.pdf** — Detailed internship report.


## 📦 Installation

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt



 ▶ Running the Code

Train YOLOv7 on your dataset

python src/custom_yolov7_train.py

Run Tracking & Re-Identification

python src/tracking_reid.py`


📊 Results

| Task                    | Model  | mAP\@0.5 | FPS |
| ----------------------- | ------ | -------- | --- |
| Custom Object Detection | YOLOv7 | 94%      | 25  |

Sample Outputs
Detection example:
![Sample Detection](outputs/sample_detection.jpg)

Tracking & Re-ID example:
![Tracking Demo](outputs/tracking_demo.mp4)

---

## 📧 Contact

Email: [your.email@example.com](mailto:your.email@example.com)
LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)

---



