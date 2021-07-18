# My projects


# **Building_Energy_Efficiency_Register_Analysis**

My first Data Science project. I obtained the latest Building Energy Efficiency Register dataset through CKAN API, and analysed the energy efficiency of large office buildings over Australia. In addition, I did further study in SA buildings to find out the most energy efficient one.
In conclusion:
- Large office buildings over most states have similar energy efficiency. Although TAS has a significant higher result, the sample size is too small to judge.
- There is no significant difference in energy efficiency between SA large office buildings in CBD and outside CBD. However, a few buildings in the CBD consume a lot more energy per year.
- The energy efficiency of Australian large office buildings will not have a significant change any time soon.


**Australian_Energy_Consumption_Prediction**

My second Data Science project. The goal was to compare the performance of different machine learning algorithms in predicting energy consumption. The features for prediction were `Total Population`, `Population in Largest Cities`, `Rural Population`, and `GDP`. Regarding the targets, `Total Energy Consumption` and `Energy Consumption of the Top Three Industires (Manufacturing, Electricity Generation, Transport)` were selected. In addition, I tried to use all 10 industires as targets at once out of curiosity. The result was not bad, but not as good as predicting the targets one by one.

The script has five options of targets under the section "Select features and targets". Change the targets to see different results.

In the presentation ppt, the Average R^2 Score is the average score out of seven trials with the seeds 1~7. The figures show the best trials only.
