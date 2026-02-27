**Sentiment Analysis on Product Reviews**

This project performs Sentiment Analysis on product reviews using Natural Language Processing (NLP) techniques. The goal is to classify customer reviews based on their ratings and textual feedback.

The repository includes:

Dataset (data.csv)

Trained model (sentiment_model.pkl)

Jupyter Notebook (sentiment_task.ipynb)

📁 *Project Structure*
<img width="717" height="143" alt="image" src="https://github.com/user-attachments/assets/90c8d5d8-97d2-40b7-b5b0-23cf1ec264da" />


*Data Insights*

Total Reviews: 8,518

Rating Scale: 1 to 5

Majority of reviews are 5-star ratings

Dataset is skewed toward positive sentiment

Ratings column has no missing values

Rating Distribution

⭐ 1 Star: 769

⭐ 2 Stars: 308

⭐ 3 Stars: 615

⭐ 4 Stars: 1,746

⭐ 5 Stars: 5,080

*Problem Statement*

Build a machine learning model to:

Perform Sentiment Classification

Predict review sentiment from text

Optionally classify into:

Negative (1–2)

Neutral (3)

Positive (4–5)

*Technologies Used*

1.Python

2.Pandas

3.NumPy

4.Scikit-learn

5.Natural Language Processing (NLP)

6.Pickle (Model Serialization)

*Workflow*

1.Data Loading

2.Data Cleaning & Preprocessing

3.Text Vectorization (e.g., TF-IDF)

4.Model Training

5.Model Evaluation

6.Model Saving (sentiment_model.pkl)

*Conclusion*
This project demonstrates a complete NLP pipeline for sentiment analysis, from data preprocessing to model deployment. It can be extended further for real-world applications like:

- Customer feedback monitoring

- Product review analysis

- Brand reputation tracking
