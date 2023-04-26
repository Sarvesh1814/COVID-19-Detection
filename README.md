# COVID-19-Detection-
This repository contains code for a COVID-19 detection system using deep learning models. The system utilizes a dataset of chest X-ray images to train various deep learning models, including CNN, MobileNet, ResNet50, VGG-19, Xception, ResNet101, ANN, and AlexNet.

# Dataset
The dataset used in this project is the COVID-19 Dataset, which contains total 5786 images of both positive and negative class equally distributed.
Link of the dataset: https://drive.google.com/drive/folders/18nj7Xok8Hu2jUgOuoiWJPFBZ6v9a-o4A?usp=sharing

# Usage
1. Clone the repository to your local machine
2. Download the dataset.
3. Open the Jupyter Notebook file 'COVID_19_AML_Project.ipynb' in Google Colab or Jupyter Notebook and run the cells.
4. To compare the performance of the various models, run the plot_histories() function in the notebook.
5. To test a specific model on a new chest X-ray image, run the code block that loads the model and prompts the user to select the model from a list of available models. Then, run the code block that prompts the user to upload an image to test.

# Dependencies
* tensorflow==2.4.0
* keras==2.4.3
* numpy==1.19.5
* pandas==1.1.5
* seaborn==0.11.1
* scikit-learn==0.22.2.post1
* matplotlib==3.2.2
* opencv-python==4.1.2.30
* pillow==7.1.2

All dependencies can be installed via pip.
