# CS229: Machine Learning — Study Notes & Practice Notebooks

Self-study materials for Stanford's [CS229: Machine Learning](https://cs229.stanford.edu/) course taught by Andrew Ng.

This repository contains **lecture summaries** and **hands-on Jupyter notebooks** for each lecture, built from scratch to reinforce the concepts through theory and implementation.

---

## 📂 Repository Structure

    CS229/
    ├── README.md
    ├── Notebooks/
    │   ├── CS229_Lecture_2.ipynb
    │   ├── CS229_Lecture_3.ipynb
    │   ├── CS229_Lecture_4.ipynb
    │   └── CS229_Lecture_5.ipynb
    ├── Lecture Handouts/
    │   ├── cs229-notes1.pdf
    │   ├── cs229-notes2.pdf
    │   ├── cs229-notes3.pdf
    │   ├── cs229-notes4.pdf
    │   ├── cs229-notes5.pdf
    │   ├── cs229-notes6.pdf
    │   ├── cs229-notes7a.pdf
    │   ├── cs229-notes7b.pdf
    │   ├── cs229-notes8.pdf
    │   ├── cs229-notes9.pdf
    │   ├── cs229-notes10.pdf
    │   ├── cs229-notes11.pdf
    │   └── cs229-notes12.pdf
    └── Review Notes/
        ├── cs229-cvxopt.pdf
        ├── cs229-cvxopt2.pdf
        ├── cs229-gp.pdf
        ├── cs229-hmm.pdf
        ├── cs229-linalg.pdf
        └── cs229-prob.pdf


---

## 📒 Notebooks Overview

| Lecture | Topic | Key Concepts |
|---------|-------|--------------|
| **Lecture 2** | Linear Regression & Gradient Descent | Linear regression, cost function (MSE), batch/stochastic gradient descent, normal equations, feature scaling |
| **Lecture 3** | Locally Weighted & Logistic Regression | Locally weighted linear regression, logistic regression, sigmoid function, binary cross-entropy, Newton's method |
| **Lecture 4** | Perceptron & Generalized Linear Models | Perceptron algorithm, Exponential family, GLM framework, Linear/Logistic/Softmax Regression as GLMs |
| **Lecture 5** | GDA & Naive Bayes | Discriminative vs. Generative models, Gaussian Discriminant Analysis, Naive Bayes, Laplace smoothing |

> More notebooks will be added as I progress through the course.

---

## 🧠 What Each Notebook Contains

- **Markdown cells** — Theory, derivations, and key equations from the lecture
- **Code cells** — From-scratch implementations of all algorithms (NumPy only)
- **Visualizations** — Decision boundaries, loss curves, distribution plots
- **Comparisons** — Side-by-side evaluation of related models
- **Exercises** — Practice problems with starter code

---

## 🛠 Requirements

    python >= 3.8
    numpy
    matplotlib
    scipy
    scikit-learn
    jupyter

Install dependencies:

    pip install numpy matplotlib scipy scikit-learn jupyter

---

## 🚀 Getting Started

1. Clone the repository:

        git clone https://github.com/<your-username>/cs229.git
        cd cs229

2. Launch Jupyter:

        jupyter notebook

3. Open any notebook and run the cells sequentially.

---

## 📚 Course Resources

- [CS229 Course Website](https://cs229.stanford.edu/)
- [CS229 Lecture Notes](http://cs229.stanford.edu/main_notes.pdf)
- [CS229 YouTube Playlist](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU)
- [CS229 Problem Sets](https://cs229.stanford.edu/syllabus.html)

---

## 📌 Notes

- All algorithms are implemented **from scratch** using NumPy for learning purposes — no ML library calls for the core models.
- `scikit-learn` is used only for dataset generation, train/test splitting, and baseline comparisons.
- Notebooks are self-contained — each one can be run independently.

---

## 📄 License

This repository is for **personal educational use**. Course materials and lecture content belong to Stanford University and the CS229 teaching team.
