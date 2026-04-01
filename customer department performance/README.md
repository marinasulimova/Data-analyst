# **Customer service department’s performance** #

## Visialization:
[Dashboadrs in Power BI](https://github.com/marinasulimova/Data-analyst/blob/main/customer%20department%20performance/customer%20department%20performance.pbix)  
[Dashboards in pdf](https://github.com/marinasulimova/Data-analyst/blob/main/customer%20department%20performance/customer%20department%20performance.pdf)  

## Short description of a project
A report of customer service department's performance.   
### Used data: 
online telephony.  
### Used instruments: 
Excel for cleaning and wrangling.   
Dax for counting.   
Power BI for visualization.  

## Business problem: 
Low Order Volume from Individual Clients despite High Workload on Client Department Managers.  
Small customer orders combined with heavy workloads for managers reveal inefficiencies in the client department. 
Existing processes aren't set up well for smooth customer handling, which wastes time and drags down productivity.

## Background: 
Previous reports, managed by a Head of Customer Service Department, have not reflected the whole story of department's performance.

## Project objective:  
1. To evaluate the dynamics of the key performance indicators of client department from January 2024 through July 2025,  
2. identify the factors influencing the level of customer service,   
3. determine potential directions for process optimization.

## Project tasks:
1. Compare the number of answered and missed calls by month in 2024 and 2025, with a focus on the share of missed inquiries.
2. Analyze changes in operator response speed and the average client waiting time on the line.
3. Identify time windows and days of the week with the highest level of call losses.
4. Assess the workload and performance efficiency of client department staff.

## Hypothesis for analytical report:
1. A significant share of incoming calls may be registered before or after operator shifts, which could explain part of the losses.  
*Validation*:  
&#x20;Build a heatmap of incoming calls by hour and day of the week.  
&#x20;Overlay the contact center’s operating schedule and analyze overlaps.  
&#x20;Assess the share of missed calls outside working hours to quantify the scale of the issue.  
*Additional Questions*:  
&#x20;Is there seasonality or specific days of the week when missed calls are more frequent?  
&#x20;Could this indicate latent demand for extended operating hours?  

2. Inefficient IVR Configuration Contributes to Client Loss  
*Basis*: In 2024, 24% of calls were lost within the voice menu.  
*Validation*: Analyze the average time to enter IVR and to terminate the call, identifying exit points.  

3. Queueing for Operators Leads to Abandonment  
*Basis*: In 2024, 74% of missed calls were linked to waiting for an operator.    
In the first seven months of 2025, this figure was 71%, indicating insufficient operator capacity.  
*Validation*: Build a distribution of waiting times and analyze the share of abandoned versus completed calls depending on wait duration.  

4. Call Answer Speed Does Not Always Meet Standards  
*Basis*: Between July and October 2024, the share of calls answered within 60 seconds was below the 80% target.     
Specifically: July–August at 54%, September at 59%, October at 75%.  
*Validation*: Compare response times with successful call completion and customer satisfaction levels.  

## Conclusions after analytical report:
1. Continuous high percentage of abandoned calls (an average near 30%)  
2. Shortage of contact center staff (especially on summer period)  
3. The hypothesis about missed calls during not working time is not confirmed  
4. No clear pattern in the number if missed calls based on day of week (working, weekend)  
5. Noted the quality of work with received calls  
6. Lack of personal motivation of employees.  

## Recommendations:
1. Work schedule optimization  
2. Set up an automatically call back system  
3. Configure AI bots for relieving lines  
4. Develop alternative channels for client's interaction  
5. Implement a motivation system and KPIs for managers  
6. Develop new instructions  
7. Carry out a speech analytics system for conversations.  
