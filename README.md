# AWS QuickSight + DynamoDB Analytics

## 📌 Project Overview
This project demonstrates how to visualize NoSQL data stored in AWS DynamoDB using Amazon QuickSight, AWS Athena, and a Lambda Connector.

## 🛠️ Tech Stack
- **AWS DynamoDB**: NoSQL database to store task data.
- **AWS Lambda**: Used to connect Athena and DynamoDB.
- **AWS Athena**: Query DynamoDB data using SQL.
- **AWS Glue**: Manages metadata and schema for Athena.
- **Amazon S3**: Stores Athena query results.
- **AWS IAM**: Manages permissions for QuickSight.

## 📊 Key Features
✅ Set up DynamoDB table and populate it with JSON data.  
✅ Use AWS Lambda as a connector between Athena and DynamoDB.  
✅ Configure AWS Glue for schema definition.  
✅ Query DynamoDB data using Athena.  
✅ Visualize data in QuickSight (Bar charts, Donut charts, Tables).  
✅ Secure resource access with IAM roles & policies.  

## 🔥 Architecture Diagram
(Insert an image or link to your architecture diagram)

## 📝 Step-by-Step Guide
1. **Create a DynamoDB Table**
   - Define Partition Key and Sort Key.
   - Insert sample JSON records.

2. **Connect Athena to DynamoDB**
   - Use AWS Glue to define schema.
   - Create an S3 bucket for Athena results.
   - Configure Athena Lambda Connector.

3. **Set Up QuickSight**
   - Grant IAM permissions.
   - Create a dataset pulling from Athena.
   - Build interactive charts.

4. **Final Visualization**
   - Create a dashboard with different data visualizations.
   - Refresh data dynamically.

## 🎥 Demo (Optional)
Include screenshots or a Loom/Youtube video link.

## 🗑️ Cleanup
Make sure to delete your AWS resources to avoid charges.

## 📂 Project Structure
