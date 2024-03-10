**How Machine Learning Helps Farmers the Best Crop**


Farmers have various options when it comes to deciding which crop to plant each season. Their primary objective is to maximize the yield of their crops, taking into account different factors. One crucial factor that affects crop growth is the condition of the soil in the field. So lets assess measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield.

Lets use a dataset called soil_measures.csv, which contains:
*   "N": Nitrogen content ratio in the soil
*   "P": Phosphorous content ratio in the soil
*   "K": Potassium content ratio in the soil
*   "pH" value of the soil
*   "crop": categorical values that contain various crops (target variable).
  
In this project, I applied machine learning to build a multi-class classification model to predict the type of "crop".
Here we use techniques to avoid multicollinearity, which is a concept where two or more features are highly correlated.

**Conclusion:**
The model with ['N', 'K', 'ph'] is accepted as 0.558010495235685 outsmarted the threshold.
