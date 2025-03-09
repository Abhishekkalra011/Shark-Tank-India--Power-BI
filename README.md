# Shark-Tank-India--Power-BI
![image](https://github.com/user-attachments/assets/75944a0e-66fe-4760-8d98-503f0bb72448)
## Report View
https://app.powerbi.com/view?r=eyJrIjoiOTE4YmM3OWYtYTg5YS00NjNlLTk1ZTMtYTk2ODY3ZGNmMTFlIiwidCI6IjU1YmQ5ZTdkLTdkMWEtNGZlNy1hNmZmLTJhOWY0YzdkZjAxYSJ9
## Project Overview:
The primary objective of this project is to analyze the investment patterns and trends in the Indian startup ecosystem, as depicted by the Shark Tank India show. Specifically, the project aims to:
1.	Identify Popular Domains: Determine the most popular domains or sectors that attract the most investment.
2.	Analyze Investor Behavior: Understand the investment strategies and preferences of individual sharks.
3.	Track Investment Trends: Analyze trends in investment amounts, deal sizes, and equity stakes over time.
4.	Identify High-Potential Startups: Identify startups with high growth potential based on their business model, team, and market opportunity.
5.	Provide Recommendations: Offer actionable insights to entrepreneurs, investors, and policymakers to foster the growth of the Indian startup ecosystem.
![image](https://github.com/user-attachments/assets/0dafd47e-f7e0-4c7c-9d74-4c192e31b25f)

## Data Structure:
Tables and Their Relationships
### 1.	Domain
o	Columns: Domain Name, Brand, Debt, Debt Numerical, Equity, Episode No, Idea, Investment
o	Relationships: 
	One-to-many relationship with the Sharks table. Each Domain can have multiple Sharks associated with it.
### 2.	Sharks
o	Columns: Column8, Company, Description, Name of Sharks, Total Companies, Total Companies (Numbers), Total Investment, Total Investment Text
o	Relationships: 
	Many-to-one relationship with the Domain table. Multiple Sharks can be associated with a single Domain.
### 3.	Sharks Updated
o	Columns: Column8, Company, Description, Name of Sharks, Total Companies, Total Companies Text, Total Investment, Total Investment Text
o	Relationships: 
	One-to-one relationship with the Sharks table. This table might be an updated version of the Sharks table or a specific view of it.
### Data Structure Summary
•	Domain Table: Contains information about different business domains, including the number of pitches, investments, and the sharks involved.
•	Sharks Table: Stores details about individual sharks, such as their names, the companies they invested in, and the total investments made.
•	Sharks Updated Table: This table might be a more recent version of the Sharks table, containing updated information about the sharks and their investments.

## Executive Summary:
The analysis of the Shark Tank India data reveals several key insights:
•Food and Beverages emerged as the most popular domain, attracting the highest number of pitches.
•Aman Gupta was the most active investor, with the highest number of deals and total investment amount.
•Investment Trends: Most investments were concentrated in the lower investment range, with fewer deals in the higher investment range.
•Deal Size Distribution: The distribution of deal sizes and equity stakes followed a similar pattern, with most deals having lower equity stakes.

## Insights Deep Dive:
![image](https://github.com/user-attachments/assets/bff42a7c-8a02-4b75-ab12-d337f4769351)

### Overall Performance:
•	Total Investment: ₹336.20M, indicating significant investor interest in Indian startups.

•	Total Pitches: 117 pitches received, showcasing a wide range of business ideas.

•	Total Domains: 11 unique domains of business were presented.

•	Highest Investment: ₹15M was the highest investment made in a single deal.

### Investment Trends:
•	The majority of investments are concentrated in the lower investment range (0-5M).

•	There are fewer investments in the higher investment range (15M+).

•	The distribution of investments across different equity percentages follows a similar pattern, with most deals having lower equity stakes.
![image](https://github.com/user-attachments/assets/0c3ffacd-951f-4c2c-b90a-ffad1f4955d0)

### Analyzing the Shark Tank India:
•	This report page provides a visual representation of the investment activity of the various sharks on the show.
![image](https://github.com/user-attachments/assets/0492bd41-951d-410e-875e-82a8c08d4215)

### Investor Performance:
•	Aman Gupta: Invested in 28 companies, totaling ₹93.58M.

•	Peyush Bansal: Invested in 27 companies, totaling ₹82.97M.

•	Anupam Mittal: Invested in 24 companies, totaling ₹53.38M.
![image](https://github.com/user-attachments/assets/e5e25f51-108a-42f4-9cdf-f0a50b4159e6)

### Overall Performance:
•	Total Pitches: 117 pitches were received across 35 episodes.

•	Total Investment: A total of ₹390.01M was invested in various startups.

### Domain-wise Analysis:
•	Food and Beverages: This domain emerged as the most popular, accounting for 29.91% of the total pitches.

•	Accessories: The second most popular domain, with 17.09% of the pitches.

•	Retail and Fashion: Followed closely with 11.97% of the pitches.


## Recommendations:
### • Focus on High-Potential Domains: 
Entrepreneurs should focus on developing businesses in domains with high investor interest, such as Food and Beverages, Technology, and Retail. 
### • Tailor Pitch Decks:
 Pitch decks should be tailored to the specific interests and investment criteria of each shark. 
### • Build Strong Teams: 
A strong and experienced team is crucial for attracting investment. 
### • Focus on Scalability and Growth:
 Investors are looking for businesses with high growth potential and scalability. 
### • Leverage the Shark Tank Platform:
 Utilize the platform to build brand awareness, generate buzz, and attract additional funding.
