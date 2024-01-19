# XAI-tutorial
A course on explainable AI with Python. You can access the course here [coming soon].

### File Structure and Descriptions
The resources in the `src` folder are as follows:

| Folder             | File                             | Dataset           | Chapter | Description                                                                                           |
| ------------------ | -------------------------------- | ----------------- | ------- | ----------------------------------------------------------------------------------------------------- |
| intro              | human_friendly_explanations.ipynb| insurance.csv     | 4       | Using SHAP plots as the basis for human-friendly explanations                                         |
| linear_models      | power_of_linear_models.ipynb     | performance.csv   | 5       | Demonstrating how feature engineering allows linear models to model non-linear relationships          |
|                    | feature_engineering.ipynb        | credit_score.csv  | 6       | Interpretable feature engineering methods                                                             |
|                    | feature_clustering.ipynb         | credit_score.csv  | 8       | Feature selection with hierarchical feature clustering                                                |
|                    | linear_regression.ipynb          | credit_score.csv  | 9       | Explaining linear regression to a non-technical audience                                              |
|                    | challenge_notebook.ipynb         | credit_score.csv  | 5-9     | Logistic regression model for Part 2 challenge                                                        |
| model_agnostic     | feature_importance.ipynb         | credit_score.csv  | 11      | Calculating PFI scores from scratch                                                                   |
|                    | pdp_and_ice.ipynb                | PDP_ICE.csv       | 12      | Applying PDPs and ICE plots with scikit-learn                                                         |
|                    | ale.ipynb                        | abalone.data      | 13      | Applying ALEs with Alibi Explained                                                                    |
|                    | h_stat.ipynb                     | abalone.data      | 14      | Applying Friedman's H-stat with artemis                                                               |
|                    | lime.ipynb                       | abalone.data      | 15      | Applying lime                                                                                         |
|                    | shap.ipynb                       | credit_score.csv  | 16      | Applying SHAP                                                                                         |
| misc               | transaction_data_generator.ipynb | -                 | -       | Used to generate credit_score dataset                                                                 |

### Datasets

The datasets used by the files can be found in the `data` folder. More information about the datasets is available at these links:

- [credit_score.csv](https://www.kaggle.com/datasets/conorsully1/credit-score)
- [insurance.csv](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- [abalone.data](https://archive.ics.uci.edu/ml/datasets/Abalone)
- [PDP_ICE.csv](https://www.kaggle.com/datasets/conorsully1/pdp-and-ice-plots)
- [performance.csv](https://www.kaggle.com/datasets/conorsully1/annual-promotions)

### Packages and Versions

For the majority of the course, we use:

- Python 3.11.5
- `requirements.txt`

For Chapter 13's notebook, `ale.ipynb`, we use:

- Python 3.9.12
- `requirements_ale.txt`
