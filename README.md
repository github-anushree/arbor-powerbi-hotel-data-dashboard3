Hotel Operations and Revenue Insights – Power BI Dashboard
📘 Project Overview

This Power BI project provides an end-to-end data analytics solution for hotel operations — from data cleaning and transformation in Power Query to insightful visualizations that drive business decisions.

The dashboard helps hotel management teams monitor booking performance, revenue, ratings, and room type trends across different locations.

🧠 Objectives

Analyze hotel bookings and cancellations.

Compare performance across multiple hotel locations.

Track average ratings, revenue, and booking status.

Identify most popular room types and pricing trends.

Build an interactive and visually appealing dashboard in Power BI.

⚙️ Data Source

File Name: arbor_powerbi_hotel_data.xlsx

Data Fields:

HotelID

HotelName

Location

RoomType

Rating

PricePerNight

BookingStatus

CheckInDate

🧹 Data Transformation (Power Query Steps)

Loaded the dataset from Excel into Power BI.

Inspected data quality using column profiling (valid, error, empty).

Removed duplicates and unnecessary spaces.

Replaced invalid entries like N/A or blanks with null.

Converted data types:

Rating and PricePerNight → Decimal

CheckInDate → Date (using try ... otherwise null to fix conversion errors)

Created calculated columns and measures for KPIs:

Total Bookings

Total Revenue

Average Daily Rate (ADR)

Average Rating

Cancellation Rate

📊 Dashboard Features

The Hotel Operations and Revenue Insights Dashboard includes:

🔹 KPI Cards

Total Revenue

Total Bookings

Average Daily Rate (ADR)

Average Price Per Night

Average Rating

🔹 Visuals Used
Visualization	Description	Columns Used
Bar Chart	Count of bookings by location	Location, HotelID
Bar Chart	Bookings by hotel	HotelName, HotelID
Column Chart	Average price per room type	RoomType, PricePerNight
Bar Chart	Average rating by hotel	HotelName, Rating
Donut Chart	Room type popularity	RoomType
Pie Chart	Booking status breakdown	BookingStatus
Slicers	Location, RoomType, BookingStatus, Month	For interactive filtering
🧮 Key Insights

New York had the highest number of bookings, followed closely by Miami.

Deluxe rooms are the most popular, contributing 40% of total bookings.

The Average Daily Rate (ADR) is $152.50, indicating premium pricing.

50% of bookings were confirmed, 29% cancelled, and 21% pending.

Mountain Inn achieved the highest rating (4.6) and leads in confirmed bookings.

💡 Tools & Technologies

Microsoft Power BI (Desktop)

Power Query Editor

DAX (Data Analysis Expressions)

Excel (for initial dataset)

🏁 End-to-End Workflow

Data collection (Excel file)

Data cleaning & transformation (Power Query)

Data modeling & relationships

KPI creation using DAX

Dashboard design & visualization

Insights interpretation and storytelling

🧭 Key Learnings

Handling date conversion errors in Power Query using try...otherwise.

Creating clean, dynamic visuals with consistent themes.

Building DAX measures for revenue, booking counts, and averages.

Designing dashboards for both aesthetics and decision support.


⭐ How to Use

Clone this repository.

Open the .pbix file in Power BI Desktop.

Load your own dataset (optional) to replicate the analysis.

Explore interactive filters to analyze insights dynamically.

💬 Feedback

If you found this helpful, please ⭐ the repo and connect with me on LinkedIn!
Your feedback helps me improve future analytics projects.
