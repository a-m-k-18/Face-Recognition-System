# Face Recognition System
 - Used MTCNN for face detection
 - FaceNet Model is used to create a face embedding for each detected face.
 - Developed a Linear Support Vector Machine for face classification

# Pre-processing
 - Face alignment using MTCNN
 - Detect face and store it as dataset.npz
 - Create face-embedding for all the images from dataset.npz and store it in embeddings.npz

# Running 
 - Add your photos(>10) in a folder with your name and store it in dataset/train and dataset/val(Use different pictures , since this is used for testing)
 - Run facedetect.py and faceemebed.py to create face-embeddings and run classify to get the result.

# Output

![Screenshot](screenshot.PNG)

# Accuracy
- Next, the model is evaluated on the train and test dataset, showing perfect classification accuracy. This is not surprising given the size of the dataset and the power of the face detection and face recognition models used.
- Dataset: train=103, test=29
Accuracy: train=100.000, test=100.000
