# Sentiment Analysis -Amazon Fine Food Reviews

In this project, I conducted sentiment analysis on Amazon Fine Food Reviews using two distinct approaches as a part of machine learning (ML) project:
* VADER (Valence Aware Dictionary and sEntiment Reasoner) - Bag of words approach: a rule-based sentiment analysis tool based on a bag-of-words approach, particularly tuned for social media text and short reviews.
* RoBERTa (A Robustly Optimized BERT Pretraining Approach): a transformer-based model from Hugging Face's 🤗 Transformers library, pre-trained on a large corpus to understand context and nuances in natural language.
* Using the Hugging Face pipeline, I applied the RoBERTa model directly to the review dataset, allowing for seamless and scalable inference. I compared the outputs of both models across a range of reviews and sentiment categories to evaluate their performance and interpretability.

**Dataset**: I used the Amazon Fine Food Reviews dataset available on [Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews). This dataset contains over 500,000 food reviews from Amazon, including:
- Review text
- Summary
- User information
- Product ID
- Time of review

Both, VADER and RoBERTa models are widely used for natural language processing (NLP) tasks such as sentiment analysis, text classification, and recommendation systems.

Click [here](https://sachinbasyal.com/da-projects/project-sa) to view the complete project report.
