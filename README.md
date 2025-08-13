# PRODIGY_ML_04
✋ Task 04 – Hand Gesture Recognition Model
Prodigy Infotech – Machine Learning Internship

🎯 Objective
Develop a machine learning model to accurately identify and classify hand gestures from grayscale images using a supervised learning approach (SVM). This project simulates intuitive gesture-based control systems.

📁 Dataset
Name: gesture_small
Description: Grayscale images representing multiple hand gestures.
Structure: All images stored in a single folder, filenames are labeled like 1(9)_S.jpg, 2(4)_S.jpg, etc., where the digit before the ( indicates the class.
📌 Sample filename: 3(12)_S.jpg → Class label = 3

🧰 Tools & Libraries
Python 🐍
NumPy
OpenCV
scikit-learn (SVM classifier)
matplotlib
🛠️ Steps Performed
1. Data Loading & Preprocessing
Read all image files from a single directory.
Resize each image to 64×64 pixels.
Convert each image to grayscale.
Extract class labels from filenames.
2. Data Splitting
Split the data into training (80%) and testing (20%) sets using train_test_split.
3. Model Training
Used Support Vector Machine (SVM) with an RBF kernel to train the model on the gesture images.
4. Evaluation
Calculated accuracy score and classification report.
Visualized actual vs predicted results using matplotlib.
📊 Sample Results
✅ Accuracy: ~90% (varies based on dataset size & balance)
✅ Classification Report: Shows precision, recall, F1-score for each gesture class.
✅ Visualization: Side-by-side comparison of actual and predicted gestures in color-coded plots.
🖼️ Output Visualization
Correct predictions are shown in green.
Incorrect predictions are shown in red.
📎 gesture_predictions.png is saved for reference.

🚀 Future Improvements
Switch to CNN (Convolutional Neural Network) for better accuracy on larger datasets.
Apply data augmentation (rotation, scaling) to handle variation.
Build a real-time gesture recognition app using a webcam.
