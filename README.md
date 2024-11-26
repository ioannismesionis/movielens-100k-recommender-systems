# Recommender Systems: A Comprehensive Guide

Welcome to this repository! This project was part of my own research to better understand recommender systems. If I had to describe the repo, I would consider it a distillation of the different resources I have read online and it's heavily based on the book "Recommender Systems: The Textbook" from Chary Aggarwal and implementations of the Cornac library. It includes notebooks on collaborative filtering, content-based recommenders, contextual awareness recommenders (using time as context), and different evaluation techniques used for recommender systems.

---

## Table of Contents

- [Recommender Systems: A Comprehensive Guide](#recommender-systems-a-comprehensive-guide)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Setting Up the Environment](#setting-up-the-environment)
  - [Notebooks](#notebooks)
    - [Collaborative Filtering](#collaborative-filtering)
    - [Content-based Recommender](#content-based-recommender)
    - [Contextual Awareness Recommender Systems](#contextual-awareness-recommender-systems)
    - [Evaluation of Recommender Systems](#evaluation-of-recommender-systems)

---

## Overview

This repository focuses on building and evaluating recommender systems. The goal is to provide a comprehensive and practical approach to understanding and implementing:

- Collaborative Filtering Recommenders
- Content-based Recommenders
- Contextual Awareness in Recommendation Engines
- Evaluation of Recommenders

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

You can find more information in the [uv](https://docs.astral.sh/uv/getting-started/) documentation page.

## Notebooks

### Collaborative Filtering

Notebook: `recommender-systems-notebooks/collaborative-filtering.ipynb`

- Learn the fundamentals of collaborative filtering and the type of recommenders.
- Includes various implementation (e.g. matrix factorisation) using the movieLens 100K dataset.

### Content-based Recommender

Notebook: `recommender-systems-notebooks/content-based.ipynb`

- Learn the fundamentals of content-based recommenders.
- Includes the mathematics of different algorithms presented in Aggarwal's book.

### Contextual Awareness Recommender Systems

Notebook: `recommender-systems-notebooks/contextual-aware-recommender.ipynb`

- Explore the role of context in recommendations.
- Implement contextual modeling techniques.
- Use advanced algorithms like Factorization Machines (FM) and Context-Aware Collaborative Filtering.

### Evaluation of Recommender Systems

Notebook: `recommender-systems-notebooks/evaluation-recommenders.ipynb`

- Understand evaluation metrics for recommender systems.
- Compare accuracy, diversity, novelty, and fairness.

---