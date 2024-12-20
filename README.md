# Real-Time Object Detection Using Neural Network

This project implements a real-time object detection system using YOLOv5 (You Only Look Once), a state-of-the-art deep learning model. The goal is to detect and classify objects in real-time with high accuracy and speed.

---

## Key Features
- **Real-Time Detection:** Optimized for detecting objects in real-time.
- **Custom Training:** Supports custom datasets for training.
- **Scalable Models:** Includes lightweight and complex model options for various use cases.
- **Pretrained Models:** Utilize pretrained weights for faster implementation.

---

## Table of Contents
1. [Setup](#setup)
2. [Usage](#usage)
3. [Project Structure](#project-structure)
4. [Dataset Preparation](#dataset-preparation)
5. [Training the Model](#training-the-model)
6. [Running Inference](#running-inference)
7. [Results](#results)
8. [Future Enhancements](#future-enhancements)
9. [License](#license)

---

## Setup

### Prerequisites
- Python 3.8 or higher
- GPU with CUDA support (optional, for faster training/inference)
- Libraries: PyTorch, OpenCV, NumPy

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/RamcharanSinghRamavath/Real-Time-Object-Detection-Using-Neural-Network.git
   cd Real-Time-Object-Detection-Using-Neural-Network

### Install the required Python packages:

 2. pip install -r requirements.txt
## Running Inference 

3. Run the detection script to classify objects in real-time:
    python detect.py --source 0 //for the live camera
    python detect.py --weights yolov5s.pt --img 640 --conf 0.25 --source data/images // for already given dataset
## Results
4. The model achieves:

     Precision: 92%
     Recall: 88%
     Inference Time: 15 ms/image (on GPU)
 ### Example detection output:
 
## Screenshots
## Screenshot Example

Here is a sample screenshot:

![Sample Screenshot](images/Screenshot%202024-12-20%20142106.png)



## Future Enhancements
   Integration with a web application for deployment.
   Support for additional neural network architectures.
   Improvement in inference speed and scalability.



