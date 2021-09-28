# My projects

## Avocado Prices 2020 (28 September 2021)

Tableau visualisation project to show the trend of avocado price and volume sold in the last five years. In addition, I compared the sales of different kind of avocados, and highlighted the states that have higher demand. In conclusion, California has the highest number of avocado sold throughout the last five years, followed by Midsouth, Los Angeles and New York. The dashboard is shared on the Tableau Public server. [url]https://public.tableau.com/app/profile/eric3982/viz/Avocado_2020/Dashboard1?publish=yes[/url]

## Road Users Protection Improvement (20 August 2021)

Data Science & AI capstone project. The objective of this project is to provide solutions to reduce UK road accidents and casualties for the Department for Transport. In order to do that, we looked into the relationship between different factors and number of accidents / casualty severity, as well as what group of road users was more likely to get into a road accident. The dataset was provided by the Department for Transport, recorded 117536 cases with 71 attributes.

Since there were three relational tables recording accident, vehicle and casualty details, we utilised SQL database for queries. The SQL database was created in the "Capstone_DataCleaning.ipynb" notebook. Another advantage of using SQL was that we could maintain the consistency of the input data such as attribute names. This allowed us to reuse the Exploratory Data Analysis (EDA) pipeline easily in the future.

As a result of this project, we provided three possible solutions to protect road users covering Road Crossings, Speed Limits and Marketing and Communication. The next step of this project will be investigating pedestrians crossing facilities to improve usage rate.

Tools and libraries used:  
Jupyter Notebook  
Python 3 (numpy, pandas, sqlite3, sqlalchemy, matplotlib, seaborn, time, sklearn, lightgbm)  
SQL  
Microsoft Excel

## Optimal Chess KRK-Endgame Position (2 August 2021)

The goal of this project is to find out the best chess endgame position for white and black. In this scenario, white has a rook and king remaining, while black only has a king, and it is black's turn to move. The dataset contains data about the pieces' positions and the optimal number of moves for white to win. We used the distance between pieces and board centre as features to train different models to predict the result.

In conclusion, white will win sooner if white king is near the centre and closed to black king; in contrast, black can survive longer and perhaps force a draw if black king is near the centre. Regarding model prediction, Decision Trees and other ensemble methods have similar accuracy, but the ensemble methods consume much more time to process so ensemble method is not recommended for this analysis.

Future Improvements:
- Show confusion matrix
- Reduce the result digits to three decimal places

## Australian Energy Consumption Prediction (19 July 2021)

My second Data Science project. The goal was to compare the performance of different machine learning algorithms in predicting energy consumption. The features for prediction were `Total Population`, `Population in Largest Cities`, `Rural Population`, and `GDP`. Regarding the targets, `Total Energy Consumption` and `Energy Consumption of the Top Three Industries (Manufacturing, Electricity Generation, Transport)` were selected. In addition, I tried to use all 10 industries as targets at once out of curiosity. The result was not bad, but not as good as predicting the targets one by one.

The script has five options of targets under the section "Select features and targets". Change the targets to see different results.

In the presentation slides, the Average R^2 Score is the average score out of seven trials with the seeds 1~7. The figures show the best trials only.

Future Improvements: 
- Show the trend of energy consumption of each industry against features with area graph.
- X axis label of the prediction graph should be clearer (instead of "sample", explain it is "year").
- Avoid using highly correlated features together.

## Building Energy Efficiency Register Analysis (2 July 2021)

My first Data Science project. I obtained the latest Building Energy Efficiency Register dataset through CKAN API, and analysed the energy efficiency of large office buildings over Australia. In addition, I did further study in SA buildings to find out the most energy efficient one.

In conclusion:
- Large office buildings over most states have similar energy efficiency. Although TAS has a significantly higher result, the sample size is too small to judge.
- There is no significant difference in energy efficiency between SA large office buildings in CBD and outside CBD. However, a few buildings in the CBD consume a lot more energy per year.
- The energy efficiency of Australian large office buildings will not have a significant change any time soon.

Future Improvements: It was unnecessary to create the "state_num" column since it could not provide useful information in the correlation heatmap.
