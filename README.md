# Rooznamcha360 - Web-Based Inventory Management-System
<img width="1920" height="1200" alt="Rooznamcha360 - Inventory Management System" src="https://github.com/user-attachments/assets/0ee855a8-a763-4072-a3bc-b7bf26dad484" />
*(Note: Client data shown are for demonstration purposes)*

## 🍰 Project Overview
**Rooznamcha360** is a modern, web-based Inventory and POS solution built for a high-traffic retail business ("Pakistan Sweets"). 

Unlike traditional cloud SaaS applications, this system was engineered to run **On-Premise** on the client's local server using **Docker**. This hybrid approach gives the client the modern interface of a web app with the offline reliability and speed of a local installation.

## 🛠️ Tech Stack & DevOps
* **Framework:** ASP.NET Core (Razor Pages)
* **Database:** MySQL
* **Frontend:** Bootstrap 5 / jQuery
* **Deployment:** **Docker Containers** (Local Client Machine)
* **Server:** Kestrel / Nginx

## 🐳 The Docker Strategy (DevOps)
One of the key technical challenges was deploying a modern web stack on a client's local hardware without complex configuration. 
* **Containerization:** The entire application (App + Database) is containerized.
* **Ease of Install:** The client machine requires only Docker Desktop. No .NET Runtime or MySQL installation is needed on the host OS.
* **Portability:** Updates are delivered by simply pulling a new image tag.

## 🚀 Key Features

### 📊 Smart Financial Dashboard
* **Profit Analysis:** Real-time calculation of *Today's*, *Monthly*, and *Yearly* profit margins.
* **Live Counters:** Instant visibility on Sales, Purchases, and Expense totals for the day.
* **Stock Valuation:** Dynamic calculation of the total asset value sitting in the warehouse.

### 🔔 Inventory Intelligence
* **Threshold Alerts:** Automated "Near Out of Stock" warnings (Yellow alerts) and "Out of Stock" (Red alerts) to prevent lost sales.
* **Quick Actions:** Shortcut buttons for high-frequency tasks like "Create Sale" or "Add Purchase" to speed up counter operations.

### 📝 Operations & Reporting
* **Purchase Management:** Tracks supplier invoices and dues.
* **Sales Invoicing:** Generates fast, formatted receipts for customers.
* **Expenses:** Daily operational expense logging (Utility bills, staff tea, etc.).

## 💡 Why ASP.NET Core?
Migrating from legacy desktop apps to ASP.NET Core allowed for a responsive, browser-based UI that can be accessed from any device on the local network (Tablets/Laptops) without installing software on every device.

---

### 🔒 Project Status
**Private Client Project.**
*This repository serves as a portfolio showcase demonstrating Full Stack Web Development and Docker deployment skills. Source code is private.*
