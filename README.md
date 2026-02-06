# Learning-On-Graphs

This repository contains **hands-on implementations and experiments with graph representation learning methods**, including both **neural graph models** and **random-walk–based embeddings**.

The code is organized as **individual Jupyter notebooks**, each focusing on a specific method, combining:

* exploratory / rough work, and
* a final, working implementation with evaluation results

---

## Implemented Methods

The repository includes implementations and experiments with the following models:

* **Graph Neural Networks (GNNs)**
* **Graph Attention Networks (GAT)**
* **GraphSAGE**
* **Node2Vec**
* **MetaPath2Vec**

These methods cover both:

* deep learning–based message passing approaches, and
* classical graph embedding techniques based on random walks

---

## Experimental Setup

* All models are evaluated on an in-house graph dataset
* The dataset is not included due to privacy and licensing constraints
* Manual cross-validation is performed for each method
* Evaluation results and observations are included directly in the notebooks

Each notebook is self-contained and documents:

* preprocessing steps
* model configuration
* training procedure
* validation strategy
* final results and insights

---

Each notebook contains:

* exploratory analysis and intermediate experiments
* a finalized implementation
* reported validation results

---

## Notes on Reproducibility

* Due to the absence of the dataset, the notebooks are intended to:

  * demonstrate implementation details
  * illustrate experimental design
  * showcase model comparison and analysis
* Dataset-dependent paths and loading logic may need to be adapted for external use

---

## Intended Use

This repository is intended for:

* learning and experimentation with graph representation learning
* reference implementations of common graph models
* demonstrating practical understanding of GNNs and graph embeddings

It is not designed as a plug-and-play library, but rather as a research and experimentation notebook collection.

---

## Key Takeaways

* Comparison of neural and random-walk–based graph embeddings
* Practical insights into training stability and performance differences
* Effects of model choice under consistent validation settings

---

