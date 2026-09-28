# UBER-RIDE-ANALYTICS
# EXCEL PROJECT

## PROJECT DETAILS

**Name:** Shada
**Topic:** Uber Data Analytics
**Tool Used:** Microsoft Excel
**Data Source:** Kaggle

### Dataset Source

The dataset used for this project was sourced from Kaggle:

**Uber Ride Analytics Dashboard — Yash Dev Laddha**

**Kaggle Dataset Link:**
https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard

---

## PROJECT OVERVIEW

The **Uber Data Analytics** project is an Excel-based data analytics project created to analyze Uber ride-booking data and generate meaningful business insights.

The project follows the complete data analytics workflow:

**RAW DATA → DATA CLEANING → DATA TRANSFORMATION → DATA ANALYSIS → PIVOT TABLES → KPIs → DASHBOARDS → INSIGHTS**

---

## DATASET OVERVIEW

The dataset contains Uber ride-booking information, including:

* Booking ID
* Booking Status
* Vehicle Type
* Booking Value
* Ride Distance
* Payment Method
* Customer Rating
* Driver Rating
* Customer Cancellation
* Driver Cancellation
* Cancellation Reasons
* Incomplete Ride Reasons
* Average VTAT
* Average CTAT
* Date and Time
* Time Period

**Dataset Size:** 150,000 rows

---

## DATA CLEANING

The raw dataset was cleaned and prepared before analysis.

The major cleaning steps included:

* Checked the dataset for duplicate records.
* Checked duplicate Booking IDs.
* Identified and handled missing values.
* Replaced missing **Average VTAT** values with 0.
* Replaced missing **Average CTAT** values with 0.
* Handled missing cancellation-related fields.
* Replaced non-applicable cancellation reasons with **Not Applicable**.
* Created a cleaned **Driver Rating** column.
* Checked and standardized data fields.
* Created a **Time Period** column from the date/time information.
* Categorized bookings into **Morning, Afternoon, Evening, and Night**.
* Validated the cleaned data before analysis.

---

## DATA TRANSFORMATION

**Power Query** was used as part of the data preparation process.

The workflow was:

**Raw Data → Power Query → Cleaning & Transformation → Clean Data → Analysis**

Power Query was used to prepare the dataset for analysis and dashboard creation.

---

## DATA ANALYSIS

The cleaned dataset was analyzed using **Excel Pivot Tables and Pivot Charts**.

The analysis covered:

* Booking status
* Vehicle type
* Booking volume
* Booking value
* Monthly bookings
* Monthly revenue
* Payment methods
* Time periods
* Customer cancellations
* Driver cancellations
* Cancellation reasons
* Customer ratings
* Driver ratings

---

## KEY PERFORMANCE INDICATORS

The Overall Dashboard contains four main KPI cards:

### TOTAL BOOKINGS

**150K**

### COMPLETED RIDES

**93K**

### TOTAL BOOKING VALUE

**₹51.8M**

### COMPLETION RATE

**62%**

---

## DASHBOARDS

The project is organized into five main analytical areas:

### 1. Overall Dashboard
![OVERVIEW DASHBOARD](OVERVIEWDASHBOARD.PNG)
Provides an overall view of:

* Total Bookings
* Completed Rides
* Total Booking Value
* Completion Rate
* Monthly booking trends
* Booking status
* Payment methods
* Time periods
* Key insights

### 2. Vehicle Type Dashboard

Analyzes:

* Bookings by vehicle type
* Vehicle-wise booking performance
* Vehicle-wise booking value
* Comparison between vehicle categories

### 3. Revenue Dashboard

Analyzes:

* Revenue by month
* Revenue by payment method
* Booking value trends
* Revenue contribution

### 4. Cancellation Dashboard

Analyzes:

* Customer cancellations
* Driver cancellations
* Cancellation reasons
* Cancellation patterns

### 5. Ratings Dashboard

Analyzes:

* Driver ratings
* Customer ratings
* Vehicle-wise ratings
* Customer and driver experience

---

## KEY FINDINGS

* **150,000** total bookings were analyzed.
* **93,000** rides were completed.
* Total booking value was **₹51,846,183**.
* Overall completion rate was approximately **62%**.
* **Evening** had the highest booking volume with **60,424 bookings**.
* **Auto** had the highest booking volume with **37,419 bookings**.
* **Auto** generated the highest booking value among vehicle types at **₹12,878,422**.
* **UPI** recorded **45,909 bookings**.
* UPI generated approximately **₹23.35 million** in booking value.
* Average customer rating was **4.40**.
* Average driver rating was **4.23**.

---

## BUSINESS PROBLEMS IDENTIFIED

The analysis highlights areas that require further attention:

* A significant number of bookings were not completed.
* Driver cancellations were observed across several cancellation reasons.
* Customer cancellations were also present.
* Some bookings had no driver found.
* Some rides were classified as incomplete.
* Peak booking periods can create higher demand for available vehicles/drivers.

---

## POSSIBLE BUSINESS ACTIONS

Based on the analysis, possible areas for improvement include:

* Investigating major driver cancellation reasons.
* Monitoring periods with high booking demand.
* Ensuring sufficient driver availability during peak periods.
* Investigating bookings where no driver was found.
* Examining customer cancellation reasons.
* Monitoring incomplete rides.
* Using payment-method trends to understand customer preferences.
* Monitoring vehicle-level ratings and customer experience.

---

## TOOLS USED

### Microsoft Excel

Used for:

* Data cleaning
* Data analysis
* Pivot Tables
* Pivot Charts
* KPI calculations
* Dashboard creation
* Data visualization

### Power Query

Used for:

* Data transformation
* Data cleaning
* Handling missing values
* Standardization
* Preparing the dataset for analysis

---

## PROJECT WORKFLOW

**1. DATA SOURCE**
Kaggle

↓

**2. RAW DATA**
Uber ride-booking dataset

↓

**3. DATA CLEANING**
Duplicate checking → Missing-value treatment → Standardization → Rating & cancellation-field cleaning

↓

**4. DATA TRANSFORMATION**
Power Query → Time Period creation → Data validation

↓

**5. DATA ANALYSIS**
Pivot Tables → KPIs → Aggregations

↓

**6. DATA VISUALIZATION**
Pivot Charts → Dashboard

↓

**7. BUSINESS INSIGHTS**
Booking → Vehicle → Revenue → Cancellation → Ratings

↓

**8. BUSINESS ACTIONS**
Identify problem areas and possible improvements

---

## FINAL OUTCOME

The final outcome of this project is an **Excel-based Uber Data Analytics Dashboard** that transforms raw ride-booking data into meaningful business information.

The project demonstrates practical skills in:

* Data Cleaning
* Power Query
* Excel
* Pivot Tables
* Pivot Charts
* KPI Creation
* Data Visualization
* Dashboard Design
* Business Analysis
* Insight Generation

### Data Source

**Kaggle:**
https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard
