# Ticket Sales Analysis
### Project Overview
This project analyzes ticket sales transaction of a transportation company. The company sells its tickets and collects revenue through four banks. It analyzes revenue generated across 10 branches, with banking partnerships led by Gtbank. The company processed 5,000 transactions with an average ticket price of $6,510. Each branch contributes fairly evenly to the revenue, with minimal variation in their individual performance and transaction volumes.


![transportation dashboard](https://github.com/user-attachments/assets/78e07f5b-7238-4c34-9c61-01cfb41e6e5e)

### Data Sources
Ticket Sales Data: The main dataset utilized for this analysis is the 'Ticket Sales Data.csv' file, which includes comprehensive records of every sale conducted by the company and revenue collected by the banks.
### Tools
- Mysql: Database Management and Cleaning
- Tableau: Visualization

### Data Cleaning/ Preparation
  In the data cleaning and preparation phase, we performed the following task:
  - Data loading and inpection
  - Handling missing values
  - Joined multiple tables that contains different datasets
  - Data Cleaning and formatting

### Exploratory Data Analysis
    EDA conducted on the dataset involves exploring the data to uncover key insights such as:
    1. How is the company performing financially overall?
    2. Which branches are contributing most to the company's revenue?
    3. Which banking partners are most effective in processing payments?
    4. How efficient are different terminals in handling transactions?

### Results and Findings
The main insights from the ticket sales analysis are as follows:
1. The revenue distribution among branches is remarkably balanced, with all branches generating between $3-3.5 million. Enugu leads slightly with $3.47 million, while Rivers generates about $3.06 million. This suggests consistent operational standards across locations.
2. Banking Partners: GTbank emerges as the strongest financial partner, processing nearly $9.8 million in transactions, significantly outperforming other banks. There's a clear hierarchy in banking partnerships, descending from GTbank to Paga ($8.4M), Opay ($7.8M), and Polaris bank ($6.4M).
3. Transaction Patterns: Despite similar revenue numbers, there are some variations in transaction volumes across branches. Enugu handles the highest volume with 542 transactions, while Kaduna processes the lowest at 462 transactions. This variance in transaction numbers despite similar revenues might indicate different pricing strategies or ticket types across locations.
4. Revenue: The company shows strong financial performance with $32.5 million in revenue, operating through a network of 10 branches that process 5,000 transactions.

### Recommendation
- Given the significant performance gap between GTbank ($9.8M) and other banks, especially Polaris bank ($6.4M), we recommend that the company should consider either reducing dependency on lower-performing banks or working with them to improve their processing efficiency to match GTbank's performance levels.
- Terminal Efficiency: The dashboard shows varying terminal performance levels. The company should investigate terminals with lower performance metrics and either upgrade or optimize them to match better-performing ones to ensure consistent service delivery across all points of sale.
- While the revenue distribution is fairly even, there are variations in transaction volumes (Kaduna at 462 vs Enugu at 542 transactions). We recommend that The company should involve standardizing operational practices across branches or sharing best practices from high-volume branches like Enugu.


### Limitation
Limited Customer Insights: There's no customer-related data such as satisfaction rates, complaints, route preferences, or passenger demographics, which would be crucial for a transport company's service improvement decisions.
