Feedback Classifier
Project Description
This project uses the lightweight DistilGPT-2 language model to generate synthetic feedback for educational video content. The feedback is classified into key categories such as:

Content Clarity
Engagement
Relevance
Pacing
Technical Issues
A balanced synthetic dataset (15,000 comments) is created, and a classification model is trained to analyze and evaluate the quality of educational materials.

Features
Synthetic Feedback Generation: Automatically generates realistic feedback using DistilGPT-2.
Balanced Dataset Creation: Ensures equal representation across feedback categories.
Classification Model: Trains a machine learning model (e.g., Logistic Regression, BERT) to classify feedback.
Scalable Design: Designed for expansion to other domains or datasets.
Technologies Used
Language Model: DistilGPT-2 (via Hugging Face Transformers)
Programming Language: Python
Libraries:
transformers for LLM
pandas for data handling
scikit-learn for classification
torch for LLM support

Project Workflow
Synthetic Feedback Generation:
Use DistilGPT-2 to generate 3,000 comments for each feedback category.

Dataset Preparation:
Preprocess and clean the generated comments.
Save as a structured CSV file.

Classification Model Training:
Train a machine learning model (e.g., Logistic Regression or BERT).

Evaluation:
Evaluate the model using accuracy, precision, recall, and F1-score metrics.
Deployment (Optional):
Deploy the model as a feedback analysis tool.
