# Knife Detection using YOLOv5

This repository contains the implementation of knife detection using YOLOv5. The project is our research paper presented at the ACM International Conference on Intelligent Information Technology (ICIIT) 2024.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Dataset](#dataset)
- [Evaluation](#evaluation)
- [Results](#results)

## Introduction

Knife detection is a crucial task in various security applications, such as surveillance systems and threat detection in public areas. This project leverages the power of YOLOv5, a state-of-the-art object detection model, to accurately identify and locate knives in images and videos.

The detailed methodology and results of this project are documented in our paper presented at ICIIT 2024. You can access the paper [here]([https://camps.aptaracorp.com/ACM_PMS/PMS/ACM/ICIIT2024/2/2e3f4117-f0c8-11ee-8182-16bb50361d1f/OUT/iciit2024-2.html#bib11](https://dl.acm.org/doi/10.1145/3654522.3654524)).

## Installation

To get started with the project, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/TruongSinhAI/Knife-Detection-YOLOv5.git
cd Knife-Detection-YOLOv5
```
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
## Dataset
The dataset used for training the knife detection model can be obtained from [link to dataset](https://github.com/ari-dasci/OD-WeaponDetection/tree/master/Knife_detection).

![image](https://github.com/user-attachments/assets/a3679c4d-adc8-42da-aeba-db7e84e98174)

## Evaluation
Evaluate the trained model using:

```bash
python val.py --weights runs/train/exp/weights/best.pt --data data/knife.yaml --img 640
```

## Results
The results of the knife detection model, including precision, recall, and mAP, are documented in the results directory. Detailed evaluation metrics and performance analysis can be found in our [ICIIT 2024 paper.]([https://camps.aptaracorp.com/ACM_PMS/PMS/ACM/ICIIT2024/2/2e3f4117-f0c8-11ee-8182-16bb50361d1f/OUT/iciit2024-2.html#bib11](https://dl.acm.org/doi/10.1145/3654522.3654524))

![image](https://github.com/user-attachments/assets/d098e7f4-b295-48b7-9481-398b09187bdd)



