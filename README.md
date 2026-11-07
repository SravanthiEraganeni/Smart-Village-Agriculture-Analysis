# Smart Village Agriculture Analysis

## Project Overview

An interactive agricultural analytics project built to explore crop
production, seasonal patterns, ward-level performance, irrigation
productivity, and fertilizer usage. The project uses Microsoft Excel and
Power Query for data preparation and Power BI for data modelling, DAX
measures, and interactive reporting.

## Tools & Technologies

-   Microsoft Excel
-   Power Query
-   Power BI Desktop
-   DAX
-   Data cleaning, transformation, and visualization

## Dataset

The dataset includes farmer and citizen identifiers, ward number, crop,
season, land area, irrigation type, fertilizer used, yield, and market
price per quintal.

## Data Preparation

-   Reviewed and cleaned duplicate and missing/inconsistent values.
-   Standardized text fields and checked numeric data types.
-   Validated ward values against the expected ward range used in the
    project.
-   Created `Yield_Per_Acre` to analyse land productivity.
-   Created `Estimated_Crop_Value` using yield and market price. This is
    an estimated gross value, not profit or confirmed revenue.

## Power BI Measures

The report includes measures for: - Total Production - Total Farmers -
Total Crop Types - Estimated Crop Value - Average Yield Per Acre

## Dashboard Components

-   KPI cards for production, farmers, crop types, and estimated crop
    value.
-   Crop-wise production bar chart.
-   Season-wise production column chart.
-   Ward-wise production bar chart.
-   Crop contribution treemap.
-   Crop-versus-season production matrix.
-   Interactive slicers for crop, season, ward, and irrigation type.

## Key Questions Explored

1.  Which crops contribute most to total production?
2.  How does production vary by season?
3.  How does production differ across wards?
4.  How is production distributed across crop and season combinations?
5.  How do irrigation and fertilizer categories relate to productivity?

## Important Data Notes

-   Missing or unclassified categories should be retained in the
    underlying data and handled transparently in visuals.
-   Validate the `Total Crop Types` KPI against the cleaned crop column;
    the expected named crop categories in the current analysis are
    Mustard, Potato, Rice, Sugarcane, and Wheat.
-   Reconcile production totals across crop, season, and ward analyses
    using the same `yield_ton` field and consistent filters before
    publishing final conclusions.
-   Estimated crop value is calculated as yield in metric tons × 10
    quintals per ton × market price per quintal. It is a gross estimate
    and does not account for costs, losses, or realized sale prices.

## Repository Contents

-   `README.md` --- project documentation.
-   `images/dashboard.png` --- screenshot of the Power BI dashboard.
-   `Smart_Village_Agriculture_Analysis.pbix` --- add your saved Power
    BI report file here before publishing.

## How to Use

1.  Download or clone this repository.
2.  Open `Smart_Village_Agriculture_Analysis.pbix` in Power BI Desktop.
3.  Refresh the data source if required and review the report visuals
    and slicers.

## Author

Data Analytics Portfolio Project
