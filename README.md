# Medical_Insurance_Price_Prediction
Created this project to predict medical insurance prices.<br />
<br />
Read in the dataset.<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/7e8a975c-1d5b-4a3e-bf8c-3046cad9b3b2)<br />
<br />
<b>Data Cleaning</b><br />
<br />
Checked for Null values to enable machine learning and see if any techniques would need to be used to fill in missing values.<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/2f5a3503-cd20-43b9-bce9-a9a0dada08a0)<br />
<br />
Encoded the data to allow categorical features to be used for regression models.<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/884abf08-7564-4669-a952-e66bab02a26b)<br />
<br />
<br />
<b>Split the data into train & test variables.</ b><br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/de19b3bb-b6da-49fb-9836-94a989bed214)<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/8c958813-23dd-4f2f-ac2e-6a5ded9d8979)<br />
<br />
<br />
<b>Model Handling</ b><br />
<br />
Imported, created, fitted, & tested several regression models with hyperparameter tuning, but used KNeighborsRegressor model with hyperparameter tuning to make & test predictions.<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/ff85f895-2a32-4914-9133-16387af1d5da)<br />
<br />
Printed a table of all combinations of hyperparameter values & their respective R^2 and R^2 Adjusted values.<br />
Note that R^2 values were used & compared against R^2 values to test for overfitting.<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/2b3bd4cd-3d4f-46d1-a5bb-063429799a91)<br />
<br />
Printed records where the R^2 score was maximized, given that the R^2 minus R^2 Adjusted value was <= 0.10.<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/9b836e30-5b8a-4291-92ef-8fda3915e69c)<br />
<br />
Showed graphs of all R^2 values vs. continuous hyperparameter values.<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/903a6fe9-5e7f-4297-96b6-61bee74c2280)<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/09afd1b3-e0fd-439c-a122-98b483fcb038)<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/b828489c-b04a-4808-ac2b-174fb3758817)<br />
<br />
Reimported, created, fitted, & tested the KNeighborsRegressor model with hyperparameters corresponding to the maximum R^2 value.<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/f8a775fd-f9be-48cb-84d3-96dd61c041c9)<br />
<br />
Created a DataFrame to store actual vs. predicted insurance prices.<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/b5f252b9-3f14-4e1e-b973-1ef4952890f1)<br />
<br />
<br />
<b>ANOVA Testing</ b><br />
<br />
Performed F-Test/ ANOVA on features, and only showed ones deemed statistically significant (p <= 0.05).<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/728ebbd6-14f9-45cd-b43b-a4e3cf41411c)<br />
Also showed correlation coefficients for other models (couldn't do this for KNeighborsRegressor model though).<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/86073c9d-261d-43b7-a183-b9bcbdd578c1)<br />
<br />
<br />
<b>Actual vs. Predicted Prices Graph</ b><br />
Showed graph of actual vs. predicted insurance prices.<br />
![image](https://github.com/KotR9001/Medical_Insurance_Price_Prediction/assets/57807780/05fb1e32-a2f3-406b-8d7b-209491b161cd)
<br />
<br />
