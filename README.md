# DALI Data Challenge 22X

## Part 1 
![Preliminary Data Visualizations](/part-1/store_x_insights.png)

The visualizations were produced in the following [notebook](part-1/data_challenge_p1.ipynb).


## Part 2
For the data modelling part, I decided showcase some of my machine learning skills. Using the provided sales data, I designed the following three predictive  models using Catboost gradient boosting: 

(1) Given the discount and product ID of a transactions, the first model predicts whether the transaction resulted in a net gain or loss (**~99.8% accuracy**). 

(2) Given the sub-category, U.S. state, and whether a transaction was profitable, the second model predicts the exact discount percentage applied to the transaction (**r-squared of ~0.992**).

(3) Given the postal code, profit, quantity, discount, and shipping time of the transaction, the third model predicts the sub-category of the transaction. This model was a bit more complex, so I used some hyperparameter tuning to ramp up performance. (**~99.6% accuracy**)

My full process and model considerations are detailed in the following [notebook](part-2/data_challenge-p2.ipynb). 