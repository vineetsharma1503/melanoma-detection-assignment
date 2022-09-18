# Project Name
> 
melanoma-detection-assignment (Using CNN without transfer learning)

## Table of Contents
* [General Info](# Convolutional Neural Network Model using trained to identify melanoma (a type of skin cancer) by feeding image of the skin lesion
* [Technologies Used](# Python, Pandas, Matplotlib, Keras API & Tenserflow )
* [Conclusions](# We have created a neural network which is working good for 9 class classification problem)
* [Acknowledgements](# stackoverflow)


## General Information
Convolutional neural network Model to classify a given input image into one of the 9 categories. These are close-up shots of lesions on skin of different patients.
One of these classes is Melanoma which is a cancer and is fatal if not detected early on.
Using the model medical practitioners will save time in identify if a lesion is malenoma or not.



## Conclusions
- The model is having a accuracy of 95% on train data and 82% on validation data set.
- We used 50 epochs to train data with batch size 32. However the optimum results were reached in about 15 epochs and we could have used an early stopping.
- Loss function used is SparseCategoricalCrossentropy, Optimizer is adam and accuracy was used as metric
- seborrheic keratosis class has the least number of samples
- melanoma, pigmented benign keratosis and basal cell carcinoma classes dominate the data in terms proportionate number of samples

![index](https://user-images.githubusercontent.com/102841813/190917278-228ea95d-ef92-4122-bb2a-98b7950d0eaf.png)

## Technologies Used
- Python - version 3.0
- Jupyter Lab - version 3.2.1
- Keras API and Tenserflow
- Matplotlib for visualization



## Contact
Created by [@vineetsharma1503] - feel free to contact me!
