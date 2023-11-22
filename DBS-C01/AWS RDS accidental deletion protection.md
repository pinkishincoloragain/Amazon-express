An AWS CloudFormation stack that included an Amazon RDS DB instance was **accidentally deleted and recent data was lost**. A Database Specialist needs to **add RDS settings** to the CloudFormation template to **reduce the chance of accidental instance data loss in the future**.

- **Set DeletionProtection to true**
- Set MultiAZ to True
- Set TerminationProtection to True
- **Set DeleteAutomatedBackups to False**
- Set DeletionPolicy to Delete
- **Set DeletionPolicy to Retain**
