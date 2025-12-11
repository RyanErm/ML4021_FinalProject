## Repository Overview

### Project Description
In this repository, we have implemented 4 different machine learning models (SVM, Neural Network, Random Forest, Ridge Regression) to attempt to predict the score of an anime show based on many different feature columns. The data used for this project was acquired from [Kaggle](https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020) and perfomed exploratory analysis to understand and visualize the trends directly visible. For each model, we used a validation split of the data to measure the out of sample accuracy, then saved the test data for the final evaluation of the optimized models. 

### Software and Platform
This is project was run on Python 3.11

The packages used were:
- pandas
- numpy
- matplotlib
- scikit-learn
- torch
- ipykernel

Operating Systems: MacOS/Linux and Windows

### File structure
```mermaid
graph TD
    A[ML4021_FinalProject] --> B(notebooks);
    A --> C(data);
    B --> D(eda.ipynb);
    B --> E(ensemble.ipynb);
    B --> F(final_test.ipynb);
    B --> G(neuralnet_cv.ipynb);
    B --> H(ridge.ipynb);
    B --> I(svr.ipynb);
    A --> J(outputs);
    J --> K(tree.png)
    A --> L(.gitignore)
    A --> M(README.md)
    A --> N(requirements.txt)
    J --> O(nntraining.png)
    J --> P(svr.png)
    J --> Q(ridge.png)
    C --> R(cleaning_and_splitting.ipynb)
    C --> S(anime.csv)
    C --> T(X_test_data.csv)
    C --> U(X_train_data.csv)
    C --> V(Y_test_data.csv)
    C --> W(Y_train_data.csv)
```


