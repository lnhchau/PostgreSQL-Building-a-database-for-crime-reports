# PostgreSQL-Building-a-database-for-crime-reports
In this project, we will put everything together to build a database for storing data related to crimes that occurred in Boston. 

1. `incident_number`: identifier of the crime. 
2. `offense_code`: a numeric identifier code for the committed crime. 
3. `description`: a description of the crime. 
4. `date`: the date when the crime happened
5. `day_of_the_week`: the corresponding day of the week. 
6. `lat`: the location of the crime with latitude 
7. `long`: the location of the crime with longitude coordinates.

### The goal of this project:
- Creating **a database** named `crimes_db` with a **table** – `boston_crimes` – with appropriate **datatypes for storing the data** from the `boston.csv` file. 
- Creating the **table** inside a schema named `crimes`. 
- Creating the `readonly` and `readwrite` **groups** with the appropriate privileges, then create **1 user** for each of these groups.
