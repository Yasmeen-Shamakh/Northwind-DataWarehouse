# Northwind-DataWarehouse
- A data warehouse is designed and implemented on the **"Northwind"** database.<br /> 
- The Northwind database contains the sales data for a fictitious company called “Northwind Traders” which imports and exports specialty foods from around the world.

## Project Steps
- **Data Profiling** <br />
   - Conducted in-depth data profiling of the "Northwind" database to identify data quality issues and anomalies.<br /> 
   - Documented and addressed missing values, data types, unique values, and data patterns within the dataset. <br />

   ![oltp](https://github.com/Yasmeen-Shamakh/Northwind-DataWarehouse/assets/57462948/534e1e9d-ff35-4b9b-8eff-770fde6d77d9)



- **Data Warehouse Design &Data Modeling**  <br />
   - Employed denormalization techniques to enhance query performance and reduce the need for complex joins.
   - Designed and implemented a **Star Schema** model for efficient data warehousing.
 
     ![d1 (1)](https://github.com/Yasmeen-Shamakh/Northwind-DataWarehouse/assets/57462948/7e475132-cb5b-49af-b020-d0674c2caf13)



- **ETL Data Pipelines** <br />
   - Developed ETL data pipelines using SQL Server Integration Services **(SSIS)** to automate the extraction, transformation, and loading of data from the source database (OLTP) to the data warehouse (OLAP).
     
     ![dtaflow](https://github.com/Yasmeen-Shamakh/Northwind-DataWarehouse/assets/57462948/d7c0f108-545a-4023-ba39-7f6070466711)

   - The important part was loading the data into the **Fact Table** and that was done by collecting all the IDs from tables in the source database using a Merge Join transformation.
   - Then, use a Lookup transformation to get the surrogate key for each dimension and apply any necessary transformations required.
     
     ![gg](https://github.com/Yasmeen-Shamakh/Northwind-DataWarehouse/assets/57462948/9af4c2ae-77a8-4db8-aeb0-437509de9a79)


- **Data Analysis** <br />
   - Connected  the data warehouse with **Power BI** for data analysis and visualization.<br />
   - Created interactive dashboards and reports to support data-driven decision-making processes.<br />
      ![image](https://github.com/Yasmeen-Shamakh/Northwind-DataWarehouse/assets/57462948/de71db34-7318-4a86-b791-473f4f02ac8d)

  - &nbsp; Interact with the dashboard on [NovyPro](https://www.novypro.com/project/northwind-sales-dashboard)


