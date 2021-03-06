## Authors:
[Jake Horban](https://github.com/h0rban) and [Pranav Ahluwalia](https://github.com/pranavwalia) 

# Flower Harvest Prediction
Supervised Machine Learning with [Scikit-Learn](https://scikit-learn.org/stable/) Project - Regression. A personal project completed as a Final Project for a Northeastern's course DS3000: Foundations of Data Science. The presentation of this project is availible on [YouTube](https://youtu.be/KCqaqe3K1hM).
<p align="center">
  <img src="https://raw.githubusercontent.com/h0rban/flower-harvest-prediction/master/Vizualizations/smooth_target_v_time2.png" alt="graph demo"/ height="600">
</p>

## Summary
This project is focused on identifying the patterns and predicting the number of roses produced in a specific greenhouse based on the conditions inside and outside of the greenhouse. Plants usually need nutritious soil, water, sunlight, and carbon dioxide to grow. While the greenhouse controls the constant supply of nutrition and water, other conditions are variable. The amount of how much roses are produced appears to have a sinusoidal pattern with a variable vertical shift, amplitude, and period that depend on weather conditions. Full writeup is availible as [ipynb](https://github.com/h0rban/flower-harvest-prediction/blob/master/writeup.ipynb) (may not render on github) and [html](https://h0rban.github.io/flower-harvest-prediction/).


## Conclusion
We expected better results from the Kernel Ridge regression as scikit learn documentation says it is often highly predictive of sinusoidal data. Perhaps we could have done a better job fine tuning the prameters of that specific model or perhaps a Kernel ridge regression warrants a more specific feature selection process. We were surprised that kNN model could be tuned to such a high degree of accuracy. The performance of the Gaussian Process was not surprising as it is often highly predictive of cyclical data. 

Future work of this project could involve combining the error prediction model with the smoothed target prediction. Additionally we believe this model has effective real world utility for greenhouse companies and possibly for other crops that are farmed. The real world implications of this project could perhaps be employed by certain hedge funds or investment firms to predict yields of various crops (other than flowers) in order to effectively price commodity futures. 
