# AWS Database Project - MySQL on EC2

## Project Overview
This project demonstrates the installation and configuration of MySQL on an AWS EC2 instance running Ubuntu 24.04 LTS, along with basic SQL database operations.

## Architecture
- EC2 instance running Ubuntu 24.04 LTS
- MySQL Server installed via APT package manager
- Security Group allowing SSH, HTTP, HTTPS and SMTP traffic

## Steps Completed

### 1. EC2 Setup
Launched an EC2 instance using Ubuntu 24.04 LTS on a t3.micro free tier instance in the eu-west-3 (Paris) region.

### 2. MySQL Installation
Installed MySQL Server using the APT package manager and verified it was running using systemctl.

### 3. Database Creation
Created a database called coffee_shop containing three tables.

### 4. Tables Created
- coffee_table : stores coffee products with id, name, region and roast columns
- customer_name : stores customer information with id, first_name, last_name and email columns
- customer_order : stores orders with order_id, customer_id, coffee_id and quantity columns

### 5. Data Insertion
Inserted data into all three tables using SQL INSERT statements.

### 6. Data Types Used
- INT : for whole numbers like IDs and quantities
- VARCHAR(255) : for text like names and emails

## Screenshots
All screenshots are available in the screenshots folder.

## Technologies Used
- AWS EC2
- Ubuntu 24.04 LTS
- MySQL
- SQL
