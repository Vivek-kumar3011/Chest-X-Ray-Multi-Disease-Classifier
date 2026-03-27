# Chest-X-Ray-Multi-Disease-Classifier

What is the problem?
This competition involves multi-class classification of chest X-ray images into 20 diagnostic categories. Given a chest X-ray image, the model must predict exactly one condition from the 20 possible classes including diseases such as Atelectasis, Cardiomegaly, Effusion, Pneumonia, and a "No Finding" class indicating a healthy scan.

Why is it important?
Automated chest X-ray diagnosis is a critical problem in healthcare. Radiologists are often overwhelmed with large volumes of scans, and an accurate automated system can assist in prioritizing urgent cases, reducing diagnostic errors, and improving patient outcomes especially in resource-limited settings.

What is the dataset?
The dataset consists of chest X-ray images in PNG format with the following structure:

Training set: 51,043 images with 20 binary label columns (one-hot encoded)
Test set: 17,015 images (labels hidden)
Image format: PNG, grayscale converted to RGB
Label type: Single-label multi-class (exactly one condition per image)
The 20 classes are: Atelectasis, Cardiomegaly, Consolidation, Edema, Effusion, Emphysema, Fibrosis, Hernia, Infiltration, Mass, Nodule, Pleural Thickening, Pneumonia, Pneumothorax, Pneumoperitoneum, Pneumomediastinum, Subcutaneous Emphysema, Tortuous Aorta, Calcification of the Aorta, and No Finding.


Kaggle Competition: https://www.kaggle.com/competitions/26-t-1-dl-gen-ainppe-1
