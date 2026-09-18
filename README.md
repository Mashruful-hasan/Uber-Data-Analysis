# Uber Data Analysis using Power BI

An interactive Power BI dashboard analyzing Uber ride booking data — covering revenue, bookings, ratings, cancellations, and location-based trends across multiple report pages.


## 1. Overview Page

**KPIs (Key Performance Indicators)**
1. Completed Bookings
2. Lost Bookings
3. Revenue
4. Total Distance
5. Avg Distance

**Features**
- Filter for Vehicle Type
- Monthly Analysis — Bookings Completed, Revenue
- Quarterly Analysis — Bookings Completed, Revenue
- Revenue by Vehicle Type
- Top Drop and Pickup Locations based on booking count
- Ratings — Avg Rider Rating, Avg Driver Rating

## 2. Vehicle Page

- Detailed information by vehicle:
  - Booking Count
  - Revenue
  - Contribution

## 3. Revenue Page

- By Customer
- By Vehicle
- By Payment Method
- Monthly and Quarterly trends

## 4. Rider Page

- Cancelled Rides by Reason
- By Payment Method
- Monthly and Quarterly trends
- Detailed data table
- Rider segmentation: First Rider, Return Rider, Regular Rider

## 5. Location Page

- Monthly Total Distance
- Total Distance by Vehicle
- Busy Time Slots
- Busy Areas

## 6. UX / Report Design

- Hide/Show filter panel added for cleaner spacing
- Multiple filters added across report pages for deeper interactivity



## Tech Stack

The dashboard was built using the following tools and technologies:

- **Power BI Desktop** – Main data visualization platform used for report creation.
- **Power Query** – Data transformation and cleaning layer for reshaping and preparing the data.
- **DAX (Data Analysis Expressions)** – Used for calculated measures, dynamic visuals, and conditional logic.
- **Data Modeling** – Relationships established among tables to enable cross-filtering and aggregation.
- **File Format** – `.pbix` for development and `.png` for dashboard previews.

---

## Data Source

**Source:** Simulated Uber ride booking dataset, sourced from a public YouTube Power BI tutorial project and supplementary reference material from Google.

The dataset contains ride-level booking records, including fields such as:
- Booking status (Completed / Cancelled / Lost)
- Vehicle type
- Fare / Revenue
- Pickup and drop-off locations
- Ride distance
- Booking and ride timestamps (used for monthly/quarterly analysis)
- Rider and driver ratings
- Cancellation reasons
- Payment method



## Screenshots
https://github.com/Mashruful-hasan/Uber-Data-Analysis/blob/main/Home%20Page.png
https://github.com/Mashruful-hasan/Uber-Data-Analysis/blob/main/Location.png
https://github.com/Mashruful-hasan/Uber-Data-Analysis/blob/main/Overview.png
https://github.com/Mashruful-hasan/Uber-Data-Analysis/blob/main/Revenue.png
https://github.com/Mashruful-hasan/Uber-Data-Analysis/blob/main/Rider.png
https://github.com/Mashruful-hasan/Uber-Data-Analysis/blob/main/Vehicle.png


