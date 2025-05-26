# Manual Steps Performed on AWS

1. Created an Amazon RDS SQL Server instance named `my-sql-db`
2. Chose instance type `db.t3.micro` (Free Tier)
3. Set master username: `admin`
4. Set VPC and assigned default subnet group
5. Created a new Security Group to allow inbound on port 1433 (SQL Server)
6. Enabled public access for testing (secured via SG)
7. Connected from EC2 instance using `sqlcmd` with the endpoint
8. Ran SQL scripts to create table and manage data
