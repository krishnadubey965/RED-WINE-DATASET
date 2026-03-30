# Red Wine Quality Exploratory Data Analysis (EDA)

This project contains an Exploratory Data Analysis (EDA) on the Red Wine Quality dataset. The analysis is performed using Python in a Jupyter Notebook and leverages popular data science libraries such as pandas, matplotlib, and seaborn to uncover insights and relationships within the data.

## Dataset
The dataset `winequality-red.csv` contains physicochemical tests of red variants of the Portuguese "Vinho Verde" wine, along with sensory data (quality ratings).

## Analysis Overview
The Jupyter Notebook (`Red Wine Dataset.ipynb`) covers the following steps:
1. **Data Loading & Summary**: Loading the dataset and examining its structure using `.info()`, `.describe()`, and exploring the columns.
2. **Data Cleaning**: Checking for missing values and identifying/removing duplicated rows to ensure data integrity.
3. **Correlation Analysis**: Generating a correlation matrix and visualizing it using a heatmap to understand the relationships between different physicochemical properties.
4. **Data Visualization**:
   - **Target Variable Analysis**: Visualizing the distribution of the `quality` variable (revealing an imbalanced dataset).
   - **Feature Distributions**: Plotting histograms with Kernel Density Estimates (KDE) for all features (e.g., alcohol content) to understand their distributions.
   - **Multivariate Analysis**: Using extensive visualizations including pairs plots (`sns.pairplot`), categorical box plots (`sns.catplot`), and scatter plots to explore relationships (e.g., `alcohol` vs. `pH` colored by `quality`).

## Technologies Used
- **Python**
- **Pandas** for data manipulation
- **Matplotlib** & **Seaborn** for data visualization

## How to Run
To run the analysis locally:
1. Ensure you have Python and Jupyter installed.
2. Install the necessary libraries:`pip install pandas matplotlib seaborn`.
3. Open `Red Wine Dataset.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the cells to see the analysis and visualizations.
