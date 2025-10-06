# Airline-Flights-Analysis-Python-
This project involves an end-to-end data analysis workflow, focusing on a real-world structured dataset containing flights booking details. Utilizing core Python libraries, this analysis explores operational trends, price variations, and customer booking behaviors within the Indian aviation domain

# Project Goal
The primary goal of this project is to analyze a comprehensive flights booking dataset to uncover actionable insights regarding pricing strategies, operational logistics, and the factors influencing ticket costs, which is highly relevant for those working in the airlines, travel, or aviation domains.

# Tools & Techonology 
The entire analysis was performed in a Jupyter notebook environment, leveraging essential Python data science libraries:

Pandas (pd): Used extensively for data manipulation, cleaning (removing the unnecessary index column), statistical summaries (describe()), filtering, and grouping data (groupby).


NumPy (np): Imported for numerical operations.


Matplotlib (plt): Used to create various visualizations, including bar graphs and subplots, to show frequencies of airlines and flight timings.


Seaborn (sns): Utilized for drawing advanced categorical plots (catplot) and relational plots (relplot) to analyze price variations across airlines, classes, and cities

# Key Analytical Insights
The project successfully addressed several business questions through data cleaning, exploratory data analysis (EDA), and advanced filtering:

1. Inverse Price-Lead Time Correlation: Identified a substantial inverse correlation between booking lead time and price. Tickets booked just 1 to 4 days before departure incurred the highest mean prices (₹30,000 for 2 days left), while tickets booked 49 days in advance averaged lower prices ₹18,000.

2. Airline Price Benchmarking: Statistical analysis revealed significant price variance across airlines. Vistara Airlines maintained the maximum mean ticket price ₹30,000, whereas Air Asia offered the lowest mean price ₹4,917.

3. Operational Dominance: Using frequency counts and visualizations, the analysis established Vistara as the top airline by flight volume (over 127,000 flights). Delhi was identified as the principal source city (61,000+ flights) and Mumbai as the primary destination city.

4. Class Price Disparity: Discovered a massive pricing gap between travel classes, with the mean ticket price for Business Class averaging ₹52,540 compared to Economy Class at ₹6,572.

5. Niche Market Pricing: Applied advanced multi-conditional filtering across four parameters (Airline, Source, Destination, Class) to calculate the specific average ticket price for a Vistara business class flight from Delhi to Hyderabad, which averaged ₹47,939
