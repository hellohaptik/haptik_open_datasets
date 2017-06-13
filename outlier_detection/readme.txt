The training data contains one file, each line contains a message from user. (types of queries which are rarely asked -> outliers)
Task: Train an unsupervised model to find potential outliers. The model should be able to predict, given a query, if it is an outlier or not.
Evaluation:
For evaluation, a separate evaluation daa file is provided. Each line contains an unseen message and a corresponding tag representing if the query is an outlier or not.
Accuracy of the model on evaluation model will be used for evaluation
NOTE: Please note that the messages are in raw format, it also contains system specific content which may not be important for outlier detection.We have kept it as it is, to give a glimpse of real world data. It is important to preprocess messages and remove such information for better training.
