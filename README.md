# GeeksFiesta_AI-ML_NewbieAI
<u></u>
## DAY-1: Made a private repo and given accesses.
<u> </u>
## DAY-2: TASK-1: Data Cleaning, find count of missing values in each column, describe the dataset (mean,median etc )

<p><h3>In this task firstly I have taken out the info about dataset (how many are null and wrong values). Then using the drop method I removed a row 'Unnamed: 0' which has no use in the dataset problem. Some values were also wrong in the dataset in row 'year', 'month' and 'pressure', which I have corrected them using 'loc' method and replace it with correct or almost similar data.</h3></p>
 <p><h3>   After correcting the dataset, using pandas method 'to_numeric' I changed the dtype of parameters to their correct dtype. Then, I used interpolate method to fill the null values in each given columns.</h3></p>
 <p><h3>   I then describe the datset with 'describe' function and then find median using numpy method 'median', and mode using scipy method. At the end, after finding the mode, I fill the data values in the 'wind_direction' column where null values were exited using 'fillna' method. </h3></p>
 
<u></u>

<u></u>
## DAY 3 - DAY 4
<p><H3> In day's 3 tasks, I have to find and fix the outliers, which I have done through first by BOX PLOT method and then to find the exact values, used Z-score method. After then I find relationships and correlations between different columns using 'scatter plot', 'bar' plot, 'heatmap' and using 'corr()' method. 
  And at last concluded that column 'PM2.5' does not affected by or depends on other columns. </H3></p>

## DAY 5 - DAY 6
<h3> In this task, I have trained and evaluated the model. Firstly, I did label encoding to change the dtype of wind_direction parameter from object to int type. I then 
splitted the model using sklearn and then trained and fit using SVR algorithm, I also tried SGD but it gave very low accuracy value. I then lastly, predicted, vizulalised by using 
graph and evaluated the model. </h3>

## DAY 7
<H3> In the given task, I just predicted the PM2.5 value based on the given test dataset. I first predict the values in the model trained in previous task and insert these values in a new file of test dataset.</h3>

## DAY 8 - DAY 9
<h3> At the end of the project, we have to deploy the model using flask. So, first I did pickling of the code using pickle library and dumped it. Then write a html code file which I have to deploy as a web page, then made a app file for flask deployment and at the end hosted the page using heroku.</h3>