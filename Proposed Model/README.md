This folder consists of information about the Proposed Esembled Model performed on the Dataset having

1. Input Parameter:- Spindle Speed, Feed Rate and Drill Diameter.
2. Output Parameters:- MRR, Circularity, Cylindricity and Delamination Factor.

The proposed Esembled Model consists of XGBoost, MLP, and LSTM.

**Proposed_Esemble_Model.ipynb** performs training and testing of Dataset 2 of around 1600 data points through augmentation on a given Esembled Model.

Tasks Performed in these Models involve:-

1. **Evaluation Metrics** like MSE, RMSE, R2, and MAE on both training and testing data.
2. **Residual Plots** for each model (training and test data).
3. **Subplots** for training and test residuals.
4. **Contribution plot** for models with feature importance or coefficients.
5. **Correlation matrix**.
6. **Pairplot for detailed correlation visualization**.
7. Loop through each model and generate **SHAP and LIME**.
