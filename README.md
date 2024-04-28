# Safari-Animal-Image-Classification

This project is one of the challenges in the online courses of Microsoft Azure Data Scientist Associate on Coursera.<br />

Goal: <br />
To create a convolution neural network for classifying different animal images.<br />

Dataset: <br />
From Microsoft and it is a simple dataset with only four types of animals.<br />

Process:
- Review the images.
- Transform the images to tensor and perform normalization.
- Split the data for training and testing and load them to DataLoader.
- Build three convolution layers to extract features, followed by pooling layer and ReLu activation function.
- Drop some features to avoid overfitting.
- Evaluate the model with confusion matrix.
- Use the model to predict unseen images in the testing folder.
- These are implemented in both PyTorch and Tensorflow.
