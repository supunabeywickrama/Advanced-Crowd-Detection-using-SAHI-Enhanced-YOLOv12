# 🚀 Advanced Crowd Detection using SAHI-Enhanced YOLOv12

Accurate crowd detection in dense environments is challenging due to **small object size, heavy occlusion, and down-sampling in standard object detectors**.  
This project addresses those challenges by combining **YOLOv12** with **SAHI (Slicing Aided Hyper Inference)** to significantly improve **person detection and crowd counting accuracy** in high-density scenes.

---
## 🎥 Demo Video

👉 **[▶ Watch Demo Videos](https://drive.google.com/drive/folders/1GuuSfCuYVbzZrR6shHrMDTqPBNkUZsU0?usp=sharing)** 

---

## 📌 Project Overview

Traditional YOLO inference often misses **distant or partially visible people** in crowded scenes.  
To overcome this limitation, this project uses **SAHI**, which slices high-resolution images and video frames into overlapping tiles, allowing the detector to better recognize **small and occluded individuals**.

The final system supports:

- High-resolution image inference  
- Real-time and offline video processing  
- Accurate crowd counting  
- Scalable deployment for surveillance and analytics  

---

## 🎯 Key Features

- ✅ YOLOv12-based person detection  
- ✅ SAHI slicing for improved small-object detection  
- ✅ Works on dense crowds and wide-angle scenes  
- ✅ Supports images and videos  
- ✅ Accurate people counting  
- ✅ OpenCV-based visualization  
- ✅ Optimized for real-world surveillance use cases  

---

## 🧠 Why SAHI?

Standard YOLO inference downsamples images, which causes **small people in crowded scenes to be missed**.

SAHI improves this by:

- Splitting high-resolution frames into overlapping slices  
- Running detection on each slice independently  
- Merging predictions back using non-maximum suppression (NMS)  

This allows the model to:

- Detect small, distant people  
- Handle overlapping and occluded individuals  
- Achieve higher recall in dense crowds  

---

## 🏗️ System Architecture

Input Image / Video
↓
SAHI Slicing (Overlapping Tiles)
↓
YOLOv12 Detection on Each Slice
↓
Prediction Merging (NMS)
↓
Crowd Detection + Counting Output

yaml
Copy code

---

## 🛠️ Tech Stack

- **Model:** YOLOv12 (Ultralytics)  
- **Inference Framework:** SAHI  
- **Language:** Python  
- **Libraries:** PyTorch, OpenCV, NumPy  
- **Platforms:** Kaggle, Google Colab  
- **Output:** Annotated images, videos, CSV counts  

---

## 📂 Project Structure

<img width="866" height="451" alt="image" src="https://github.com/user-attachments/assets/ce0fc121-b61b-483b-bd12-fc53fba37782" />


---


## 📊 Results

- 📈 Improved recall for small and distant people  
- 👥 More accurate crowd counts compared to standard YOLO inference  
- 🎥 Stable performance on high-resolution videos  
- 🧠 Better handling of occlusion and dense scenes  

---

## 📌 Use Cases

- Smart city surveillance  
- Event and stadium safety  
- Public transport monitoring  
- Crowd density analysis  
- Drone-based crowd observation  
- Emergency and disaster management  

---

## 📜 License

This project is released under the **Apache 2.0 License**, allowing free use for academic and commercial purposes.

---

## 🙌 Acknowledgements
- Ultralytics YOLO
- SAHI (Slicing Aided Hyper Inference)
- Open-source computer vision community
