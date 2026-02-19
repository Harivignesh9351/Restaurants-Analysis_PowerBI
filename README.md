Zomato Restaurant Analysis

📌 Project Overview Zomato is a restaurant search and discovery service that operates in several countries worldwide. This project aims to analyze Zomato's restaurant data to identify trends and insights, helping stakeholders understand their business performance better.

🎯 Business Requirements The primary objectives of this analysis are:

Identify the total number of restaurants across continents, countries, and cities.
Enable both global and granular-level analysis of restaurants.
Rank top-performing restaurants based on customer ratings.
Identify top restaurants based on affordability (least average cost).
Provide filtering capabilities based on:
Continent, country, and city
Services like online delivery or table booking
Average rating categories
Identify restaurants with the highest number of cuisines served.
Create a multi-page Power BI report with easy navigation.
Ensure the report is accessible via web browsers and mobile devices.
🛠 High-Level Steps

Data Import: Load restaurant data from multiple Excel files.
Data Transformation: Clean and preprocess the data (fix city names, remove unused columns, create new tables, etc.).
Data Modeling: Define relationships between tables, ensuring correct cardinality and filter directions.
Data Manipulation: Categorize geographic columns, create user-defined hierarchies, and group countries into continents.
Using DAX (Data Analysis Expressions):
Define a "Rating Color" column based on the rating scale.
Create measures like Restaurant Count, Average Cost, Average Rating, and Cuisine Count.
Map countries to continents.
Data Visualization: Develop interactive Power BI reports with:
Cards displaying key metrics (Average Cost, Average Rating, Restaurant Count)
Maps showing restaurant distribution
Slicers for filtering data
Infographic designer visuals for top restaurants
Gauges to visualize restaurant ratings and costs
Navigation buttons for an intuitive user experience
Publishing & Accessibility:
Publish the report On netlify
🏗 Dataset Details The dataset consists of multiple Excel files containing restaurant information across different continents. Key tables include:

Restaurant Data: Restaurant name, address, city, country, cuisines, average cost, rating, etc.
Geographic Data: Country codes and continent mappings.
Fact Table: Aggregated restaurant-related metrics.
🖥 Tools & Technologies Used

Power BI (for data visualization and reporting)
Excel (for data storage and preprocessing)
DAX (for calculations and aggregations)
