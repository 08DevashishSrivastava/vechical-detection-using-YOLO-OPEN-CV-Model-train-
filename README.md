# 🚗 YOLO Object Detection with Graph Visualization

This project performs **real-time object detection** using YOLOv8 and visualizes the results using **Matplotlib graphs**.

---

## 📌 Features

* 🎯 Object detection using YOLOv8
* 🎥 Works on video input (cars.mp4)
* 📊 Graph visualization of detections per frame
* 📈 Simple and easy-to-understand implementation

---

## 🛠️ Technologies Used

* Python 🐍
* OpenCV
* Ultralytics YOLOv8
* Matplotlib

---

## 📂 Project Structure

```
├── main.py          # Main detection + graph code
├── cars.mp4         # Input video file
├── README.md        # Project documentation
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install dependencies

```
pip install ultralytics opencv-python matplotlib
```

---

## ▶️ How to Run

```
python main.py
```

---

## 📊 Output

* 🎥 Detects objects frame-by-frame
* 📈 Displays a graph:

  * X-axis → Frame Number
  * Y-axis → Number of Objects Detected

---

## 🧠 How It Works

1. Load YOLOv8 model
2. Read video frame-by-frame
3. Detect objects in each frame
4. Count detected objects
5. Store results in a list
6. Plot graph using Matplotlib

---

## 📸 Example Use Cases

* Traffic analysis 🚦
* Vehicle counting 🚗
* Object tracking research 📊

---

## 🚀 Future Improvements

* Real-time live graph
* Speed detection of vehicles
* Web dashboard integration
* Save graph as image

---

## 🤝 Contributing

Feel free to fork this repo and improve it!

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Devashish Srivastava**

---

⭐ If you like this project, don’t forget to star the repository!
