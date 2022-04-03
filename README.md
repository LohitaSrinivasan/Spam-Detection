# Spam-Detection

# Scope and Output
Developed a probabilistic classification model to classify spam emails. Used natural language processing techniques to pre-process the text content of emails, extracted relevant features and trained a robust support vector machine classifier to differentiate spam/genuine emails using Python. Achieved ~84% accuracy on public(30% of the test dataset) and private leader board(70% of the test dataset).

# Text Pre-processing Steps
1. Used regular expressions to manipulate strings to provide more definition/explanation to the model
2. Stopwords removal
3. Converting text into vectors 

# Modelling
Support Vector Classifer with linear kernel:
“Support Vector Machine” (SVM) is a supervised machine learning algorithm which can be used for both classification or regression challenges. However, it is mostly used in classification problems. In the SVM algorithm, we plot each data item as a point in n-dimensional space (where n is a number of features you have) with the value of each feature being the value of a particular coordinate. Then, we perform classification by finding the hyper-plane that differentiates the two classes very well.
