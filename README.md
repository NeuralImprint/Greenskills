# Greenskills
The modified notebook includes several key improvements that enhance its readiness for machine learning tasks. It begins by importing additional essential libraries such as `matplotlib.pyplot` and `seaborn` for data visualization, as well as multiple `sklearn` modules including `RandomForestClassifier`, `train_test_split`, `MinMaxScaler`, and `classification_report` for preprocessing, modeling, and evaluation. It also introduces `joblib` for saving the trained model.

The dataset is explicitly loaded using `pandas.read_csv()` from a CSV file named `irrigation_machine.csv`, establishing a clear data entry point. A statistical overview of the dataset is provided using `df.describe()` to summarize key metrics. The data is then organized by separating input features (`X`) from the output labels (`y`), with the first 20 columns used as features and the remaining columns as targets.

To prepare the data for modeling, `MinMaxScaler` is applied to normalize the feature values, ensuring they are scaled between 0 and 1. These modifications collectively transition the notebook from basic data handling to a structured, machine learning-ready workflow.
