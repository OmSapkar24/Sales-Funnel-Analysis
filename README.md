# **Sales Funnel Analysis**

This project focuses on analyzing the stages of a sales funnel, identifying key metrics, and visualizing conversion rates to derive actionable insights. The dataset contains synthetic sales funnel data, providing detailed information about customer behavior, revenue potential, and other crucial metrics.

---

## **Project Overview**
The primary goal of this project is to:
- **Understand Conversion Rates**: Analyze the number of leads at each stage of the funnel.
- **Revenue Potential**: Evaluate the revenue potential across different customer segments.
- **Engagement Impact**: Study the effect of engagement scores, discounts, and marketing spend on conversions.
- **Visualize Key Metrics**: Generate insightful visualizations for easier decision-making.

---

## **Features of the Dataset**
The dataset includes the following columns:
1. **Lead_ID**: Unique identifier for each lead.
2. **Customer_Name**: Anonymized customer names.
3. **Age**: Age of the lead.
4. **Gender**: Gender of the lead (Male, Female, Other, Prefer Not to Say).
5. **Region**: The geographic region of the lead (North, South, East, West, Central).
6. **Industry**: The industry associated with the lead (e.g., Retail, Finance, Technology).
7. **Revenue_Potential**: The potential revenue associated with each lead.
8. **Lead_Source**: How the lead was generated (Email, Social Media, Website, etc.).
9. **Stage**: Current stage of the lead in the sales funnel (e.g., Awareness, Interest, Purchase).
10. **Time_Spent_in_Stage_Days**: Time (in days) spent by the lead in the current stage.
11. **Engagement_Score**: A score representing lead engagement (0-100).
12. **Converted**: Whether the lead converted (1 for yes, 0 for no).
13. **Preferred_Contact_Method**: The preferred contact method of the lead (e.g., Email, Phone).
14. **Competitor_Consideration**: Whether the lead considered competitors (1 for yes, 0 for no).
15. **Marketing_Spend**: Marketing spend associated with the lead.
16. **Discount_Offered**: Discounts offered to the lead.
17. **Customer_Feedback**: Feedback from the customer (Positive, Neutral, Negative, No Feedback).

---

## **Analysis and Visualizations**
The notebook includes the following key analyses and visualizations:
1. **Funnel Conversion Analysis**: 
   - Bar chart for leads at each funnel stage.
   - Line chart for conversion rates across stages.

2. **Revenue Potential**:
   - Distribution histogram of potential revenue.

3. **Correlation Analysis**:
   - Heatmap to understand relationships between numerical fields.

4. **Advanced Analysis**:
   - Impact of discounts and engagement scores on conversions.
   - Comparison of competitor consideration rates.

---

## **Steps to Run the Notebook**
1. Install the required libraries:

   pip install pandas numpy matplotlib seaborn

Load the notebook in Jupyter Notebook or JupyterLab.
Execute the cells step by step to:
Load the dataset.
Perform exploratory data analysis.
Visualize the data.
Save insights and reports.
