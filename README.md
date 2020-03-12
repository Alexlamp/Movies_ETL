# Movies-ETL

### Background

I was tasked with creating an extract, trasform and load system or (ETL) for gathering box office data from Wikipedia and Kaggle. While an ETL can be used for a one-time transfer of data, I was challenged with building it out as an automated, ongoing process. Since this process will be running without supervision, incoming data may contain errors, causing the ETL process to halt or produce corrupted data. This problem is negated with try-except blocks that make the automated ETL script more resilient to errors.

### Objectives

Create an automated ETL pipeline. <br /> 
Extract data from multiple sources. <br /> 
Clean and transform the data automatically using Pandas and regular expressions. <br /> 
Load new data into PostgreSQL. <br /> 

### Process Assumptions 
1. The assumption is made that the initial cleansing of the raw data from wikipedia and Kaggle is sufficient. More code can be written so that further data cleansing can be performed; however it is forgone due to the time constraints.

2. We assume that the reqular expressions used to parse through our box office data will capture the same desired data. Potentially, regex syntax could change or be updated therfore altering our search patterns.

3. 
4.
5.
