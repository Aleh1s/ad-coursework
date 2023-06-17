# Data Analysis Coursework Repository

This repository contains the coursework project on data analysis. The project aims to analyze a specific domain by following several stages and tasks. The main objectives of the project are as follows:

1. Analysis of the subject area.
2. Data loading, description, and preprocessing.
3. Preliminary data analysis.
4. Data partitioning for model training.
5. Selection of prediction methods.
6. Analysis and comparison of results for each method.

The goal is to create an application that accepts data of a specific structure, cleans, transforms, analyzes, and displays relevant graphs. The application will also build models to classify data into two classes: CT (Counter-Terrorists) and T (Terrorists), determining which side will win the round.

Prediction will be performed using classification models, specifically Random Forest, Decision Tree, and K-Nearest Neighbors. It is necessary to find the optimal parameters for the models, where the mean squared error, R2 score, and accuracy metrics are optimized. Subsequently, a comparison of the evaluations of all models will be conducted to identify the best model for the most accurate prediction of results.

The input parameters consist of a snapshot of the game field during a specific period of the round. The snapshot includes information such as the map, health points, players, specific types of weapons, grenades, armor, defusal kits, time remaining in the round, money, whether the bomb is planted, the current score, and the round winner.

## Dependencies

To run the application and reproduce the results, the following dependencies are required:

- Python 3.x
- Libraries: pandas, scikit-learn, matplotlib, seaborn, etc.
- Jupyter Notebook
- Dataset: [Counter-Strike: Global Offensive Matchmaking Data](https://www.kaggle.com/datasets/christianlillelund/csgo-round-winner-classification)
- IDE: PyCharm

## Contributors

This coursework project was developed by Oleksandr Palamarchuk (Aleh1s). If you have any questions or suggestions, please feel free to contact us.

We hope you find this repository helpful for your data analysis project!
