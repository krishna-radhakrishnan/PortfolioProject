# PortfolioProject

Covid Report was designed in Microsoft Power BI using data for Covid’19 Deaths and Vaccinations, from the “Our World in Data” website.
https://ourworldindata.org/covid-deaths

The data was downloaded as a single CSV file containing all the data as columns. Analysis was done on the data by importing it into Power BI, cleansed by removing null values,
duplicates and unwanted columns, filtering rows and replacing values. Data transformations were done by merging queries, renaming and reordering columns and a data model
was created on top of it. Different visuals were created from this data model which helps in analyzing the data more efficiently.

Concepts used in the report: 
  1. Map, Clustered Column Chart, Line Chart, Doughnut Chart, Treemap
  2. Slicer visual to dynamically filter values in the report 
  3. Drill down and drill through features 
  4. Date wise report on covid cases, deaths and vaccinations 
  5. Bookmark, Selection and Buttons to toggle between different charts 
  6. Visual level filter to display only top vaccinated countries 
  7. Calculated Measures using DAX 
  8. Null value checks, data consistency checks and other data cleanses done with Power BI 
  9. Data transformations using Merge queries 
  10. Data model (Star Schema) creation  
  
 Future Work:
  1. Create more calculated measures and columns using DAX
  2. Create more visuals
  3. Publish Covid Report to Power BI service
  4. Create a dashboard from this report
  3. Implement RLS ( Row-level security) to restrict data across different locations for different roles
