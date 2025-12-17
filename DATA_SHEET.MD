# Data Sheet

# Motivation
To explore surrogate‑based optimisation strategies for black box function. There are 8 functions.
Goal is to identify the maximum value 

# Composition

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

# Collection process

- surrogate models fitted on given inputs and output
- Acqusition function used to propose new points
- Each week a new points is provided and the output of the previous week goes as an additional input


# Preprocessing and uses
- Normalisation : for GP GaussianProcessRegressor is used with normalize_y=True
- Kernel choice : Matern v=2.5 smoothness assumption

# Distribution and maintenance

- Data set is available in this github rep under /data and each week's input/output is in the code as append
- This data can be freely used
- This repo is maintained by myself (Naresh)


