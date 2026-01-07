# Aircraft Risk Analysis for Strategic Investment

## Overview
This project analyzes historical aviation accident data to support data-driven decision-making for a company entering the aviation industry. The objective is to identify aircraft characteristics associated with lower operational risk and translate these findings into actionable recommendations for aircraft acquisition and operational planning.

Using data cleaning, aggregation, and visualization techniques, the project transforms complex accident records into clear insights that help business stakeholders minimize safety risks, operational costs, and long-term exposure as the company diversifies into aviation.


## Business Understanding


### Business Problem
The company plans to purchase and operate aircraft for commercial and private use but lacks prior experience in aviation risk assessment. Poor aircraft selection could lead to increased accident risk, higher insurance premiums and operational disruptions.

### Key Business Question
- What data-driven strategies can reduce risk when entering the aviation market?


## Data Understanding and Analysis

### Data Understanding

The dataset is sourced from the National Transportation Safety Board (NTSB) and contains detailed records of civil aviation accidents and incidents spanning multiple decades. It includes a broad range of variables describing aircraft characteristics, operational conditions, environmental factors, injury outcomes, and accident investigation details.

Given the business objective of assessing aircraft-related risk, the analysis emphasizes understanding overall safety patterns rather than examining every available variable. The richness of the dataset allows for aggregation and comparison across different aircraft and operating conditions, supporting insights that are relevant to strategic decision-making in aviation.

### Analytical Approach
- Cleaned and standardized raw data to ensure reliability
- Handled missing values to reduce bias
- Aggregated accident records by aircraft and operational characteristics
- Calculated average accident severity to compare relative risk
- Used clear visualizations to communicate insights to non-technical stakeholders

### Key Visualizations
1. **Average Accident Severity by Aircraft Make**  
   Identifies manufacturers associated with lower historical risk.
   <img width="695" height="539" alt="image" src="https://github.com/user-attachments/assets/a61562b5-de83-4a9b-98f7-f47b4eb8b7e4" />


3. **Average Accident Severity by Engine Type**  
   Highlights engine configurations linked to safer outcomes.
   <img width="696" height="535" alt="image" src="https://github.com/user-attachments/assets/96ac6886-8256-4117-bf33-79857b288153" />


5. **Average Accident Severity by Weather Condition**  
   Demonstrates the impact of weather conditions on aviation risk.
   <img width="696" height="514" alt="image" src="https://github.com/user-attachments/assets/6ac16918-7ed9-4b63-b329-d7447f9241cf" />


These same visualizations appear in the final notebook and presentation.

---
## Interactive Dashboard
An interactive Tableau dashboard is created to allow stakeholders to explore aviation risk patterns dynamically by aircraft characteristics and operating conditions.

View the interactive Tableau dashboard here:  
Tableau Public Dashboard Link: https://public.tableau.com/views/tableauvisualizationphase1project/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Recommendations

### Prioritize Aircraft Manufacturers with Lower Historical Severity
Analysis shows that manufacturers like Grumman-Schweizer and AVIATEK have lower average accident severity compared to Aviat and Waco. Therefore, the company should prioritize acquiring aircraft from manufacturers with historically safer outcomes, which can reduce operational disruptions, lower insurance costs, and enhance overall safety.

### Select Engine Types with Lower Accident Severity
Analysis indicates that single-engine piston aircraft consistently show lower accident severity compared to more complex engine types. Therefore, the company should focus on simpler, historically safer engine types, which can minimize mechanical complexity, lower maintenance costs, and reduce the risk of severe accidents while building operational experience.

### Implement Weather-Based Operational Policies
Analysis shows that accidents occurring in IMC or adverse/unknown weather conditions have substantially higher severity than those in VMC. Therefore, the company should enforce policies that limit flights in poor weather, supported by enhanced monitoring, conservative go/no-go rules, and pilot training focused on weather risk management, reducing environmental risk and improving safety.

## Conclusion
Aviation risk varies across aircraft manufacturers, engine types, and operating conditions. By selecting manufacturers and engine types with lower historical severity and implementing strict weather-based operational policies, the company can reduce accident severity, control costs, and ensure safer, more reliable operations. These recommendations provide a clear, data-driven strategy for effective entry into the aviation market.


---



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



