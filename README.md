# SuperKart-Problem-Statement
Model Deployment
Criteria
Data Overview and Exploratory Data Analysis
- Observations on the shape of data, data types of various attributes, missing values, duplicate values and statistical summary.
- Univariate Analysis (boxplots, distribution plots for important variables)
- Bivariate Analysis
- Insights based on EDA
Comments
* Observations are provided on the dataset structure, including the data shape, attribute types, missing values, and a brief statistical summary.

* Univariate analysis is presented using boxplots and distribution plots for numerical variables and bar plots for categorical variables.

* Bivariate analysis is explored through scatterplots and a correlation plot to examine relationships between variables.

* The exploratory analysis concludes with key insights that summarize the main patterns observed in the data.
Points
6/6
Criteria
Data Preprocessing
- Feature engineering (provide rationale if not needed)
- Outlier detection and treatment (provide rationale if treatment is not needed)
- Prepare the data for analysis (Train and Test sets)
- Define the preprocessing pipeline for encoding categorical features
Comments
* Feature engineering has been performed, and justification has been provided.

* Outliers in the dataset have not been identified or handled.

* The dataset has been split into training and testing sets.

* Preprocessing pipeline has been defined for encoding categorical variables.
Points
4/5
Criteria
Model Building
- Choose the metric of choice with proper rationale
- Build any 2 ML models as a part of a pipeline with the data preprocessing steps
- Comment of the perfomance of the models

* The ML models to be built can be any two out of Decision Tree, Bagging, Random Forest, AdaBoost, Gradient Boosting, and XGBoost
Comments
* The metric of choice is selected with a suitable rationale, explaining its relevance for evaluating the model.

* Two machine learning models are built within a pipeline that includes the required data preprocessing steps.

* The performance of the models is discussed with brief and relevant commentary.
Points
7/7
Criteria
Model Performance Improvement - Hyperparameter Tuning
- Use hyperparameter tuning to tune the models wrt the metric of choice
- Comment of the perfomance of the tuned models
Comments
* The models were tuned using suitable hyperparameter tuning methods, and this is completed.

* The performance of the tuned models is discussed with brief interpretation, and this is done.
Points
7/7
Criteria
Model Performance Comparison, Final Model Selection, and Serialization
- Compare the performances of all models built and choose the best model (with proper rationale)
- Check the performance of the best model on the test set
- Serialize the best model
- Load the serialized model and make predictions on the test set
Comments
* The performance of the tuned models on both the training and validation datasets is compared to understand their generalisation and overall behaviour.

* The most appropriate model is selected with clear reasoning based on the evaluation outcomes.

* The performance of the final selected model on the test dataset is checked to assess its behaviour on unseen data.

* The best performing trained model is serialized for future use and reproducibility.

* The serialized model is loaded again and its predictions are validated to confirm that it works as expected.
Points
7/7
Criteria
Deployment - Backend
- Define the Flask API
- Define the dependencies
- Define the Dockerfile
- Create the Docker space in Hugging Face
- Upload the files to the space
- Share the link of the Hugging Face space
Comments
* The Flask API is defined for serving the application.

* The required dependencies are defined for the project environment.

* The Dockerfile is defined to support containerised deployment.

* The Docker space in Hugging Face is created for hosting the project.

* The project files are uploaded to the Hugging Face space.

* The Hugging Face space link is shared for access to the application.
Points
9/9
Criteria
Deployment - Frontend
- Define the streamlit web application
- Define the dependencies file
- Create the Streamlit space in Hugging Face
- Upload the files to the space
- Share the link of the Hugging Face space
Comments
* The Streamlit web application is defined clearly.

* The dependencies file is defined with the required libraries.

* The Streamlit space is created.

* The project files are uploaded to the space.

* The Hugging Face space link is shared.
Points
7/7
Criteria
Actionable Insights and Recommendations
- Write down insights from the analysis conducted
- Provide actionable business recommendations
Comments
* Insights are clearly presented with at least three meaningful observations.

* Recommendations are provided with at least two practical suggestions based on the insights.
Points
4/4
Criteria
Presentation/Notebook - Overall quality
- Structure and flow
- Crispness
- Visual appeal
- Conclusion and Business Recommendations

OR

- Structure and flow
- Well commented code
- Conclusion and Business Recommendations
Comments
* Clear structure and logical flow are demonstrated, and the content presents a coherent narrative throughout the notebook.

* The explanations remain concise and focused, with an appropriate level of detail that keeps attention on the key points.

* Visual presentation is well executed, with effective use of charts, colours, and diagrams that support interpretation and improve overall readability.
Points
8/8
