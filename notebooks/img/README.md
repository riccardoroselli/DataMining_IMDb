# Figure index

Every plot in this project exists twice: embedded in the notebook that produced
it, and extracted to a file here, so a figure can be linked to from the README
or the report without opening a notebook.

One directory per notebook. Files are numbered in the order their outputs appear
in that notebook and named from the `plt.title()` of the plot that made them.
Two groups are named positionally instead, because their source cannot name them:
the four untitled histograms in `00`, and the loop-generated shapelet and motif
plots in `04` and `05`, whose titles are f-strings filled in at runtime.

**318 figures** across 9 notebooks.

| Notebook | Figures |
|---|---:|
| [`00_preprocessing_and_outlier_detection.ipynb`](../00_preprocessing_and_outlier_detection.ipynb) | 4 |
| [`01a_imbalanced_grouped_rating_binary.ipynb`](../01a_imbalanced_grouped_rating_binary.ipynb) | 61 |
| [`01b_imbalanced_grouped_rating_multiclass.ipynb`](../01b_imbalanced_grouped_rating_multiclass.ipynb) | 61 |
| [`01c_imbalanced_is_adult.ipynb`](../01c_imbalanced_is_adult.ipynb) | 61 |
| [`01d_imbalanced_title_type.ipynb`](../01d_imbalanced_title_type.ipynb) | 29 |
| [`02_advanced_classification.ipynb`](../02_advanced_classification.ipynb) | 23 |
| [`03_explainable_ai.ipynb`](../03_explainable_ai.ipynb) | 6 |
| [`04_time_series_classification.ipynb`](../04_time_series_classification.ipynb) | 68 |
| [`05_sequential_pattern_mining.ipynb`](../05_sequential_pattern_mining.ipynb) | 5 |

## `00_preprocessing_and_outlier_detection.ipynb`

| # | Figure | Source cell |
|---:|---|---:|
| 1 | [`01_knn_imputed_vs_observed_runtime_distribution.png`](00_preprocessing_and_outlier_detection/01_knn_imputed_vs_observed_runtime_distribution.png) | 59 |
| 2 | [`02_isolation_forest_score_distribution.png`](00_preprocessing_and_outlier_detection/02_isolation_forest_score_distribution.png) | 69 |
| 3 | [`03_isolation_forest_vs_hbos_scores.png`](00_preprocessing_and_outlier_detection/03_isolation_forest_vs_hbos_scores.png) | 72 |
| 4 | [`04_isolation_forest_minus_hbos_score_difference.png`](00_preprocessing_and_outlier_detection/04_isolation_forest_minus_hbos_score_difference.png) | 73 |

## `01a_imbalanced_grouped_rating_binary.ipynb`

| # | Figure | Source cell |
|---:|---|---:|
| 1 | [`01_distribution_of_groupedrating_preprocessed.png`](01a_imbalanced_grouped_rating_binary/01_distribution_of_groupedrating_preprocessed.png) | 7 |
| 2 | [`02_distribution_of_groupedrating_no_outliers.png`](01a_imbalanced_grouped_rating_binary/02_distribution_of_groupedrating_no_outliers.png) | 9 |
| 3 | [`03_decision_tree_confusion_matrix_preprocessed.png`](01a_imbalanced_grouped_rating_binary/03_decision_tree_confusion_matrix_preprocessed.png) | 13 |
| 4 | [`04_decision_tree_roc_curves_preprocessed.png`](01a_imbalanced_grouped_rating_binary/04_decision_tree_roc_curves_preprocessed.png) | 13 |
| 5 | [`05_decision_tree_confusion_matrix_nooutliers.png`](01a_imbalanced_grouped_rating_binary/05_decision_tree_confusion_matrix_nooutliers.png) | 14 |
| 6 | [`06_decision_tree_roc_curves_nooutliers.png`](01a_imbalanced_grouped_rating_binary/06_decision_tree_roc_curves_nooutliers.png) | 14 |
| 7 | [`07_class_distribution_after_rus.png`](01a_imbalanced_grouped_rating_binary/07_class_distribution_after_rus.png) | 19 |
| 8 | [`08_decision_tree_confusion_matrix_rus_preprocessed.png`](01a_imbalanced_grouped_rating_binary/08_decision_tree_confusion_matrix_rus_preprocessed.png) | 19 |
| 9 | [`09_decision_tree_roc_curves_rus_preprocessed.png`](01a_imbalanced_grouped_rating_binary/09_decision_tree_roc_curves_rus_preprocessed.png) | 19 |
| 10 | [`10_class_distribution_after_rus_nooutliers.png`](01a_imbalanced_grouped_rating_binary/10_class_distribution_after_rus_nooutliers.png) | 20 |
| 11 | [`11_decision_tree_confusion_matrix_rus_nooutliers.png`](01a_imbalanced_grouped_rating_binary/11_decision_tree_confusion_matrix_rus_nooutliers.png) | 20 |
| 12 | [`12_decision_tree_roc_curves_rus_nooutliers.png`](01a_imbalanced_grouped_rating_binary/12_decision_tree_roc_curves_rus_nooutliers.png) | 20 |
| 13 | [`13_class_distribution_after_tomek_links.png`](01a_imbalanced_grouped_rating_binary/13_class_distribution_after_tomek_links.png) | 22 |
| 14 | [`14_decision_tree_confusion_matrix_tomek_links_preprocessed.png`](01a_imbalanced_grouped_rating_binary/14_decision_tree_confusion_matrix_tomek_links_preprocessed.png) | 22 |
| 15 | [`15_decision_tree_roc_curves_tomek_links_preprocessed.png`](01a_imbalanced_grouped_rating_binary/15_decision_tree_roc_curves_tomek_links_preprocessed.png) | 22 |
| 16 | [`16_class_distribution_after_tomek_links_nooutliers.png`](01a_imbalanced_grouped_rating_binary/16_class_distribution_after_tomek_links_nooutliers.png) | 23 |
| 17 | [`17_decision_tree_confusion_matrix_tomek_links_nooutliers.png`](01a_imbalanced_grouped_rating_binary/17_decision_tree_confusion_matrix_tomek_links_nooutliers.png) | 23 |
| 18 | [`18_decision_tree_roc_curves_tomek_links_nooutliers.png`](01a_imbalanced_grouped_rating_binary/18_decision_tree_roc_curves_tomek_links_nooutliers.png) | 23 |
| 19 | [`19_class_distribution_after_enn.png`](01a_imbalanced_grouped_rating_binary/19_class_distribution_after_enn.png) | 25 |
| 20 | [`20_decision_tree_confusion_matrix_enn_preprocessed.png`](01a_imbalanced_grouped_rating_binary/20_decision_tree_confusion_matrix_enn_preprocessed.png) | 25 |
| 21 | [`21_decision_tree_roc_curves_enn_preprocessed.png`](01a_imbalanced_grouped_rating_binary/21_decision_tree_roc_curves_enn_preprocessed.png) | 25 |
| 22 | [`22_class_distribution_after_enn_nooutliers.png`](01a_imbalanced_grouped_rating_binary/22_class_distribution_after_enn_nooutliers.png) | 26 |
| 23 | [`23_decision_tree_confusion_matrix_enn_nooutliers.png`](01a_imbalanced_grouped_rating_binary/23_decision_tree_confusion_matrix_enn_nooutliers.png) | 26 |
| 24 | [`24_decision_tree_roc_curves_enn_nooutliers.png`](01a_imbalanced_grouped_rating_binary/24_decision_tree_roc_curves_enn_nooutliers.png) | 26 |
| 25 | [`25_class_distribution_after_cluster_centroids.png`](01a_imbalanced_grouped_rating_binary/25_class_distribution_after_cluster_centroids.png) | 30 |
| 26 | [`26_decision_tree_confusion_matrix_cluster_centroids_preprocessed.png`](01a_imbalanced_grouped_rating_binary/26_decision_tree_confusion_matrix_cluster_centroids_preprocessed.png) | 30 |
| 27 | [`27_decision_tree_roc_curves_cluster_centroids_preprocessed.png`](01a_imbalanced_grouped_rating_binary/27_decision_tree_roc_curves_cluster_centroids_preprocessed.png) | 30 |
| 28 | [`28_class_distribution_after_cluster_centroids_nooutliers.png`](01a_imbalanced_grouped_rating_binary/28_class_distribution_after_cluster_centroids_nooutliers.png) | 31 |
| 29 | [`29_decision_tree_confusion_matrix_cluster_centroids_nooutliers.png`](01a_imbalanced_grouped_rating_binary/29_decision_tree_confusion_matrix_cluster_centroids_nooutliers.png) | 31 |
| 30 | [`30_decision_tree_roc_curves_cluster_centroids_nooutliers.png`](01a_imbalanced_grouped_rating_binary/30_decision_tree_roc_curves_cluster_centroids_nooutliers.png) | 31 |
| 31 | [`31_class_distribution_after_random_oversampling.png`](01a_imbalanced_grouped_rating_binary/31_class_distribution_after_random_oversampling.png) | 34 |
| 32 | [`32_decision_tree_confusion_matrix_random_oversampling_preprocessed.png`](01a_imbalanced_grouped_rating_binary/32_decision_tree_confusion_matrix_random_oversampling_preprocessed.png) | 34 |
| 33 | [`33_decision_tree_roc_curves_random_oversampling_preprocessed.png`](01a_imbalanced_grouped_rating_binary/33_decision_tree_roc_curves_random_oversampling_preprocessed.png) | 34 |
| 34 | [`34_class_distribution_after_random_oversampling_nooutliers.png`](01a_imbalanced_grouped_rating_binary/34_class_distribution_after_random_oversampling_nooutliers.png) | 35 |
| 35 | [`35_decision_tree_confusion_matrix_random_oversampling_nooutliers.png`](01a_imbalanced_grouped_rating_binary/35_decision_tree_confusion_matrix_random_oversampling_nooutliers.png) | 35 |
| 36 | [`36_decision_tree_roc_curves_random_oversampling_nooutliers.png`](01a_imbalanced_grouped_rating_binary/36_decision_tree_roc_curves_random_oversampling_nooutliers.png) | 35 |
| 37 | [`37_class_distribution_after_smote.png`](01a_imbalanced_grouped_rating_binary/37_class_distribution_after_smote.png) | 37 |
| 38 | [`38_decision_tree_confusion_matrix_smote_preprocessed.png`](01a_imbalanced_grouped_rating_binary/38_decision_tree_confusion_matrix_smote_preprocessed.png) | 37 |
| 39 | [`39_decision_tree_roc_curves_smote_preprocessed.png`](01a_imbalanced_grouped_rating_binary/39_decision_tree_roc_curves_smote_preprocessed.png) | 37 |
| 40 | [`40_class_distribution_after_smote_nooutliers.png`](01a_imbalanced_grouped_rating_binary/40_class_distribution_after_smote_nooutliers.png) | 38 |
| 41 | [`41_decision_tree_confusion_matrix_smote_nooutliers.png`](01a_imbalanced_grouped_rating_binary/41_decision_tree_confusion_matrix_smote_nooutliers.png) | 38 |
| 42 | [`42_decision_tree_roc_curves_smote_nooutliers.png`](01a_imbalanced_grouped_rating_binary/42_decision_tree_roc_curves_smote_nooutliers.png) | 38 |
| 43 | [`43_class_distribution_after_adasyn.png`](01a_imbalanced_grouped_rating_binary/43_class_distribution_after_adasyn.png) | 40 |
| 44 | [`44_decision_tree_confusion_matrix_adasyn_preprocessed.png`](01a_imbalanced_grouped_rating_binary/44_decision_tree_confusion_matrix_adasyn_preprocessed.png) | 40 |
| 45 | [`45_decision_tree_roc_curves_adasyn_preprocessed.png`](01a_imbalanced_grouped_rating_binary/45_decision_tree_roc_curves_adasyn_preprocessed.png) | 40 |
| 46 | [`46_class_distribution_after_adasyn_nooutliers.png`](01a_imbalanced_grouped_rating_binary/46_class_distribution_after_adasyn_nooutliers.png) | 41 |
| 47 | [`47_decision_tree_confusion_matrix_adasyn_nooutliers.png`](01a_imbalanced_grouped_rating_binary/47_decision_tree_confusion_matrix_adasyn_nooutliers.png) | 41 |
| 48 | [`48_decision_tree_roc_curves_adasyn_nooutliers.png`](01a_imbalanced_grouped_rating_binary/48_decision_tree_roc_curves_adasyn_nooutliers.png) | 41 |
| 49 | [`49_original_class_distribution.png`](01a_imbalanced_grouped_rating_binary/49_original_class_distribution.png) | 44 |
| 50 | [`50_decision_tree_confusion_matrix_class_weights_balanced.png`](01a_imbalanced_grouped_rating_binary/50_decision_tree_confusion_matrix_class_weights_balanced.png) | 44 |
| 51 | [`51_decision_tree_roc_curves_class_weights_balanced.png`](01a_imbalanced_grouped_rating_binary/51_decision_tree_roc_curves_class_weights_balanced.png) | 44 |
| 52 | [`52_original_class_distribution_nooutliers.png`](01a_imbalanced_grouped_rating_binary/52_original_class_distribution_nooutliers.png) | 45 |
| 53 | [`53_decision_tree_confusion_matrix_class_weights_balanced_nooutliers.png`](01a_imbalanced_grouped_rating_binary/53_decision_tree_confusion_matrix_class_weights_balanced_nooutliers.png) | 45 |
| 54 | [`54_decision_tree_roc_curves_class_weights_balanced_nooutliers.png`](01a_imbalanced_grouped_rating_binary/54_decision_tree_roc_curves_class_weights_balanced_nooutliers.png) | 45 |
| 55 | [`55_decision_tree_confusion_matrix_manual_class_weights_preprocessed.png`](01a_imbalanced_grouped_rating_binary/55_decision_tree_confusion_matrix_manual_class_weights_preprocessed.png) | 47 |
| 56 | [`56_decision_tree_roc_curves_manual_class_weights_preprocessed.png`](01a_imbalanced_grouped_rating_binary/56_decision_tree_roc_curves_manual_class_weights_preprocessed.png) | 47 |
| 57 | [`57_original_class_distribution_nooutliers_2.png`](01a_imbalanced_grouped_rating_binary/57_original_class_distribution_nooutliers_2.png) | 48 |
| 58 | [`58_decision_tree_confusion_matrix_manual_class_weights_nooutliers.png`](01a_imbalanced_grouped_rating_binary/58_decision_tree_confusion_matrix_manual_class_weights_nooutliers.png) | 48 |
| 59 | [`59_decision_tree_roc_curves_manual_class_weights_nooutliers.png`](01a_imbalanced_grouped_rating_binary/59_decision_tree_roc_curves_manual_class_weights_nooutliers.png) | 48 |
| 60 | [`60_decision_tree_confusion_matrix_adjusted_thresholds_preprocessed.png`](01a_imbalanced_grouped_rating_binary/60_decision_tree_confusion_matrix_adjusted_thresholds_preprocessed.png) | 50 |
| 61 | [`61_decision_tree_roc_curves_adjusted_thresholds_preprocessed.png`](01a_imbalanced_grouped_rating_binary/61_decision_tree_roc_curves_adjusted_thresholds_preprocessed.png) | 50 |

## `01b_imbalanced_grouped_rating_multiclass.ipynb`

| # | Figure | Source cell |
|---:|---|---:|
| 1 | [`01_distribution_of_groupedrating_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/01_distribution_of_groupedrating_preprocessed.png) | 7 |
| 2 | [`02_distribution_of_groupedrating_no_outliers.png`](01b_imbalanced_grouped_rating_multiclass/02_distribution_of_groupedrating_no_outliers.png) | 9 |
| 3 | [`03_decision_tree_confusion_matrix.png`](01b_imbalanced_grouped_rating_multiclass/03_decision_tree_confusion_matrix.png) | 13 |
| 4 | [`04_decision_tree_roc_curves.png`](01b_imbalanced_grouped_rating_multiclass/04_decision_tree_roc_curves.png) | 13 |
| 5 | [`05_decision_tree_confusion_matrix_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/05_decision_tree_confusion_matrix_nooutliers.png) | 14 |
| 6 | [`06_decision_tree_roc_curves_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/06_decision_tree_roc_curves_nooutliers.png) | 14 |
| 7 | [`07_class_distribution_after_rus.png`](01b_imbalanced_grouped_rating_multiclass/07_class_distribution_after_rus.png) | 19 |
| 8 | [`08_decision_tree_confusion_matrix_rus_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/08_decision_tree_confusion_matrix_rus_preprocessed.png) | 19 |
| 9 | [`09_decision_tree_roc_curves_rus_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/09_decision_tree_roc_curves_rus_preprocessed.png) | 19 |
| 10 | [`10_class_distribution_after_rus_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/10_class_distribution_after_rus_nooutliers.png) | 20 |
| 11 | [`11_decision_tree_confusion_matrix_rus_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/11_decision_tree_confusion_matrix_rus_nooutliers.png) | 20 |
| 12 | [`12_decision_tree_roc_curves_rus_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/12_decision_tree_roc_curves_rus_nooutliers.png) | 20 |
| 13 | [`13_class_distribution_after_tomek_links.png`](01b_imbalanced_grouped_rating_multiclass/13_class_distribution_after_tomek_links.png) | 22 |
| 14 | [`14_decision_tree_confusion_matrix_tomek_links_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/14_decision_tree_confusion_matrix_tomek_links_preprocessed.png) | 22 |
| 15 | [`15_decision_tree_roc_curves_tomek_links_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/15_decision_tree_roc_curves_tomek_links_preprocessed.png) | 22 |
| 16 | [`16_class_distribution_after_tomek_links_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/16_class_distribution_after_tomek_links_nooutliers.png) | 23 |
| 17 | [`17_decision_tree_confusion_matrix_tomek_links_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/17_decision_tree_confusion_matrix_tomek_links_nooutliers.png) | 23 |
| 18 | [`18_decision_tree_roc_curves_tomek_links_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/18_decision_tree_roc_curves_tomek_links_nooutliers.png) | 23 |
| 19 | [`19_class_distribution_after_enn.png`](01b_imbalanced_grouped_rating_multiclass/19_class_distribution_after_enn.png) | 25 |
| 20 | [`20_decision_tree_confusion_matrix_enn_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/20_decision_tree_confusion_matrix_enn_preprocessed.png) | 25 |
| 21 | [`21_decision_tree_roc_curves_enn_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/21_decision_tree_roc_curves_enn_preprocessed.png) | 25 |
| 22 | [`22_class_distribution_after_enn_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/22_class_distribution_after_enn_nooutliers.png) | 26 |
| 23 | [`23_decision_tree_confusion_matrix_enn_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/23_decision_tree_confusion_matrix_enn_nooutliers.png) | 26 |
| 24 | [`24_decision_tree_roc_curves_enn_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/24_decision_tree_roc_curves_enn_nooutliers.png) | 26 |
| 25 | [`25_class_distribution_after_cluster_centroids.png`](01b_imbalanced_grouped_rating_multiclass/25_class_distribution_after_cluster_centroids.png) | 30 |
| 26 | [`26_decision_tree_confusion_matrix_cluster_centroids_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/26_decision_tree_confusion_matrix_cluster_centroids_preprocessed.png) | 30 |
| 27 | [`27_decision_tree_roc_curves_cluster_centroids_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/27_decision_tree_roc_curves_cluster_centroids_preprocessed.png) | 30 |
| 28 | [`28_class_distribution_after_cluster_centroids_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/28_class_distribution_after_cluster_centroids_nooutliers.png) | 31 |
| 29 | [`29_decision_tree_confusion_matrix_cluster_centroids_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/29_decision_tree_confusion_matrix_cluster_centroids_nooutliers.png) | 31 |
| 30 | [`30_decision_tree_roc_curves_cluster_centroids_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/30_decision_tree_roc_curves_cluster_centroids_nooutliers.png) | 31 |
| 31 | [`31_class_distribution_after_random_oversampling.png`](01b_imbalanced_grouped_rating_multiclass/31_class_distribution_after_random_oversampling.png) | 34 |
| 32 | [`32_decision_tree_confusion_matrix_random_oversampling_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/32_decision_tree_confusion_matrix_random_oversampling_preprocessed.png) | 34 |
| 33 | [`33_decision_tree_roc_curves_random_oversampling_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/33_decision_tree_roc_curves_random_oversampling_preprocessed.png) | 34 |
| 34 | [`34_class_distribution_after_random_oversampling_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/34_class_distribution_after_random_oversampling_nooutliers.png) | 35 |
| 35 | [`35_decision_tree_confusion_matrix_random_oversampling_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/35_decision_tree_confusion_matrix_random_oversampling_nooutliers.png) | 35 |
| 36 | [`36_decision_tree_roc_curves_random_oversampling_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/36_decision_tree_roc_curves_random_oversampling_nooutliers.png) | 35 |
| 37 | [`37_class_distribution_after_smote.png`](01b_imbalanced_grouped_rating_multiclass/37_class_distribution_after_smote.png) | 37 |
| 38 | [`38_decision_tree_confusion_matrix_smote_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/38_decision_tree_confusion_matrix_smote_preprocessed.png) | 37 |
| 39 | [`39_decision_tree_roc_curves_smote_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/39_decision_tree_roc_curves_smote_preprocessed.png) | 37 |
| 40 | [`40_class_distribution_after_smote_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/40_class_distribution_after_smote_nooutliers.png) | 38 |
| 41 | [`41_decision_tree_confusion_matrix_smote_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/41_decision_tree_confusion_matrix_smote_nooutliers.png) | 38 |
| 42 | [`42_decision_tree_roc_curves_smote_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/42_decision_tree_roc_curves_smote_nooutliers.png) | 38 |
| 43 | [`43_class_distribution_after_adasyn.png`](01b_imbalanced_grouped_rating_multiclass/43_class_distribution_after_adasyn.png) | 40 |
| 44 | [`44_decision_tree_confusion_matrix_adasyn_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/44_decision_tree_confusion_matrix_adasyn_preprocessed.png) | 40 |
| 45 | [`45_decision_tree_roc_curves_adasyn_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/45_decision_tree_roc_curves_adasyn_preprocessed.png) | 40 |
| 46 | [`46_class_distribution_after_adasyn_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/46_class_distribution_after_adasyn_nooutliers.png) | 41 |
| 47 | [`47_decision_tree_confusion_matrix_adasyn_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/47_decision_tree_confusion_matrix_adasyn_nooutliers.png) | 41 |
| 48 | [`48_decision_tree_roc_curves_adasyn_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/48_decision_tree_roc_curves_adasyn_nooutliers.png) | 41 |
| 49 | [`49_original_class_distribution.png`](01b_imbalanced_grouped_rating_multiclass/49_original_class_distribution.png) | 44 |
| 50 | [`50_decision_tree_confusion_matrix_class_weights_balanced.png`](01b_imbalanced_grouped_rating_multiclass/50_decision_tree_confusion_matrix_class_weights_balanced.png) | 44 |
| 51 | [`51_decision_tree_roc_curves_class_weights_balanced.png`](01b_imbalanced_grouped_rating_multiclass/51_decision_tree_roc_curves_class_weights_balanced.png) | 44 |
| 52 | [`52_original_class_distribution_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/52_original_class_distribution_nooutliers.png) | 45 |
| 53 | [`53_decision_tree_confusion_matrix_class_weights_balanced_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/53_decision_tree_confusion_matrix_class_weights_balanced_nooutliers.png) | 45 |
| 54 | [`54_decision_tree_roc_curves_class_weights_balanced_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/54_decision_tree_roc_curves_class_weights_balanced_nooutliers.png) | 45 |
| 55 | [`55_decision_tree_confusion_matrix_manual_class_weights_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/55_decision_tree_confusion_matrix_manual_class_weights_preprocessed.png) | 47 |
| 56 | [`56_decision_tree_roc_curves_manual_class_weights_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/56_decision_tree_roc_curves_manual_class_weights_preprocessed.png) | 47 |
| 57 | [`57_original_class_distribution_nooutliers_2.png`](01b_imbalanced_grouped_rating_multiclass/57_original_class_distribution_nooutliers_2.png) | 48 |
| 58 | [`58_decision_tree_confusion_matrix_manual_class_weights_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/58_decision_tree_confusion_matrix_manual_class_weights_nooutliers.png) | 48 |
| 59 | [`59_decision_tree_roc_curves_manual_class_weights_nooutliers.png`](01b_imbalanced_grouped_rating_multiclass/59_decision_tree_roc_curves_manual_class_weights_nooutliers.png) | 48 |
| 60 | [`60_decision_tree_confusion_matrix_adjusted_thresholds_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/60_decision_tree_confusion_matrix_adjusted_thresholds_preprocessed.png) | 50 |
| 61 | [`61_decision_tree_roc_curves_adjusted_thresholds_preprocessed.png`](01b_imbalanced_grouped_rating_multiclass/61_decision_tree_roc_curves_adjusted_thresholds_preprocessed.png) | 50 |

## `01c_imbalanced_is_adult.ipynb`

| # | Figure | Source cell |
|---:|---|---:|
| 1 | [`01_distribution_of_groupedrating_preprocessed.png`](01c_imbalanced_is_adult/01_distribution_of_groupedrating_preprocessed.png) | 7 |
| 2 | [`02_distribution_of_groupedrating_no_outliers.png`](01c_imbalanced_is_adult/02_distribution_of_groupedrating_no_outliers.png) | 9 |
| 3 | [`03_decision_tree_confusion_matrix_preprocessed.png`](01c_imbalanced_is_adult/03_decision_tree_confusion_matrix_preprocessed.png) | 13 |
| 4 | [`04_decision_tree_roc_curves_preprocessed.png`](01c_imbalanced_is_adult/04_decision_tree_roc_curves_preprocessed.png) | 13 |
| 5 | [`05_decision_tree_confusion_matrix_nooutliers.png`](01c_imbalanced_is_adult/05_decision_tree_confusion_matrix_nooutliers.png) | 15 |
| 6 | [`06_decision_tree_roc_curves_nooutliers.png`](01c_imbalanced_is_adult/06_decision_tree_roc_curves_nooutliers.png) | 15 |
| 7 | [`07_class_distribution_after_rus.png`](01c_imbalanced_is_adult/07_class_distribution_after_rus.png) | 20 |
| 8 | [`08_decision_tree_confusion_matrix_rus_preprocessed.png`](01c_imbalanced_is_adult/08_decision_tree_confusion_matrix_rus_preprocessed.png) | 20 |
| 9 | [`09_decision_tree_roc_curves_rus_preprocessed.png`](01c_imbalanced_is_adult/09_decision_tree_roc_curves_rus_preprocessed.png) | 20 |
| 10 | [`10_class_distribution_after_rus_nooutliers.png`](01c_imbalanced_is_adult/10_class_distribution_after_rus_nooutliers.png) | 21 |
| 11 | [`11_decision_tree_confusion_matrix_rus_nooutliers.png`](01c_imbalanced_is_adult/11_decision_tree_confusion_matrix_rus_nooutliers.png) | 21 |
| 12 | [`12_decision_tree_roc_curves_rus_nooutliers.png`](01c_imbalanced_is_adult/12_decision_tree_roc_curves_rus_nooutliers.png) | 21 |
| 13 | [`13_class_distribution_after_tomek_links.png`](01c_imbalanced_is_adult/13_class_distribution_after_tomek_links.png) | 23 |
| 14 | [`14_decision_tree_confusion_matrix_tomek_links_preprocessed.png`](01c_imbalanced_is_adult/14_decision_tree_confusion_matrix_tomek_links_preprocessed.png) | 23 |
| 15 | [`15_decision_tree_roc_curves_tomek_links_preprocessed.png`](01c_imbalanced_is_adult/15_decision_tree_roc_curves_tomek_links_preprocessed.png) | 23 |
| 16 | [`16_class_distribution_after_tomek_links_nooutliers.png`](01c_imbalanced_is_adult/16_class_distribution_after_tomek_links_nooutliers.png) | 24 |
| 17 | [`17_decision_tree_confusion_matrix_tomek_links_nooutliers.png`](01c_imbalanced_is_adult/17_decision_tree_confusion_matrix_tomek_links_nooutliers.png) | 24 |
| 18 | [`18_decision_tree_roc_curves_tomek_links_nooutliers.png`](01c_imbalanced_is_adult/18_decision_tree_roc_curves_tomek_links_nooutliers.png) | 24 |
| 19 | [`19_class_distribution_after_enn.png`](01c_imbalanced_is_adult/19_class_distribution_after_enn.png) | 26 |
| 20 | [`20_decision_tree_confusion_matrix_enn_preprocessed.png`](01c_imbalanced_is_adult/20_decision_tree_confusion_matrix_enn_preprocessed.png) | 26 |
| 21 | [`21_decision_tree_roc_curves_enn_preprocessed.png`](01c_imbalanced_is_adult/21_decision_tree_roc_curves_enn_preprocessed.png) | 26 |
| 22 | [`22_class_distribution_after_enn_nooutliers.png`](01c_imbalanced_is_adult/22_class_distribution_after_enn_nooutliers.png) | 27 |
| 23 | [`23_decision_tree_confusion_matrix_enn_nooutliers.png`](01c_imbalanced_is_adult/23_decision_tree_confusion_matrix_enn_nooutliers.png) | 27 |
| 24 | [`24_decision_tree_roc_curves_enn_nooutliers.png`](01c_imbalanced_is_adult/24_decision_tree_roc_curves_enn_nooutliers.png) | 27 |
| 25 | [`25_class_distribution_after_cluster_centroids.png`](01c_imbalanced_is_adult/25_class_distribution_after_cluster_centroids.png) | 31 |
| 26 | [`26_decision_tree_confusion_matrix_cluster_centroids_preprocessed.png`](01c_imbalanced_is_adult/26_decision_tree_confusion_matrix_cluster_centroids_preprocessed.png) | 31 |
| 27 | [`27_decision_tree_roc_curves_cluster_centroids_preprocessed.png`](01c_imbalanced_is_adult/27_decision_tree_roc_curves_cluster_centroids_preprocessed.png) | 31 |
| 28 | [`28_class_distribution_after_cluster_centroids_nooutliers.png`](01c_imbalanced_is_adult/28_class_distribution_after_cluster_centroids_nooutliers.png) | 32 |
| 29 | [`29_decision_tree_confusion_matrix_cluster_centroids_nooutliers.png`](01c_imbalanced_is_adult/29_decision_tree_confusion_matrix_cluster_centroids_nooutliers.png) | 32 |
| 30 | [`30_decision_tree_roc_curves_cluster_centroids_nooutliers.png`](01c_imbalanced_is_adult/30_decision_tree_roc_curves_cluster_centroids_nooutliers.png) | 32 |
| 31 | [`31_class_distribution_after_random_oversampling.png`](01c_imbalanced_is_adult/31_class_distribution_after_random_oversampling.png) | 35 |
| 32 | [`32_decision_tree_confusion_matrix_random_oversampling_preprocessed.png`](01c_imbalanced_is_adult/32_decision_tree_confusion_matrix_random_oversampling_preprocessed.png) | 35 |
| 33 | [`33_decision_tree_roc_curves_random_oversampling_preprocessed.png`](01c_imbalanced_is_adult/33_decision_tree_roc_curves_random_oversampling_preprocessed.png) | 35 |
| 34 | [`34_class_distribution_after_random_oversampling_nooutliers.png`](01c_imbalanced_is_adult/34_class_distribution_after_random_oversampling_nooutliers.png) | 36 |
| 35 | [`35_decision_tree_confusion_matrix_random_oversampling_nooutliers.png`](01c_imbalanced_is_adult/35_decision_tree_confusion_matrix_random_oversampling_nooutliers.png) | 36 |
| 36 | [`36_decision_tree_roc_curves_random_oversampling_nooutliers.png`](01c_imbalanced_is_adult/36_decision_tree_roc_curves_random_oversampling_nooutliers.png) | 36 |
| 37 | [`37_class_distribution_after_smote.png`](01c_imbalanced_is_adult/37_class_distribution_after_smote.png) | 38 |
| 38 | [`38_decision_tree_confusion_matrix_smote_preprocessed.png`](01c_imbalanced_is_adult/38_decision_tree_confusion_matrix_smote_preprocessed.png) | 38 |
| 39 | [`39_decision_tree_roc_curves_smote_preprocessed.png`](01c_imbalanced_is_adult/39_decision_tree_roc_curves_smote_preprocessed.png) | 38 |
| 40 | [`40_class_distribution_after_smote_nooutliers.png`](01c_imbalanced_is_adult/40_class_distribution_after_smote_nooutliers.png) | 39 |
| 41 | [`41_decision_tree_confusion_matrix_smote_nooutliers.png`](01c_imbalanced_is_adult/41_decision_tree_confusion_matrix_smote_nooutliers.png) | 39 |
| 42 | [`42_decision_tree_roc_curves_smote_nooutliers.png`](01c_imbalanced_is_adult/42_decision_tree_roc_curves_smote_nooutliers.png) | 39 |
| 43 | [`43_class_distribution_after_adasyn.png`](01c_imbalanced_is_adult/43_class_distribution_after_adasyn.png) | 41 |
| 44 | [`44_decision_tree_confusion_matrix_adasyn_preprocessed.png`](01c_imbalanced_is_adult/44_decision_tree_confusion_matrix_adasyn_preprocessed.png) | 41 |
| 45 | [`45_decision_tree_roc_curves_adasyn_preprocessed.png`](01c_imbalanced_is_adult/45_decision_tree_roc_curves_adasyn_preprocessed.png) | 41 |
| 46 | [`46_class_distribution_after_adasyn_nooutliers.png`](01c_imbalanced_is_adult/46_class_distribution_after_adasyn_nooutliers.png) | 42 |
| 47 | [`47_decision_tree_confusion_matrix_adasyn_nooutliers.png`](01c_imbalanced_is_adult/47_decision_tree_confusion_matrix_adasyn_nooutliers.png) | 42 |
| 48 | [`48_decision_tree_roc_curves_adasyn_nooutliers.png`](01c_imbalanced_is_adult/48_decision_tree_roc_curves_adasyn_nooutliers.png) | 42 |
| 49 | [`49_original_class_distribution.png`](01c_imbalanced_is_adult/49_original_class_distribution.png) | 45 |
| 50 | [`50_decision_tree_confusion_matrix_class_weights_balanced.png`](01c_imbalanced_is_adult/50_decision_tree_confusion_matrix_class_weights_balanced.png) | 45 |
| 51 | [`51_decision_tree_roc_curves_class_weights_balanced.png`](01c_imbalanced_is_adult/51_decision_tree_roc_curves_class_weights_balanced.png) | 45 |
| 52 | [`52_original_class_distribution_nooutliers.png`](01c_imbalanced_is_adult/52_original_class_distribution_nooutliers.png) | 46 |
| 53 | [`53_decision_tree_confusion_matrix_class_weights_balanced_nooutliers.png`](01c_imbalanced_is_adult/53_decision_tree_confusion_matrix_class_weights_balanced_nooutliers.png) | 46 |
| 54 | [`54_decision_tree_roc_curves_class_weights_balanced_nooutliers.png`](01c_imbalanced_is_adult/54_decision_tree_roc_curves_class_weights_balanced_nooutliers.png) | 46 |
| 55 | [`55_decision_tree_confusion_matrix_manual_class_weights_preprocessed.png`](01c_imbalanced_is_adult/55_decision_tree_confusion_matrix_manual_class_weights_preprocessed.png) | 48 |
| 56 | [`56_decision_tree_roc_curves_manual_class_weights_preprocessed.png`](01c_imbalanced_is_adult/56_decision_tree_roc_curves_manual_class_weights_preprocessed.png) | 48 |
| 57 | [`57_original_class_distribution_nooutliers_2.png`](01c_imbalanced_is_adult/57_original_class_distribution_nooutliers_2.png) | 49 |
| 58 | [`58_decision_tree_confusion_matrix_manual_class_weights_nooutliers.png`](01c_imbalanced_is_adult/58_decision_tree_confusion_matrix_manual_class_weights_nooutliers.png) | 49 |
| 59 | [`59_decision_tree_roc_curves_manual_class_weights_nooutliers.png`](01c_imbalanced_is_adult/59_decision_tree_roc_curves_manual_class_weights_nooutliers.png) | 49 |
| 60 | [`60_decision_tree_confusion_matrix_adjusted_thresholds_preprocessed.png`](01c_imbalanced_is_adult/60_decision_tree_confusion_matrix_adjusted_thresholds_preprocessed.png) | 51 |
| 61 | [`61_decision_tree_roc_curves_adjusted_thresholds_preprocessed.png`](01c_imbalanced_is_adult/61_decision_tree_roc_curves_adjusted_thresholds_preprocessed.png) | 51 |

## `01d_imbalanced_title_type.ipynb`

| # | Figure | Source cell |
|---:|---|---:|
| 1 | [`01_distribution_of_groupedtitletype.png`](01d_imbalanced_title_type/01_distribution_of_groupedtitletype.png) | 7 |
| 2 | [`02_decision_tree_confusion_matrix.png`](01d_imbalanced_title_type/02_decision_tree_confusion_matrix.png) | 11 |
| 3 | [`03_decision_tree_roc_curves.png`](01d_imbalanced_title_type/03_decision_tree_roc_curves.png) | 11 |
| 4 | [`04_class_distribution_after_rus.png`](01d_imbalanced_title_type/04_class_distribution_after_rus.png) | 20 |
| 5 | [`05_decision_tree_confusion_matrix_rus.png`](01d_imbalanced_title_type/05_decision_tree_confusion_matrix_rus.png) | 20 |
| 6 | [`06_decision_tree_roc_curves_rus.png`](01d_imbalanced_title_type/06_decision_tree_roc_curves_rus.png) | 20 |
| 7 | [`07_class_distribution_after_tomek_links.png`](01d_imbalanced_title_type/07_class_distribution_after_tomek_links.png) | 22 |
| 8 | [`08_decision_tree_confusion_matrix_tomek_links.png`](01d_imbalanced_title_type/08_decision_tree_confusion_matrix_tomek_links.png) | 22 |
| 9 | [`09_decision_tree_roc_curves_tomek_links.png`](01d_imbalanced_title_type/09_decision_tree_roc_curves_tomek_links.png) | 22 |
| 10 | [`10_class_distribution_after_enn.png`](01d_imbalanced_title_type/10_class_distribution_after_enn.png) | 24 |
| 11 | [`11_decision_tree_confusion_matrix_enn.png`](01d_imbalanced_title_type/11_decision_tree_confusion_matrix_enn.png) | 24 |
| 12 | [`12_decision_tree_roc_curves_enn.png`](01d_imbalanced_title_type/12_decision_tree_roc_curves_enn.png) | 24 |
| 13 | [`13_class_distribution_after_cluster_centroids.png`](01d_imbalanced_title_type/13_class_distribution_after_cluster_centroids.png) | 28 |
| 14 | [`14_decision_tree_confusion_matrix_cluster_centroids.png`](01d_imbalanced_title_type/14_decision_tree_confusion_matrix_cluster_centroids.png) | 28 |
| 15 | [`15_decision_tree_roc_curves_cluster_centroids.png`](01d_imbalanced_title_type/15_decision_tree_roc_curves_cluster_centroids.png) | 28 |
| 16 | [`16_class_distribution_after_random_oversampling.png`](01d_imbalanced_title_type/16_class_distribution_after_random_oversampling.png) | 31 |
| 17 | [`17_decision_tree_confusion_matrix_random_oversampling.png`](01d_imbalanced_title_type/17_decision_tree_confusion_matrix_random_oversampling.png) | 31 |
| 18 | [`18_decision_tree_roc_curves_random_oversampling.png`](01d_imbalanced_title_type/18_decision_tree_roc_curves_random_oversampling.png) | 31 |
| 19 | [`19_class_distribution_after_smote.png`](01d_imbalanced_title_type/19_class_distribution_after_smote.png) | 33 |
| 20 | [`20_decision_tree_confusion_matrix_smote.png`](01d_imbalanced_title_type/20_decision_tree_confusion_matrix_smote.png) | 33 |
| 21 | [`21_decision_tree_roc_curves_smote.png`](01d_imbalanced_title_type/21_decision_tree_roc_curves_smote.png) | 33 |
| 22 | [`22_class_distribution_after_adasyn.png`](01d_imbalanced_title_type/22_class_distribution_after_adasyn.png) | 35 |
| 23 | [`23_decision_tree_confusion_matrix_adasyn.png`](01d_imbalanced_title_type/23_decision_tree_confusion_matrix_adasyn.png) | 35 |
| 24 | [`24_decision_tree_roc_curves_adasyn.png`](01d_imbalanced_title_type/24_decision_tree_roc_curves_adasyn.png) | 35 |
| 25 | [`25_original_class_distribution.png`](01d_imbalanced_title_type/25_original_class_distribution.png) | 40 |
| 26 | [`26_decision_tree_confusion_matrix_class_weights_balanced.png`](01d_imbalanced_title_type/26_decision_tree_confusion_matrix_class_weights_balanced.png) | 40 |
| 27 | [`27_decision_tree_roc_curves_class_weights_balanced.png`](01d_imbalanced_title_type/27_decision_tree_roc_curves_class_weights_balanced.png) | 40 |
| 28 | [`28_decision_tree_confusion_matrix_manual_class_weights.png`](01d_imbalanced_title_type/28_decision_tree_confusion_matrix_manual_class_weights.png) | 42 |
| 29 | [`29_decision_tree_roc_curves_manual_class_weights.png`](01d_imbalanced_title_type/29_decision_tree_roc_curves_manual_class_weights.png) | 42 |

## `02_advanced_classification.ipynb`

| # | Figure | Source cell |
|---:|---|---:|
| 1 | [`01_logistic_regression_confusion_matrix.png`](02_advanced_classification/01_logistic_regression_confusion_matrix.png) | 9 |
| 2 | [`02_logistic_regression_roc_curves.png`](02_advanced_classification/02_logistic_regression_roc_curves.png) | 9 |
| 3 | [`03_linearsvc_confusion_matrix.png`](02_advanced_classification/03_linearsvc_confusion_matrix.png) | 12 |
| 4 | [`04_linearsvc_roc_curves.png`](02_advanced_classification/04_linearsvc_roc_curves.png) | 12 |
| 5 | [`05_neural_network_confusion_matrix.png`](02_advanced_classification/05_neural_network_confusion_matrix.png) | 16 |
| 6 | [`06_neural_network_roc_curves.png`](02_advanced_classification/06_neural_network_roc_curves.png) | 16 |
| 7 | [`07_randomforest_confusion_matrix.png`](02_advanced_classification/07_randomforest_confusion_matrix.png) | 19 |
| 8 | [`08_random_forest_roc_curves.png`](02_advanced_classification/08_random_forest_roc_curves.png) | 19 |
| 9 | [`09_random_forest_last_tree_depth_2.png`](02_advanced_classification/09_random_forest_last_tree_depth_2.png) | 20 |
| 10 | [`10_bagging_classifier_confusion_matrix.png`](02_advanced_classification/10_bagging_classifier_confusion_matrix.png) | 22 |
| 11 | [`11_bagging_classifier_roc_curves.png`](02_advanced_classification/11_bagging_classifier_roc_curves.png) | 22 |
| 12 | [`12_adaboost_confusion_matrix.png`](02_advanced_classification/12_adaboost_confusion_matrix.png) | 24 |
| 13 | [`13_adaboost_roc_curves.png`](02_advanced_classification/13_adaboost_roc_curves.png) | 24 |
| 14 | [`14_gradient_boosting_confusion_matrix.png`](02_advanced_classification/14_gradient_boosting_confusion_matrix.png) | 27 |
| 15 | [`15_gradient_boosting_roc_curves.png`](02_advanced_classification/15_gradient_boosting_roc_curves.png) | 27 |
| 16 | [`16_histgradientboosting_confusion_matrix.png`](02_advanced_classification/16_histgradientboosting_confusion_matrix.png) | 29 |
| 17 | [`17_histgradientboosting_roc_curves.png`](02_advanced_classification/17_histgradientboosting_roc_curves.png) | 29 |
| 18 | [`18_xgboost_confusion_matrix.png`](02_advanced_classification/18_xgboost_confusion_matrix.png) | 31 |
| 19 | [`19_xgboost_roc_curves.png`](02_advanced_classification/19_xgboost_roc_curves.png) | 31 |
| 20 | [`20_lightgbm_confusion_matrix.png`](02_advanced_classification/20_lightgbm_confusion_matrix.png) | 33 |
| 21 | [`21_lightgbm_roc_curves.png`](02_advanced_classification/21_lightgbm_roc_curves.png) | 33 |
| 22 | [`22_catboost_confusion_matrix.png`](02_advanced_classification/22_catboost_confusion_matrix.png) | 35 |
| 23 | [`23_catboost_roc_curves.png`](02_advanced_classification/23_catboost_roc_curves.png) | 35 |

## `03_explainable_ai.ipynb`

| # | Figure | Source cell |
|---:|---|---:|
| 1 | [`01_randomforest_confusion_matrix.png`](03_explainable_ai/01_randomforest_confusion_matrix.png) | 10 |
| 2 | [`02_neural_network_confusion_matrix.png`](03_explainable_ai/02_neural_network_confusion_matrix.png) | 11 |
| 3 | [`03_bagging_classifier_confusion_matrix.png`](03_explainable_ai/03_bagging_classifier_confusion_matrix.png) | 12 |
| 4 | [`04_adaboost_confusion_matrix.png`](03_explainable_ai/04_adaboost_confusion_matrix.png) | 13 |
| 5 | [`05_mlpclassifier_global_shap_kernel_stratified.png`](03_explainable_ai/05_mlpclassifier_global_shap_kernel_stratified.png) | 19 |
| 6 | [`06_top_10_features_by_random_forest.png`](03_explainable_ai/06_top_10_features_by_random_forest.png) | 20 |

## `04_time_series_classification.ipynb`

| # | Figure | Source cell |
|---:|---|---:|
| 1 | [`01_rating_category.png`](04_time_series_classification/01_rating_category.png) | 11 |
| 2 | [`02_knn_flattened_confusion_matrix.png`](04_time_series_classification/02_knn_flattened_confusion_matrix.png) | 18 |
| 3 | [`03_knn_flattened_roc_curves.png`](04_time_series_classification/03_knn_flattened_roc_curves.png) | 18 |
| 4 | [`04_dtw_knn_confusion_matrix.png`](04_time_series_classification/04_dtw_knn_confusion_matrix.png) | 20 |
| 5 | [`05_dtw_knn_k_w_best_knn_dtw_distance_params.png`](04_time_series_classification/05_dtw_knn_k_w_best_knn_dtw_distance_params.png) | 20 |
| 6 | [`06_decision_tree_confusion_matrix.png`](04_time_series_classification/06_decision_tree_confusion_matrix.png) | 25 |
| 7 | [`07_decision_tree_roc_curves.png`](04_time_series_classification/07_decision_tree_roc_curves.png) | 25 |
| 8 | [`08_decision_tree_confusion_matrix_catch22.png`](04_time_series_classification/08_decision_tree_confusion_matrix_catch22.png) | 26 |
| 9 | [`09_decision_tree_roc_curves_catch22.png`](04_time_series_classification/09_decision_tree_roc_curves_catch22.png) | 26 |
| 10 | [`10_randomforest_confusion_matrix_raw_series.png`](04_time_series_classification/10_randomforest_confusion_matrix_raw_series.png) | 29 |
| 11 | [`11_randomforest_roc_curves_raw_series.png`](04_time_series_classification/11_randomforest_roc_curves_raw_series.png) | 29 |
| 12 | [`12_catch22_plus_rf_confusion_matrix.png`](04_time_series_classification/12_catch22_plus_rf_confusion_matrix.png) | 30 |
| 13 | [`13_catch22_plus_rf_roc_curves.png`](04_time_series_classification/13_catch22_plus_rf_roc_curves.png) | 30 |
| 14 | [`14_adaboost_dt_base_confusion_matrix.png`](04_time_series_classification/14_adaboost_dt_base_confusion_matrix.png) | 32 |
| 15 | [`15_adaboost_dt_base_roc_curves.png`](04_time_series_classification/15_adaboost_dt_base_roc_curves.png) | 32 |
| 16 | [`16_histgradientboostingclassifier_confusion_matrix.png`](04_time_series_classification/16_histgradientboostingclassifier_confusion_matrix.png) | 35 |
| 17 | [`17_histgradientboostingclassifier_roc_curves.png`](04_time_series_classification/17_histgradientboostingclassifier_roc_curves.png) | 35 |
| 18 | [`18_proximitytree_confusion_matrix.png`](04_time_series_classification/18_proximitytree_confusion_matrix.png) | 38 |
| 19 | [`19_proximitytree_roc_curves.png`](04_time_series_classification/19_proximitytree_roc_curves.png) | 38 |
| 20 | [`20_canonicalintervalforest_confusion_matrix.png`](04_time_series_classification/20_canonicalintervalforest_confusion_matrix.png) | 41 |
| 21 | [`21_cif_roc_curves.png`](04_time_series_classification/21_cif_roc_curves.png) | 41 |
| 22 | [`22_timeseriesforestclassifier_confusion_matrix.png`](04_time_series_classification/22_timeseriesforestclassifier_confusion_matrix.png) | 45 |
| 23 | [`23_timeseriesforestclassifier_roc_curves.png`](04_time_series_classification/23_timeseriesforestclassifier_roc_curves.png) | 45 |
| 24 | [`24_shapelettransformclassifier_confusion_matrix.png`](04_time_series_classification/24_shapelettransformclassifier_confusion_matrix.png) | 48 |
| 25 | [`25_shapelettransformclassifier_roc_curves.png`](04_time_series_classification/25_shapelettransformclassifier_roc_curves.png) | 48 |
| 26 | [`26_randomshapelettransform_plus_knn_confusion_matrix.png`](04_time_series_classification/26_randomshapelettransform_plus_knn_confusion_matrix.png) | 50 |
| 27 | [`27_randomshapelettransform_plus_knn_roc_curves.png`](04_time_series_classification/27_randomshapelettransform_plus_knn_roc_curves.png) | 50 |
| 28 | [`28_shapelet_length_distribution.png`](04_time_series_classification/28_shapelet_length_distribution.png) | 52 |
| 29 | [`29_shapelet_information_gain_distribution.png`](04_time_series_classification/29_shapelet_information_gain_distribution.png) | 52 |
| 30 | [`30_shapelet_1.png`](04_time_series_classification/30_shapelet_1.png) | 52 |
| 31 | [`31_shapelet_2.png`](04_time_series_classification/31_shapelet_2.png) | 52 |
| 32 | [`32_shapelet_3.png`](04_time_series_classification/32_shapelet_3.png) | 52 |
| 33 | [`33_shapelet_4.png`](04_time_series_classification/33_shapelet_4.png) | 52 |
| 34 | [`34_shapelet_5.png`](04_time_series_classification/34_shapelet_5.png) | 52 |
| 35 | [`35_shapeletlearningclassifierpyts_confusion_matrix.png`](04_time_series_classification/35_shapeletlearningclassifierpyts_confusion_matrix.png) | 54 |
| 36 | [`36_shapeletlearningclassifierpyts_roc_curves.png`](04_time_series_classification/36_shapeletlearningclassifierpyts_roc_curves.png) | 54 |
| 37 | [`37_rdstclassifier_confusion_matrix.png`](04_time_series_classification/37_rdstclassifier_confusion_matrix.png) | 57 |
| 38 | [`38_rdstclassifier_roc_curves.png`](04_time_series_classification/38_rdstclassifier_roc_curves.png) | 57 |
| 39 | [`39_individualboss_confusion_matrix.png`](04_time_series_classification/39_individualboss_confusion_matrix.png) | 60 |
| 40 | [`40_individualboss_roc_curves.png`](04_time_series_classification/40_individualboss_roc_curves.png) | 60 |
| 41 | [`41_bossensemble_confusion_matrix.png`](04_time_series_classification/41_bossensemble_confusion_matrix.png) | 62 |
| 42 | [`42_bossensemble_roc_curves.png`](04_time_series_classification/42_bossensemble_roc_curves.png) | 62 |
| 43 | [`43_sfafast_plus_1_nn_confusion_matrix.png`](04_time_series_classification/43_sfafast_plus_1_nn_confusion_matrix.png) | 64 |
| 44 | [`44_sfafast_plus_1_nn_roc_curves.png`](04_time_series_classification/44_sfafast_plus_1_nn_roc_curves.png) | 64 |
| 45 | [`45_mrseql_confusion_matrix.png`](04_time_series_classification/45_mrseql_confusion_matrix.png) | 66 |
| 46 | [`46_mrseql_roc_curves.png`](04_time_series_classification/46_mrseql_roc_curves.png) | 66 |
| 47 | [`47_weasel_confusion_matrix.png`](04_time_series_classification/47_weasel_confusion_matrix.png) | 68 |
| 48 | [`48_muse_confusion_matrix.png`](04_time_series_classification/48_muse_confusion_matrix.png) | 70 |
| 49 | [`49_weasel_v2classifier_confusion_matrix.png`](04_time_series_classification/49_weasel_v2classifier_confusion_matrix.png) | 72 |
| 50 | [`50_weasel_v2classifier_roc_curves.png`](04_time_series_classification/50_weasel_v2classifier_roc_curves.png) | 72 |
| 51 | [`51_mlpclassifier_confusion_matrix.png`](04_time_series_classification/51_mlpclassifier_confusion_matrix.png) | 75 |
| 52 | [`52_mlpclassifier_roc_curves.png`](04_time_series_classification/52_mlpclassifier_roc_curves.png) | 75 |
| 53 | [`53_cnnclassifier_confusion_matrix.png`](04_time_series_classification/53_cnnclassifier_confusion_matrix.png) | 77 |
| 54 | [`54_cnnclassifier_roc_curves.png`](04_time_series_classification/54_cnnclassifier_roc_curves.png) | 77 |
| 55 | [`55_simplernnclassifier_confusion_matrix.png`](04_time_series_classification/55_simplernnclassifier_confusion_matrix.png) | 79 |
| 56 | [`56_simplernnclassifier_roc_curves.png`](04_time_series_classification/56_simplernnclassifier_roc_curves.png) | 79 |
| 57 | [`57_resnetclassifier_confusion_matrix.png`](04_time_series_classification/57_resnetclassifier_confusion_matrix.png) | 83 |
| 58 | [`58_resnetclassifier_roc_curves.png`](04_time_series_classification/58_resnetclassifier_roc_curves.png) | 83 |
| 59 | [`59_inceptiontimeclassifier_confusion_matrix.png`](04_time_series_classification/59_inceptiontimeclassifier_confusion_matrix.png) | 85 |
| 60 | [`60_inceptiontimeclassifier_roc_curves.png`](04_time_series_classification/60_inceptiontimeclassifier_roc_curves.png) | 85 |
| 61 | [`61_lstmfcnclassifier_confusion_matrix.png`](04_time_series_classification/61_lstmfcnclassifier_confusion_matrix.png) | 87 |
| 62 | [`62_lstmfcnclassifier_roc_curves.png`](04_time_series_classification/62_lstmfcnclassifier_roc_curves.png) | 87 |
| 63 | [`63_tapnetclassifier_confusion_matrix.png`](04_time_series_classification/63_tapnetclassifier_confusion_matrix.png) | 89 |
| 64 | [`64_tapnetclassifier_roc_curves.png`](04_time_series_classification/64_tapnetclassifier_roc_curves.png) | 89 |
| 65 | [`65_rocketclassifier_confusion_matrix.png`](04_time_series_classification/65_rocketclassifier_confusion_matrix.png) | 92 |
| 66 | [`66_rocketclassifier_roc_curves.png`](04_time_series_classification/66_rocketclassifier_roc_curves.png) | 92 |
| 67 | [`67_rocket_plus_knn_confusion_matrix.png`](04_time_series_classification/67_rocket_plus_knn_confusion_matrix.png) | 94 |
| 68 | [`68_rocket_plus_knn_roc_curves.png`](04_time_series_classification/68_rocket_plus_knn_roc_curves.png) | 94 |

## `05_sequential_pattern_mining.ipynb`

| # | Figure | Source cell |
|---:|---|---:|
| 1 | [`01_motif_1_start_day_histogram.png`](05_sequential_pattern_mining/01_motif_1_start_day_histogram.png) | 9 |
| 2 | [`02_motif_2_start_day_histogram.png`](05_sequential_pattern_mining/02_motif_2_start_day_histogram.png) | 9 |
| 3 | [`03_motif_3_start_day_histogram.png`](05_sequential_pattern_mining/03_motif_3_start_day_histogram.png) | 9 |
| 4 | [`04_motif_4_start_day_histogram.png`](05_sequential_pattern_mining/04_motif_4_start_day_histogram.png) | 9 |
| 5 | [`05_motif_5_start_day_histogram.png`](05_sequential_pattern_mining/05_motif_5_start_day_histogram.png) | 9 |
