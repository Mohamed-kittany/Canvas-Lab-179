# Migration to Amazon RDS

## Lab Overview

This lab instructs you on how to migrate the café web application from using a local database instance to a fully managed Amazon Relational Database Service (Amazon RDS) database.

### Starting architecture

<img width="408" alt="StartingArchitecture" src="https://github.com/Mohamed-kittany/Canvas-Lab-179/assets/161580792/7fe37445-7e04-4d63-9b09-76f3e8effa7b">

### Final architecture

<img width="758" alt="FinalArchitecture" src="https://github.com/Mohamed-kittany/Canvas-Lab-179/assets/161580792/a34fbc51-95b0-4ed4-933f-feca81a72da8">

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
