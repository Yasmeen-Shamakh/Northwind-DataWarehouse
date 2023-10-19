# Northwind-DataWarehouse
- A data warehouse is designed and implemented on the "Northwind" database.<br /> 
- The Northwind database contains the sales data for a fictitious company called “Northwind Traders” which imports and exports specialty foods from around the world.

## Project Steps
- Data Profiling <br />
   - Conducted in-depth data profiling of the "Northwind" database to identify data quality issues and anomalies.<br /> 
   - Documented and addressed missing values, data types, unique values, and data patterns within the dataset.  <br />
  
  ![oltp](https://github.com/Yasmeen-Shamakh/Northwind-DataWarehouse/assets/57462948/28b3a0ea-e4e8-4cd7-8532-1cdc98f820d1)


- Data Warehouse design &Data Modeling  <br />
   - Employed denormalization techniques to enhance query performance and reduce the need for complex joins.
   - Designed and implemented a **Star Schema** model for efficient data warehousing.
  ![d1 (1)](https://github.com/Yasmeen-Shamakh/Northwind-DataWarehouse/assets/57462948/6486c633-e304-46f8-8f84-4aad7732715b)


- ETL Data Pipelines <br />
   - Developed ETL data pipelines using SQL Server Integration Services **(SSIS)** to automate the extraction, transformation, and loading of data from the source database (OLTP) to the data warehouse (OLAP).
  ![dtaflow](https://github.com/Yasmeen-Shamakh/Northwind-DataWarehouse/assets/57462948/7043d8b0-d958-4f9f-8316-3084f2030632)

   - The important part was loading the data into the Fact Table and that was done by collecting all the IDs from tables in the source database using a Merge Join transformation.
   - Then, use a Lookup transformation to get the surrogate key for each dimension and apply any necessary transformations required.
     ![gg](https://github.com/Yasmeen-Shamakh/Northwind-DataWarehouse/assets/57462948/7b346f7b-b1d2-4483-bab2-0e5c8dc7064a)


- Data Analysis <br />
   - Connected  the data warehouse with **Power BI** for data analysis and visualization.<br />
   - Created interactive dashboards and reports to support data-driven decision-making processes.<br />

