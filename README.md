#  Azure Intro Tutorial: Resource Group, Storage Account, and Blob Upload

This high-level guide walks you through the essential steps to get started with Microsoft Azure, including creating a **Resource Group**, a **Storage Account**, and a **Blob Container**, and uploading a simple file to it.

---

## 🧰 Prerequisites

- A free Microsoft Azure account  
  👉 [Sign up here](https://azure.microsoft.com/en-us/free/)
- A valid credit/debit card (for identity verification only)
- Use a **personal Microsoft account** (not work/school)

---

##  Step 1: Create a Resource Group

1. Go to the [Azure Portal](https://portal.azure.com)
2. In the top search bar, type **"Resource Groups"**
3. Click **Create**
4. Fill in:
   - **Subscription** (select the default or free subscription)
   - **Resource Group Name** (e.g., `my-resource-group`)
   - **Region** (e.g., `East US 2`)
5. Click **Review + Create**, then **Create**

---

##  Step 2: Create a Storage Account

1. In the Azure search bar, type **"Storage Accounts"**
2. Click **Create**
3. Under the **Basics** tab:
   - **Subscription**: your active one
   - **Resource Group**: select the one you just created
   - **Storage account name**: must be globally unique
   - **Region**: same as the Resource Group
4. Leave other settings at default and click **Review + Create**, then **Create**

---

##  Step 3: Create and Upload a File

### On Mac:
- Open **TextEdit**, change format to **Plain Text** (TextEdit > Settings > Format)
- Create a new file with the content:
  ```
  Hello
  ```
- Save it as `Azure-Lab.txt` on your desktop

### On Windows:
- Open **Notepad**
- Type `Hello`
- Save as `Azure-Lab.txt` on your desktop

---

##  Step 4: Create a Blob Container and Upload

1. In Azure Portal, go to your **Storage Account**
2. Under **Data Storage**, click **Containers**
3. Click **+ Container**, give it a name (e.g., `lab-test`), then click **Create**
4. Open the container and click **Upload**
5. Upload the `Azure-Lab.txt` file you created

---

##  Step 5: Edit and Verify the File

1. Inside the container, click on your uploaded file
2. Choose **Edit**, replace "Hello" with "Goodbye"
3. Save the changes
4. Download the file to your desktop to confirm the updated content

---

##  You're Done!

You’ve created a full storage workflow in Azure:
- ✔ Resource Group
- ✔ Storage Account
- ✔ Container
- ✔ Uploaded and edited a blob

---

## 📎 Optional Next Steps

- Explore access tiers and redundancy options in Storage Account settings
- Try connecting with Azure CLI or Storage Explorer for more advanced workflows

---

*Created as part of an introductory Azure learning project.*
