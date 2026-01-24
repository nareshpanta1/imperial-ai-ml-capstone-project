# imperial-ai-ml-capstone-project
Repo for Capstone project as part of Professional Certificate in AI and ML
This is a black-box challenge which consists of eight functions for which we are trying to find the maximum.



# challenge objectives
This is a black-box challenge which consists of eight functions for which we are trying to find the maximum.
Each week we submit one set of input (x)  for each function and we receive the output(y) once the submission is processed.
We then take these input and output and add it to the initial data set and rerun the process again optimising iteratively.

# inputs and outputs (data)
|Function   | Input  | Output  |
|---|---|---|
|Function 1  | 2D array  | 1D array  |
|Function 2  | 2D array  | 1D array  |
|Function 3  | 3D array  | 1D array  |
|Function 4  | 4D array  | 1D array  |
|Function 5  | 4D array  | 1D array  |
|Function 6  | 5D array  | 1D array  |
|Function 7  | 6D array  | 1D array  |
|Function 8  | 8D array  | 1D array  |

initial data can be found in the /data folder. Each week's addition and output is in the code itself and also can be found in the observations.xlsx

# techincal approach 

1.Load the intital data into X and y array\
2.For Week2 onwards append the previous weeks input and output\
3.Find the maximum value of y in the input\
4.Define the surroage  model (GP and SVM is used in this case) and fit X,y\
5.Create a grid or random sample depdending on whether doing grid search or random search\
7.Use the acquisition function to get the new inputs\
8.Submit this as a next best point\
9.Repeat this every week by refining the strategy

# hyperparameter optimisations

I tuned UCB’s kappa, EI’s xi, SVM’s C value, and  sampling/grid sizes to control how aggressively or cautiously  optimisation explored the search space, and these adjustments directly shaped the improvements week by week.


# results

The main lesson from the BBO capstone was that good optimisation isn’t just about picking the right model but it’s about adapting the strategy as we learn more. 
Early we need to explore widely, even if the results look messy, but later we have to shift toward focused, careful exploitation to get the best scores. 

Please refer to the [Observations](observations/Observations.xlsx) for the week by week results

# Data sheet
[Data Sheet](/DATA_SHEET.MD)

# Model card
[Model Card](/MODEL_CARD.MD)

