# RSS Evaluation Artifacts

The following are the artifacts for the RSS paper:

- All Evaluations on Benchmark #1: [re_v2_all_files.pkl](re_v2_all_files.pkl)
- [Jupyter Notebook on the comparison between PDF and KL - Benchmark #2](PDF_vs_KL.ipynb) (Figure 2)
- [Dataset for the summary of data (Table 1-Avg) - Benchmark #2](benchmark_2_pdf_kl_mean.pickle)
- [Dataset for the summary of data (Table 1-Std) - Benchmark #2](benchmark_2_pdf_kl_std.pickle)
- All AutoML evaluations for CD plot: [all_cd_data.pickle](all_cd_data.pickle)
- [Jupyter Notebook for AutoML CD Plot](automl_cd.ipynb) which produces a [TeX file](automl_cd.tex)
- All AutoML evaluations on extra time budgets for 10 datasets with 10 random seeds: [10_dataset_10_seed_extra_time.pkl](10_dataset_10_seed_extra_time.pkl)
- All other plots for Benchmark #1: Source files come from $R^2$ evaluations as `R2_B.pickle` where $B=\beta$ and $\beta \in [0, 10, 100, 1k]$ based on the number of strata. Similarly, for RMSE evaluation, use `RMSE_B.pickle`. [A compiled version of Jupyter Notebook #1 for all other plots](Benchmark_1_all_plots.ipynb) (i.e., Figure 3, 7, 8, 9).
