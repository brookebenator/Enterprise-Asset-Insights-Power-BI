# Enterprise-Asset-Insights-Power-BI

**Overview**  
Note: Please note that the raw data presented in this report has been AI-generated and simulated for demonstration purposes only and does not represent real company data

This Power BI dashboard is a fully-functional, mock version of a real dashboard with similar elements I created for the Government Compliance team, where I manage a database of enterprise government-owned assets that merges together 3 different software environments. These visualizations provide insights into necessary information such as best historical data, asset usage, and asset trends.

![Summary](https://github.com/brookebenator/Enterprise-Asset-Insights-Power-BI/blob/main/Summary.png)
---

**Tools Used**  

-Sunflower: Asset management software  
-Excel  
-Alteryx  
-Power BI  

---

**Power BI Features**    

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

**2. Risk Review:** Housing enterprise assets comes with carrying risk. This page highlights information about asset risk and offers insights about how to protect our assets and business.
	
**3. Asset Detail:** End users can filter by specific part numbers to see their attributes and specific information and history. KPIs show specific information about the part and provides insights to make informed business decisions.

	
---
	
**Business Insights & Real-Life Application**  
1. **Summary Page**:  
	
**● Data Point: How can we forecast an accurate budget to align with asset increases?**  
**Insight**: Asset values typically increase sharply every 5 years. This provides a key insight into how a budget can be created to forecast increasing expenditures. 

**● Data Point: How does asset count and value compare to each other in regards to asset type?**  
**Insight**: The dashboard shows how asset amount and value differ by asset type. Using the button to toggle between viewing the number of assets vs. the dollar amount for each type allows the end user flexibility when viewing this important piece of information.  

**● Data Point: Where are our assets physically located?**  
**Insight**: Determining asset location aids in hiring extra personnel and finding trends within location. Since most assets are clustered around the Atlanta area, it is important to make sure there are enough asset managers and employees.


2. **Risk Review**:
   
**● Data Point: What is the risk distribution of our assets compared to their dollar amount**  
**Insight**: Using a box plot can quickly show the distribution of assets and their risk. Noting the maximum, minumum, and average asset values by risk level can aid in strategic decision making.

**● Data Point: How can risk be mitigated by asset type?**  
**Insight**: High risk assets such as medical equipment and surveillance equipment each have over 1,000 assets that are overdue on calibration. To save costs and reduce risk, it is important this number must decrease to benefit the company. It was also determined there was a massive spike of uncalibrated IT equipment, which is worth diving deeper into how this problem arose and how it can be fixed.  

**● Data Point: What percent of our assets are overdue on calibration? Is there a certain trend when comparing by risk level?**  
**Insight**: Used for an operational visual on the dashboard, the gauges give a quick glance into the health of the enterprise assets. As risk level increases, so does the % of assets that are overdue on calibration. Noting this trend can be used for making effective business decisions such as increasing calibration technicians, automating overdue notifications, and prrocess improvement.

3. **Asset Details**:
   
**● Data Point: Is the selected asset overdue on calibration?**  
**Insight**: Monitoring if an asset is overdue on calibration, in conjunction with its average risk score can help reduce risk and adverse effects such as damages or losses.

**● Data Point: How can we be proactive when it comes to purchasing parts?**  
**Insight**: The cost history visual is great for a quick glance of previous purchasing amounts. For example, if the price of a part has only decreased over time, it is worth noting manufacturers that provide low-cost assets in order to build relationships for future business decisions.

**Feature - Filter Pane**: The filter pane implemented on this dashboard allows the end user to be able to drill further into the information. Being able to filter by Department, Condition, Program, and Manufacturer provides insights into how the assets differ within the enterprise. This filter pane is fully functional, and includes a counter that displays how many filters are applied to the current page. The Clear button also removes all filters, and the X button hides the filter pane.
