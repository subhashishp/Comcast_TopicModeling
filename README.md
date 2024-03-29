# Comcast_TopicClustering

### About The Project
Comcast is an American global telecommunication company. The firm has been providing terrible customer service. They continue to fall short despite repeated promises to improve. Only last month 
(October 2016) the authority fined them $2.3 million, after receiving over 1000 consumer complaints.

-----

### Objective:-
A project to make an Exploratory Data Analysis to find insight into feedback they receive. Comcast is an American global telecommunication company.

-----
### Dataset:-
From Kaggle - https://www.kaggle.com/datasets/archaeocharlie/comcastcomplaints

-----

Used BERTopic, a topic modeling technique that leverages 🤗 transformers and c-TF-IDF to create dense clusters allowing for easily interpretable topics while keeping important words in the topic descriptions.

Applied hierarchical clustering on the topics generated on the reviews by the BERT model to get an overall idea of the kind of problems on which customers are complaining.

Cluster 1 (C1): These are problems related to outages, internet speed, and modem-related problems. 
2066 Reviews - 46.54%

Cluster 2 (C2): Are extra billing-related and hidden charges
1382 Reviews - 31.13%

Cluster 3 (C3): Are problems related to customer care behavior or service provided or technician-related problems
991 Reviews - 22.32%

![image](https://github.com/subhashishp/Comcast_TopicModeling/assets/69890203/0709ac03-e40d-4b72-a96f-cabf0b9b967d)

Topic Model
The most frequently discussed issues in each cluster

![image](https://github.com/subhashishp/Comcast_TopicModeling/assets/69890203/eb13d08f-9e65-49ec-8d6c-d9638e30648c)
Similar topics containing clusters can be merged to form a bigger cluster.
#### Overall 3 Clusters form.

----

### Challenges faced

1. It was difficult to decide between the clustering model. Eventually dropped HDBSCAN (which is considered the best) as it was hard to control the number of clusters leading to poor results.
2. Choosing the number of clusters for best results was a challenge.
-----

### Show your support
Give a ⭐️ if this project helped you!
