# Indian Startup Funding Analysis (2018-2021)

## Overview

This project analyzes funding trends, patterns, and insights for Indian startups between 2018 and 2021. The analysis covers various aspects such as funding amounts, sectoral preferences, investment stages, key investors, and geographical distribution. The data is sourced from multiple platforms and undergoes thorough cleaning and processing to ensure accuracy and reliability.

## Table of Contents

- [Overview](#overview)
- [Data Sources](#data-sources)
- [Data Preparation and Cleaning](#data-preparation-and-cleaning)
- [Hypothesis Testing](#hypothesis-testing)
- [Analytical Questions](#analytical-questions)
  - [Trends and Patterns in Funding Amounts](#trends-and-patterns-in-funding-amounts)
  - [Sectoral Preferences Over Time](#sectoral-preferences-over-time)
  - [Funding Distribution Across Startup Stages](#funding-distribution-across-startup-stages)
  - [Key Investors and Their Investment Patterns](#key-investors-and-their-investment-patterns)
  - [Geographical Distribution of Startup Funding](#geographical-distribution-of-startup-funding)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Resource Links](#resource-links)

## Data Sources

The data for this analysis was collected from the following sources:
1. **SQL Server**: Contains 2020 and 2021 datasets.
2. **GitHub Repository**: Contains 2018 dataset.
3. **OneDrive Link**: Contains 2019 dataset.

## Data Preparation and Cleaning

The data was consolidated and cleaned using the following techniques:
- **Handling Missing Values**: Missing values were filled with mean or median values, or rows with significant gaps were removed.
- **Data Normalization**: Funding amounts were converted into a common currency for consistency.
- **Removing Duplicates**: Duplicate entries were identified and removed.
- **Categorical Data Standardization**: Categories such as industry names and investor names were standardized.

## Hypothesis Testing

Before analysis, hypothesis testing was conducted to validate data integrity and identify significant patterns:
- **ANOVA (Analysis of Variance)**: Used to determine if there were significant differences in funding amounts across different sectors and years.

## Analytical Questions

### Trends and Patterns in Funding Amounts

This analysis examines annual and quarterly trends in funding amounts to identify growth trajectories and patterns, including any peaks, dips, or consistent growth periods.

### Sectoral Preferences Over Time

This section identifies which industries received the most funding and how sectoral preferences evolved from 2018 to 2021.

### Funding Distribution Across Startup Stages

An analysis of funding amounts at different startup stages (e.g., Seed, Series A) to understand investment appetites and risk preferences of investors.

### Key Investors and Their Investment Patterns

This section identifies the most active investors and analyzes their investment portfolios and patterns to reveal strategic preferences and alliances.

### Geographical Distribution of Startup Funding

This analysis explores the geographical distribution of startup funding within India and how it changed over the years, highlighting regional hotspots and shifts in focus.

## Visualizations

The project includes various visualizations to illustrate the findings:
- Bar charts showing top investors and their funding patterns.
- Bar charts representing sectoral preferences and funding stages.
- Line graphs depicting trends in funding amounts over time.

## Dashboard

Here is a visualization of the analysis:

![Dashboard](https://raw.githubusercontent.com/briansiaw5/Analysis-of-Indian-Startup-Funding/main/Dashboard.png)


## Conclusion

The analysis reveals a dynamic and evolving Indian startup ecosystem, with significant insights into sectoral trends, investment stages, key investors, and geographical distribution. These findings can inform entrepreneurs, investors, and policymakers about the current state and future direction of the startup landscape in India.

## Usage

To run the analysis and generate visualizations, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/briansiaw5/Analysis-of-Indian-Startup-Funding.git
    cd Indian-Startup-Funding
    ```

2. **Install Dependencies**:
    Ensure you have Python and the necessary libraries installed and would need access to login credentials to access the SQL database. You can install the required libraries using:
    ```bash
    pip install pyodbc
    pip install python-dotenv
    ```

3. **Load Data**:
    Load the data from the specified sources (SQL Server, GitHub, OneDrive).

4. **Run the Analysis**:
    Execute the analysis scripts to generate insights and visualizations.

## Contributing

This work itself was a team effort from Team Namibia from the Azubi Africa Cohort 7. As such we very much welcome contributions from anyone interested. If you have suggestions or improvements, please open an issue or submit a pull request. Ensure your contributions align with the project's goals and maintain high-quality standards.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Resource Links

Below are links to access my published article on LinkedIn as well as my PowerBI dashboard. Also the links to the OneDrive and Github repository are also listed below:

| Source           | Link                                                                                      |
|------------------|-------------------------------------------------------------------------------------------|
| **LinkedIn**     | [LinkedIn Link](https://www.linkedin.com/posts/brian-siaw_my-article-analyzing-the-funding-of-startups-activity-7205670977886679040-O0v5?utm_source=share&utm_medium=member_desktop)                                                                                          |
| **PowerBI**      | [PowerBI Link](https://app.powerbi.com/groups/me/reports/539164b4-9b08-4401-bf3e-869619fd38a9?ctid=4487b52f-f118-4830-b49d-3c298cb71075&amp;pbi_source=linkShare)  |
| **OneDrive**     | [OneDrive Link](https://azubiafrica-my.sharepoint.com/personal/teachops_azubiafrica_org/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fteachops%5Fazubiafrica%5Forg%2FDocuments%2FCareer%20Accelerator%20Data%5FSets%2FLP1%20Datasets&ga=1)  |
| **Github**       | [Github Link](https://github.com/Azubi-Africa/Career_Accelerator_LP1-Data_Analysis)                                            |

