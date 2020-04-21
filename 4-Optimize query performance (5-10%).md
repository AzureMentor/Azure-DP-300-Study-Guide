# DP-300: Optimize Query Performance (5-10%)

## Review query plans

* [Determine the appropriate type of execution plan](https://docs.microsoft.com/en-us/sql/relational-databases/performance/execution-plans?view=sql-server-ver15)
  * [Live Query Statistics](https://docs.microsoft.com/en-us/sql/relational-databases/performance/live-query-statistics?view=sql-server-ver15)
  * [Actual Execution Plan](https://docs.microsoft.com/en-us/sql/relational-databases/performance/display-an-actual-execution-plan?view=sql-server-ver15)
  * [Estimated Execution Plan](https://docs.microsoft.com/en-us/sql/relational-databases/performance/display-the-estimated-execution-plan?view=sql-server-ver15)
  * [Showplan](https://docs.microsoft.com/en-us/sql/tools/sql-server-profiler/analyze-queries-with-showplan-results-in-sql-server-profiler?view=sql-server-ver15)
* [Identify problem areas in execution plans](https://docs.microsoft.com/en-us/sql/relational-databases/performance/analyze-an-actual-execution-plan?view=sql-server-ver15)
* [Extract query plans from the Query Store](https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15)

## Evaluate performance improvements
* [Determine the appropriate Dynamic Management Views (DMVs) to gather query performance information](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-monitoring-with-dmvs)
* [Identify performance issues using DMVs](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-monitoring-with-dmvs)
* [Identify and implement index changes for queries](https://docs.microsoft.com/en-us/sql/relational-databases/sql-server-index-design-guide?view=sql-server-ver15)
* [Recommend query construct modifications based on resource usage](https://docs.microsoft.com/en-us/sql/relational-databases/performance/upgrade-dbcompat-using-qta?view=sql-server-ver15)
    * [Monitoring performance by using the Query Store](https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15)
* [Assess the use of Hints for Query performance](https://docs.microsoft.com/en-us/sql/t-sql/queries/hints-transact-sql-query?view=sql-server-ver15)

## Review database table and index design
* [Identify data quality issues with duplication of data](https://docs.microsoft.com/en-us/sql/data-quality-services/introduction-to-data-quality-services?view=sql-server-ver15)
    * [Data Matching](https://docs.microsoft.com/en-us/sql/data-quality-services/data-matching?view=sql-server-ver15)
* [Identify normal form of database](https://docs.microsoft.com/en-us/office/troubleshoot/access/database-normalization-description)
* [Assess index design for performance](https://docs.microsoft.com/en-us/sql/relational-databases/sql-server-index-design-guide?view=sql-server-ver15)
    * [Improve the performance of your Azure SQL Databases using Index Advisor](https://azure.microsoft.com/en-in/blog/optimize-database-performance-using-index-advisor-7/)
* [Validate Data Types defined for columns](https://docs.microsoft.com/en-us/sql/t-sql/data-types/data-types-transact-sql?view=sql-server-ver15)
    * [Validate Integer and Decimal Values in SQL Server](https://www.mssqltips.com/sqlservertip/4799/validate-integer-and-decimal-values-in-sql-server/)
* [Recommend table and index storage including filegroups](https://docs.microsoft.com/en-us/sql/relational-databases/databases/database-files-and-filegroups?view=sql-server-ver15)
* [Evaluate Table Partitioning strategy](https://docs.microsoft.com/en-us/azure/architecture/best-practices/data-partitioning)
* [Evaluate the use of Compression for tables and indexes](https://docs.microsoft.com/en-us/sql/relational-databases/data-compression/enable-compression-on-a-table-or-index?view=sql-server-ver15)
    * [sp_estimate_data_compression_savings (Transact-SQL)](https://docs.microsoft.com/en-us/sql/relational-databases/system-stored-procedures/sp-estimate-data-compression-savings-transact-sql?view=sql-server-ver15)

[Return to Table of Contents](README.md)