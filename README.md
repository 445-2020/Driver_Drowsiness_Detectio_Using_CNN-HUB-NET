# Driver Fatigue Detection Using CNN (HUB-NET)
This project uses a convolutional neural network (CNN) to detect driver drowsiness. The CNN is trained on a dataset of 85,000 eye images, which are provided in the mrl_eye_data.npz file. The images are resized to 64x64 pixels.
The CNN is trained using a 67/33 train-test split. The model achieves an accuracy of 98.48% on the test set.
A real-time application is also implemented. The application uses a Haar cascade algorithm to detect faces and eyes in real-time. The detected eyes are then passed to the trained CNN model for classification.
