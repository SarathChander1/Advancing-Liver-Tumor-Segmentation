# Advancing-Liver-Tumor-Segmentation
This project employs a deep learning model for semantic segmentation of MRI scan images, utilizing a custom neural network with attention mechanisms and Dice Cross-Entropy loss for better handling of imbalanced data. The model is trained to classify each pixel in an image, distinguishing between background and object (e.g., tumors or lesions).

Key components of the project:

Data Processing: Loads, preprocesses, and normalizes MRI scans for training and evaluation.
Model Architecture: Uses a convolutional neural network (ConvNet) with attention mechanisms for improved performance on medical images.
Loss Function: Combines Dice loss and Cross-Entropy loss to handle both pixel-wise accuracy and class imbalance.
Visualization: Visualizes input images, segmentation outputs, and ground truth to assess model performance.
Model Evaluation: Computes key metrics such as Dice score, Precision, Recall, F1-Score, and Confusion Matrix.
