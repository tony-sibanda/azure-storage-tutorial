# Azure Storage Account Tutorial (High-Level)

This repository provides a high-level, beginner-friendly walkthrough for creating an Azure Storage Account and uploading files using the Azure Portal. It includes step-by-step instructions and helpful screenshots.

---

## 🧾 Prerequisites

- A Microsoft Azure account ([Sign up here](https://azure.microsoft.com/en-us/free))
- A browser and internet connection
- No coding experience required

---

## 🚀 Step-by-Step Tutorial

### 1. Choose Your Azure Account

Sign in and choose an Azure Free or Pay-As-You-Go account.

![Azure Free vs Pay-as-you-go](images/Azure%20Screenshot%201.png)

---

### 2. Go to the Azure Portal Dashboard

This is your home screen in Azure.

![Azure Portal Homepage](images/Azure%20Screenshot%202.png)

---

### 3. Create a Resource Group

Resource groups organize your Azure resources.

1. Click "Resource groups"
2. Click **Create**
3. Choose your subscription and region
4. Enter a name like `Lab-Test-Tony`

![View Resource Groups](images/Azure%20Screenshot%203.png)
![Create a Resource Group](images/Azure%20Screenshot%204.png)
![Enter Name for Resource Group](images/Azure%20Screenshot%205.png)
![Optional Tags](images/Azure%20Screenshot%206.png)
![Review and Create](images/Azure%20Screenshot%207.png)
![Confirmation](images/Azure%20Screenshot%208.png)

---

### 4. Start Creating a Storage Account

From your new resource group, click **Create**, then **Storage Account**.

![Resource Group Overview](images/Azure%20Screenshot%209.png)
![Start Storage Account Creation](images/Azure%20Screenshot%2010.png)

---

### 5. Fill Out the Storage Account Details

- Choose subscription and resource group
- Enter a storage account name (e.g., `tonycoursecareers123`)
- Choose **Locally-redundant storage (LRS)** for replication

![Fill Out Basic Info](images/Azure%20Screenshot%2011.png)
![Review Storage Account Settings](images/Azure%20Screenshot%2012.png)

---

### 6. Create and Deploy

Click **Create** and watch the deployment.

![Deployment in Progress](images/Azure%20Screenshot%2013.png)
![Deployment Complete](images/Azure%20Screenshot%2014.png)

---

### 7. Upload Files to Your Storage Account

1. Go to your storage account
2. Choose **Containers**, then create or use a container
3. Upload a file

![Blob Uploaded](images/Azure%20Screenshot%2020.png)
![View Uploaded File Content](images/Azure%20Screenshot%2021.png)

---

## ✅ You're Done!

You've now successfully:
- Created a resource group
- Created and deployed a storage account
- Uploaded a file into Azure Blob Storage

---

## 📂 Folder Structure

```
azure-storage-tutorial/
├── README.md
└── images/
    ├── Azure Screenshot 1.png
    ├── Azure Screenshot 2.png
    └── ... etc.
```

Feel free to clone this repo, reuse the guide, and continue building your Azure skills!
