# Text-Classifier

About the project:
This project will discuss a detailed approach of identifying the aspect of user review using Naive Bayes Theorem built from the scratch. Fundamentally, there are numerous options for categorizing Text Data, many of which are excellent at offering high levels of accuracy. However, this project will examine the Naive Bayes implementation of the same from scratch in the current circumstance. The dataset for this is the rotten tomatoes movie review from kaggle contest. The collection has about 480000 items with a class type of either fresh potato or rotten tomato. 

Brief overview of steps followed in the Project:
1. Compute the prior probability of each class c. This is the probability of a randomly selected data point belonging to the class c, without considering any features.
2. Considering each class c, get the probable probability of detecting the traits x. This is the likelihood that the data point will include the features x if it is a member of class c.
3. Compute the evidence probability P(x), which is the probability of observing the features x. This probability can be computed by summing the product of the prior probability and the likelihood probability for each class.
4. Choose the class with the highest posterior probability as the predicted class for the data point.

Installation Instructions: 
This does not require any specifi installations as the project is built over colab. However there are some libraries that need to be included for this project. Most of them are the basic libraries such as 'numpy' and 'pandas' which are a must include in every Machine Learning project. We need another 'nltk' for natural language processing in this project.

How to run the project:
Open Google Colab in your web browser and sign in using your Google account.
Pull the code from the repository to your colab or you can directly click on 'https://github.com/mayukhathumiki876/Text-Classifier/blob/affc9b4a955bde06755cbd34a5400b3e9afa0ad1/Text_Classifier.ipynb' link for code. This is a view only notebook and you will have to create a copy of it in your local drive for editing.
Select a runtime type by clicking on "Runtime" in the top menu, then change to "GPU" for running faster.
Download the dataset from 'https://www.kaggle.com/datasets/ulrikthygepedersen/rotten-tomatoes-reviews?resource=download' and upload it the drive.
Access the dataset from the drive by mounting it.
Rest of the instructions include running every code snippet and get the output.

Additional Information: 
This deals with a bulky dataset of size approximately 480000 reviews. Thus it is recommended that one uses high RAM and faster runtime hardware for computation.
