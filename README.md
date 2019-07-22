# Image-classification-using-SVM

Classifying images of dogs, cats, horses and humans using Support Vector Machine

Our brains make vision seem easy. It doesn't take any effort for humans to tell apart a lion and a jaguar, read a sign, or recognize a human's face. But these are actually hard problems to solve with a computer: they only seem easy because our brains are incredibly good at understanding images.

### Problem Statement
Given a DataSet of Images of cats, dogs, horses and humans, Your job is to prepare a classifier that can classify given image and predicts its class.

### DataSet
    Dataset contains 4 folders named as cats, dogs, humans and horses in which images for each category is saved. The images can be of different size so we need to reshape all of the images to one std size.
    Dataset is attached in the repo and do save the dataset in the same folder as that of the code otherwise you need to change the directory of the path in the code to load images from it.

### Classifier
The classifier used is of Support vector Machine and I have used One-Vs-One scheme to perform classification between multiple Classes.
