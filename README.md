# Sampling

 Creditcards.csv has a dataset about credit cards. It is a binary classification problem. The dataset is imbalanced and hence it is balanced by using random over sampling technique. After balancing the dataset, different sampling techniques are used and 5 different models have been applied to get the accuracy on testing set. The dataset is divided into a 20-80 ratio of testing and training set.
# Methodology
Balancing Dataset

Creating different types of samples

Training different machine learning models

Testing the models

Analysing the Result obtained

# Sampling Technique Description and Sampling Size Formula

# Simple Random Sampling 

Simple random sampling is a type of probability sampling in which the researcher randomly selects a subset of participants from a population. Each member of the population has an equal chance of being selected. Data is then collected from as large a percentage as possible of this random subset
A simple random sample is a subset of a statistical population in which each member of the subset has an equal probability of being chosen.
image

Z = 1.96 (for 95% confidence)

p = 0.5

E = 0.03 (assumed 3%)

n = 1067

# Stratified Sampling

Stratified random sampling is a method of sampling that involves the division of a population into smaller subgroups known as strata. In stratified random sampling, or stratification, the strata are formed based on members' shared attributes or characteristics, such as income or educational attainment.
image

Z = 1.96 (for 95% confidence)

p = 0.5

E = 0.07 (assumed 7%)

S = 2

n = 784 (392 for each class)

# Systematic Sampling 

Systematic sampling is a type of probability sampling method in which sample members from a larger population are selected according to a random starting point but with a fixed, periodic interval. This interval, called the sampling interval, is calculated by dividing the population size by the desired sample size.

# Cluster Sampling

Cluster sampling is a probability sampling method in which you divide a population into clusters, such as districts or schools, and then randomly select some of these clusters as your sample. The clusters should ideally each be mini-representations of the population as a whole.

Rows per Cluster = 20

Number of Clusters = 28 (sqrt(n/2) where n is the total number of rows)

# Multi-Stage Sampling

In this method we have used a combination of sampling technique, i.e. cluster and simple random. The dataset is divided into clusters and then random samples are chosen from those clusters. During this sampling method, significant clusters of the selected people are split into sub-groups at various stages to make it simpler for primary data collection.




Written By
Name : Riya

Roll No. : 102003451

Sub-Group: 3CO18
