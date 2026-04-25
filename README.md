# 🚀 Automated Employee Onboarding & Offboarding System

## 📌 Overview

This project automates employee onboarding and offboarding processes using ServiceNow.

It dynamically handles request types, validates inputs, manages assets, and stores lifecycle data.

---

## 🎯 Features

* Dynamic form behavior using UI Policies
* Field validation using Client Scripts
* Automated record creation using Flow Designer
* Role-based access control (ACLs)
* Default field population
* Request tracking via Service Catalog

---

## ⚙️ Modules Implemented

### 🧾 Service Catalog

* Onboard New Employee form
* Offboarding handling

### 🎨 UI/UX Enhancements

* Hide/Show fields dynamically
* Mandatory validations

### 🔄 Flow Automation

* Trigger: Service Catalog Request
* Get Catalog Variables
* Create record in `u_employee_lifecycle`
* Approval process

### 🔐 Access Control

* Role-based ACLs for:

  * Read
  * Write
  * Create
  * Delete

---

## 🗂️ Data Handling

* Custom Table: `u_employee_lifecycle`
* Stores:

  * Employee ID
  * Manager
  * Department
  * Joining/Exit Date
  * Assets
  * Access Revocation

---

## 🧪 Testing

* Tested onboarding & offboarding scenarios
* Validated UI policies and client scripts
* Verified flow execution and record creation

---

## 📸 Screenshots

Available in `/docs/screenshots`

---

## 📦 Update Set

Located in `/update-set/employee_onboarding.xml`

---

## 🛠️ Technologies Used

* ServiceNow
* Flow Designer
* Catalog UI Policies
* Client Scripts
* ACL (Access Control Rules)

---

## 👨‍💻 Author

Harindra

---
