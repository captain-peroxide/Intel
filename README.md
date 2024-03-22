#Diabetic Retinopathy Detection using ResNet34
This project aims to detect diabetic retinopathy in retinal images using the ResNet34 convolutional neural network architecture. Diabetic retinopathy is a common complication of diabetes and early detection is crucial for effective treatment.

#Dataset
The dataset used for training and testing the model is the Kaggle Diabetic Retinopathy Detection dataset, which contains a large number of high-resolution retinal images labeled with diabetic retinopathy severity levels.

#Model Architecture
The model architecture used is ResNet34, which is a variant of the ResNet (Residual Network) architecture. ResNet34 has 34 layers and is known for its effectiveness in image classification tasks.

#Requirements
Python 3.x
PyTorch
torchvision
intel extensions for pandas, scikitlearn nad pytorch
NumPy
Matplotlib
Pandas
Jupyter Notebook (for running and viewing the code)
Install the required libraries using the following command:

#Usage
Data Preparation: Download the Kaggle Diabetic Retinopathy Detection dataset and organize it into training and testing folders. Make sure to preprocess the images as necessary (e.g., resizing, normalization).

Training: Run the provided Jupyter Notebook or Python script to train the ResNet34 model on the prepared dataset. Adjust hyperparameters such as learning rate, batch size, and number of epochs as needed.

Evaluation: Evaluate the trained model on a separate test set to measure its performance in detecting diabetic retinopathy.


#Files Included
README.md: Overview and instructions for the project.
Blindness_detection.ipynb: Jupyter Notebook containing the code for data preprocessing, model training, evaluation, and deployment.
EDA.ipynb: Jupyter notebook containing the code for dataset visulaizations and EDA.
Credits
ResNet34 architecture: Deep Residual Learning for Image Recognition by Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun.
PyTorch documentation: PyTorch
#License
This project is licensed under the MIT License - see the LICENSE file for details.
