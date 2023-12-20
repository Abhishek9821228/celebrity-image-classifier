
# Celebrity Image Classifier


Celebrity Image Classifier:
This Code contains a Python script for classifying celebrity images based on facial features. The classifier utilizes face and eye detection techniques, image preprocessing, and machine learning to identify celebrities. The code uses the OpenCV library for image processing and scikit-learn for machine learning.

### Prerequisites

- Python (3.x recommended)
- OpenCV
- scikit-learn
- NumPy
- Matplotlib
- Seaborn
- PyWavelets

### Usage

- Step 1:  Detecting Faces and Eyes
The initial steps involve face and eye detection in an image. The script uses Haar cascades for face and eye detection.

- Step 2: Preprocessing Images
Then code provides a function to crop images if two eyes are detected. This function is then used to preprocess the dataset.

- Step 3: Feature Extraction
Wavelet transformation is applied to images to extract features related to facial characteristics.

- Step 4: Model Training
Then we trains a Support Vector Machine (SVM) model using scikit-learn. It also includes an option to explore different models and hyperparameters using GridSearch.

- Step 5: Model Comparison
Then we did compare different models.
