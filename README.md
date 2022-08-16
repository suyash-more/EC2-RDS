## **Project**

#### **Problem Statement**
***
Configure and Connect a MySQL Database Instance with a Web Server

#### **Description**
***
You are working as a database administrator for an IT firm. You have been asked to create a new database instance on AWS cloud and connect it with the employee management portal hosted on a web server.

#### **Background of the problem statement:** 
***
Your organization wants to deploy a new multi-tier application. The application will take live inputs from the employees and it will be hosted on a web server running on the AWS cloud. 

The development team has asked you to set up the web server and configure it to scale automatically in cases of a traffic surge, to make the application highly available. They have also asked you to take the inputs from the employees and store them securely in the database


#### **Specifications**
***
Create a Database Instance with the following specifications: 

Database creation method: Standard Create<br>
Engine: MySQL<br>
Database Instance size: db.t2.micro<br>

 

Create an EC2 Instance with the following specifications: 

AMI: Amazon Linux <br>
Region: Use only US East (N Virginia), us-east-1, and us-east-2<br>
Instance types: t2.micro and t3.micro<br>
Allowed EBS types: GP2 and Standard<br>

## Architecture Diagram
### Level 1
***
![alt text](images/EC2-RDS.png)
***
### Can be Upgraded accordingly - Level 2
***
![alt text](images/EC2-RDSMod.png)
***

#### **Writeup**
***
![alt text](images/1.jpg)
***
![alt text](images/2.jpg)
***
![alt text](images/3.jpg)
***
![alt text](images/4.jpg)
***

