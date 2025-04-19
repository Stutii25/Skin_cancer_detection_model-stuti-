# Skin_cancer_detection_model-stuti-
# Skin Cancer Detection using CNN

This project uses Convolutional Neural Networks (CNNs) to classify skin cancer images using a curated dataset from Hugging Face.

## 📂 Dataset
The dataset is hosted on Hugging Face:
- **Source**: [Pranavkpba2000/skin_cancer_small_dataset](https://huggingface.co/datasets/Pranavkpba2000/skin_cancer_small_dataset)

## 🔧 Technologies Used
- Python
- TensorFlow / Keras
- Hugging Face Datasets
- Matplotlib, NumPy, Pandas

## 🧠 Model Architecture
- Sequential CNN with:
  - Conv2D, MaxPooling2D
  - Flatten, Dense layers
- Trained using categorical crossentropy loss

## 📈 Results
- The model achieves high accuracy in detecting skin cancer types.
- Training and validation performance is plotted for analysis.

## 🚀 How to Run
1. Install required packages:
    ```bash
    pip install datasets tensorflow keras
    ```
2. Run the Jupyter Notebook:
    ```bash
    jupyter notebook skin_cancer2.ipynb
    ```

## 🤝 Acknowledgements
- Dataset by Pranavkpba2000 on Hugging Face
