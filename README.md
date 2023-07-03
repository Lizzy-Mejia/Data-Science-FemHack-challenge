# Data-Science-FemHack-challenge
Data Science FemHack challenge
Team members:
Elizabeth Mejia,
Lorena Guadalupe Vázquez Figueroa

In this repository, we present our solution for the FemHack Data Science challenge, which involved utilizing AI to analyze petitions on Change.org and predict their likelihood of success.

We have uploaded two projects developed using Google Colab. The first project focuses on data exploration, where we studied the behavior of the data and drew conclusions regarding the significance of various columns. In the second project, we addressed the challenge of language diversity by translating the "titles" variable to ensure all information was in a single language. Once we have done this, we deleted the punctuation marks and stopwords using the library -----. Then we used the library CountVectorizer in the process of the titles vectorization. Due to the importance of the number of data in the training of the models, we implemented the Synthetic Minority Oversampling Technique with the objetive to obtain a balanced dataset. Finally, we tested multiple models to achieve optimal performance: Logistic Regression, SVM, K-Neighbors, BernoulliNB, Decision Tree, Random Forest and Ada Boost.

After evaluating all of them, we selected Random Forest due to its accuracy of 90.62%.
