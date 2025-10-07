# Not All Candidates are Created Equal: A Heterogeneity-Aware Approach to Pre-ranking in Recommender Systems
In industrial recommender systems, the pre-ranking stage serves as a critical middle layer between retrieval and ranking, tasked with filtering thousands of candidates down to hundreds — all within millisecond-level latency budgets. However, these candidates are highly heterogeneous: some are easy to distinguish, while others closely resemble ground-truth positives. This mix leads to conflicting gradient signals during training and inefficient computation in deployment.
![System Architecture](imgs/rec_system.pdf)
![Gradient Conflicts](imgs/grad_confict.pdf)
