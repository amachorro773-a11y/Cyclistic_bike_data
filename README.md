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
After reviewing and processing over 1 million rows of raw trip data, the findings reveal that **while casual riders utilize the service for long, weekend leisure trips, annual members** rely on Cyclistic for **consistent weekday commuting**. By bridging these data-driven insights with marketing strategy, I developed three actionable recommendations to convert high-value casual riders into loyal subscribers, driving the company’s long-term growth and profitability.

<img width="999" height="799" alt="Capstone (1)" src="https://github.com/user-attachments/assets/7469f958-8027-4e9f-aba1-ed2b3b9dbd0f" />

### So What?
Now that we know that casual riders are not just “unregistered members”, they are leisure seekers who value the experience of these rides, we can take the appropriate steps to turn them into members.
By failing to convert these high-duration weekend riders, Cyclistic is missing out on stable, recurring revenue that could fund fleet maintenance and expansion.

# Recommendations (3 Actions):

## 1. The "Weekend Explorer" Membership Tier
Strategy: Capture the high-volume weekend leisure market by introducing a specialized annual membership tier designed for non-commuter usage patterns.
  - **Data-Driven Market Segmentation**: Analysis of 5 months of trip data reveals that casual ridership peaks on Saturdays and Sundays, with average          durations nearly double those of weekday members. This identifies a distinct "Leisure Segment" that is currently underserved by existing daily or         annual commuter-focused plans.
  - **Targeted Revenue Growth**: By implementing a weekend-specific annual pass priced at 50% of the standard rate, Cyclistic can convert sporadic, high-       intent weekend users into a predictable, recurring revenue stream. This pricing strategy lowers the barrier to entry while maintaining the premium        value of the full annual membership.
  - **Risk Mitigation & Conversion**: To maximize adoption, the tier will include a "First-Month Flex" grace period allowing for a penalty-free cancellation.   This removes the primary friction point of long-term commitment, incentivizing casual users to enter the "Member Pipeline" and increasing long-term       Customer Lifetime Value (CLV).

## 2. Leisure-Enhanced Membership Perks
Strategy: Elevate the Annual Membership value proposition by integrating leisure-focused benefits, specifically targeting the high-duration ride patterns identified in the casual rider segment.
  - **Premium Fleet Access**: Grant exclusive or priority access to "Leisure-Class" equipment, such as newer cargo bikes or reclining models, to annual         members.
    - **Business Logic**: By reserving specialized equipment for members, we transform a "functional" utility into a "lifestyle" amenity, directly                appealing to the leisure preferences seen in the casual rider data.
  - **The "Conversion" Trial Program**: Implement a 7-day "Member Experience" trial for high frequency casual riders.
    - **Strategic Billing**: At the end of the 7-day trial, users are seamlessly transitioned into a monthly subscription. This "opt-out" model reduces           friction and has been shown to significantly increase long-term conversion rates.
  - **Operational Efficiency**: Position these perks as a zero-marginal-cost benefit. Since the specialized fleet is already part of Cyclistic’s                inventory, utilizing them as a membership incentive maximizes asset utilization without increasing capital expenditure.

## 3. Geospatial Marketing & Station-Specific Conversion
Strategy: Deploy hyper-localized marketing campaigns at identified "Casual Hubs" to intercept high-intent users at the point of interaction.
  - **Precision Placement**: Utilize geospatial data to prioritize the top 10 stations with the highest casual rider traffic for physical signage and           digital geofencing.
    - **Data-Driven Rationale**: Analysis confirms that casual ridership is heavily concentrated at specific "Leisure Stations" (e.g., Streeter Dr &              Grand Ave), whereas members are distributed across transit hubs. Targeting these specific high-traffic hotspots ensures maximum visibility among          the core audience.
  - **In-App Interventions**: Trigger automated push notifications or "Upgrade Now" prompts when a casual rider starts a trip at one of the identified          top-tier stations.
    - **Strategic Goal**: By reaching the user during the "start-of-ride" phase, we capitalize on a moment of high engagement, increasing the likelihood          of immediate conversion to the "Weekend Explorer" or "Member Experience" tiers.
  - **Signage Alignment**: Ensure physical advertisements at these stations specifically highlight the benefits casual riders care about, such as the           availability of cargo/reclining bikes and unlimited ride time, rather than just commuting speed.

# Plan of Action (12 Month Period)   
## Phase 1: Infrastructure
  - Inventory Audit:
    - Making sure we have the appropriate supply and demand for Leisure Perks program
  - Beta Testing for “Weekend Explorer” tier membership:
    - Launch tier program near areas where casual members frequent
  - Geofencing Setup:
    - Configure digital marketing triggers at the top 10 identified stations

## Phase 2: Marketing and Conversion
  - Physical Signage Rollout:
    - Deploy targeted physical advertisements near dense casual stations
  - Initiate a week free trial:
    - Allow people to initiate a 7-day member trial program, transitioning participants into a monthly billing cycle towards the end of trial
  - KPI Tracking:
    - Monitor conversion rates from casual to “Weekend Explorer” vs. full annual memberships to refine subscription prices
    
## Phase 3: Scaling and Long-term Retention:
  - Full Fleet Integration:
    - Scale premium bike access to ALL stations across the Cyclistic network
  - Annual Strategy Review:
    - Analyze impact on CLV and determine if additional tiers are required

