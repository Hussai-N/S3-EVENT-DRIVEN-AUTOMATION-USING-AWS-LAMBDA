# S3 Event-Driven Automation using AWS Lambda

## 📌 Project Overview
This project showcases how to automatically trigger a **Lambda function** whenever a file is uploaded to an **S3 bucket**, enabling **event-driven automation** without manual intervention.

---

## ⚙️ Technologies Used
- **Amazon S3** (Storage & Event Source)
- **AWS Lambda** (Serverless Compute)
- **IAM Role** (Permissions)
- **Python** (Lambda Function Code)
- **CloudWatch** (Monitoring Lambda Execution)

---

## 🚀 Process Flow
1. A file is uploaded to an **S3 Bucket**.
2. S3 **Event Notification** triggers the **Lambda function**.
3. Lambda processes the file (e.g., logs the event, extracts metadata, processes data, etc.).
4. **CloudWatch** captures logs of the Lambda execution.

---

## ✨ Key Features
- Fully automated and **event-driven**.
- No servers to manage — purely serverless.
- Real-time file processing.
- Secure through **IAM Role-based access**.
- Easily customizable for different file types and processing needs.

---

## 💡 Example Use Cases
- Real-time **image resizing** when images are uploaded.
- **Metadata extraction** when new files arrive.
- **Log processing** from application dumps.
- **Trigger notifications** on file arrival.

---

## 📂 Example Folder Structure
```bash
📁 Project Folder
├── 📄 lambda_function.py  # Lambda logic
├── 📄 README.md            # This file
