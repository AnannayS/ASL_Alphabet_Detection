# ASL Alphabet Detection

**Context**:
American Sign Language (ASL) is the most popular standard for sign language in North America. However, it can be tough for those who do not know sign language to communicate with those who cannot communicate easily without it. This project serves as an introduction into the world of using ML to recognize sign language.

**Objective**:
The goal of this project was to create a convolutional neural network to recognize the  ASL alphabet.

**Dataset**:
https://www.kaggle.com/grassknoted/asl-alphabet

Dataset credits: Akash (https://www.kaggle.com/grassknoted)

The dataset contains 87,000 200x200 pixel images; 3000 images for each letter of the alphabet, in addition to space, delete, and nothing. 

**Built With**:
* Pytorch: Used to create CNN
* OpenCV: Used for image processing
* Matplotlib and Seaborn for image visualization

**Results**:
The model achieved an accuracy of 97% after completing 17 epochs.

**Next Steps**:
* Expanding the vocabulary to include common ASL expressions.
* Experimenting with thresholding and other preprocessing techniques to allow the model to learn faster and be more compact.
* Combine with a camera module to allow for real-time translation.
* ”Reversing the translation process, i.e. writing/speech to sign language.
