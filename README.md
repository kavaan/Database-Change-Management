# Database Change Management


As your software grows in complexity, managing database changes can become challenging for you and your team. Luckily, there are tools available to streamline this process for developers.

<img src="https://github.com/kavaan/Database-Change-Management/blob/main/main.png?raw=true"/>

 <h3>Some of these tools include:</h3>

1- Flyway: Flyway is an open-source database migration tool that helps manage and version database schema changes.
Database Support: A wide range of relational databases, including PostgreSQL, MySQL, Oracle, SQL Server and many others. 
Key features:
  + Simple and easy to use.
  + Supports various relational databases.
  + Handles database schema changes through version control.
  + Provides a command-line interface for migrations.
  + Enables repeatable migrations for consistent database changes.
  + Supports undoing migrations.
  + Integrates with various build tools and Continuous Integration (CI) pipelines.

Availability: Open-source

Website: https://flywaydb.org

2- Liquibase : Liquibase is a flexible open-source tool that helps manage versioning and migration of database schema across different databases, with CLI and CI integration.
Database Support: A wide range of relational databases including MySQL, Oracle, PostgreSQL, SQL Server, IBM DB2, MariaDB, SQLite and H2.
Key features:
  + Enables versioning and management of database schema changes.
  + Supports a wide range of relational databases.
  + Provides a flexible XML or YAML syntax for defining changes.
  + Enables rollbacks and reverting to previous versions.
  + Enables repeatable migrations for consistent database changes.
  + Integrates with build tools and Continuous Integration (CI) pipelines.
  + Provides a command-line interface for migrations.
  + Offers extensions for non-relational databases(such as Cassandra, MongoDB, and Couchbase).

Availability: Open-source

Website: https://www.liquibase.org

3- ApexSQL Diff:  ApexSQL Diff is a tool for comparing and syncing SQL Server database schema and data changes, with flexible comparison modes and CLI and source control integration.
Database Support: Supports Microsoft SQL Server databases(from SQL Server 2005 to the latest), Azure SQL Database and Amazon RDS for SQL Server.
Key features:
  + Enables comparison and synchronization of SQL Server database schema and data changes.
  + Supports various comparison modes, such as object-by-object, snapshot and project comparison.
  + Provides a command-line interface for automation.
  + Integrates with source control systems for versioning and collaboration.
  + Enables filtering and customizing comparison results.
  + Provides detailed reports and logging for auditing and compliance.
  + Supports comparison and synchronization of SQL Server database backups.

Availability: Licensed

Website: https://www.apexsql.com/sql_tools_diff.aspx

4- Fluent migrations: Fluent Migrations is an open-source library for managing database schema migrations using a fluent API syntax in code, supporting multiple databases and providing a CLI.
Database Support: Supports Microsoft SQL Server, PostgreSQL, MySQL, SQLite, Oracle and Firebird.
Key features:
  + Enables database schema migration management using a fluent API syntax in code.
  + Supports versioning of database schema changes and repeatable migrations.
  + Provides a consistent and structured approach to applying database schema changes.
  + Supports various relational databases, including Microsoft SQL Server, PostgreSQL, MySQL, SQLite, Oracle, and Firebird.
  + Provides a CLI for executing migrations and integrating with build and deployment workflows.
  + Offers a flexible and extensible architecture for customizing and extending the library.

Availability: Open-source

Website: https://github.com/fluentmigrator/fluentmigrator

5- Evolve:  Database migration tool for .NET and .NET Core projects. Inspired by Flyway.
Database Support: Supports Microsoft SQL Server, PostgreSQL, MySQL, SQLite, MariaDB, Cassandra and CockroachDB.
Key features:
  + Simplifies the process of applying database schema changes over time.
  + Uses a YAML or JSON file format to define migrations.
  + Enables versioning and management of database schema changes in a structured and repeatable manner.
  + Supports various relational databases, including Microsoft SQL Server, PostgreSQL, MySQL and Oracle.
  + Provides a CLI for executing migrations and integrating with build and deployment workflows.
  + Integrates with popular build and deployment tools like Jenkins and Octopus Deploy.
  + Provides an extensible architecture for customizing and extending the tool's functionality.

Availability: Open-source

Website: https://evolve-db.netlify.app

6- NoSQL database migration tools:
  + MongoDB Database Migration Tool: It's a command-line tool for migrating data to and between MongoDB instances.
  (https://docs.mongodb.com/database-tools/mongomirror)
  + Amazon DynamoDB Data Pipeline: Amazon DynamoDB Data Pipeline is a web service for migrating data to Amazon DynamoDB and other AWS services.
  (https://aws.amazon.com/datapipeline/)
  + Cassandra Migrator: a command-line tool that allows users to migrate data from Apache Cassandra to other databases or vice versa.
  (https://github.com/pcmanus/ccm/blob/master/doc/migrator.md)
  + Redis Migrate Tool:  tool for migrating data between Redis instances, with support for different data structures and background migrations.
  (https://redis.io/topics/migration)
  
