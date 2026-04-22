🚦 Indian Road Accident Analytics Dashboard
A data analytics project built using Power BI to explore, clean, and visualize road accident patterns across major Indian states from 2022 to 2025.

📌 Project Overview
Road accidents are a major public safety concern in India. This project analyzes a dataset of ~20,000 road accident records across 7 states to uncover patterns related to:

Accident severity and causes
Weather and visibility conditions
Road types and traffic density
Monthly and yearly trends
State-wise comparisons

The goal is to turn raw data into meaningful visual insights that can help understand where, when, and why accidents happen.

📁 Files in This Repository
FileDescriptionindian_roads_dataset.csvRaw/cleaned dataset with ~20,000 accident recordsINDIA_Pbi.pbixPower BI dashboard file (2 pages of visuals)P3.pngScreenshot – Dashboard Page 1 (Overview)P4.pngScreenshot – Dashboard Page 2 (Trends)README.mdProject documentation (this file)

📊 Dataset Description
The dataset contains 20,000 rows and 24 columns covering accidents across Delhi, Maharashtra, Karnataka, Punjab, Tamil Nadu, Telangana, and West Bengal.
Key Columns
ColumnDescriptionaccident_idUnique ID for each accidentcity, stateLocation of the accidentlatitude, longitudeGPS coordinatesdate, time, hourWhen the accident occurredday_of_week, is_weekendDay contextroad_typeHighway / Urban / RuralweatherClear / Fog / RainvisibilityLow / Medium / HightemperatureTemperature at the time (°C)traffic_densityLow / Medium / HighcauseDistraction / Overspeeding / Drunk Driving / Poor Road / Weatheraccident_severityMinor / Major / Fatalvehicles_involvedNumber of vehiclescasualtiesNumber of casualtiesis_peak_hourWhether accident occurred during peak hoursfestivalFestival period (if any)risk_scoreComputed risk score (0 to 1)

🧹 Data Cleaning Steps
The following cleaning steps were performed before building the dashboard:

Checked for null/missing values across all 24 columns
Standardized date format — converted date column to a consistent DD-MM-YYYY format
Verified data types — ensured numeric columns (latitude, longitude, temperature, risk_score) were correctly typed
Validated categorical columns — confirmed consistent values in road_type, weather, accident_severity, cause, visibility, and traffic_density
Removed duplicates — verified accident_id uniqueness
Derived columns used in Power BI — month, year, extracted from date for time-series visuals


📈 Dashboard Pages
Page 1 — Overview Dashboard
Show Image
Key Visuals:

KPI Cards — Total Accidents (20K), Fatal % (0.15), Average Casualties (1.73), Sum of Casualties (35K)
Cause Filter — Slicer to filter by accident cause (distraction, drunk driving, overspeeding, poor road, weather)
Road Type Filter — Slicer to filter by road type
State Filter — Checkbox slicer for all 7 states
Map Visual — Geographical distribution of accidents across India by state
Bar Chart — Total Accidents by Accident Severity (Minor: 11K, Major: 6K, Fatal: 3K)
Bar Chart — Count of Accidents by Number of Casualties
Stacked Bar Chart — Total Accidents by Visibility and Weather condition (clear / fog / rain)


Page 2 — Trend Analysis Dashboard
Show Image
Key Visuals:

Area Chart — Total Accidents by Year (2022–2025), showing a declining trend toward 2025
Pie Chart — Total Accidents by Road Type (Urban: 33.73%, Highway: 33.08%, Rural: 33.2%) — nearly equal distribution
Horizontal Bar Chart — Count of Accident Severity by State (Maharashtra leads with 5K, followed by Punjab, Tamil Nadu, West Bengal at ~2.6K each)
Line Chart — Total Accidents by Month — peaks in January/February and April, drops through mid-year


🔍 Key Insights

Maharashtra records the highest number of accidents among all states (~5,000)
Minor accidents are the most common (11K out of 20K total)
The Fatal % is 15%, meaning roughly 1 in 7 accidents results in fatalities
Accidents are nearly equally distributed across Urban, Rural, and Highway road types (~33% each)
Low visibility + fog conditions are strongly associated with higher accident counts
Accidents peak in early months (January–April) and decline through mid-year
Year-over-year, total accidents show a downward trend from 2022 to 2025
Distraction and Overspeeding are among the top recorded causes


🛠️ Tools Used
ToolPurposePower BI DesktopData cleaning, modeling, and dashboard creationMicrosoft Excel / CSVRaw data storage and initial reviewPower Query (within Power BI)Data transformation and column derivation

🚀 How to Use This Project
View the Dashboard (No Installation Needed)

Open P3.png and P4.png to view the dashboard screenshots directly.

Open the Power BI File

Download and install Power BI Desktop (free)
Clone or download this repository
Open INDIA_Pbi.pbix in Power BI Desktop
The dashboard will load with all visuals and slicers ready to use
Use the State, Cause, and Road Type slicers to filter data interactively

Explore the Dataset

Open indian_roads_dataset.csv in Excel, Python (pandas), or any data tool
The dataset is clean and ready for further analysis


📂 Folder Structure
indian-road-accident-analytics/
│
├── INDIA_Pbi.pbix              # Power BI file
├── P3.png                      # Dashboard screenshot - Page 1
├── P4.png                      # Dashboard screenshot - Page 2
├──  README.md                   # This file
└── indian_roads_dataset.csv    # Dataset

🙋 About This Project
This project was created as a data analytics exercise focused on:

Practicing data cleaning in Power BI / Power Query
Building interactive dashboards with filters and KPI cards
Deriving insights from real-world public safety data

Feel free to fork this repository, explore the data, or extend the dashboard with additional visuals!

📬 Contact
If you have questions or suggestions, feel free to open an Issue or reach out via GitHub.

Made with ❤️ using Power BI
