### Uber Trips Data Analysis — Exploring Ride Patterns and Operational Insights

### Objective:
To analyze Uber trip data to identify ride trends, customer behavior, and operational insights that can help optimize performance, driver allocation, and customer experience.

### Project Overview:
The intern will work with historical Uber trip data to uncover insights about ride frequency, locations, time-based demand, and other performance metrics. The analysis will focus on discovering key business trends and presenting them through data visualization and dashboards.

#### Files in the Project
1. **Uber Trips Data.csv**: The original dataset containing raw Uber ride data.
2. **Uber Trips Data Cleaned.csv**: The cleaned dataset after preprocessing.
3. **Dashboard.png**: An image file showing the dashboard visualizing the analysis results.

#### Analysis Steps
1. **Importing Libraries**:
   - Used pandas for data manipulation, numpy for numerical operations, matplotlib.pyplot and seaborn for data visualization.

2. **Loading the Dataset**:
   - Loaded the Uber dataset from a CSV file and displayed the first 10 rows to understand its structure.

3. **Basic Data Exploration**:
   - Generated summary statistics, concise data summary, checked for missing values, duplicate rows, and unique values in each column.

4. **Handling Missing Values**:
   - Filled missing values in the 'PURPOSE' column using forward fill method.

5. **Converting Date Columns**:
   - Converted 'START_DATE' and 'END_DATE' columns to datetime format.

6. **Extracting Date and Time Components**:
   - Extracted date, time, month, and year from 'START_DATE' and 'END_DATE' columns and added these as new columns.

7. **Dropping Original Date Columns**:
   - Dropped 'START_DATE' and 'END_DATE' columns and rearranged the remaining columns.

8. **Handling Missing Values in 'Month' and 'Year' Columns**:
   - Filled missing values in the 'month' and 'year' columns using the mode and converted them to integer type.

9. **Extracting Hour and Minute Components**:
   - Extracted hours and minutes from 'start_time' and 'end_time' columns and added them as new columns.

10. **Calculating Duration**:
    - Calculated the duration of each trip in minutes and added it as a new column.

11. **Plotting Data**:
    - Visualized the data using various plots like heatmap for correlations, count plots, bar plots, and distribution plots to understand the patterns and distributions in the data.

12. **Saving Cleaned Data**:
    - Saved the cleaned and processed DataFrame to a new CSV file.

#### Dashboard Insights
The dashboard visualizes key insights from the analysis:
1. **Revenue by Month**: Display the Revenue for each Month.
2. **Fare (INR) by Month**: Displays Fare (INR) for each month.
3. **Trips by Weekday**: Show the Number of Trips Per Weekdays.
4. **Fare (INR) by Vehicle Type**: Display the Fare (INR) by Vehicle Type.
5. **Trips by Payment Type**: Show the Payment Type for Trips.
6. **Trips by Drop Zone**: Show the Top 10 Drop Zone in Pichart.
7. **Pickup Zone**: display the pichup Zone in the Map.

#### Recommendations
Based on the analysis, the following recommendations are made:
1. **Optimize Trip Allocation During Peak Months**.
2. **Target Marketing Campaigns by Purpose**.
3. **Improve Services During Peak Hours**.
4. **Monitor and Reduce Trip Duration**.
5. **Enhance Services in High-Demand Categories**.
6. **Seasonal Promotions**.
7. **Analyze High-Mileage Trips**.
8. **Focus on Popular Routes and Destinations**.
9. **Customer Feedback Integration**.
10. **Driver Training Programs**.

By implementing these recommendations, Uber can enhance its operational efficiency, improve customer satisfaction, and increase overall ridership.

#### How to Use This Project
1. Load the provided CSV files (`Uber Trips Data.csv` and `Uber Trips Data Cleaned.csv`) into a pandas DataFrame.
2. Follow the documented steps to understand the data cleaning and preprocessing process.
3. Review the dashboard (`Dashboard.png`) to gain insights from the visualized data.

#### Author
- Suriyaprakash - itssuriyas@gmail.com

Feel free to reach out to any of the collaborators for questions or further information regarding the project.

#### Steps for Cloning the Project
1. **Clone the Repository**:
   ```
   git clone 
   ```
2. **Navigate to the Project Directory**:
   ```
   cd uber_trips_data_analysis
   ```
3. **Install the Required Libraries**:
   ```
   pip install -r requirements.txt
   ```
4. **Run the Jupyter Notebook**:
   ```
   jupyter notebook Uber_Trips_Data_Analysis.ipynb
   ```

## Sample of Dashboard
<img src= "Dashboard.png">

### Final Deliverables:
1.	Cleaned and documented Uber trips dataset
2.	EDA summary with charts and statistical insights
3.	Interactive dashboard showcasing trends and metrics
4.	Analytical report or presentation deck with insights and recommendations