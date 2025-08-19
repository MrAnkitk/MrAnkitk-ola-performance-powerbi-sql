🚖 Ola Rides Analysis – Power BI Dashboard

Analyzing ride patterns, cancellations, payments, and customer behavior from Ola ride-hailing data (July 2024). This project demonstrates how data visualization + business intelligence can uncover insights to improve operations and customer experience.

📌 Table of Contents

Overview
Business Problem
Dataset
Tools & Technologies
Project Structure
Data Cleaning & Preparation
Exploratory Data Analysis (EDA)
Research Questions & Key Findings
Dashboard
How to Run This Project
Final Recommendations
Author & Contact

📝 Overview
This project evaluates ride bookings, cancellations, payment methods, and customer loyalty for Ola. The analysis highlights areas to improve driver allocation, reduce cancellations, and strengthen customer satisfaction.

A complete workflow was developed using Power BI for dashboarding and insights storytelling.

❓ Business Problem

Ride-hailing companies face challenges like high cancellations, unreliable drivers, and fragmented payment adoption. This project answers:

What % of rides end successfully vs cancelled?

What are the top cancellation reasons (driver vs customer)?

Which payment methods contribute most to revenue?

Who are the top customers driving loyalty and repeat bookings?

How stable are driver ratings across the month?

📂 Dataset

Period: 01 July – 30 July 2024

Total Bookings: 40,539

Total Revenue: ₹14M

Fields include: Booking ID, Booking Status, Payment Method, Ride Distance, Customer ID, Driver Rating, etc.

🛠 Tools & Technologies

Power BI (DAX, Data Modeling, Dashboards)

Excel/CSV (Raw Data Source)

GitHub (Project Repository & Documentation)

📁 Project Structure
ola-rides-analysis/
│
├── README.md
├── ola-rides-report.pdf           # Project summary report
├── dashboard/                     # Power BI Dashboard
│   └── ola_rides_dashboard.pbix
├── data/                          # Sample dataset (if shareable)
└── images/                        # Screenshots of dashboard visuals

🧹 Data Cleaning & Preparation

Removed duplicate bookings and null values

Standardized date & time format

Categorized booking status into Success, Cancelled by Driver, Cancelled by Customer, Driver Not Found

Calculated KPIs: Success Rate, Cancellation Rate, Avg Rating, Revenue per Customer

🔎 Exploratory Data Analysis (EDA)

Booking Status Distribution

Revenue by Payment Method

Ride Distance Patterns over time

Top Customers by Value

Driver & Customer cancellation reasons

📊 Research Questions & Key Findings

1️⃣ Total Bookings – 40,539 | Revenue – ₹14M
2️⃣ Booking Status – 62% Success | 28% Cancelled | 10% Driver Not Found
3️⃣ Cancellations – Driven by driver personal issues & customer plan changes
4️⃣ Payments – UPI & Credit Cards dominate, Cash still significant
5️⃣ Top Customers – 5 customers alone contributed ~₹19.5K
6️⃣ Ratings – Stable at ~4.0 → indicates reliable service perception

📊 Dashboard

The Power BI dashboard provides:

Booking Status Overview

Cancellation Breakdown (Driver vs Customer)

Revenue by Payment Method

Ride Distance Trends

Top Customers & Loyalty Indicators

Driver Ratings over time

📸 (Add dashboard screenshots here from /images)

▶️ How to Run This Project

Clone the repository:

git clone https://github.com/yourusername/ola-rides-analysis.git


Open the dashboard file:

dashboard/ola_rides_dashboard.pbix


Explore filters, slicers, and KPIs in Power BI Desktop.

✅ Final Recommendations

Driver Allocation – Address frequent cancellation reasons with better driver management

Customer Loyalty – Reward top customers through targeted offers

Payments – Promote digital payments to reduce cash dependency

Cancellation Reduction – Improve real-time driver tracking and customer communication

Operational Insights – Use data to optimize ride distribution during weekends & peak hours

👤 Author & Contact

Ankit Kumar
Data Analyst | Power BI Developer
📧 Email: (Add your email)
🔗 [LinkedIn](Add your link)
🔗 [Portfolio / GitHub](Add link)
