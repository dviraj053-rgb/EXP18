# EXP18
**Aim:**
To explore statistical methods and advanced data visualization techniques.

**Theory:**
The main objective of Exploratory Data Analysis (EDA) is to understand the structure of a dataset, identify outliers, detect patterns, and validate assumptions before applying formal models. By combining statistical summaries with visual tools—such as box plots to examine data distribution and scatter plots to analyze relationships—analysts can gain a deeper understanding of the dataset’s quality and underlying trends. Data visualization plays a key role in transforming complex information into clear graphical representations, making it easier to uncover patterns, correlations, and insights.

Key functions and operations include:

* **import seaborn as sns:** Loads the Seaborn library for creating visually appealing statistical graphics.
* **import matplotlib.pyplot as plt:** Imports Matplotlib for generating a wide range of visualizations.
* **pd.read_csv():** Reads data from a CSV file into a DataFrame.
* **df.head():** Displays the first few rows to quickly inspect the dataset.
* **df.info():** Provides a summary of the dataset, including data types and non-null values.
* **df.describe():** Produces descriptive statistics such as mean, standard deviation, and quartiles.
* **df.isnull().sum():** Identifies and counts missing values in each column.
* **df.drop():** Removes selected rows or columns to clean the dataset.
* **sns.histplot():** Visualizes the distribution of a single numerical variable.
* **sns.boxplot():** Shows data spread and highlights potential outliers.
* **sns.scatterplot():** Illustrates relationships between two numerical variables.
* **plt.figure(figsize=...):** Sets the size of the plot for better readability.
* **plt.title():** Adds a meaningful title to the visualization.
* **plt.show():** Displays the generated plots.

**Conclusion:**
This experiment demonstrates that EDA is a crucial step in the data analysis process. By combining statistical techniques with visualizations, it becomes easier to detect issues such as missing values and outliers, as well as to uncover meaningful relationships that guide further analysis and decision-making.
