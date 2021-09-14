# GeeksFiesta_AI-ML_NewbieAI
<u></u>
## DAY-1: Made a private repo and given accesses.
<u> </u>
## DAY-2: TASK-1: Data Cleaning, find count of missing values in each column, describe the dataset (mean,median etc )

<p><h3>In this task firstly I have taken out the info about dataset (how many are null and wrong values). Then using the drop method I removed a row 'Unnamed: 0' which has no use in the dataset problem. Some values were also wrong in the dataset in row 'year', 'month' and 'pressure', which I have corrected them using 'loc' method and replace it with correct or almost similar data.</h3></p>
 <p><h3>   After correcting the dataset, using pandas method 'to_numeric' I changed the dtype of parameters to their correct dtype. Then, I used interpolate method to fill the null values in each given columns.</h3></p>
 <p><h3>   I then describe the datset with 'describe' function and then find median using numpy method 'median', and mode using scipy method. At the end, after finding the mode, I fill the data values in the 'wind_direction' column where null values were exited using 'fillna' method. </h3></p>
<u></u>
