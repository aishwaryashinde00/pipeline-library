![StreamSets Logo](images/Full%20Color%20Transparent.png)

<h1><p align="center">Pipeline Library</p></h1>

This repo contains pipeline templates and samples that will help you get started with common use cases using StreamSets.  The directory structure is broken out by the StreamSets engine (datacollector or transformer).  Within each engine, the directory structure is broken out by origins and destinations.  Many templates and samples will be located in multiple locations so you can easily find them by origin or destination.  For example, MySQL CDC to Databricks Delta Lake is found in both origins/mysql and destinations/databricks-delta-lake.

The following templates/samples are currently available:
| Origin            | Destination     |
| --------------- | --------------- |
| [AWS](datacollector/origins/aws) | [AWS](datacollector/destinations/aws) |
| [Azure](datacollector/origins/azure) | [Azure](datacollector/destinations/azure) |
| [HTTP](datacollector/origins/http) | [Databricks Delta Lake](datacollector/destinations/databricks-delta-lake) |
| [MySQL](datacollector/origins/mysql) | [Redshift](datacollector/destinations/redshift) |
| [Oracle](datacollector/origins/oracle) | [Snowflake](datacollector/destinations/snowflake) |
| [PostgreSQL](datacollector/origins/postgresql) | [Synapse](datacollector/destinations/synapse) |
| [Salesforce](datacollector/origins/salesforce) | |
| [SQLServer](datacollector/origins/sqlserver) | |

# Help

For any queries, questions, comments related to these pipelines reach out on any of these channels:

[Chat on Slack](https://streamsetters-slack.herokuapp.com/)

[User Group](https://groups.google.com/a/streamsets.com/d/forum/sdc-user)

[Ask StreamSets](https://ask.streamsets.com/questions/)
