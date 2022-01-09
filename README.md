# Neural_Networks


# Overview of the analysis: Explain the purpose of this analysis.

We will be working with Beks to showcase our skills using neural networks to help assist Beks foundation predict where to make investments. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively

Our Goal is to preprocess our data for our neural network model. We will compile our data and optimze it to best fit our model to make our predictions.


# Results:
o Data Preprocessing read in our CSV

![image](https://user-images.githubusercontent.com/88467263/148705133-974f75f6-b7e3-46c0-b75d-d88216b87ae5.png)

## Drop the EIN and NAME columns because they are not relevant to our analysis.

<img width="745" alt="nonbenfid" src="https://user-images.githubusercontent.com/88467263/148705158-1f6a16ce-1d8b-4330-8b4b-bc4cfa4fd384.PNG">

* What variable(s) are considered the target(s) for your model?

 The IS_SUCCESSFUL column was our target variable for the deep learning model, as it contains binary data referring to whether or not the charity donation was successful
 
 ![image](https://user-images.githubusercontent.com/88467263/148705343-6fa2a50c-489f-4ef8-9a63-165ea6a7fd75.png)

 
* What variable(s) are considered to be the features for your model?

I used the following columns as features for the model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT

![image](https://user-images.githubusercontent.com/88467263/148705408-e72c0d4e-34f7-4ae0-baae-9d4fe0de9de1.png)





![image](https://user-images.githubusercontent.com/88467263/148705251-d0cfc03d-9502-4b2b-8044-90e1a4eb6323.png)


* What variable(s) are neither targets nor features, and should be removed from the input data?
o Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
* Were you able to achieve the target model performance?
* What steps did you take to try and increase model performance?

![image](https://user-images.githubusercontent.com/88467263/148705444-e0863081-8f02-4dfb-8fca-8180f0e5f388.png)

3. Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

