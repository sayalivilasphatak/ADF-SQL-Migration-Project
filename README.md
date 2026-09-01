An end-to-end data engineering pipeline that extracts data from an On-Premise SQL Server, processes it using Azure Data Factory, and stores it in Azure Data Lake Storage Gen2. 
The pipeline implements a metadata-driven incremental loading strategy using a watermark table, ensuring that only new or updated records are processed.

This solution implements a scalable and efficient incremental data loading framework using watermark logic. 
It ensures optimized data movement, reduces processing time, and maintains data consistency through dynamic pipeline orchestration and automated watermark updates.
