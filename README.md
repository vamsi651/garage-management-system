# 🚗 Garage Management System - Salesforce CRM Project

### 🔧 Developed by: Rayachoti Vamsi (22HM1A05A5)  
📧 vamsirayachoti604@gmail.com  
🏫 Annamacharya Institute of Technology and Sciences, Kadapa

---

## 📌 Project Overview

The **Garage Management System (GMS)** is a fully integrated CRM solution built on Salesforce Lightning, tailored for automotive repair and maintenance facilities. The system digitizes customer interaction, appointment scheduling, service records, billing, and inventory tracking — all within a unified interface to enhance operational efficiency and customer satisfaction.

---

## 🎯 Objectives

- **Improve Customer Experience**: Enable quick, self-service appointment booking.
- **Streamline Operations**: Automate work order assignments, billing updates, and inventory tracking.
- **Enable Data-Driven Decisions**: Real-time reports & dashboards for managers.
- **Ensure Compliance**: Maintain accurate logs and validation rules for audit readiness.

---

## 🚀 Key Features

| Feature | Description |
|--------|-------------|
| **Customer & Vehicle Management** | Centralized record keeping of all customer and vehicle information. |
| **Service Appointment Booking** | Self-service booking with validation and technician auto-assignment. |
| **Dynamic Service Pricing (Apex)** | Automatically calculates billing based on selected service types. |
| **Automated Email Notifications (Flow)** | Sends confirmation emails once payments are marked complete. |
| **Billing & Feedback Collection** | Automated payment tracking and rating system for services. |
| **Reports & Dashboards** | Real-time insights into services, ratings, revenue, and stock levels. |

---

## ⚙️ Salesforce Components Used

- **Custom Objects**:  
  - `Customer_Details__c`, `Appointment__c`, `Service_Records__c`, `Billing_Details_and_Feedback__c`, `Inventory__c`

- **Automation**:  
  - Record-Triggered **Flows** (Email Notifications, Status Updates)  
  - **Apex Trigger** & Class: `AmountDistributionHandler` for dynamic pricing logic

- **Validation & Duplicate Rules**:  
  - Enforced regex formats (e.g., Vehicle Number Plates)  
  - Prevented duplicate entries using Matching Rules

- **Role Hierarchy**:  
  - Admin → Service Manager → Technician (Controlled record access and approval levels)

---

## 🧩 Functional Modules

### 📅 Work Order Management
- Appointments tied to Service Records
- Quality Checks and automated status updates

### 👨‍🔧 Technician Automation
- Auto-assignment using Flows
- Permissions restricted via Role Hierarchy

### 💳 Billing & Rating System
- Auto-fills payment based on services
- Customer rates the service (1–5 scale)

### 📈 Reports & Dashboards
- "New Service Information" report
- "Customer Review" Dashboard with real-time analytics

---

## 🌐 App Setup

- Salesforce Lightning App: **Garage Management Application**
- All custom objects, Flows, Apex Classes, Reports, and Dashboards are organized under one app interface for simplified navigation and administration.

---

## ✅ Conclusion

This project demonstrates how Salesforce can revolutionize traditional garage operations by replacing manual workflows with automated, user-friendly CRM features. The **Garage Management System** serves as a scalable, maintainable, and intuitive platform that enhances both technician productivity and customer experience.

---

## 📎 Useful Links

- 🔗 [Create Salesforce Developer Org](https://developer.salesforce.com/signup)
---

> 📁 Clone this repo and customize for your own domain or business needs!
