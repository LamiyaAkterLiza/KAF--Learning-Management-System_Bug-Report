# KAF--Learning-Management-System_Bug-Report

## 📌 Project Overview

This repository contains comprehensive bug reports for the **KAF Learning Management System (KLMS)**, covering multiple modules including Website, Admin Panel, and Organization Panel.

The purpose of this repository is to track, manage, and resolve system issues efficiently while maintaining clear documentation for QA and development teams.

---

## 🔗 Project Links

* Website: https://kaflms.razinsoft.com/
* Admin Panel: https://kaflms.razinsoft.com/admin
* Organization Panel: https://kaflms.razinsoft.com/admin

---

## 🧩 Modules Covered

### 🌐 Website

Includes user-facing issues such as:

* UI/UX inconsistencies
* Navigation problems
* Course display issues
* Quiz and certificate functionality bugs

### ⚙️ Admin Panel

Includes administrative issues such as:

* Validation errors
* Role & permission issues
* Transaction miscalculations
* System errors (500 / 502)

### 🏢 Organization Panel

Includes organization-specific issues such as:

* Dashboard inconsistencies
* Permission visibility issues
* Registration and verification gaps
* Notification mismatches

---

## 🐞 Bug Summary

### 🔴 Critical Issues

* Payment bypass via receipt upload without validation
* Course marked complete without quiz/exam completion
* Quiz not auto-submitted when timer reaches 0
* Certificate not mapped with course
* Incorrect transaction calculations
* QR code redirect issue

### 🟠 Major Issues

* UI misalignment and layout breaks
* Incorrect labels and titles
* Language selector showing unnecessary options
* Profile and dashboard inconsistencies
* Scrolling issues on instructor page
* Sorting/filtering issues

### 🟡 Minor Issues

* Incorrect button labels
* Text/content mismatches

---

## 📁 Repository Structure


KAF-LMS-Bug-Reports/
│
├── Website/
├── Admin-Panel/
├── Organization-Panel/
├── attachments/
└── README.md


---

## 📎 Attachments

All supporting files (screenshots, videos, documents) are stored in the `/attachments` directory or linked via external sources (e.g., Google Drive).

---

## 🚨 Key Observations

* Lack of proper validation in multiple modules
* Security vulnerability in payment verification
* Inconsistent UI/UX across different panels
* Missing business logic for course completion and certification
* Error handling is not user-friendly in several cases

---

## ✅ Recommendations

* Implement strict validation for forms and inputs
* Fix business logic for course completion and certification
* Add proper error handling and user-friendly messages
* Ensure consistent UI/UX across all modules
* Introduce verification steps in sensitive flows (e.g., payments, registration)

---

## 👤 Reported By

**QA Team**/n
Lamiya – QA Engineer

---

## 📌 Status

* Multiple bugs: Fixed
* Some bugs: Re-test / Pending

---

## 📢 Note

This repository is intended for internal QA tracking and development collaboration. All bugs are documented based on real testing scenarios.

---
