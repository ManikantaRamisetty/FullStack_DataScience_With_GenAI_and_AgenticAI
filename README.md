# FullStack_DataScience_With_GenAI_and_AgenticAI

Pandas vs Matplotlib vs Seaborn
Library	Purpose
Pandas	Work with and analyze data
Matplotlib	Create charts
Seaborn	Create statistical/ML charts

import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

df = pd.read_csv("employees.csv")

# Data analysis
print(df.describe())

# Visualization
sns.scatterplot(data=df, x='Exp', y='Salary')
plt.show()
