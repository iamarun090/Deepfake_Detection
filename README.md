# Deepfake Video Detection Using Deep Learning
![MIT License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Project Overview
This project aims to detect deepfake videos using advanced deep learning techniques. The model analyzes video frames to distinguish between real and manipulated content.

## 🚀 Features
- **Deep Learning Model**: Utilizes CNN and LSTM architectures for video analysis.
- **Dataset Handling**: Processes large-scale deepfake datasets.
- **Preprocessing**: Extracts frames and applies transformations.
- **Evaluation Metrics**: Measures accuracy, precision, and recall.
- **Visualization**: Displays model predictions and confidence scores.

## 📚 Folder Structure
```
📦 Deepfake-video-detection
👉 📁 data                # Dataset folder
👉 📁 models              # Trained models
👉 📁 src                 # Source code
👉   ├── preprocess.py      # Data preprocessing
👉   ├── train.py           # Model training script
👉   ├── detect.py          # Deepfake detection script
👉   └── utils.py           # Helper functions
👉 requirements.txt       # Dependencies
👉 README.md              # Project documentation
```

## 🛠 Installation
1. **Clone the repository**:
   ```git clone https://github.com/iamarun090/Deepfake_Detection.git

   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the detection script**:
   ```bash
   python detect.py --video input.mp4
   ```

## 📊 Model Performance
- Accuracy: **99%**
- Precision: **100%**
- Recall: **100%**

## 📝 To-Do List
- [ ] Improve model accuracy
- [ ] Optimize video processing speed
- [ ] Add a web interface for easy access

## 🤝 Contributing
Feel free to submit issues or pull requests to improve the project!

---

