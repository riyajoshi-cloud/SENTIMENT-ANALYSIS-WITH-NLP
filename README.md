# SENTIMENT-ANALYSIS-WITH-NLP

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: RIYA JOSHI

*INTERN ID*: CT04DZ615

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

## Description of the Task

The main objective of the task was to analyze a dataset of customer reviews and build a model that could predict the sentiment behind each review. Since the data was in text format, I had to follow a pipeline that involved data preprocessing, feature extraction, model building, and evaluation.

First, I imported the dataset using pandas. The dataset consisted of customer reviews along with sentiment labels (positive or negative). The preprocessing step was crucial because raw text data contains noise such as stopwords, punctuation, numbers, and sometimes special characters. To clean the text, I applied steps like converting all words to lowercase, removing stopwords, tokenizing, and applying stemming/lemmatization. These steps ensured that only the most relevant words were retained for analysis.

After preprocessing, I converted the text data into numerical features using TF-IDF Vectorization (Term Frequency – Inverse Document Frequency). This technique assigns weights to words based on how important they are in a given review compared to the entire dataset. It helped capture the significance of words like excellent, poor, love, or worst, which strongly indicate sentiment.

Once the feature vectors were ready, I used a Logistic Regression classifier to build the model. Logistic Regression is a simple yet effective algorithm for binary classification tasks like this one. I split the dataset into training (80%) and testing (20%) sets using train_test_split, trained the model on the training set, and then tested it on the unseen data.

The evaluation was done using metrics like accuracy score, precision, recall, F1-score, and confusion matrix. The accuracy of the model came out to be fairly good, and it was able to distinguish positive and negative reviews effectively. This step highlighted how well the model generalized and whether it was biased towards a particular class.

For this project, I used Jupyter Notebook as my development platform. Jupyter Notebook is particularly suitable for machine learning projects because it allows running the code step by step while displaying the output instantly. I also documented my process alongside the code, making the notebook both executable and readable.

The libraries I used included pandas and numpy for data handling, scikit-learn for machine learning algorithms, nltk (Natural Language Toolkit) for text preprocessing, and matplotlib for visualizing evaluation results. The integration of these libraries in Python made the entire workflow smooth anD efficient.

Applicability of the Task

Sentiment Analysis is one of the most practical applications of NLP and is widely used across industries. Some common applications include:

Business and Marketing – Companies analyze product reviews and customer feedback to improve their services.

Social Media Monitoring – Organizations use sentiment analysis to track public opinion about brands, political events, or social issues on platforms like Twitter.

Customer Support – Automated systems detect customer emotions in support tickets or chats to prioritize urgent issues.

Entertainment Industry – Movie producers and streaming platforms analyze audience reviews to understand reactions to new releases.

The task made me realize the importance of text preprocessing. Without cleaning and transforming the data, the model would not be able to understand human language. This also showed me the challenges of NLP, such as handling sarcasm, slang, or mixed emotions in a review. Still, techniques like TF-IDF combined with machine learning models provide a strong baseline for sentiment classification.

In conclusion, this project on Sentiment Analysis with NLP helped me develop both technical and conceptual knowledge. I learned how to preprocess raw text data, convert it into numerical features, and apply machine learning algorithms to classify sentiment. Working with TF-IDF and Logistic Regression gave me a solid foundation in text-based machine learning.

Using Jupyter Notebook as the editor made the process interactive and easy to manage, while Python’s NLP and ML libraries provided all the necessary tools.

Most importantly, I realized how valuable sentiment analysis is in real-world scenarios, especially for businesses that rely on customer feedback. This task not only improved my technical skills but also gave me a deeper understanding of how machine learning can be applied to everyday problems.
