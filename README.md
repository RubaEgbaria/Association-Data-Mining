Assignment Two
Association Data Mining
In this Assignment you will explore unsupervised knowledge discovery techniques of association rule 
mining and sequential patterns mining. In particular you will apply the priori algorithm on a real-world data set
for SPAM analysis.
The data is contained in the file Spam_SMS.csv which is accessible through the course’s Moodle. Each 
record is a message “tweet” and a description where the message is ham or spam. Your goal is to perform 
Association Rule discovery on the data set using
1. The priori algorithm.
2. Frequent-Pattern growth algorithm (FP growth algorithm)
Note: you first need to tokenize the message into binary form such as exist or not exist. 
Next perform association rule discovery on the transformed data. Experiment with different parameters so 
that you get at least 80-100 strong rules (e.g., rules with high lift and confidence which at the same time have 
relatively good support). Then:
➢ List the top 10 popular items for each algorithm
➢ Bar plot visualization of the 10 top popular items for each algorithm
➢ scatterplot of the rules was generated i.e. scatter plot between support and confidence of the generated rules
for each algorithm
➢ Select the top 5 most interesting rules from each algorithm that their consequent is only ham or spam and 
for each specify the following:
• An explanation of the pattern and why you believe it is interesting based on the objectives
• Any recommendations based on the discovered rule that might help in discovering spam. 
Note: The top 5 most interesting rules are most likely not the top 5 in the result set. They are rules that, in 
addition to having high support, lift, and confidence, also provide some non-trivial, actionable knowledge based 
on the underlying problem objectives. 
