# Data-Science-Analytics-and-Exploration_Capstone-Project-II

## Purpose
This is the code and data set for the second capstone project under HyperionDev's Data Science - Level 2 task. The purpose was to review a CSV document provided by the course and write code to perform an exploratory analysis and create visuals from the raw data.

## Data Set
The CSV document contains info on a set of 205 automobile details, loaded with 26 descriptor columns relating to the manufacturer, the mechanical specifications and the performance metrics. The set is provided in a text doc format. 

## Data Analysis
As an initial step to comprehend the data, numerous scatter plots were created to provide visual indications of potential trends the overall relationships between the data columns. This helped with identifying outliers and lead into the data cleaning step. 

Various Matplotlib and Seaborn plots were generated to identify major market players and popular automobile types by breaking the population in different categories. Furthermore, specific model types were isolated from the population and plotted against each other to determine the performance metrics for automobiles of different designs. 

A risk profile based on the individual vehicles "Symboling" was created to give an indication of the status of the automobile industry. The symboling contains a numeric value ranging from -2 to 3, with the lower value indicating a low risk model and the higher value indicating the highest risk. Further to this, a plot indicating the value of normalised losses per symbol category was generated. 

## Findings
The data set provided shows that there are three major players in the industry, namely Toyota (with a fairly large margin of the market share), Nissan and Mazda. 

Regarding generic automobile type specifications: it is clear that Gas/Petrol is hugely more popular than Diesel; standard vehicles are in much higher demand that turbos; the split between 4 door and 2 door is fairly even with a higher demand for 4 door; when considering model type the sedan option is the most popular with hatchback and convertible holding the two lowest portions of market share. 

A comparison of the horsepower range for automobiles of different drive-train options showed that FWD held the highest proportion of lower ranking horsepower options with RWD options showing a strong spread on the higher end of the range. Surprisingly, 4WD models occupied a mid range but with a strong trend towards the lower end only marginally higher than FWD options.

As expected, the risk profile generated across all makes showed a normal distribution with a strong majority of models falling over "0" and "1" and tails extending towards the extremes. There is however a higher number of high risk options than low risk, indicating a fairly strong automobile market with a considerable demand for high risk models.

A scatter plot analysis was generated comparing the vehicles consumptions performance vs. horsepower. The plots showed a strong indirect correlation between the two parameters, indicating that consumption decreases greatly with increased horsepower output. 
