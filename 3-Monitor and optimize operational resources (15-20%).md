# DP-300: Monitor and Optimize Operational Resources (15-20%)

## Monitor activity and performance

* [Prepare an operational performance baseline](https://docs.microsoft.com/en-us/sql/relational-databases/performance/establish-a-performance-baseline?view=sql-server-ver15)
* [Determine sources for performance metrics](https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15)
* [Interpret performance metrics](https://docs.microsoft.com/en-us/sql/relational-databases/performance/performance-monitoring-and-tuning-tools?view=sql-server-ver15)
* [Assess database performance by using Azure SQL Database Intelligent Performance](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-query-performance)
* [Configure and monitor activity and performance at the infrastructure, server, service, and
database levels](https://docs.microsoft.com/en-us/sql/relational-databases/performance/query-profiling-infrastructure?view=sql-server-ver15)

## Implement performance-related maintenance tasks
* [Implement index maintenance tasks](https://docs.microsoft.com/en-us/sql/relational-databases/maintenance-plans/rebuild-index-task-maintenance-plan?view=sql-server-ver15)
* [Implement statistics maintenance tasks](https://docs.microsoft.com/en-us/sql/relational-databases/maintenance-plans/update-statistics-task-maintenance-plan?view=sql-server-ver15)
* [Configure database auto-tuning](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-automatic-tuning-enable)
* [Automate database maintenance tasks](https://docs.microsoft.com/en-us/sql/relational-databases/maintenance-plans/use-the-maintenance-plan-wizard?view=sql-server-ver15)
  * Azure SQL agent jobs
  * Azure automation
  * SQL server agent jobs
* [Manage storage capacity](https://docs.microsoft.com/en-us/sql/sql-server/maximum-capacity-specifications-for-sql-server?view=sql-server-ver15)

## Identify performance-related issues
* [Configure Query Store to collect performance data](https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15)
* [Identify sessions that cause blocking](https://support.microsoft.com/en-gb/help/224453/inf-understanding-and-resolving-sql-server-blocking-problems)
* [Assess growth/fragmentation of databases and logs](https://docs.microsoft.com/en-us/sql/relational-databases/indexes/reorganize-and-rebuild-indexes?view=sql-server-ver15)
* [Assess performance-related database configuration parameters including:](https://support.microsoft.com/en-gb/help/315512/considerations-for-the-autogrow-and-autoshrink-settings-in-sql-server)
  * AutoClose
  * AutoShrink
  * AutoGrowth

## Configure resources for optimal performance
* [Configure storage and infrastructure resources](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-storage-configuration)
  * optimize:
    * IOPS
    * throughput
    * latency
  * optimize tempdb performance
  * optimize data and log files for performance
* [Configure server and service account settings for performance](https://support.microsoft.com/en-gb/help/319942/how-to-determine-proper-sql-server-configuration-settings)
* [Configure Resource Governor for performance](https://docs.microsoft.com/en-us/sql/relational-databases/resource-governor/resource-governor?view=sql-server-ver15)

## Configure a user database for optimal performance
* [Implement database-scoped configuration](https://docs.microsoft.com/en-us/sql/t-sql/statements/alter-database-scoped-configuration-transact-sql?view=sql-server-ver15)
* [Configure compute resources for scaling](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-single-database-scale)
* [Configure Intelligent Query Processing (IQP)](https://docs.microsoft.com/en-us/sql/relational-databases/performance/intelligent-query-processing?view=sql-server-ver15)

[Return to Table of Contents](README.md)