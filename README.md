# Recommender Systems: A Comprehensive Guide

Welcome to this repository! This project is a deep dive into the world of recommender systems. It includes notebooks on collaborative filtering, contextual awareness, and evaluation techniques for recommender systems.

---

## Table of Contents

1. [Overview](#overview)
2. [Getting Started](#getting-started)
3. [Notebooks](#notebooks)
   - [Collaborative Filtering](#collaborative-filtering)
   - [Content-based Recommender](#content-based-recommender)
   - [Contextual Awareness Recommender Systems](#contextual-awareness-recommender-systems)
   - [Evaluation of Recommender Systems](#evaluation-of-recommender-systems)
4. [Usage Instructions](#usage-instructions)

---

## Overview

This repository focuses on building and evaluating recommender systems. The goal is to provide a comprehensive and practical approach to understanding and implementing:

- Collaborative Filtering techniques
- Contextual Awareness in recommendations
- Effective evaluation methodologies for recommenders

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.9 or above
- [UV](https://github.com/iterative/uv) (for dependency management)

### Setting Up the Environment

To ensure you replicate the exact environment, the repository includes a `uv.lock` file. Follow these steps to set up:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/recommender-systems.git
   cd recommender-systems
   ```

2. **Install dependencies using UV:**:
   ```bash
   uv --sync install
   ```

3. **Activate the environment:**:
   ```bash
   uv shell
   ```


## Notebooks

### Collaborative Filtering

Notebook: `recommender-systems-notebooks/collaborative-filtering.ipynb`

- Learn the fundamentals of collaborative filtering.
- Implement both user-based and item-based collaborative filtering.
- Analyze strengths and weaknesses with real-world examples.

### Content-based Recommender

Notebook: `recommender-systems-notebooks/content-based.ipynb`

- Learn the fundamentals of content-based recommenders.
- Implement popular algorithms.
- Analyze strengths and weaknesses with real-world examples.

### Contextual Awareness Recommender Systems

Notebook: `recommender-systems-notebooks/contextual-aware-recommender.ipynb`

- Explore the role of context in recommendations.
- Implement contextual modeling techniques.
- Use advanced algorithms like Factorization Machines (FM) and Context-Aware Collaborative Filtering.

### Evaluation of Recommender Systems

Notebook: `recommender-systems-notebooks/evaluation-recommenders.ipynb`

- Understand evaluation metrics for recommender systems.
- Compare accuracy, diversity, novelty, and fairness.
- Experiment with real-world datasets to evaluate performance.

---

## Usage Instructions

1. Open the Jupyter Notebook interface using the setup instructions above.
2. Navigate to the `notebooks/` folder.
3. Select the desired notebook to explore:
   - `collaborative_filtering.ipynb`
   - `contextual_aware_recommender.ipynb`
   - `evaluation.ipynb`
4. Run the cells sequentially to replicate the results and learn the concepts.

---

