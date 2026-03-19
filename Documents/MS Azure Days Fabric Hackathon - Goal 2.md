---
layout: page
title: Goal 2 - Transform Your Ingested Data for Analytics
---

# Transform Your Ingested Data for Analytics (2 hours)

Once your data is in Fabric, you have multiple options to shape it into something useful. Pick the approach that best fits your workflow or challenge.

## Transformation Options

- Use a notebook to clean, prep, or enrich your data.
- Build a workflow to automate transformations.
- Write SQL to transform data directly in your Lakehouse.
- Create views to simplify or structure your datasets.
- Use any other Fabric feature that fits your scenario.

Fabric gives you the flexibility to transform data however you prefer.

## Notes and References

### 1. Transform with Dataflows (Visual / No-Code)

Description: Use Dataflow Gen2 to visually prepare and transform data using Power Query before landing it into your Lakehouse or curated tables. It is great for filtering, joins, type changes, and light cleansing at scale.

- [Tutorial - Copy data and transform with Dataflow](https://learn.microsoft.com/en-us/fabric/data-factory/tutorial-load-data-lakehouse-transform)

### 2. Transform with Notebooks (Code-Driven)

Description: Use Microsoft Fabric Notebooks (Spark Python/SQL) to clean, enrich, and reshape your data after ingestion. Notebooks give you full control with code and are ideal for complex transformations and machine learning preparation.

- [How to use Microsoft Fabric Notebooks](https://learn.microsoft.com/en-us/fabric/data-engineering/how-to-use-notebook)

### 3. Prepare and Transform in Lakehouse Using Notebooks

Description: A hands-on tutorial showing how to take raw files, transform them using Spark, write them as Delta tables, and then query with SQL within Fabric.

- [Transform data with Apache Spark and SQL in OneLake](https://learn.microsoft.com/en-us/fabric/onelake/onelake-onecopy-quickstart)

### 4. Transform with Dataflow (Gen2 Detailed)

Description: Step-by-step guide to use Dataflow Gen2 to transform data from raw to gold tables using Power Query transformations.

- [Module - Transform with a dataflow in Data Factory](https://learn.microsoft.com/en-us/fabric/data-factory/tutorial-end-to-end-dataflow)

### 5. Transform Using SQL Queries

Description: Once data is stored in your Lakehouse, a SQL analytics endpoint lets you run familiar T-SQL queries to aggregate, filter, and prepare data for analytics or BI workloads.

- [Lakehouse SQL analytics endpoint overview](https://learn.microsoft.com/en-us/fabric/data-warehouse/get-started-lakehouse-sql-analytics-endpoint)

### 6. Create SQL Views for Analytics

Description: In Fabric, you can define SQL views over your transformed data to simplify query logic or expose curated datasets for BI tools or users.

- [Discussion: Create SQL views on Lakehouse tables](https://community.fabric.microsoft.com/t5/Data-Engineering/Create-SQL-views-with-Fabric-lakehouse-SQL-endpoint-from-Fabric/m-p/3977200)

### 7. Use Materialized Lake Views for Faster Analytics

Description: Materialized lake views let you define transformations in SQL and persist the results as Delta tables. Fabric manages refresh behavior and dependencies, which can improve performance and simplify downstream reporting.

- [What are materialized lake views in Microsoft Fabric?](https://learn.microsoft.com/fabric/data-engineering/materialized-lake-views/overview-materialized-lake-view)

