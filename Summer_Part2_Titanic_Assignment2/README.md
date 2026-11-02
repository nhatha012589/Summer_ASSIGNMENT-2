# Titanic Data Analysis — Assignment 2, Part 2

## Project Overview
This project performs exploratory data analysis (EDA) on the Titanic training dataset from Kaggle. It investigates whether passenger survival is associated with passenger class, gender, and age.

The notebook follows the assignment instructions: explore the dataset, analyze at least three hypotheses, create plots for each hypothesis, and summarize the findings in a one-page PDF report.

## Research Questions
1. Is survival rate associated with passenger class?
2. Is survival rate associated with gender?
3. Is survival rate associated with age?

## Repository Structure
```text
Summer_Titanic_Assignment2/
├── Data/
│   └── train.csv
├── Src/
│   └── Summer_Assignment_2_Part_2.ipynb
├── Docs/
│   └── Summer_Assignment_2_Part_2_Report.pdf
├── Results/
│   ├── Survival Rate by Passenger Class.png
│   ├── Survival Rate by Gender.png
│   ├── Survival Count by Gender.png
│   └── Age Distribution by Survival Status.png
└── README.md
```

## Tools and Libraries
- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn

## Key Findings
- **Passenger class:** First-class passengers had the highest observed survival rate (about 63%), followed by second class (about 47%) and third class (about 24%).
- **Gender:** Female passengers had a higher observed survival rate (about 74%) than male passengers (about 19%).
- **Age:** The average ages of passengers who did not survive and those who survived were approximately 30.6 and 28.3 years, respectively. The age distributions overlap considerably.

These findings describe associations in the dataset and do not establish causation. Age is missing for 177 passengers, so age analysis uses records with an available age.

## How to Run
1. Download or clone this repository.
2. Open `Src/Summer_Assignment_2_Part_2.ipynb` in Jupyter Notebook.
3. Run the cells from top to bottom.
4. The notebook reads the dataset from `../Data/train.csv` and saves generated charts in `../Results/`.

Install the required libraries if needed:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Final Report
The one-page PDF report is available in the `Docs/` folder.

## Author
Summer
