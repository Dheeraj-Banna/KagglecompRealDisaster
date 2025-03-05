Predicting Real Disasters from Tweets
Social media platforms like Twitter are often the first places where breaking news, including disasters, is shared. However, distinguishing between real disaster-related tweets and unrelated chatter is a challenging task.
In this competition, participants will build machine learning models to classify tweets as either real disaster tweets or non-disaster tweets. The dataset consists of labeled tweets, providing a mix of genuine crisis-related posts and unrelated content.
Objective:
Develop a model that accurately predicts whether a tweet describes a real disaster or not. Your solution will help improve automated crisis response systems by filtering out noise and ensuring that emergency responders and organizations can focus on real emergencies.
Dataset:
Train.csv – Contains tweets labeled as disaster (1) or not (0).
Test.csv – Contains tweets for which you need to predict the disaster label.
Sample_submission.csv – The format in which you should submit your predictions.
Evaluation Metric:
The model will be evaluated using F1 Score, which balances precision and recall, making it well-suited for handling imbalanced datasets.
