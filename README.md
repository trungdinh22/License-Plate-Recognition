# Vietnamese License Plate Recognition

This repository provides you with a detailed guide on how to training and build a Vietnamese License Plate detection and recognition system. This system can work on 2 types of license plate in Vietnam, 1 line plates and 2 lines plates.

## Installation & Run Demo

```bash
  git clone https://github.com/Marsmallotr/License-Plate-Recognition.git
  cd License-Plate-Recognition
  pip install -r ./requirement.txt
```

- Trained model provided in ./model folder in this repo 

- **Download yolov5 (old version) from this link:** [yolov5 - google drive](https://drive.google.com/file/d/1S_-GbVr24EYcRI9p4b24sVrDmnjX35l4/view?usp=sharing)

- Copy yolov5 folder to project folder

- Run step by step in LP_recognition.ipynb

## Vietnamese Plate Dataset

This repo uses 2 sets of data for 2 stage of license plate recognition problem:

- [License Plate Detection Dataset](https://drive.google.com/drive/folders/115k1rQMx-BYqnZx6uGKXL_0hBLtqaRyh?usp=sharing)
- [Character Detection Dataset](https://drive.google.com/drive/folders/1auj1aPoU_fthl6UXyp-Bziv-27-kDae6?usp=sharing)

## Training

**Training code for Yolov5:**

Use code in ./training folder
```bash
  training/Plate_detection.ipynb     #for LP_Detection
  training/Letter_detection.ipynb    #for Letter_detection
```
