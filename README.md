# GOOGLE FIBER FIRST CALL RESOLUTION PROJECT
### BACKGROUND:
Google Fiber provides people and businesses with fiber optic internet. Currently, the customer service team working in their call centers answers calls from customers in their established service areas. In this fictional scenario, the team is interested in exploring trends in repeat calls to reduce the number of times customers have to call for an issue to be resolved. 
### TASK:
As a business intelligence analyst currently interviewing for a BI position on the Google Fiber call center team. As part of the interview process, I was asked to develop a dashboard tool that allows them to explore trends in repeat calls. The team needs to understand how often customers call customer support after their first inquiry. This will help leadership understand how effectively the team can answer customer questions the first time.
### BUSINESS INTELLIGENCE COURSE REVIEW:
The business intelligence course involves the automating of processes and information channels to transform relevant data into actionable insights that are easily available for decision-making by stakeholders. This is further broken down into three other stages which are the capture, analysis, and monitor

  #### Capture: 
         one way to ensure that you capture the big picture project requirement, stay organized, and make an impact in the organization is to create a BI document.
           - Stakeholder requirement document.
           - Project requirement document
           - Strategy document
         This is the foundation of business intelligence.

  #### Analyse: 
         The analysis phase involves using data models to build database systems, how schemas help organize database systems, and how pipelines move data. It involves the movement of data from source to destination, which 
         involves ETL (extract, transform, and load) and the importance of data integrity. The analysis phase is not complete without mentioning the use of database systems like Datawarehouse such as BIGQUERY and SQL for 
         communicating with the database. The production, import, export, merging of datasets and also cleaning, analyzing, and statistical dictation are done at this stage. This analysis stage is also known as the path 
         to insight(data models and pipelines)

  #### Monitoring: 
         The monitoring involves the data visualizations which is the graphical representation of data. This is the decision-making phase where dashboards are created.it is also important to mention the creation 
         of low-fidelity mockups for the dashboards before eventually creating the final dashboards for the stakeholders to make their decisions. This phase is not just about reporting and making dashboards but to 
         creating a dynamic system for the implementation of the all project. In this project, Tableau was used to create the dynamic dashboard which involves encoding the dimensions(qualitative) and measure(quantitative) 
         of data.

### Business intelligence tools used in the project
- Bigquery SQL workbench or data flow
- Spreadsheet
- Tableau
- Powerpoint

# 1st phase: Capture
# 1. Project Requirements Document: Google Fiber customer service
 
### BI Analyst: Akinbosede Morohunfoluwa Opemiposi 
#### Client/Sponsor: Fiber customer service team
#### Purpose: 
The team needs to understand how often customers phone customer support again after their first inquiry; this will help leaders understand whether the team can answer customer questions the first time. Further, leaders want to explore trends in repeat calls to identify why customers have to call more than once and how to improve the overall customer experience. A dashboard will be created to reveal insights about repeat callers. 
#### Key dependencies: Team members: 
- Ian Ortega, BI Analyst
- Sylvie Essa, BI Analyst

*Primary contacts are Emma and Keith*

#### Primary requirements: 
- A chart or table measuring repeat calls by their first contact date
- A chart or table exploring repeat calls by market and problem type
- Charts showcasing repeat calls by week, month, and quarter

#### Stakeholder requirements: Stakeholders:
- Emma Santiago, Hiring Manager
- Keith Portone, Project Manager
- Minna Rah, Lead BI Analyst

#### Success criteria: 
The team’s ultimate goal is to reduce call volume by increasing customer satisfaction and improving operational optimization. The dashboard should demonstrate an understanding of this goal and provide stakeholders with insights about repeat caller volumes in different markets and the types of problems they represent. The result must be specific, measurable, action-oriented, relevant, and time-bound
User journeys: The user journey is to explore trends in repeat calls to identify why customers are having to call more than once, as well as how to improve the overall customer experience in the future

#### Assumptions: 
 How often does the customer service team receive repeat calls from customers?
 What problem types generate the most repeat calls?
 Which market city’s customer service team receives the most repeat calls?

#### Compliance and privacy: 
This dataset is a version of actual data the team works with. Because of this, the data is already anonymized and approved. It includes:
- Number of calls
- Number of repeat calls after first contact
- Call type
- Market City
- Date

#### Accessibility: 
To anonymize and fictionalize the data, the datasets the columns market_1, market_2, and market_3 to indicate three different city service areas the data represents. 
The data also lists five problem types:
- Type_1 is account management
- Type_2 is technician troubleshooting
- Type_3 is scheduling
- Type_4 is construction
- Type_5 is internet and wifi

#### Roll-out plan: 
The dataset records repeat calls over seven-day periods. The initial contact date is listed as contacts_n. The other call columns are then contacts_n_number of days since the first call. For example, contacts_n_6 indicates six days since the first contact. 


# 2.  Stakeholder Requirements Document: Google Fiber customer service
                                                                                        
### BI Professional: AKINBOSEDE MOROHUNFOLUWA OPEMPOSI
#### Client/Sponsor: Fiber customer service team
#### Business problem: 
The team needs to understand how often customers phone customer support again after their first inquiry
 
 #### Stakeholders:
- Emma Santiago, Hiring Manager
- Keith Portone, Project Manager
- Minna Rah, Lead BI Analyst
#### Team members: 
- Ian Ortega, BI Analyst
- Sylvie Essa, BI Analyst

  *Primary contacts are Emma and Keith*

#### Stakeholder usage details: 
stakeholders will have access to all datasets so they can explore the steps I’ve taken.

#### Primary requirements: 
- A chart or table measuring repeat calls by their first contact date
- A chart or table exploring repeat calls by market and problem type
- Charts showcasing repeat calls by week, month, and quarter

# 3. Strategy Document: Google Fiber

### Sign-off matrix:

#### Name: AKINBOSEDE MOROHUNFOLUWA OPEMIPOSI
#### Team / Role: Fiber customer service team
#### Date: 2/9/2024 

#### Proposer: 
Emma Santiage, Hiring Manager

#### Status:
Draft > Under review > Implemented | Not Implemented

#### Primary dataset: 
market_1, market_2, market_3

#### Secondary dataset: 
User Profiles Who is the intended audience for this dashboard? How do you expect them to use this dashboard?
- Emma Santiage,  Hiring Manager
- Keith Portone, Project Manager
- Minna Rah,  Lead BI Analyst
- Ian Ortega,  BI Analyst
- Sylvie Essa,  BI Analyst
    
Dashboard Functionality
Dashboard Feature
Your Request
Reference dashboard
Should this dashboard be modeled on an existing dashboard? If so, provide a link and describe the similarity.
Build a new dashboard to explore the number of repeat callers and their problem types in three different market cities.



Access
How should access to the dashboard be limited? Who needs to have access?
Access will be provided as read-only to the user profiles listed in this document. 
Scope
What data should be included (or excluded) in this dashboard?
Fields include: date, market, problem_type, contact_n and contact_n_#
Date filters and granularity
Should the dashboard include date filters? If so, what time frame should be displayed by default? Should the dashboard include a “Granularity” drop-down? If so, what granularity should be selected by default?
Data filters can be applied for the following:
Week, Month, Quarter

Granularity:
Any chart with detailed metrics should have the ability to click on that metric to view specific information.




Metrics and Charts
Please create a table like the example below for each chart that you’d like to include in the dashboard. If you’d like to break the dashboard under different headers, feel free to list those here as well.
Chart 1
Chart Feature
Your Request
Chart title
Repeat calls by first date
Chart type
What type of chart needs to be created? This could include any chart type, including a line chart (timeseries), bar chart, or table.
Table
Dimension(s)
What dimensions does this chart need to include?
Day of initial call, subsequent repeat calls
Metric(s)
What metrics are relevant to this chart?
Contact


Chart 2
Chart Feature
Your Request
Chart title
Market and Problem Type of First Repeat Calls
Chart type
What type of chart needs to be created? This could include any chart type, including a line chart (timeseries), bar chart, or table.
Bar
Dimension(s)
What dimensions does this chart need to include?
Call type, market, contact_n_1
Metric(s)
What metrics are relevant to this chart?
Contact




Chart 3
Chart Feature
Your Request
Chart title
Calls by Market and Type
Chart type
What type of chart needs to be created? This could include any chart type, including a line chart (timeseries), bar chart, or table.
Table
Dimension(s)
What dimensions does this chart need to include?
Market, call type, day
Metric(s)
What metrics are relevant to this chart?
Contact


Chart 4
Chart Feature
Your Request
Chart title
Repeats by Week, Month, and Quarter
Chart type
What type of chart needs to be created? This could include any chart type, including a line chart (timeseries), bar chart, or table.
Bar
Dimension(s)
What dimensions does this chart need to include?
Date, contact
Metric(s)
What metrics are relevant to this chart?
Date




           



2ND PHASE: Analyze





 
