# YouTube Page Title Analysis by Continent

## Overview
SQL project for analyzing user interaction with YouTube-related page titles across different continents.

The query identifies how often users visited pages containing the word "youtube" in the page title and calculates the percentage of such visits relative to all page views.

## Metrics
- YouTube-related page views
- Total page views
- Percentage of YouTube page views
- Continent-based segmentation

## SQL Concepts Used
- JOIN
- UNNEST
- CASE WHEN
- COUNT
- Aggregations
- Filtering
- String functions (`LOWER`, `LIKE`)

## Logic
1. Extract nested event parameters using `UNNEST`
2. Filter only `page_title` events
3. Detect YouTube-related titles using `LIKE '%youtube%'`
4. Count:
   - YouTube page titles
   - Total page titles
5. Calculate the percentage share by continent
6. Result <img width="798" height="243" alt="image" src="https://github.com/user-attachments/assets/047c11e6-bbc9-4f98-bed3-eb5607e868ab" />
