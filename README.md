# DSProject-InProgress-Advertising



# Which Customer Will Click On The Ad Campaign: Predicting A Profit Of Nearly 20,000$

The task is to predict who will most likely click on the ad. Let's consider that a marketing company is asking for our insight on whether their ad campaign is generating profit or not. Firstly, we have to understand what constitutes a profit and a loss.

### The Buisness Premise
Let's assume that the marketing company spends 1000$ per potential customer which they believed will click on the ad. For each customer that is targeted with the ad campaign and that clicks on the ad, an overall profit of 100$ is estimated. However, if a targeted customer ends up not clicking on the ad, the company loses 1050$. Therefore we can conclude that for each customer that was not targeted by the ad campaign and who clicks on the ad, an overall profit of 1100$ is recorded for the company. 

### Using Logistic Regression To Maximize the Revenue And Minimize The Loss
After exlploring the data, we came to the conclusion that 


The name "Pokémon" comes from the contraction of "pocket" and "monster", and was first introduced in 1989 when the first video game was released on the GameBoy. The goal of the game was to collect the different species of Pokemons, and to train some of your creatures in order to compete against other players. The outcome of a fight could be influenced by the characteristics of each Pokemon. In this notebook, we will explore these characteristics as published on the Kaggle. This journey will include two parts:

    An exploration of the data
    A prediction of who will win their next match

Exploration Of The Data

In the first section, we will explore the characteristics of the different Pokemons and perform data analysis in order to extract specific information about this sample. Furthermore, we will perform feature engineering which will be extremely useful in the second part where we will perform machine learning in order to predict the potential winner for each fight. This first section was done using R.
Prediction Of The Next Winner

In this section, we tested several algorithms, including Logistic Regression, K-Nearest Neighbors, and Random Forest to name a few. Our Random Forest ended up being the one which perform the best with a striking 99% accuracy on our validation set. This second section was accomplished using scikit-learn in Python.
