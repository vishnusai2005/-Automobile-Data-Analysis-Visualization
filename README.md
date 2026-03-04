# Automobile-Data-Analysis-Visualization
This repository contains an exploratory data analysis (EDA) and visualization project using Python. The project explores the `Automobile_data.csv` dataset to uncover trends, relationships, and distributions among various car features such as price, horsepower, engine size, and fuel efficiency.
## Dataset
The `Automobile_data.csv` file contains 205 records of various cars with 26 attributes. 
Key features include:
- **Physical Specifications:** Length, width, height, body style.
- **Engine Details:** Engine type, number of cylinders, engine size, horsepower, peak RPM.
- **Metrics:** City-mpg, Highway-mpg, and Price.

## Project Workflow
1. **Data Cleaning:** Replaced hidden null values (represented as `?`) with `NaN`, checked for duplicates, and converted necessary string columns (like `price` and `horsepower`) to numerical float types.
2. **Statistical Analysis:** Used Pandas to calculate means, medians, standard deviations, and generate a correlation matrix.
3. **Data Visualization:** Utilized Matplotlib and Seaborn to generate highly illustrative charts:
   - **Categorical Analysis:** `countplot`, `barplot`
   - **Distribution Analysis:** `boxplot`, `violinplot`, `distplot`
   - **Relational Analysis:** `scatterplot`, `lineplot`, `pairplot`, `heatmap`

## Technologies & Libraries Used
- **Python 3**
- **Pandas & NumPy** (Data manipulation and cleaning)
- **Matplotlib & Seaborn** (Data visualization)
- **Jupyter Notebook** (Interactive coding environment)

## How to Run
1. Clone the repository.
2. Ensure you have the required libraries installed: `pip install pandas numpy matplotlib seaborn`
3. Open `Seaborn.ipynb` in Jupyter Notebook or JupyterLab to view the code and visualizations.
