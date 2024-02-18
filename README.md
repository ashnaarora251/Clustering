# Clustering-Analysis

## Dataset Used - Wine Quality

## Preprocessing Approaches:
1) Raw Data Usage: Clustering directly employs the unprocessed data.
2) Scaling: Values are adjusted to fit within the range of 0 to 1.
3) Principal Component Analysis (PCA): Reduction of data dimensionality is achieved through PCA.
4) Transformation Followed by Scaling: Initial PCA is utilized for dimensionality reduction, succeeded by scaling.
5) Sequential Transformation, Scaling, and PCA: PCA precedes scaling, and then another PCA step further reduces dimensionality.

## Evaluation Metrics
1) Silhouette Score: Assesses the similarity of an object to its cluster versus other clusters. A high score implies good intra-cluster matching.
2) Calinski-Harabasz Score: Quantifies the ratio of between-cluster dispersion mean to within-cluster dispersion, indicating the clarity of clusters.
3) Davies-Bouldin Score: Measures average cluster similarity to its most akin cluster, with lower scores indicating better clustering.

![alt text](https://github.com/ThatSpaceCowboy/Clustering-Analysis/blob/main/analysis_final_result.png?raw=true)

## Summary:
PCA preprocessing exhibits superior performance across Silhouette, Calinski-Harabasz, and Davies-Bouldin Scores, signifying clearer and more distinct clusters compared to alternative preprocessing methods.
