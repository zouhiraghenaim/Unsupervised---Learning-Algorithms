# Unsupervised Learning Algorithms

An educational repository dedicated to implementing fundamental unsupervised machine learning algorithms as part of practical lab works (TPs) using Python and Scikit-Learn.

---

## 📂 Repository Structure

The project is organized into dedicated directories to maintain a clean workspace:

* 📂 **K-Means-Clustering**: Contains files and models related to the practical assignment (TP 08) on K-Means Clustering:
  * `TP8_01_K_mean_Clustring_model.ipynb` — Implementation of a basic K-Means clustering model.
  * `TP8_02_k_mean_multiple.ipynb` — Comprehensive application of K-Means clustering using multiple dataset features.
  * `customer_behavior_kmeans.csv` & `kmean_cluster.csv` — Datasets used for clustering experiments.
  * `k_mean Clustring.pdf` — Theoretical guide and lab instructions.
* 📂 **TP09 Hirarical_Clustering**: Contains files and models related to the practical assignment (TP 09) on Hierarchical Clustering:
  * `TP9_01 Hirarical_Clustering.ipynb` — Implementation of basic Agglomerative Hierarchical Clustering and dendrogram visualization.
  * `TP9_02 Hirarical_Full_Clustering.ipynb` — Comprehensive application of Hierarchical Clustering using multiple features and linkage methods.

---

## Theoretical Overview

### 1. K-Means Clustering
An iterative, centroid-based clustering algorithm used to partition an unlabeled dataset into $K$ distinct, non-overlapping clusters. The algorithm aims to minimize the Within-Cluster Sum of Squares (WCSS / Inertia) by assigning each data point to its nearest cluster centroid and updating the centroids until convergence.

$$J = \sum_{j=1}^{K} \sum_{i=1}^{n} \|x_i^{(j)} - \mu_j\|^2$$

### 2. Hierarchical Clustering
An unsupervised clustering algorithm that builds a hierarchy of clusters without requiring the number of clusters ($K$) to be specified in advance. Using the **Agglomerative (bottom-up)** approach, each data point starts as an individual cluster and pairs of clusters are successively merged based on a distance metric (e.g., Euclidean distance) and a linkage criterion (such as Ward's method), visualized using a **Dendrogram**.

$$d(u, v) = \sqrt{\sum_{i=1}^{n} (u_i - v_i)^2}$$

---

##  Tools & Libraries

* **Language:** Python 3
* **Environment:** Google Colab / Jupyter Notebooks
* **Key Packages:** `scikit-learn` • `pandas` • `numpy` • `matplotlib` • `seaborn`

---

**Author:** **Zouhira Ghenaim**
