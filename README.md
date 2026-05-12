# Countries-of-the-world-
Literacy Rate vs GDP per Capita
A data analysis project exploring the relationship between literacy rates and GDP per capita across 227 countries, using the "Countries of the World" dataset from Kaggle.
Hypothesis
Higher literacy rates lead to higher GDP per capita.
Key Findings

Correlation between Literacy (%) and GDP per Capita: 0.51 (strong positive relationship)
Average GDP for countries with literacy above 90%: $14,285.96
Average GDP for countries with literacy at or below 90%: $4,001.05
Linear Regression R² score: 23.47% (literacy alone explains about a quarter of the variance in GDP)

The data supports the hypothesis: countries with higher literacy rates tend to have higher GDP per capita.
Tech Stack

Python 3
pandas (data cleaning and analysis)
NumPy (numerical operations)
matplotlib & seaborn (visualization)
scikit-learn (Linear Regression model, train/test split, scaling)

Project Workflow

Import dataset: Load the "Countries of the World" CSV file.
Clean data: Handle missing values, convert European decimal format (comma) to standard decimal (dot), and cast columns to numeric types.
Explore data: Compute correlation and group averages.
Visualize: Create scatter plot (Literacy vs GDP) and bar plot (Average GDP by literacy group).
Model: Train a Linear Regression model with feature scaling and evaluate using R² score.

How to Run
Option 1: On Kaggle (recommended)

Open the notebook on Kaggle.
Add the "Countries of the World" dataset to the notebook input.
Run all cells.

Option 2: Locally

Install dependencies:

bash   pip install pandas numpy matplotlib seaborn scikit-learn

Download the dataset from Kaggle and place it in your working directory.
Update the file path in the notebook from /kaggle/input/countries of the world.csv to your local path.
Open the notebook in Jupyter or VS Code and run all cells.

Dataset

Source: Countries of the World on Kaggle
Rows: 227 countries
Columns: 20 (Country, Region, Population, Area, GDP, Literacy, Birthrate, etc.)

Limitations

The R² score of 23.47% shows literacy is a useful predictor but not the only factor affecting GDP per capita.
Other variables (infrastructure, natural resources, governance, industry mix) likely play a significant role.
Correlation does not imply causation: high literacy and high GDP could both be effects of broader economic development.

Future Work

Add more features (Phones per 1000, Infant mortality, Industry share) to improve the regression model.
Try non-linear models (KNN, Random Forest, Gradient Boosting).
Group countries by region and analyze regional patterns.

Author
Linh, 12th-grade student learning Python at Algorithmics.

Email: aylinspaceu2@gmail.com
GitHub: @aylinph

License
Released under the MIT License. See LICENSE for details.ProgressSee task progress for longer tasks.Working foldersCODE PORTFOLIO - GITHUBInstructions · CLAUDE.mdLICENSEREADME.mdquiz-app-pythonContextUploadsprojectalgoptpcase2-mainmain (4).ipynbabout.html
