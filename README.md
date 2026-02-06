The model uses a Convolutional Neural Network with a pre-trained ResNet50 architecture to extract robust facial features that are not affected by age variations.

Objectives
To develop a face recognition system independent of age changes
To extract deep facial features using transfer learning
To improve recognition accuracy across different age groups

Technologies Used
Python
TensorFlow
Keras
OpenCV
NumPy
Scikit-learn
Jupyter Notebook

Dataset Description

The dataset consists of facial images of individuals at different ages

Images are organized in folders based on person identity
Images are resized and normalized before training

Methodology
Load face image dataset
Preprocess images by resizing and normalization
Encode class labels
Split data into training and testing sets
Use ResNet50 as a feature extractor
Train the CNN model
Evaluate model performance

System Features
Age invariant face recognition
Deep feature extraction using ResNet50
Accurate identification across age differences
Efficient image preprocessing
How to Run the Project


Install required Python libraries
Open the Jupyter Notebook file
Update the dataset path
Run all cells sequentially

Results
The system successfully recognizes individuals across different age variations, proving its effectiveness as an age invariant face recognition system.

Applications
Biometric authentication
Security and surveillance systems
Law enforcement investigation
Identity verification systems

Future Enhancements
Train with larger and more diverse datasets
Improve accuracy using advanced deep learning models
Deploy the system as a web or mobile application
