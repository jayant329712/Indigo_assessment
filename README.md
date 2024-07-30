# Indigo_assessment

We aimed to create an AI system for generating accurate responses to user queries using a dataset from Quora. We explored, cleaned, and preprocessed the data, and tested various models (GPT-2, T5, BERT) using metrics like ROUGE, BLEU, and F1-score. Hyperparameter tuning was attempted to improve performance. Libraries used included Hugging Face Transformers, Datasets, and Plotly for visualization. Despite poor initial scores, we explored fine-tuning and parameter adjustments, generating insights and suggesting improvements for better results.

**Tech Stack** : Python 

**Objective Definition:**

**Goal:** Create an AI system capable of understanding and generating accurate responses to user queries, mimicking human-like interaction.
Data Loading and Preprocessing:

**Loaded dataset from Quora.**
Explored and cleaned the data to remove irrelevant information.
Applied NLP techniques such as tokenization, stop word removal, and stemming/lemmatization.

**Initial Model Testing:**
Tested various NLP models (GPT-2, T5, BERT) to generate responses.
Used metrics like ROUGE, BLEU, and F1-score to assess model performance.
Hyperparameter Tuning:

Attempted to improve BLEU and ROUGE scores by tuning hyperparameters like max_length, temperature, top_k, and top_p for GPT-2.
Evaluated the performance of different parameter combinations.
**Error Handling:**
Addressed issues such as missing special tokens in BERT.
Adjusted the approach to use a compatible BERT-based sequence-to-sequence model.

**Model Evaluation**

Calculated ROUGE, BLEU, and F1 scores for each model and hyperparameter combination.
Visualized performance metrics using Plotly.

**Insights and Improvements:**

Extracted insights from data distribution, feature importance, and model performance.
Suggested improvements based on insights, such as simplifying questions, shortening answers, and focusing on common words in questions and answers.

**Libraries and Metrics Used**
Libraries:

Hugging Face Transformers (for models and tokenizers)
Datasets (for loading and preprocessing data)
Plotly (for visualizations)
Pandas (for data manipulation)
PrettyPrint (for displaying insights)

**Metrics:**

ROUGE (for recall-oriented understanding)
BLEU (for precision-oriented understanding)
F1-score (for harmonic mean of precision and recall)








