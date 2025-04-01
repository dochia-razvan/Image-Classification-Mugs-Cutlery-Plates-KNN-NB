# Image-Classification-Mugs-Cutlery-Plates-KNN-NB
Classifying images from a dataset containing objects from three categories: mugs, cutlery, and plates. My main goal was to compare the performance of two machine learning algorithms, K-Nearest Neighbors (KNN) and Naive Bayes (NB), to determine which is more suitable for this image classification task. I desired to understand their behavior on visual data. The comparison evaluates performance in terms of accuracy, classification report, confusion matrix, and ROC curves.

The dataset was sourced from Universe Roboflow, containing approximately 1500 images, which were resized to 64x64 pixels to make them compatible with the machine learning models. Images were then flattened into 1D vectors for input into the algorithms.

In terms of accuracy, KNN with 3 neighbors outperformed Naive Bayes, achieving an accuracy of 83%, compared to 72% for Naive Bayes. KNN also demonstrated better precision, recall, and F1-score, particularly for classes like Mugs and Plates. The AUC values for KNN ranged from 0.83 to 0.96, while Naive Bayes performed with AUC values between 0.77 and 0.89. The confusion matrices highlighted that Naive Bayes had more difficulty distinguishing between Plates and other classes, while KNN performed well in class separation. Based on these observations, KNN with n_neighbors=3 is more suitable for this dataset.

A project for the Faculty of Automatic Control and Computers, University Politehnica of Bucharest.
