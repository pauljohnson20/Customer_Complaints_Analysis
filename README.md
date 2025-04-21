# Customer_Complaints

### Table of Contents:
- [Project Overview](#project-overview)
- [Business Objective](#business-objective)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Understanding](#data-understanding)
- [KPIs](#kpis)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis (Tableau Visuals)](#data-analysis-tableau-visuals)
- [Project Insights](#project-insights)
- [Recommendations](#recommendations)
- [How to Use This Report](#how-to-use-this-report)
- [Contact](#contact)

### Project Overview:
This project analyzes customer complaints related to banking services across the U.S. The dashboard provides key metrics and visual trends. The goal is to uncover insights to improve customer satisfaction.

### Business Objective:
Banks and financial institutions receive thousands of complaints annually. Understanding the nature, source, and frequency of these complaints can help reduce dissatisfaction and improve service quality. This analysis helps identify trends and areas for improvement.

### Data Source:
  - Source: CSV file [Download Here](https://github.com/user-attachments/files/19835801/complaints_Full.Data.csv)
  - Contains real-world customer complaint records related to various banking products and services.

### Tools Used:
  - Excel (for cleaning and preprocessing)
  - Tableau (for building interactive visualizations and dashboards)

### Data Understanding:
  - Total Records: 75,513
  - Total Columns: 21
  - Key columns include: Date received, Product, Sub-product, Issue, Company, State, Response type, Timely response, Consumer consent, Submitted via, etc.

### KPIs:
  1. Total number of complaints
  2. Number of complaints by Product Group
  3. Complaint trends over the years
  4. Percentage change by year
  5. Complaints by state
  6. Complaints by submission method
  7. Timely vs untimely responses
  8. Interactive dashboard [View Dashboard](https://github.com/user-attachments/assets/43ec0ea3-8f37-425c-b55d-17dc20956b13)

### Data Cleaning:
  - Performed in Excel:
      - Converted date columns to proper format
      - Handled missing/null values
      - Filtered irrelevant records
  - Grouped related products in Tableau to create a new field named 'Product Group', which was later used as a filter in the dashboard.

### Exploratory Data Analysis:
  - Reviewed distributions of complaint types
  - Analyzed complaint counts by state and submission method
  - Checked yearly trends and outliers
  - Analyzed the effectiveness of company responses across different product types, focusing on timely and appropriate resolutions.

### Data Analysis (Tableau Visuals):
  - KPI Cards → Total complaints and breakdown by Product Group
  - Bar Chart → Product Group over years with percentage variation
  - Map View → State-wise number of complaints
  - Bar Chart → Request type (Web, Referral, Phone, Mail, Fax, Email)
  - Line Chart (Yearly Trend) → Trends by Product Group

Snap of Customer Complaint Dashboard

![Image](https://github.com/user-attachments/assets/43ec0ea3-8f37-425c-b55d-17dc20956b13)

### Project Insights:
  - Most complaints were related to Credit Cards and Mortgage services, accounting for over 40% of total complaints.
  - Web and Referral were the most common channels for submitting complaints, contributing to more than 80% of total submissions.
  - There was a 30% increase in complaints in 2018 compared to the previous year, indicating a spike in customer dissatisfaction during that period.
  - A few states—California, Texas, Florida, and New York—alone account for over 40% of total complaints, highlighting potential service or communication gaps in these regions.

### Recommendations:
  - **Enhance Support for High-Complaint Products:** Focus on improving customer experience for Credit Card and Mortgage services, as they contribute to a large portion of complaints.
  - **Optimize Web and Referral Channels:** Since over 80% of complaints are submitted via Web and Referral, prioritize making these channels more user-friendly, responsive, and efficient.
  - **Investigate 2018 Complaint Spike:** Conduct a detailed review of 2018 operations and customer feedback to understand the root cause behind the 30% increase in complaints.
  - **Target High-Volume States with Proactive Support:** Allocate more resources and training in California, Texas, Florida, and New York to address customer concerns proactively and reduce complaint volume.
  - **Monitor Complaint Trends Regularly:** Set up monthly or quarterly tracking of complaints by product, state, and channel to detect early signs of service issues and take timely action.

### How to Use This Report:
  - Use the 'Product Group' Filter: Select specific product categories to analyze complaints by service type.
  - Hover for Details: Hover over any chart, map, or line to view detailed tooltips with exact numbers and percentages.
  - Explore Yearly Trends: Use the line chart to track complaint trends over the years and identify spikes.
  - Analyze Complaints by State: Refer to the map view to see which states report the most complaints and compare regional patterns.
  - Understand Submission Patterns: Check the bar chart for request types to find out how customers most commonly submit their complaints.

### Contact:
For further information or inquiries regarding this project, feel free to reach out:
  - Email     : pauljohnson2094@gmail.com
  - LinkedIn  : www.linkedin.com/in/pauljohnson2094
  - GitHub    : https://github.com/pauljohnson20
