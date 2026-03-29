# Shakespeare Sentiment Analysis (NLP Project)

## Objective
This project applies basic Natural Language Processing (NLP) techniques to text from Shakespeare’s works in order to classify the sentiment of sentences.

## Approach
The program first loads Shakespeare text and performs several preprocessing steps. These include converting the text to lowercase, removing punctuation, tokenizing the sentences, removing stopwords, and applying stemming.  

After preprocessing, a rule-based sentiment analyzer compares the processed tokens with predefined positive and negative word lists to calculate a sentiment score for each sentence.

## Difficulties Faced
One of the main challenges was that Shakespeare’s language often includes complex and archaic vocabulary. Many of these words were not present in the initial sentiment word lists, which affected the accuracy of the sentiment classification.

## Resolution
To improve the results, the preprocessing pipeline was enhanced by adding stemming and expanding the sentiment word lists. This allowed the program to recognize a wider range of words and improved sentiment detection.

## Results
The system successfully analyzes sentences from Shakespeare’s text and classifies them as **Positive**, **Negative**, or **Neutral** based on their sentiment score.

## Learnings
Through this project, the following NLP concepts were explored:

- Basic NLP preprocessing  
- Tokenization  
- Stopword removal  
- Stemming  
- Rule-based sentiment analysis  

## How to Run

1. Install the required library:

```
pip install nltk
```

2. Run the Python script or notebook.

3. Make sure the Shakespeare text file is in the same folder as the program.

4. The program will process the text and print the sentence, sentiment score, and predicted sentiment.
