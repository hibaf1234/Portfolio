# DataCamp: Exploring London's Travel Network

**Project Description**

**Overview**
How do Londoners get around? This project dives into the vast public transport network provided by Transport for London (TfL). With over 1.5 million journeys per day, TfL plays a crucial role in facilitating efficient travel across the UK's capital. This introductory project uses SQL to analyze a database containing information about TfL journeys spanning 12 years, from 2010 to 2022.

**Objectives**
- Most Popular Transport Types: Write SQL queries to identify the most popular transport methods based on the total number of journeys. The output should include columns for Journey Type (JOURNEY_TYPE) and Total Journeys in millions (TOTAL_JOURNEYS_MILLIONS), sorted in descending order. Save the query as most_popular_transport_types.
- Emirates Airline Popularity: Determine the top five months and years for the Emirates Airline cable car. The output should include columns for Month (MONTH), Year (YEAR), and Journeys in millions rounded to two decimal places (ROUNDED_JOURNEYS_MILLIONS). Save the result as emirates_airline_popularity.
- Least Popular Years for Underground & DLR Journeys: Find the five years with the lowest volume of Underground & DLR journeys. The output should include columns for Year (YEAR), Journey Type (JOURNEY_TYPE), and Total Journeys in millions (TOTAL_JOURNEYS_MILLIONS). Save the result as least_popular_years_tube.

**Guided Project (Snowflake)**
- For those using Snowflake, the project offers a guided approach with specific tasks and real-time automated code checks to ensure a smooth workflow.

**Instructions**
- Utilize the provided SQL cells in the Workspace.
- Access the Snowflake database using the syntax FROM TFL.JOURNEYS (ensure uppercase).
- Keep the names of the DataFrames consistent with the provided ones to avoid renaming issues.
- Follow the specified output format for each query.
- Let's embark on this journey through London's travel network data!
