# **Sound Clustering**

## **Overview**

This repository contains visualizations shows the analysis of unlabeled sound data. 
The visualizations are created using various clustering techniques and dimensionality reduction methods to explore and understand the structure of the sound data.
Below is a description of each visualization included in this repository.

## 1. **Feature Extraction Visualization**

**Description**:

   - This visualization represents the extracted features from the sound data. The features are derived using Mel Spectrograms, which capture the frequency content of the sound signals over time.
   - The plot shows the mean Mel Spectrogram values across different frequency bins, providing insights into the spectral characteristics of the sound data.
     
![Image](https://github.com/user-attachments/assets/0f5f422c-a0b1-49c4-970c-def7ed2525cc)

## 2.This visualizationsi s comparing **PCA** and **t-SNE** for dimensionality reduction in 3D space.

- Principal Component Analysis (PCA) is a linear dimensionality reduction technique that projects high-dimensional data into a lower-dimensional space 
while preserving as much variance as possible.

- The PCA visualization shows a more spread-out distribution of points, reflecting its ability to retain global structure

t-Distributed Stochastic Neighbor Embedding (t-SNE) is a non-linear dimensionality reduction method that focuses on preserving local structures. 

- The t-SNE visualization presents clusters that are more compact and highlight relationships between similar data points.

![Image](https://github.com/user-attachments/assets/1f4c2fd7-874d-4bf9-b86b-56a4dbc1323c)

## 3. **Elbow Method Visualization**

**Description**:

   -   This visualization illustrates the Elbow Method used to determine the optimal number of clusters for the K-Means clustering algorithm.
   - The plot shows the inertia (a measure of how internally coherent clusters are) on the y-axis against the number of clusters on the x-axis.
   -  The "elbow" point in the plot indicates the optimal number of clusters, where adding more clusters does not significantly reduce inertia.
   -  This method helps in selecting the most appropriate number of clusters for the sound data.

![Image](https://github.com/user-attachments/assets/9ceaff41-5e80-4929-aec3-0ba7cfa8f5d4)

## 2. **K-Means Clustering Visualization**
**Description**:
   
   -  This visualization represents the results of applying the K-Means clustering algorithm to the sound data.
   -  The plot shows the clusters formed by grouping similar sound features together, with each cluster represented by a different color.
   -   The x-axis and y-axis represent the reduced dimensions of the data, and the plot helps in understanding the distribution and separation of clusters identified by the K-Means algorithm.

![Image](https://github.com/user-attachments/assets/e33dc475-4d0e-4d11-8eb1-25b7fc646abb)


## 4. **Final Clusters (t-SNE Visualization with K-Means Labels)**

**Description**:
   
   - This visualization displays the final clusters obtained from the K-Means clustering algorithm, visualized in a 2D space using t-SNE (t-Distributed Stochastic Neighbor Embedding).
   -  The plot shows the t-SNE components on the x and y axes, with each point colored according to its K-Means cluster label.
   -  This visualization helps in understanding the separation and distribution of clusters in a reduced-dimensional space, providing insights into the effectiveness of the K-Means clustering.

![Image](https://github.com/user-attachments/assets/d7bac545-da56-4ccc-a421-9549498b84b2)
     
