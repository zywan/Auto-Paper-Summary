# Auto-Paper-Summary

We want to build a auto-paper-summary based on LSTM.

For the dataset part, we have two candidates. The first one is DUC 2003 and 2004 dataset. The second one is NIST 2015 dataset. Both of those two have great reputation. However, DUC dataset contains lots of unnecessary massages so we prefer NIST 2015 dataset for now.

First, we turn word into vectors which the computer should recognize. Second, we use the method of LSTM to train our label and vectors. This give us our model. Then, we turn the paper from the user into vectors and use it as the input of our model, we should get output vectors. At last, we turn the output vectors into words and print out the summary we make. 

For the website building part, we want to use Django based on Python. User can input a paper on our website and we are able to give them a summarization directly. For now, we prefer the default database sqlite3. If it fails to fulfill our needs, we would try MySQL.
