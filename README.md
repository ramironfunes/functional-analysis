# 📑 Functional Analysis – University Library Management System

This repository showcases a **full functional analysis case study** for a University Library Management System.  
It demonstrates how a Functional Analyst translates business needs into requirements, use cases, user stories, and test cases.

---

## 🎯 Business Context
The University currently manages library operations manually (spreadsheets, paper logs).  
This causes inefficiencies such as:
- Long waiting times
- Inconsistent reporting
- Limited visibility of book availability

The new system provides a **modern, web-based platform** to manage catalog, borrowing, returns, fines, and reporting.

---

## 🏆 Business Objectives
- Reduce checkout time to **< 2 minutes**
- Provide **real-time book availability**
- Automate overdue **fine calculation**
- Deliver **weekly/monthly reports**
- Increase **student satisfaction** > 80% after 6 months

---

## 👥 Stakeholders
- **Students** → Borrow and return books  
- **Librarians** → Manage catalog, oversee loans/fines  
- **IT Department** → Maintain system, integrations  
- **Finance** → Track fines and payments  
- **University Management** → Consume reports for decisions  

---

## 📌 Deliverables Included in This Repo
- **Use Cases Document** (UC-01 to UC-06)  
- **Detailed User Stories** with acceptance criteria & tasks  
- **UAT/QA Test Cases** covering functional flows  
- **Traceability Matrix** mapping Requirements → Use Cases → Stories → Tests  

> These documents illustrate the full **requirements-to-testing workflow** of a Functional Analyst.

---

## 📘 Use Cases (Sample)
- UC-01: Search Books  
- UC-02: Borrow Book  
- UC-03: Return Book  
- UC-04: Pay Fine  
- UC-05: Manage Catalog  
- UC-06: Generate Reports  

---

## 📗 User Stories (Sample)
- *As a Student, I want to search books by title/author, so I can quickly find resources.*  
- *As a Librarian, I want to generate overdue reports, so I can notify students.*  
- *As Management, I want to view monthly borrowing trends, so I can plan acquisitions.*  

---

## 🧪 Test Cases (Sample)
- TC-01: Search Books – valid keyword returns results in < 3s  
- TC-04: Borrow Book – student cannot exceed 3 active loans  
- TC-07: Pay Fine – successful payment updates Finance records  
- TC-12: Reports – system generates 10k+ record report within 10s  

---

## 🔗 Traceability Matrix (Excerpt)

| Requirement          | Use Case(s) | User Story(ies) | Test Case(s) | Status   |
|----------------------|-------------|-----------------|--------------|----------|
| REQ-01: Book Search  | UC-01       | US-01, US-02    | TC-01, TC-02 | Covered  |
| REQ-02: Borrow Books | UC-02       | US-03           | TC-03, TC-04 | Covered  |
| REQ-04: Pay Fines    | UC-04       | US-04           | TC-07, TC-08 | Covered  |

---

## 📂 Repository Structure
