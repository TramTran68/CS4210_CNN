# CS4210_Perceptron

This Python program (cnn.py) trains and tests a Convolutional Neural Network (CNN) for classifying optically recognized handwritten digits. The dataset used consists of images of handwritten digits, and the CNN model is evaluated based on its performance on the test set. The program handles both training and testing phases, using a convolutional architecture to classify the images and reporting the test accuracy and loss.

## **Training set:**
digit_dataset/train - Directory containing the training images.

## **Test set:**
digit_dataset/test - Directory containing the test images.

## **Requirements**
- Python 3.x  
- tensorflow  
- numpy  
- Pillow (PIL)  
You can install the necessary dependencies using the following command:
pip install tensorflow numpy pillow

## **Usage**
Ensure that the digit_dataset directory with train and test subdirectories is in the same directory as the cnn.py script.  
Run the script: python cnn.py    
The script will:
- Load the images from the train and test directories.
- Preprocess the images (convert to grayscale, resize, and normalize pixel values).
- Build a CNN model using Keras.
- Train the model on the training dataset.
- Evaluate the model on the test dataset.
- Output the test accuracy and test loss.

## **Output**
The program will print the test accuracy and test loss for the CNN model after evaluation:  
Test accuracy: {value}  
Test loss: {value}
