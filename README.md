# **Online Course Analysis**

### **Data Model** 
The Teacher table is been created to perform a specific instructor related query on the data, so that only that specific data is transformed and filtered. It contains the same columns and the same data.
![](https://github.com/worksakshi/Online-Course-Analysis/blob/main/Data%20Model.PNG)

### **Interactive Dashboard**  
![Insight_1](https://github.com/worksakshi/Online-Course-Analysis/blob/main/image%201.PNG)
![Insight_2](https://github.com/worksakshi/Online-Course-Analysis/blob/main/Image%202.PNG)
![Insight_3](https://github.com/worksakshi/Online-Course-Analysis/blob/main/image%203.PNG)

---

## **Objective**  
To help an EdTech startup identify category-wise trends and strategic opportunities in recorded lectures using a comprehensive, interactive dashboard. This analysis aims to guide content creation, platform accessibility, and instructor collaborations based on data-driven insights.


### **Key Features**   
1. **Course Type Trends**
Analyzed course vs. specialization distribution across categories to reveal learner preferences and support informed content launch decisions.
2. **Average Viewership Analysis**
Calculated average views by category, sub-category, and language to understand viewer engagement and tailor content strategies accordingly.
3. **In-Demand Skills by Category**
Identified the most commonly taught and trending skills in each category, helping the company stay aligned with industry and job market demand.
4. **Language Distribution**
Visualized how different languages are used across courses and which categories favor which languages, helping optimize course accessibility.
5. **Top 5 Categories – Language Preferences**
Focused analysis on the five highest-performing categories based on user views to map viewer language preferences and course accessibility needs.
6. **Subtitle Impact on Views**
Analyzed the correlation between the number of subtitles and average views to determine if subtitle availability influences engagement.
7. **Top Instructors by Ratings (Static View)**
Highlighted the top three instructors per category and sub-category based on learner ratings, identifying key educators to potentially collaborate with.
8. **Course Duration vs. Engagement**
Explored how course length affects viewership. Adjusted duration for monthly content (60 hours/month) and flexible scheduling (200 hours).
9. **Skill Variety vs. Viewership**
Investigated whether the number of different skills offered in a category/sub-category affects viewer interest and total views.

### **Technology Stack**  
- **Data Sources:**  CSV 
- **Tools:** Power BI, Power Query, DAX.  

### **Execution Steps**  

1. **Data Modeling**: Built a star schema with factEcommerce as the central table, ensuring referential integrity through one-to-many relationships.
2. **Data Cleaning & Transformation**: Cleaned data using Power Query, standardized naming, and ensured data types and keys were consistent.
3. **Visualization**: Developed multi-page reports with performance metrics, including maps for regional analysis and charts for payment trends.
4. **Image Mapping**: Merged product and country flag images using Product ID and Country as keys, allowing for enriched visuals.
5. **Time Intelligence**: Used the Calendar table to support YoY and MoM growth analysis.
6. **User Experience Design**: Included bookmarks for better usability.



## **Impact**  

The dashboard provides clear and actionable insights into sales, profits, and product performance, enabling the XGRIP team to make data-driven decisions. It offers users a visually appealing interface with interactive features and seamless data updates, significantly improving the efficiency of business reporting and analysis.

---

## **Key Learnings**  
1. Importance of a clean, star-schema data model for high performance in Power BI.
2. Techniques for using DAX to calculate time-based metrics and profit-related KPIs.
3. How to integrate external media like product and flag images dynamically.




   
