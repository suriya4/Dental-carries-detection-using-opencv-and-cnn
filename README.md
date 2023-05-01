# Dental-carries-detection-using-opencv-and-cnn
This project aims to develop a computer vision system to detect dental caries (also known as tooth decay) in dental X-ray images. The system is implemented using convolutional neural networks (CNN) and the OpenCV library.
#Dataset
The dataset used in this project is a collection of dental X-ray images with annotations indicating the presence or absence of caries. The dataset is split into training, validation, and testing sets.

#CNN Model
The CNN model used in this project consists of several convolutional and pooling layers followed by a fully connected layer and an output layer. The model is trained on the training set using the Adam optimizer and binary cross-entropy loss. The model is evaluated on the validation set to monitor its performance and prevent overfitting.

#OpenCV Implementation
The OpenCV library is used to preprocess the X-ray images and extract relevant features for the CNN model. The preprocessing steps include contrast stretching, histogram equalization, and noise reduction. The features are then normalized and fed into the CNN model for classification.

#Results
The performance of the dental caries detection system is evaluated on the testing set using metrics such as accuracy, precision, recall, and F1-score. The results show that the system achieves high accuracy and can effectively detect dental caries in X-ray images.

#Usage
The code for this project is available on GitHub and can be used to train and test the dental caries detection system on new datasets. The dataset used in this project is not publicly available due to privacy concerns.

#Dependencies
The following Python libraries are required to run this project:

#TensorFlow
Keras
OpenCV
NumPy

