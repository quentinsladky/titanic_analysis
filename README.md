# Titanic_survival_analysis
An exploratory analysis of the decisive factors for survival aboard the Titanic, using the Kaggle train.csv database, gathering 891 passengers and 12 columns, covering age, gender and class. The goal is to pinpoint which variable is the dominant survival factor, and which acts as an amplifier. 
Stack : Python, Pandas, NumPy, Matplotlib, Seaborn. 
Developed in VS Code and presented as a Jupyter Notebook. 

## Key Findings
- Female survival is higher than Men's : Women 74%, Men 19%.
- The higher the class is, the better the chances of survival are : First class 63%, Second class 47%, Third class 24%.
- Children have more chances of survival than Adults and Elders : Children 50%, Adults 36%, Elders 23%.
- Gender is the dominant survival factor, while class acts as an amplifier : Women in First class 97%, Women in Third class 50%, Men in First class 37%, Men in Third class 14%.

## Project Structure
- `titanic_analysis.ipynb` — Main Jupyter Notebook (analysis + visualizations)
- `train.csv` — Kaggle Titanic dataset

## How to Run
1. Clone the repository
2. Install dependencies : `pip install pandas numpy matplotlib seaborn jupyter`
3. Open `titanic_analysis.ipynb` in Jupyter Notebook

> **Note :** `train.csv` is not included. Download it from [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data).
