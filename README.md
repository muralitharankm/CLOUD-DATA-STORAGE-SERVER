# EX-5 CLOUD DATA STORAGE SERVER
CLOUD DATA STORAGE SERVER
# REG NO : 212223040121
# NAME : MURALITHARAN K M

## AIM

To create and configure an Amazon RDS MySQL DB instance with Multi-AZ deployment, connect it to a web application using a security group and DB subnet group, and perform CRUD (Create, Read, Update, Delete) operations on the database through the application.

## ALGORITHM

1. Log in to the AWS Management Console.
2. Create a DB Security Group allowing MySQL (3306) access from the Web Security Group.
3. Create a DB Subnet Group with subnets in two Availability Zones.
4. Launch an Amazon RDS MySQL Multi-AZ DB instance.
5. Configure the DB instance with the required username, password, and database name. Wait until the database status becomes Available and copy the endpoint.
6. Open the provided web application using the Web Server IP.
7. Enter the RDS endpoint, database name, username, and password.
8. Connect the application to the database.
9. Test the application by adding, editing, viewing, and deleting records.

## OUTPUT

<img width="1880" height="907" alt="image" src="https://github.com/user-attachments/assets/e2085cd7-bba0-4c33-8214-54a1ba5c6303" />
<img width="1886" height="922" alt="image" src="https://github.com/user-attachments/assets/e40dd114-105c-4ec2-8b52-0daa921d49f9" />
<img width="1887" height="925" alt="image" src="https://github.com/user-attachments/assets/9ee07bfc-7141-4fc4-9efb-a3c2bd5a9f3b" />
<img width="1451" height="572" alt="image" src="https://github.com/user-attachments/assets/b13b6156-5e2a-47ce-8ee3-50e19c614ef3" />
<img width="1811" height="880" alt="image" src="https://github.com/user-attachments/assets/0a93c459-03cd-4f72-9bd5-35201bef43d4" />
<img width="1495" height="910" alt="image" src="https://github.com/user-attachments/assets/64991ae3-af3b-4af3-a2e7-8fc6fa3b9adb" />



## RESULT

The Amazon RDS MySQL Multi-AZ DB instance was successfully created and connected to the web application, and CRUD operations were performed successfully on the database.
