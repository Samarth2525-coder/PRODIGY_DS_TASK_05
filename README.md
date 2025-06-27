📦 1. Importing Libraries & Loading Data
Imports required libraries such as pandas, matplotlib, seaborn for data analysis & visualization, and folium for interactive maps.

Loads the accident dataset using pd.read_csv().

🧹 2. Data Cleaning & Feature Engineering
Drops missing values in critical columns like latitude, longitude, and weather.

Converts Start_Time to datetime format.

Extracts hour, day, month, and year from timestamps for time-based analysis.

⏰ 3. Time-of-Day Accident Analysis
Uses a bar plot to visualize accident frequency by hour of the day.

Helps identify peak hours when most accidents occur (e.g., morning rush, evening traffic).

☁️ 4. Weather Condition Analysis
Shows top 10 most common weather conditions during accidents using a bar chart.

Helps assess how conditions like rain, fog, snow may impact accident frequency.

📅 5. Day of Week Pattern
Visualizes accident distribution across the days of the week (Mon–Sun).

Useful to see if weekends or weekdays have more incidents.

🗺️ 6. Accident Hotspot Heatmap (Using Folium)
Filters accidents to California (or any state) for map clarity.

Plots a heatmap using latitude and longitude of accident locations.

Creates an interactive HTML file to explore high-risk geographic areas.

🌪️ 7. Average Severity by Weather Condition
Calculates the average accident severity (scale 1–4) for each weather type.

Uses a bar plot to show which weather types tend to result in more serious accidents (e.g., fog or snow).

📈 Key Insights Enabled by the Code:
Time Patterns: When (hour/day) accidents are most likely.

Weather Impact: Which weather types are most dangerous.

Hotspots: Where accidents cluster geographically.

Severity Risks: What factors are linked to more severe crashes.

📁 Output Files
An interactive HTML heatmap file (CA_Accident_Heatmap.html) that can be opened in any browser to explore hotspots.

