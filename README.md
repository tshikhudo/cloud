# ABC Retail Azure Storage Web Application

## 📌 Overview

This project is a cloud-based web application developed for **ABC Retail** to demonstrate the use of **Microsoft Azure Storage Services**.
The system replaces legacy on-premises infrastructure with scalable, reliable, and cost-effective cloud solutions.

---

## 🎯 Objectives

The application demonstrates the following Azure capabilities:

* Store customer profiles using **Azure Table Storage**
* Upload and manage images using **Azure Blob Storage**
* Handle order processing messages using **Azure Queue Storage**
* Store log files using **Azure File Storage**
* Deploy a working web application using **Azure App Service**

---

## 🛠️ Technologies Used

* ASP.NET Core MVC (.NET 8)
* Microsoft Azure Storage Services:

  * Table Storage
  * Blob Storage
  * Queue Storage
  * File Storage
* Visual Studio 2022
* GitHub (Version Control)

---

## ⚙️ Features

### 1. Customer Management (Table Storage)

* Add customer names via web form
* Data stored in Azure Table Storage
* Display list of stored customers

### 2. Image Upload (Blob Storage)

* Upload images from local machine
* Images stored in Azure Blob container

### 3. Queue Messaging (Queue Storage)

* Send messages (e.g., "Processing Order")
* Messages stored in Azure Queue

### 4. File Upload (Azure Files)

* Upload documents/files
* Stored in Azure File Share

---

## 🚀 How to Run Locally

1. Extract the project ZIP
2. Open the project in **Visual Studio**
3. Ensure NuGet packages restore automatically
4. Run the project:

   * Click ▶️ **Run (IIS Express)**

---

## ☁️ Azure Configuration

Ensure your Azure Storage connection string is configured in:

```
StorageController.cs
HomeController.cs
```

---

## 🌐 Deployment

The application is deployed using **Azure App Service**.

Example URL format:

```
http://<your-student-number>.azurewebsites.net
```

---

## 📸 Required Screenshots (For Submission)

Include screenshots of:

* Azure Table Storage (≥ 5 records)
* Azure Blob Storage (≥ 5 images)
* Azure Queue Storage (≥ 5 messages)
* Azure File Storage (≥ 5 files)
* Deployed Web Application (running in browser)

---

## 📂 Project Structure

```
/Controllers
    HomeController.cs
    StorageController.cs

/Views
    /Home
        Index.cshtml

Program.cs
ABCRetailAzureProject.csproj
```

---

## 🧠 Key Benefits

* Scalable cloud storage
* Improved performance vs legacy systems
* Reliable message handling
* Cost-effective infrastructure
* Real-time data interaction

---

## 👨‍💻 Author

Student Number: ST10499815
Module Code: CLDV7112


