# Airlines SSAS - OLAP Analysis

A SQL Server Analysis Services (SSAS) project that builds a multidimensional OLAP cube on top of the Airlines Data Warehouse, enabling fast analytical queries and business intelligence reporting. This is the final stage of a 3-part data warehousing system.

## Project Overview
The data warehouse cube is processed through SSAS to enable multidimensional analysis of airline performance metrics including on-time rates, route utilisation, and passenger trends.

## Architecture
Data Warehouse → [SSAS OLAP Cube] → Analytical Reporting

## What You Can Analyse
- Flight on-time performance rates
- Route utilisation and popularity
- Passenger volume trends over time
- Aircraft performance metrics

## Technologies
- SQL Server Analysis Services (SSAS)
- MDX (Multidimensional Expressions)
- SQL Server

## Part of a 3-Repo Data Warehouse System
| Repo | Role |
|------|------|
| [AirlinesLoad_Staging](https://github.com/JaneeshaPabasara/AirlinesLoad_Staging) | ETL Pipeline & Staging |
| [AirlinesCube_IT23599604](https://github.com/JaneeshaPabasara/AirlinesCube_IT23599604) | Data Warehouse Cube |
| **Airlines_SSAS** (this repo) | OLAP Analysis & Reporting |
