# python-week-7-assignment
Data Analysis Assignment — Iris Dataset
📌 Objective

Load and analyze a dataset using pandas.

Create simple plots and charts using matplotlib (and seaborn for styling).

📂 Dataset

Dataset: Iris dataset (loaded from sklearn.datasets.load_iris()).

Contains 150 samples of iris flowers with 4 features:

Sepal length (cm)

Sepal width (cm)

Petal length (cm)

Petal width (cm)

Target column: species (setosa, versicolor, virginica).

✅ Tasks Completed
Task 1: Load and Explore the Dataset

Loaded the dataset into a pandas DataFrame.

Displayed the first rows with .head().

Checked structure using .info().

Verified no missing values.

Task 2: Basic Data Analysis

Computed descriptive statistics with .describe().

Grouped data by species and calculated mean values.

Observed patterns such as:

Setosa has the smallest petal length and width.

Strong correlation between petal length and petal width.

Task 3: Data Visualization

Created four visualizations using matplotlib:

Line Chart — sample index vs sepal length.

Bar Chart — average petal length per species.

Histogram — distribution of sepal length.

Scatter Plot — sepal length vs sepal width (colored by species).

Each plot includes titles, labels, and legends.

🛠️ Tools & Libraries

Python 3

pandas

matplotlib

seaborn

scikit-learn

📊 Findings & Observations

Setosa species has noticeably smaller petals compared to others.

Virginica generally has the largest petal measurements.

Sepal length and sepal width show a mild negative correlation.

Petal length and petal width are strongly positively correlated.

📎 Submission

File submitted: kipepeo_iris_analysis_with_outputs.ipynb

The notebook contains:

Data loading and cleaning

Analysis

Visualizations

Findings
