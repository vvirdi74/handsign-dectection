#  Sign Language Recognition using YOLOv5

##  Project Overview

This project aims to recognize hand gestures according to sign language alphabets using a YOLOv5 object detection model. The system recognizes 26 alphabets (A–Z) from either input images or a live webcam feed.

---

##  Dataset Description

The dataset used for this project is from **Roboflow** and contains multiple classes corresponding to different sign language gestures. It is already preprocessed and split into training and validation sets.

---

##  Objectives

- Detect hand signs using YOLOv5.
- Recognize each detected hand sign into one of 26 alphabet categories (A–Z).
- Visualize predictions in real time using OpenCV.
- Evaluate model performance with metrics like precision, recall, and mAP.

---

##  Tools & Technologies

- **Python**: Core programming language.
- **YOLOv5**: Object detection framework.
- **PyTorch**: Deep learning backend.
- **OpenCV**: Image processing and real-time visualization.
- **Google Colab**: Training and experimentation platform.

---


##  Training Results

- **Precision**: 0.994  
- **Recall**: 0.997  
- **mAP@0.5**: 0.995  
- **mAP@0.5:0.95**: 0.873

---

##  Testing Results

After training, the model was evaluated on a separate test set to assess its generalization to unseen data. The test results were as follows:

- **Precision**: 0.990  
- **Recall**: 0.992  
- **mAP@0.5**: 0.995  
- **mAP@0.5:0.95**: 0.867

---

## 🙌 Acknowledgements



- Ultralytics YOLOv5 .
- Roboflow (https://roboflow.com/) .

