# BDA-Miniproject
Here’s a professional **README** for your **Electric Vehicles Analysis** project:

---

# Electric Vehicles Analysis Project

## Overview

This project analyzes a dataset of electric vehicles (EVs) using **PySpark** for data processing and **Python libraries** such as **Matplotlib**, **Seaborn**, and **Pandas** for visualization. The goal is to extract insights about EV trends, range, pricing, manufacturers, and vehicle types.

The analysis culminates in a **PDF report** that summarizes key findings with visualizations and textual insights.

---

## Features

* Load and process a CSV dataset of electric vehicles using PySpark.
* Perform statistical analysis on EV attributes.
* Visualize data relationships using plots:

  * Distribution of electric range.
  * Top manufacturers by average electric range.
  * Vehicle type distribution.
  * Trend of EV models over the years.
  * Electric range vs Base MSRP.
* Generate a professional PDF report with all plots and insights.

---

## Dataset

* File: `electric_vehicles_dataset.csv`
* Key columns:

  * `Make`: Manufacturer of the vehicle.
  * `ModelYear`: Year of the model.
  * `VehicleType`: Type of vehicle (car, SUV, etc.).
  * `ElectricRange`: Range of the vehicle on a full charge.
  * `BaseMSRP`: Manufacturer suggested retail price.

> Ensure the CSV file is present in the same directory as the project script.

---

## Requirements

* Python 3.x
* PySpark
* Pandas
* Matplotlib
* Seaborn
* ReportLab (for PDF generation)

## Usage

1. Place the dataset `electric_vehicles_dataset.csv` in the project folder.
2. Run the main Python script

3. The script will:

   * Generate plots for various analyses.
   * Create a PDF report named `ElectricVehiclesAnalysisReport.pdf` with visualizations and insights.

---

## Outputs

* **Plots** (saved as PNG):

  * Distribution of Electric Range
  * Top 10 Manufacturers by Average Electric Range
  * Vehicle Type Distribution
  * Trend of Electric Vehicle Models Over the Years
  * Electric Range vs Base MSRP
* **PDF Report**:

  * Combines all plots and key insights for presentation or reporting purposes.

---

## Insights (Sample)

* Average electric range across all models.
* Most common vehicle type.
* Top manufacturer by average electric range.
* Trends in the number of EV models over the years.

---



