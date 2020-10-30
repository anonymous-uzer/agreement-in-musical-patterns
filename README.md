# Repository of Pattern datasets #

This repository contains the analysis of musical patterns gathered with the PAF and the ANOMIC annotation tools, as well as patterns discovered with various SIA-based pattern discovery algorithms. The analysis is split into two sections, the inter-annotator agreement analysis and the feature-based analysis. The inter-agreement analysis is based on the below agreement matrices between annotators of all datasets. 
Meanwhile the feature-based analysis results consist of t-test and KS-test results between the feature distributions of the aforementioned datasets, and boxplot visualisations of these distributions.


# Inter-annotator agrement and algorithm-annotator agreement matrices #
*F1* score matrices, representing pairwise agreement between annotators, with the time threshold set to 5 crotchets. Each matrix showcases results for a different piece of music. Matrix columns and rows denote different annotators, grouped based on the annotation tool used (PAF or ANOMIC) and their musical background. An exception are the last few rows, labeled ALG, where each row represents a separate pattern discovery algorithm. Matrix cell colours correspond to the obtained pairwise agreement values, where yellow denotes high agreement and blue low. Some annotators did not provide annotations for all pieces, which can be seen on the diagonals as low agreement.

![](/comparison_figures/agreement_matrices.png)


# Boxplot visualisations of significant features #
Boxplots showcasing the distributions of the analysed pattern features of the PAF, ANOMIC and algorithmic datasets. For each feature the three distributions were normalised in order to fit on the same plot. Separate plots for each feature can be seen lower on this page.

![](/comparison_figures/significant_feature_boxplots.png)

# T-test tables #
Tables showcasing *t* and *p* values of t-tests with *alpha* of 0.05, between the PAF, the ANOMIC (musicians and non-musicians) and the algorithmic datasets on the features of the first column. Orange cells denote tests with *p* values higher than the predefined threshold *alpha*, which means that the difference between the two tested distributions is not statistically significant.

![](/comparison_tables/t_tests_PAF_ANOMIC_ALG.png){width=80%}

![](/comparison_tables/t_tests_PAF_MUS_NONMUS.png)

# KS-test tables #
Tables showcasing the *D* statistics and *p* values of Kolmogorov-Smirnov tests on the pairs of PAF, ANOMIC (musicians and non-musicians) and algorithmic feature distributions. The tests were performed with a threshold *alpha* of 0.05 and a critical value of 1.36. Yellow cells denote tests whose *D* statistic is lower than the critical value. Orange cells denote tests whose *p* value is higher than the threshold *alpha*, meaning that the difference between distributions cannot be considered as statistically significant.

![](/comparison_tables/ks_tests_PAF_ANOMIC_ALG.png)

![](/comparison_tables/ks_tests_PAF_MUS_NONMUS.png)



# Separate boxplots visualisations for all analysed features #
![](/comparison_figures/boxplot_figures/cardinality.png)

![](/comparison_figures/boxplot_figures/occurrences.png)

![](/comparison_figures/boxplot_figures/coverage.png)

![](/comparison_figures/boxplot_figures/compression_ratio.png)

![](/comparison_figures/boxplot_figures/threeCs.png)

![](/comparison_figures/boxplot_figures/rhythmic_density.png)

![](/comparison_figures/boxplot_figures/pattern_duration.png)

![](/comparison_figures/boxplot_figures/last_note_duration.png)

![](/comparison_figures/boxplot_figures/melodic_arcs.png)

![](/comparison_figures/boxplot_figures/rhythmic_variability.png)

![](/comparison_figures/boxplot_figures/mc_cardinality_occurrences.png)

![](/comparison_figures/boxplot_figures/expected_occurrences.png)

![](/comparison_figures/boxplot_figures/geometric_mean_likelihood.png)

![](/comparison_figures/boxplot_figures/score.png)

![](/comparison_figures/boxplot_figures/interest.png)

![](/comparison_figures/boxplot_figures/prominence.png)

![](/comparison_figures/boxplot_figures/alternative_prominence.png)

![](/comparison_figures/boxplot_figures/note_range.png)

![](/comparison_figures/boxplot_figures/signed_pitch_range.png)

![](/comparison_figures/boxplot_figures/unsigned_pitch_range.png)

![](/comparison_figures/boxplot_figures/max_pitch_centre.png)

![](/comparison_figures/boxplot_figures/chromatic.png)

![](/comparison_figures/boxplot_figures/pitch_direction_changes.png)

![](/comparison_figures/boxplot_figures/small_intervals.png)

![](/comparison_figures/boxplot_figures/intervallic_leaps.png)

![](/comparison_figures/boxplot_figures/mean_melodic_interval.png)

![](/comparison_figures/boxplot_figures/roots.png)

![](/comparison_figures/boxplot_figures/thirds.png)

![](/comparison_figures/boxplot_figures/fifths.png)

![](/comparison_figures/boxplot_figures/mean_steepness.png)

![](/comparison_figures/boxplot_figures/repeated_notes.png)

![](/comparison_figures/boxplot_figures/most_common_note.png)

![](/comparison_figures/boxplot_figures/unique_notes.png)