# Chess-Prediction
Predicting the Unpredictable 


The foundation of our project was laid by two data sets. The first data set was sourced from Kaggle containing metadata from over 130,000 chess games, however, many crucial variables for further analysis were missing. Thus, we created a second data set using the Lichess API which included these additional values.

After merging the data sets, we prepared the data for analysis and prediction purposes. As part of the exploratory analysis, we examined the correlation between variables via correlation matrix. Additionally, we looked at the distribution of the variables using  scatterplots in order to identify possible trends.

Furthermore, it ought to be mentioned that we used PCA to project the data in two dimensions allowing us to visualize the game outcomes more clearly. The resulting PCA biplot highlighted the features which have a significant impact on the principal components.

Following this process, we also experimented with simple heuristics for predicting results. By doing so, we aimed to establish a baseline before applying more advanced machine learning models.

All previous steps taken into account, we finally modeled a Decision Tree, a Random Forest and a Logistic Regression model and further presented their accuracy and calibration.

