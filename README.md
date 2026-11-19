# DeepShield: CNN-Based Medical Image Analysis and Secure Data Handling

## 1. Project Overview

DeepShield is a medical image analysis project that uses Convolutional Neural Networks (CNNs) to analyse medical images, focusing on pneumonia image classification.

The project combines deep learning techniques with data security mechanisms to support secure handling and transmission of medical images.

The model was developed using TensorFlow and Keras. Additionally, AES encryption and steganography were implemented using PyCryptodome to protect sensitive medical image data.

## 2. Problem Statement

Medical image analysis plays an important role in identifying abnormalities and supporting healthcare professionals.

However, working with medical images presents two major challenges:

- **Image classification:** Developing a deep learning model capable of identifying relevant patterns in medical images.
- **Data security:** Protecting sensitive medical images during storage and transmission.

DeepShield addresses these challenges by combining CNN-based image analysis with encryption and steganography techniques.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| TensorFlow | Deep learning framework |
| Keras | CNN model development |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| PyCryptodome | AES encryption |
| Jupyter Notebook | Development and experimentation |

## 4. Methodology

The project follows these main stages:

1. **Dataset Preparation:** Load and organise the medical image dataset.
2. **Data Preprocessing:** Prepare images for CNN model training and evaluation.
3. **Model Development:** Develop a CNN-based deep learning model using TensorFlow and Keras.
4. **Model Training:** Train the model to learn relevant patterns from the medical images.
5. **Model Evaluation:** Evaluate model performance using accuracy, precision, recall and F1-score.
6. **Data Security:** Implement AES encryption and steganography to support secure storage and transmission of medical images.

## 5. Model Evaluation Results

The CNN model achieved the following evaluation results:

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 82% |
| Precision | 0.87 |
| Recall | 0.85 |
| F1-Score | 0.86 |

These metrics provide an indication of the model's classification performance on the evaluated dataset.

## 6. Data Preprocessing

Data preprocessing was performed to prepare medical images for deep learning.

The project involved:

- Preparing and organising medical image data.
- Processing images for CNN model input.
- Addressing class imbalance to improve model performance.
- Preparing the dataset for model training and evaluation.

## 7. Encryption and Steganography

To address medical image data security, the project incorporates two techniques:

**AES Encryption**

Advanced Encryption Standard (AES) was implemented using PyCryptodome to encrypt medical image data and support secure storage and transmission.

**Steganography**

Steganography was implemented to explore hiding information within image data, providing an additional layer of data protection.

The project also explored converting pneumonia dataset images into byte streams for encryption.

## 8. How to Run the Notebook

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries

### Step 1: Clone the repository

```bash
git clone https://github.com/abbusaif007/DeepShield.git
```

### Step 2: Navigate to the project directory

```bash
cd DeepShield
```

### Step 3: Install dependencies

```bash
pip install tensorflow numpy matplotlib pycryptodome jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the notebook

Open `CNN_Working_Backend.ipynb` in Jupyter Notebook and execute the cells sequentially.

Ensure that the required dataset is available at the location expected by the notebook.

---

## Repository Structure

```text
DeepShield/
│
├── CNN_Working_Backend.ipynb
│
└── README.md
```


GitHub: https://github.com/abbusaif007

---

*This project was developed as an academic project exploring deep learning applications in medical image analysis and secure medical data handling.*
