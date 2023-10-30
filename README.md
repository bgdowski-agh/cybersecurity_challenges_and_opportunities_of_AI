# cybersecurity_challenges_and_opportunities_of_AI
Figures and results of tests covered in "Cybersecurity Challenges and Opportunities of Artificial Intelligence" article

## Table of contents:
+ [Fig. 1: The division of AI into subcategories.](#fig-1-the-division-of-ai-into-subcategories)
+ [Fig. 2: Balancing the data representing specific categories in subsequent experiments examining the effect of class proportion on classification efficiency.](#fig-2-balancing-the-data-representing-specific-categories-in-subsequent-experiments-examining-the-effect-of-class-proportion-on-classification-efficiency)
  - [Fig. 2a): Phase 1, test 1.](#fig-2a-phase-1-test-1)
  - [Fig. 2b): Phase 1, test 2.](#fig-2b-phase-1-test-2)
  - [Fig. 2c): Phase 1, test 3.](#fig-2c-phase-1-test-3)
  - [Fig. 2d): Phase 1, test 4.](#fig-2d-phase-1-test-4)
  - [Fig. 2e): Phase 2, test 1.](#fig-2e-phase-2-test-1)
  - [Fig. 2f): Phase 2, test 2.](#fig-2f-phase-2-test-2)
  - [Fig. 2g): Phase 2, test 3.](#fig-2g-phase-2-test-3)
  - [Fig. 2h): Phase 2, test 4.](#fig-2h-phase-2-test-4)
+ [Appendix - Table 1: Balancing the data representing specific categories in subsequent experiments. Phase 1. Tests 1-4.](#appendix---table-1-balancing-the-data-representing-specific-categories-in-subsequent-experiments-phase-1-tests-1-4)
+ [Appendix - Table 2: Balancing the data representing specific categories in subsequent experiments. Phase 2. Tests 1-4.](#appendix---table-2-balancing-the-data-representing-specific-categories-in-subsequent-experiments-phase-2-tests-1-4)
+ [Fig. 3: GNB – confusion matrices for experiments examining the effect of class balance on classification efficiency.](#fig-3-gnb--confusion-matrices-for-experiments-examining-the-effect-of-class-balance-on-classification-efficiency)
  - [Fig. 3a): Phase 1, test 1.](#fig-3a-phase-1-test-1)
  - [Fig. 3b): Phase 1, test 2.](#fig-3b-phase-1-test-2)
  - [Fig. 3c): Phase 1, test 3.](#fig-3c-phase-1-test-3)
  - [Fig. 3d): Phase 1, test 4.](#fig-3d-phase-1-test-4)
  - [Fig. 3e): Phase 2, test 1.](#fig-3e-phase-2-test-1)
  - [Fig. 3f): Phase 2, test 2.](#fig-3f-phase-2-test-2)
  - [Fig. 3g): Phase 2, test 3.](#fig-3g-phase-2-test-3)
  - [Fig. 3h): Phase 2, test 4.](#fig-3h-phase-2-test-4)
+ [Fig. 4: DT – confusion matrices for experiments examining the effect of class balance on classification efficiency.](#fig-4-dt--confusion-matrices-for-experiments-examining-the-effect-of-class-balance-on-classification-efficiency)
  - [Fig. 4a): Phase 1, test 1.](#fig-4a-phase-1-test-1)
  - [Fig. 4b): Phase 1, test 2.](#fig-4b-phase-1-test-2)
  - [Fig. 4c): Phase 1, test 3.](#fig-4c-phase-1-test-3)
  - [Fig. 4d): Phase 1, test 4.](#fig-4d-phase-1-test-4)
  - [Fig. 4e): Phase 2, test 1.](#fig-4e-phase-2-test-1)
  - [Fig. 4f): Phase 2, test 2.](#fig-4f-phase-2-test-2)
  - [Fig. 4g): Phase 2, test 3.](#fig-4g-phase-2-test-3)
  - [Fig. 4h): Phase 2, test 4.](#fig-4h-phase-2-test-4)
+ [Fig. 5: RF – confusion matrices for experiments examining the effect of class balance on classification efficiency.](#fig-5-rf--confusion-matrices-for-experiments-examining-the-effect-of-class-balance-on-classification-efficiency)
  - [Fig. 5a): Phase 1, test 1.](#fig-5a-phase-1-test-1)
  - [Fig. 5b): Phase 1, test 2.](#fig-5b-phase-1-test-2)
  - [Fig. 5c): Phase 1, test 3.](#fig-5c-phase-1-test-3)
  - [Fig. 5d): Phase 1, test 4.](#fig-5d-phase-1-test-4)
  - [Fig. 5e): Phase 2, test 1.](#fig-5e-phase-2-test-1)
  - [Fig. 5f): Phase 2, test 2.](#fig-5f-phase-2-test-2)
  - [Fig. 5g): Phase 2, test 3.](#fig-5g-phase-2-test-3)
  - [Fig. 5h): Phase 2, test 4.](#fig-5h-phase-2-test-4)
+ [Fig. 6: SVM – confusion matrices for experiments examining the effect of class balance on classification efficiency.](#fig-6-svm--confusion-matrices-for-experiments-examining-the-effect-of-class-balance-on-classification-efficiency)
  - [Fig. 6a): Phase 1, test 1.](#fig-6a-phase-1-test-1)
  - [Fig. 6b): Phase 1, test 2.](#fig-6b-phase-1-test-2)
  - [Fig. 6c): Phase 1, test 3.](#fig-6c-phase-1-test-3)
  - [Fig. 6d): Phase 1, test 4.](#fig-6d-phase-1-test-4)
  - [Fig. 6e): Phase 2, test 1.](#fig-6e-phase-2-test-1)
  - [Fig. 6f): Phase 2, test 2.](#fig-6f-phase-2-test-2)
  - [Fig. 6g): Phase 2, test 3.](#fig-6g-phase-2-test-3)
  - [Fig. 6h): Phase 2, test 4.](#fig-6h-phase-2-test-4)
+ [Fig. 7: LogR – confusion matrices for experiments examining the effect of class balance on classification efficiency.](#fig-7-logr--confusion-matrices-for-experiments-examining-the-effect-of-class-balance-on-classification-efficiency)
  - [Fig. 7a): Phase 1, test 1.](#fig-7a-phase-1-test-1)
  - [Fig. 7b): Phase 1, test 2.](#fig-7b-phase-1-test-2)
  - [Fig. 7c): Phase 1, test 3.](#fig-7c-phase-1-test-3)
  - [Fig. 7d): Phase 1, test 4.](#fig-7d-phase-1-test-4)
  - [Fig. 7e): Phase 2, test 1.](#fig-7e-phase-2-test-1)
  - [Fig. 7f): Phase 2, test 2.](#fig-7f-phase-2-test-2)
  - [Fig. 7g): Phase 2, test 3.](#fig-7g-phase-2-test-3)
  - [Fig. 7h): Phase 2, test 4.](#fig-7h-phase-2-test-4)
+ [Fig. 8: GBC – confusion matrices for experiments examining the effect of class balance on classification efficiency.](#fig-8-gbc--confusion-matrices-for-experiments-examining-the-effect-of-class-balance-on-classification-efficiency)
  - [Fig. 8a): Phase 1, test 1.](#fig-8a-phase-1-test-1)
  - [Fig. 8b): Phase 1, test 2.](#fig-8b-phase-1-test-2)
  - [Fig. 8c): Phase 1, test 3.](#fig-8c-phase-1-test-3)
  - [Fig. 8d): Phase 1, test 4.](#fig-8d-phase-1-test-4)
  - [Fig. 8e): Phase 2, test 1.](#fig-8e-phase-2-test-1)
  - [Fig. 8f): Phase 2, test 2.](#fig-8f-phase-2-test-2)
  - [Fig. 8g): Phase 2, test 3.](#fig-8g-phase-2-test-3)
  - [Fig. 8h): Phase 2, test 4.](#fig-8h-phase-2-test-4)
+ [Fig. 9: ANN – confusion matrices for experiments examining the effect of class balance on classification efficiency.](#fig-9-ann--confusion-matrices-for-experiments-examining-the-effect-of-class-balance-on-classification-efficiency)
  - [Fig. 9a): Phase 1, test 1.](#fig-9a-phase-1-test-1)
  - [Fig. 9b): Phase 1, test 2.](#fig-9b-phase-1-test-2)
  - [Fig. 9c): Phase 1, test 3.](#fig-9c-phase-1-test-3)
  - [Fig. 9d): Phase 1, test 4.](#fig-9d-phase-1-test-4)
  - [Fig. 9e): Phase 2, test 1.](#fig-9e-phase-2-test-1)
  - [Fig. 9f): Phase 2, test 2.](#fig-9f-phase-2-test-2)
  - [Fig. 9g): Phase 2, test 3.](#fig-9g-phase-2-test-3)
  - [Fig. 9h): Phase 2, test 4.](#fig-9h-phase-2-test-4)
+ [Fig. 10: Accuracy graph for experiments examining the effect of class balance on classification efficiency.](#fig-10-accuracy-graph-for-experiments-examining-the-effect-of-class-balance-on-classification-efficiency)
  - [Fig. 10a): Phase 1.](#fig-10a-phase-1)
  - [Fig. 10b): Phase 2.](#fig-10b-phase-2)
+ [Fig. 11: Precision graph for experiments examining the effect of class balance on classification efficiency.](#fig-11-precision-graph-for-experiments-examining-the-effect-of-class-balance-on-classification-efficiency)
  - [Fig. 11a): Phase 1.](#fig-11a-phase-1)
  - [Fig. 11b): Phase 2.](#fig-11b-phase-2)
+ [Fig. 12: Recall graph for experiments examining the effect of class balance on classification efficiency.](#fig-12-recall-graph-for-experiments-examining-the-effect-of-class-balance-on-classification-efficiency)
  - [Fig. 12a): Phase 1.](#fig-12a-phase-1)
  - [Fig. 12b): Phase 2.](#fig-12b-phase-2)
+ [Fig. 13: F1score graph for experiments examining the effect of class balance on classification efficiency.](#fig-13-f1score-graph-for-experiments-examining-the-effect-of-class-balance-on-classification-efficiency)
  - [Fig. 13a): Phase 1.](#fig-13a-phase-1)
  - [Fig. 13b): Phase 2.](#fig-13b-phase-2)
+ [Appendix - Table 3: Removing samples from training datasets to balance classes. Tests 1-7.](#appendix---table-3-removing-samples-from-training-datasets-to-balance-classes-tests-1-7)
+ [Appendix - Fig A1: Removing samples from training datasets to balance classes. Test 1: 10\% of KDD'99.](#appendix---fig-a1-removing-samples-from-training-datasets-to-balance-classes-test-1-10-of-kdd99)
+ [Appendix - Fig A2: Removing samples from training datasets to balance classes. Tests 2-7.](#appendix---fig-a2-removing-samples-from-training-datasets-to-balance-classes-tests-2-7)
  - [Fig. A2a): Test 2: reduction of all \textit{DoS} attack by a factor of 2.](#fig-a2a-test-2-reduction-of-all-textitdos-attack-by-a-factor-of-2)
  - [Fig. A2b): Test 3: reduction of all \textit{DoS} attack by a factor of 4.](#fig-a2b-test-3-reduction-of-all-textitdos-attack-by-a-factor-of-4)
  - [Fig. A2c): Test 4: reduction of all \textit{DoS} attack by a factor of 8.](#fig-a2c-test-4-reduction-of-all-textitdos-attack-by-a-factor-of-8)
  - [Fig. A2d): Test 5: reduction of all \textit{DoS} attack by a factor of 20 and \textit{normal} by a factor of 10.](#fig-a2d-test-5-reduction-of-all-textitdos-attack-by-a-factor-of-20-and-textitnormal-by-a-factor-of-10)
  - [Fig. A2e): Test 6: reduction of all \textit{DoS} attack by a factor of 40 and \textit{normal} by a factor of 10.](#fig-a2e-test-6-reduction-of-all-textitdos-attack-by-a-factor-of-40-and-textitnormal-by-a-factor-of-10)
  - [Fig. A2f): Test 7: reduction of all \textit{DoS} attack by a factor of 80 and \textit{normal} by a factor of 10.](#fig-a2f-test-7-reduction-of-all-textitdos-attack-by-a-factor-of-80-and-textitnormal-by-a-factor-of-10)
+ [Fig. 14: Accuracy for datasets of various sizes.](#fig-14-accuracy-for-datasets-of-various-sizes)
+ [Fig. 15: Standard correlation coefficient for KDD Cup'99 dataset features.](#fig-15-standard-correlation-coefficient-for-kdd-cup99-dataset-features)
+ [Appendix - Table 4: Different thresholds of acceptable correlation coefficients. Tests 1-4.](#appendix---table-4-different-thresholds-of-acceptable-correlation-coefficients-tests-1-4)
+ [Appendix - Fig A3: Different thresholds of acceptable correlation coefficients. Tests 1-4.](#appendix---fig-a3-different-thresholds-of-acceptable-correlation-coefficients-tests-1-4)
  - [Fig. A3a): Test 1: The Threshold of correlation coefficients set to 98\%.](#fig-a3a-test-1-the-threshold-of-correlation-coefficients-set-to-98)
  - [Fig. A3b): Test 2: The Threshold of correlation coefficients set to 100\%.](#fig-a3b-test-2-the-threshold-of-correlation-coefficients-set-to-100)
  - [Fig. A3c): Test 3: The Threshold of correlation coefficients set to 90\%.](#fig-a3c-test-3-the-threshold-of-correlation-coefficients-set-to-90)
  - [Fig. A3d): Test 4: The Threshold of correlation coefficients set to 80\%.](#fig-a3d-test-4-the-threshold-of-correlation-coefficients-set-to-80)
+ [Fig. 16: Accuracy for the different thresholds of the acceptable correlation coefficients.](#fig-16-accuracy-for-the-different-thresholds-of-the-acceptable-correlation-coefficients)
+ [Appendix - Table 5: Comparison of the classifier’s effectiveness due to used training/testing dataset. Tests: 1-4.](#appendix---table-5-comparison-of-the-classifiers-effectiveness-due-to-used-trainingtesting-dataset-tests-1-4)
+ [Fig. 17: Distribution of data representing the various types of attacks for experiments examining the effect of features correlation on classification efficiency.](#fig-17-distribution-of-data-representing-the-various-types-of-attacks-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
  - [Fig. 17a): NSL-KDD train dataset.](#fig-17a-nsl-kdd-train-dataset)
  - [Fig. 17b): NSL-KDD test dataset.](#fig-17b-nsl-kdd-test-dataset)
  - [Fig. 17c): KDD Cup'99 train/test dataset.](#fig-17c-kdd-cup99-traintest-dataset)
+ [Fig. 18: Accuracy graph for experiments examining the effect of features correlation on classification efficiency.](#fig-18-accuracy-graph-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
+ [Fig. 19: Precision graph for experiments examining the effect of features correlation on classification efficiency.](#fig-19-precision-graph-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
+ [Fig. 20: Recall graph for experiments examining the effect of features correlation on classification efficiency.](#fig-20-recall-graph-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
+ [Fig. 21: F1score graph for experiments examining the effect of features correlation on classification efficiency.](#fig-21-f1score-graph-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
+ [Fig. 22: GNB – confusion matrices for experiments examining the effect of features correlation on classification efficiency.](#fig-22-gnb--confusion-matrices-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
  - [Fig. 22a): Train: NSL, test: NSL.](#fig-22a-train-nsl-test-nsl)
  - [Fig. 22b): Train: NSL, test: KDD.](#fig-22b-train-nsl-test-kdd)
  - [Fig. 22c): Train: KDD, test: NSL.](#fig-22c-train-kdd-test-nsl)
  - [Fig. 22d): Train: KDD, test: KDD.](#fig-22d-train-kdd-test-kdd)
+ [Fig. 23: DT – confusion matrices for experiments examining the effect of features correlation on classification efficiency.](#fig-23-dt--confusion-matrices-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
  - [Fig. 23a): Train: NSL, test: NSL.](#fig-23a-train-nsl-test-nsl)
  - [Fig. 23b): Train: NSL, test: KDD.](#fig-23b-train-nsl-test-kdd)
  - [Fig. 23c): Train: KDD, test: NSL.](#fig-23c-train-kdd-test-nsl)
  - [Fig. 23d): Train: KDD, test: KDD.](#fig-23d-train-kdd-test-kdd)
+ [Fig. 24: RF – confusion matrices for experiments examining the effect of features correlation on classification efficiency.](#fig-24-rf--confusion-matrices-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
  - [Fig. 24a): Train: NSL, test: NSL.](#fig-24a-train-nsl-test-nsl)
  - [Fig. 24b): Train: NSL, test: KDD.](#fig-24b-train-nsl-test-kdd)
  - [Fig. 24c): Train: KDD, test: NSL.](#fig-24c-train-kdd-test-nsl)
  - [Fig. 24d): Train: KDD, test: KDD.](#fig-24d-train-kdd-test-kdd)
+ [Fig. 25: SVM – confusion matrices for experiments examining the effect of features correlation on classification efficiency.](#fig-25-svm--confusion-matrices-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
  - [Fig. 25a): Train: NSL, test: NSL.](#fig-25a-train-nsl-test-nsl)
  - [Fig. 25b): Train: NSL, test: KDD.](#fig-25b-train-nsl-test-kdd)
  - [Fig. 25c): Train: KDD, test: NSL.](#fig-25c-train-kdd-test-nsl)
  - [Fig. 25d): Train: KDD, test: KDD.](#fig-25d-train-kdd-test-kdd)
+ [Fig. 26: LogR – confusion matrices for experiments examining the effect of features correlation on classification efficiency.](#fig-26-logr--confusion-matrices-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
  - [Fig. 26a): Train: NSL, test: NSL.](#fig-26a-train-nsl-test-nsl)
  - [Fig. 26b): Train: NSL, test: KDD.](#fig-26b-train-nsl-test-kdd)
  - [Fig. 26c): Train: KDD, test: NSL.](#fig-26c-train-kdd-test-nsl)
  - [Fig. 26d): Train: KDD, test: KDD.](#fig-26d-train-kdd-test-kdd)
+ [Fig. 27: GBC – confusion matrices for experiments examining the effect of features correlation on classification efficiency.](#fig-27-gbc--confusion-matrices-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
  - [Fig. 27a): Train: NSL, test: NSL.](#fig-27a-train-nsl-test-nsl)
  - [Fig. 27b): Train: NSL, test: KDD.](#fig-27b-train-nsl-test-kdd)
  - [Fig. 27c): Train: KDD, test: NSL.](#fig-27c-train-kdd-test-nsl)
  - [Fig. 27d): Train: KDD, test: KDD.](#fig-27d-train-kdd-test-kdd)
+ [Fig. 28: ANN – confusion matrices for experiments examining the effect of features correlation on classification efficiency.](#fig-28-ann--confusion-matrices-for-experiments-examining-the-effect-of-features-correlation-on-classification-efficiency)
  - [Fig. 28a): Train: NSL, test: NSL.](#fig-28a-train-nsl-test-nsl)
  - [Fig. 28b): Train: NSL, test: KDD.](#fig-28b-train-nsl-test-kdd)
  - [Fig. 28c): Train: KDD, test: NSL.](#fig-28c-train-kdd-test-nsl)
  - [Fig. 28d): Train: KDD, test: KDD.](#fig-28d-train-kdd-test-kdd)
+ [Fig. 29: An example of a model theft attack from the publication: Goodfellow et al. in 1412.6572.](#fig-29-an-example-of-a-model-theft-attack-from-the-publication-goodfellow-et-al-in-14126572)
+ [Fig. 30: An example of an model inversion attack by: Jin et al. in 2110.15122.](#fig-30-an-example-of-an-model-inversion-attack-by-jin-et-al-in-211015122)
