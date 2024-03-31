# HR-Analysis-Dashboard (Attrition Analysis)
This is a HR Analysis Dashboard which is developed to Analyse Employee Attrition based on various factors. 

### Dashboard Link :https://app.powerbi.com/reportEmbed?reportId=26ae390b-6597-4237-93ab-60acb0fbaeb7&autoAuth=true&ctid=23772a0d-1985-4134-98bb-31e340786ca1

## Problem Statement

High employee turnover can negatively impact an organization's productivity, morale, and customer satisfaction. This Dashboard makes it easy to identify trends, understand the root causes of employee departures, and develop targeted interventions to reduce turnover.

### Steps followed 

### 1. Gather Your Data:

Identify sources: Look for employee info in your HRIS, payroll system, or surveys. This might include:
- Demographics (age, department, location)
- Job titles and positions
- Hire and exit dates
- Performance data
- Training records
- Compensation and benefits details
 Import the data: Use a Business Intelligence (BI) tool like Power BI, Tableau, or Qlik Sense. The data format can be CSV, Excel, or directly connected to databases.

### 2. Clean Up Your Data:

- Check for errors: Look for typos, duplicates, or formatting issues in your imported data.
- Cleanse the data: Fix typos, remove duplicates, and ensure consistent formatting (e.g., date format).
- Transform the data (if needed): Create new fields (e.g., tenure length), group data (e.g., age ranges), or combine data sets from different sources.
### 3. Visualize Your Insights:

* Pick key metrics: Decide what you want to track, like: Turnover rate by department or tenure
- Time to fill open positions
- Cost per hire
- Reasons for employee departure
- Employee satisfaction ratings
* Design visualizations: Create informative charts and graphs to - represent these metrics. Consider using a variety of visuals:
- Bar charts for comparisons (e.g., turnover rate by department)
- Line charts for trends over time (e.g., changes in employee satisfaction)
- Pie charts for breakdowns (e.g., reasons for leaving)
- Maps for location-based data (e.g., high-turnover teams)
- Cards for displaying key performance indicators (KPIs)

### 4. Make it Interactive:

- Add slicers and filters: Allow users to focus on specific areas by filtering data (e.g., department, job title, hire date).
- Enable drill-down functionality: Let users explore details behind data points. For example, clicking a department with high turnover could reveal reasons for leaving in that department.
- Include tooltips: Provide informative pop-ups that appear on hover, offering additional details about data points within the visualizations.
### 5. Share Your Dashboard:

- Publish the dashboard: Make your completed HR Analysis Dashboard accessible to authorized users within your BI tool.
- Schedule updates: Set up automatic data refreshes to ensure the dashboard reflects the latest HR data.


# Example Dashboard Elements

### 1. Employee Turnover:

Metric: Track overall employee turnover rate over time (e.g., monthly, quarterly, yearly).
Visualization: Line chart or area chart to visualize trends in turnover rate. This can reveal seasonal variations or identify periods of significant changes.
### 2. Department Analysis:

Metric: Show turnover rate by department using a bar chart.
Comparison: Optionally, include a line representing the overall company turnover rate for comparison.
Drill-Down: Allow users to click on a specific department to see details on reasons for leaving within that department.
### 3. Tenure Analysis:

Metric: Analyze turnover rate by employee tenure (e.g., 0-6 months, 6-12 months, etc.) using a bar chart or histogram.
Insight: This can identify if new hires or experienced employees are more likely to leave.
### 4. Exit Reasons:

Metric: Show the distribution of reasons for employee departure using a pie chart or donut chart.
Possible Reasons: Categories might include compensation, career advancement, work-life balance, dissatisfaction with management, etc.
### 5. Cost of Turnover:

Metric: Calculate and display the estimated cost of employee turnover using a card or KPI tile. This could include factors like recruitment costs, lost productivity, and training expenses.
### 6. Time to Fill:

Metric: Track the average time it takes to fill open positions using a gauge chart or KPI tile.
Target: Optionally, set a target time-to-fill metric for comparison.

### 7. Employee Engagement:

Metric: Include a gauge chart or satisfaction rating scale to represent employee engagement levels. This data might come from employee surveys.


### Insights that dashboard provides

  (a) Count of total Employee

  (b) Calulation of total Attrition
  
  (c) Calulation of Attrition rate
  
  (d) Calulation of average age of attritted employee
  
  (e) Calulation of average salary of attritted employee

# Additional Considerations

- Time in Role: Create a calculated column to show the duration an employee has been in their current role. This can be helpful in analyzing if recent hires or long-term employees are more likely to leave.

- Performance & Turnover: Define a measure to calculate the average performance rating for employees who left within a specific timeframe (e.g., past 6 months). This can reveal potential connections between performance and turnover.

- Departmental Cost per Hire: Create a measure to calculate the average cost of hiring new employees for each department. This can help identify areas for potential cost optimization in the recruitment process.

- Department Turnover: Clicking on a department with high turnover in a bar chart could drill down to reveal details on: Demographics of departing employees (age, experience level) Specific reasons for leaving within that department Performance data of departed employees compared to those who stayed

- Exit Reasons: Clicking on a specific reason for leaving in a pie chart could drill down to show:Departments where that reason is most prevalent Job titles associated with that reason Tenure length of employees who left for that reason

# Benefits of Using This Dashboard

- Gain valuable insights into sales performance, customer behavior, and product trends.
- Identify areas for improvement and make data-driven decisions to optimize your e-commerce business.
- Track progress over time and measure the effectiveness of marketing campaigns.
- Improve customer satisfaction and loyalty by addressing their needs and preferences.

        
A card visual was used to represent the Attrition rate.

![Screenshot 2024-03-31 213336](https://github.com/harshsinghrajput7/HR-Analysis-Dashboard/assets/106376866/8cc89fc7-b889-4ac8-abf9-4163b2132952)


 A card visual was used to represent the Sum of Profit.
 
 Snap of employee Count.

![Screenshot 2024-03-31 213459](https://github.com/harshsinghrajput7/HR-Analysis-Dashboard/assets/106376866/578a26e2-dbb1-4702-bb7c-42cbc2663d17)

 
# publishing
 
![Screenshot 2024-03-31 140200](https://github.com/harshsinghrajput7/HR-Analysis-Dashboard/assets/106376866/5c8c2731-96b5-495e-9f90-1a7b04c4706b)




 # Report Snapshot (Power BI DESKTOP)

![Screenshot 2024-03-31 140637](https://github.com/harshsinghrajput7/HR-Analysis-Dashboard/assets/106376866/4b004bc2-c4f9-4a11-befe-c2f3675c5ee6)


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of employee = 1470

   Total Attrition = 237

   Attrition rate = 16.1% 

 ### [4] Some other insights
 
 ### Attrition with respect to education field

- life sciences 
        
        37.6% thus,life sciences is having maximum Attrition.

- Medical

        14.8%

- other

        4.6%  thus,other is having minimum Attrition.
 
