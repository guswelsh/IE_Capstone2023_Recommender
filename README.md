# **MIND (MIcrosoft News Dataset) News Recommendation**
### Capstone Project - IE School of Science and technology - 2023

- Gustavo Welsh
- Dilhan Tanir
- Pierre-Louis Berlemont
- Felipe Basurto
- Ramón Peláez
-----------------

MIcrosoft News Dataset (MIND) is a large-scale dataset for news recommendation research. It was collected from anonymized behavior logs of Microsoft News website. The mission of MIND is to serve as a benchmark dataset for news recommendation and facilitate the research in news recommendation and recommender systems area.

MIND contains about 160k English news articles and more than 15 million impression logs generated by 1 million users. Every news article contains rich textual content including title, abstract, body, category and entities. Each impression log contains the click events, non-clicked events and historical news click behaviors of this user before this impression. To protect user privacy, each user was de-linked from the production system when securely hashed into an anonymized ID.

----------------

| Mind - demo 
| Model   | group_auc | mean_mrr | ndcg@5 | ndcg@10 |
|----------|----------|----------|--------|---------|
| Popularity    |   -  |   -  | 0.2766 |  0.333 |
| Random    |   -  |   -  | 0.2194 |  0.3631 |
| NPA    |   0.5968   |   0.2718   | 0.2926  |  0.3601 |
| NMRS    |   0.6169  |   0.2729  | 0.2948 |  0.3659 |
| NAML    |   0.6187  |   0.2848  | 0.3098 |  0.3736 |
| LSTUR    |   0.6443  |   0.2961  | 0.327 |  0.3897 |

| Mind - small
| Model   | group_auc | mean_mrr | ndcg@5 | ndcg@10 |
|----------|----------|----------|--------|---------|
| NRMS    |   0.6175  |   0.2723  | 0.2943 |  0.3645 |
| LSTUR    |   0.6622  |   0.31  | 0.3435 |  0.4066 |

| Mind - large
| Model   | group_auc | mean_mrr | ndcg@5 | ndcg@10 |
|----------|----------|----------|--------|---------|
| LSTUR    |   0.6806  |   0.3295  | 0.3629 |  0.427 |
