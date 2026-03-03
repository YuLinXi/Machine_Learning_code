# Machine Learning Code

A code repository containing complete implementations of the Machine Learning Specialization course by Andrew Ng.

## Course Overview

This repository contains code implementations for all three courses in the Machine Learning Specialization:

1. **Supervised Machine Learning: Regression and Classification**
2. **Advanced Learning Algorithms**
3. **Unsupervised Learning, Recommenders, Reinforcement Learning**

## Course Content

### Course 1: Supervised Machine Learning: Regression and Classification

| Week | Topics |
|------|--------|
| Week 1 | Supervised vs. Unsupervised Learning, Regression Models, Gradient Descent |
| Week 2 | Multiple Linear Regression, Feature Scaling, Learning Rate Tuning |
| Week 3 | Logistic Regression Classification, Decision Boundaries, Overfitting, Regularization |

### Course 2: Advanced Learning Algorithms

| Week | Topics |
|------|--------|
| Week 1 | Intuitive Understanding of Neural Networks, Neural Network Models, TensorFlow Implementation |
| Week 2 | Neural Network Training, Activation Functions, Multi-class Classification |
| Week 3 | Practical Advice for Machine Learning, Bias and Variance Analysis |
| Week 4 | Decision Trees, Ensemble Methods |

### Course 3: Unsupervised Learning, Recommenders, Reinforcement Learning

| Week | Topics |
|------|--------|
| Week 1 | Clustering Algorithms, K-means, Anomaly Detection |
| Week 2 | Collaborative Filtering Recommender Systems, Content-Based Recommendations |
| Week 3 | Reinforcement Learning Fundamentals, Deep Q-Learning |

## Key File Descriptions

### Utility Libraries

- `lab_utils_common.py` - General utility functions (gradient descent, cost functions, etc.)
- `lab_utils_uni.py` - Visualization tools for univariate regression
- `lab_utils_multi.py` - Visualization tools for multivariate regression
- `lab_utils_relu.py` - ReLU activation function visualization
- `lab_utils_softmax.py` - Softmax visualization
- `lab_utils_multiclass_TF.py` - TensorFlow tools for multi-class classification

### Practical Assignments

Each course includes:

- **Jupyter Notebook Labs** - Interactive programming exercises
- **Practice Quizzes** - Chapter knowledge checks
- **Programming Assignments** - Comprehensive project exercises
- **Datasets** - Example datasets used in the course

## Environment Requirements

- Python 3.x
- NumPy
- Matplotlib
- TensorFlow
- Scikit-learn

Install dependencies:

```bash
pip install numpy matplotlib tensorflow scikit-learn
```

## Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://gitee.com/yulinxibest/Machine_Learning_code
   ```

2. Navigate to the corresponding course directory:
   ```bash
   cd "One Supervised Machine Learning Regression and Classification"
   ```

3. Launch Jupyter Notebook to open and run `.ipynb` files:
   ```bash
   jupyter notebook
   ```

## Course Reference

The code in this repository is based on Andrew Ng’s Machine Learning Specialization course on Coursera.

- Course Link: https://www.coursera.org/specializations/machine-learning-introduction

## Directory Structure

```
Machine_Learning_code/
├── One Supervised Machine Learning Regression and Classification/
│   ├── week1/          # Fundamentals of Supervised Learning
│   ├── week2/          # Multiple Linear Regression
│   └── week3/          # Logistic Regression
├── Two Advanced Learning Algorithms/
│   ├── week1/          # Neural Network Fundamentals
│   ├── week2/          # Neural Network Training
│   ├── week3/          # Bias and Variance
│   └── week4/          # Decision Trees
└── Three Unsupervised Learning Recommenders Reinforcement Learning/
    ├── week1/          # Clustering and Anomaly Detection
    ├── week2/          # Recommender Systems
    └── week3/          # Reinforcement Learning
```

## License

This repository is intended solely for learning and educational purposes. Please respect the course copyright.

## Acknowledgments

Thank you to Professor Andrew Ng and his team for providing high-quality machine learning course content.