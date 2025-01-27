# LegoSets Dashboard

This repository contains a Power BI project designed to analyze data related to Lego sets. The dashboard provides insights into various aspects of Lego sets, including themes, piece counts, years of release, and pricing trends. Below are the details of the dashboard and its features.

## Dashboard Overview
The LegoSets Dashboard helps users:
- Understand the distribution of Lego sets across themes.
- Identify trends in set releases over the years.
- Analyze the relationship between piece count and pricing.

## Features
1. **Interactive Filters:**
   - Filter by Year, Theme, Piece Count Range, and Price Range.
2. **Data Visualizations:**
   - Bar charts for set counts by theme and year.
   - Scatter plots to analyze the relationship between piece count and price.
   - Card visuals for key metrics such as total sets, average piece count, and average price.
3. **Custom Measures:**
   - Total number of Lego sets: `COUNT`
   - Average piece count: `AVERAGE`
   - Average price: `AVERAGE`
4. **Trend Analysis:**
   - Line charts to showcase yearly trends in Lego set releases.

## Steps to Create the Dashboard
### Data Preparation
1. Imported a dataset into Power BI Desktop from a CSV file.
2. Checked column distribution, quality, and profiling.
3. Cleaned null values and handled missing data appropriately.

### Data Analysis
1. Created calculated columns and measures using DAX:
   - **Year Grouping**: Grouped sets by release year range.
   - **Piece Count Analysis**: Created measures to calculate average and total piece counts.
   - **Price Analysis**: Analyzed pricing trends and calculated averages.

### Visualizations
1. Added slicers for Year, Theme, Piece Count Range, and Price Range.
2. Designed charts and visuals to represent:
   - Distribution of sets by theme.
   - Trends in set releases over time.
   - Correlation between piece count and price.
3. Used card visuals for summary statistics.
4. Applied themes and branding for a clean, professional look.

### Report Publishing
1. Published the report to Power BI Service for sharing and collaboration.
2. Enhanced the report with Lego branding:
   - Added Lego logo and themed design elements.

## Tools & Technologies Used
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **CSV Dataset**
- **Power BI Service**

## Insights from the Dashboard
1. **Set Distribution**:
   - Top themes by set count include Licensed & Mordern Day.
   - Largest sets by piece count are typically associated with Star Wars & Marvel Super Heroes.
2. **Yearly Trends**:
   - The number of Lego sets released per year has increased over time.
   - Significant milestones include the introduction of new themes in 2010-2017.
3. **Piece Count vs. Price**:
   - A positive correlation exists between piece count and price, with exceptions for collector or limited edition sets.

## File Information
- **Filename**: `LegoSets.pbix`
- **Format**: Power BI Desktop Report File

## Future Improvements
- Add real-time data updates for newly released Lego sets.
- Include additional filters, such as "Set Type" or "Target Age Group."
- Incorporate predictive analytics to forecast trends in Lego set releases and pricing.

---

Feel free to clone this repository and use the provided `LegoSets.pbix` file to explore the dashboard further. Contributions and feedback are welcome!



