# diabetes_predictions_python_sklearn

Database:
https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database?resource=download

"This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on."

The attached code splits the database into a training set and a test set (0.75 / 0.25) </p>
Suspicious zero values in X variables are replaced with median values or predicted values using SVR. </p>
Models created in order to predict Y (Outcome) are: XGBoost, Random Forest, SVM, Artificial Neural Network. </p>
Few hyperparameters combinations were tested, attached code contains best ones. </p>
Best accuracy was achieved by Random Forest (77% accuracy on test set) - model was built using 128 tress with max depth 3. </p>
