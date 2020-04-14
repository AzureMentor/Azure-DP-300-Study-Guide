# DP-300: Plan and Implement a High Availability and Disaster Recovery (HADR) Environment (15-20%)

## Recommend an HADR strategy for a data platform solution
* [Recommend HADR strategy based on RPO/RTO requirements](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-business-continuity) | [Overview of business continuity with Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-business-continuity)
* [Evaluate HADR for hybrid deployments](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-high-availability-dr)
* [Evaluate Azure-specific HADR solutions](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-high-availability) | [Azure-only: Disaster recovery solutions](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-high-availability-dr#azure-only-disaster-recovery-solutions)
* [Identify resources for HADR solutions](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/sql-server-backup-and-restore-with-microsoft-azure-blob-storage-service?redirectedfrom=MSDN&view=sql-server-ver15) | [Always On availability groups: a high-availability and disaster-recovery solution](https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/always-on-availability-groups-sql-server?redirectedfrom=MSDN&view=sql-server-ver15) | [Always On Failover Cluster Instances (SQL Server)](https://docs.microsoft.com/en-us/sql/sql-server/failover-clusters/windows/always-on-failover-cluster-instances-sql-server?redirectedfrom=MSDN&view=sql-server-ver15) | [Log Shipping (SQL Server)](https://docs.microsoft.com/en-us/sql/database-engine/log-shipping/about-log-shipping-sql-server?redirectedfrom=MSDN&view=sql-server-ver15)

## Test an HADR strategy by using platform, OS and database tools
* [Test HA by using failover](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-configure-failover-group?tabs=azure-portal) | [Perform a planned manual failover of an Always On availability group (SQL Server)](https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/perform-a-planned-manual-failover-of-an-availability-group-sql-server?view=sql-server-ver15)
* [Test DR by using failover or restore](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-disaster-recovery)

## Perform backup and restore a database by using database tools
* [Perform a database Backup with options](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/back-up-database-backup-options-page?view=sql-server-ver15) | [Create a Full Database Backup](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/create-a-full-database-backup-sql-server?view=sql-server-ver15#TsqlProcedure)
* [Perform a database Restore with options](https://docs.microsoft.com/en-us/sql/t-sql/statements/restore-statements-transact-sql?view=sql-server-ver15)
* [Perform a database Restore to a point in time](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/restore-a-sql-server-database-to-a-point-in-time-full-recovery-model?view=sql-server-ver15) | [Azure SQL Database Point in Time Restore](https://azure.microsoft.com/en-in/blog/azure-sql-database-point-in-time-restore/)
* [Configure long-term Backup retention](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-long-term-retention) | [Manage Azure SQL Database long-term backup retention](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-long-term-backup-retention-configure)

## Configure DR by using platform and database tools
* [Configure replication](https://docs.microsoft.com/en-us/azure/sql-database/replication-to-sql-database) | [Tutorial: Prepare SQL Server for replication (publisher, distributor, subscriber)](https://docs.microsoft.com/en-us/sql/relational-databases/replication/tutorial-preparing-the-server-for-replication?view=sql-server-ver15)
* [Configure Azure Site Recovery for a database offering](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-sql)

## Configure HA using platform, OS and database tools
* [Create an Availability Group](https://docs.microsoft.com/en-us/sql/t-sql/statements/create-availability-group-transact-sql?view=sql-server-ver15) | [Tutorial: Configure availability group on Azure SQL Server VM manually](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-portal-sql-availability-group-tutorial)
* [Integrate a database into an Availability Group](https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/availability-group-add-a-database?view=sql-server-ver15)
* [Configure Quorum options for a Windows Server Failover Cluster](https://docs.microsoft.com/en-us/windows-server/failover-clustering/manage-cluster-quorum) | [WSFC Quorum Modes and Voting Configuration (SQL Server)](https://docs.microsoft.com/en-us/sql/sql-server/failover-clusters/windows/wsfc-quorum-modes-and-voting-configuration-sql-server?view=sql-server-ver15)
* [Configure an Availability Group Listener](https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/create-or-configure-an-availability-group-listener-sql-server?view=sql-server-ver15)


[Return to Table of Contents](README.md)