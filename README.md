# Face-Recognition-Project
This project demonstrates a pipeline for face recognition using Principal Component Analysis (PCA) for dimensionality reduction and Support Vector Machines (SVM) for classification. It utilizes the Labeled Faces in the Wild (LFW) dataset to predict the names of individuals based on their facial images.

Features
 > Implements PCA for feature extraction and data whitening.

 >  Uses SVM with an RBF kernel and hyperparameter tuning via grid search.

 > Visualizes predicted labels, with incorrect predictions highlighted in red.

 > Generates a classification report and confusion matrix for detailed analysis.

Workflow and Methodology

1. Data Acquisition
The Labeled Faces in the Wild (LFW) dataset consists of grayscale images of various individuals. The dataset is preprocessed to include only individuals with a minimum number of images.

2. PCA for Dimensionality Reduction
PCA is applied to the data to reduce its dimensions from thousands of pixels to 150 principal components. Whitening is used to normalize the variance across the components, enhancing performance.

3. SVM Training
An SVM classifier is trained on the reduced-dimensional feature set. Hyperparameters C (controls regularization) and gamma (controls the RBF kernel width) are fine-tuned using grid search.

4. Model Evaluation
The trained model is tested on a holdout set:
Predictions are visualized, with incorrect labels shown in red for easier interpretation.
A confusion matrix is generated to assess classification performance per class.
Precision, recall, and F1-scores are calculated for each category.

#Output:

![{8839A1EC-D970-4603-A305-A2A228CD9B90}](https://github.com/user-attachments/assets/2b68f79f-925f-4db5-84bf-100c61466b07)



![{5B70BFEF-1DCE-42A7-B1EF-D459717CED3F}](https://github.com/user-attachments/assets/26520882-ef18-407b-87d6-cb2358de283f)




Results:
Accuracy: Achieves an overall accuracy of 84% on the test set.
Detailed Metrics: Precision, recall, and F1-score for each class are provided.
Confusion Matrix: A heatmap representation of the true vs. predicted labels.

Contributing
Feel free to fork the repository and submit pull requests for improvements or bug fixes.
