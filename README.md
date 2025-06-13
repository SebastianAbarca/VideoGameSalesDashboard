# 🎮 Video Game Sales Dashboard

This project visualizes global video game sales data using Tableau. It provides insights into trends across genres, regions, platforms, and more.

## 📁 Repository Structure

- `cleaned_data.csv`  
  Final cleaned dataset used in Tableau.

- `MyFirstBook.twbx`  
  Tableau packaged workbook.

- `screenshots/`  
  Folder containing images related to the project.  
  - `dashboard_overview.png` — Preview image of the main dashboard.

- `README.md`  
  Project overview and documentation.

## 📊 Dashboard Overview

This repository contains a Tableau workbook focused on analyzing video game sales across time, genres, and regions.  

The featured **dashboard** combines key insights such as:

- 📈 **Sales over Time**  
  Displays global total sales trends from the 1970s to the 2020s, allowing users to observe growth, peaks, and declines over time.

- 🎮 **Sales by Genre**  
  Compares genre popularity using stacked bar charts, broken down by regional sales (North America, Japan, PAL, and Other).

Interactive filters on the right allow you to refine the view by genre and region, helping explore how specific categories performed across global markets.

> 🔎 Note: The full Tableau **workbook** (`.twbx`) includes additional visualizations (sheets) and will be expanded with more dashboards and a Tableau Story in future updates.

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
4. Or visit https://public.tableau.com/shared/PKQMNX2N7?:display_count=n&:origin=viz_share_link
