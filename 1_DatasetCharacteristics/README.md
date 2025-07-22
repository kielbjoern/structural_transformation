# Dataset Characteristics

- **I have data for the economic structural shift for whole Germany and for Schleswig-Holstein for the years 1882, 1895, 1907, 1925, 1933 and 1939. I have data for several cohorts (generations) from the censuses.** 

- **I need data for each birth year in order to meaningfully identify the changes. I used TensorFlow for the interpolation of the missing data. I used '01_imputation_of_missing_values_ger.ipynb' and '01_imputation_of_missing_values_sh.ipynb' for this.**

- **And I have to calculate the average shift for each birth year between the censuses. I used '02_calculate_of_the_average_shift_ger.ipynb' and '02_calculate_of_the_average_shift_sh.ipynb' for this.**

- **I made an attempt for the data analysis with the total set of data after the imputation ('03_exploratory_data_analysis.ipynb').**

- **The share of the primary sector shows a much wider range across generations than the other two sectors.**

- **There are no biases.**

- **There is a positive correlation between the 1. sector and delta. And a negativ between the other sectors and delta.**

**[Imputation](01_imputation_of_missing_values_ger.ipynb)**

**[Calculation](02_calculate_of_the_average_shift_ger.ipynb)**

**[Data Analysis](03_exploratory_data_analysis.ipynb)**
