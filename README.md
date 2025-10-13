# GNN Model Comparison on RNA Secondary Structure Data

**Objective**: This notebook explores and compares the performance of different Graph Neural Network (GNN) models for the classifying RNA secondary structure graphs.

**Dataset**: RNA secondary structure graphs (13 classes).

**Models**:
* Graph Isomorphism Network (GIN)
* Graph Attention Network (GAT)
* DiffPool (Hierarchical Pooling with GCN-based layers)

**Implementation Details:**
* Utilizes the **DGL library** for graph handling and **PyTorch** for model implementation.
* Node features are derived from graph structure (degree, depth, subtree size, leaf status, number of children).
* A custom **BANANAS-inspired Bayesian Optimization** approach is implemented for hyperparameter tuning.
* Training includes techniques like **Learning Rate Scheduling** and **Gradient Clipping**.
* Results: Achieved an average test accuracy of approximately 42%, 40%, 32% for GIN, GAT, and DiffPool models, respectively.

Detailed metrics and comparison tables are provided later in the notebook.
