CNN-Based Medical Image Classification (X-Ray / TB Detection)

Overview
This project uses a Convolutional Neural Network (CNN) to classify medical X-ray images for disease detection such as Tuberculosis or normal vs abnormal cases. The model is trained on chest X-ray images and learns important features for accurate classification.

The goal is to build a deep learning-based system that can assist in early medical diagnosis.

Features
- Image preprocessing and augmentation
- CNN model built using TensorFlow/Keras
- Training and validation accuracy tracking
- Model evaluation using accuracy and loss metrics
- Prediction on new X-ray images
- Visualization of training performance (accuracy/loss graphs)

Project Structure
Project-Medical Imaging/
- Data               : Contains Raw and Processed Data of chest Xrays
- Data/Raw           : 2 files consisting of 3500 Normal chest Xrays and 700 TB infected Chest xrays
- Data/Processed     : Raw data is divided into TRAIN , VALIDATION , TEST , a 70-15-15 split for each TB and Normal Data
- Plots              : Consists of graphical plots made using data
- Logs               : It contains saved baseline models
- Checkpoints        : baseline model saved as a .h5 file 
- README.md          : Project documentation

Model Architecture
The CNN model consists of:
- Convolutional layers for feature extraction
- MaxPooling layers for downsampling
- Dropout layers to reduce overfitting
- Fully connected dense layers
- Output layer with sigmoid/softmax activation for classification

Installation

Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn

Future Improvements
- Use transfer learning (ResNet, VGG16) for better accuracy
- Deploy model using Flask or Streamlit
- Build a web interface for image upload and prediction
- Train on larger and more diverse datasets

Disclaimer
This project is for educational purposes only and should not be used as a medical diagnostic tool.

Author
Tushar Dey
B.Sc. Applied Statistics and Analytics
