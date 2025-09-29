# Task-5--Exploratory-Data-Analysis
Tools- Python(Pandas, Matplotlib, Seaborn)
# Task 5: Exploratory Data Analysis (EDA) on the Titanic Dataset
Project Goal
The primary objective of this project was to perform comprehensive Exploratory Data Analysis (EDA) on the provided dataset to extract meaningful insights using visual and statistical exploration. The ultimate outcome is to gain skill in finding patterns, trends, and anomalies within the data.

Dataset
Primary Dataset: TITANIC DATASET (or an equivalent relevant dataset).

Tools and Libraries
The analysis was performed entirely within a Jupyter Notebook (p1.ipynb) using the following Python libraries:

Data Manipulation: Pandas

Numerical Operations: NumPy

Visualization: Matplotlib and Seaborn

Methodology and Steps
The EDA process followed a structured approach as outlined in the task brief:

Initial Data Inspection:

Used .info() to inspect data types and identify missing values.

Used .describe() to view the central tendency, dispersion, and shape of the numerical columns.

Used .value_counts() on categorical variables to understand distribution.

Univariate Analysis:

Plotted Histograms to visualize the distribution of numerical features (e.g., Age, Fare).

Created Boxplots to detect outliers and understand the five-number summary for numerical features.

Bivariate and Multivariate Analysis:

Used sns.pairplot() to visualize the pairwise relationships between selected numerical features.

Plotted Scatterplots to investigate correlations between two numerical variables.

Generated a Heatmap using sns.heatmap() on the correlation matrix to identify strong linear relationships between variables.

Used Boxplots and KDE plots to visualize the relationship between key categorical features (e.g., Pclass, Sex) and the target variable (e.g., Survival).

Insight Generation:

Wrote observations for each visual representation.

Provided a comprehensive summary of findings.
