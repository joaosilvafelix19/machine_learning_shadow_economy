# machine_learning_shadow_economy
 
Data and codes for Felix, Alexandre, and Lima (2024), “Applying Machine Learning Algorithms to Predict the Size of the Informal Economy”, Computational Economics.

df_shadow_econ.csv: the database.

01_linear_models: run the linear models (linear regression, elastic net, lasso, and ridge).

02_ML_models_metrics_performance: run the ML models. Compute the performance metrics of both ML and linear models.

02_shap_values: compute the SHAP values for the ML models and save them as Numpy array files.

03_shap_graphs: using the original database and the files computed in the previous code, generate the SHAP plots (bee swarm plots, absolute SHAP value plots, and partial dependence plots). 