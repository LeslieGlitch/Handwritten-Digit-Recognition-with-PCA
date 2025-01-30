# Handwritten Digit Recognition with PCA

A PCA machine learning model written in Python to recognize handwritten digits in real time. I utilized the Scikit-Learn library for training the model. Training/testing data comes from the MNIST handwritten digits dataset. 60,000 images were used in training, and a sample of 10,000 images were used for testing.
Model correctly identified 94.23% of the testing images. I also implemented a window for real-time digit recognition where a user can write a digit and receive a prediction.

-----
A sample of the images from the training dataset

![PCA_sample](https://github.com/user-attachments/assets/f5a5e837-1223-4561-8fa9-0837dae93290)
-----
The eigenfaces orthagonal to the 10 most useful eigenvectors after reducing dimensionality with PCA. Eigenvectors were limited to 10 to match the number of potential outputs (0-9).

![PCA_eigenfaces](https://github.com/user-attachments/assets/2d9cccdd-4733-40dc-8be9-4a878b284524)
-----
A confusion matrix displaying the results of testing. 10,000 images were tested, with 9,423 being correctly labelled. These correct labels are shown as the green/yellow diagonal across the grid, while the purple spaces represent incorrect labels.

![PCA_results](https://github.com/user-attachments/assets/955e99d6-dfbd-4783-b8f6-0cffd6306aca)
