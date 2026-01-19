🎬 Netflix Global Content Analysis Dashboard

📌 Project Overview

This project transforms the raw Netflix Movies and TV Shows dataset into a professional, interactive Business Intelligence dashboard. The goal is to provide a comprehensive look at how Netflix has evolved its content library, targeted specific audiences, and expanded its global footprint.

📊 Key Dashboards & Insights
The final report is designed with a Z-pattern layout for optimal readability, featuring:

1. Executive Summary (KPIs)

*Library Size: Total titles currently available on the platform.

*Content Split: A Doughnut Chart showing the percentage ratio between Movies and TV Shows.

*Content Growth: An Area Chart tracking the massive surge in Netflix releases from 1920 to the present day.

2. Global Strategy

*Geographical Map: A dark-themed bubble map visualizing content production by country.

*Top 10 Genres: A clustered bar chart identifying the most popular categories, led by International Movies and Dramas.

3. Audience Demographics

*Ratings Treemap: A filtered view of the Top 5 Audience Ratings (TV-MA, TV-14, etc.), showing that Netflix heavily prioritizes mature adult audiences over kids' programming.

🛠️ Technical Implementation

*Data Cleaning (Power Query): 

* Fixed "column shifting" errors (e.g., removing misplaced director names from the Type category).

Handled null values in director, cast, and country columns.

*DAX Measures: Created custom measures for Total Titles, Total Movies, and Total TV Shows to power dynamic KPI cards.

*UI/UX Design: 
    
    * Implemented a custom Netflix Brand Theme using Hex Codes: Red (#E50914) and Charcoal (#141414).
    
    * Utilized Top N Filters to reduce visual clutter in the Treemap.
    
    * Integrated Interactive Slicers for Year Range and Content Type.

💡 Strategic Conclusions

*Series-First Strategy: While Movies dominate in volume, the growth rate of TV Shows has increased significantly since 2015 to drive user retention.

*Global Hubs: Outside of the US, India and South Korea have emerged as the primary engines for international content growth.

*Adult-Centric Brand: Netflix has successfully branded itself as a destination for mature content, with TV-MA being the most prevalent rating across all regions.

🚀 How to View

*Tools Used: Power BI Desktop, Power Query, DAX.

*Dataset: Netflix Movies and TV Shows (Kaggle).

*Interactivity: Click on any bubble on the map or a slice of the doughnut chart to cross-filter the entire dashboard.