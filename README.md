# SQL_Skills_Project
### A selection of SQL queries used to answer a few questions. The querys were focused on using basic SQL code, including WHERE, ORDER BY, LIMIT and simple JOINs.

## All the queries were made on a country table, and a city table

#### 1. Count Cities in USA

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/6bccf927f5965400c802b1c929ec08c93342c638/Images/Screenshot%202026-02-16%20150639.png)

A quick aggregation on count, grouping by country.

#### 2. Country with Highest Life Expectancy

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/6bccf927f5965400c802b1c929ec08c93342c638/Images/Screenshot%202026-02-16%20150702.png)

A 1 limited query on country sorted by Life expectancy.

#### 3. "New Year Promotion: Featuring Cities with 'New'

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/6bccf927f5965400c802b1c929ec08c93342c638/Images/Screenshot%202026-02-16%20150716.png)

A WHERE LIKE filter applied to the name field.

#### 4. Display Cities by Population with Limit (First 10 Rows)

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/6bccf927f5965400c802b1c929ec08c93342c638/Images/Screenshot%202026-02-16%20150757.png)

Cities ordered by population the limited to 10 entries.

#### 5. Cities with Population Larger than 2,000,000

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/6bccf927f5965400c802b1c929ec08c93342c638/Images/Screenshot%202026-02-16%20150810.png)

WHERE filter for cities only over 2,000,000 Population

#### 6. Cities Beginning with 'Be' Prefix

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/6bccf927f5965400c802b1c929ec08c93342c638/Images/Screenshot%202026-02-16%20150822.png)

A WHERE filter searching from cities beginning with 'Be'.

#### 7. Cities with Population Between 500,000-1,000,000

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/6bccf927f5965400c802b1c929ec08c93342c638/Images/Screenshot%202026-02-16%20150835.png)

A inclusive WHERE filter for use between 2 values.

#### 8. Display Cities Sorted by Name in Ascending Order

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/6bccf927f5965400c802b1c929ec08c93342c638/Images/Screenshot%202026-02-16%20150847.png)

Cities sorted alphabetically. A string data type sorted will simply order alphabetically

#### 9. Most Populated City

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/9aa59f0c3109c1ff084ae51a77702576da953f19/Images/Screenshot%202026-02-16%20150901.png)

Cities sorted by population with a 1 limit just to return the top result.

#### 10. City Name Frequency Analysis: Supporting Geography Education

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/09841ab8905cbda7c48c1ab3d4462b2803b8abad/Images/Screenshot%202026-02-16%20150910.png)

A count aggregation on city names.

#### 11. City with the Lowest Population

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/94c3f29441ed712644acbf1c34e56a15bb33afe6/Images/Screenshot%202026-02-16%20153936.png)

Cities sorted by population ascending with a 1 limit just to return the lowest result.

#### 12. Country with Largest Population

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/09841ab8905cbda7c48c1ab3d4462b2803b8abad/Images/Screenshot%202026-02-16%20153559.png)

Country sorted by popultion with a 1 limit to return the top result.

#### 13. Capital of Spain

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/94c3f29441ed712644acbf1c34e56a15bb33afe6/Images/Screenshot%202026-02-16%20150948.png)

A join between the two tables, in order to retrieve the capital city ID from the country table, then pull that ID into the cities table to return the city name

#### 14. Cities in Europe

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/94c3f29441ed712644acbf1c34e56a15bb33afe6/Images/Screenshot%202026-02-16%20151000.png)

A join between the tables, to check for countries in Europe and then return all cities with a country code that is in Europe.

#### 15. Average Population by Country

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/94c3f29441ed712644acbf1c34e56a15bb33afe6/Images/Screenshot%202026-02-16%20151013.png)

A query to calculate the Poulation average across the cities within a country, and then return the countries ordered by that average.

#### 16. Capital Cities Population Comparison

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/94c3f29441ed712644acbf1c34e56a15bb33afe6/Images/Screenshot%202026-02-16%20151026.png)

A comparison to check the Capital cities by using the country table, then ordering by Population in the Capital cities.

#### 17. Countries with Low Population Density

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/94c3f29441ed712644acbf1c34e56a15bb33afe6/Images/Screenshot%202026-02-16%20151038.png)

A query calculating the population density, then returning countries ordered by that population density.

#### 18. Cities with High GDP per Capita

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/94c3f29441ed712644acbf1c34e56a15bb33afe6/Images/Screenshot%202026-02-16%20151050.png)

A table merge to calculate the GDP_capita for a country, then sorting the cities table by that GDP_ capita and excluding all cities below the average.

#### 19. Display Columns with Limit (Rows 31-40)

![alt text](https://github.com/Doordiver/SQL_Skills_Project/blob/94c3f29441ed712644acbf1c34e56a15bb33afe6/Images/Screenshot%202026-02-16%20151103.png)

A query to show use of an offset, to select values from further down the results.

