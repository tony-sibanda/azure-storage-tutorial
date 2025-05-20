# Azure Storage Account Tutorial (High-Level)

This repository provides a high-level, beginner-friendly walkthrough for creating an Azure Storage Account and uploading files using the Azure Portal. It includes step-by-step instructions and helpful screenshots.

---

## 🧾 Prerequisites

- A Microsoft Azure account ([Sign up here](https://azure.microsoft.com/en-us/free))
- A browser and internet connection
- No coding experience required

---

##  Step-by-Step Tutorial

### 1. Choose Your Azure Account

Sign in and choose an Azure Free or Pay-As-You-Go account.
Be sure to use a personal account (Not your school or work account)

<img src="images/Azure%20Screenshot%201.png" alt="Azure Free vs Pay-as-you-go" width="500"/>

---

### 2. Go to the Azure Portal Dashboard

This is your home screen in Azure.

<img src="images/Azure%20Screenshot%202.png" alt="Azure Portal Homepage" width="500"/>

---

### 3. Create a Resource Group

Resource groups organize your Azure resources.

1. Click "Resource groups"
2. Click **Create**
3. Choose your subscription and region
4. Enter a name like `Lab-Test-Tony` or any name that you'd like to use

<img src="images/Azure%20Screenshot%203.png" alt="View Resource Groups" width="500"/>
<img src="images/Azure%20Screenshot%204.png" alt="Create a Resource Group" width="500"/>
<img src="images/Azure%20Screenshot%205.png" alt="Enter Name for Resource Group" width="500"/>
<img src="images/Azure%20Screenshot%206.png" alt="Optional Tags" width="500"/>
<img src="images/Azure%20Screenshot%207.png" alt="Review and Create" width="500"/>
<img src="images/Azure%20Screenshot%208.png" alt="Confirmation" width="500"/>

---

### 4. Start Creating a Storage Account

From your new resource group, click **Create**, then **Storage Account**.

<img src="images/Azure%20Screenshot%209.png" alt="Resource Group Overview" width="500"/>
<img src="images/Azure%20Screenshot%2010.png" alt="Start Storage Account Creation" width="500"/>

---

### 5. Fill Out the Storage Account Details

- Choose subscription and resource group
- Enter a storage account name (e.g., `tonycoursecareers123`)
- Choose **Locally-redundant storage (LRS)** for replication

<img src="images/Azure%20Screenshot%2011.png" alt="Fill Out Basic Info" width="500"/>
<img src="images/Azure%20Screenshot%2012.png" alt="Review Storage Account Settings" width="500"/>

---

### 6. Create and Deploy

Click **Create** and watch the deployment.

<img src="images/Azure%20Screenshot%2013.png" alt="Deployment in Progress" width="500"/>
<img src="images/Azure%20Screenshot%2014.png" alt="Deployment Complete" width="500"/>

---

### 7. Upload Files to Your Storage Account

1. Go to your storage account
2. Choose **Containers**, then create or use a container
3. Upload a file

<img src="images/Azure%20Screenshot%2020.png" alt="Blob Uploaded" width="500"/>
<img src="images/Azure%20Screenshot%2021.png" alt="View Uploaded File Content" width="500"/>

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
