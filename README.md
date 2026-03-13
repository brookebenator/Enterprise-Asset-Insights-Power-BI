# Enterprise-Asset-Insights-Power-BI

**Overview**  
Note: Please note that the data presented in this report has been AI-generated and simulated for demonstration purposes only and does not represent real company data

This PowerBI dashboard is a fully-functional, mock version of a real dashboard with similar elements I created for the Government Compliance team, where I manage a database of enterprise government-owned assets that merges together 3 different software environments. These visualizations provide insights into necessary information such as best historical data, asset usage, and asset trends.

---

**Tools Used**  
-Sunflower: Asset management software  
-Microsoft Excel  
-Alteryx  
-PowerBI  

---

**Data Cleansing**  
-Excel was used primarily for data exploration, pattern identification, and understanding key issues to be resolved  
-Next, using both AI and domain knowledge, Alteryx was utilized to integrate the three different data sets from each software environment together. Alteryx was also used to fix incorrect records, change null values, etc

---

**Dashboard Overview**  
1. Summary Page: The summary page gives quick, high-level information about all of the enterprise's assets. The visuals show broad information such as total assets and total monetary value, where they are located, and what are the different types.
	
2. Asset Detail: End users can filter by specific part numbers to see their attributes and specific information and history. KPIs show specific information about the part and provides insights to make informed business decisions.
	
3. Risk Review: Housing enterprise assets comes with carrying risk. This page highlights information about asset risk and offers insights about how to protect our assets.
	
---
	
**Business Insights & Real-Life Application**  
1. Summary Page:  
	
a. **Data Point: How can we forecast an accurate budget to align with asset increases?**  
i. **Insight**: Asset amounts and values typically increase sharply every 5 years. This provides a key insight into how a budget can be created to forecast 		increasing expenditures. 

b. **Data Point: How does asset count and value compare to each other over time?**  
i. **Insight**: The dashboard shows how asset amount and value are changing by year. If the total asset count is higher than the total value, we can expect to manage assets with a low dollar value, which are generally less risky. When filtering by Instance-C, we see an important pattern that value is actually generally higher than its asset count which is the opposite pattern found in Instances A and B.  

c. **Data Point: Where are our assets physically located?**  
i. **Insight**: Determining asset location aids in hiring extra personnel and finding trends within location. Since most assets are clustered around the Atlanta area, it is important to make sure there are enough asset managers and employees.

2. **Asset Details**:
   
a. **Data Point: Is the selected asset overdue on calibration?**  
i. **Insight**: Monitoring if an asset is overdue on calibration, in conjunction with its average risk score can help reduce risk and adverse effects such as damages or losses.

b. **Data Point: How can we effectively reduce costs when buying new assets?**  
i. **Insight**: To determine cost saving efforts, an end user can identify on average, which manufacturer sells the part for the lowest price. This aids in effective buying practices by also facilitating negotiation with loyal manufacturers.  

c. **Data Point: How can we be proactive when it comes to purchasing parts?**  
i. **Insight**: This visual is great for a quick glance of the parts cost history. For example, if a parts price has only increased over the past few years, it might be worth checking out if this part can be replaced by a cheaper alternative.

3. **Risk Review**:
   
a. **Data Point: What is the risk distribution of our assets including the total asset count and value?**  
i. **Insight**: Most of the enterprise assets are low risk, although a high amount are considered a medium risk, and most monetary value is tied up in medium risk assets. This gives an overview of effective management of medium and high risk assets.

b. **Data Point: How can risk be mitigated by asset type?**  
i. **Insight**: High risk assets such as medical equipment and surveillance equipment each have over 1,000 assets that are overdue on calibration. To save costs and reduce risk, it is important this number must decrease to benefit the company. It was also determined there was a massive spike of uncalibrated IT equipment, which is worth diving deeper into how this problem arose and how it can be fixed.  

c. **Data Point: Which software environment houses the most high risk assets?**  
i. **Insight**: Software Instance-A houses the most high risk assets. This information helps in determining next actions such as implementing software security, hiring security personnel, and managing records for compliance purposes.
