# SmartCart Customer Clustering

An unsupervised machine-learning project that segments customers based on demographic, purchasing, and engagement behavior.

## Objective

The goal is to discover meaningful customer groups without predefined labels. These segments can be used as a foundation for personalized marketing, customer profiling, and business decision-making.

## Workflow

```text
Customer Data
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
Categorical Encoding
     ↓
Feature Scaling
     ↓
Dimensionality Reduction
     ↓
Clustering
     ↓
Cluster Evaluation
     ↓
Customer Segments
```

## Feature Engineering

The notebook derives features such as:

- Age
- Customer tenure
- Total spending
- Number of children
- Purchase-channel behavior
- Education grouping
- Marital-status grouping

## Algorithms

The project explores:

- K-Means Clustering
- Agglomerative Clustering

It also uses:

- Elbow/Knee analysis for cluster selection
- Silhouette score for evaluating cluster quality
- PCA for dimensionality reduction and visualization

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- `kneed`
- Jupyter Notebook

## Getting Started

```bash
git clone https://github.com/muskanmundra18-lab/smartcart-clustering.git
cd smartcart-clustering
```

Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn kneed
```

Open:

```text
minor_project_2.ipynb
```

## Why Unsupervised Learning?

Customer segmentation does not always have predefined target labels. Clustering can reveal naturally occurring groups in customer behavior and help turn raw customer data into actionable segments.

## Future Improvements

- Add cluster profiles with business-friendly names
- Build an interactive visualization
- Compare clustering stability across random seeds
- Add a recommendation/marketing strategy for each segment
- Deploy the segmentation pipeline as an application

## Author

**Muskan Mundra**
