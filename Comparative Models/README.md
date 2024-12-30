This folder consists of information about the **Comparative Model** performed on the Dataset having
1. **Input Parameter**:-  Spindle Speed, Feed Rate and Drill Diameter.
2. **Output Parameters**:-  MRR, Circularity, Cylindricity and Delamination Factor.

Comparative Models like Linear Regression, Decision Tree, XGBoost, Random Forest, Gradient Boosting, and KNN.

Initially, the Dataset was generated through practical performances and 27 data points or results were generated.
We used these 27 data points and Input Parameter values and generated the theoretical regression formula to augment the dataset to perform on the Models to avoid Factors like Underfitting/Overfitting.

**Comparative_Modelv1.ipynb** performs training and testing of Dataset 1 of around 360 data points through augmentation on a given Comparative Model.
**Comparative_Modelv2.ipynb** performs training and testing of Dataset 2 of around 1200 data points through augmentation on a given Comparative Model.
We Trained the Model on 2 Different Datasets to guess the best results among two datasets.

Tasks Performed in these Models involve:-
1. **Evaluation Metrics** like MSE, RMSE, R2, and MAE on both training and testing data.
2. **Residual Plots** for each model (training and test data).
3. **Subplots** for training and test residuals.
4. **Contribution plot** for models with feature importance or coefficients.
5. **Correlation matrix**.
6. **Pairplot for detailed correlation visualization**.
7. Loop through each model and generate **SHAP and LIME**.
