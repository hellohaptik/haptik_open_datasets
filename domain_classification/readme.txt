The dataset contains two separate files for training and testing/evaluation of data.
Each human query/message is categorized into single/multiple domains by human annotators.
"T" -> message can belong to the corresponding class
"F" -> message does not belong to the corresponding class (column heading represents the class name)

Task: train a multi-label classifier to classify "message" into one or more classes/domains.
Ecaluation: 
Precision, Recall, Accuracy per class
Overall Accuracy (all classes are correctly identified)
NOTE: Please note that the messages are in raw format, it also contains system specific content which may not be important for identifying domain.We have kept it as it is, to give a glimpse of real world data. It is important to preprocess messages and remove such information for better training.
