# Enterprise-Asset-Insights-Power-BI

**Overview**  
Note: Please note that the data presented in this report has been AI-generated and simulated for demonstration purposes only and does not represent real company data

This PowerBI dashboard is a fully-functional, mock version of a real dashboard with similar elements I created for the Government Compliance team, where I manage a database of enterprise government-owned assets that merges together 3 different software environments. These visualizations provide insights into necessary information such as best historical data, asset usage, and asset trends.

![Summary Page](https://github.com/brookebenator/Enterprise-Asset-Insights-Power-BI/blob/main/Summary%20Page.png?raw=true)
---

**Tools Used**  

-Sunflower: Asset management software  
-Microsoft Excel  
-Alteryx  
-PowerBI  

---

**PowerBI Features**    

-**Page Navigation:** This button allows the end user to easily toggle between pages to view specific asset information.    
-**Filter Button:** This fully functional filter button displays a filter pane when pressed, and provides the user with customizable filter options. The filter pane also has an option to clear all filters.    
-**Clear Filters Button:** A simple button that when pressed, clears all filters applied on the current page.    
-**Total Assets/Total Value ($) Button:** In order to toggle the visual to display asset count vs. its dollar value, the end user can simply switch between buttons in order to change the visual and gather insights on how the two metrics compare to eachother.    

---

**Data Cleansing**  

-Excel was used primarily for data exploration, pattern identification, and understanding key issues to be resolved  
-Using both AI and domain knowledge, Alteryx was utilized to integrate the three different data sets from each software environment together. Alteryx was also used to fix incorrect records, change null values, etc

---

**Dashboard Overview**  
**1. Summary Page:** The summary page gives quick, high-level information about all of the enterprise's assets. The visuals show broad information such as total assets and total monetary value, where they are located, and what are the different types.
	
**2. Asset Detail:** End users can filter by specific part numbers to see their attributes and specific information and history. KPIs show specific information about the part and provides insights to make informed business decisions.
	
**3. Risk Review:** Housing enterprise assets comes with carrying risk. This page highlights information about asset risk and offers insights about how to protect our assets.
	
---
	
**Business Insights & Real-Life Application**  
1. **Summary Page**:  
	
**● Data Point: How can we forecast an accurate budget to align with asset increases?**  
**Insight**: Asset values typically increase sharply every 5 years. This provides a key insight into how a budget can be created to forecast increasing expenditures. 

**● Data Point: How does asset count and value compare to each other in regards to asset type?**  
**Insight**: The dashboard shows how asset amount and value differ by asset type. Using the button to toggle between viewing the number of assets vs. the dollar amount for each type allows the end user flexibility when viewing this important piece of information.  

**● Data Point: Where are our assets physically located?**  
**Insight**: Determining asset location aids in hiring extra personnel and finding trends within location. Since most assets are clustered around the Atlanta area, it is important to make sure there are enough asset managers and employees.

2. **Asset Details**:
   
**● Data Point: Is the selected asset overdue on calibration?**  
**Insight**: Monitoring if an asset is overdue on calibration, in conjunction with its average risk score can help reduce risk and adverse effects such as damages or losses.

**● Data Point: How can we be proactive when it comes to purchasing parts?**  
**Insight**: This visual is great for a quick glance of the parts cost history. For example, if a parts price has only increased over the past few years, it might be worth checking out if this part can be replaced by a cheaper alternative.

**Feature - Filter Pane**: The filter pane implemented on this dashboard allows the end user to be able to drill further into the information. Being able to filter by Department, Condition, Program, and Manufacturer provides insights into how the assets differ within the enterprise. This filter pane is fully functional, and includes a counter that displays how many filters are applied to the current page. The Clear button also removes all filters, and the X button hides the filter pane.

3. **Risk Review**:
   
**● Data Point: What is the risk distribution of our assets including the total asset count and value?**  
**Insight**: Most of the enterprise assets are low risk, although a high amount are considered a medium risk, and most monetary value is tied up in medium risk assets. This gives an overview of effective management of medium and high risk assets.

**● Data Point: How can risk be mitigated by asset type?**  
**Insight**: High risk assets such as medical equipment and surveillance equipment each have over 1,000 assets that are overdue on calibration. To save costs and reduce risk, it is important this number must decrease to benefit the company. It was also determined there was a massive spike of uncalibrated IT equipment, which is worth diving deeper into how this problem arose and how it can be fixed.  

**● Data Point: Which of our high risk assets are overdue on calibration?**  
**Insight**: Using a table visual in PowerBI provides a quick glance at information and provides the ability to sort information. For example, an end user can filter by which asset has the oldest calibration due date. By displaying this information, the enterprise has collected together in one spot all of the assets that pose not only a high risk to the company, but provides insights on which assets to fix ASAP which will further prevent costly expenses.
