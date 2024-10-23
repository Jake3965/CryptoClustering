# CryptoClustering
Utilized lessons from class, reviewed all recorded sessions (I missed 10/17 class)
utilized extension add ins:
- "Code Runner" to run code in the notebook
Copilot
Amazon Q
proofed code with ChatGPT

Answers to questions asked in the notebook:

1) #### Answer the following question: 
**Question:** What is the best value for `k`?

**Answer:** 4 clusters are the best value for 'k'.

2) #### Answer the following question: 

**Question:** What is the total explained variance of the three principal components?

**Answer:** 0.3719856 + 0.34700813 + 0.17603793 = 0.89503166, The total explained variance is about 89.5% of the variance in the original data. 

3) #### Answer the following questions: 
* **Question:** What is the best value for `k` when using the PCA data?

  * **Answer:** 4 Clusters is the best value for 'k' with PCA Data.


* **Question:** Does it differ from the best k value found using the original data?

  * **Answer:** No, botht the PCA and Original data '4' was the best value for 'k'.

4) #### Answer the following question: 

* **Question:** Which features have the strongest positive or negative influence on each component? 
 
* **Answer:** 

For PCA1:

Strongest Positive Influence: price_change_percentage_200d (0.594468) and price_change_percentage_1y (0.568379) have the strongest positive influence on PCA1.
Strongest Negative Influence: price_change_percentage_24h (-0.416728) has the strongest negative influence on PCA1.

For PCA2:

Strongest Positive Influence: price_change_percentage_14d (0.540415) and price_change_percentage_30d (0.562182) have the strongest positive influence on PCA2.
Strongest Negative Influence: price_change_percentage_1y (-0.150789) has the strongest negative influence on PCA2.

For PCA3:

Strongest Positive Influence: price_change_percentage_7d (0.787670) has the strongest positive influence on PCA3.
Strongest Negative Influence: price_change_percentage_60d (-0.361377) has the strongest negative influence on PCA3.
    