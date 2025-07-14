# 🧠 Brain Tumor Classification using CNN

This project implements a Convolutional Neural Network (CNN)-based deep learning model for **brain tumor image classification**. The model architecture, training process, and hyperparameters are carefully designed to achieve high performance within constrained computational environments. For a detailed view of the model and training workflow, refer to the included Jupyter Notebook (`Brain_Tumor_CNN.ipynb`).

---

## 🚀 How to Use

### 🔧 Option 1: Google Colab (Recommended)

If you’re using **Google Colab**, simply upload and run the `.ipynb` file. All dependencies can be installed in Colab via standard commands.

### 💻 Option 2: Local Environment (Anaconda (miniconda) / PyCharm / VSCode)

If running locally, it's recommended to use:

- **Python 3.10** [Install Python](https://www.python.org/downloads/release/python-3100/)
- **Jupyter Notebook** (via Anaconda or IDE-integrated environment like PyCharm) [Install PyCharm Community Edition](https://www.jetbrains.com/pycharm/download/#section=linux)


To set up the required environment, use the provided `requirements.txt` file, that you can find beneath this line, and in project files (within the main directory):

```bash
pip install -r requirements.txt
```

## 📦 Requirements (`requirements.txt`)

Below is the compatible `requirements.txt` content:

    kagglehub==0.3.12
    matplotlib==3.10.0
    numpy==2.0.2
    seaborn==0.13.2
    Pillow==11.2.1
    torch==2.6.0
    torchvision==0.21.0
    scikit-learn==1.6.1
    optuna==4.3.0
    joblib==1.4.2


> ⚠️ **Note:** The model was developed and tested using the exact versions listed above. While backward compatibility is likely, results may vary with other versions.

If you're using CUDA support, make sure to have the appropriate **PyTorch CUDA wheel** installed for your system:  
👉 [Install PyTorch with CUDA](https://pytorch.org/get-started/locally/)