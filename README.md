# Cyclistic-analysis
Cyclistic Bike-Share Analysis: How Does a Bike-Share Navigate Speedy Success?🚴‍♀️
https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white
https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=RStudio&logoColor=white
https://img.shields.io/badge/tidyverse-1A162D?style=for-the-badge&logo=tidyverse&logoColor=white
📋 Project Overview
This project analyzes bike-share usage data from Cyclistic, a fictional bike-share company in Chicago, to understand the differences between casual riders and annual members. The goal is to provide data-driven recommendations for converting casual riders into annual members.
Business Question: How do annual members and casual riders use Cyclistic bikes differently?
🎯 Key Findings

Usage Patterns: Annual members use bikes more frequently for commuting (weekday peaks), while casual riders use them more on weekends for leisure
Ride Duration: Casual riders take longer trips on average, suggesting recreational use
Seasonal Trends: Both groups show increased usage during summer months, with different peak patterns
Strategic Recommendation: Target marketing campaigns during summer weekends when casual riders are most active

🛠️ Tools & Technologies

R - Data analysis and visualization
RStudio - Development environment
tidyverse (dplyr, ggplot2, lubridate) - Data manipulation and visualization
R Markdown - Reproducible reporting

📊 Dataset

**Data Files:**
- Due to file size limitations, data files are not included in this repository
- Download the original data: [Divvy Trip Data](https://divvy-tripdata.s3.amazonaws.com/index.html)
- Files used: `Divvy_Trips_2019.csv`, `Divvy_Trips_2020_Q1.csv`
  
The analysis uses Cyclistic trip data from 2019-2020:

Source: Divvy Trips historical data
Time Period: Q1 2019 - Q1 2020
Size: ~3.8 million rides
Key Variables: Ride ID, start/end times, station locations, user type

Note: Cyclistic is a fictional company. The data is based on the real Divvy bike-share program in Chicago.
📁 Repository Structure
cyclistic-analysis/
├── README.md                          # Project overview (this file)
├── Cyclistic_analysis.Rmd             # R Markdown analysis file
├── Cyclistic_analysis.html            # HTML output report
├── Case_Study_1_speedy_success.pdf    # Presentation/summary
├── data/                              # Data files
│   ├── Divvy_Trips_2019.csv
│   └── Divvy_Trips_2020_Q1.csv
└── images/                            # Visualizations (optional)
🔍 Analysis Process

Ask - Define the business problem and stakeholder expectations
Prepare - Collect and organize the data
Process - Clean and transform data for analysis
Analyze - Identify patterns and trends
Share - Create visualizations and communicate findings
Act - Provide actionable recommendations

📈 Key Visualizations
The analysis includes:

Ride frequency by user type and day of week
Average ride duration comparisons
Seasonal usage patterns
Geographic distribution of popular stations
Time-of-day usage patterns

💡 Business Recommendations

Weekend Marketing Campaigns: Focus digital campaigns on Friday-Sunday when casual riders are most active
Summer Promotions: Launch special membership offers during peak summer months (June-August)
Leisure-Focused Messaging: Emphasize flexibility and convenience for weekend recreational use
Station-Based Targeting: Focus on popular tourist and recreational stations with high casual rider usage

🚀 How to Run This Analysis

Clone this repository
Ensure you have R and RStudio installed
Install required packages:

rinstall.packages(c("tidyverse", "lubridate", "ggplot2"))

Open Cyclistic_analysis.Rmd in RStudio
Click "Knit" to generate the HTML report

📝 About This Project
This case study is part of the Google Data Analytics Professional Certificate capstone project. It demonstrates skills in:

Data cleaning and preparation
Exploratory data analysis
Data visualization
Business insight generation
Stakeholder communication

👩‍💻 Author
Silvia Navío Luque

📧 silvianavioluque@gmail.com
🌐 Portfolio: github.com/SILNALU

📄 License
This project is open source and available under the MIT License.

⭐ If you found this project helpful, please consider giving it a star!
