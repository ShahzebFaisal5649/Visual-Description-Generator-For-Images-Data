# Visual Description Generator for Images Data

This project aims to generate textual descriptions for images using deep learning techniques. The system takes an image as input and outputs a textual description describing the content of the image.

# Dependencies:
python 3.10.13
keras 3.2.1
tensorflow 2.15.0
rarfile
matplotlib
numpy
pandas
scikit-learn

# Installation:
!pip install rarfile matplotlib numpy pandas scikit-learn

# Usage:
1. Import Required Libraries: Before running the code, ensure all the required libraries are installed. This includes TensorFlow, Keras, Matplotlib, NumPy, Pandas, and scikit-learn.
2. Import Dataset: Import the ImageDS dataset along with its captions. The dataset is assumed to be in the RAR format and is extracted to the desired directory.
3. Display Images and Captions: Display images and their corresponding captions from the dataset for visualization.
4. Clean Captions: Clean the captions by removing punctuation, single characters, and numeric values to prepare them for further analysis and processing.
5. Visualize Top Words: Visualize the top words in the cleaned dataset to gain insights into the vocabulary distribution.6. Add Start and 6. End Sequence Tokens: Add start and end sequence tokens to each caption to mark the beginning and end of the sequence.
7. Feature Extraction: Extract features from images using the pre-trained VGG-16 model to prepare them for further processing.
8. Plot Similar Images: Plot similar images from the dataset by clustering them based on their features obtained from VGG-16.
9. Merge Images and Captions: Merge images and captions for training the model.
10. Tokenize Captions: Tokenize the captions to convert them into vectors for model input.
11. Split Training and Test Data: Split the dataset into training, validation, and test sets for model evaluation.
12. Building the LSTM Model: Build the LSTM model for training to generate captions for images.
13. Training the Model: Train the LSTM model using the prepared dataset and evaluate its performance.
14. Generating Captions: Generate captions for a small set of images to test the model's performance.

# Contributors:
Shahzeb Faisal

Haris Amjad
