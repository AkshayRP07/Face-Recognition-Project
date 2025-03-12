# Face-Recognition-ProjectFace Recognition Using PCA and SVM
This project demonstrates a pipeline for face recognition using Principal Component Analysis (PCA) for dimensionality reduction and Support Vector Machines (SVM) for classification. It utilizes the Labeled Faces in the Wild (LFW) dataset to predict the names of individuals based on their facial images.

Features
 > Implements PCA for feature extraction and data whitening.

 >  Uses SVM with an RBF kernel and hyperparameter tuning via grid search.

 > Visualizes predicted labels, with incorrect predictions highlighted in red.

 > Generates a classification report and confusion matrix for detailed analysis.

Installation
Clone this repository:

bash
git clone <repository_url>
Install the required Python libraries:

bash
pip install numpy matplotlib seaborn scikit-learn
Usage
Run the script to train the SVM model and make predictions:

bash
python <script_name>.py
Explore the visualization of predicted names and the classification metrics.

Results:
Accuracy: Achieves an overall accuracy of 84% on the test set.
Detailed Metrics: Precision, recall, and F1-score for each class are provided.
Confusion Matrix: A heatmap representation of the true vs. predicted labels.

Contributing
Feel free to fork the repository and submit pull requests for improvements or bug fixes.
