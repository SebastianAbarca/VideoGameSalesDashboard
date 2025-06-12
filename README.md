# 🎮 Video Game Sales Dashboard

This project visualizes global video game sales data using Tableau. It provides insights into trends across genres, regions, platforms, and more.

## 📁 Repository Structure
video-game-sales-dashboard/
├── cleaned_data.csv # Final cleaned dataset used in Tableau
├── MyFirstBook.twbx # Tableau packaged workbook
├── screenshots/
│ └── dashboard_overview.png # Preview image of the main dashboard
├── README.md # Project overview

x## 📊 Dashboard Overview

The dashboard includes:
- **Sales by Genre**: Total and regional sales stacked by genre.
- **Platform Performance**: Visual comparison of sales across gaming platforms.
- **Publisher Trends**: Sales breakdown by publisher and region.
- **Critic Scores & Sales**: Exploration of how review scores relate to performance.

> 🖼️ _Preview available in the `screenshots/` folder._

## 🔧 Data Cleaning (Python)

The original dataset required several preprocessing steps, including:
- Filling missing values using genre-based proportions
- Inferring missing release dates with the RAWG API
- Dropping records with insufficient information
- Standardizing console generation using a custom rank system

> _Scripts for data cleaning can be shared or linked in a future update._

## 📦 How to View the Dashboard

1. Install Tableau (Desktop or Public)
2. Open `MyFirstBook.twbx`
3. Explore the dashboards and visual sheets
