# Water-Quality-Prediction-Analysis


**Deployed with Vercel app:** https://waterqualityprediction-omyvr6qch-ophelia113s-projects.vercel.app/


**What is Water Quality?**

Water Quality refers to the chemical, physical, and biological characteristics of water based on the standards of its usage.

**Management of water quality is a real-world issue!!**

Over time, there has been increasing recognition of the importance of drinking water quality and its impact on public health. This has led to increasing protection and management of water quality.




**Aim of this Project:**

Addressing a real-world issue, this project aims to find the best-fit model to predict the water potability based on a dataset which contains water quality metrics for 3276 different water bodies.
The goal is to correctly classify water samples as potable (1) or not potable (0).




**About the dataset:**

The dataset contains water quality measurements and assessments from 3276 different water bodies, related to potability, which is the suitability of water for human consumption. The dataset's primary objective is to provide insights into water quality parameters and assist in determining whether the water is potable or not.

Columns:

pH: The pH level of the water.
Hardness: Water hardness, a measure of mineral content.
Solids: Total dissolved solids in the water.
Chloramines: Chloramines concentration in the water.
Sulfate: Sulfate concentration in the water.
Conductivity: Electrical conductivity of the water.
Organic_carbon: Organic carbon content in the water.
Trihalomethanes: Trihalomethanes concentration in the water.
Turbidity: Turbidity level, a measure of water clarity.
Potability: Target variable; indicates water potability with values 1 (potable) and 0 (not potable).




**Libraries used:**  NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

**Preprocessing of data:**

•	Feature Scaling is done with StandardScaler. 

•	Missing values are handled by replacing them with means.


**Algorithms used for prediction:**

•	Logistic Regression

•	Decision Tree Classifier

•	Random Forest Classifier

•	K-Nearest Neighbours

•	SVM

•	XGBoost


For each algorithm, the model is trained on training data and its accuracy of prediction is tested on testing data.
Finally, we will compare the accuracy of various models used.
