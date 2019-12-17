# Credit_Card_Fraud_Detection_Unsupervised_Capstone_Project

## Objective:
* Credit Fraud Detection
## Methods:
* Dimension reduction: PCA, TSNE, and UMAP
* Algrithms: KMean, Hierarchical Cluster, and Gaussian Mixture Models
* Prediction measurement: Rand Index Score and Adjusted Rand Index
## Summary
* The imbalance dataset converted into a balance dataset using .sample()
* Outlier data points have beed removed by applying winsorization with a threshold 0.05
* Three dimension reduction methods have been explored and data vasulized in 2D plot. Umap showed the most clearly separated clusters. TSNE also resolved two clusters, but it is hard to detect when there is no labels. PCA did not resolve very well in this case.
* From the cumulative explained_variance_ratio plot, it is seen that with about 15 premary components which could represent 90% of the total variance.
* Ingeneral, TSNE is more suitable for this project since all the algrithms showed higher accuracy and confidence. Umap also showed very good accuracy, but the prediction tend to be more random.
* Three algrithms were tested and there is no clear advantages interms of accuracy and confidence level between different algrithms. However, using Hierachical with applying TSNE produce the highest accuracy 0.904 and confidence 0.654.
