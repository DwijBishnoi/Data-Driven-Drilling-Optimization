This folder consists information about **Comparative Model** performed on Dataset having
1. **Input Parameter** :-  Spindle Speed, Feed Rate and Drill Diameter.
2. **Output Parameters** :-  MRR, Circularity, Cylindricity and Delamination Factor.

Comparive Models like Linear Regression, Decision Tree, XGBoost, Randmon Forest, Gradient Boosting and KNN.

Initially Dataset was generated through practical performances and 27 datapoints were generated or result were generated.
We used these 27 Datapoints and Input Parameter values and generated the theoritical regression formula to augment the dataset to perform on the Models to avoid Factors like Underfitting/Overfitting.
**Comparative_Modelv1.ipynb** performs training and testing of Dataset 1 of aroung 360 datapoints through augmentation on given Comparative Model.
**Comparative_Modelv2.ipynb** performs training and testing of Dataset 2 of aroung 1200 datapoints through augmentation on given Comparative Model.
We Trained the Model on 2 Different Dataset to guess the best results among to datasets.

Tasks Performed in these Models involves :-
1. **Evaluation Metrics** like MSE, RMSE, R2, MAE on both training data as well as testing data.
2. **Residual Plots** for each model (training and test data).
3. **Subplots** for training and test residuals.
4. **Contribution plot** for models with feature importance or coefficients.
5. **Correlation matrix**.
6. **Pairplot for detailed correlation visualization**.
7. Loop through each model and generate** SHAP and LIME**.
