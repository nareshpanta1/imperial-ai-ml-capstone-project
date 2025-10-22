# imperial-ai-ml-capstone-project
Repo for Capstone project as part of Professional Certificate in AI and ML
This is a black-box challenge which consists of eight functions for which we are trying to find the maximum.

# inputs and outputs 
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

# challenge objectives
This is a black-box challenge which consists of eight functions for which we are trying to find the maximum.
Each week we submit one set of input (x)  for each function and we receive the output(y) once the submission is processed.
We then take these input and output and add it to the initial data set and rerun the process again optimising iteratively.

# techincal approach 

1.Load the intital data into X and y array\
2.For Week2 onwards append the previous weeks input and output\
3.Find the maximum value of y in the input\
4.Define the GP model and fit X,y\
5.Define a UCB aquisition function\
6.Create a grid or random sample depdending on whether doing grid search or random search\
7.use the UCB function to get the ucb scores of the sample from above step\
8.find the maximum value of the ucb scores\
9.submit this as a next best point\