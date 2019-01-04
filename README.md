## Movie-Review-Sentiment-Analysis
## [Kernel Link](https://www.kaggle.com/c/movie-review-sentiment-analysis-kernels-only)
## [My Kernel](https://www.kaggle.com/aaneloy/movie-review-sentiment-analysis)

## Description
"There's a thin line between likably old-fashioned and fuddy-duddy, and The Count of Monte Cristo ... never quite settles on either side."

The Rotten Tomatoes movie review dataset is a corpus of movie reviews used for sentiment analysis, originally collected by Pang and Lee [1]. In their work on sentiment treebanks, Socher et al. [2] used Amazon's Mechanical Turk to create fine-grained labels for all parsed phrases in the corpus. This competition presents a chance to benchmark your sentiment-analysis ideas on the Rotten Tomatoes dataset. You are asked to label phrases on a scale of five values: negative, somewhat negative, neutral, somewhat positive, positive. Obstacles like sentence negation, sarcasm, terseness, language ambiguity, and many others make this task very challenging.

## Evaluation
Submissions are evaluated on classification accuracy (the percent of labels that are predicted correctly) for every parsed phrase. The sentiment labels are:

```
0 - negative
1 - somewhat negative
2 - neutral
3 - somewhat positive
4 - positive

```
