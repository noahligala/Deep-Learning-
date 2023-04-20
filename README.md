# Deep-Learning-
using machine learning to train on detection of crop diseases
This is submitted as a fulfilment for an undergratuate research paper to Moi University Department of Science and Aerospace Studies
For a Bachelors in Science Computer Science
All the initial Data is from Kaggle 
I use 80% for training and 20% for prediction and checking effeciency

# Problem Statement.
Agriculture being the back bone of our economy it is primal to most local industry that focus on agricultural produce, as such any threat to the agricultural processes is a direct threat to our economy. 
In clear sight is also the fact that traditional models of farming have reached the peak curve and are no linger able to increase the yield,
despite increase in input. 

Additionally
Crop disease is a major threat to global food security, with an estimated 20-40% of global crop yields lost annually due to plant diseases. Traditional methods of crop disease detection involve visual inspection by trained agronomists, which is time-consuming, labor-intensive, and prone to human error. To address this issue, a deep learning project can be developed to automate the process of crop disease detection using image analysis techniques. The project will aim to develop a model that can accurately classify images of crops as healthy or diseased, and identify the specific disease affecting the plant. The model will be trained on a large dataset of images of healthy and diseased crops, and will be evaluated on its ability to accurately identify the presence and type of disease in new images. The goal of this project is to provide farmers and agronomists with a tool that can quickly and accurately detect crop diseases, allowing for early intervention and reducing the risk of crop loss.

In this Projest I try to make this accessible to the farmers through an API that accepts images and returns a response with details of the plant type and disease detected and later on provide various solutions and drugs to counter the disease.

# DATA COLLECTION
there exists several datasets that will be used for this machine learning I make use of kaggle crop diseases datasets.
The data majorly consists of images of different crop diseases.
# DATA CLEANING AND PROCESSING
One of the challenging task is data cleaning fortunately we will have most of the data already cleaned and we will in this project assume that all data supplied is credible and useful.

For Processing the data we will try different CNN algorithms to see which will give us the best and shortest learning curve.

#CHALLENGES
The data collected appears to have some noise especially dark pictures and despite augmetinting the data to increase the training sample I still have a challenge with the training of the model.

#MODEL TRAINING
There are a plethora of methods to train a model especially a CNN model however most of the models still remain a probability scenario depending on trial and error as there is no predetermined diraction that changes the learning curve adversely or in the direction required it is a change of parameters with the hope that the model will learn as much from the data
