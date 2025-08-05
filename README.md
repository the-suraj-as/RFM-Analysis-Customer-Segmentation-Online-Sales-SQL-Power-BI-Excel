# Customer Segmentation(RFM Analysis) of Online Sales data using SQL, Excel and PowerBI

## Table of content
- [Project Overview](#Project-Overview)
- [Data Set](#Data-Set)
- [Tech Stack](#Tech-Stack)
- [Highlights](#Highlights)
- [Walkthrough Visuals with Insights](#Walkthrough-Visuals-with-Insights)
- [Business Insights](#Business-Insights)
- [Dashboard Preview](#Dashboard-Preview)

## Project Overview
The RFM Segmentation Dashboard is a data-driven solution designed to classify customers based on their Recency, Frequency, and Monetary purchase behavior. By uncovering patterns in customer activity and value, the dashboard enables businesses to understand loyalty, engagement levels, and revenue contribution.  Identified key segments such as Champions, Loyal, and At-Risk customers, with tailored marketing actions suggested for each, enabling strategic decision-making in retention and reactivation. <br> <br>

## Data Set
**Online sales transactional data.**

- Total Customers: 18,484  
- Total Sales: $29.36M  

- Customer details including:
  - Demographics (Age, Gender, Marital Status)
  - Location (Country, City)
  - Purchase History (Sales Amount, Purchase Frequency, Last Purchase Date)

- Data transformed into:
  - RFM scores for each customer
  - RFM-based customer segments (Example: Champions, Loyal, At Risk, New Customers) <br> <br>

## Tech Stack
**The dashboard was built using the following tools and technologies:**

- SQL - Used to pull and aggregate customer-level data from relational tables
- Excel - Used for generate customer segments based on RFM Score.
- Power Query - Used for data cleaning and transformations  
- Power BI Desktop - Primary platform used to design the report and dashboard  
- DAX – Created calculated measures and customer segmentation logic.
- Data Modeling - Structured relationships between the data tables 
- File Format - `.pbix` for development and `.png` for static previews <br> <br>

## Highlights

### • Business Problem

Retail businesses often lack a clear understanding of customer behavior and engagement levels. Without segmentation, marketing efforts are generalized and inefficient, leading to missed revenue opportunities and poor retention.

### • Goal of the Dashboard

To deliver a business-friendly dashboard that:

- Categorizes customers based on Recency, Frequency, and Monetary behavior  
- Enables marketing teams to personalize outreach and promotions  
- Helps decision-makers prioritize high-value and at-risk customer groups  
- Supports campaign planning based on segment-level insights  <br> <br>

## Walkthrough Visuals with Insights

- **Demographic Customer Overview:**  
  - Total Sales: $29.36M  
  - Total Customers: 18,484  
  - Balanced Sales by Gender & Marital Status: Sales are nearly evenly split by gender (Male 50.46%, Female 49.54%) and marital status (Single 51.73%, Married 48.27%), indicating that marketing should emphasize inclusivity.
  - Age Group Opportunity: The 65-74 and 55-64 age groups contribute the most sales ($7.7M and $11.4M). Efforts to deepen engagement in these age brackets, such as age-relevant offers and targeted messaging, could further boost revenue. Conversely, the 85-94 demographic contributes the least ($0.7M), suggesting limited potential there.
  - Geographical Focus: United States, Australia and UK lead in sales. These should remain primary target regions. Other European countries (France, Germany) aswell are the significant contributors.  

- **No Of Customers By Segment**
  - Largest segments: "New Customers" (3,200) and "Promising" (2,600) dominate in count, indicating ongoing acquisition, but their monetary value is low.

  - Potential focus: Although "Champions," "Loyal," and "Cannot Lose Them" have fewer customers than the acquisition segments, they deliver higher business value. Prioritize moving new and promising customers up the value ladder.

- **Total Sales By Segment**
  - Top revenue drivers: "Champions" ($8.3M), "At Risk" ($7.3M), "Loyal" ($6.2M), and "Cannot Lose Them" ($3.9M) contribute most of the sales.

  - Churn risk: "At Risk" and "Cannot Lose Them" segments, though valuable, are at risk of disengagement. Immediate retention actions are needed to avoid losing significant sales.

- **Recency Value By Segment**
  - Recent activity: "New Customers" and "Promising" segments show the highest recency, consistent with recent acquisition strategies.

  - Monitor disengagement: Low recency values in "About To Sleep," "Hibernating Customers," and "Lost Customers" signal the need for re-activation campaigns.

- **Frequency Value By Segment**
  - Best repeat business: "Champions" and "Loyal" have the highest frequency of engagement. These are ideal candidates for targeted loyalty rewards and referral programs.

  - Low engagement: "Need Attention," "About To Sleep," and "Hibernating Customers" shows low purchase frequency, personalization campaigns are advised.

- **Monetary Value By Segment**
  - Highest spenders: "Champions," "Loyal," "Cannot Lose Them," and "At Risk" are the segments with the highest average value per customer.

  - Low monetary value: "New Customers," "Potential Loyalist," and "Need Attention" segments with the the least spending customer.

- **Customer Details Table:**  
  - Full view of customers with Age, Gender, Country, Contact Details, Total Sales, and Assigned Segment  
  - Useful for individual-level targeting.

- **RFM Segment Description Table:**
  - RFM Description
  - Marketing actions recommended for each segment <br> <br>

## Business Insights

The business’s highest revenue comes from the “Champions,” “Loyal,” “At Risk,” and “Cannot Lose Them” segments, which require focused retention and personalized engagement to safeguard sales. New and promising customers show strong acquisition but need nurturing to increase their value. Disengaged groups like “Hibernating” and “Lost Customers” should be targeted with reactivation campaigns. Demographically, sales are balanced by gender and marital status, with the 55–74 age range driving most revenue. Key markets include the US, Australia, and the UK. Tailored marketing by segment and demographics will maximize growth and retention.  

### Dashboard Preview
![]
