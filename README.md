# DSProject-InProgress-Advertising



# Which Customer Will Click On The Ad Campaign: Predicting A Profit Of Nearly 20,000$

The task is to predict who will most likely click on the ad. Let's consider that a marketing company is asking for our insight on whether their ad campaign is generating profit or not. Firstly, we have to understand what constitutes a profit and a loss.

### The Buisness Premise
Let's assume that the marketing company spends 1000$ per potential customer which they believed will click on the ad. For each customer that is targeted with the ad campaign and that clicks on the ad, an overall profit of 100$ is estimated. However, if a targeted customer ends up not clicking on the ad, the company loses 1050$. Therefore we can conclude that for each customer that was not targeted by the ad campaign and who clicks on the ad, an overall profit of 1100$ is recorded for the company. 

### Using Logistic Regression To Maximize the Revenue And Minimize The Loss
After exlploring the data, my analysis brought me to the conclusion that the following features are good predictors of whether a customer will click or not on an ad:
- Daily Time Spent on site
- Daily Internet Usage
- Age
- Country
- Area income

Furthermore after adjusting our threshold to minimize the prediction that a customer will click on the ad, while he/she will not in reality, our model predicts that for the next 200 customers, **we would make a profit of 19,000$**. That corresponds to  ratio of 96$/customer considering that our sample is representative of the general population.

### Actionable Recommendations
According to our model, we can identify potential clients by getting information about users on the features identified previously.

By getting this information, the marketing company can target new customers with their ad campaign to maximize the chance of a return on investment. We can speculate that the level of education could correlate with these findings since it was been previously reported that income correlates with the level of education. So the targeted population should be customers with:

- Lower income
- Spending less time on the website
- Spending less time on the internet
- Who are older than our average sample (mean around 40 years old)

Also by increasing our threshold from our model, we can minimize the false positives (e.g., minimizing loss) which optimizes our business approach.
