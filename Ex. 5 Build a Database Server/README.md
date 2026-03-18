# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: Vasanth P
* **Register Number**: 212224230295
* **Date of Submission**: 18-03-2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

1. Logged in to AWS Management Console and opened Amazon EC2.
2. Launched a new EC2 instance using Amazon Linux 2 AMI and selected an appropriate instance type.
3. Created/selected a key pair and configured a security group for the instance.
4. Modified the security group to allow SSH (Port 22) and database access (3306 for MySQL or 5432 for PostgreSQL).
5. Connected to the EC2 instance using an SSH client such as PuTTY or terminal.
6. 6.Installed the database server (e.g., MySQL, MariaDB, or PostgreSQL) using Linux package manager commands.
7. Started the database service and configured basic settings such as the root password and user privileges.
8. Created a sample database and table and inserted a few records.
9. Tested database connectivity by running basic SQL queries.


---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1320" height="681" alt="image" src="https://github.com/user-attachments/assets/81e2c935-09d2-487a-9f83-b3fb3c31bc20" />

<img width="1316" height="677" alt="image" src="https://github.com/user-attachments/assets/68fe3ef2-2b4f-4c1c-95aa-2e4dd2b16f44" />

---

### Screenshot 2: Database Service Running

<img width="1326" height="680" alt="image" src="https://github.com/user-attachments/assets/75bfe9d4-fffa-47b4-865e-99ce8ad5daaa" />
<img width="1318" height="772" alt="image" src="https://github.com/user-attachments/assets/290f83bc-f9ad-437a-8306-ca2c9a98529d" />



---

### Screenshot 3: Sample Database and Table

(Insert Screenshot Here)<img width="1308" height="767" alt="image" src="https://github.com/user-attachments/assets/0a5043ea-d354-43f1-bf4b-0b269ee86377" />


---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
