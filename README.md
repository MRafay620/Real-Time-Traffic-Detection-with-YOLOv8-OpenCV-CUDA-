# 📌 Traffic Detection using YOLOv8 🚦

![Traffic Detection](https://img.shields.io/badge/OpenCV-%2348A8DC.svg?style=for-the-badge&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=pytorch&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-%23FFDD44.svg?style=for-the-badge&logo=yolo&logoColor=black)

🚗 **Real-time Traffic Object Detection** using **YOLOv8** and **OpenCV** to detect and count vehicles from a video feed.

---

## 🌟 Features
✅ Real-time object detection using **YOLOv8**  
✅ **GPU acceleration** support for fast processing ⚡  
✅ Counts and displays detected vehicles 🚗🚛🚕  
✅ Works with **any traffic video feed** 🎥  

---

## 🛠️ Installation

🔹 First, clone the repository:
```bash
git clone https://github.com/your-username/traffic-detection.git
cd traffic-detection
```

🔹 Install the required dependencies:
```bash
pip install -r requirements.txt
```

🔹 Ensure you have the **YOLOv8 model** and **OpenCV** installed:
```bash
pip install ultralytics torch opencv-python
```

---

## 🚀 Usage

🔹 Run the script:
```bash
python traffic.py
```

🔹 Press **'q'** to exit the video window.

---

## 🏢 Project Structure

```
📂 traffic-detection
 ├── 📄 traffic.py        # Main detection script
 ├── 📄 requirements.txt  # Required dependencies
 ├── 🎥 traffic.mp4       # Sample traffic video (optional)
 ├── 📜 README.md         # Project documentation
```

---

## 🎯 How It Works?

1⃣ Loads the **YOLOv8** model  
2⃣ Reads video input using **OpenCV**  
3⃣ Resizes frames for efficient processing  
4⃣ Detects vehicles and counts them  
5⃣ Displays results in real-time with bounding boxes  

---

## ⚡ Performance Optimization

🔹 **Use GPU (CUDA) if available** to accelerate detection ⚡  
🔹 Resize video frames to **640x480** for better speed  
🔹 Use a **smaller YOLO model** like `yolov8n.pt` for real-time detection  

---

## 📄 Requirements

- Python 3.x 🐖  
- OpenCV 🎥  
- PyTorch ⚡  
- YOLOv8 🚗  

Install all dependencies using:
```bash
pip install -r requirements.txt
```

---


## 💜 License

📄 This project is licensed under the **MIT License**.

---

## ✨ Credits

👨‍💻 Developed by **Muhammad Rafay**  
🔗 [GitHub](https://github.com/MRafay620)  

---

