### Project Description

This capstone project comprises two distinct tasks. Ensure to submit your solutions to homework@dsa.az by February 05, 23:59.

### Task 1: Performance Analysis

In this phase, you are tasked with applying your Tableau skills to showcase your ability to choose the right types of charts and create user-friendly dashboards. Incorporate all the concepts covered during the boot camp to keep the dashboards concise.

**Submission Deliverables (PerformanceAnalysis.zip):**
1. One Tableau desktop file (twb) containing two dashboards only.
2. A text document with answers to the provided questions.

### Task 2: Voice Revenue Analysis

This part evaluates your approach to specific business problems and your ability to communicate analytics results. You have the freedom to design your own dashboard using various visualization techniques.

**Submission Deliverables (VoiceDeclinersproblem.zip):**
1. One Tableau desktop file (twb) with two dashboards.

### Performance Analysis

#### Introduction

As a data analyst in a Telecom Company, your role involves handling ad-hoc requests from marketing and CRM departments regarding tariff performance for different KPIs over various time periods. The goal is to create dynamic dashboards conveying all required insights.

Think strategically about the best ways to visualize each request, keeping in mind the need for optimal charts. Apply design elements such as color, labels, titles, tooltips, sorting, filters, parameters, etc., to enhance the user-friendliness of the dashboards.

#### Data

You have an Excel workbook containing daily revenues and the number of subscribers for different tariffs. Data manipulation methods like joining different sheets and simple calculations may be required for analysis.

**Consideration:**
- For each row (each day and tariff):
  - Average Revenue Per Subscriber = Total Revenue / Number of Subscribers
  - Average Voice Revenue Per Subscriber = Total Voice Revenue / Number of Voice Subscribers
  - Average Data Revenue Per Subscriber = Total Data Revenue / Number of Data Subscribers
  - Average On-net Revenue Per Subscriber = Total On-net Revenue / Number of On-net Subscribers
  - Average Off-net Revenue Per Subscriber = Total Off-net Revenue / Number of Off-net Subscribers

#### Weekly KPI Performance Analysis

**KPI List:** Total Revenue, Minutes of Usage, On-net Minutes of Usage, Off-net Minutes of Usage, MB of usage

1. Use KPI list as a parameter.
2. Create a weekly time plot for each KPI.
3. List the top 5 tariffs for each KPI in the last week and their growth rate.
4. Analyze the performance of each KPI in the last week.
5. Evaluate the KPI growth in the last week and provide alerts based on positive or negative trends.

#### Daily Revenue Performance Analysis

1. Analyze total revenue.
2. Visualize the revenue proportion of each tariff.
3. Compare tariffs on a daily basis for:
   - Average revenue per subscriber
   - Average voice revenue per subscriber
   - Average data revenue per subscriber
   - Average on-net revenue per subscriber
   - Average off-net revenue per subscriber
4. Visualize the cluster of tariffs for voice and data revenue. Add a daily timeline of voice and data revenue as a tooltip.
5. Determine the portion of data revenue in the total revenue for each tariff.

**After creating the dashboard, answer the following questions:**
1. Which tariff has the highest revenue in January 2020?
2. Which tariff has the highest data revenue growth in the last month?
3. For which tariff is data revenue higher than other types of revenue?

### Voice Revenue Analysis

#### Introduction

The Board of Directors observes a consistent decline in total voice duration and suspects various reasons. With limited data, determining significant predictors of the decline is challenging. Your task is to provide valuable insights using available data.

Focus on describing people experiencing a decline in voice duration and identify factors related to the decline.

#### Data

You are provided with an Excel workbook containing 4 months of usage history for anonymized subscribers on different tariffs. Data manipulation methods may be needed for analysis.

#### Subscribers Profile Analysis

Build a dashboard to analyze the following questions:

1. Did voice duration decrease more for subscribers:
   a. With higher MB of usage?
   b. With higher revenue?
   c. With higher minutes of usage?

2. Did voice duration decrease for all top 10 tariffs with the highest voice revenue?

3. Which tariff's voice duration decreased the most?

4. Did tariff 5 subscribers' voice duration decrease more for those with higher MB of usage?

5. Were the answers to the above questions the same when analyzed for subscribers whose voice duration decreased more than 50%?
### Author
Ilaha Musayeva
