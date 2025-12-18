
MNIST DIGIT RECOGNITION USING NEURAL NETWORK
===========================================

Project Description
-------------------
This project implements a handwritten digit recognition system using a Neural Network
trained on the MNIST dataset. The trained model can classify digits (0–9) and also
predict the digit from a custom image uploaded to Google Drive.

The project is fully compatible with Google Colab and is organized in a clear,
part-wise manner for learning, exams, and project submission.

Dataset
-------
Dataset Name : MNIST Handwritten Digits
Source       : TensorFlow / Keras built-in dataset
Details      :
- 60,000 training images
- 10,000 testing images
- Image size: 28 x 28 (grayscale)
- Classes   : Digits from 0 to 9

Technologies Used
-----------------
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- Google Colab
- Google Drive

Project Structure
-----------------
MNIST_Digit_Recognition_Colab.ipynb   -> Main notebook
README.txt                            -> Project documentation

Model Architecture
------------------
1. Flatten Layer (28x28 input)
2. Dense Layer (128 neurons, ReLU)
3. Dense Layer (64 neurons, ReLU)
4. Output Layer (10 neurons, Softmax)

Loss Function : Sparse Categorical Crossentropy
Optimizer    : Adam
Metric       : Accuracy

How to Run the Project (Google Colab)
------------------------------------
1. Open Google Colab
2. Upload the file: MNIST_Digit_Recognition_Colab.ipynb
3. Run all cells sequentially
4. Allow Google Drive access when prompted
5. Upload a handwritten digit image to Google Drive
6. Update the image path in PART 10
7. Run the prediction cell to get the digit

Input Image Requirements
------------------------
- Image must contain a single handwritten digit
- Prefer white digit on black background (MNIST style)
- Any image size (automatically resized to 28x28)
- Supported formats: PNG, JPG, JPEG

If the digit is black on white background, invert colors using:
img = 1 - img

Output
------
- Predicted digit (0–9)
- Visualization of the input image with predicted label
- Test accuracy of approximately 97–98%

Applications
------------
- Handwritten digit recognition
- Bank cheque processing
- Postal code recognition
- OCR preprocessing systems
- Learning Neural Networks fundamentals

Future Enhancements
-------------------
- Use Convolutional Neural Networks (CNN)
- Real-time digit recognition using camera
- Extend to EMNIST (digits + letters)
- Deploy using Flask or FastAPI
- Improve robustness using data augmentation

Author
------
Project developed for academic and learning purposes by Bukke Sunitha.

License
-------

This project is free to use for educational and non-commercial purposes.
