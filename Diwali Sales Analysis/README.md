# Diwali Sales Analysis

This repository contains a comprehensive analysis of customer behavior and sales trends during the Diwali season. The project aims to derive actionable insights that can optimize marketing strategies and enhance sales performance for future Diwali campaigns.

## Objective
The primary goal is to analyze customer purchasing patterns, identify top-performing products, and uncover demographic segments contributing significantly to sales. These insights will inform data-driven marketing and inventory strategies.

## Dataset Overview
- **Total Rows**: 11,251
- **Total Columns**: 15
- **Key Columns**:
  - `User_ID`: Unique identifier for each customer.
  - `Cust_name`: Name of the customer.
  - `Gender`: Customer's gender.
  - `Age Group`: Categorized age range of the customer.
  - `Marital_Status`: Indicates whether the customer is married.
  - `State` and `Zone`: Customer's geographic location.
  - `Occupation`: Profession of the customer.
  - `Product_Category`: Category of the purchased product.
  - `Orders`: Number of orders placed.
  - `Amount`: Total amount spent by the customer.

## Key Features

1. **Data Cleaning**:
   - Address missing values in the `Amount` column.
   - Remove irrelevant columns (`Status` and `unnamed1`) that contain no usable data.

2. **Exploratory Data Analysis (EDA)**:
   - Examine customer demographics, such as `Gender`, `Age Group`, and `State`.
   - Analyze sales trends across `Zones`, `Occupations`, and `Product_Categories`.

3. **Visualization**:
   - Generate insightful visualizations using bar charts, pie charts, and heatmaps.
   - Showcase trends in sales performance across regions and demographics.

4. **Insights Extraction**:
   - Identify high-performing states, zones, and product categories.
   - Understand purchasing behavior by age group, gender, and marital status.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries Used**:
  - `pandas` and `numpy` for data manipulation
  - `matplotlib` and `seaborn` for visualization

## Deliverables

1. **Key Insights**:
   - Demographic segments contributing the most to sales.
   - Trends in product preferences and geographic sales distribution.
   - Recommendations for marketing and inventory strategies during Diwali.

2. **Visual Dashboard**:
   - A visually appealing summary showcasing:
     - Sales distribution by demographic groups.
     - Top-performing states and zones.
     - Popular product categories and their revenue contributions.

3. **Professional Report**:
   - A detailed report summarizing the analysis, key findings, and actionable recommendations.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diwali-sales-analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd diwali-sales-analysis
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Diwali_Sales_Analysis.ipynb
   ```

4. Run the notebook cells sequentially to execute the analysis.

## Future Enhancements

- Integrate predictive modeling to forecast sales trends for upcoming Diwali seasons.
- Automate dashboard generation for real-time sales monitoring.
- Expand the analysis to include comparative studies across multiple festive seasons.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For queries or collaboration opportunities, please reach out at [padmachbehera23@example.com](mailto:your.email@example.com).

