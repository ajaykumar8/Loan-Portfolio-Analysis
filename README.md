

```markdown
# Loan Portfolio Analysis

This project provides an analysis of a loan portfolio using various visualizations to explore key metrics such as average days past due, capital balances, and interest rates by borrower category and province. The analysis utilizes Python libraries including pandas, matplotlib, and seaborn to facilitate data manipulation and visualization.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [License](#license)

## Overview

The primary objective of this analysis is to derive insights from the loan dataset by:

- Calculating the average days past due by borrower category.
- Analyzing average capital balances and interest rates by province.
- Creating a heatmap to visualize correlations between various variables in the dataset.
- Compiling a risk profile for different provinces based on average metrics.

## Technologies Used

- **Python 3.x**
- **pandas**
- **matplotlib**
- **seaborn**

## Dataset

The dataset used in this project is a CSV file named `Loan_Portfolio_Confidential.csv`. It contains loan information such as:

- Loan Category
- Monthly Income
- Dependants
- Capital Balance
- Rate
- Day past due
- Province

Please ensure that the dataset is located in the same directory as the script or provide the correct path in the code.

## Installation

To run this project, ensure you have Python installed on your system. You can use pip to install the required libraries:

```bash
pip install pandas matplotlib seaborn
```

## Usage

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/ajaykumar8/loan-portfolio-analysis.git
    cd loan-portfolio-analysis
    ```

2. Ensure that the dataset `Loan_Portfolio_Confidential.csv` is in the same directory as the script.

3. Run the script:

    ```bash
    python loan_analysis.py
    ```

    Replace `loan_analysis.py` with the name of your Python script file if it is different.

## Visualizations

The analysis generates the following visualizations:

1. **Average Days Past Due by Borrower Category**: A bar chart illustrating the average number of days loans are past due, segmented by borrower category.
  
2. **Average Capital Balance and Rate by Province**: Two bar charts displaying average capital balances and interest rates for each province.

3. **Correlation Heatmap**: A heatmap that shows the correlation between different variables in the dataset.

4. **Risk Profile by Province**: A summary table of key metrics (average days past due, average capital balance, and average rate) for each province.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
