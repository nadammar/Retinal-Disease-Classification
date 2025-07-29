# 👁️ Retinal Disease Classification 

##  Project Overview

This project focuses on **automated classification of retinal diseases** using deep learning models. The dataset was sourced from **Kaggle** and consists of retinal images categorized into four classes:

* `CNV`: Choroidal Neovascularization
* `DME`: Diabetic Macular Edema
* `DRUSEN`: Drusen (deposits beneath the retina)
* `NORMAL`: Healthy retinas

![Sample Retinal Images](images/retinal_classes.png)

The goal of this project is to leverage transfer learning and convolutional neural networks to accurately classify these retinal conditions and provide an easy-to-use web interface for predictions.

## 🛠️ Key Contributions

* Trained and fine-tuned deep learning models including **VGG16**, **DenseNet**, and **ResNet** for retinal disease classification.
* Developed a simple **Flask-based web application** to allow users to upload retinal images and receive classification results in real-time.

## 📚 Tools & Technologies

* Python, TensorFlow/Keras, OpenCV
* Deep learning models: VGG16, DenseNet, ResNet
* Flask (for the web app interface)
* Data preprocessing and augmentation libraries (NumPy, Pandas, Scikit-learn, etc.)

## ⚙️ Installation & Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/nadammar/Retinal-Disease-Classification.git  
   cd Retinal-Disease-Classification  
   ```
2. **Prepare the dataset:**

   * Download the dataset from Kaggle and organize retinal images in folders for the four classes (`CNV`, `DME`, `DRUSEN`, `NORMAL`).
   * Update dataset paths as needed.
3. **Train or load pre-trained models**

4. **Run the Flask web app**


## 👨‍💻 Author

Project developed by **Nada Ammar** using deep learning and web technologies to aid early detection of retinal diseases.

