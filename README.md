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

---

## Theoretical Overview

### 1. K-Means Clustering
An iterative, centroid-based clustering algorithm used to partition an unlabeled dataset into $K$ distinct, non-overlapping clusters. The algorithm aims to minimize the Within-Cluster Sum of Squares (WCSS / Inertia) by assigning each data point to its nearest cluster centroid and updating the centroids until convergence.

$$J = \sum_{j=1}^{K} \sum_{i=1}^{n} \|x_i^{(j)} - \mu_j\|^2$$

---

##  Tools & Libraries

* **Language:** Python 3
* **Environment:** Google Colab / Jupyter Notebooks
* **Key Packages:** `scikit-learn` • `pandas` • `numpy` • `matplotlib` • `seaborn`

---

**Author:** Zouhira Ghenaim
