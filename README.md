# ADA511 Course Project: Yahtzee 

By: Ole A. Solem & Henrik Vallestad 

 

* We have limited our project to only the **first part of Yahtzee**, where the goal is to get as many of each kind **[1, 2, 3, 4, 5, 6] ** and then sum them up. 

* If the **sum** of [1s, 2s, 3s, 4s, 5s, 6s] is 63, the agent gets a **bonus of 50 points**.  

* Also, if the agent gets 5 of a kind, **Yahtzee**, it gets 50 points (which **do not** count on the 63-bonus, but it adds to the total score) 

* We run **400 000** games for each scenario, this will give us enough data to accurately compare them. 

 

We have programmed four different scenarios: 

 

1. **Greedy Algorithm**: Always keeps the highest value. 

2. **Strategy with Three of a Kind**: Incorporates a strategy where we try to always get three of a kind and use probability inference to decide whether to keep multiple or discard. 

3. **Keep or Discard**: Performs probability inference on possible scenarios of [Keep or discard] for all the dice and always uses the one that yields the highest probability. 

4. **Probability Distribution and Utility Calculation**: Calculates the probability distribution for each of the dice sides, then multiplies the probabilities with its corresponding dice to get the corresponding utility. The algorithm then picks the one that yields the highest utility. 

 

## Project in the file Yahtzee_Notebook.ipynb 
