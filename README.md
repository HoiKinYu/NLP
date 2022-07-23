# Natural Language Processing - NLP
This repository sharing my practice on Natural Language Processing (NLP) by different dataset.

### Algorithms in NLP:
1. Similarity Search - Facebook AI Similarity Search (Faiss)

### Logs:
2022-07-22 Uploaded ***Similarity Search - Facebook AI  Faiss - Twitter Airline Dataset 220722.ipynb***

***Executive Summary:***

In this notebook, a pole is attached by an un-actuated joint to a cart, which moves along a frictionless track and ***the goal is to prevent it from falling over.*** I try differnet methods to complete this goal. First, ***a simle policy to choose actions by monitoring the Velocity of Pole Angular***, but the ***average score only reach 181 out of 500***. Second, the ***agent with deep learning nerual network with Keras*** received 500 out of 500 scores starting from 36220 episode***. Third, the ***agent with Epsilon-Greedy Policy reach perfect score at epoch #31*** during the learning process in only 6 minutes of learning. Forth, the ***agent with Deep Crossentropy Method (Monte Carlo Method)*** with ***mean reward reach 499 at around 25 sessions***. Finally, the ***Actor Critic Network with 2 fully conneted layers***, it reach ***highest performance in episode 8437 with score 364*** and ***avgerage score 335.9***. (Time spend 9h 45min)

What is Facebook AI Similarity Search (Faiss)?

- Faiss is a library developed by Facebook AI — that enables ***efficient similarity search***.

- Given a set of vectors, we can index them using Faiss

- Using another vector (the query vector), we ***search for the most similar vectors within the index***.

Twitter Airline Dataset originally came from: https://appen.com/pre-labeled-datasets/

----------------------------------------------------------------------------------------------------------
