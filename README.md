# Face Detection AI and Custom Dataset using YOLOv11

# 📌 Overview

## This project provides a face detection AI using YOLOv11. It consists of two main scripts:

1- train.py – Used to train the YOLOv11 model on your dataset.

2- run.py – Runs the trained model to detect faces using the trained weights.

3- This project supports any dataset for face detection and can be customized as needed.

# 🚀 Installation

1️⃣ Install Dependencies

1- Ensure you have Python 3.8+ installed, then install the required dependencies:

2- pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126

3- pip install Ultralytics

2️⃣ Clone the Repository

1- git clone https://github.com/AyoubBrm/ai-face-detect-and-custom-data-set.git

2- cd face-detect

# 🏋️‍♂️ Training the Model

# To train the model on your dataset, run:

1- python train.py

2- Ensure your dataset is prepared and formatted for YOLO.

3- Modify train.py to adjust training parameters such as epochs, batch size, and dataset path,
   and replace a FACE.DET.v3i.yolov11 folder with your data set .

# 🏃 Running Face Detection

1- After training, you can run the model using:

2- python run.py

# This script loads the trained weights from:

* detect/train4/weights/best.pt

* Ensure the model file exists in this directory before executing the script .

# 🔧 Customization

1- Supports any dataset in YOLO annotation format.

2- Modify train.py to adjust training settings like batch size, learning rate, and epochs .

3- Update run.py to configure inference settings, such as confidence thresholds and input sources .

# 📖 Note

*  You can use your own dataset instead of a predefined one, this is not just for face detect it work's with all dataset . 

# 📊 Result

![Face Detection](runs/detect/predict/WIN_20240902_07_30_49_Pro.jpg)
