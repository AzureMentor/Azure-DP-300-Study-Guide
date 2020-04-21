# DP-300: Implement a Secure Environment (15-20%)

## Configure database authentication by using platform and database tools

* [Configure Azure AD authentication](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-aad-authentication-configure?tabs=azure-powershell)
* [Create users from Azure AD identities](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-aad-authentication)
    * [Create contained database users in your database mapped to Azure AD identities](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-aad-authentication-configure?tabs=azure-powershell#create-contained-database-users-in-your-database-mapped-to-azure-ad-identities)
* [Configure Security Principals](https://docs.microsoft.com/en-us/sql/relational-databases/security/securing-sql-server?view=sql-server-ver15)
    * [Azure AD Service Principal authentication to SQL DB - Code Sample](https://techcommunity.microsoft.com/t5/azure-sql-database/azure-ad-service-principal-authentication-to-sql-db-code-sample/ba-p/481467)

## Configure database authorization by using platform and database tools
* [Configure database and object-level permissions using graphical tools](https://docs.microsoft.com/en-us/sql/relational-databases/security/permissions-database-engine?view=sql-server-ver15)
    * [Getting Started with Database Engine Permissions](https://docs.microsoft.com/en-us/sql/relational-databases/security/authentication-access/getting-started-with-database-engine-permissions?view=sql-server-ver15)
* [Apply principle of least privilege for all securables](https://docs.microsoft.com/en-us/dotnet/framework/data/adonet/sql/authorization-and-permissions-in-sql-server)

## Implement security for data at rest
* [Implement Transparent Data Encryption (TDE)](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/transparent-data-encryption?view=sql-server-ver15)
    * [Transparent data encryption for SQL Database and Azure Synapse](https://docs.microsoft.com/en-us/azure/sql-database/transparent-data-encryption-azure-sql?tabs=azure-portal)
* [Implement object-level encryption](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/encrypt-a-column-of-data?view=sql-server-ver15)
    * [Always Encrypted: Protect sensitive data and store encryption keys in Azure Key Vault](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-always-encrypted-azure-key-vault?tabs=azure-powershell)
* [Implement Dynamic Data Masking](https://docs.microsoft.com/en-us/sql/relational-databases/security/dynamic-data-masking?view=sql-server-ver15)
    * [Get started with SQL Database dynamic data masking with the Azure portal](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-dynamic-data-masking-get-started-portal)
* [Implement Azure Key Vault and disk encryption for Azure VMs](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-key-vault)
    * [Quickstart: Create and encrypt a Windows virtual machine with the Azure portal](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-portal-quickstart)

## Implement security for data in transit
* [Configure SQL DB and database-level firewall rules](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-firewall-configure)
    * [sp_set_database_firewall_rule (Azure SQL Database)](https://docs.microsoft.com/en-us/sql/relational-databases/system-stored-procedures/sp-set-database-firewall-rule-azure-sql-database?redirectedfrom=MSDN&view=azuresqldb-current)
* [Implement Always Encrypted](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/always-encrypted-database-engine?view=sql-server-ver15)
    * [Always Encrypted: Protect sensitive data and store encryption keys in the Windows certificate store](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-always-encrypted)
* [Configure Azure Data Gateway](https://docs.microsoft.com/en-us/azure/analysis-services/analysis-services-gateway)
    * [Install and configure an on-premises data gateway](https://docs.microsoft.com/en-us/azure/analysis-services/analysis-services-gateway-install)

## Implement compliance controls for sensitive data
* [Apply a data classification strategy](https://docs.microsoft.com/en-us/sql/relational-databases/security/sql-data-discovery-and-classification?view=sql-server-ver15&tabs=t-sql)
    * [What is data classification?](https://docs.microsoft.com/bs-latn-ba/azure/cloud-adoption-framework/govern/policy-compliance/data-classification)
* [Configure server and database audits](https://docs.microsoft.com/en-us/sql/relational-databases/security/auditing/create-a-server-audit-and-database-audit-specification?view=sql-server-ver15)
    * [Azure SQL Auditing](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-auditing)
    * [A Boost in Security for Azure SQL Database: Auditing](https://azure.microsoft.com/en-in/blog/a-boost-in-security-for-azure-sql-database-auditing/)
* [Implement data change tracking](https://docs.microsoft.com/en-us/sql/relational-databases/track-changes/track-data-changes-sql-server?view=sql-server-ver15)
    * [Enable and Disable Change Tracking (SQL Server)](https://docs.microsoft.com/en-us/sql/relational-databases/track-changes/enable-and-disable-change-tracking-sql-server?view=sql-server-ver15)
* [Perform vulnerability assessment](https://docs.microsoft.com/en-us/sql/relational-databases/security/sql-vulnerability-assessment?view=sql-server-ver15)
    * [SQL Vulnerability Assessment helps you identify database vulnerabilities](https://docs.microsoft.com/en-us/azure/sql-database/sql-vulnerability-assessment)

[Return to Table of Contents](README.md)