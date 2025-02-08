# Descriptive and prescriptive analysis for Data mart

## Project background


Data mart is Danny’s latest venture that runs international operations for his online supermarket that specializes in fresh products.

In June 2020 - large-scale supply changes were made at the Data mart. All Data mart products now use sustainable packaging methods in every single step, starting from farm to customer. Danny needs your help to quantify the impact of this change on the sales performance of Data mart and its separate business areas.

The analysis produces insights and recommendations in the following areas:


- Before & after analysis: Provide metrics for the impact on sales performance before/after the introduction of sustainable packaging methods. The results cover the impact at a global level and different business areas.


The data was synthetically generated [here](https://8weeksqlchallenge.com/case-study-5/).  


## Data structure and initial checks

The provided dataset has 17,117 observations, each representing the sales for every region at a weekly level. It contains 7 columns that includes data about:

| Column        | Purpose                                                  |
|---------------|----------------------------------------------------------|
| week_date     | Date of the week for which the data is recorded         |
| region        | Geographical region where the transactions occurred      |
| platform      | Platform used for the transactions (e.g., Retail, Shopify) |
| segment       | Segment of customers or products                         |
| customer_type | Type of customer (e.g., New, Existing, Guest)            |
| transactions  | Number of transactions made                               |
| sales         | Total sales value|

