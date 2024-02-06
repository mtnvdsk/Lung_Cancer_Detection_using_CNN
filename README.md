# Lung Cancer Detection using Chest X-ray Images
This project involves the development of a deep learning model to detect lung cancer from chest X-ray images. The model is implemented using the Keras library and trained on a dataset containing images labeled as either 'PNEUMONIA' or 'NORMAL'.

# Dataset
The dataset used for training, testing, and validation is obtained from chest-xray-pneumonia dataset. It consists of chest X-ray images categorized into 'PNEUMONIA' and 'NORMAL' classes.

# Model Architecture
The deep learning model architecture includes convolutional layers, batch normalization, max-pooling, dropout, and dense layers. The model is trained using an image data generator to perform data augmentation.

# Training
The model is trained for 12 epochs with a learning rate reduction callback to improve performance. Training and validation accuracy, as well as loss, are visualized using matplotlib.

# Evaluation
The model's performance is evaluated on a separate test set, and metrics such as accuracy, loss, and a classification report are presented. Confusion matrix and sample predictions with images are also displayed.

# How to Use
1. Clone the repository:
```
git clone https://github.com/yourusername/your-repository.git
cd your-repository

```
2.Install the required dependencies:
```
pip install -r requirements.txt

```
3.Run the Jupyter Notebook:
```
jupyter notebook Lungcancerdetect.ipynb
```
Feel free to explore, modify, and contribute to this lung cancer detection project.

Make sure to replace "yourusername" and "your-repository" with your actual GitHub username and repository name. Also, consider adding a license, contributing guidelines, and any other relevant information to enhance the README file.
