import numpy as np
import pandas as pd
import matplotlib as plt
import seaborn as sns
from sklearn.datasets import fetch_california_housing
from sklearn.model selection import train_test_split, GridSearchCV
from sklearn.linear_model import linearRegression, Ridge
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import mean_squared_error, mean_absolute-error, r2

data = fetch_califorina_housing()
x = pd.DataFrame(data.data, columns=data.forms,)
