# DP-300: Plan and Implement Data Platform Resources (15-20%)

## Deploy resources by using manual methods
* [Deploy database offerings on selected platforms](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-paas-vs-sql-server-iaas) | [Quickstart: Create an Azure SQL Database single database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-single-database-get-started?tabs=azure-portal)
* [Configure customized deployment templates](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-resource-manager-samples?tabs=single-database) | [Quickstart: Create a single database in Azure SQL Database using the Azure Resource Manager template](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-single-database-get-started-template?tabs=azure-powershell)
* [Apply patches and updates for hybrid and IaaS deployment](https://docs.microsoft.com/en-us/azure/automation/automation-tutorial-update-management) | [Automated Patching for SQL Server in Azure VM](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-automated-patching) | [Patching SQL Azure](https://azure.microsoft.com/en-in/blog/patching-sql-azure/)

## Recommend an appropriate database offering based on specific requirements
* [Evaluate requirements for the deployment](https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/azure-sqldb?view=azure-devops&tabs=yaml)
* [Evaluate the functional benefits/impact of possible database offerings](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-paas-vs-sql-server-iaas)
* [Evaluate the scalability of the possible database offering](https://techcommunity.microsoft.com/t5/azure-sql-database/azure-sql-database-8211-scalability/ba-p/386201)
* [Evaluate the HA/DR of the possible database offering](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-high-availability) | [High availability and disaster recovery for SQL Server in Azure VMs](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-high-availability-dr) | [Disaster recovery strategies for applications using SQL Database elastic pools](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-disaster-recovery-strategies-for-applications-with-elastic-pool)
* [Evaluate the security aspects of the possible database offering](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-security-overview)

## Configure resources for scale and performance
* [Configure Azure SQL database/elastic pools for scale and performance](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-scale-introduction) | [Manage elastic pools in Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-pool-manage) | [Scale elastic pool resources in Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-pool-scale) | [Tune applications and databases for performance in Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-performance-guidance)
* [Configure Azure SQL Managed Instances for scale and performance](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance) | [Managed instance service tiers](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance#managed-instance-service-tiers)
* [Configure SQL Server in Azure VMs for scale and performance](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-performance)
* [Calculate resource requirements](https://docs.microsoft.com/en-us/sharepoint/administration/storage-and-sql-server-capacity-planning-and-configuration)
* [Evaluate database partitioning techniques, such as database sharding](https://docs.microsoft.com/en-us/azure/architecture/best-practices/data-partitioning) | [Sharding pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/sharding)

## Evaluate a strategy for moving to Azure
* [Evaluate requirements for the Migration](https://docs.microsoft.com/en-us/sql/dma/dma-assesssqlonprem?view=sql-server-ver15) | [Overview of prerequisites for using the Azure Database Migration Service](https://docs.microsoft.com/en-us/azure/dms/pre-reqs)
* [Evaluate OFFLINE or ONLINE Migration strategies](https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-to-azure-sql) | [Migrate SQL Server to Azure SQL Database](https://datamigration.microsoft.com/scenario/sql-to-azuresqldb?step=1#offline-versus-online-migrations)
* [Evaluate requirements for the Upgrade](https://docs.microsoft.com/en-us/sql/database-engine/install-windows/supported-version-and-edition-upgrades-version-15?view=sql-server-ver15) | [Pre Upgrade Checklist](https://docs.microsoft.com/en-us/sql/database-engine/install-windows/supported-version-and-edition-upgrades-version-15?view=sql-server-ver15#pre-upgrade-checklist)
* [Evaluate OFFLINE or ONLINE Upgrade strategies](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-manage-application-rolling-upgrade)

## Implement a migration or upgrade strategy for moving to Azure
* [Implement an ONLINE migration strategy](https://datamigration.microsoft.com/scenario/sql-to-azuresqldb?step=1) | [Tutorial: Migrate SQL Server to a single database or pooled database in Azure SQL Database ONLINE using DMS](https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-azure-sql-online)
* [Implement an OFFLINE migration strategy](https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-to-azure-sql)
* [Implement an ONLINE upgrade strategy](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-manage-application-rolling-upgrade)
* [Implement an OFFLINE upgrade strategy](https://docs.microsoft.com/en-us/sql/database-engine/install-windows/upgrade-to-a-different-edition-of-sql-server-setup?view=sql-server-ver15)

[Return to Table of Contents](README.md)