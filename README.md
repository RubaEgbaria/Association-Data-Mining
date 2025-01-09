Assignment Two

Association Data Mining

In this assignment, you will explore unsupervised knowledge discovery techniques of association rule mining and sequential patterns mining. In particular, you will apply the Apriori algorithm on a real-world dataset for SPAM analysis.

Dataset Information

The data is contained in the file Spam_SMS.csv, which is accessible through the course’s Moodle. Each record is a message (“tweet”) and a description where the message is classified as ham or spam.

Goal

Your goal is to perform Association Rule Discovery on the dataset using:

The Apriori algorithm.

The Frequent-Pattern Growth algorithm (FP-Growth algorithm).

Steps

Tokenize the messages into binary form, indicating the existence or absence of each word.

Perform association rule discovery on the transformed data.

Experiment with different parameters to generate at least 80-100 strong rules (e.g., rules with high lift and confidence and relatively good support).

Tasks

List the top 10 popular items for each algorithm.

Create a bar plot visualization of the top 10 popular items for each algorithm.

Generate a scatterplot of the rules:

Scatterplot of support vs. confidence for the generated rules for each algorithm.

Select the top 5 most interesting rules from each algorithm, where the consequent is only ham or spam, and for each rule:

Provide an explanation of the pattern and why it is interesting based on the objectives.

Provide any recommendations based on the discovered rule that might help in identifying spam.

Notes

The top 5 most interesting rules are most likely not the top 5 in the result set. These are rules that, in addition to having high support, lift, and confidence, also provide non-trivial and actionable knowledge based on the underlying problem objectives.

