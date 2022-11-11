# BGP_2021_B
Big Geodata Processing -2022 - Group A

Group project with the goal to predict the observer intensity (defined as the number of observers per 1km^2-block and per hour/per week) in time and space, based on data from the Citizen Science project waarneming.nl.

The data was provided through the following data base: \
host: gip.itc.utwente.nl\
port: 5434\
database: c211\
user: sxxxxxx\
password: xxxxxx\

### Instructions
1. Folder 1_data_preparation: The notebook data_preparation.ipynb prepare the original dataframes from database tables and merges them on left join with block
For further processing and for ease of use the output is exported to a CSV file. We have also created the table using the create table and the join conditions in the respective schema so we can also export to a CSV from the database table directly.

2. Folder 2_data_exploration_modelling is used for exploratory analysis and also for modelling and hyper parameter tunning using random search and grid search. We have also used Dask to utillizie parallel computing.
