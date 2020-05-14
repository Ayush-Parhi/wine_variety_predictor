This wine variety predictor is capable of predicting the variety of wine consumed by the customers. It predicts the variety by going through the reviews given by the customers. The main aim of this repository is to practice NLP techniques and its implementations.

### Summary of techniques used in the notebook:

- Data visualization
- Data Analysis
- Data preprocessing
	- Feature Extraction 
	- Feature Engineering
		- Handling missing values
		- Feature selection
* Tokenization of the reviews
* Encoding the reviews
* Model architecture
	-Train/Dev split
	-RNN model building
	-Hyperparameter tuning
* Training the model 
* Model performance Diagnosis
* Prediction of the variety of wine
	- Decoding the reviews
	- Predictions
* Predicting the variety for test dataset
* Saving a new CSV file as variety_predictions

The Data Description is as follows:
- user_name - user_name of the reviewer
- country -The country that the wine is from.
- review_title - The title of the wine review, which often contains the vintage.
- review_description - A verbose review of the wine.
- designation - The vineyard within the winery where the grapes that made the wine are from.
- points - ratings given by the user. The ratings are between 0 -100.
- price - The cost for a bottle of the wine
- province - The province or state that the wine is from.
- region_1 - The wine-growing area in a province or state (ie Napa).
- region_2 - Sometimes there are more specific regions specified within a wine-growing area (ie Rutherford inside the Napa Valley), but this value can sometimes be blank.
- winery - The winery that made the wine
- variety - The type of grapes used to make the wine.
