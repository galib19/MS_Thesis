# Significant Features Analysis For Android Malware Detection Using Machine Learning Techniques

## Abstract

Android malware poses a significant threat to the security of the Android operating system, often evading traditional antivirus solutions and outdated detection methods. This research focuses on the analysis of significant features for effective Android malware detection using machine learning techniques. As malware continues to employ various evasion tactics to appear benign, a perceptive approach becomes essential in countering these threats. The challenge lies in detecting Android malware proactively in the rapidly evolving digital landscape.

Conventional malware detection methods, such as static analysis, dynamic analysis, and hybrid analysis, rely on comprehensive feature sets for classification. However, the ever-growing number of features in the Android system complicates the process, leading to potential overfitting of data and misleading classifiers. This study proposes the analysis of significant features as a means to reduce complexity and enhance large-scale malware detection.

The research examines Permissions, API Calls, and ensemble features separately to evaluate their individual impact and overall performance. An innovative approach is introduced, involving incremental feature analysis through various feature selection techniques. This incremental analysis helps identify a well-suited feature selection technique, leading to the identification of a minimal set of significant features. Subsequently, a correlation-based feature elimination strategy further reduces the identified significant features.

Experiments conducted on two benchmark datasets reveal that Recursive Feature Elimination with Random Forest Classifier effectively identifies significant features in all cases. Evaluation results demonstrate that the proposed approach significantly reduces the size of the feature set while maintaining close performance to the full set in terms of accuracy, recall, F1-score, AU-ROC curve, and execution time. The study also identifies top significant features in malware detection, indicating that significant ensemble features outperform significant Permissions and API Calls. Additionally, significant API Calls perform better than significant Permissions.

This research underscores the importance of significant features in classifying Android malware effectively while preserving detection performance. The findings contribute to accelerating large-scale malware detection with a focus on performance considerations.

## List of Publications

1. Galib, A.H., Hossain, B. M. (2020, July). [Significant API Calls in Android Malware Detection (Using Feature Selection Techniques and Correlation Based Feature Elimination)](https://ksiresearch.org/seke/seke20paper/paper143.pdf). In Proceedings of the 32nd International Conference on Software Engineering Knowledge Engineering (pp. 566-571).

2. Galib, A.H., Hossain, B. M. (2019, December). [A Systematic Review on Hybrid Analysis using Machine Learning for Android Malware Detection](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9290548&tag=1). International Conference on Innovation in Engineering and Technology (ICIET) 2019.

3. Galib, A. H., Hossain, B. M. (2020). [A Review on Hybrid Analysis using Machine Learning for Android Malware Detection](https://jase.du.ac.bd/uploads/articles/202051%20&%202/6362a17312e83.pdf). Dhaka University Journal of Applied Science Engineering (DUJASE), Volume 5(1 & 2). Manuscript in press.
