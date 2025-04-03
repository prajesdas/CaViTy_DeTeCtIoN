# 🦷 Cavity Detection Model

## 📌 Overview
This project implements a **Cavity Detection Model** using deep learning techniques to identify dental cavities from images. The model utilizes **YOLO** for object detection and a custom-trained deep learning model for classification.


## 📂 Project Structure
```
📁 cavity-detection
├── 📜 README.md
├── 📜 requirements.txt
├── 📂 dataset
│   ├── 🖼 images/
│   ├── 📄 annotations/
├── 📂 models
│   ├── 🧠 cavity_detection_model.pth
├── 📂 src
│   ├── 📝 train.py
│   ├── 📝 detect.py
│   ├── 📝 utils.py
└── 📂 results
    ├── 📊 performance_metrics.png
    ├── 🖼 sample_predictions/
```

## 🛠 Installation
Make sure you have Python installed. Then, run the following command to install the dependencies:
```bash
pip install -r requirements.txt
```

## 🎯 Features
✅ Automated cavity detection from dental images 🦷  
✅ High accuracy with YOLO-based object detection 📈  
✅ Customizable model for different datasets 🔧  
✅ Easy-to-use interface with real-time detection 🎥  

## 🏃‍♂️ Usage
### 🔍 Run Detection
```bash
python detect.py --image path/to/dental_xray.jpg
```

### 📊 Train the Model
```bash
python train.py --epochs 50 --batch-size 16
```

## 📌 Sample Results
Example of cavity detection on a sample dental X-ray:

![Screenshot 2025-04-03 230348](https://github.com/user-attachments/assets/e56cd453-10b0-4ef1-b2be-ab2abd323383)

![Screenshot 2025-04-03 230430](https://github.com/user-attachments/assets/8d77b98c-4d19-433a-b58b-e706e159fe03)




## 🚀 Future Improvements
- Improve model accuracy with more labeled data 📚  
- Develop a mobile application for real-time detection 📱  
- Implement an explainable AI approach for dentists 🏥  



