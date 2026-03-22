#  Netflix Content Analysis Dashboard (Power BI)

##  Objective
To analyze Netflix’s content catalog and uncover patterns in content distribution, audience targeting, and content quality using IMDb-based metrics.

---

##  Tools Used
- Power BI  
- Excel 

---

##  Dataset
Netflix Movies & TV Shows dataset  
  

---

##  Dashboard Preview

###  Catalog Overview
![Catalog](Dashboards/Catalog%20Overview.png)

###  Content Quality & Trust
![Quality](Dashboards/Content%20Quality.png)

###  Patterns & Segments
![Patterns](Dashboards/Patterns%20%26%20Segments.png)

###  Insights Over Time
![Time](Dashboards/Timely%20Insights.png)

---

##  Key Insights
- Movies dominate the platform compared to TV Shows  
- Majority content falls into the **“Mid-age” bucket (5–15 years old)**  
- IMDb scores are more reliable for content with higher vote counts  
- Teen and Adult categories have slightly higher average ratings  
- Content growth surged post-2000, followed by stabilization  

---

##  Data Modeling & Transformations

###  Calculated Columns
- Created **content age** and categorized into New / Mid / Old  
- Classified IMDb reliability based on vote threshold  
- Segmented audience into Kids, Teen, Adult, and Unrated  
- Grouped runtime into Short, Medium, and Long  
- Built a **popularity index** combining score and votes  

 

---

###  Key Measures (DAX)
- Average IMDb Score (Reliable content only)  
- Weighted IMDb Score (based on votes)  
- Total content count  
- Average runtime  


---





