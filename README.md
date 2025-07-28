# NLP_final_project
# Built emotional classification system using pre-trained models
# Project Statement
This Project aims to classify emotions based on texts into six different categories that include
Sadness, Joy, Anger, Fear, Surprise and Love.

Goal of this Project:
Develop an effective Classification model that analyses different sentiments in social media and business platforms using pre-trained models like Distilbert and gpt-2
# Model Architecture
Distil-BERT: The model is trained using distil-BERT which is lighter weight version of BERT model having 66M
Parameters which is effective for classification tasks and sentiment analysis.
The model imports sequence classification from distil BERT specially fined tuned for category classification. It is easier to load and fast for training the dataset.
GPT-2: The model is trained using GPT-2 pre trained model excellent to generate long text and documents but special library GPT2forsequenceclassification is good for classification tasks for complex dataset.
This model uses 1.5 Billion parameters and takes almost 15 to 20 times more time to train the dataset. It is mainly used for generating tasks but depending on data it can be used for classification tasks and in some research papers it outperforms other transformer models.
# kaggle dataset link
https://www.kaggle.com/datasets/nelgiriyewithana/emotions

# link to my Project: https://colab.research.google.com/drive/15mHp6cDCLUGqxvn08T6czF_CNGifXb-x?usp=sharing




