# My projects

## Optimal_Chess_KRK-Endgame_Position (2 August 2021)
The goal of this project is to find out the best chess endgame position for white and black. In this senario, white has a rook and king remaining, while black only has a king, and it is black's turn to move. The dataset contains data about the pieces' positions and the optimal number of moves for white to win. We used the distance between pieces and board centre as features to train different models to predict the result.

In conclusion, white will win sooner if white king is near the centre and closed to black king; in contrast, black can survive longer and perhaps force a draw if black king is near the centre. Regarding model prediction, Decision Trees and other ensemble methods have similar accuracy, but the ensemble methods consume much more time to process so ensemble method is not recommanded for this analysis.

Future Improvements:
- Show confusion matrix
- Reduce the result digits to three decimal places

## Australian_Energy_Consumption_Prediction (19 July 2021)

My second Data Science project. The goal was to compare the performance of different machine learning algorithms in predicting energy consumption. The features for prediction were `Total Population`, `Population in Largest Cities`, `Rural Population`, and `GDP`. Regarding the targets, `Total Energy Consumption` and `Energy Consumption of the Top Three Industires (Manufacturing, Electricity Generation, Transport)` were selected. In addition, I tried to use all 10 industires as targets at once out of curiosity. The result was not bad, but not as good as predicting the targets one by one.

The script has five options of targets under the section "Select features and targets". Change the targets to see different results.

In the presentation ppt, the Average R^2 Score is the average score out of seven trials with the seeds 1~7. The figures show the best trials only.

Future Improvements: 
- Show the trend of energy consumption of each industry against features with area graph.
- X axis label of the prediction graph should be clearer (instead of "sample", explain it is "year").
- Avoid using highly correlated features together.

## Building_Energy_Efficiency_Register_Analysis (2 July 2021)

My first Data Science project. I obtained the latest Building Energy Efficiency Register dataset through CKAN API, and analysed the energy efficiency of large office buildings over Australia. In addition, I did further study in SA buildings to find out the most energy efficient one.
In conclusion:
- Large office buildings over most states have similar energy efficiency. Although TAS has a significantly higher result, the sample size is too small to judge.
- There is no significant difference in energy efficiency between SA large office buildings in CBD and outside CBD. However, a few buildings in the CBD consume a lot more energy per year.
- The energy efficiency of Australian large office buildings will not have a significant change any time soon.

Future Improvements: The "state_num" column that I made was not necessary.

