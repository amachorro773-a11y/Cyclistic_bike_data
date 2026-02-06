# Project Background

Cyclistic is a pioneering bike-sharing service based in Chicago that has rapidly transitioned from a niche startup to a mainstream pillar of urban transportation. Launched with a mission to make eco-friendly commuting accessible to all, Cyclistic features a diverse fleet of over **5,800** bicycles, including standard two-wheelers, reclining bikes, hand tricycles, and cargo bikes, spread across a network of **692** tracking stations.
Initially popularized by local weekend explorers and tourists, Cyclistic has seen a massive surge in "mainstream" adoption. As Chicago infrastructure continues to prioritize green lanes and sustainable transit, Cyclistic has become a primary choice for daily commuters.\
Data used for analysis can be found [here](https://divvy-tripdata.s3.amazonaws.com/index.html) 



### The Business Challenge
Despite its growing popularity, Cyclistic’s financial success depends on more than just total ridership. The marketing strategy currently focuses on two distinct segments:
  - **Casual Riders**: Customers who purchase single-ride or full-day passes.
  - **Cyclistic Members**: Annual subscribers who use the service for consistent, daily transit.
### My Goal: 
As a Junior Data Analyst, I am analyzing historical trip data to identify how these two groups use Cyclistic differently. By understanding these patterns, I aim to design a data-driven strategy to convert casual riders into loyal, annual members, securing the company's long-term growth.
### Why does this matter? 
By increasing the amount of members, we establish:
  - **Predictable revenue**: recurring income guaranteed, allows for company maintenance, expansion, and infrastructure upgrades.
  - **Operational efficiency**: More predictable behaviors towards bike usage, such as commuters.
  - **Customer Acquisition Cost (CAC)**: Easier to maintain an existing member than it is to find new riders.


# Data Structure and Initial Checks:
Cyclistics database is composed of a single table that includes the following:

<img width="516" height="935" alt="export (1)" src="https://github.com/user-attachments/assets/91af01a1-092c-4ce5-9e07-f9e3fe34b0e7" />

From this data, I was able to create a sub table that quantified metrics involving average time, day of the week, and other helpful info:

<img width="516" height="452" alt="export (3)" src="https://github.com/user-attachments/assets/9f8f411b-d9d7-4f36-a6cf-5a0b3dfad82e" />

Prior to beginning the analysis, a variety of checks were made for quality control and familiarization with the datasets. The SQL queries used to inspect and conduct quality checks can be found [here](https://github.com/user-attachments/files/25114379/SQL.Queries.Page.pdf)

# Executive Summary:
After reviewing and processing over 1 million rows of raw trip data, my findings revealed that **while casual riders utilize the service for long, weekend leisure trips, annual members** rely on Cyclistic for **consistent weekday commuting**. By bridging these data-driven insights with marketing strategy, I developed three actionable recommendations to convert high-value casual riders into loyal subscribers, driving the company’s long-term growth and profitability.

<img width="999" height="799" alt="Capstone (1)" src="https://github.com/user-attachments/assets/7469f958-8027-4e9f-aba1-ed2b3b9dbd0f" />

### So What?
Now that we know that casual riders are not just “unregistered members”, they are leisure seekers who value the experience of these rides, we can take the appropriate steps to turn them into members.
By failing to convert these high-duration weekend riders, Cyclistic is missing out on stable, recurring revenue that could fund fleet maintenance and expansion.
