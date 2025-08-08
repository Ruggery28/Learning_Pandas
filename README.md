# Titanic Survival Prediction 🚢

In this notebook, I explore the Titanic dataset to identify which factors influenced passenger survival.  
I clean the data, visualize key patterns, and build a simple machine learning model to predict who survived.

import pandas as pd

# Load dataset
url = "https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"
df = pd.read_csv(url)

df.head()

df.info()
df.describe()


