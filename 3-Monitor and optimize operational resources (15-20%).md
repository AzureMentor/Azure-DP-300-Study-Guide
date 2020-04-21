# DP-300: Monitor and Optimize Operational Resources (15-20%)

## Monitor activity and performance

* [Prepare an operational performance baseline](https://docs.microsoft.com/en-us/sql/relational-databases/performance/establish-a-performance-baseline?view=sql-server-ver15)
* [Determine sources for performance metrics](https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15)
    * [Query Performance Insight for Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-query-performance)
    * [Monitoring and tuning capabilities in the Azure portal](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-monitor-tune-overview#sql-database-resource-monitoring)
* [Interpret performance metrics](https://docs.microsoft.com/en-us/sql/relational-databases/performance/performance-monitoring-and-tuning-tools?view=sql-server-ver15)
* [Assess database performance by using Azure SQL Database Intelligent Performance](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-query-performance)
    * [Intelligent Insights using AI to monitor and troubleshoot database performance (Preview)](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-intelligent-insights)
* [Configure and monitor activity and performance at the infrastructure, server, service, and database levels](https://docs.microsoft.com/en-us/sql/relational-databases/performance/query-profiling-infrastructure?view=sql-server-ver15)
    * [Monitoring and performance tuning in Azure SQL Database](https://docs.microsoft.com/bs-latn-ba/azure/sql-database/sql-database-monitor-tune-overview)

## Implement performance-related maintenance tasks
* [Implement index maintenance tasks](https://docs.microsoft.com/en-us/sql/relational-databases/maintenance-plans/rebuild-index-task-maintenance-plan?view=sql-server-ver15)
* [Implement statistics maintenance tasks](https://docs.microsoft.com/en-us/sql/relational-databases/maintenance-plans/update-statistics-task-maintenance-plan?view=sql-server-ver15)
* [Configure database auto-tuning](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-automatic-tuning-enable)
* [Automate database maintenance tasks](https://docs.microsoft.com/en-us/sql/relational-databases/maintenance-plans/use-the-maintenance-plan-wizard?view=sql-server-ver15)
  * [Azure SQL agent jobs](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-job-automation-overview#sql-agent-jobs)
  * [Azure automation](https://azure.microsoft.com/en-us/blog/azure-automation-your-sql-agent-in-the-cloud/)
  * [SQL server agent jobs](https://docs.microsoft.com/en-us/sql/ssms/agent/create-a-job?view=sql-server-ver15)
* [Manage storage capacity](https://docs.microsoft.com/en-us/sql/sql-server/maximum-capacity-specifications-for-sql-server?view=sql-server-ver15)
    * [Manage file space for single and pooled databases in Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-file-space-management)

## Identify performance-related issues
* [Configure Query Store to collect performance data](https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15)
    * [Query Performance Insight for Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-query-performance)
* [Identify sessions that cause blocking](https://support.microsoft.com/en-gb/help/224453/inf-understanding-and-resolving-sql-server-blocking-problems)
    * [Finding Blocking Queries in SQL Azure](https://azure.microsoft.com/en-in/blog/finding-blocking-queries-in-sql-azure/)
* [Assess growth/fragmentation of databases and logs](https://docs.microsoft.com/en-us/sql/relational-databases/indexes/reorganize-and-rebuild-indexes?view=sql-server-ver15)
* [Assess performance-related database configuration parameters including:](https://support.microsoft.com/en-gb/help/315512/considerations-for-the-autogrow-and-autoshrink-settings-in-sql-server)
  * [AutoClose](https://docs.microsoft.com/en-us/sql/relational-databases/policy-based-management/set-the-auto-close-database-option-to-off?view=sql-server-ver15)
  * [AutoShrink and AutoGrowth](https://support.microsoft.com/en-us/help/315512/considerations-for-the-autogrow-and-autoshrink-settings-in-sql-server)

## Configure resources for optimal performance
* [Configure storage and infrastructure resources](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-storage-configuration)
  * optimize:
    * IOPS
    * throughput
    * latency
  * [optimize tempdb performance](https://docs.microsoft.com/en-us/sql/relational-databases/databases/tempdb-database?view=sql-server-ver15)
  * [optimize data and log files for performance](https://docs.microsoft.com/en-us/azure/data-factory/concepts-data-flow-performance#optimizing-for-azure-sql-database-and-azure-sql-data-warehouse-synapse)
    * [Manage the size of the transaction log file](https://docs.microsoft.com/en-us/sql/relational-databases/logs/manage-the-size-of-the-transaction-log-file?view=sql-server-ver15)
* [Configure server and service account settings for performance](https://support.microsoft.com/en-gb/help/319942/how-to-determine-proper-sql-server-configuration-settings)
    * [How to determine proper SQL Server configuration settings](https://support.microsoft.com/en-in/help/319942/how-to-determine-proper-sql-server-configuration-settings)
* [Configure Resource Governor for performance](https://docs.microsoft.com/en-us/sql/relational-databases/resource-governor/resource-governor?view=sql-server-ver15)
    * [Resource governance in Azure SQL Database](https://azure.microsoft.com/en-in/blog/resource-governance-in-azure-sql-database/)

## Configure a user database for optimal performance
* [Implement database-scoped configuration](https://docs.microsoft.com/en-us/sql/t-sql/statements/alter-database-scoped-configuration-transact-sql?view=sql-server-ver15)
* [Configure compute resources for scaling](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-single-database-scale)
    * [Manage compute in Azure Synapse Analytics data warehouse](https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-manage-compute-overview)
* [Configure Intelligent Query Processing (IQP)](https://docs.microsoft.com/en-us/sql/relational-databases/performance/intelligent-query-processing?view=sql-server-ver15)

[Return to Table of Contents](README.md)