## Toxic Comment Classification Challenge
This practical assessment simulates a 2018 Kaggle challenge for $35000 focusing on classifying the level of toxicity in disrespectful comments on social media. Kaggle, a prominent online community for data scientists and machine learning practitioners, hosts machine learning competitions where participants compete to build effective algorithms. The Toxic Comment Classification Challenge, a popular Kaggle competition since 2018, involves developing methods for detecting and classifying various levels of toxicity in online comments.

More info on the challenge can be found [here](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge):

### To complete this assignment
Please carry out the following tasks:

**Perform detailed data analysis of the dataset provided by the competition, observing:**

- Number of sentences and tokens per class (and check if the dataset is unbalanced or not).
- Analyse the most common words for each class and, therefore, understand the most used terms for each level of toxicity.

**Select three Machine Learning algorithms among the ones listed below(many of these methods were explored in this module and previous ones):**
- Support Vector Machine (SVM)
- K-Nearest Neighbours (KNN)
- NaïveBayes
- Decision Trees
- Logistic Regression
- Random Forest
- Multi-LayerPerceptron
  
Analyse their performance in classifying the level of toxicity of different comments. Please make use of the main metrics **(accuracy, F1-score, Recall, Precision, and AUC)** to compare the different algorithms. Additionally, clearly explain the parameters defined for each model. Any MLpython Library can be used during implementation(such as sklearn and keras).

Consider the main Feature Extraction methods studied in previous Lectures, such as TF-IDF and WordEmbeddings. Using the same three classifier previously analysed, change the Feature Extraction method initially used (for example, if you used Word Embeddings, change to TF-IDF) and repeat the previous experiments and observe if there is any considerable difference between the new results and the previous one (i.e. if the method of feature extraction impacts the classification performance).

Submit your best algorithm to the competition page and check how good it performs in comparison with other groups in the leader board. Discuss the reasons of that performance and what could be done to improve your proposed solution(maximum of two paragraphs).
