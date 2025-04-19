---

## 📃 License

This project is for academic and demonstration purposes.

---

# Concerts and Conferences Management System (CCMS)

## 📌 Introduction

The Concerts and Conferences Management System (CCMS) is a comprehensive solution for organizing and coordinating events such as concerts, conferences, and parties. It provides a centralized platform to manage coordinators, clients, institutions, parties, and contracts. The goal is to enhance event planning efficiency, improve coordination, and ensure seamless execution.

## 🎯 Motivation

In today's fast-paced world, events are crucial for communication, networking, and creating memorable experiences. However, managing them is complex. CCMS was built to simplify these processes by:
- Centralizing event information
- Managing multi-role relationships
- Reducing manual efforts
- Offering a user-friendly interface

---

## 🧭 Mission

To provide a robust and secure database system that centralizes all key event management operations while maintaining accuracy, efficiency, and scalability.

### ✅ Objectives:
- Centralized Data Management
- User-friendly Interface
- Strong Relationship Management
- Automation and Efficiency
- Scalable Architecture
- Data Security & Authorization
- Real-time Reporting
- Easy Integration with external tools

---

## 📦 System Scope & Features

### 🔹 Modules Included:
- **Coordinator Management**
- **Party Management**
- **Contract Management**
- **Institution Management**
- **Client Management**
- **Relational Mapping Between Entities**

### 🔹 User Views:
- **Coordinator View**
- **Client View**
- **Institution View**
- **Admin View**

Cross-referencing allows smooth collaboration across all views.

---

## 🔍 Requirements

### 👥 Stakeholders:
- Coordinators
- Clients
- Institutions
- System Administrators

### 🧩 Functional Requirements:
- Coordinators can manage profiles, parties, and contracts.
- Clients can track events and view contract details.
- Institutions can manage contracts and information.
- Admins can configure system settings and user access.

### ⚙️ Non-Functional Requirements:
- Usability across roles
- Fast performance
- Scalable architecture
- Secure access and authorization
- Reliable system availability

---

## 📐 System Design

### 🔸 Conceptual Design:
- ER Diagram connecting Coordinators, Parties, Contracts, Institutions, and Customers with clear cardinalities.

### 🔸 Logical Design:
Schema includes:
- `Coordinator`
- `Party`
- `Contract`
- `Institution`
- `Customer`
- `PartyCustomer` (relationship table)

### 🔸 Physical Design:
- Implemented using SQL statements (see `/sql` folder or documentation for full script)
- Includes table creation and insertion of sample data

---

## 🗃️ DBMS Selection

A relational database management system (RDBMS) was chosen due to the structured nature of the data. Recommended DBMS options:
- PostgreSQL
- MySQL
- SQL Server
- Cloud: Google Cloud SQL / Amazon RDS

Factors:
- Scalability
- Performance
- Security
- Support for relational integrity

---

## 📊 Sample Queries

- View all parties and their coordinators
- Retrieve all contracts with linked institutions
- Access customer-parties associations

---

## 🧪 Prototyping & Testing

Interactive prototypes were developed and improved with stakeholder feedback. The final system was designed with a focus on usability, clarity, and robustness.

---

## 👤 Developed by

**Mawdah Fahad M. Albalawi**  
Graduate of Information Technology, University of Tabuk  

---


