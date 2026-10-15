# Machine Learning

Before we start, 

Classical Machine Learning generally refers to traditional ML techniques, particularly those that don't rely on deep neural networks.
Deep learning is a family of techniques, whereas supervised, unsupervised, and reinforcement learning describe learning paradigms.

# Classical Machine Learning — Our Roadmap

Before we start, here's the order we'll follow.

| No. | Concept |
| --- | --- |
| 1 | Supervised vs. Unsupervised Learning |
| 2 | Regression vs. Classification |
| 3 | Linear Regression |
| 4 | Logistic Regression |
| 5 | Decision Trees & Random Forests |
| 6 | Clustering — K-Means |
| 7 | Overfitting, Underfitting & Bias-Variance |
| 8 | Model Evaluation Metrics |
| 9 | Feature Engineering & Feature Selection |
| 10 | Support Vector Machines (SVM) |
| 11 | K-Nearest Neighbors (KNN) |
| 12 | Naive Bayes |
| 13 | Ensemble Learning — Bagging & Boosting |
| 14 | Dimensionality Reduction — PCA |
| 15 | Reinforcement Learning Fundamentals |

## Types of machine learning

### 1. Supervised learning

**Definition:** The model learns from labeled data, where the correct answers are provided during training.

| Type | Purpose | Example | Algorithms |
| --- | --- | --- | --- |
| Regression | Predict a numerical value | Predict house prices | Linear Regression, Decision Tree Regression |
| Classification | Predict a category | Detect fraudulent transactions | Logistic Regression, Decision Trees, SVM |

### Important algorithms

- Linear Regression
- Polynomial Regression
- Logistic Regression
- Decision Trees
- Random Forests
- Support Vector Machines (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Gradient Boosting
- XGBoost

### 2. Unsupervised Machine Learning

**Definition:** The model discovers patterns or structures in data without predefined target labels.

| Type | Purpose | Algorithms | Example |
| --- | --- | --- | --- |
| Clustering | Group similar data points | K-Means, DBSCAN, Hierarchical Clustering | Customer segmentation |
| Dimensionality Reduction | Reduce the number of features | PCA, t-SNE, UMAP | Visualizing high-dimensional data |
| Association Rule Learning | Discover co-occurring items | Apriori, FP-Growth | Market basket analysis |
| Anomaly Detection | Identify unusual observations | Isolation Forest, One-Class SVM | Detecting unusual transactions |

### Note that anomaly detection can also be supervised or semi-supervised, depending on the data and method.

### 3. Semi-supervised learning

**Definition:** Uses a small amount of labeled data alongside a larger amount of unlabeled data.

**Example:** Training an image classifier when only a small fraction of available images have been labeled.

Important approaches:

- Pseudo-labeling.
- Consistency regularization.
- Label propagation.

### 4. Reinforcement Learning

**Definition:** An agent learns to make decisions by interacting with an environment and receiving rewards or penalties.

| Concept | Meaning |
| --- | --- |
| Agent | The decision-making entity |
| Environment | The world in which it operates |
| State | The current situation |
| Action | A decision made by the agent |
| Reward | Feedback on an outcome |
| Policy | A strategy for choosing actions |

Important algorithms:

- Q-Learning.
- SARSA.
- Deep Q-Networks (DQN).
- Policy Gradient Methods.
- Actor-Critic Methods.

### 5. Self supervised

**Definition:** The model learns from training signals generated from the data itself rather than relying entirely on manually labeled examples.

Examples:

- Predicting masked words.
- Predicting the next token in a sequence.
- Learning representations from images.

**Modern relevance:** Self-supervised learning is fundamental to the pretraining of many large language models.

For example, GPT-style models are commonly pretrained to predict the next token.
