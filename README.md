# CLOUD-DATA-STORAGE-SERVER

## NAME: ABISHA RANI S
## REG NO: 212224040012

## Aim

To create and configure an Amazon Relational Database Service (Amazon RDS) instance as a cloud data storage server, configure the required security settings, connect it to a web application, and perform database operations using the application.

## Algorithm / Steps

1. Create a Security Group for the RDS database.
2. Add an inbound rule to allow MySQL (Port 3306) access from the Web Security Group.
3. Create a DB Subnet Group using two Availability Zones.
4. Launch an Amazon RDS MySQL database instance.
5. Configure the database with the required identifier, username, password, storage, and instance class.
6. Associate the database with the created Security Group and Subnet Group.
7. Wait until the database status becomes **Available**.
8. Copy the RDS endpoint.
9. Open the web application using the provided Web Server IP address.
10. Enter the RDS endpoint, database name, username, and password.
11. Connect the application to the database.
12. Verify the connection by adding, editing, and deleting records in the Address Book application.


## Program

### Security Group Configuration

* Security Group Name: **DB Security Group**
* Inbound Rule: **MySQL/Aurora (3306)**
* Source: **Web Security Group**

### DB Subnet Group

* Name: **DB-Subnet-Group**
* VPC: **Lab VPC**

### Amazon RDS Configuration

* Engine: **MySQL**
* Template: **Dev/Test**
* Availability: **Multi-AZ**
* DB Instance Identifier: **lab-db**
* Username: **main**
* Password: **lab-password**
* Instance Class: **db.t3.micro**
* Storage: **20 GB (General Purpose SSD)**

### Connect the Application

```text
Endpoint : <RDS Endpoint>
Database : lab
Username : main
Password : lab-password
```

After submitting the above details, perform Add, Edit, and Delete operations on the Address Book application.

## Output

<img width="1919" height="887" alt="Screenshot 2026-08-07 135749" src="https://github.com/user-attachments/assets/0419c190-0d1d-4250-a631-0be304d5105f" />
<img width="1919" height="877" alt="Screenshot 2026-08-07 135852" src="https://github.com/user-attachments/assets/3ce77187-de09-4ecb-afe1-f929b661b4dc" />

<img width="1919" height="810" alt="Screenshot 2026-08-07 140114" src="https://github.com/user-attachments/assets/af6bf2ae-af3f-4408-b786-9e5237a1fc72" />

<img width="1919" height="877" alt="Screenshot 2026-08-07 141142" src="https://github.com/user-attachments/assets/b7dda040-cb91-441e-a929-5d76f35bad05" />

<img width="1919" height="940" alt="Screenshot 2026-08-07 144002" src="https://github.com/user-attachments/assets/69e9c0f4-7565-4e7f-866b-d79ab8225960" />

<img width="1919" height="953" alt="Screenshot 2026-08-07 144032" src="https://github.com/user-attachments/assets/a4390d5f-4f3c-451f-a136-0b25b8321ec5" />

<img width="1919" height="948" alt="Screenshot 2026-08-07 144127" src="https://github.com/user-attachments/assets/e41ee2c5-e582-4981-9b7f-5c9edb2a2046" />

<img width="1919" height="946" alt="Screenshot 2026-08-07 144135" src="https://github.com/user-attachments/assets/212da7f9-4c85-41d2-b818-0d0cea605767" />

<img width="1919" height="874" alt="Screenshot 2026-08-07 144257" src="https://github.com/user-attachments/assets/214677e9-c0cc-4308-b9d3-b7f334ccd30d" />

## Result

Thus, an Amazon RDS database instance was successfully created and configured as a cloud data storage server. The database was securely connected to a web application, and data operations such as inserting, updating, and deleting records were successfully performed through the application.

