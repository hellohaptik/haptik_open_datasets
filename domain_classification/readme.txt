The dataset contains two separate files for training and testing/evaluation of data.
Each human query/message is categorized into single/multiple domains by human annotators.
"T" -> message can belong to the corresponding class
"F" -> message does not belong to the corresponding class (column heading represents the class name)

Task: train a multi-label classifier to classify "message" into one or more classes/domains.
Ecaluation: 
Precision, Recall, Accuracy per class
Overall Accuracy (all classes are correctly identified)
