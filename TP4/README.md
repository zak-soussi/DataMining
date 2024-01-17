<!DOCTYPE html>
<html>
<head>
    <title>Lab Assignment No. 4: Unsupervised Learning - Clustering</title>
</head>

<body>
<h1>Lab Assignment No. 4: Unsupervised Learning - Clustering</h1>
<h2>Objectives:</h2>
    <p>The primary goal of unsupervised learning methods is to group similar elements together, minimizing intra-cluster distance and maximizing inter-cluster distance.<br>
    This lab assignment aims to implement two clustering methods:</p>
    <ul>
        <li>k-Means</li>
        <li>Hierarchical Agglomerative Clustering</li>
    </ul>
<h2>Contents:</h2>
 <h3>I- Dataset:</h3>
    <ol>
        <li><strong>Fromage:</strong>
            <p>A dataset named "fromage.txt" consists of 29 instances of cheese, represented by 9 attributes.</p>
        </li>
        <li><strong>Exploration Tasks:</strong>
            <ul>
                <li>Understanding the dataset's structure.</li>
                <li>Plotting data distribution based on different attribute pairs.</li>
            </ul>
        </li>
    </ol>
    <h3>II- K-Means:</h3>
    <p>In this part, the k-means algorithm will be used with the Scikit-Learn package.<br>
        The number of clusters (k) is predetermined, and the goal is to iteratively improve the partition.</p>
    <h3>III- Hierarchical Agglomerative Clustering (HAC):</h3>
    <p>
        Hierarchical Agglomerative Clustering (HAC) is a bottom-up approach in clustering where each data point starts as a single cluster and iteratively merges with the closest clusters until a single cluster containing all points is formed. It results in a hierarchical tree-like structure, known as a dendrogram, reflecting the relationships between data points.</p>
<h3>IV- Principal Component Analysis (PCA):</h3>
    <p>Principal Component Analysis (PCA) is a statistical method used for dimensionality reduction in multivariate data. It identifies the most influential directions, called principal components, to represent the dataset's variability. By projecting data onto these components, PCA simplifies analysis while preserving key information.</p>
    <h3>V- Diana:</h3>
    <p>
    Divisive Analysis is a divisive hierarchical clustering algorithm that starts with a single cluster containing all data points and iteratively divides clusters into smaller ones based on dissimilarity measures. It recursively separates clusters until each data point forms its own cluster. </p>
</body>

</html>
