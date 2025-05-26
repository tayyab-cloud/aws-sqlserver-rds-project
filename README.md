# Provisioning and Managing SQL Server Databases Using Amazon RDS

This project demonstrates how to provision, configure, and manage a SQL Server database on AWS using Amazon RDS.

## 🔧 Features

- SQL Server deployment on AWS RDS
- Configuration of VPC, Subnets, Security Groups
- Manual creation of tables using `sqlcmd`
- Data insertion and retrieval using SQL scripts
- High availability and automated backups

## 📁 Project Structure

- `create_table.sql` – Script to create a Students table
- `insert_data.sql` – Script to insert demo data
- `select_data.sql` – Script to retrieve data
- `steps.md` – Manual steps performed in AWS Console
- `connection-info.txt` – RDS endpoint & credentials (no passwords)

## 💡 Learning Outcome

Learned how to use Amazon RDS to manage SQL Server databases including:
- Connecting remotely from EC2/Linux terminal
- Using `sqlcmd` utility
- Managing access via security groups and ports
