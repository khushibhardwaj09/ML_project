# ML_project

# Introduction & Background: 
In today’s rapidly evolving financial landscape, with the popularization of digital payments, credit card fraud is a significant concern. According to the 2023 Credit Card Fraud Report, 65% of credit card holders in the US have been victims of credit card fraud. Previous research on fraudulent credit transactions uses several machine learning classifiers.  Logistic Regression determines the probability of fraudulent transactions through a linear function (Ileberi et al.) whereas Random Forest combines Decision Trees to determine fraudulence based on majority classification. Naive Bayes assumes feature independence to estimate fraud likelihood (Ileberi et. al.). Sulaiman et al. proposes ANNs, which involves layered nodes for precise classification in a privacy-focused federated learning framework and genetic algorithms aid in feature selection to enhance model accuracy (Ileberi et. al.). 

Our study will consider various transaction features such as location, amount, method, and user history in the datasets that we are looking into.

# Problem Definition:
Scammers are continually adapting to advances in fraud detection systems. Therefore, it remains highly challenging to differentiate between legitimate and fraudulent credit transactions. We aim to develop a model that can predict the authenticity of a transaction with high accuracy based on a wide variety of features. 

# Methods:
For our methods, we will utilize an existing credit card transaction dataset which contains attributes such as location, transaction amount, and user purchase history. We preprocess the data to address missing values and other issues as necessary. Following this, we will use various machine learning models as mentioned before. We will partition the dataset into training and testing datasets; the former will be used to train our machine learning models while the latter will be used to evaluate their performance. Additionally, we will use cross-validation to ensure that the model performs ideally on various splits. 

# Results and Discussion:
We will utilize multiple metrics to evaluate the correctness of our model. We will primarily use accuracy to measure the correctness of the detection of fraud and the F1-score, that combines both precision and recall to assess the balance between correctly identifying fraud cases and capturing all cases. Additionally, we will use Matthew’s Correlation Coefficient (MCC) to measure the correlation coefficient for classes of different sizes in the case of an imbalanced data set. Other metrics we plan on using include receiver operating characteristic (ROC) curve, area under the curve (AUC-ROC), confusion matrix, and feature importance. 

The discussion will revolve around how well our model performs in comparison to existing research, highlighting its strengths and weaknesses. We'll also consider the practical implications of deploying such a model in real-world financial systems, including privacy concerns, scalability, and adaptability to evolving fraud tactics. 

# Potential Datasets:
* Dataset 1 - contains various transaction details such as location, amount, and type
* Dataset 2 - contains a large series of data points, but is highly imbalanced and feature titles are hidden for confidentiality purposes

# Sources:
* 2023 credit card fraud report. Security.org. (2023, May 22). https://www.security.org/digital-safety/credit-card-fraud-report/
* Bin Sulaiman, R., Schetinin, V. & Sant, P. Review of Machine Learning Approach on Credit Card Fraud Detection. Hum-Cent Intell Syst 2, 55–68 (2022). https://doi.org/10.1007/s44230-022-00004-0
* Dornadula, V. N. and Geetha, S. Credit Card Fraud Detection using Machine Learning Algorithms. Procedia Computer Science 165, 631–641 (2019). https://doi.org/10.1016/j.procs.2020.01.057
* Ileberi, E., Sun, Y. & Wang, Z. A machine learning based credit card fraud detection using the GA algorithm for feature selection. J Big Data 9, 24 (2022). https://doi.org/10.1186/s40537-022-00573-8

# Contributions:
* Introduction/Background: Shreya Malpani, Ishita Verma, Khushi Bhardwaj 
* Problem Definition: Shreya Malpani and Ishita Verma
* Gantt Chart: Shreya Malpani and Ishita Verma
* Methods: Amirita Manickandan and Priyanka Mosur
* Potential Results & Discussion: Khushi Bhardwaj, Priyanka Mosur, Amirita Manickandan
* Video: Amirita Manickandan and Priyanka Mosur
* GitHub Pages: Khushi Bhardwaj, Priyanka Mosur, Amirita Manickandan

