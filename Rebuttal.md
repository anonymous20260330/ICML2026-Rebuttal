


![GP across LLMs without leakage](./gp_across_llms_no_leakage.png)

**Figure 1.** This figure compares the performance of Gaussian Process (GP) across different feature models, including LLM-based features and non-LLM features (fingerprints). The results show that all methods exhibit similar trends, where all methods improve gradually over BO iterations rather than converging early, suggesting that the observed performance gains are not driven by memorization or leakage from pretraining data. Instead, the improvements are consistent with the inductive biases introduced by the modeling approach.

![Average GAP across different feature models for different LLM APIs](./gap_visualization_api_ablation.png)
**Figure 2.: API ablation across feature models on Redox-mer dataset.** Average GAP over BO rounds for different LLM APIs (GPT-4o, Gemini-2.5-pro and Qwen3.5-Plus) across multiple feature representations. Shaded regions denote variability across runs. Results show consistent performance trends across APIs, with stronger models (e.g., Gemini-2.5-pro and Qwen3.5-Plus) achieving faster convergence. Overall, It suggests that BO performance is robust to the choice of LLM API and primarily driven by the underlying algorithmic design.

![Average Regret across different feature models for different LLM APIs](./regret_visualization_api_ablation.png)
**Figure 3.: API ablation across feature models on Redox-mer dataset.** Average Regret over BO rounds for different LLM APIs (GPT-4o, Gemini-2.5-pro and Qwen3.5-Plus) across multiple feature representations. Shaded regions denote variability across runs. Results show consistent performance trends across APIs, with stronger models (e.g., Gemini-2.5-pro and Qwen3.5-Plus) achieving faster convergence. Overall, It suggests that BO performance is robust to the choice of LLM API and primarily driven by the underlying algorithmic design.
