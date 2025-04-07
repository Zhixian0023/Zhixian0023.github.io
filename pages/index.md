---
layout: page
title: Final Project - Bigfoot Visualizations
permalink: /
---

# Bigfoot Sightings Visualizations

This project uses the BFRO Bigfoot sightings dataset to explore patterns in reports across the United States. The visualizations were created using Python, Altair, and Vega-Lite.

---

## Visualization 1: Sightings by State

**What I visualized:**  
This chart displays the number of Bigfoot sightings reported across different U.S. states.

**Design choices:**  
The horizontal axis lists the states, while the vertical axis shows the number of reports. A bar chart format was used to clearly highlight differences in report frequency between states. The color intensity reflects the number of reports, using a blue color scale to help distinguish states with higher sighting counts.

**Data transformations:**  
The data was grouped by state using `groupby()` in Python to calculate the total number of reports per state.

---

## Visualization 2: Sightings by Month (per Year)

**What I visualized:**  
This line chart shows how the number of Bigfoot reports varies by month within a selected year.

**Design choices:**  
A slider allows viewers to choose a specific year, and the chart updates accordingly. The line format helps highlight trends over time, making it easier to observe seasonal patterns or fluctuations.

**Interactivity:**  
Interactive features include the year slider and tooltips, which provide a more engaging way to explore the data and examine month-to-month changes in greater detail.

---

## Links

- [The Data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/bfro_reports_fall2022.csv)  
- [The Analysis](https://github.com/YOUR_USERNAME/YOUR_REPO/blob/main/Workbook.ipynb)

---

## Visualizations

<iframe src="/assets/plot1.html" width="700" height="400"></iframe>  
<iframe src="/assets/plot2.html" width="700" height="400"></iframe>
