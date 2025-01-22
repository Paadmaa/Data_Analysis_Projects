# Customer Churn Analysis

This repository contains a Jupyter Notebook (`TCA.ipynb`) that analyzes customer churn data. The notebook explores the dataset, cleans the data, and lays the groundwork for a detailed analysis of factors influencing customer churn.

## Key Features

1. **Data Loading**:
   - The dataset is loaded using the `pandas` library.
   - Initial data exploration provides insights into the dataset's structure and content.

2. **Data Cleaning**:
   - Blank values in the `TotalCharges` column are identified and replaced with `0`.
   - Data types are adjusted for numerical operations (e.g., converting `TotalCharges` to `float`).

3. **Exploratory Data Analysis (EDA)**:
   - Potential analyses include understanding churn rates across demographics, contract types, and services.
   - Numeric data such as `MonthlyCharges` and `TotalCharges` can be visualized to identify patterns or trends.

4. **Dataset Details**:
   - **Rows**: 7043
   - **Columns**: 21
   - Key Columns:
     - `customerID`: Unique identifier for each customer.
     - `gender`: Gender of the customer.
     - `SeniorCitizen`: Indicates if the customer is a senior citizen.
     - `tenure`: Number of months the customer has been with the company.
     - `InternetService`: Type of internet service (DSL, Fiber optic, None).
     - `MonthlyCharges`: Monthly charges for the customer.
     - `TotalCharges`: Total charges for the customer.
     - `Churn`: Indicates if the customer has churned (Yes/No).

## Prerequisites

To run the notebook, ensure you have the following installed:
- Python 3.7+
- Jupyter Notebook
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/churn-analysis.git
   ```

2. Navigate to the folder and open the notebook:
   ```bash
   cd churn-analysis
   jupyter notebook TCA.ipynb
   ```

3. Run the notebook cells sequentially to:
   - Load and clean the data.
   - Explore key metrics and insights.

## Future Enhancements

- Add detailed visualizations to identify trends and patterns.
- Implement predictive modeling to forecast customer churn.
- Automate reporting for periodic churn analysis.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For questions or collaboration, please reach out at [padmachbehera23@gmail.com](mailto:your.email@example.com).

