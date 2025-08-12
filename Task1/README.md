🧪 Task 1: Exploring and Visualizing a Simple Dataset 📌 Objective The goal of this task is to perform Exploratory Data Analysis (EDA) on a well-known dataset to understand its structure, trends, and feature relationships through various visualizations.

📂 Dataset Used Name: Iris Dataset

Source: Built-in with seaborn library

Description: The Iris dataset contains 150 samples of iris flowers from three species (setosa, versicolor, virginica). It includes 4 features per sample:

sepal_length

sepal_width

petal_length

petal_width

🔧 Tools and Libraries pandas – for data loading and inspection

matplotlib – for plotting and charts

seaborn – for advanced visualizations

📊 Tasks Performed ✅ Loaded the Iris dataset using seaborn.load_dataset()

✅ Displayed dataset structure using .head(), .info(), .describe()

✅ Checked for missing values

✅ Visualized relationships using:

Scatter Plot: Sepal length vs width by species

Histograms: Distribution of each feature

Box Plots: To detect outliers in the dataset

📈 Sample Visuals 🔹 Scatter Plot Displays the relation between sepal length and width by species.

🔹 Histograms Shows the frequency distribution of each numerical column.

🔹 Box Plots Helps identify outliers and spread of the data.

🧠 Key Insights No missing data in the dataset

Distinct separation between species based on petal measurements

Setosa is clearly distinguishable from other species in visual plots

Some overlap exists between versicolor and virginica

📁 Folder Structure bash Copy Edit Task1_Exploratory_Analysis/ ├── iris_eda.ipynb # Main Jupyter notebook ├── README.md # Project summary (this file)

✅ Completion Checklist Dataset Loaded

EDA Completed

Visualizations Plotted

Summary Documented

🔗 Credits Dataset: Seaborn Iris Dataset

Internship Program: AI/ML Engineering Internship – DevelopersHub Corporation
