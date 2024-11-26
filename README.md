# Age Recognition (VGG16)

Classification of faces into 3 classes: YOUNG (0), MIDDLE (1), OLD (2)

## Requirements

- Python 3.12.0
- Virtual environment tool (optional but recommended)

## Setup Instructions

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Download dataset

https://www.kaggle.com/datasets/arashnic/faces-age-detection-dataset/code?select=train.csv

### 3. Setup data

Create this folder structure:

data/ \
├── Test/test_images.png (from faces_02/part3) \
├── Train/train_images.png \
└── train.csv 
