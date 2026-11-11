Week 8 Assignment: MySQL Database Backup and RestoreOverviewThis repository contains the solutions for the Week 8 Assignment:
MySQL Database Backup and Restore. 
It covers essential Database Administration (DBA) practices using mysqldump to perform logical database backups for disaster recovery and system migration.
Assignment Tasks & CommandsQuestion 1: Single Database Backup (sales)Command executed to perform a complete backup of the sales database:
mysqldump -u root -p sales > sales_backup.sql
Key Concepts:Exports structure and data of a single target schema.
Essential for routine data protection, disaster recovery, and compliance.Question 2: 
Server-Wide Database Backup (All Databases)Command executed to perform a full backup of all 
databases prior to server migration:mysqldump -u root -p --all-databases > all_databases_backup.
sql
Key Concepts:Exports every database on the host MySQL instance, including system configuration and grant tables.
Critical for complete system migration and seamless account permission restoration.File StructureFileDescriptionanswer.
sqlContains the commands, syntax breakdown, and detailed conceptual answers.
README.mdRepository summary and execution guide.How to RunOpen your terminal or command line interface.
Run the backup commands:mysqldump -u root -p sales > sales_backup.sql
mysqldump -u root -p --all-databases > all_databases_backup.sql
