# Data-Science-FemHack-challenge
Data Science FemHack challenge
Team members:
Elizabeth Mejia,
Lorena Guadalupe Vázquez Figueroa

In this repository, we present our solution for the FemHack Data Science challenge, which involved utilizing AI to analyze petitions on Change.org and predict their likelihood of success.

We have uploaded two projects developed using Google Colab. The first project focuses on data exploration, where we studied the behavior of the data and drew conclusions regarding the significance of various columns. In the second project, we addressed the challenge of language diversity by translating the "titles" variable to ensure all information was in a single language. After performing these steps, we proceeded to remove punctuation marks and stopwords from the text using the NLTK library. Next, we utilized the CountVectorizer library to vectorize the titles. Recognizing the significance of having sufficient data for model training, we implemented the Synthetic Minority Oversampling Technique (SMOTE) to ensure a balanced dataset (especially in column "victory_flag"). Lastly, we tested various models including Logistic Regression, SVM, K-Neighbors, BernoulliNB, Decision Tree, Random Forest, and Ada Boost to identify the optimal performance. 

After evaluating all of them, we selected Random Forest due to its accuracy of 90.62%. In order to improve the efficiency of our model and optimize resource utilization, we implemented dimensionality reduction using PCA. This technique allowed us to reduce the number of features in the dataset, which had become large after the transformations.
