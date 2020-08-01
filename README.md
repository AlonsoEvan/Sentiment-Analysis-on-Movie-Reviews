# Sentiment-Analysis-on-Movie-Reviews
Kaggle Project

The Rotten Tomatoes movie review dataset is a corpus of movie reviews used for sentiment analysis. 
This competition presents a chance to benchmark your sentiment-analysis ideas on the Rotten Tomatoes dataset.
We are asked to label phrases on a scale of five values: negative, somewhat negative, neutral, somewhat positive, positive.
Obstacles like sentence negation, sarcasm, terseness, language ambiguity, and many others make this task very challenging.

Kaggle is hosting this competition for the machine learning community to use for fun and practice.


## Table of Contents
<details open>
<summary>Show/Hide</summary>
<br>

1. [ File Descriptions ](#File_Description)
2. [ Technologies Used ](#Technologies_Used)    
3. [ Structure ](#Structure)
4. [ Future Development ](#Executive_Summary)
</details>

## File Descriptions
<details>
<a name="File_Description"></a>
<summary>Show/Hide</summary>
<br>
  
The dataset is comprised of tab-separated files with phrases from the Rotten Tomatoes dataset. The train/test split has been preserved for the purposes of benchmarking, but the sentences have been shuffled from their original order. Each Sentence has been parsed into many phrases by the Stanford parser. Each phrase has a PhraseId. Each sentence has a SentenceId. Phrases that are repeated (such as short/common words) are only included once in the data.

train.tsv contains the phrases and their associated sentiment labels. We have additionally provided a SentenceId so that you can track which phrases belong to a single sentence.
test.tsv contains just phrases. You must assign a sentiment label to each phrase.
The sentiment labels are:

0 - negative
1 - somewhat negative
2 - neutral
3 - somewhat positive
4 - positive

</details>

## Technologies Used:
<details>
<a name="Technologies_Used"></a>
<summary>Show/Hide</summary>
<br>
    
* <strong>Python</strong>
* <strong>Pandas</strong>
* <strong>Numpy</strong>
* <strong>Matplotlib</strong>
* <strong>Seaborn</strong>
* <strong>NLTK</strong>
* <strong>WordCloud</strong>
* <strong>Scikit-Learn</strong>
* <strong>Keras</strong>
* <strong>Tensorflow</strong>
</details>

## Structure of Notebooks:
<details>
<a name="Structure"></a>
<summary>Show/Hide</summary>
<br>
    
1. Import packages

2. Data Exploration
   * 2.1 Number of characters in tweets
   * 2.2 Number of words in tweets
   * 2.3 Average word length in a tweet

3. Deep Learning methods
   * 3.1 Basic NLP Techniques
   * 3.2 Building model
   * 3.3 Model performances
   * 3.4 First submission to Kaggle

4. Machine Learning methods
   * 4.1 Basic NLP Techniques
   * 4.2 Building models
   * 4.3 Models performances
   * 4.4 Second Submission to Kaggle
</details>  


<a name="Executive_Summary"></a>
## Future Development
    
* Like always, I would like to deploy my best model with heroku to show easily how it works.
