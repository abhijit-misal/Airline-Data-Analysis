# ✈️ Airline Data Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing airline flight data using Python and data visualization libraries. The main objective is to explore flight information, understand ticket price variations, compare airlines, and identify patterns based on travel-related factors.

Exploratory Data Analysis (EDA) is performed to understand the dataset and discover useful insights about airline ticket prices.

## 🎯 Objectives

- Analyze the number of flights operated by different airlines.
- Explore departure and arrival time distributions.
- Analyze flight frequency across source and destination cities.
- Compare average ticket prices across airlines.
- Understand how ticket prices vary by departure and arrival time.
- Compare ticket prices for different source and destination cities.
- Analyze the relationship between ticket prices and days left before departure.
- Compare Economy and Business class ticket prices.
- Filter flights based on specific airline, route, and travel class.

## 🛠️ Technologies Used

- **Python** – Data analysis and programming
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Interactive analysis

## 📂 Project Structure

```text
Airline-Data-Analysis/
│
├── Airline_Analysis.ipynb
├── airlines_flights_data.csv
└── README.md
```

## 📊 Analysis Performed

### 1. Data Loading and Exploration
- Loaded the airline dataset using Pandas.
- Examined dataset information and descriptive statistics.
- Viewed sample records using `head()`.
- Checked missing values using `isnull().sum()`.

### 2. Airline Analysis
- Identified the number of unique airlines.
- Listed airlines available in the dataset.
- Analyzed flight counts for each airline.
- Visualized airline frequencies using a horizontal bar chart.

### 3. Departure and Arrival Time Analysis
- Analyzed the distribution of departure times.
- Analyzed the distribution of arrival times.
- Created bar charts to compare time-category frequencies.
- Examined average ticket prices by departure and arrival time.

### 4. Source and Destination City Analysis
- Explored flight counts by source city.
- Explored flight counts by destination city.
- Compared average ticket prices across cities.
- Used visualizations to examine city-wise price patterns.

### 5. Airline Ticket Price Analysis
- Calculated average ticket prices for each airline.
- Compared prices across Economy and Business classes.
- Used Seaborn bar plots to visualize price differences.

### 6. Days Left Before Departure
- Examined the different values in the `days_left` column.
- Calculated average ticket prices for different booking lead times.
- Used a line plot to visualize price variation with days left before departure.

### 7. Economy vs Business Class
- Filtered Economy class flights and calculated their average price.
- Filtered Business class flights and calculated their average price.
- Compared the two travel classes.

### 8. Conditional Filtering
Filtered flights based on multiple conditions:

- Airline: Vistara
- Source city: Delhi
- Destination city: Hyderabad
- Class: Business

Calculated the average ticket price for the filtered records.

## 🔍 Key Questions Explored

- Which airlines have the highest number of records in the dataset?
- How are flights distributed across departure and arrival times?
- Which source and destination cities have more flight records?
- How do average ticket prices differ between airlines?
- How does ticket price vary with days left before departure?
- How do Economy and Business class prices compare?
- What is the average price for a selected airline and route?

## 💡 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data cleaning and initial data inspection
- Data filtering and conditional selection
- Grouping and aggregation using `groupby()`
- Statistical summaries using `describe()` and `mean()`
- Missing-value inspection
- Data visualization using Matplotlib and Seaborn
- Extracting insights from structured datasets

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/Airline-Data-Analysis.git
   ```

2. Open the project folder:

   ```bash
   cd Airline-Data-Analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Place the `airlines_flights_data.csv` file in the project folder.

5. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `Airline_Analysis.ipynb` and run the cells.

## 📁 Dataset

The project uses `airlines_flights_data.csv`, containing flight-related information such as airline, departure time, arrival time, source city, destination city, class, duration, days left, and price.

**Note:** Upload the dataset to the repository only if you have permission to share it.

## 📌 Conclusion

This project demonstrates how Python can be used to explore airline flight data, compare ticket prices, analyze flight distributions, and visualize patterns across airlines, cities, travel classes, and booking lead times.

It helped develop practical skills in data analysis, Pandas, and data visualization.

## 👨‍💻 Author

**Abhijit Misal**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

