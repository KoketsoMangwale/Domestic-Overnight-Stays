# Domestic-Overnight-Stays
South Africa Domestic Overnight Stays Reporting

## Project Overview
This Power BI project provides a comprehensive analysis of domestic overnight stays across different regions. The report is designed to help stakeholders understand trends, patterns, and insights related to overnight stays, including year-over-year comparisons, regional performance, and key factors influencing these stays.

## Data Sources
- **Tourism Survey Data**: Contains raw data on domestic overnight stays.
- **Regional Statistics**: Provides demographic and economic data for each region.
- **Historical Data**: Includes data from previous years for trend analysis.

## Setup Instructions

### Prerequisites
- **Power BI Desktop**: Make sure you have the latest version installed.
- **Data Access**: Ensure you have access to the necessary datasets.

### Steps to Import Data
1. **Load Data Sources**: Open Power BI Desktop and go to `Home > Get Data` to import the datasets listed above.
2. **Data Transformation**: Use `Power Query Editor` to clean and transform the data:
   - Rename column names to improve tidiness
   - Rename query for easy readability
   - Remove irrelevant columns
   - Remove duplicates
   - Handle missing values
   - Apply filters for the required date range
   - Merge/append datasets if necessary (e.g., combining survey data with regional statistics OR combining 2019 and 2020 survey data)

### Building the Data Model
1. **Relationships**: Establish relationships between the tables by linking common keys, such as `RegionID` or `Date`.
2. **Calculated Columns/Measures**: Create calculated columns or measures, such as:
   - `Total Overnight Stays`
   - `Year-over-Year Growth`
   - `Average Stay Duration`

### Creating the Report
1. **Dashboard Layout**:
   - Create a multi-page report with each page focusing on a different aspect of the analysis (e.g., Overview, Regional Breakdown, Trends).
   - Use appropriate visualizations (e.g., bar charts, line charts, maps) to represent data insights effectively.
2. **Filters and Slicers**:
   - Implement filters and slicers for users to customize their view, such as filtering by region, time period, or demographics.
3. **Custom Visuals** (Optional):
   - Consider using custom visuals from the Power BI marketplace to enhance the report's interactivity and visual appeal.

### Publishing the Dashboard
1. **Publish to Power BI Service**:
   - Save your report and publish it to the Power BI Service by going to `File > Publish > Publish to Power BI`.
   - Assign the report to the relevant workspace.
2. **Dashboard Creation**:
   - Pin key visuals to a new dashboard.
   - Add additional tiles, such as KPIs or cards, to highlight critical metrics.
3. **Sharing and Permissions**:
   - Share the dashboard with stakeholders by managing access permissions.
   - Set up alerts for specific metrics if needed.

### Maintenance and Updates
1. **Data Refresh**:
   - Schedule automatic data refreshes to keep the report up to date.
   - Monitor refresh performance and troubleshoot issues as necessary.
2. **Version Control**:
   - Keep a version history of changes made to the report.
   - Document any major updates or changes in the report structure.

### Troubleshooting
- **Common Issues**: 
   - Data loading errors: Check connections and data source permissions.
   - Visualization errors: Ensure correct data types and relationships are set.
   - Performance issues: Optimize the data model and reduce the number of visuals.
