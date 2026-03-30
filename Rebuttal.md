
## Data Leakage

![GP across LLMs without leakage](./gp_across_llms_no_leakage.png)

Figure 1. This figure compares the performance of Gaussian Process (GP)-based Bayesian Optimization across different models, including LLM-based approaches and non-LLM baselines, under a controlled setting designed to avoid data leakage. The results show that all methods—including those that do not rely on LLM priors or fingerprints—exhibit similar trends, suggesting that the observed performance gains are not driven by memorization or leakage from pretraining data. Instead, the improvements are consistent with the inductive biases introduced by the modeling approach.

![Average GAP across different feature models and datastes for different LLM APIs](./gap_visualization_api_ablation.png)

![Average Regret across different feature models and datastes for different LLM APIs](./regret_visualization_api_ablation.png)
