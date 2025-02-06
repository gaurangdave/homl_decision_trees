# Hands On ML - Decision Trees

## 🎯 Project Goal
* The main goal of this project, is to practise the exercise problems in `Chapter 6 - Decision Trees` of `Hands-On Machine Learning with Scikit-Learn, Keras and Tensorflow`

## Exercises
* The project will focus on following two exercise problems,

### Exercise 1
* Train and fine-tune a decision tree for the moons dataset by following these steps:
    * Use make_moons(n_samples=10000, noise=0.4) to generate a moons dataset.
    * Use train_test_split() to split the dataset into a training set and a test set.
    * Use grid search with cross-validation (with the help of the GridSearchCV class) to find good hyperparameter values for a DecisionTreeClassifier. Hint: try various values for max_leaf_nodes.
    * Train it on the full training set using these hyperparameters, and measure your model’s performance on the test set. You should get roughly 85% to 87% accuracy.

### Exercise 2
* Grow a forest by following these steps:
    * Continuing the previous exercise, generate 1,000 subsets of the training set, each containing 100 instances selected randomly. Hint: you can use Scikit-Learn’s ShuffleSplit class for this.
    * Train one decision tree on each subset, using the best hyperparameter values found in the previous exercise. Evaluate these 1,000 decision trees on the test set. Since they were trained on smaller sets, these decision trees will likely perform worse than the first decision tree, achieving only about 80% accuracy.
    * Now comes the magic. For each test set instance, generate the predictions of the 1,000 decision trees, and keep only the most frequent prediction (you can use SciPy’s mode() function for this). This approach gives you majority-vote predictions over the test set.
    * Evaluate these predictions on the test set: you should obtain a slightly higher accuracy than your first model (about 0.5 to 1.5% higher). Congratulations, you have trained a random forest classifier!

## ✅ Solution Details

### 📒 Notebooks

## 💻 Tech Stack

![Environment](https://img.shields.io/badge/Environment-Google_Colab-FCC624?logo=googlecolab&style=for-the-badge)  
![Python](https://img.shields.io/badge/Python-3.12.2-FFD43B?logo=Python&logoColor=blue&style=for-the-badge)  
![Pandas](https://img.shields.io/badge/Pandas-2.2.2-2C2D72?logo=Pandas&logoColor=2C2D72&style=for-the-badge)  
![Plotly](https://img.shields.io/badge/Plotly-5.24.1-239120?logo=Plotly&logoColor=239120&style=for-the-badge)  
![Scikit Learn](https://img.shields.io/badge/scikit_learn-1.5.1-F7931E?logo=scikit-learn&logoColor=F7931E&style=for-the-badge)  

## 🚀 About Me

A jack of all trades in software engineering, with 15 years of crafting full-stack solutions, scalable architectures, and pixel-perfect designs. Now expanding my horizons into AI/ML, blending experience with curiosity to build the future of tech—one model at a time.

## 🔗 Links

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://gaurangdave.me/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gaurangvdave/)

## 🛠 Skills

`Python`, `Jupyter Notebook`, `scikit-learn`, `FastAPI`, `Plotly`, `Conda`