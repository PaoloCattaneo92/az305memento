

Tables and stuff to memorize for AZ305 exam.

All the content has been screenshotted in late June 2023 from the official [Microsoft Leaning pages](https://learn.microsoft.com/en-us/certifications/exams/az-305/)

# Table of contents
- [Table of contents](#table-of-contents)
- [1. Design identity, governance, and monitor solutions](#1-design-identity-governance-and-monitor-solutions)
  - [Governance](#governance)
    - [Differences between RBAC and Azure Policy:](#differences-between-rbac-and-azure-policy)
  - [AuthN/AuthZ](#authnauthz)
    - [Differences between B2B and B2C:](#differences-between-b2b-and-b2c)
  - [Log monitor](#log-monitor)
    - [Deploy options for LAW:](#deploy-options-for-law)
    - [Access mode for LAW:](#access-mode-for-law)
    - [Types of Insights:](#types-of-insights)
- [2. Business continuity](#2-business-continuity)
  - [HA + DR](#ha--dr)
    - [SQL Server HA+DR solutions for SQL Server in VM](#sql-server-hadr-solutions-for-sql-server-in-vm)
- [3. Data storage](#3-data-storage)
  - [Non relational data](#non-relational-data)
    - [Types of Storage account](#types-of-storage-account)
    - [Blob storage tiers:](#blob-storage-tiers)
    - [Azure files performances:](#azure-files-performances)
    - [Comparisons between storage solutions:](#comparisons-between-storage-solutions)
    - [Azure managed disks:](#azure-managed-disks)
  - [Relational data](#relational-data)
    - [Compare SQL deployment options](#compare-sql-deployment-options)
    - [SQL Horizontal Scaling](#sql-horizontal-scaling)
    - [SQL Vertical Scaling](#sql-vertical-scaling)
    - [SQL scalability options](#sql-scalability-options)
    - [SQL availability options](#sql-availability-options)
    - [Protect data in motion](#protect-data-in-motion)
    - [Azure SQL Edge editions](#azure-sql-edge-editions)
    - [Azure Cosmo DB Table VS Storage Table](#azure-cosmo-db-table-vs-storage-table)
  - [Data Integration](#data-integration)
    - [Azure Data Lake VS Blob Storage](#azure-data-lake-vs-blob-storage)
    - [Azure Data Factory VS Azure Synapse](#azure-data-factory-vs-azure-synapse)
- [4. Infrastructure](#4-infrastructure)
    - [VM sizes:](#vm-sizes)
    - [App Service price tiers:](#app-service-price-tiers)
    - [Storage for tier](#storage-for-tier)
    - [Pay-as-you-go VS Reserved Instances](#pay-as-you-go-vs-reserved-instances)
    - [Functions plans](#functions-plans)
    - [Max App Services per SKU](#max-app-services-per-sku)
    - [Container VS VM](#container-vs-vm)
    - [VM SLA](#vm-sla)
    - [Functions VS Logic APPS](#functions-vs-logic-apps)
    - [Messages services comparison](#messages-services-comparison)
    - [Event Grid VS Event Hubs VS Service Bus](#event-grid-vs-event-hubs-vs-service-bus)
    - [Network connectivity options](#network-connectivity-options)
    - [Network patterns](#network-patterns)
    - [Migrations options](#migrations-options)
    - [Migration tools](#migration-tools)
    - [Import/Export VS Data Box](#importexport-vs-data-box)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# 1. Design identity, governance, and monitor solutions 

##  Governance
### Differences between RBAC and Azure Policy:

![azrbac_azpolicy](/img/azrbac_azpolicy.png)

##  AuthN/AuthZ
### Differences between B2B and B2C:

![b2b_b2c](img/b2b_b2c.png)

## Log monitor
### Deploy options for LAW:

![law1](img/law1.png)

### Access mode for LAW:

![law2](img/law2.png)

### Types of Insights:

![insights](img/insights.png)

# 2. Business continuity

## HA + DR
### SQL Server HA+DR solutions for SQL Server in VM

![sqlservhadr](img/sqlonvm_hadr.png)

# 3. Data storage

## Non relational data

### Types of Storage account

![storageaccount_types](img/storageaccount_types.png)

### Blob storage tiers:

![blob](img/blobstorage1.png)

### Azure files performances:

![azfiles_performancne](img/azfiles_performance.png)

### Comparisons between storage solutions:

![storage_compare](img/storage_compare.png)

### Azure managed disks:

![managed_disks](img/managed_disks.png)

## Relational data

### Compare SQL deployment options

![sqldeploy](img/sqldeploy.png)

### SQL Horizontal Scaling

![sqlhorscsale](img/sqlhorscsale.png)

### SQL Vertical Scaling

![sqlver](img/sqlverscale.png)

### SQL scalability options

![scala](img/scalability_sol.png)

### SQL availability options

![sql_availa](img/sql_availa.png)

### Protect data in motion

![datainmotion](img/protect_data_inmotion.png)

### Azure SQL Edge editions

![sqledge](img/sql_edge_editions.png)

### Azure Cosmo DB Table VS Storage Table

![cosmovstable](img/cosmovstable.png)

## Data Integration

### Azure Data Lake VS Blob Storage

![lakevsblob](img/lakevsblob.png)

### Azure Data Factory VS Azure Synapse

![datafac](img/datafac_vs_synapse.png)

# 4. Infrastructure
### VM sizes:

![vmssize](img/vmsizess.png)

### App Service price tiers:
* Free
* Shared
* Dedicated - Basic, Standard, Premium, PremiumV2, PremiumV3
* Isolated - Isolated and IsolatedV2

![appservdedi](img/appserv_dedicated.png)

### Storage for tier
|Tier|GB|
|-|-|
|Free|1 GB|
|Shared|1 GB|
|Basic|10 GB|
|Standard|50 GB|
|Premium|250 GB|
|Isolated|1 TB|

### Pay-as-you-go VS Reserved Instances

![payg](img/payg.png)

### Functions plans

![funcplans](img/funcplans.png)

### Max App Services per SKU

![maxpersku](img/maxapppersku.png)

### Container VS VM

![containervsvm](img/containervsvm.png)

### VM SLA

| Deployment Configuration    | SLA Uptime Guarantee |
|----------------------------|---------------------|
| Single Instance VM         | 99.9%               |
| VMs in Availability Sets   | 99.95%              |
| VMs in Availability Zones  | 99.99%              |

### Functions VS Logic APPS

![funcvvslogic](img/funcvslogic.png)

### Messages services comparison

![messages](img/messages.png)

### Event Grid VS Event Hubs VS Service Bus

![event](img/evengridvshubs.png)

### Network connectivity options

![nco](img/networkconnectivityoptions.png)

### Network patterns

![np](img/netpatternss.png)

### Migrations options

![migr](img/migrationspatterns.png)

### Migration tools

![migr2](img/migration_tools.png)

![migr3](img/migration_tools2.png)

### Import/Export VS Data Box

![iedatabox](img/importvsdatabox.png)