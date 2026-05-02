# Breast Cancer Prediction using Histopathological Images

## 1. Introduction

This project focuses on the classification of breast cancer using histopathological images. It leverages machine learning and deep learning techniques to distinguish between benign and malignant tissue samples.

The dataset used for this project is the **BreakHis - Breast Cancer Histopathological Dataset**, sourced from Kaggle. The goal is to build an accurate and reliable model that can assist in early detection and diagnosis.

---

## 2. Dataset

The dataset used is:

* Name: BreakHis - Breast Cancer Histopathological Dataset
* Source: Kaggle
* Type: Image dataset (microscopic tissue images)

### Dataset Description

The dataset contains:

* Images of breast tumor tissue
* Two main classes:

  * Benign
  * Malignant
* Multiple magnification factors (e.g., 40X, 100X, 200X, 400X)

### Folder Structure (Used in this Project)

```id="n3z8mz"
dataset/
└── BreaKHis_v1/
    └── histology_slides/
        └── breast/
            ├── benign/
            │   ├── adenosis/
            │   ├── fibroadenoma/
            │   └── ...
            │
            └── malignant/
                ├── ductal_carcinoma/
                ├── lobular_carcinoma/
                └── ...
```

---

## 3. Project Structure

```id="7f42we"
Breast_Cancer_Prediction/
│
├── dataset/                 # Contains image dataset
├── main.py                  # Complete implementation code
├── requirements.txt         # Required dependencies
├── README.md                # Project documentation
└── .gitignore               # Ignored files
```

---

## 4. Requirements

Install dependencies using:

```id="c5n6ru"
pip install -r requirements.txt
```

Main libraries used:

* numpy
* pandas
* matplotlib
* seaborn
* scikit-learn
* tensorflow
* opencv-python
* tqdm
* joblib

---

## 5. How to Run

1. Clone the repository:

```id="woxp61"
git clone https://github.com/Chelva07/Breast_Cancer_Prediction.git
cd Breast_Cancer_Prediction
```

2. Install dependencies:

```id="6p7f6x"
pip install -r requirements.txt
```

3. Ensure the dataset is placed correctly inside the `dataset/` folder as shown above.

4. Run the project:

```id="lw5p9n"
python main.py
```


---

## 6. Notes

* Ensure correct dataset path is used in the code.
* Large datasets may take time to train.
* GPU is recommended for faster deep learning training.

---

## 7. License

This project is for academic and educational purposes.

---
