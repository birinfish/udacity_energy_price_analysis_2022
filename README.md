# udacity_energy_price_analysis_2022

This is a project for Data scientist, a Udacity nanodegree program.
In this project, I conducted an analysis on the price developments of power and gas </br> 
through the last two years, answering the three questions as shown below:

Q 1: How much have the prices of energy commodities increased compared to 2021? </br>
Q 2: What could have been influencing factors for price changes? </br>
Q 3: Are the two different energy commoditiy prices(Electricity, Gas) correlated? </br>

To asnwer the questions, I observed the pure price developments for thw two energy commodities,</br>
calculate daily returns, correlation coeffients, and visulaize the results.

The main libraries used for the modeeling are shown below:
 - Pandas: data preparation (cleaning, transforming)
 - numpy : calculation using log, sqrt
 - plotly: data visualization

The clear answer wasn't derived with the model I created as I just used a simple</br>
rolling correlation coefficient. However, it's fair to say the two prices are truly </br>
linked but still a number of other factors should also be taken into account.

For my next step, I would like to explore a better methodology to quantify the relationship </br>
between two commodities' prices.

The details about the analysis and the results are explained on the notenook "corr_analysis.ipynb".


Here is the file structure in this repository:</br>
 - dataset(folder): containing two datasets (csv fotmat)</br>
 - figures (folder): result figures obtained from the notebook </br>
 - corr_analysis.ipyb: the main notebook where my model for the analysis was written</br>
