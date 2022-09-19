# Multi_Label_Text_Calssification_for_Stackoverflow_Tags
A text classification model that predicts multi label for StackOverflow questions
* I used MultilabelBinarizer for text vectorization and encoding.
* I uesd TF-TDF Vectorizer for feature extraxtion. 
* 3 classical classifiers were used (SGD, LinearSVC, LogisticRegression) for modeling and I comapered their results using Jaccord score.

## Accuracy
* SVC: ~62.20
* SGD: ~52.49 
* LR: ~51.84


# Dataset
I used the preprocessed for “StackSample:10% of Stack Overflow Q&A” dataset:
"https://raw.githubusercontent.com/laxmimerit/All-CSV-ML-Data-Files-Download/master/stackoverflow.csv"

# Libraries
* sklearn
* pandas
* numpy
* ast
