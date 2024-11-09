# Sentiment-Analysis-with-Deep-Learning-using-BERT

##Data Set Used 
SMILE Twitter Emotion dataset
This dataset is collected and annotated for the SMILE project http://www.culturesmile.org. This collection of tweets mentioning 13 Twitter handles associated with British museums was gathered between May 2013 and June 2015. It was created for the purpose of classifying emotions, expressed on Twitter towards arts and cultural experiences in museums.
It contains 3,085 tweets, with 5 emotions namely anger, disgust, happiness, surprise and sadness. 
Link : https://www.kaggle.com/datasets/ashkhagan/smile-twitter-emotion-dataset

## What is BERT
BERT (Bidirectional Encoder Representations from Transformers) is a language model developed by Google that uses a deep learning technique called "transformers" to understand the context of words in a sentence, both from left-to-right and right-to-left. Unlike previous models that looked at text one direction at a time, BERT reads text in both directions, which is called bidirectional training. This allows it to grasp deeper context, especially for ambiguous language.

## The Sentiment Analysis Model
The Sentiment Analysis model is built using a pre-trained BERT transformer for large-scale language learning and is trained on the SMILE annotations dataset using the PyTorch framework. The architecture is designed for multi-class classification. Exploratory Data Analysis (EDA) was performed, followed by loading the tokenizer and encoding the data. Data loaders were created for batch processing, and an optimizer and scheduler were set up to manage the model's training.

Performance metrics were defined, and a training loop was implemented to fine-tune the BERT model in PyTorch, accelerating the process. After fine-tuning, the pre-trained model was loaded, and its performance was evaluated, achieving strong accuracy.
