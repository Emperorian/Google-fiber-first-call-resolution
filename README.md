![logo](https://github.com/Emperorian/Google-fiber-project/assets/101293550/78d13337-2d7f-4d5f-a229-52458441c49d)

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
![DASHBOARD FUNCTIONALITY](https://github.com/Emperorian/Google-fiber-project/assets/101293550/d78009c4-e190-409c-bba0-a5820ded28df)
#### Metrics and Charts
Please create a table like the example below for each chart that you’d like to include in the dashboard. If you’d like to break the dashboard under different headers, feel free to list those here as well.
![CHAT 1](https://github.com/Emperorian/Google-fiber-project/assets/101293550/d38a2ae7-10d8-42af-90eb-006c25b52452)

![CHAT 2](https://github.com/Emperorian/Google-fiber-project/assets/101293550/31fe8cc8-29e3-40fd-8483-354c0852bdc5)

![CHAT 3](https://github.com/Emperorian/Google-fiber-project/assets/101293550/16fa21af-a3bf-49bd-bfaa-2bfe9be35423)

![CHAT 4](https://github.com/Emperorian/Google-fiber-project/assets/101293550/805d0543-13e9-4f49-a48f-a8d65b973839)

# 2ND PHASE: Analyze
In the phase with the dataset, we going to create a dashboard for the stakeholders. To work with the Google Fiber data, you will need to upload your data to the appropriate workspace. If you plan on using BigQuery or Dataflow, upload the files to your project space to JOIN them. Additionally, because this data is already clean, you can connect these datasets in Tableau directly and merge them there. 
Your interviewers have provided three CSV files: 

#### market_1 [LINK](https://docs.google.com/spreadsheets/d/1a9IKjkvOvYHRx84SyRdp4Sq81EzgeOZPufcRtrUcAIc/template/preview#gid=775366698)
#### Market_2 [LINK](https://docs.google.com/spreadsheets/d/19CINdvAwp-2RF5pphkLywZLQJyJu66EOjX6CgrW32nA/template/preview#gid=2065220237)
#### Market_3 [LINK](https://docs.google.com/spreadsheets/d/1K6X9ZhjWtbneBss7PQH7IobGCzQ5NzG1hxs1D-hbsZM/template/preview?resourcekey=0-q90E-1XwD8nkNSjs0Ws3-w)

These datasets are observed to be clean and the data appears to be in  (ROCCC) standard. To produce a dynamic tableau table the 3 tables as to be merged into one via bigquery SQL workbench or directly into tableau in a situation where bigquery is not accessible. The table consists of 450 rows and 11 columns.  
 For the SQL code in big query:
 ```sql
SELECT
  date_created,
  contacts_n,
  contacts_n_1,
  contacts_n_2,
  contacts_n_3,
  contacts_n_4,
  contacts_n_5,
  contacts_n_6,
  contacts_n_7,
  new_type,
  new_market
FROM `your project.fiber.market_1`
UNION ALL
SELECT
  date_created,
  contacts_n,
  contacts_n_1,
  contacts_n_2,
  contacts_n_3,
  contacts_n_4,
  contacts_n_5,
  contacts_n_6,
  contacts_n_7,
  new_type,
  new_market
FROM `your project.fiber.market_2`
UNION ALL
SELECT
  date_created,
  contacts_n,
  contacts_n_1,
  contacts_n_2,
  contacts_n_3,
  contacts_n_4,
  contacts_n_5,
  contacts_n_6,
  contacts_n_7,
  new_type,
  new_market
FROM `your project.market_3`
```
The above code will produce the a merge of the three tables into one target table of destination with the following columns
#### Descriptions of columns:
 
 ****date_created = creation of customer support calls****
 
 ****contacts_n = number of first calls****
 
 ****contacts_n_1 = number of follow-up calls (out of the first calls) after 1 day****
 
 ****contacts_n_2 = number of follow-up calls (out of the first calls) after 2 days****
 
 ****contacts_n_3 = number of follow-up calls (out of the first calls) after 3 days****
 
 ****contacts_n_4 = number of follow-up calls (out of the first calls) after 4 days****

 ****contacts_n_5 = number of follow-up calls (out of the first calls) after 5 days****
 
 ****contacts_n_6 = number of follow-up calls (out of the first calls) after 6 days****
 
 ****contacts_n_7 = number of follow-up calls (out of the first calls) after 7 days****
 
 ****new_type = type of the problem for the call (type_1 = account management,****
 
 ****type_2 = technician troubleshooting, type_3 = scheduling, type_4 = construction,**** 
 
 ****type_5 = internet and wifi)****
 
 ****new_market = there are 3 possible values (market_1, market_2, market_3) that correspond to different cities and that are anonymized by the course instructors**** 

The UNION ALL statement is applied here instead of a JOIN statement because the tables already have matching columns, making them easy to merge completely. 
After you have run this query, you should have a combined table like this:
![combined table](https://github.com/Emperorian/Google-fiber-project/assets/101293550/1df04425-1760-4d30-9f47-899b889dea01)

The table above is cropped but  the table should be 1350 rows.

# 3rd phase: Monitor 
The monitor stage is the design of the dashboard but before the dash, a low-fidelity mockup must be produced which is a rough sketch of what the dash should look like. However, we have to keep in mind some important parameters. The whole project focuses on FIRST CALL RESOLUTION (FCR) which is one of the issues with KPI (key performance index) this simply shows how call issues are resolved after the first call and how many total calls are received for the same purpose as calls initially. Also, we to keep in mind that we have to use project planning documents to identify key metrics and dashboard requirements. 
This is a mockup of the dashboard  which initially designed, although it is not perfect it should include the total number of calls, market problems, and type, three to four charts. I will make my chart as side-by-side bars for the total first calls and follow-up calls. In this way, the stakeholders can still determine how many customers repeat, which answers their problems.

Also, showing the base value (the total number of first calls) gives justice for comparing 

#### Low-fidelity mock-up table for the project:
![low fidelity mockups](https://github.com/Emperorian/Google-fiber-project/assets/101293550/e2f3f247-aadd-4f37-8d01-8a9ee09da69b)

# The final dashboard
![day 0 by market and type across Q1](https://github.com/Emperorian/Google-fiber-project/assets/101293550/dbb82cd6-52f4-4278-92c6-7d48ed34dbb0)

The final dashboard came out different from initial design as anticipated. However the analysis still stands. For the market and type showing in percentage for day 0 market and type across Q1, type_2 for maerket _1 show 32.51% dont forget that type 2 is troubleshooting while there is also a significant increase in type_5 which is internet and wifi.

![1st repeat call by market and type across](https://github.com/Emperorian/Google-fiber-project/assets/101293550/4a005d5b-5315-4d0c-a636-4f1ad634d62f)

For 1st repeat calls by market and type across Q1 type_5 for all the market shows signinantly high returns which show that internet and wifi needs looking into. There is also a slightly high return for the type_2 as well, which is the troubleshooting.

![calls by market and type](https://github.com/Emperorian/Google-fiber-project/assets/101293550/caaaeee8-0ec9-4cbb-a8b5-a8374561e381)
![Repeat by 1st call date](https://github.com/Emperorian/Google-fiber-project/assets/101293550/aa9dfa87-43e2-4fba-9301-8883006160a3)

Calls by market and type in total shows an average of 64 thousand for first call while an average of 2 thousand was showing for total repeated calls.The first table allows stakeholders to explore the number of different types of calls by date. The second table then separates calls into market and problem type to provide more specific information about what markets experience the most calls and the problems customers have that seem to prompt repeat calls. 

![market and first repeat call](https://github.com/Emperorian/Google-fiber-project/assets/101293550/56e91a0d-4df0-435f-9e24-46038a8e17e2)
![repeat by month](https://github.com/Emperorian/Google-fiber-project/assets/101293550/fd831d9a-e2fd-4522-82bc-73c93e1e11aa)

#### Market and Type for First Repeat Calls
The Market and Type for First Repeat Calls uses the data from the previous tabs table in order to further visualize the problem types that seem to generate the most repeat calls for different markets. 
You can interact with the dashboard on tableau here: [google fiber link tableau](https://public.tableau.com/authoring/GOOGLEBUSINESSINTELLIGENCECAPSTONEPROJECTGOOGLEFIBER/Story1#1)


# Key Findings:
- Market_1 generates the highest percentage of repeat calls, followed by market_3 and market_2.
- Internet and wifi (Type_5) and technician troubleshooting (Type_2) issues account for 80.24% of repeat calls.
- The customer service team receives an average of 25% repeat calls within seven days of the initial contact.

 
 # Recommendations:
- Providing additional training and support for handling technician troubleshooting and internet and wifi issues.
- Allocating more resources and staff to market_1 to address the higher volume of repeat calls.
- A verification department might be created to double calls activity on a day basics to avoid huge complilations





































