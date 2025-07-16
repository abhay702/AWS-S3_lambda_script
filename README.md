# AWS S3 Lambda Notification Automation

This project automates the creation of AWS resources and sets up a notification workflow using Lambda and SNS. Whenever a new object is uploaded to an S3 bucket, an email notification is triggered automatically.

---

## 🚀 Features

Automatically provisions and configures:

- ✅ IAM role with the necessary permissions
- ✅ S3 bucket for file uploads
- ✅ Lambda function triggered on S3 object creation
- ✅ SNS topic to manage email notifications
- ✅ Email subscription and notification delivery

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python** | Lambda function and scripting logic |
| **Bash** | Automating AWS resource creation |
| **AWS CLI** | AWS infrastructure configuration |
| **boto3** | AWS SDK used within the Lambda function |

---

## ⚙️ Setup

### ✅ Prerequisites

- An active AWS account
- AWS CLI installed and configured (`aws configure`)
- Python 3.8+ and `boto3` installed (preferably in a virtual environment)

### 📦 Clone the Repository

```bash
git clone https://github.com/abhay702/AWS-S3_lambda_script.git
cd AWS-S3_lambda_script

<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/ee410908-054a-4a0e-ba56-8ec76f1eb4d9" />