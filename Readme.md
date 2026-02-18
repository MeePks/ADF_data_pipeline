# Enterprise-Ready Azure Data Factory (ADF) Pipeline

## Project Overview
This project demonstrates a **full end-to-end ETL/ELT pipeline** built in **Azure Data Factory (ADF)**. It processes **CSV files from Azure Blob Storage** and loads data into **SQL tables**, incorporating enterprise best practices.

The pipeline covers:

- Bulk load from source files to staging
- Incremental load to fact tables with watermarking
- Slowly Changing Dimension (SCD Type 2) handling
- Dynamic file processing with ForEach loops
- Schema drift handling
- Logging and error handling
- Restart logic for failed pipelines
- Triggers (schedule & event-based)
- Performance optimization (DIUs, partitioning, parallelism)

## Author

**Pikesh Maharjan**  
- ETL / Data Engineer | ADF, SQL, Python, PySpark  
- [LinkedIn Profile](https://www.linkedin.com/in/pikesh-maharjan-6022341b4/)


