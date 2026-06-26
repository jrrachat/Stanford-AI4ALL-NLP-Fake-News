# Stanford-AI4ALL-NLP-Fake-News
This project builds a fake news detector by combining multiple NLP techniques into a single ensemble model. 
We analyze news articles using linguistic features (punctuation patterns, capitalization), TF-IDF text representations with Naive Bayes, and a RoBERTa classifier with the LIAR dataset. These signals are combined as input features to a Gradient Boosting classifier, with 94% accuracy on the fake/real news dataset.

Datasets: Fake/True news CSV dataset (Kaggle) + LIAR dataset (also found on Kaggle)

Demo on Hugging Face located here: https://huggingface.co/spaces/rachat/fakenewsdetector


