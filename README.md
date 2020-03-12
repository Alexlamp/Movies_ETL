# Movies-ETL

### Background

I was tasked with creating an extract, trasform and load system or (ETL) for gathering box office data from Wikipedia and Kaggle. While an ETL can be used for a one-time transfer of data, I was challenged with building it out as an automated, ongoing process. Since this process will be running without supervision, incoming data may contain errors, causing the ETL process to halt or produce corrupted data. This problem is negated with try-except blocks that make the automated ETL script more resilient to errors.

### Objectives

Create an automated ETL pipeline. <br /> 
Extract data from multiple sources. <br /> 
Clean and transform the data automatically using Pandas and regular expressions. <br /> 
Load new data into PostgreSQL. <br /> 

### Process Assumptions 
