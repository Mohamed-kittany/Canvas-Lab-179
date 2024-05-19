# Migration to Amazon RDS

## Lab Overview

This lab instructs you on how to migrate the café web application from using a local database instance to a fully managed Amazon Relational Database Service (Amazon RDS) database.

## Steps Involved

### 1. Data Preparation
Begin by generating some initial data on your current database setup.

### 2. Data Migration
Transfer the existing data to the newly configured Amazon RDS instance.

### 3. Infrastructure Setup
Construct the necessary infrastructure components which include:
- Two private subnets across different Availability Zones.
- A security group tailored for the database instance.
- The Amazon RDS DB instance itself.

### 4. Application Reconfiguration
After migrating your database, modify the café application to connect to the Amazon RDS database, replacing the local database instance.

## Conclusion

This lab provides practical experience with Amazon RDS and guides you through the critical steps and considerations needed for a successful database migration.
