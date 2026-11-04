**End-to-End Data Engineering Pipeline Using Microsoft Fabric**

**Project Overview**

This project demonstrates the implementation of an end-to-end data engineering pipeline using Microsoft Fabric, covering data ingestion, transformation, data warehousing, and semantic modeling.

The solution follows a modern Lakehouse architecture, leveraging Microsoft Fabric capabilities such as OneLake, Lakehouse, Dataflows Gen2, PySpark Notebooks, Fabric Data Warehouse, and Power BI Semantic Models.

The primary objective is to understand and implement how raw transactional data can be ingested, transformed, structured into analytical warehouse tables, and exposed through a centralized semantic layer for downstream reporting and analytics.

**Phase 1 – Data Ingestion & Storage**
- Ingest raw transactional datasets such as sales.csv.
- Store raw files in Fabric Lakehouse.
- Leverage OneLake as the underlying unified storage layer.
  
**Phase 2 – Data Transformation & Warehousing**
- Use Dataflows Gen2 for low-code data transformation.
- Use PySpark Notebooks for code-based data processing and aggregations.
- Create curated Delta tables.
- Load  data into Fact and Dimension tables using T-SQL.
- Build the Data Warehouse on top of the Lakehouse staging layer.
  
**Phase 3 – Semantic Modeling**
- Design a Star Schema using Fact and Dimension tables.
- Establish relationships between tables.
- Create a centralized Semantic Model in Microsoft Fabric.
- Prepare the semantic layer for future Power BI reporting and analytics.
3. **Technologies used**
  
Technology	Purpose

Microsoft Fabric	    -  Unified analytics platform

OneLake	               - Centralized data storage

Lakehouse              -	Raw and staged data storage

Dataflows Gen2	       - Low-code ETL

PySpark	               - Data transformation

Delta Lake	           - Curated data storage

Fabric Data Warehouse	 - Analytical data modeling

T-SQL	                 - Fact and Dimension loading

Semantic Model	       - Business data layer
