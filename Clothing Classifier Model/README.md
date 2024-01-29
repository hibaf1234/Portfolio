# Fashion Forward E-Commerce Clothing Classifier

**Project Overview**

Welcome to the Fashion Forward E-Commerce Clothing Classifier project! In this endeavor, we aim to revolutionize the fashion and retail industry by developing an innovative garment classification system. Our goal is to create a smarter, more efficient, and user-friendly shopping experience, leveraging cutting-edge AI and machine learning techniques.

**Objective**

As a data scientist, the primary objective is to implement a garment classifier that automates the categorization of clothing items for Fashion Forward, a new AI-based e-commerce clothing retailer. The classifier will assist in automatically categorizing new product listings, making it easier for customers to find their desired items and facilitating efficient inventory management.

**Technical Details**
To achieve this, we will define a Convolutional Neural Network (CNN) classifier with specific layers, including convolutional layers, RectiLinear unit activation layers, max pooling layers, and fully connected layers. The model will be trained on the FashionMNIST dataset, a collection of grayscale images representing various clothing types.

**Implementation Steps**
1) Define the CNN classifier with the specified layers.
2) Train the CNN on the provided train_data using a suitable optimizer.
3) Limit the training loop to 1 or 2 epochs to optimize run time.
4) Test the CNN on the provided test_data and store predictions in a list called predictions.
5) Calculate accuracy, per-class precision, and recall for the trained classifier on the test data.
6) Store the results in variables accuracy, precision, and recall respectively, using lists of appropriate length for precision and recall.
