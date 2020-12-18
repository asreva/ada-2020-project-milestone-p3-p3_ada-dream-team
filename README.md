# P3 Milestone submission: Friendship and home position 
### 1. Abstract:
Our project extension aims to inspect the difference in quantity, quality and distribution of friends according to where a person lives. Cultural factors, as well as geography and political decisions, may influence the result. We will analyse the problem in different countries.
To do so, we will use BrightKite and Gowalla datasets. From them, we will compute users' nationalities and friendships characteristics such as proximity, quantity of friends and frequency of meeting. With these data, we will be able to assert (or no) the significance of regional disparities. We will inspect further the underlying causes of those disparities using another dataset that includes characteristics of each country (mobility, wealth, ...). 
By doing this study, we may find the factors that increase the number of friends or bring them closer, which may be solutions against the threat of depression and isolation augmentation.
### 2. Research Questions:
1. Is there differences in terms of friendship characteristics depending on the country?
2. What are the factors that impact the number of friends? 
3. What are the factors that impact the proximity of friends?
4. What are the factors that impact the quality of friendships?
5. Is there a relation between the number and quality of friendships?
6. How does friendship characteristics impact happiness?
### 3. Proposed dataset:
1. Gowalla dataset: https://snap.stanford.edu/data/loc-gowalla.html. A dataset from the paper. Checkins of users and friends relationship.
2. Brightkite dataset: https://snap.stanford.edu/data/loc-Brightkite.html. A dataset from the paper. Checkins of users and friends relationship.
3. Compilation of UNData: https://www.kaggle.com/sudalairajkumar/undata-country-profiles. Different characteristics for each country.
4. Compilation of USGovt: https://www.kaggle.com/fernandol/countries-of-the-world. More characteristics for each country.
5. happiness2020.pkl and countries_info.csv from "tutorial 01- Handling data". More characteristics for each country.
### 4. Methods:
1. Mapping (home position to country belonging)
2. Clustering
3. Anova test and Kruskal-Wallis test
4. Correlation matrix
5. Pair plots
6. PCA
7. Linear regression
### 5. Proposed timeline:
Week 12
1. Compute the nationalities
2. Compute friendships characteristics (number of friends, proximity of them, frequency of meetings)
Week 13
3. Find similarities and disparities between countries based on country characteristics
4. Find similarities and disparities between countries based on friendship characteristics
Week 14
5. Infer the factors that influence friendships characteristics for each country
6. Infer the relations between quality and quantity of friends for each user
7. Revising and commeting code
8. Plotting and reporting results
### 6. Organization within the team:
1. Compute the nationalities [Week 12] (Iván-Daniel)
2. Compute friendships characteristics (number of friends, proximity of them, frequency of meetings) [Week 12] (Thibault & Andrés)
3. Find similarities and disparities between countries based on country characteristics[Week 13] (Iván-Daniel & Thibault)
4. Find similarities and disparities between countries based on friendship characteristics[Week 13] (Iván-Daniel & Thibault)
5. Infer the factors that influence friendships characteristics for each country (feature importance) [Week 14] (Andrés & Iván-Daniel)
6. Infer the relations between quality and quantity of friends for each user [Week 14] (Andrés)
7. Revising and commeting code [Week 14] (All members in collaboration)
8. Plotting and reporting results [Week 14] (All members in collaboration)
