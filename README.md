# Aircraft Risk Analysis for Strategic Investment

## Overview
This project analyzes historical aviation accident data to support data-driven decision-making for a company entering the aviation industry. The objective is to identify aircraft characteristics associated with lower operational risk and translate these findings into actionable recommendations for aircraft acquisition and operational planning.

Using data cleaning, aggregation, and visualization techniques, the project transforms complex accident records into clear insights that help business stakeholders minimize safety risks, operational costs, and long-term exposure as the company diversifies into aviation.

---

## Business Understanding


### Business Problem
The company plans to purchase and operate aircraft for commercial and private use but lacks prior experience in aviation risk assessment. Poor aircraft selection could lead to increased accident risk, higher insurance premiums, operational disruptions, and reputational damage.

### Key Business Question
- What data-driven strategies can reduce risk when entering the aviation market?

---

## Data Understanding and Analysis

### Data Source
- National Transportation Safety Board (NTSB)
- Civil aviation accident and incident data
- Coverage: United States and international waters
- Time period: 1962–2023

### Data Description
The dataset includes information on:
- Aircraft make and model
- Engine type
- Weather conditions at the time of accidents
- Accident severity outcomes

### Analytical Approach
- Cleaned and standardized raw data to ensure reliability
- Handled missing values to reduce bias
- Aggregated accident records by aircraft and operational characteristics
- Calculated average accident severity to compare relative risk
- Used clear visualizations to communicate insights to non-technical stakeholders

### Key Visualizations
1. **Average Accident Severity by Aircraft Make**  
   Identifies manufacturers associated with lower historical risk.

2. **Average Accident Severity by Engine Type**  
   Highlights engine configurations linked to safer outcomes.

3. **Average Accident Severity by Weather Condition**  
   Demonstrates the impact of environmental factors on aviation risk.

These same visualizations appear in the final notebook and presentation.

---

## Conclusion

The analysis reveals that aviation risk varies significantly across aircraft manufacturers, engine types, and operating conditions. Certain aircraft makes and engine configurations consistently show lower accident severity, indicating stronger safety performance over time. Additionally, adverse weather conditions substantially increase accident severity, underscoring the need for operational risk controls alongside aircraft selection.

Based on these findings, three core recommendations emerge:
1. Prioritize aircraft manufacturers with historically lower severity outcomes.
2. Select engine types associated with reduced accident severity.
3. Implement weather-based operational policies to mitigate environmental risk.

Together, these insights provide a strong foundation for safer, more cost-effective entry into the aviation industry.

---

## Repository Structure
├── data/
│ └── aviation_data.csv
├── notebooks/
│ └── student.ipynb
├── presentation/
│ └── presentation.pdf
├── .gitignore
└── README.md


---

## How to Use This Repository
1. Review the **student.ipynb** for the complete analysis.
2. View the **presentation PDF** for a business-focused summary of findings.
3. Explore visualizations and insights used to support recommendations.



---

## Technologies Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---



