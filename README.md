# Sentiment-Analysis-Model
Build a model for sentiment analysis, deploy the model and link to a web application.

The project is developed and deployed using AWS Sagemaker. It needs active ASW Sagemaker environment. 

Following steps are performed to build a sentiment analysis model:
1. The reviews about movies used to create a word dictionary
2. The punctiations removed and the reviews encoded using the created dictionary.
3. The dataframe formatted data transformed into tensors. 
4. pytorch classifier is built and trained. The training and predicting code is also developed. 
5. Model is trained and tested
6. Model is deployed to production using AWS Sagemaker, Lambda and API GW
7. The service created from the model is linked to a simple web application. 

The files in the repository: 
* SentimentAnalysisNotebook.htm is the html export of Jupyter notebook that contains the Python code.
* Train.py and Predict.py are the Python files for training the model and running it for prediction. 
* index.htm contains the simple web application that the service is linked.
