This directory contains the Ling-Spam corpus,the along with email spam detection using Naive bayes and Suppoer vector machines :
code also contains comparison of both along with crossvalidations for both the algorithms 

There are four subdirectories, corresponding to four versions of the corpus:

bare: Lemmatiser disabled, stop-list disabled.
lemm: Lemmatiser enabled, stop-list disabled.
lemm_stop: Lemmatiser enabled, stop-list enabled.
stop: Lemmatiser disabled, stop-list enabled.

Each one of these 4 directories contains 10 subdirectories (part1, 
..., part10). These correspond to the 10 partitions of the corpus 
that were used in the 10-fold experiments. 

Each one of the 10 subdirectories contains both spam and legitimate 
messages, one message in each file. Files whose names have the form
spmsg*.txt are spam messages. All other files are legitimate messages.

Out of the entire copus part 1-5 of bare directory are used as train-test data .


TODO before running: 
change the directory path as per your convinence
run naivebayes and svm files to get the desired outputs

