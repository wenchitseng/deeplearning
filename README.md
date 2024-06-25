# Fruits fresh and rotten for classification
This coursework uses TensorFlow to determine whether a fruit in an image is fresh or rotten.

### 🔗 Data Source: 
https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification/data

### 🔍 Introduction:
This Deep Learning application aims to **improve quality control in the food, e-commerce, and retail industries**. By training models to classify fruit conditions, fresh or rotten, businesses can ensure better product quality, reduce waste, and enhance customer satisfaction. This application has potential in retail and supply chain environments, optimizing the sorting process and potentially decreasing the labor costs associated with manual inspection. 

Firstly, we used Random Search to optimize hyperparameters, including the number of nodes in different layers and the learning rate. We then trained various optimization algorithms, such as **Adam, Adadelta, SGD, and RMSprop**, as our benchmark models. Further, we implemented several techniques to enhance the model's performance and avoid overfitting, including **early stopping, adjusting the dropout rate, and varying weight initialization** strategies. Ultimately, the Adadelta model with Batch Normalization achieved a 92.06% accuracy on the testing data.
