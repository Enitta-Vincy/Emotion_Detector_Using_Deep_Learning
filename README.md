**Emotion Detector**
A deep learning-based project for real-time emotion detection from facial expressions using OpenCV, TensorFlow/Keras, and CNNs. This project recognizes seven basic human emotions from facial images.

**Features**
>Detects emotions from facial expressions in real-time using webcam or image input.
>Trained on the FER-2013 (Facial Expression Recognition) dataset.
>Uses Convolutional Neural Networks (CNNs) for classification.
>Clean preprocessing pipeline with face detection using Haar cascades.
>Simple interface for testing and predictions.

**Detected Emotions**
😃 Happy
😢 Sad
😠 Angry
😮 Surprise
😐 Neutral
😨 Fear
😖 Disgust

**Tools & Libraries Used**
Python 3.x
TensorFlow / Keras
OpenCV
NumPy
Matplotlib
Seaborn
Scikit-learn

**Dataset**
**FER-2013:** The Facial Expression Recognition 2013 dataset, available from Kaggle.
Contains grayscale 48x48 pixel face images categorized into 7 emotion classes.

 **Model Architecture**
*A CNN model with multiple convolutional and max-pooling layers.
*Followed by Dropout layers to prevent overfitting.
*Final dense layers for classification using softmax activation.
*Optimized using categorical crossentropy and the Adam optimizer.




