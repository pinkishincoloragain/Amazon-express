A company has deployed an e-commerce web application in a new AWS account. An Amazon RDS for MySQL Multi-AZ DB instance is part of this deployment with a database-1.xxxxxxxxxxxx.us-east- 1.rds.amazonaws.com endpoint listening on port 3306. **The company’s Database Specialist is able to log in to MySQL and run queries from the bastion host using these details**.
  
When users try to utilize the application hosted in the AWS account, they are presented with a generic error message. The application servers are logging a **“could not connect to server: Connection times out” error message** to **Amazon CloudWatch Logs**.  
  
What is the cause of this error?

1. The user name and password the application is using are incorrect.
2. The security group assigned to the application servers does not have the necessary rules to allow inbound connections from the DB instance.
**3. The security group assigned to the DB instance does not have the necessary rules to allow inbound connections from the application servers.**
4. The user name and password are correct, but the user is not authorized to use the DB instance.

---
- RDS, Multi-AZ DB instance
- DBA can login Mysql server, run query
- Users - cannot connect to server: Connection times out

-> DB instance does not have the necessary rules to allow inbound connections from the application servers.

#multi-az #connection #inbound #timeout
