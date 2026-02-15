# Blog Analytics Dashboard

Check out the live dashboard here:  
[View Dashboard](https://app.powerbi.com/groups/me/reports/9efe954e-45c2-4b14-b13d-38218a727b4c/de397545a1f600b70012?experience=power-bi)

# Blog Analytics Dashboard

This project is a **Power BI dashboard** that tracks and analyzes my blog posts to give insights into posting patterns and frequency.

## Overview

After writing several blogs, I realized that a dashboard could help me **track and visualize** my blogging activity. Initially, I considered using the Medium API, but since it was unavailable, I switched to **RSS feed integration**.

Using my Medium profile link, I connected to the feed via Power BI’s **Web data source** and loaded the table. I kept only the necessary columns: **Title, URL, and Publication Date**.

## Features

* **Previous Post Date (Calculated Column):** Shows the date of the previous blog post.
* **Date Gaps (Calculated Column / Measure):** Calculates the number of days between posts.
* **Average Posting Days (Measure):** Computes the average days between posts.
* **Posting Frequency (Measure):** Uses `SWITCH` conditions to classify posting frequency.
* **Visualizations:**

  * Table chart with clickable blog links
  * Line chart showing posting trends over time

## Benefits

* Track blogging consistency
* Identify patterns and trends
* Plan future posts more effectively



Do you want me to do that too?
