ElectViz Election Data Visualization for Media

Project Overview

ElectViz is an interactive, multi-page Power BI dashboard created for the Infosys Springboard Virtual Internship (Batch 6.0). This project transforms decades of complex Indian state election data (1977-2014) into a clear, intuitive, and powerful analytical tool.

It is designed for media organizations, political analysts, and the public to explore voting patterns, party performance, and historical trends without needing to sift through complex spreadsheets.

Team Members

This project was developed by Batch 2, Team D:

Pendyala Pradeep Reddy

Pavithiraa S

Hem Kumar V

V.Charan Teja

Project Objective

The primary goal of this project is to analyze and visualize complex Indian state election data.

Key objectives include:

Consolidating key election metrics, including total votes, party participation, seats won, and voter turnout.

Identifying historical voting trends by visualizing data across different election years.

Providing a comparative analysis of political party performance at both the state and national levels.

Creating a granular breakdown of seat distribution by state and constituency.

Empowering users with interactive slicers and filters to find specific, dynamic insights.

Technical Stack

Microsoft Power BI Desktop: The primary tool used for data modeling, analysis, and creating all visualizations.

Power Query Editor: Used extensively for data cleaning, transformation, and preparing the raw data for analysis.

DAX (Data Analysis Expressions): Used to create all key measures and KPIs, such as Total Votes, Total Parties, Voter Turnout %, etc.

Microsoft Excel: Used as the initial data source for the raw election data.

The Data Challenge: Cleaning & Modeling

A significant challenge was the complexity of the raw data. The dataset spanned decades and included:

3044 Million+ Total Votes

1637 Unique Political Party entries

A major part of the project involved using Power Query Editor to clean and standardize the 1,637 party names, handling duplicates, and formatting the data for accurate analysis.

ElectViz Dashboard Showcase

The final report consists of 5 interactive pages:

1. Indian State Election Analysis (Main Dashboard)

This is the main landing page, providing a high-level overview of the entire dataset. It features key slicers that control the entire report.

<img width="1109" height="732" alt="Screenshot 2025-10-30 190741" src="https://github.com/user-attachments/assets/1abeed1b-056b-4ca1-95ea-6826d2110850" />



Key KPIs: Total Votes (3044M), Total Parties (1637), Total Seats (5670), Voter Turnout % (5.52%).

Key Visuals: Seats Won by Party Name, Sum of Seats Won by State.

Interactivity: Slicers for Election Year, Political Party, State, and Constituency Type.

2. Temporal & Turnout Analysis

This page focuses on historical trends and voter engagement.

<img width="1024" height="690" alt="Screenshot 2025-10-30 190802" src="https://github.com/user-attachments/assets/9228d26d-0642-4a74-adc5-026803f75b19" />


Key Visuals:

Total Votes by year (Line Chart)

Voter Turnout % by State Name (Donut Chart)

3. Top Performers & Cumulative Growth

This dashboard gives a quick snapshot of the most significant entities and their historical growth.

<img width="1125" height="733" alt="Screenshot 2025-10-30 190824" src="https://github.com/user-attachments/assets/b65b855d-236a-4f53-b916-0a9720171224" />


Key Visuals:

Top Party: Independent (Card)

Top State: Uttar Pradesh (Card)

Count of Seats Won by year (Waterfall Chart)

4. Share & Distribution Analysis

This page breaks down performance by state and party vote share.

<img width="1308" height="734" alt="Screenshot 2025-10-30 184159" src="https://github.com/user-attachments/assets/92906a88-2dda-40bb-9e16-fb1113d85a40" />


Key Visuals:

Count of Seats Won by State name (Funnel Chart)

Vote share by party (Pie Chart)

5. State-wise Party Seat Distribution

This is the most granular dashboard, providing a detailed matrix for specific analysis.

<img width="1104" height="723" alt="Screenshot 2025-10-30 184319" src="https://github.com/user-attachments/assets/b058076f-941c-4c82-ba81-fb088b2da792" />


Key Visual: A detailed Matrix with State Name as rows, Party Abbreviation as columns, and Sum of Seats as the values.

How to View

Clone this repository.

Download the Electviz Election Data Visualization.pbix file.

Open the file using Microsoft Power BI Desktop.

Acknowledgements

We would like to express our sincere gratitude to our mentor, Mrs. Nithyasri S J , for their invaluable guidance and support throughout this project. We also thank the Infosys Springboard program for providing this excellent virtual internship opportunity.
