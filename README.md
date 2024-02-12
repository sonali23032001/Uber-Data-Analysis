I have done data analysis of Uber Data using dataset https://drive.google.com/drive/u/0/folders/1LRCzBJIA61vGfWvID6lqX7Wf1RfdijSu?q=parent:1LRCzBJIA61vGfWvID6lqX7Wf1RfdijSu
Here I have performed the whole analysis using R langauage.


Here is my R code into the 6 phases of data analysis: Ask, Prepare, Process, Analyze, Share, and Act.

### 1. Ask:
- **Objective:** Understand the distribution and patterns in Uber ride data from April to September 2014.
- **Questions:** How do the number of trips vary by hour, day, and month? What are the spatial patterns of Uber rides in New York City?

### 2. Prepare:
- **Data Loading and Cleaning:**
  - Uber ride data for April to September 2014 is loaded from separate CSV files.
  - Date and time columns are converted to appropriate formats.
  - New columns for day, month, year, time, and day of the week are created.

### 3. Process:
- **Temporal Analysis:**
  - Trips are aggregated by hour, day, month, and various combinations.
  - Data is processed to understand the temporal distribution of Uber rides.

- **Spatial Analysis:**
  - Geographical data (latitude and longitude) is plotted on a map to visualize the spatial distribution of Uber rides in New York City.

### 4. Analyze:
1. **Trips Every Hour:**
   - Bar plot illustrates the distribution of trips throughout the day.

2. **Trips by Hour and Month:**
   - Grouped bar plot shows how the number of trips varies by both month and hour.

3. **Trips Every Day:**
   - Bar plot displays the distribution of trips throughout the month.

4. **Trips by Day and Month:**
   - Grouped bar plot illustrates how the number of trips varies by both month and day.
     
5. **Trips in a Month**     
     - Bar plot illustrates how the number of trips varies by each month.
     - 
8. **Heat Map by Hour and Day:**
   - Heatmap visualizes the density of trips based on the combination of hour and day.

9. **Heat Map by Month and Day:**
   - Heatmap visualizes the density of trips based on the combination of month and day.

10. **Heat Map by Month and Day of Week:**
    - Heatmap visualizes the density of trips based on the combination of month and day of the week.

11. **NYC Map Based on Uber Rides:**
    - Maps show the geographical distribution of Uber rides in New York City.

### 5. Share:
- **Communication of Findings:**
  - Graphs, plots, and maps are shared to convey insights regarding temporal and spatial patterns in Uber ride data.
  - Descriptive titles and labels are used for clarity.

### 6. Act:
- **Decision and Action:**
  - Insights gained from the analysis may inform decisions related to Uber operations, marketing strategies, or resource allocation.
  - Identified patterns can guide future actions for optimizing service based on temporal and spatial demand.

### 7. Iterate:
- **Feedback and Continuous Improvement:**
  - Based on the results and actions taken, the analysis process may be refined or expanded in subsequent iterations.
  - Continuous feedback and analysis help in improving the understanding of Uber ride data.


