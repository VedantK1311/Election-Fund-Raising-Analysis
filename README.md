# Election Fund Raising Analysis
This project delivers a scalable ELT pipeline built with Snowflake and dbt to process and analyze FEC (Federal Election Commission) government election data. It enables efficient transformation of raw fundraising data into structured insights, powering dashboards and reports that uncover electoral trends.

Notes:
Data comes from official FEC election data sources.
Snowflake credentials (account, user, warehouse, database) must be configured in your profiles.yml for dbt.
Large datasets may require incremental dbt models for scalability.
