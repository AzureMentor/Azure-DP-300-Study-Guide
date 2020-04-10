# DP-300: Monitor and Optimize Operational Resources (15-20%)

## Monitor activity and performance

* [prepare an operational performance baseline](https://docs.microsoft.com/en-us/sql/relational-databases/performance/establish-a-performance-baseline?view=sql-server-ver15)
* [determine sources for performance metrics](https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15)
* [interpret performance metrics](https://docs.microsoft.com/en-us/sql/relational-databases/performance/performance-monitoring-and-tuning-tools?view=sql-server-ver15)
* [assess database performance by using Azure SQL Database Intelligent Performance](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-query-performance)
* [configure and monitor activity and performance at the infrastructure, server, service, and
database levels](https://docs.microsoft.com/en-us/sql/relational-databases/performance/query-profiling-infrastructure?view=sql-server-ver15)

## Implement performance-related maintenance tasks
* [implement index maintenance tasks](https://docs.microsoft.com/en-us/sql/relational-databases/maintenance-plans/rebuild-index-task-maintenance-plan?view=sql-server-ver15)
* [implement statistics maintenance tasks](https://docs.microsoft.com/en-us/sql/relational-databases/maintenance-plans/update-statistics-task-maintenance-plan?view=sql-server-ver15)
* [configure database auto-tuning](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-automatic-tuning-enable)
* [automate database maintenance tasks](https://docs.microsoft.com/en-us/sql/relational-databases/maintenance-plans/use-the-maintenance-plan-wizard?view=sql-server-ver15)
  * Azure SQL agent jobs
  * Azure automation
  * SQL server agent jobs
* [manage storage capacity](https://docs.microsoft.com/en-us/sql/sql-server/maximum-capacity-specifications-for-sql-server?view=sql-server-ver15)

## Identify performance-related issues
* [configure Query Store to collect performance data](https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15)
* [identify sessions that cause blocking](https://support.microsoft.com/en-gb/help/224453/inf-understanding-and-resolving-sql-server-blocking-problems)
* [assess growth/fragmentation of databases and logs](https://docs.microsoft.com/en-us/sql/relational-databases/indexes/reorganize-and-rebuild-indexes?view=sql-server-ver15)
* [assess performance-related database configuration parameters](https://support.microsoft.com/en-gb/help/315512/considerations-for-the-autogrow-and-autoshrink-settings-in-sql-server) including:
  * AutoClose
  * AutoShrink
  * AutoGrowth

## Configure resources for optimal performance
* [configure storage and infrastructure resources](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-storage-configuration)
  * optimize:
    * IOPS
    * throughput
    * latency
  * optimize tempdb performance
  * optimize data and log files for performance
* [configure server and service account settings for performance](https://support.microsoft.com/en-gb/help/319942/how-to-determine-proper-sql-server-configuration-settings)
* [configure Resource Governor for performance](https://docs.microsoft.com/en-us/sql/relational-databases/resource-governor/resource-governor?view=sql-server-ver15)

## Configure a user database for optimal performance
* [implement database-scoped configuration](https://docs.microsoft.com/en-us/sql/t-sql/statements/alter-database-scoped-configuration-transact-sql?view=sql-server-ver15)
* [configure compute resources for scaling](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-single-database-scale)
* [configure Intelligent Query Processing (IQP)](https://docs.microsoft.com/en-us/sql/relational-databases/performance/intelligent-query-processing?view=sql-server-ver15)

[Return to Table of Contents](README.md)