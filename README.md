# 📈 Simple Linear Regression

A hands-on exploration of **Simple Linear Regression** — one of the foundational algorithms in machine learning. This project implements the algorithm in two ways: using **scikit-learn** and **from scratch** using pure Python & NumPy.

---

## 🎯 Objective

Understand the mechanics of simple linear regression by:

1. **Building a model using scikit-learn** — leveraging the industry-standard ML library.
2. **Implementing from scratch** — deriving and coding the algorithm manually to deepen understanding of the underlying math (gradient descent, cost function, etc.).

---

## 📂 Project Structure

```
Simple linear regression/
├── simple_linear_regression_sklearn.ipynb   # Implementation using scikit-learn
├── simple_linear_regression_from_scratch.ipynb  # Implementation from scratch
└── README.md
```

---

## 🔬 What's Covered

### `simple_linear_regression_sklearn.ipynb`

- Loading and preparing data (NumPy arrays)
- Train/test split using `train_test_split`
- Fitting a `LinearRegression` model
- Making predictions on the test set
- Evaluating performance with **MSE** and **R²**
- Visualising results with a scatter plot + regression line

### `simple_linear_regression_from_scratch.ipynb`

- Manual implementation of linear regression
- Understanding the math behind the model (slope, intercept, cost function)
- Building the model without any ML library
- Comparing results to the scikit-learn implementation

---

## 📊 Sample Results (scikit-learn)

| Metric         | Value    |
|----------------|----------|
| Intercept (θ₀) | 5.038    |
| Slope (θ₁)     | 2.993    |
| MSE            | 0.270    |
| R² Score       | 0.998    |

> An R² of **0.998** indicates an excellent fit — the model explains ~99.8% of the variance in the data.

---

## 🛠️ Tech Stack

| Tool          | Purpose                        |
|---------------|--------------------------------|
| Python 3      | Programming language           |
| NumPy         | Numerical computing            |
| Matplotlib    | Data visualisation             |
| scikit-learn  | Machine learning library       |
| Jupyter / Colab | Interactive notebook environment |

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install numpy matplotlib scikit-learn jupyter
```

### Run the Notebooks

```bash
jupyter notebook
```

Then open either notebook to explore the implementations.

---

## 📖 Key Concepts

- **Simple Linear Regression**: Models the relationship between a single independent variable *X* and a dependent variable *y* using a straight line: `y = θ₀ + θ₁·X`
- **Mean Squared Error (MSE)**: Measures average squared difference between predicted and actual values — lower is better.
- **R² Score**: Indicates how well the model fits the data — closer to 1.0 is better.
- **Train/Test Split**: Divides data into training and testing subsets to evaluate generalisation.

---

## 👤 Author

**Zakaria Tanani** — [GitHub](https://github.com/TNZRalf)

---

## 📝 License

This project is open source and available for educational purposes.
