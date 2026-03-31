


![GP across LLMs without leakage](./gp_across_llms_no_leakage.png)

**Figure 1.** This figure compares the performance of Gaussian Process (GP) across different feature models, including LLM-based features and non-LLM features (fingerprints). The results show that all methods exhibit similar trends, where all methods improve gradually over BO iterations rather than converging early, suggesting that the observed performance gains are not driven by memorization or leakage from pretraining data. Instead, the improvements are consistent with the inductive biases introduced by the modeling approach.

![Average GAP across different feature models for different LLM APIs](./gap_visualization_api_ablation.png)

![Average Regret across different feature models for different LLM APIs](./regret_visualization_api_ablation.png)
