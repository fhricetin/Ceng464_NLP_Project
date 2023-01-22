# Ceng464 NLP Project

Project Description

Part A
A.1. There are two different folders in the dataset named ‘neg’ and ‘pos’. Read the data files and combine them to use as a whole. Examine the data in detail and clean it while applying 4 different preprocessing methods which are proper for the data.

Part B.
B.1.Choose 4 different general features fit for the data and extract these features from the cleaned dataset.
B.2. Create Bag of Words and Term Frequency-Inverse Document Frequency models for the data that you cleaned in step A, compare 10 most frequently occurring words and choose one of the models which you think is more suitable to use as a feature for that dataset.
B.3. With the model that you choose in step B.2, determine the 50 most frequently occurring words and visualize them with Word Clouds.
B.4. Apply 4 machine learning algorithms to develop text classifiers into your data using features you extracted in part B. Apply k-means clustering, linear regression, one classification method and one tree based method that you think is more suitable for the data. Calculate the performance measures: confusion matrix, precision, F1 score, receiver operating characteristic (ROC) curve, root mean square error (RMSE). (Note: Decide the k by yourselves while trying a specific range).

Part C
C. Apply topic modeling to data that you cleaned in part A. Use Latent Dirichlet Allocation (LDA) algorithm. Decide the correct number of topics. Then, compare its results with K- Means algorithm.

Part D
D. Apply the text summarization method using TextRank algorithm for both ‘neg’ and ‘pos’ files in the dataset. Save the summarized texts as two different new .txt files (neg_summarized.txt, pos_summarized.txt).

Part E
E. Train a sentiment model that models the dataset as positive and negative sentences. Using the cleaned data in part A extract a specific feature and apply a machine learning algorithm. Divide data into test and train sets and use test sets to predict the sentiment of data that is not seen before. Calculate the accuracy of your model.
