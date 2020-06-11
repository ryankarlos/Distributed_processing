
# Spam Detection in Apache Spark 

## *Spam detection using the lingspam dataset in pyspark*

The dataset is freely available at http://csmining.org/index.php/ling-spam-datasets.html

As per the CSMNING GROUP website the structure of the dataset is described in quotations below:

"There are four subdirectories, corresponding to four versions of the corpus:
bare: Lemmatiser disabled, stop-list disabled.
lemm: Lemmatiser enabled, stop-list disabled.
lemm_stop: Lemmatiser enabled, stop-list enabled.
stop: Lemmatiser disabled, stop-list enabled.
Each one of these 4 directories contains 10 subdirectories (part1, ..., part10). These correspond to the 10 partitions of the corpus that were used in the 10-fold experiments. In each repetition, one part was reserved for testing and the other 9 were used for training" 

The overall goal of this mini-project was to transform the data into so that we can build a classifier. The effect of following factors on classification accuracy will be explored:
* the size of the training set 
*  the size of the representation vector, and
* the preprocessing with stopword removal and/or lemmatisation.

