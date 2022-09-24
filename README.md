Image Classification is the task of assigning an input image, one label from a fixed set of categories.
In this problem, I have used Alexnet architecture to train and classify 7 categories of fruits.

Alexnet is Deep Learning Model Architecture developed by Alex Krizhevsky. 

Alexnet architecture has eight layers including five convolutional layers followed by three fully connected layers. some of the layers are followed by MaxPooling layer. Relu activation function is used based on it's performance. The network consists of a kernel or filters with size 11 x 11, 5 x 5, 3 x 3, 3 x 3 and 3 x 3 for its five convolutional layers respectively. The rest of the parameters of the network can be tuned depending on the training performances. 

Below are the list of steps used in this problem:
1. Exploratory Data Analysis
2. Model Defination Using Alexnet Architecture
3. Image Augmentation
4. Callback Lists
5. Model Training
6. Learning Curves
7. Predictions on Sample Images
