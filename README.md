## Vegan recipe classifier from ingredients

this project aims to classify recipes to vegan, non-vegan, based on the list of ingredients.
data is from Kaggle [https://www.kaggle.com/hugodarwood/epirecipes], with some changes.
#### Algorithms Used
- KNN (K nearest nieghbor).
- Logistic Regression.
- Decision Tree Classifier.

### Steps
1. Loading the CSV Data 
2. cleaning the data to remove punctuation + digits + non alphabetic characters.
3.convert the textual representation of information into  a matrix of TF-IDF features.
4. split the dataset into training and testing.
5. perform the three algorithms.

### Results 
from the results we can see that the Decision Tree Classifier yields the highest accuracy while KNN yields the lowest accuracy 

- KNN (K nearest nieghbor) = 90.4%
- Logistic Regression = 91.3%
- Decision Tree Classifier = 91.5%
