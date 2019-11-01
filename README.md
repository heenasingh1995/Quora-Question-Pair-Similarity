# Quora-Question-Pair-Similarity
Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term. so main aim of project is that predicting whether pair of questions are similar or not. This could be useful to instantly provide answers to questions that have already been answered. Credits: Kaggle

## Problem Statement:

Identify which questions asked on Quora are duplicates of questions that have already been asked.

## Real world/Business Objectives and Constraints :
* The cost of a mis-classification can be very high.
* You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.
* No strict latency concerns.
* Interpretability is partially important
## Performance Metric:
* log-loss
* Binary Confusion Matrix

## Data Overview:
Source of Data : https://www.kaggle.com/c/quora-question-pairs/data

* Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate
* Number of rows in Train.csv = 404,290

## References:
* https://www.kaggle.com/c/quora-question-pairs
* https://www.kaggle.com/c/quora-question-pairs/discussion
* Applied AI Course
* https://github.com/seatgeek/fuzzywuzzy#usage , https://chairnerd.seatgeek.com/fuzzywuzzy-fuzzy-string-matching-in-python/
* http://proceedings.mlr.press/v37/kusnerb15.pdf