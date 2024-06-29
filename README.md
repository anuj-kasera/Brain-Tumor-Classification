# Brain-Tumor-Classification

<h2>Overview</h2>

This project utilizes transfer learning with the Xception model pretrained on ImageNet to classify brain tumor MRI images into multiple classes. It achieves high accuracy through fine-tuning and augmentation techniques.

<h2>Dataset</h2>

**Source:** (https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data)

<h2>Model Training</h2>

**Architecture:** Xception model with additional layers for classification.

**Optimizer:** Adamax optimizer with a learning rate of 0.001.

**Loss Function:** Categorical cross-entropy.

**Training:** Trained for 10 epochs with early stopping based on validation loss.

<h2>Evaluation</h2>

**Metrics:** Displayed accuracy, precision, recall, and F1-score on the test set.

**Confusion Matrix:** Visualized confusion matrix to assess model performance.

<h2>Results</h2>

**Train Loss: 0.0028**

**Train Accuracy: 0.999**


**Validation Loss: 0.0598**

**Validation Accuracy: 0.989**


**Test Loss: 0.0258**

**Test Accuracy: 0.990**
