# amazon-reviews-sentiment-analysis
This project analyzes Amazon product reviews using NLP. It compares sentiment analysis results from NLTK's VADER (a rule-based model) and Huggingface's RoBERTa (a transformer-based model) to classify reviews as positive, negative, or neutral and evaluate model performance.

Developed a complete sentiment analysis pipeline to evaluate customer reviews from Amazon using both traditional and transformer-based NLP models. Preprocessed and analyzed large-scale review data, applying VADER for lexicon-based sentiment scoring and RoBERTa via Hugging Face Transformers for contextual sentiment classification. Fine-tuned and deployed a RoBERTa sentiment model using the pipeline abstraction, achieving high-accuracy predictions on real-world text. Visualized comparative performance metrics across both models using Matplotlib and Seaborn. Focused on exploring how transformer-based models outperform traditional approaches by capturing deeper semantic nuances in textual data.

Key Highlights:

Used Hugging Face Transformers to implement state-of-the-art RoBERTa model for contextual sentiment classification.

Compared VADER (rule-based) and RoBERTa (context-aware) models to evaluate performance and accuracy.

Handled over 200MB+ of review data while ensuring GitHub compatibility by applying .gitignore and history rewriting for large files.

Created dynamic visualizations to communicate sentiment trends and model comparison.

Dataset reference - https://www.kaggle.com/code/robikscube/sentiment-analysis-python-youtube-tutorial/input
